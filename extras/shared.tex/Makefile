all: compile_latex clean

.PHONY: all clean install_latex install

current:
	$(eval FILE := A1.teorica_____lenguaje.cpp)
	pdflatex -shell-escape $(FILE).tex
	pdflatex -shell-escape $(FILE).tex
	open $(FILE).pdf

bibliografia:
	@echo "Compiling LaTeX files..."
	pdflatex --shell-escape bibliografia
	bibtex bibliografia
	pdflatex --shell-escape bibliografia
	pdflatex --shell-escape bibliografia

compile_latex: bibliografia
	@for file in *.tex; \
		do \
			pdflatex -shell-escape $$file; \
			biber $$(basename $$file .tex); \
			pdflatex -shell-escape $$file; \
		done;

clean:
	@echo "Cleaning up LaTeX intermediate files..."
	@for extension in aux bbl bcf blg blx.bib fdb_latexmk fls lof log lol lot out pyg run.xml synctex.gz toc acn glo ist glsdefs acr alg glg gls; \
		do \
			find . -type f -name "*.$$extension" -delete; \
		done;

clean-all: clean
	@echo "Cleaning up PDF files..."
	@find . -type f -name "*.pdf" -delete

install_latex: # Only for OSX
	brew install --cask mactex
	brew install --cask texworks
	brew install pygments

install: install_latex # Only for OSX
	@echo "Installing OS packages for LaTeX..."
	sudo tlmgr update --self

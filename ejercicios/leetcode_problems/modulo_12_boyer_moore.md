# Módulo 12: Algoritmo Boyer-Moore

## Temas cubiertos
- El algoritmo de Boyer-Moore
- Resolución de casos de situaciones reales
- Pattern matching eficiente
- Heurísticas: bad character y good suffix
- Algoritmos de búsqueda de strings optimizados

## Ejercicios (Easy → Medium → Hard)

### 1. Implement strStr()
- **Dificultad**: Easy
- **Link**: [LeetCode #28](https://leetcode.com/problems/implement-strstr/)
- **Conceptos**: Implementar con Boyer-Moore, comparación con KMP

### 2. Reverse String
- **Dificultad**: Easy
- **Link**: [LeetCode #344](https://leetcode.com/problems/reverse-string/)
- **Conceptos**: Manipulación de strings, base para algoritmos de búsqueda

### 3. Reverse Words in a String III
- **Dificultad**: Easy
- **Link**: [LeetCode #557](https://leetcode.com/problems/reverse-words-in-a-string-iii/)
- **Conceptos**: Procesamiento de strings por palabras

### 4. Valid Anagram
- **Dificultad**: Easy
- **Link**: [LeetCode #242](https://leetcode.com/problems/valid-anagram/)
- **Conceptos**: Frecuencia de caracteres, base para pattern matching

### 5. Repeated Substring Pattern
- **Dificultad**: Easy
- **Link**: [LeetCode #459](https://leetcode.com/problems/repeated-substring-pattern/)
- **Conceptos**: Detección de patrones, aplicación de búsqueda

### 6. Longest Happy Prefix
- **Dificultad**: Hard
- **Link**: [LeetCode #1392](https://leetcode.com/problems/longest-happy-prefix/)
- **Conceptos**: KMP failure function, similar a Boyer-Moore preprocessing

### 7. Ransom Note
- **Dificultad**: Easy
- **Link**: [LeetCode #383](https://leetcode.com/problems/ransom-note/)
- **Conceptos**: Matching de caracteres, análisis de disponibilidad

### 8. Shortest Palindrome
- **Dificultad**: Hard
- **Link**: [LeetCode #214](https://leetcode.com/problems/shortest-palindrome/)
- **Conceptos**: KMP, técnicas similares a Boyer-Moore

### 9. Rotate String
- **Dificultad**: Easy
- **Link**: [LeetCode #796](https://leetcode.com/problems/rotate-string/)
- **Conceptos**: String matching, búsqueda en rotaciones

### 10. Reverse Words in a String
- **Dificultad**: Medium
- **Link**: [LeetCode #151](https://leetcode.com/problems/reverse-words-in-a-string/)
- **Conceptos**: Procesamiento de strings, múltiples búsquedas

### 11. Implement Trie (Prefix Tree)
- **Dificultad**: Medium
- **Link**: [LeetCode #208](https://leetcode.com/problems/implement-trie-prefix-tree/)
- **Conceptos**: Estructura alternativa para búsqueda de strings

### 12. Design Add and Search Words Data Structure
- **Dificultad**: Medium
- **Link**: [LeetCode #211](https://leetcode.com/problems/design-add-and-search-words-data-structure/)
- **Conceptos**: Trie con wildcards, búsqueda flexible

### 13. Palindrome Pairs
- **Dificultad**: Hard
- **Link**: [LeetCode #336](https://leetcode.com/problems/palindrome-pairs/)
- **Conceptos**: Trie, búsqueda bidireccional de patterns

### 14. Shortest Superstring Problem
- **Dificultad**: Hard
- **Link**: [LeetCode #943](https://leetcode.com/problems/find-the-shortest-superstring/)
- **Conceptos**: Overlap detection, construcción óptima de superstring

### 15. Repeated DNA Sequences
- **Dificultad**: Medium
- **Link**: [LeetCode #187](https://leetcode.com/problems/repeated-dna-sequences/)
- **Conceptos**: Rolling hash, detección de patrones repetidos

### 16. Find Pattern in Infinite Stream
- **Dificultad**: Hard
- **Link**: [LeetCode #1032](https://leetcode.com/problems/stream-of-characters/)
- **Conceptos**: Stream processing, Aho-Corasick (generalización de Boyer-Moore)

### 17. Longest Word in Dictionary through Deleting
- **Dificultad**: Medium
- **Link**: [LeetCode #524](https://leetcode.com/problems/longest-word-in-dictionary-through-deleting/)
- **Conceptos**: Subsequence matching, búsqueda en diccionario

### 18. Prefix and Suffix Search
- **Dificultad**: Hard
- **Link**: [LeetCode #745](https://leetcode.com/problems/prefix-and-suffix-search/)
- **Conceptos**: Preprocessing similar a Boyer-Moore, búsqueda bidireccional

### 19. Shortest Way to Form String
- **Dificultad**: Medium
- **Link**: [LeetCode #1055](https://leetcode.com/problems/shortest-way-to-form-string/) (Premium)
- **Conceptos**: Pattern matching repetido
- **Alternativa**: [LeetCode #392](https://leetcode.com/problems/is-subsequence/)

### 20. Minimum Window Subsequence
- **Dificultad**: Hard
- **Link**: [LeetCode #727](https://leetcode.com/problems/minimum-window-subsequence/) (Premium)
- **Conceptos**: Búsqueda de ventana mínima con subsecuencia
- **Alternativa**: [LeetCode #76](https://leetcode.com/problems/minimum-window-substring/)

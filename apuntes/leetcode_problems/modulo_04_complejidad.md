# Módulo 4: Complejidad de Algoritmos

## Temas cubiertos
- Cálculo de métricas
- Algoritmos generalizados
- Análisis de los algoritmos
- Bajo promedio, peor caso, mejor caso
- Definición formal de la notación asintótica
- Determinar la complejidad asintótica experimentalmente

## Ejercicios (Easy → Medium → Hard)

### 1. Reverse String
- **Dificultad**: Easy
- **Link**: [LeetCode #344](https://leetcode.com/problems/reverse-string/)
- **Conceptos**: Two pointers, análisis mejor/peor caso O(n), espacio O(1)

### 2. Reverse Integer
- **Dificultad**: Medium
- **Link**: [LeetCode #7](https://leetcode.com/problems/reverse-integer/)
- **Conceptos**: Math, análisis de complejidad O(log n) en dígitos

### 3. Palindrome Number
- **Dificultad**: Easy
- **Link**: [LeetCode #9](https://leetcode.com/problems/palindrome-number/)
- **Conceptos**: Math, análisis sin conversión a string

### 4. Happy Number
- **Dificultad**: Easy
- **Link**: [LeetCode #202](https://leetcode.com/problems/happy-number/)
- **Conceptos**: Hash table, detección de ciclos, análisis de peor caso

### 5. Single Number
- **Dificultad**: Easy
- **Link**: [LeetCode #136](https://leetcode.com/problems/single-number/)
- **Conceptos**: Bit manipulation, O(n) tiempo, O(1) espacio

### 6. Find the Duplicate Number
- **Dificultad**: Medium
- **Link**: [LeetCode #287](https://leetcode.com/problems/find-the-duplicate-number/)
- **Conceptos**: Floyd's cycle detection, análisis O(n) sin modificar array

### 7. Set Matrix Zeroes
- **Dificultad**: Medium
- **Link**: [LeetCode #73](https://leetcode.com/problems/set-matrix-zeroes/)
- **Conceptos**: Matrix, análisis in-place O(1) espacio vs O(m+n)

### 8. Merge Intervals
- **Dificultad**: Medium
- **Link**: [LeetCode #56](https://leetcode.com/problems/merge-intervals/)
- **Conceptos**: Sorting, análisis O(n log n), mejor caso vs peor caso

### 9. Insert Interval
- **Dificultad**: Medium
- **Link**: [LeetCode #57](https://leetcode.com/problems/insert-interval/)
- **Conceptos**: Arrays, análisis mejor caso O(log n), peor caso O(n)

### 10. Minimum Size Subarray Sum
- **Dificultad**: Medium
- **Link**: [LeetCode #209](https://leetcode.com/problems/minimum-size-subarray-sum/)
- **Conceptos**: Sliding window, análisis O(n) vs O(n log n), mejor vs peor caso

### 11. Jump Game
- **Dificultad**: Medium
- **Link**: [LeetCode #55](https://leetcode.com/problems/jump-game/)
- **Conceptos**: Greedy, análisis mejor caso vs peor caso O(n)

### 12. Rotate Array
- **Dificultad**: Medium
- **Link**: [LeetCode #189](https://leetcode.com/problems/rotate-array/)
- **Conceptos**: Arrays, comparación de 3 métodos, O(1) espacio

### 13. Next Permutation
- **Dificultad**: Medium
- **Link**: [LeetCode #31](https://leetcode.com/problems/next-permutation/)
- **Conceptos**: Arrays, análisis in-place O(n)

### 14. Find First and Last Position in Sorted Array
- **Dificultad**: Medium
- **Link**: [LeetCode #34](https://leetcode.com/problems/find-first-and-last-position-of-element-in-sorted-array/)
- **Conceptos**: Binary search, análisis O(log n) en todos los casos

### 15. Valid Sudoku
- **Dificultad**: Medium
- **Link**: [LeetCode #36](https://leetcode.com/problems/valid-sudoku/)
- **Conceptos**: Hash table, análisis O(1) constante (9x9 fijo)

### 16. Spiral Matrix
- **Dificultad**: Medium
- **Link**: [LeetCode #54](https://leetcode.com/problems/spiral-matrix/)
- **Conceptos**: Matrix traversal, análisis O(m×n) estricto

### 17. Game of Life
- **Dificultad**: Medium
- **Link**: [LeetCode #289](https://leetcode.com/problems/game-of-life/)
- **Conceptos**: Matrix, análisis in-place vs extra space

### 18. Largest Rectangle in Histogram
- **Dificultad**: Hard
- **Link**: [LeetCode #84](https://leetcode.com/problems/largest-rectangle-in-histogram/)
- **Conceptos**: Stack, análisis O(n) vs O(n²), mejor y peor caso

### 19. Longest Increasing Path in a Matrix
- **Dificultad**: Hard
- **Link**: [LeetCode #329](https://leetcode.com/problems/longest-increasing-path-in-a-matrix/)
- **Conceptos**: DFS + memoization, análisis O(m×n) con poda

### 20. Max Sum of Rectangle No Larger Than K
- **Dificultad**: Hard
- **Link**: [LeetCode #363](https://leetcode.com/problems/max-sum-of-rectangle-no-larger-than-k/)
- **Conceptos**: Prefix sum + binary search, análisis O(m²n log n)

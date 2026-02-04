# Módulo 5: Recurrencias Homogéneas

## Temas cubiertos
- Resolución de recurrencias
- Recurrencias homogéneas
- Método iterativo de Jacoby
- Método iterativo de Gauss-Seidel
- Polinomio interpolador de Lagrange
- Acotación del error
- Polinomio interpolador en la forma de Newton

## Ejercicios (Easy → Medium → Hard)

### 1. Fibonacci Number
- **Dificultad**: Easy
- **Link**: [LeetCode #509](https://leetcode.com/problems/fibonacci-number/)
- **Conceptos**: Recurrencia lineal homogénea, F(n) = F(n-1) + F(n-2)

### 2. Climbing Stairs
- **Dificultad**: Easy
- **Link**: [LeetCode #70](https://leetcode.com/problems/climbing-stairs/)
- **Conceptos**: Recurrencia tipo Fibonacci, análisis de la ecuación característica

### 3. N-th Tribonacci Number
- **Dificultad**: Easy
- **Link**: [LeetCode #1137](https://leetcode.com/problems/n-th-tribonacci-number/)
- **Conceptos**: Recurrencia lineal homogénea de orden 3

### 4. Min Cost Climbing Stairs
- **Dificultad**: Easy
- **Link**: [LeetCode #746](https://leetcode.com/problems/min-cost-climbing-stairs/)
- **Conceptos**: Recurrencia con optimización, relación de recurrencia

### 5. House Robber
- **Dificultad**: Medium
- **Link**: [LeetCode #198](https://leetcode.com/problems/house-robber/)
- **Conceptos**: Recurrencia lineal, dp[i] = max(dp[i-1], dp[i-2] + nums[i])

### 6. Delete and Earn
- **Dificultad**: Medium
- **Link**: [LeetCode #740](https://leetcode.com/problems/delete-and-earn/)
- **Conceptos**: Recurrencia similar a House Robber

### 7. Decode Ways
- **Dificultad**: Medium
- **Link**: [LeetCode #91](https://leetcode.com/problems/decode-ways/)
- **Conceptos**: Recurrencia lineal homogénea con condiciones

### 8. Unique Paths
- **Dificultad**: Medium
- **Link**: [LeetCode #62](https://leetcode.com/problems/unique-paths/)
- **Conceptos**: Recurrencia bidimensional, dp[i][j] = dp[i-1][j] + dp[i][j-1]

### 9. Unique Binary Search Trees
- **Dificultad**: Medium
- **Link**: [LeetCode #96](https://leetcode.com/problems/unique-binary-search-trees/)
- **Conceptos**: Números de Catalan, recurrencia homogénea

### 10. Integer Break
- **Dificultad**: Medium
- **Link**: [LeetCode #343](https://leetcode.com/problems/integer-break/)
- **Conceptos**: Recurrencia para maximización, análisis matemático

### 11. Perfect Squares
- **Dificultad**: Medium
- **Link**: [LeetCode #279](https://leetcode.com/problems/perfect-squares/)
- **Conceptos**: Recurrencia con sumas de cuadrados

### 12. Coin Change 2
- **Dificultad**: Medium
- **Link**: [LeetCode #518](https://leetcode.com/problems/coin-change-2/)
- **Conceptos**: Recurrencia de conteo de combinaciones

### 13. Number of Ways to Stay in Same Place After Some Steps
- **Dificultad**: Hard
- **Link**: [LeetCode #1269](https://leetcode.com/problems/number-of-ways-to-stay-in-the-same-place-after-some-steps/)
- **Conceptos**: Recurrencia 2D compleja, optimización espacial

### 14. Knight Dialer
- **Dificultad**: Medium
- **Link**: [LeetCode #935](https://leetcode.com/problems/knight-dialer/)
- **Conceptos**: Recurrencia con matriz de transición

### 15. Domino and Tromino Tiling
- **Dificultad**: Medium
- **Link**: [LeetCode #790](https://leetcode.com/problems/domino-and-tromino-tiling/)
- **Conceptos**: Recurrencia lineal compleja, orden superior

### 16. Count Sorted Vowel Strings
- **Dificultad**: Medium
- **Link**: [LeetCode #1641](https://leetcode.com/problems/count-sorted-vowel-strings/)
- **Conceptos**: Recurrencia combinatoria

### 17. Count Number of Teams
- **Dificultad**: Medium
- **Link**: [LeetCode #1395](https://leetcode.com/problems/count-number-of-teams/)
- **Conceptos**: Recurrencia con conteo condicional

### 18. Solving Questions With Brainpower
- **Dificultad**: Medium
- **Link**: [LeetCode #2140](https://leetcode.com/problems/solving-questions-with-brainpower/)
- **Conceptos**: Recurrencia con saltos variables

### 19. Count Ways To Build Good Strings
- **Dificultad**: Medium
- **Link**: [LeetCode #2466](https://leetcode.com/problems/count-ways-to-build-good-strings/)
- **Conceptos**: Recurrencia tipo Fibonacci generalizada

### 20. Number of Music Playlists
- **Dificultad**: Hard
- **Link**: [LeetCode #920](https://leetcode.com/problems/number-of-music-playlists/)
- **Conceptos**: Recurrencia 2D compleja, permutaciones con restricciones

# 📑 Documentación impresa completa para ICPC 2025

## 1. Plantillas de código (snippets probados)
- **I/O rápido** en C++ (`ios::sync_with_stdio(false); cin.tie(nullptr);`).
- **Macros útiles** (`#define all(x)`, `#define pb push_back`, etc.).
- **Lectura de casos múltiples** y parseo de input.
- **Estructuras de datos básicas**: stack, queue, deque, priority_queue.
- **Union-Find (DSU)** con path compression y union by rank.
- **Segment Tree** (sum, min/max, lazy propagation).
- **Fenwick Tree (BIT)**.
- **Sparse Table** para RMQ.
- **Hashing de strings** (rolling hash, double hash).
- **Trie** y Aho-Corasick.
- **Suffix Array / Suffix Automaton**.
- **Algoritmos de grafos**:
  - BFS, DFS.
  - Dijkstra, Bellman-Ford, Floyd-Warshall.
  - Kruskal, Prim.
  - Topological sort.
  - SCC (Kosaraju/Tarjan).
  - Bridges y articulation points.
  - Dinic / Edmonds-Karp (max flow).
  - Min-cost max-flow.
- **Programación dinámica**:
  - Knapsack (0/1, bounded, unbounded).
  - LIS (O(n log n)).
  - DP en bitmasks.
  - DP en árboles.
- **Geometría**:
  - Orientación (CCW).
  - Intersección de segmentos.
  - Convex hull (Graham/Andrew).
  - Área de polígono (shoelace).
  - Distancia punto-recta, punto-polígono.
- **Matemáticas**:
  - Criba de Eratóstenes.
  - Factorización rápida.
  - Exponenciación binaria.
  - Inverso modular.
  - nCr mod p (con factoriales precomputados).
  - GCD/LCM extendido.
  - CRT (Teorema Chino del Resto).
  - FFT/NTT para convoluciones.
- **Miscelánea**:
  - Binary search on answer.
  - Ternary search.
  - Algoritmos greedy clásicos.
  - Matching bipartito (Hopcroft-Karp).

---

## 2. Tablas de referencia rápida
- **Complejidades de contenedores STL** (`vector`, `set`, `map`, `unordered_map`, etc.).
- **Funciones de `<algorithm>`** más usadas (`sort`, `binary_search`, `lower_bound`, `upper_bound`, `next_permutation`, `nth_element`).
- **Funciones de `<cmath>`** (`sqrt`, `pow`, `hypot`, `atan2`, `fabs`).
- **Funciones de strings** (`substr`, `find`, `stoi`, `to_string`).
- **Funciones de bits** (`__builtin_popcount`, `__builtin_clz`, `bitset`).
- **Formatos de I/O** (`%lld`, `%.10f`, etc.).
- **Constantes útiles**: `INT_MAX`, `LLONG_MAX`, `DBL_EPSILON`, π, e.
- **Complejidades típicas**: qué tamaño de `n` aguanta O(n), O(n log n), O(n²), etc.

---

## 3. Fórmulas matemáticas y combinatorias
- Sumatorias y progresiones.
- Fórmulas de geometría (área de círculo, triángulo, polígono).
- Identidades combinatorias básicas.
- Probabilidad y expectativa (linealidad).
- Matrices: multiplicación rápida, exponenciación de matrices.

---

## 4. Estrategias de debugging y testing
- Plantilla de **generador de casos aleatorios**.
- Plantilla de **solución lenta/bruta** para validar.
- Macros de debug (`cerr <<`).
- Checklist de errores comunes:
  - Overflow en `int`.
  - Precisión en `double`.
  - Índices fuera de rango.
  - Inicialización de arrays.

---

## 5. Organización del documento
- **Índice al inicio** con secciones claras.
- **Separadores visuales** (colores, títulos grandes).
- **Código compacto** (sin comentarios largos, pero con nombres claros).
- **Lenguaje unificado** (C++17/20 recomendado).

---

## 6. Estrategia de equipo
- **Roles definidos**: quién lee problemas, quién programa, quién busca en el documento.
- **Protocolo de clarifications**: cómo redactarlas y quién las envía.
- **Rotación de teclado**: plan de turnos.
- **Checklist de inicio**: probar I/O, compilar snippets, leer todos los problemas.

---

## 7. Extra: “Mini-cppreference” impreso
Aunque tengas docs offline en la máquina, imprime:
- Tabla de complejidades STL.
- Métodos más usados de `vector`, `set`, `map`, `unordered_map`.
- Algoritmos de `<algorithm>` con ejemplos cortos.
- Funciones matemáticas y de strings más comunes.

---

✅ **En resumen**:  
Tu documento impreso debe ser un **manual de referencia rápida** con:
1. Plantillas de código probadas.  
2. Tablas de complejidad y funciones STL.  
3. Fórmulas matemáticas y geométricas.  
4. Estrategias de debugging.  
5. Organización clara e índice.  
6. Estrategia de equipo.  
7. Mini-cppreference impreso.  

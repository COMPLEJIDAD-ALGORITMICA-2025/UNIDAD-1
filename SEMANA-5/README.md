# 📘 Semana 5 – Grafos: Técnicas de Recorrido y Búsquedas

Este directorio contiene el material correspondiente a la **Semana 5** del curso de **Complejidad Algorítmica**, donde se profundiza en las **técnicas avanzadas de búsqueda en grafos**, incluyendo recorridos informados, variantes de la búsqueda en profundidad y algoritmos para caminos óptimos.

---

## 📌 Contenidos principales

### 🔹 Caminos y recorridos en grafos
- Definición de camino (path) y ciclo.
- Longitud de un camino.
- Caminos Eulerianos y Hamiltonianos.
- Conectividad entre vértices.

### 🔹 Técnicas de búsqueda en grafos
- Repaso de:
  - Búsqueda en profundidad (DFS).
  - Búsqueda en amplitud (BFS).
- Comparación en términos de:
  - Completitud.
  - Optimalidad.
  - Uso de memoria.

---

## 🔍 Búsquedas informadas y avanzadas

### 🔹 Búsqueda por Costo Uniforme (UCS)
- Aplicable a grafos ponderados.
- Selecciona siempre el nodo con **menor costo acumulado**.
- Relación directa con el algoritmo de **Dijkstra**.
- Uso de colas de prioridad.

### 🔹 Algoritmo de Dijkstra
- Implementación usando:
  - Matriz de adyacencia.
  - Lista de adyacencia.
- Cálculo del camino mínimo desde un nodo origen.
- Análisis de complejidad temporal y espacial.

### 🔹 Introducción al algoritmo A*
- Algoritmo de búsqueda informada.
- Uso de la función:
  \[
  f(n) = g(n) + h(n)
  \]
- Optimiza la búsqueda combinando costo real y heurística.
- Aplicaciones en:
  - Planeamiento de rutas.
  - Inteligencia Artificial.
  - Videojuegos y mapas.

---

## 🔁 Búsquedas por profundidad

### 🔹 Búsqueda en Profundidad Limitada (DLS)
- Variante de DFS con un límite máximo de profundidad.
- Evita recorridos infinitos.
- Puede no ser completa ni óptima.

### 🔹 Búsqueda en Profundidad Iterativa (IDS)
- Repite DLS incrementando gradualmente el límite.
- Combina ventajas de DFS y BFS.
- Reduce consumo de memoria y mantiene completitud.

---

## 🧩 Análisis estructural de grafos

### 🔹 k-Cores y degeneración
- Definición de k-Core.
- Eliminación iterativa de vértices con grado menor que k.
- Cálculo de la **degeneración** de un grafo.
- Aplicaciones en análisis de redes y comunidades.

---

## 🧪 Ejercicios y soluciones

- Implementación de:
  - UCS.
  - Dijkstra.
  - DLS.
  - IDS.
  - BFS y DFS (matriz y lista de adyacencia).
- Resolución completa de la **Hoja de Ejercicios 5**.
- Notebook de **soluciones y validación de algoritmos**, incluyendo:
  - Verificación de recorridos.
  - Análisis de caminos óptimos.
  - Pruebas de k-Cores.

---

## 🎯 Objetivo de la semana

Al finalizar esta semana, el estudiante será capaz de:

- Aplicar técnicas de búsqueda informadas en grafos ponderados.
- Encontrar caminos mínimos usando UCS y Dijkstra.
- Comprender la base del algoritmo A*.
- Controlar la profundidad de búsqueda mediante DLS e IDS.
- Analizar la estructura interna de un grafo mediante k-Cores.
- Evaluar la complejidad algorítmica de cada técnica.

---

## 📂 Estructura del contenido

- Diapositivas teóricas del Módulo 5.
- Hoja de Ejercicios 5.
- Notebooks en Python:
  - BFS y DFS.
  - DLS e IDS.
  - Dijkstra (matriz y lista).
  - UCS.
  - Soluciones completas de los ejercicios.

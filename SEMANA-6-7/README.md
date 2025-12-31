# 📘 Semana 6 y 7 – Grafos: Ordenamiento Topológico y Componentes Fuertemente Conexos

Este directorio contiene el material correspondiente a las **Semanas 6 y 7** del curso de **Complejidad Algorítmica**, donde se estudian técnicas avanzadas de análisis en **grafos dirigidos**, enfocándose en el **Ordenamiento Topológico** y los **Componentes Fuertemente Conexos (SCC)**.

Estas semanas permiten comprender cómo analizar dependencias, detectar ciclos y descomponer grafos dirigidos en estructuras más simples para su estudio y optimización.

---

## 📌 Contenidos principales

Los archivos PDF, notebooks y hojas de ejercicios incluidos en esta carpeta desarrollan los siguientes temas:

---

## 🔹 Ordenamiento Topológico

### 📍 Definición
- El **ordenamiento topológico** es un ordenamiento lineal de los vértices de un **grafo dirigido acíclico (DAG)**.
- Cada vértice aparece antes que todos los vértices a los que apunta.
- Solo es aplicable a grafos **dirigidos sin ciclos**.

### 📍 Propiedades
- Un grafo puede tener **más de un orden topológico válido**.
- Siempre inicia con un nodo de **grado de entrada 0**.
- Si no existe un nodo con grado de entrada 0, el grafo contiene ciclos.

### 📍 Algoritmos de ordenamiento topológico
- Algoritmo **iterativo** basado en eliminación de nodos con grado de entrada 0.
- Ordenamiento topológico basado en **DFS**.
- Análisis de casos donde no existe ordenamiento (grafos cíclicos).

### 📍 Aplicaciones
- Planificación de tareas con dependencias.
- Orden de compilación de módulos de software.
- Análisis de prerequisitos académicos.
- Flujos de trabajo y procesos industriales.
- Detección de ciclos en grafos dirigidos.

---

## 🔹 Componentes Fuertemente Conexos (SCC)

### 📍 Definición
- Un **componente fuertemente conectado** es un subgrafo máximo donde:
  - Existe un camino dirigido entre **cada par de vértices**.
- Aplicable únicamente a **grafos dirigidos**.

### 📍 Importancia
- Permite detectar ciclos.
- Simplifica el análisis de grafos complejos.
- Base para optimización y análisis estructural de redes.

---

## 🔹 Algoritmos para SCC

### 🔸 Algoritmo Exhaustivo
- Inicialmente, cada nodo pertenece a su propia CFC.
- Se recorren las aristas fusionando componentes.
- Alto costo computacional.

### 🔸 Algoritmo de Kosaraju
- Basado en **dos recorridos DFS**.
- Pasos:
  1. DFS sobre el grafo original y apilado de vértices.
  2. Inversión del grafo.
  3. DFS sobre el grafo invertido siguiendo el orden de la pila.
- Complejidad:
  \[
  O(|V| + |E|)
  \]

### 🔸 Algoritmo de Tarjan
- Algoritmo basado en DFS y low-link values.
- Detecta SCC en **una sola pasada**.
- Eficiente para grafos grandes.

---

## 🔹 Análisis y comparación de algoritmos

- Comparación entre:
  - Algoritmo exhaustivo.
  - Kosaraju.
  - Tarjan.
- Evaluación del rendimiento variando:
  - Número de nodos \( n \).
  - Número de aristas \( m \).
- Identificación de:
  - Componentes aislados.
  - Componentes gigantes.
  - Distribución de tamaños de SCC.

---

## 🧪 Ejercicios prácticos

- Implementación de:
  - Ordenamiento topológico (iterativo y DFS).
  - Algoritmo exhaustivo de SCC.
  - Algoritmo de Kosaraju.
  - Algoritmo de Tarjan.
- Cálculo del tamaño de las SCC.
- Conteo de SCC por tamaño.
- Análisis de la aparición de componentes gigantes.
- Optimización del algoritmo exhaustivo.

---

## 🎯 Objetivo de las semanas 6 y 7

Al finalizar estas semanas, el estudiante será capaz de:

- Determinar si un grafo dirigido admite ordenamiento topológico.
- Implementar distintos algoritmos de ordenamiento topológico.
- Identificar y calcular componentes fuertemente conexos.
- Comparar algoritmos de SCC en términos de eficiencia.
- Analizar el comportamiento estructural de grafos dirigidos.
- Aplicar estos conceptos a problemas reales de dependencias y ciclos.

---

## 📂 Estructura del contenido

- Diapositivas teóricas del Módulo 6.
- Hoja de Ejercicios 6.
- Notebooks en Python:
  - Ordenamiento topológico.
  - SCC con algoritmo exhaustivo.
  - SCC con Kosaraju.
  - Comparación de algoritmos.
- Ejercicios resueltos y análisis experimental.

---

📌 **Nota:**  
Este material corresponde a las **Semanas 6 y 7** y cierra el bloque de **análisis estructural de grafos**, preparando al estudiante para algoritmos más avanzados y aplicaciones en optimización, redes y análisis de sistemas complejos.

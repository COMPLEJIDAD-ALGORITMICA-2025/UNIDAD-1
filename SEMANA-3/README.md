# 📘 Semana 3 – Algoritmo Divide y Vencerás

Este directorio contiene el material correspondiente a la **Semana 3** del curso de **Complejidad Algorítmica**, donde se estudia el paradigma de diseño de algoritmos **Divide y Vencerás (Divide and Conquer)**, una de las técnicas fundamentales para resolver problemas de forma eficiente mediante el uso de recursividad.

Durante esta semana se analiza cómo dividir un problema en subproblemas más pequeños, resolverlos recursivamente y combinar sus soluciones, así como el impacto de este enfoque en la complejidad algorítmica.

---

## 📌 Contenidos principales

Los archivos PDF y notebooks incluidos en esta carpeta desarrollan los siguientes temas:

### 🔹 Definición del algoritmo Divide y Vencerás
- Paradigma de diseño basado en recursividad.
- Estructura general del algoritmo:
  1. **Dividir** el problema en subproblemas más pequeños.
  2. **Conquistar** resolviendo recursivamente cada subproblema.
  3. **Combinar** las soluciones parciales para obtener la solución final.
- Representación mediante seudocódigo y diagramas de recursión.

### 🔹 Problemas clásicos que aplican Divide y Vencerás
- **Búsqueda del elemento máximo y mínimo en un arreglo**.
- **Cálculo del valor máximo en un arreglo no ordenado** usando:
  - Algoritmo clásico (iterativo).
  - Algoritmo Divide y Vencerás.
- Comparación entre ambos enfoques.

### 🔹 Multiplicación de enteros de n cifras
- Algoritmo clásico de multiplicación.
- Aplicación del enfoque Divide y Vencerás.
- Reducción del número de operaciones.
- Análisis de eficiencia del algoritmo resultante.

### 🔹 Multiplicación de matrices cuadradas
- Descomposición de matrices en submatrices.
- Esquema de multiplicación matricial clásica.
- Análisis de la complejidad temporal del algoritmo.
- Relación con algoritmos más avanzados basados en Divide y Vencerás.

### 🔹 Complejidad algorítmica en Divide y Vencerás
- Formulación de recurrencias del tipo:

  \[
  T(n) = aT\left(\frac{n}{b}\right) + f(n)
  \]

- Introducción al **Teorema Maestro** para la resolución de recurrencias.
- Análisis de complejidad para ejemplos vistos en clase:
  - Máximo en un arreglo.
  - Multiplicación de enteros.
  - Multiplicación de matrices.

### 🔹 Ejercicios prácticos
- Implementación de algoritmos Divide y Vencerás en Python.
- Análisis comparativo entre soluciones simples y recursivas.
- Problemas clásicos:
  - Quicksort.
  - Contador de palabras (base conceptual de MapReduce).
  - Problema del Skyline.

---

## 🎯 Objetivo de la semana

Al finalizar esta semana, el estudiante será capaz de:

- Comprender el paradigma Divide y Vencerás.
- Diseñar algoritmos recursivos para problemas clásicos.
- Formular y resolver recurrencias de complejidad.
- Aplicar el Teorema Maestro para analizar eficiencia.
- Comparar algoritmos clásicos vs Divide y Vencerás.

---

## 📂 Estructura del contenido

- Diapositivas teóricas del Módulo 3.
- Hojas de ejercicios de Divide y Vencerás.
- Notebooks en Python:
  - Máximo y mínimo en arreglos.
  - Multiplicación de números de n cifras.
  - Multiplicación de matrices.
  - Ejercicios prácticos guiados.
- Problemas clásicos resueltos y propuestos.

---

📌 **Nota:**  
Este material corresponde exclusivamente a la **Semana 3** y establece las bases para el análisis avanzado de algoritmos recursivos y técnicas más eficientes que se estudiarán en las siguientes semanas del curso.

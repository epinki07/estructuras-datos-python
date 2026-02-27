# Protecto-iterativo-

# Evaluación 2 - Estructura de Datos (Grafos)

Este repositorio contiene nuestra implementación en Python de un grafo usando **lista de adyacencia** y recorridos.

## Qué incluye este código
### Proyecto 1 (BFS con cola propia)
- Clase `Queue` (cola propia) con:
  - `enqueue(x)`, `dequeue()`, `first()` / `peek()`, `is_empty()`, `size()`
- Clase `Graph` con lista de adyacencia (diccionario)
- Métodos:
  - `bfs(start)` -> regresa el orden de visita
  - `bfs_parents(start)` -> regresa un diccionario `parent` para reconstruir caminos
  - `path_unweighted(start, goal)` -> regresa la ruta (lista) o `None` si no existe


## Cómo ejecutar
En tu computadora o en Colab:


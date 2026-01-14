# Proyecto-VRP
Proyecto de optimización del Problema de Ruteo de Vehículos (VRP) utilizando el algoritmo de Optimización por Colonia de Hormigas (ACO), enfocado en encontrar rutas eficientes que minimicen la distancia total recorrida, respetando restricciones de capacidad por vehículo y aplicando búsqueda local para mejorar las soluciones.

# Vehicle Routing Problem (VRP) con Ant Colony Optimization (ACO)

Este proyecto implementa una solución al **Problema de Ruteo de Vehículos (VRP)** utilizando el algoritmo de **Optimización por Colonia de Hormigas (Ant Colony Optimization, ACO)**, con el objetivo de encontrar rutas eficientes que minimicen la distancia total recorrida, respetando restricciones de capacidad por vehículo.

El sistema procesa múltiples instancias del problema, aplica paralelización para mejorar el rendimiento y exporta los resultados para su análisis.

---

## 🧠 Descripción del Proyecto

Se utiliza un enfoque bioinspirado basado en colonias de hormigas para explorar el espacio de soluciones del VRP.  
El algoritmo construye rutas probabilísticamente usando feromonas y heurísticas, e incorpora una búsqueda local (2-opt) para mejorar la calidad de las soluciones.

---

## 🚀 Características

- Implementación del algoritmo ACO capacitado
- Restricciones de capacidad por vehículo
- Optimización local mediante 2-opt
- Procesamiento paralelo de instancias
- Soporte para datasets pequeños, medianos y grandes
- Exportación automática de resultados a Excel

---

## 📁 Estructura del Proyecto

- `src/` → Código fuente del proyecto
- `datasets/` → Instancias del problema VRP
- `results/` → Resultados generados por el algoritmo
- `requirements.txt` → Dependencias del proyecto

---

## ▶️ Ejecución

1. Instalar dependencias:
```bash
pip install -r requirements.txt


##Ejecutar el proyecto:

python src/main.py


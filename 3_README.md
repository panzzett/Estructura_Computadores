# Simulación de Procesadores DLX y DLXV  
#EJECUCIÓN Y OPTIMIZACIÓN DE PIPELINES EN ARQUITECTURAS SEGMENTADAS

Este proyecto consiste en una práctica de simulación de procesadores utilizando las herramientas WinDLX y DLXV. El objetivo es analizar el comportamiento de arquitecturas segmentadas, detectar cuellos de botella debidos a dependencias entre instrucciones y aplicar técnicas de optimización como `nop`, desenrollado de bucles, encadenamiento vectorial y adelanto de resultados.

## ⚙️ Tecnologías y herramientas

- Simuladores: WinDLX y DLXV  
- Procesador DLX clásico  
- Procesador vectorial DLXV  

## 📁 Estructura

- `Act3_GalvezReguera_Carlos.pdf`: Informe completo del laboratorio con análisis, simulaciones y comparativas.
- `src/`: Scripts de simulación.
- `3_README.md`: Descripción del experimento y enlaces.

## 📌 Objetivo

Comprender cómo afectan las dependencias entre instrucciones al rendimiento del pipeline y explorar cómo distintas estrategias permiten mitigar estos efectos.  
Se simulan tanto arquitecturas clásicas como vectoriales para estudiar y comparar técnicas como:

- Inserción de instrucciones `nop` para evitar conflictos RAW
- Reordenamiento y desenrollado de bucles
- Encadenamiento vectorial (`chaining`)
- Adelanto de resultados (`forwarding`)

## 🧪 Contenidos clave

### 🔹 Procesador DLX clásico
- Simulación básica con conflictos RAW
- Inserción de `nop` para resolver dependencia
- Desenrollado de bucle para mayor eficiencia

### 🔹 Procesador DLXV vectorial
- Simulación sin mejoras (pipeline secuencial)
- Activación de encadenamiento vectorial
- Activación de `forwarding`
- Comparativa estructural del rendimiento del pipeline

## 📈 Resultados y conclusiones

Aunque los programas simulados son breves, los resultados muestran cómo pequeñas decisiones en la organización del código afectan al flujo del pipeline.  
Las técnicas de optimización implementadas mejoran el aprovechamiento del procesador, reducen parones y preparan el código para un mejor rendimiento en escenarios reales más complejos.

## 🧑‍💻 Autor

Carlos Gálvez

> Proyecto orientado al análisis de eficiencia y paralelismo en arquitectura de computadores mediante simulación.

## 📄 Memoria Técnica

📥 [Act3_GalvezReguera_Carlos.pdf](./Act3_GalvezReguera_Carlos.pdf)

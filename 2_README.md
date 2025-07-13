# Comparativa de Procesadores Superescalares  
#IBM POWER4 vs Sun UltraSPARC III

Este proyecto presenta una comparativa técnica entre dos arquitecturas superescalares representativas de enfoques diferentes en el diseño de procesadores: el IBM POWER4 y el Sun UltraSPARC III. A lo largo del documento se abordan tanto los elementos estructurales como los aspectos más avanzados que afectan al rendimiento y paralelismo de ejecución.

## 🧠 Objetivo

Analizar las diferencias clave entre dos procesadores superescalares desde una perspectiva estructural y funcional.  
Se comparan aspectos como:

- Cauces de ejecución  
- Número de vías superescalares  
- Unidades funcionales  
- Técnicas de paralelismo (ordenada vs fuera de orden)  
- Predicción de saltos  
- Renombrado de registros  
- Arquitecturas RISC PowerPC y SPARC

## ⚙️ Contenidos principales

### 🔹 IBM POWER4
- Arquitectura de doble núcleo (CMP), 4 vías por núcleo (hasta 8 instrucciones por ciclo)
- Ejecución fuera de orden, con renombrado dinámico y buffer de reordenamiento
- Predicción de saltos dinámica multietapa
- Enfoque orientado a rendimiento intensivo y paralelismo dinámico (ILP)

### 🔹 Sun UltraSPARC III
- Arquitectura RISC de 64 bits basada en SPARC V9
- Ejecución ordenada, con segmentación profunda (14 etapas)
- Uso de ventanas de registros para gestión eficiente de contextos
- Predicción de saltos estática mejorada

### 📊 Comparación técnica

| Característica              | IBM POWER4                 | Sun UltraSPARC III             |
|----------------------------|----------------------------|--------------------------------|
| Ejecución                  | Fuera de orden             | Ordenada                       |
| Núcleos                    | 2                          | 1                              |
| Vías superescalares        | 4 por núcleo               | 4                              |
| Renombrado de registros    | Sí                         | No                             |
| Buffer de reordenamiento   | Sí                         | No                             |
| Predicción de saltos       | Dinámica (multi-nivel)     | Estática                       |
| Tecnología fabricación     | 180 nm                     | 180 nm                         |
| Aplicaciones               | HPC, servidores críticos   | Estaciones UNIX, servidores    |

## 📝 Conclusión

El IBM POWER4 representa una arquitectura superescalar moderna con fuerte orientación al paralelismo dinámico, mientras que el UltraSPARC III adopta un enfoque más clásico, basado en ejecución ordenada y eficiencia estructural.  
Ambos ofrecen soluciones válidas para distintos contextos, con ventajas específicas en escalabilidad, predictibilidad y rendimiento según el tipo de carga de trabajo.

## 📂 Archivos

- `2_Memoria_Técnica_Carlos_galvez_act2.pdf`: Informe completo con análisis y comparativa estructurada.

## 🧑‍💻 Autor

Carlos Gálvez

> Trabajo orientado al análisis comparativo de arquitecturas superescalares en procesadores RISC.

📥 [2_Memoria_Técnica_Carlos_galvez_act2.pdf](./2_Memoria_Técnica_Carlos_galvez_act2.pdf)

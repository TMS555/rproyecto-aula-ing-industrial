# 🏭 Simulador de Línea de Ensamblaje (Detección de Cuellos de Botella)

Este proyecto implementa una **Simulación de Eventos Discretos** para modelar una línea de manufactura secuencial. Su objetivo principal es aplicar la **Teoría de Restricciones (TOC)** para identificar automáticamente cuál estación limita la capacidad productiva del sistema (el Cuello de Botella).

## 📋 Descripción del Proyecto

El script simula el flujo de 100 productos a través de 4 estaciones de trabajo con tiempos de proceso heterogéneos:
1. **Corte** (Promedio: 4 min)
2. **Ensamble** (Promedio: 6 min)
3. **Pintura** (Promedio: 12 min)
4. **Empaque** (Promedio: 5 min)

El sistema calcula el tiempo que cada estación pasa trabajando vs. esperando, y determina la **Utilización (%)**. La estación con el porcentaje más alto es identificada como la restricción del sistema.

## 🛠️ Requisitos Técnicos

Para ejecutar este simulador necesitas tener instalado **Python 3** y las siguientes librerías:

* **SimPy:** Motor de simulación de eventos discretos.
* **Pandas:** Para la estructuración y cálculo de datos.

### Instalación de dependencias
Ejecuta el siguiente comando en tu terminal:

```bash
pip install simpy pandas
            

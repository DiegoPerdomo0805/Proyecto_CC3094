# Detección de tráfico DDoS mediante comportamiento de flujo de red

## Pregunta de investigación

**Can flow-level network behavior distinguish benign traffic from DDoS traffic?**

Este proyecto analiza si las características de flujo de red permiten distinguir entre tráfico benigno y tráfico DDoS mediante modelos de clasificación supervisada.

## Descripción del proyecto

El objetivo del proyecto es implementar y evaluar modelos de machine learning capaces de clasificar tráfico de red como benigno o DDoS a partir de variables de comportamiento a nivel de flujo.

El trabajo utiliza una formulación binaria del problema:

- `0`: BENIGN
- `1`: DDoS

La implementación incluye análisis exploratorio de datos, limpieza, selección de características, entrenamiento de modelos, evaluación de métricas y análisis de resultados en el contexto de ciberseguridad.

## Dataset

El dataset utilizado proviene de **CICIDS2017**, específicamente del archivo correspondiente al tráfico de viernes por la tarde con ataques DDoS:

```text
Friday-WorkingHours-Afternoon-DDos.pcap_ISCX.csv
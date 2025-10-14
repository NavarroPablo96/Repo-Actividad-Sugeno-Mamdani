\# Sistemas de Inferencia Difusa (Fuzzy Inference Systems)



Este repositorio contiene las implementaciones en Python de modelos de \*\*Lógica Difusa (Fuzzy Logic)\*\*, centrados en los sistemas \*\*Sugeno\*\* y \*\*Mamdani\*\*, aplicados a problemas de series de tiempo y control.



\*\*\*



\## Estructura del Repositorio



| Archivo | Descripción |

| :--- | :--- |

| `Actividad 1a - Sugeno VDA.ipynb` | Implementación de un modelo Sugeno (tipo genfis2) aplicado a la predicción de una \*\*señal VDA\*\* (Vibración de Datos de Acelerómetro). |

| `Actividad 1b - Sugeno SPY.ipynb` | Implementación del modelo Sugeno aplicado a la predicción y \*\*extrapolación\*\* de la serie de tiempo de las acciones \*\*S\&P 500 (SPY)\*\*. |

| `Actividad 2a Mamdani.ipynb` | Implementación de un Sistema de Inferencia Difusa de tipo \*\*Mamdani\*\* para la aplicación de \*\*Control\*\* (ejemplo del "Calderista"). |

| `Informe - Actividad 2a - Mamdani Calderista.pdf` | Documento que detalla el diseño, la lógica de reglas y los resultados del sistema Mamdani. |

| `samplesVDA1.txt` | Dataset de la señal de Vibración de Datos de Acelerómetro (VDA). |

| `spy.csv` | Dataset de precios históricos de las acciones del S\&P 500 (SPY). |

| `Informe - Actividad 1a - Sugeno VDA.pdf` | Informe detallado de la actividad 1a. |

| `Informe - Actividad 1b - Sugeno SPY.pdf` | Informe detallado de la actividad 1b. |



\*\*\*



\## Requisitos



Para ejecutar los \*notebooks\* de Jupyter, necesitarás las siguientes librerías de Python:



```bash

pip install numpy pandas matplotlib scikit-learn scipy


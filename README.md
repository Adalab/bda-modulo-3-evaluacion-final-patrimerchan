# Análisis de Lealtad de Clientes de Aerolínea

Este proyecto analiza los datos de los clientes de una aerolínea para comprender su comportamiento de vuelo y su lealtad. Utiliza dos conjuntos de datos para explorar la actividad de vuelo y el historial de lealtad de los clientes.

## Conjuntos de datos

- **Customer Flight Activity.csv**: Contiene datos sobre la actividad de vuelo de los clientes, como vuelos reservados, distancia y puntos acumulados/canjeados.
- **Customer Loyalty History.csv**: Proporciona información demográfica y del programa de fidelización de los clientes, como el país, la educación, el salario y el tipo de tarjeta de fidelización.

## Análisis

El análisis exploratorio de datos (EDA) y la limpieza de datos se realizan en el notebook `Evaluacion_Final_Modulo_3.ipynb`. Se utilizan librerías como Pandas, Matplotlib y Seaborn para procesar y visualizar los datos.

### Ejemplos

Carga de los datos:
```python
import pandas as pd

# Cargar los datos de actividad de vuelo
df_activity = pd.read_csv('Customer Flight Activity.csv')

# Cargar el historial de lealtad de los clientes
df_history = pd.read_csv('Customer Loyalty History.csv')
```

Visualización de vuelos reservados:
```python
import seaborn as sns
import matplotlib.pyplot as plt

sns.histplot(data=df_activity, x='Flights Booked')
plt.show()
```

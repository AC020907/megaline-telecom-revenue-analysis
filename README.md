#  Análisis de Ingresos de Planes Telefónicos

## Descripción del proyecto

Este proyecto analiza el comportamiento de clientes de una compañía de telecomunicaciones con el objetivo de comparar dos planes móviles y determinar cuál genera mayores ingresos.

El análisis incluye limpieza de datos, exploración estadística y visualizaciones para identificar patrones de consumo y validar hipótesis relacionadas con llamadas, mensajes, uso de internet e ingresos mensuales.

## Funcionalidades del análisis

- **Limpieza y preparación de datos**
  - Corrección de tipos de datos
  - Unión de múltiples datasets
  - Tratamiento de valores ausentes

- **Análisis exploratorio (EDA)**
  - Consumo de llamadas
  - Uso de mensajes y datos móviles
  - Comparación de ingresos por plan
  - Distribución del comportamiento de usuarios

- **Análisis estadístico**
  - Pruebas de hipótesis
  - Comparación de ingresos promedio
  - Diferencias entre grupos de usuarios

- **Visualizaciones**
  - Histogramas
  - Boxplots
  - Gráficos comparativos
  - Distribuciones de consumo

## Tecnologías utilizadas

- [Python 3](https://www.python.org/)
- [Pandas](https://pandas.pydata.org/) – análisis y manipulación de datos
- [NumPy](https://numpy.org/) – operaciones numéricas
- [Matplotlib](https://matplotlib.org/) – visualización de datos
- [SciPy](https://scipy.org/) – pruebas estadísticas
- [Jupyter Notebook](https://jupyter.org/) – entorno de desarrollo

## Estructura del proyecto

Cómo ejecutar el proyecto localmente

Clona el repositorio:

git clone <URL_DEL_REPOSITORIO>
cd <NOMBRE_DEL_REPOSITORIO>

2. Crea y activa un entorno virtual:
   ```bash
   python -m venv env
   source env/bin/activate   # macOS/Linux
   env\Scripts\activate      # Windows

Instala las dependencias:

pip install pandas numpy matplotlib scipy jupyter

Ejecuta Jupyter Notebook:

jupyter notebook
Abre el archivo .ipynb
Principales conclusiones
Uno de los planes genera ingresos promedio significativamente mayores.
El comportamiento de consumo cambia dependiendo del tipo de usuario.
Existen diferencias importantes en el uso de llamadas, mensajes e internet.
Las pruebas estadísticas permitieron validar diferencias relevantes entre grupos.

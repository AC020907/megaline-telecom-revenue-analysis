```markdown
# Análisis de Rentabilidad de Planes de Telecomunicaciones - Megaline

📋 Descripción del Proyecto
Este proyecto analiza la rentabilidad de dos planes de prepago ofrecidos por el operador de telecomunicaciones Megaline: Surf y Ultimate. El objetivo es determinar cuál plan genera mayores ingresos para optimizar la estrategia de marketing y asignación presupuestaria.

🎯 Objetivos
Analizar comportamiento de usuarios por plan (llamadas, SMS, datos)
Calcular ingresos mensuales considerando tarifas base y excedentes
Comparar rentabilidad entre planes Surf y Ultimate
Realizar pruebas estadísticas para validar diferencias significativas
Proporcionar recomendaciones estratégicas basadas en evidencia
📊 Conjunto de Datos
Período de análisis: Año 2018  
Muestra: 500 clientes de Megaline

Estructura de datos:
Usuarios (megaline_users.csv):
- Información demográfica y plan contratado
- Fechas de registro y cancelación

Llamadas (megaline_calls.csv):
- 137,735 registros de llamadas
- Duración y fechas de cada llamada

Mensajes (megaline_messages.csv):
- 76,051 registros de SMS
- Fechas de envío por usuario

Internet (megaline_internet.csv):
- 104,825 sesiones de navegación
- Consumo en MB por sesión

Planes (megaline_plans.csv):
- Detalles de tarifas y límites incluidos

🛠️ Tecnologías Utilizadas
Python 3.9+
Pandas: Manipulación y análisis de datos
NumPy: Cálculos numéricos y redondeo
Matplotlib: Visualización de datos
SciPy: Pruebas estadísticas
Jupyter Notebook: Entorno de desarrollo
📈 Principales Hallazgos
Comparación de Planes
Métrica	Plan Surf	Plan Ultimate
Tarifa mensual	$20 USD	$70 USD
Ingreso promedio	$60.42 USD	$72.25 USD
Desviación estándar	$53.60 USD	$11.04 USD
Minutos incluidos	500 min	3,000 min
Mensajes incluidos	50 SMS	1,000 SMS
Datos incluidos	15 GB	30 GB
Patrones de Comportamiento
Plan Surf:
- Usuarios casuales con consumo impredecible
- Alta variabilidad en ingresos
- Frecuentes excedentes que generan cargos adicionales

Plan Ultimate:
- Usuarios empresariales/formales
- Consumo más estable y predecible
- Mejor planificación del uso de servicios

🔧 Metodología de Análisis
1. Limpieza de Datos
Conversión de tipos: Fechas a formato datetime
Filtrado de llamadas: Eliminación de llamadas con duración 0
Redondeo de minutos: Aplicación de np.ceil() por llamada individual
**

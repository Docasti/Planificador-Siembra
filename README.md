##🌾 Planificador de Siembra Inteligente

¡Aplicación en vivo! Puedes acceder y probar la calculadora aquí: URL: https://d002f1ae85b6867ce6.gradio.live

Descripción del Proyecto
Este proyecto es una herramienta de ciencia de datos diseñada para ayudar a pequeños productores agropecuarios a tomar decisiones de siembra más informadas. El sistema utiliza modelos de Machine Learning para predecir rendimientos de cultivos y un modelo de optimización matemática para recomendar la asignación óptima de hectáreas.

El objetivo principal es transformar datos climáticos e información de consumo en una recomendación clara y accionable, permitiendo a los productores maximizar sus ganancias y asegurar la subsistencia familiar.

Caso de Uso
El proyecto se centra en un pequeño productor de la zona rural de Santiago del Estero, Argentina. La herramienta lo asiste para planificar su siembra anual, tomando en cuenta la necesidad de autoconsumo para su familia y ganado, y la rentabilidad. Un caso de uso clave es la capacidad del modelo para priorizar cultivos más resistentes en escenarios de sequía, mitigando el riesgo de pérdida de cosecha.

Características Clave

Simulación de Datos (ETL): El app_gradio.ipynb contiene la simulación de datos. 

Predicción de Rendimientos: Utiliza un modelo de Random Forest Regressor para pronosticar la producción de Maíz, Choclo y Zapallo.

Modelo de Optimización de Siembra: use de SciPy ( scipy.optimize.linprog para optimización lineal, recomienda la distribución ideal de hectáreas para maximizar la ganancia total.

Calculadora de Autoconsumo: Calcula las hectáreas mínimas necesarias para asegurar las necesidades alimentarias de la familia y el ganado.

Interfaz de Usuario (MVP): La herramienta se entrega a través de una aplicación web simple construida con Gradio, que permite a los usuarios interactuar con el modelo sin necesidad de ver o modificar el código.

Estructura del Repositorio
app_gradio.ipynb: El código principal del proyecto, incluyendo la simulación de datos, los modelos de IA y la interfaz de Gradio.

presentacion.md: Documentación detallada del proyecto, incluyendo la presentación  y los conceptos técnicos.

README.md: Este archivo.

Tecnologías Utilizadas
Python

Librerías de Ciencia de Datos: Pandas, NumPy, Scikit-learn, SciPy

Plataforma: Google Colab

Interfaz de Usuario: Gradio

Próximos Pasos (Visión a Futuro)
El siguiente paso para el proyecto sería integrar la entrada de datos automática a través de APIs. Esto permitiría a la aplicación consultar directamente servicios como la NASA o el Servicio Meteorológico Nacional para obtener datos climáticos en tiempo real, eliminando la necesidad de que el usuario los ingrese manualmente y transformando el MVP en una herramienta completamente automatizada.

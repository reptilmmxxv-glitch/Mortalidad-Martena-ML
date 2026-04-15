

# Mortalidad-Martena-ML
Sistema de predicción de riesgo de mortalidad materna usando Regresión Logística
Desarrollado por C. Rozas Balboa
Matron / Alumno ingernieria civil informatica
Facultad de Ingeniería, Universidad Andrés Bello

Descripción del Proyecto
Este proyecto consiste en el desarrollo de un sistema predictivo orientado a la identificación del riesgo de mortalidad materna a partir del conjunto de datos KDHS 2022. Mediante la aplicación de técnicas de Aprendizaje Automático, se analizan 22 atributos de naturaleza sociodemográfica y clínica para ofrecer una herramienta funcional de apoyo en la toma de decisiones médicas.

Resultados del Análisis
De acuerdo con el análisis realizado en el entorno de desarrollo, el modelo de Regresión Logística fue seleccionado por presentar el desempeño más robusto con un área bajo la curva de 0.63. Los resultados indican que el nivel educacional, la paridad, el número de controles prenatales y la ubicación geográfica actúan como los predictores de mayor relevancia. Para asegurar la transparencia de las predicciones, se incorporó la metodología SHAP, permitiendo interpretar la contribución de cada variable en los resultados finales.

Propuesta de Interfaz
La operacionalización del modelo se presenta mediante un prototipo de interfaz de usuario diseñado para maximizar la agilidad en entornos clínicos. El sistema incluye un formulario de entrada para los parámetros del estudio y un indicador visual de riesgo categorizado en niveles bajo, moderado y alto. La propuesta prioriza la privacidad del paciente al procesar la información de manera efímera, evitando el almacenamiento persistente de datos sensibles.

Arquitectura Técnica Proyectada
La infraestructura futura de la aplicación contempla un entorno de front-end basado en HTML y Bootstrap para garantizar la responsividad en diferentes dispositivos. El motor de inferencia se ejecutará en un back-end desarrollado con el microframework Flask de Python, el cual gestionará la carga del modelo entrenado y la generación de informes técnicos en formato PDF para su entrega inmediata a la paciente.


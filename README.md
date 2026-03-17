#Case Study: Análisis de Datos de Cyclistic - Estrategia de Conversión
##Introducción
Este proyecto es parte del Certificado Profesional de Análisis de Datos de Google. El análisis se centra en Cyclistic, una empresa de bicicletas compartidas en Chicago, con el objetivo de identificar patrones de uso que permitan diseñar una estrategia de marketing para convertir a usuarios ocasionales en miembros anuales.

##Escenario de Negocio
La dirección de marketing busca maximizar la rentabilidad a largo plazo incrementando el número de membresías anuales. La tarea principal consiste en responder a la pregunta: ¿En qué se diferencian los miembros anuales y los ciclistas ocasionales en el uso de las bicicletas de Cyclistic?

##Estructura de los Datos
Los datos analizados corresponden al primer trimestre de 2020 (Q1 2020).

Fuente de datos: Datos históricos de viajes de Cyclistic alojados en Amazon S3.

Volumen: 406,000 registros individuales de viaje.

Variables principales: ID de viaje, tipo de bicicleta, marcas de tiempo (inicio/fin), nombres de estaciones y tipo de usuario (miembro/casual).

Integridad: Los datos han sido verificados bajo los parámetros ROCCC para asegurar su fiabilidad y relevancia.

##Proceso de Análisis
Preparar y Procesar
Se realizaron tareas de limpieza y manipulación de datos para garantizar la precisión del análisis:

Eliminación de registros con duraciones de viaje negativas o nulas.

Exclusión de viajes de prueba internos del sistema.

Creación de nuevas columnas: Duración del viaje (en minutos) y Día de la semana.

##Analizar y Hallazgos Clave
El análisis reveló diferencias críticas en el comportamiento de los usuarios:

Diferencia de Duración: Los usuarios ocasionales realizan trayectos significativamente más largos, multiplicando por ocho la duración promedio de los miembros.

Patrones de Tiempo: Los miembros muestran un uso utilitario con picos en horas de entrada y salida laboral (lunes a viernes). Los ocasionales presentan un uso recreativo concentrado en fines de semana.

Geografía del Uso: El segmento ocasional se concentra en estaciones cercanas a zonas turísticas, parques y la costa, mientras que los miembros tienen una distribución más uniforme en la ciudad.

##Recomendaciones Estratégicas
Nueva Estructura de Membresía: Desarrollar un plan anual de bajo costo enfocado exclusivamente en el uso recreativo de fin de semana para captar al usuario ocasional recurrente.

Marketing por Geolocalización: Implementar campañas de publicidad digital y señalética física en las 10 estaciones con mayor afluencia de usuarios ocasionales detectadas en el análisis.

Incentivo de Conversión por Uso: Crear un programa donde los minutos acumulados en pases diarios se traduzcan en un descuento proporcional para la adquisición de la membresía anual.

Herramientas Utilizadas
Procesamiento de datos: SQL / R

Visualización: Tableau / Power BI / Excel

Documentación: Markdown y GitHub

En este caso de estudio, analicé más de 400,000 registros de viajes de la empresa Cyclistic para identificar oportunidades de crecimiento en membresías. A través de un proceso de limpieza y análisis estadístico, descubrí que los usuarios ocasionales utilizan el sistema principalmente para ocio en fines de semana, con trayectos mucho más largos que los miembros. Mis recomendaciones finales proponen una estrategia de marketing geolocalizado y nuevos planes de suscripción adaptados a este comportamiento recreativo, proporcionando al equipo ejecutivo una hoja de ruta basada en datos para aumentar la rentabilidad.

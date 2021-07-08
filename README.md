# Deteccion-y-Alerta-Temprana-GEM

Trabajo Fin de Máster

Máster Ciberseguridad - Universidad Pontificia Comillas (ICAI)

## Código
Todo el código se puede ver en los siguientes enlaces:
1. [Proyecto AlertaTemprana](https://bitbucket.org/mrchamizo/alertatemprana2021/src/master/): contiene el proyecto CETA.
2. [Correlación datos](https://github.com/MrChamizo98/Clusterizado): contiene el código para el desarrollo de la correlación en CETA.
3. [Clusterizado datos](https://github.com/MrChamizo98/Correlation): contiene el código para el desarrollo del clusterizado en CETA.

## Resumen 
El objetivo principal del trabajo es la creación de una plataforma que incorpore las principales herramientas de monitorización de una organización, que junto con la conexión a sondas externas que proporcionen una visión de los activos de esta misma desde el exterior se convierta en la herramienta central para gestionar la seguirdad de la entidad. 

Este proyecto surge como consecuencia de la continuación del proyecto inicial realizado por el tutor Juan Carlos Cortinas, dónde realizó una herramienta que se encargaba de visualizar los activos externos de una organización y mezclar esa información con las posibles vulnerabilidades públicas existentes de dichos activos.

En cuanto a la plataforma se la ha dotado de nueva funcionalidad como es la visualización en tiempo real de las alertas generadas por las diferentes herramientas de monitorización, con la posibilidad de modificar los dashboard de cada una de las herramientas y configurarlos a gusto del consumidor. Además, cabe la posibilidad de poder añadir más herramientas en un futuro debido a la facilidad de escalado de la que dispone la plataforma. 

Finalmente, la plataforma denominada CETA cobra un valor aún mayor con la incorporación de la correlación de los datos proporcionados por las diferentes herramientas. De este modo, cabe la posibilidad de observar las alertas generadas de forma conjunta en vez de manera individual. Y no sólo eso, la implementación de un algoritmo de Machine Learning como es el clusterizado, permite la clasificación de todas las alertas recibidas en tiempo real. 

En definitiva, un sistema totalmente completo y revolucionario de cara a ser una referencia en la monitorización de oganizaciones. 

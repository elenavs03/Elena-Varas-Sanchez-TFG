# TFG: Estimación de la prima pura en seguros de automóvil mediante modelos lineales generalizados y su aplicación en Power BI
Trabajo de Fin de Grado en Estadística centrado en la estimación de la prima pura en seguros de automóvil mediante modelos lineales generalizados. Se analiza la siniestralidad desde un enfoque frecuencia-severidad y mediante un modelo Tweedie, integrando los resultados en un dashboard interactivo desarrollado en Power BI.

## Resumen
En los seguros de automóvil, la tarificación es un elemento clave para garantizar el equilibrio técnico de la cartera y una adecuada gestión del riesgo. Este proceso requiere comprender y cuantificar adecuadamente la siniestralidad, teniendo en cuenta la elevada heterogeneidad del riesgo presente en este tipo de carteras. Por ello, es necesario disponer de modelos que permitan estimar de forma consistente el coste esperado y analizar la influencia de las características del asegurado y del vehículo. Además, es importante que este análisis sea comprensible y pueda presentarse de forma clara y sencilla a perfiles de gestor, de forma que los resultados sirvan como apoyo a la toma de decisiones.

En este trabajo, se emplean modelos lineales generalizados para estimar la prima pura y analizar de forma diferenciada las dos componentes fundamentales de la siniestralidad: la frecuencia y la severidad de los siniestros. La modelización se aborda mediante un enfoque en dos etapas, que se complementa con una estimación alternativa basada en el modelo Tweedie, permitiendo comparar ambas metodologías. A lo largo del trabajo se discuten las principales decisiones metodológicas adoptadas y se analiza el efecto de las distintas variables explicativas sobre el riesgo esperado.

Una vez estimados los modelos, los resultados ponen de manifiesto la elevada heterogeneidad del riesgo y una mayor capacidad explicativa de la variable en la modelización de la frecuencia que en la severidad. Además, la comparación entre metodologías muestra que el modelo Tweedie tiende a generar estimaciones de prima pura más conservadores, mientras que el enfoque frecuencia-severidad ofrece una mayor interpretabilidad. Por último, los resultados obtenidos se integran en un dashboard interactivo en Power BI que permite visualizar el riesgo de forma clara y apoyar la toma de decisiones en la gestión aseguradora.

## Entorno de desarollo del proyecto

Este trabajo de Fin de Grado se ha desarrollado principalmente utilizando el lenguaje de programación R y la herramienta de visualización Power BI.

### Lenguajes y entornos utilizados
- R: empleado para el tratemiento de datos, el anális exploratorio y la modelización estadística.
- Power BI: utilizado para la construcción de un dashboard interactivo orientado al análisis del riego y al apoyo a la toma de decisiones en un contexto de gestión aseguradora

### Paquetes de R utilizados
Los paquetes necesarios para el desarrollo del proyecto en el entorno R son los siguientes: 

- zoo
- xts
- CASdatasets
- dplyr
- tidyr
- ggplot2
- scales
- forcast
- kableExtra
- MASS
- survival
- effects
- broom
- stringr
- tweedie
- statmod
- openxlsx
- glmmTMG
- cplm

## Contenido del repositorio
Dentro de este repositorio se puede encontrar:

- En la carpeta [memoria](memoria), el documento final del Trabajo de Fin de Grado en formato PDF.
- En la carpeta **code**, los scripts en R utilizados para el análisis exploratorio de los datos, la estimación de los modelos lineales generalizados y la obtención de las predicciones de frecuencia, severidad y prima pura.
- En la carpeta **powerbi**, el archivo del dashboard desarrollado en Power BI, que integra los resultados obtenidos a partir de los modelos estadísticos.

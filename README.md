# 911-Baltimore Proyecto TVI


# Análisis

Este informe presenta visualizaciones sobre un dataset de llamadas al 911 en Baltimore, analizando el comportamiento ante distintos tipos de emergencias a nivel de ciudad, distritos y barrios.

## Resumen 

El informe analiza un dataset de llamadas al 911 en Baltimore, reduciendo los datos a 19 columnas y 1,045,903 filas tras eliminar duplicados y columnas irrelevantes. Se utilizaron librerías como pandas, matplotlib, numpy, seaborn y geopandas para crear las visualizaciones. Las columnas principales incluyen Fecha y Hora, Distrito, Ubicación, Distrito Sheriff y Prioridad.

### Visualizaciones:

1. **Distribución de Llamadas por Distrito y Prioridad**:
   
   <img width="442" alt="image" src="https://github.com/tvonriegen/911-Baltimore/assets/173301239/e71fbf9d-1f60-493a-b0a8-89fd0627ef48">
   
   - La mayoría de las llamadas en todos los distritos son de prioridad "Baja" y "Media".
   - Las categorías "No Emergencia" y "Alta" son menos comunes.
   - "Emergencia" y "Fuera de Servicio" son las menos frecuentes.
   - El distrito Noroeste tiene el menor número de llamadas, mientras que los distritos Sur y Noreste tienen las más altas, superando las 140,000 llamadas.

2. **Llamadas por Mes y Tipo de Incidente (Ene 2021 - Ene 2023)**:

   <img width="442" alt="image" src="https://github.com/tvonriegen/911-Baltimore/assets/173301239/9ad7b720-0a64-4e46-b2af-7062ee9c2dd5">

   - "Asalto común" y "Accidente de auto" son constantes con alrededor de 2500 llamadas mensuales.
   - "Narcóticos" y "Choque y correr" muestran aumentos y fluctuaciones.
   - "Asalto grave" es menos frecuente y tiende a la baja.
   - Aumento de incidentes durante el verano del hemisferio norte.

3. **Heatmap de Llamadas por Distrito Sheriff**:
   
   <img width="442" alt="image" src="https://github.com/tvonriegen/911-Baltimore/assets/173301239/5cc9bff9-9d36-451c-853b-9a90afed2b4d">

   - Los colores más oscuros indican más llamadas, con un pico notable en julio de 2022.
   - La cantidad de llamadas es relativamente constante, sin un distrito con un número significativamente mayor de llamadas.

4. **Mapa Geográfico de Llamadas por Barrio**:

   <img width="442" alt="image" src="https://github.com/tvonriegen/911-Baltimore/assets/173301239/8ed64ef4-0f31-4798-94db-ca85d36a3949">

   - Colores claros indican más llamadas, con un barrio central destacado con hasta 40,000 llamadas.
   - La mayoría de los barrios tienen menos llamadas (colores oscuros).

5. **Nombres de Barrios con Mayor Demanda de Llamadas**:

   <img width="442" alt="image" src="https://github.com/tvonriegen/911-Baltimore/assets/173301239/c43ed991-b05a-44af-86fd-5d54f815f234">

   - Downtown tiene el mayor volumen de llamadas, seguido por Brooklyn, Frankford y Belair-Edison.

### Conclusiones

- Las zonas central y noreste de Baltimore concentran la mayoría de las llamadas, con el distrito Noreste liderando.
- El barrio con más llamadas está en la zona central, lo que resalta la necesidad de asignar recursos según estas distribuciones.
- El análisis es útil para entidades gubernamentales y residentes o futuros residentes de Baltimore, ayudándoles a identificar áreas que requieren más recursos o que podrían preferir evitar.

### Limitaciones

- Desconocimiento de la cultura y peligros específicos de Baltimore.
- Falta de información financiera sobre recursos requeridos por llamada.
- El análisis se limita a Baltimore, sin comparación con otras ciudades similares.

### Trabajo Futuro

- Comparar datasets de ciudades con características similares.
- Incluir información sobre recursos y personal requerido por llamada.
- Escalar el análisis a nivel de países para obtener una visión más completa.

### Créditos

Felipe Cisternas, Enzo Olavarria, Ignacio Rodríguez y Thomas Von Riegen

### Link Archivos

[link archivos](https://drive.google.com/drive/folders/1URNS03zH2bk8IQC2pR5dc6NPOsfqXYJo?usp=sharing)

### Agradecimientos

Los códigos usados fueron creados con ayuda de las clases de Daniela Opitz y ChatGPT.

# 911-Baltimore
# Proyecto de Visualización de Datos
# Agregar la nota sobre los códigos utilizados al contenido

content = """
# Análisis de Llamadas al 911 en Baltimore

Este informe presenta visualizaciones sobre un dataset de llamadas al 911 en Baltimore, analizando el comportamiento ante distintos tipos de emergencias a nivel de ciudad, distritos y barrios.

## Resumen del Informe

El informe analiza un dataset de llamadas al 911 en Baltimore, reduciendo los datos a 19 columnas y 1,045,903 filas tras eliminar duplicados y columnas irrelevantes. Se utilizaron librerías como pandas, matplotlib, numpy, seaborn y geopandas para crear las visualizaciones. Las columnas principales incluyen Fecha y Hora, Distrito, Ubicación, Distrito Sheriff y Prioridad.

### Visualizaciones:

1. **Distribución de Llamadas por Distrito y Prioridad**:
   - La mayoría de las llamadas en todos los distritos son de prioridad "Baja" y "Media".
   - Las categorías "No Emergencia" y "Alta" son menos comunes.
   - "Emergencia" y "Fuera de Servicio" son las menos frecuentes.
   - El distrito Noroeste tiene el menor número de llamadas, mientras que los distritos Sur y Noreste tienen las más altas, superando las 140,000 llamadas.

2. **Llamadas por Mes y Tipo de Incidente (Ene 2021 - Ene 2023)**:
   - "Asalto común" y "Accidente de auto" son constantes con alrededor de 2500 llamadas mensuales.
   - "Narcóticos" y "Choque y correr" muestran aumentos y fluctuaciones.
   - "Asalto grave" es menos frecuente y tiende a la baja.
   - Aumento de incidentes durante el verano del hemisferio norte.

3. **Mapa de Calor de Llamadas por Distrito Sheriff**:
   - Los colores más oscuros indican más llamadas, con un pico notable en julio de 2022.
   - La cantidad de llamadas es relativamente constante, sin un distrito con un número significativamente mayor de llamadas.

4. **Mapa Geográfico de Llamadas por Barrio**:
   - Colores claros indican más llamadas, con un barrio central destacado con hasta 40,000 llamadas.
   - La mayoría de los barrios tienen menos llamadas (colores oscuros).

5. **Nombres de Barrios con Mayor Demanda de Llamadas**:
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
"""

# Escribir el contenido actualizado al archivo readme.md
with open("/mnt/data/readme.md", "w") as file:
    file.write(content)

"/mnt/data/readme.md"

![Header Image](assets/visual_readme.jpg)

# Madrid Accident Map 2024

This project aims to display an **interactive map** of accidents that occurred in the city of Madrid during the year 2024. Additionally, it includes visualizations and analysis of accident data to better understand the distribution and severity of accidents in the region.

## Description

The project consists of:
1. **Interactive Map**: An interactive map created with folium, which allows visualizing the location of the accidents. The accidents have been classified according to their severity (fatalities, injuries, and without medical assistance).
2. **Visualizations**: Graphs that show relevant statistics, such as:
- Number of accidents by district.
- Number of accidents by type of vehicle.
- Accidents with or without alcohol/drug consumption.
- Distribution of accidents by time of day.
- Accident frequency by day of the week.
- Ages of individuals involved in accidents.
- Accidents by weather conditions.


El propósito de este proyecto es facilitar el análisis de datos de accidentes y proporcionar una herramienta visual para explorar la distribución de los mismos en la ciudad.


## Requisitos

Para ejecutar este proyecto en tu entorno local, necesitas instalar las siguientes librerías de Python:

- `pandas`: Para la manipulación y análisis de datos.
- `numpy`: Para operaciones matemáticas y manejo de arrays.
- `folium`: Para la creación de mapas interactivos.
- `matplotlib`: Para la creación de gráficos.
- `seaborn`: Para la visualización avanzada de datos.
- `pyproj`: Para la conversión de coordenadas UTM a geográficas (latitud y longitud).


## Uso del Mapa Interactivo
El mapa permite interactuar con las diferentes categorías de accidentes, agrupadas por severidad:

Accidentes con Fallecidos: Marcadores en color rojo.
Accidentes con Heridos: Marcadores en color azul.
Accidentes sin Asistencia Sanitaria: Marcadores en color verde.
Puedes activar o desactivar la visualización de cada grupo usando el control de capas en la esquina superior derecha del mapa. Al hacer clic en cada marcador, se muestra información detallada sobre el accidente, como la fecha, hora, localización y tipo de accidente.

## Contribuciones
Si deseas contribuir a este proyecto, por favor sigue estos pasos:

Haz un fork del repositorio.
Crea una nueva rama (git checkout -b feature/nueva-funcionalidad).
Realiza tus cambios y haz commit (git commit -am 'Añadir nueva funcionalidad').
Envía los cambios a tu repositorio (git push origin feature/nueva-funcionalidad).
Crea un Pull Request y describe los cambios propuestos.
Licencia
Este proyecto está bajo la Licencia MIT. Consulta el archivo LICENSE para obtener más detalles.

## Puedes ver el mapa aqui:
https://nachojacquot.com/dataprojects/mapa_accidentes_madrid/mapa.html

## Contacto
Si tienes preguntas o sugerencias, no dudes en contactarme a través de fiodornac@gmail.com

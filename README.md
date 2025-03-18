# Descripción del Proyecto: Análisis del Comportamiento de Escucha de Música en Springfield y Shelbyville

## Introducción

El objetivo de este proyecto fue analizar el comportamiento de escucha de música basado en los datos de los usuarios de Springfield y Shelbyville. El análisis se centró en tres hipótesis relacionadas con la actividad de los usuarios a través de diferentes días de la semana, las preferencias por géneros musicales específicos al inicio y final de la semana, y las posibles diferencias en las preferencias de géneros entre las dos ciudades. Al examinar los datos de escucha, buscamos identificar tendencias y probar si factores como el día de la semana o las preferencias de género influencian los hábitos de escucha de música.

## Hipótesis

### Hipótesis 1: Niveles de Actividad por Día de la Semana
- Los niveles de actividad de los usuarios varían a lo largo de los días de la semana en Springfield y Shelbyville, mostrando picos y valles según el día.

### Hipótesis 2: Preferencias Musicales al Inicio y al Final de la Semana
- Los usuarios de Springfield y Shelbyville prefieren diferentes géneros musicales al inicio y al final de la semana, particularmente los lunes y viernes.

### Hipótesis 3: Preferencias de Género en Springfield y Shelbyville
- Los residentes de Shelbyville prefieren la música rap, mientras que los de Springfield prefieren la música pop.

## Descripción de los Datos

El conjunto de datos contiene la actividad de escucha de música de los usuarios de Springfield y Shelbyville, incluyendo:
- **ID del Usuario**: Identifica al oyente.
- **Canción**: La canción que se está reproduciendo.
- **Artista**: El artista que interpreta la canción.
- **Género**: El género de la música.
- **Ciudad**: La ciudad donde se encuentra el usuario.
- **Hora**: La hora exacta en que se reprodujo la canción.
- **Día**: El día de la semana en que se reprodujo la canción.

Los datos se dividieron en dos marcos de datos:
- `spr_general`: Datos de Springfield.
- `shel_general`: Datos de Shelbyville.

## Hallazgos Clave

### Hipótesis 1: Niveles de Actividad por Día de la Semana

#### Springfield:
- La actividad en Springfield alcanza su pico los **lunes** y **viernes**, lo que indica una mayor actividad de escucha de música al inicio y al final de la semana.
- Los **miércoles** presentan una caída significativa en la actividad de los usuarios.

#### Shelbyville:
- En Shelbyville, la actividad alcanza su pico los **miércoles**, con los **lunes** y **viernes** mostrando niveles más bajos de escucha.

### Hipótesis 2: Preferencias Musicales al Inicio y al Final de la Semana

Se analizaron los 15 géneros más populares para ambas ciudades durante:
1. **Lunes por la mañana (7:00 - 11:00)**
2. **Viernes por la noche (17:00 - 23:00)**

#### Hallazgos:
- **Springfield**: Pop, dance, electrónica, rock y hip-hop dominaron, aunque había muchos valores de género "desconocidos".
- **Shelbyville**: Pop, dance, rock y electrónica fueron los géneros más populares, con ligeras variaciones en los rankings.

#### Preferencias de Género:
- **Lunes por la mañana**: Ambas ciudades tuvieron preferencias similares, con el pop como el género principal.
- **Viernes por la noche**: El pop siguió siendo el género principal en ambas ciudades.

### Hipótesis 3: Preferencias de Género en Springfield y Shelbyville

Comparamos la frecuencia de preferencias de género entre las dos ciudades.

#### Hallazgos:
- **Springfield**: El pop fue el género más popular, seguido de dance, electrónica, rock y hip-hop.
- **Shelbyville**: El pop fue el género más popular, seguido de dance, rock y electrónica.
- No hubo una preferencia clara por la música **rap** en ninguna de las dos ciudades.

## Conclusión Final

### Resumen de los Hallazgos:
1. **Actividad de los Usuarios**: Los niveles de actividad en Springfield alcanzan su pico los lunes y viernes, mientras que en Shelbyville alcanza su pico los miércoles.
2. **Preferencias Musicales**: Ambas ciudades muestran una preferencia por la música pop, especialmente los lunes y viernes, aunque Springfield tuvo muchos valores faltantes.
3. **Preferencias de Género**: Ambas ciudades prefirieron la música pop, rechazando la hipótesis de que Springfield prefería pop mientras que Shelbyville prefería rap.

# Siniestralidad en las carreteras europeas

## Beatriz Alonso Casares

### Muertes en accidente de tráfico por millón de habitantes en la Unión Europea en 2020

En este mapa podemos ver las cifras oficiales de fallecidos en las carreteras, en 2020, en la Unión Europea, según los datos de la Comisión Europea. Las víctimas en este tipo de accidentes ascienden a **18.000 personas**. Según la entidad, el menor volumen de tráfico como consecuencia de la pandemia sanitaria ha tenido un impacto directo en esta bajada de la siniestralidad vial que se ha producido respecto a 2019.

**España** es el cuarto país que tuvo menos accidentes, en el año 2020, de la Unión Europea. puesto que en ese periodo se contabilizaron **29 accidentes por cada millón de habitantes**. Cerca de Suecia, el país con menos accidentes en el 2020, donde se produjeron 25 accidentes por millón de habitantes, quitándole el título a Islandia, país con menos accidentes en el año anterior. Un año más, el que más accidentes ha tenido ha sido Rumania, 117 por millón de habitantes.

![Muertes en accidente de tráfico por millón de habitantes en la Unión Europea en 2020](https://github.com/nebrijas/trabajos-nebrija-Beatriz-Alonso/blob/main/docs/img/mapaaccidentes.JPG)

~~~
<iframe title="Muertes en accidente de tráfico por millón de habitantes en la Unión Europea en 2020" aria-label="Mapa" id="datawrapper-chart-XXbwu" src="https://datawrapper.dwcdn.net/XXbwu/2/" scrolling="no" frameborder="0" style="width: 0; min-width: 100% !important; border: none;" height="686"></iframe><script type="text/javascript">!function(){"use strict";window.addEventListener("message",(function(e){if(void 0!==e.data["datawrapper-height"]){var t=document.querySelectorAll("iframe");for(var a in e.data["datawrapper-height"])for(var r=0;r<t.length;r++){if(t[r].contentWindow===e.source)t[r].style.height=e.data["datawrapper-height"][a]+"px"}}}))}();
</script> 
~~~

### Realización de la visualización

Para realizar esta visualización he descargado los datos en csv de la web de la [**Comisión Europea**](https://ec.europa.eu/commission/presscorner/detail/en/IP_21_1767) utilizando la herramienta Table Capture. 

Posteriormente, los he subido a Open Refine y he renombrado las columnas. El siguiente paso que he seguido ha sido realizar varias comprobaciones y comprobar que los datos medios de los países coincidían con la cifra total de la Unión Europea. Efectivamente, así es en 2020. En 2019 no coincidían, lo que imagino será porque en ese periodo estarán contabilizados los datos de Reino Unido. 

Por último, he realizado la representación de los datos en una visualización, seleccionando la opción de mapa en Datawrapper. Me he decantado por un mapa coroplético en el que se reflejan las víctimas mortales en accidentes de tráfico por millón de habitantes en la Unión Europea en 2020. 

Para una correcta visualización de los datos los he modificado en el formato predeterminado que requiere la web, por ello, me ha tocado cambiar el nombre de los países. Luego he modificado la leyenda, he incluido la escala y he añadido la unidad (víctimas mortales por millón de habitantes). Para finalizar, he decidido dejar visible el dato de fallecidos (un número de dos cifras) para reforzar la información de la escala de colores. 

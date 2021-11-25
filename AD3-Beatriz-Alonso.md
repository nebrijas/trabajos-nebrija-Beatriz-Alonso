# Creación de una visualización del proyecto TRESCA

## Beatriz Alonso Casares

### Gráfico de líneas

Para la visualización de estos datos he escogido un gráfico de líneas, en el que cada político estadounidense se representa con una línea y un color. En el eje horizontal he representado las fechas y en el vertical el volumen de tuits. Para hacer esta representación he tenido que realizar varias modificaciones previas en los datos. 

### Limpieza de los datos

Los principales cambios que he realizado en **Open Refine** han sido el cambio el nombre de las columnas y, posteriormente, he dividido la fecha en dos columnas creando una así una independiente para la hora. Por último, he creado una nueva columna en la que he clasificado los políticos según su partido. 

Para la organización de políticos por fecha y cantidad de tuits he realizado una tabla dinámica en excel en las filas son las fechas y las columnas los cuatro políticos. Los valores que he sumado son los tuits. De esta forma, los datos están agrupados mostrando en cada fecha la cantidad de tuits en los que se mencionó a cada político. 


![Tuits políticos estadounidenses](https://github.com/nebrijas/trabajos-nebrija-Beatriz-Alonso/blob/main/docs/img/tuitseeuu.png)

~~~
<iframe title="Tuits políticos estadounidenses" aria-label="Interactive line chart" id="datawrapper-chart-X9kFd" src="https://datawrapper.dwcdn.net/X9kFd/1/" scrolling="no" frameborder="0" style="width: 0; min-width: 100% !important; border: none;" height="400"></iframe><script type="text/javascript">!function(){"use strict";window.addEventListener("message",(function(e){if(void 0!==e.data["datawrapper-height"]){var t=document.querySelectorAll("iframe");for(var a in e.data["datawrapper-height"])for(var r=0;r<t.length;r++){if(t[r].contentWindow===e.source)t[r].style.height=e.data["datawrapper-height"][a]+"px"}}}))}();
</script>
 
~~~ 

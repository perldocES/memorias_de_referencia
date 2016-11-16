# Memorias de traducción de referencia - Perl
Este repositorio contiene memorias de traducción de proyectos de traducción y localización
al español relacionados con Perl que actualmente están inactivos. Estas memorias se pueden 
utilizar como referencia para consultar terminología o estilo, realizar experimentos de 
traducción automática, etc.

Memorias incluidas:

  * Padre
  * Kephra
  * Perltuts


El formato de las memorias es [TMX](https://www.gala-global.org/tmx-14b).

Para estos proyectos de traducción se utilizó la herramienta [OmegaT](http://www.omegat.org/),
que almacena los segmentos en cuatro archivos TMX distintos:

  * project\_save.tmx

    Contiene todos los segmentos registrados en la memoria desde el comienzo del proyecto.
    Su contenido está ordenado alfabéticamente por segmento original.
    A cada archivo project\_save.tmx le hemos agregado como prefijo el nombre de proyecto.

  * *nombre\_proyecto*-omegat.tmx

    Este archivo de OmegaT contiene etiquetas de formato específicas de OmegaT que permiten 
    usar el archivo en otros proyectos de OmegaT.

  * *nombre\_proyecto*-level1.tmx

    Contiene únicamente información textual.

  * *nombre\_proyecto*-level2.tmx

    Este archivo encapsula las etiquetas específicas de OmegaT en etiquetas TMX válidas de forma
    que se pueda utilizar el archivo con su información de formato en una herramienta de traducción
    compatible con la norma TMX de nivel 2 (o en OmegaT).
    
Los últimos tres archivos son copias (sin segmentos huérfanos) del archivo project\_save.tmx, 
la memoria de traducción principal del proyecto.



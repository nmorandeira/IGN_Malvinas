# Cómo representar a las Islas Malvinas en R y en QGIS
## Protocolos para usar el mapa base _Argenmap v2_ del Instituto Geográfico Nacional

Elaborado por Natalia Morandeira (3iA-UNSAM, CONICET; nmorandeira@unsam.edu.ar)

Publicado el 2 de agosto de 2020.

Actualizado el 13 de agosto de 2020 con archivos tipo para para páginas web (HTML Leaflet + Java + CSS), contribución de [José Mourglia](https://github.com/jmourglia) (Subsecretaría de Sistemas y Tecnologías de Información, Ministerio de Hacienda y Finanzas, Provincia de Corrientes).

### Documento completo
Para acceder al documento completo, ir a: <https://nmorandeira.netlify.app/es/post/2020-08-02-representar-islas-malvinas-en-r-y-qgis/>

### Citas sugeridas
- Para referirse a la discusión del documento se puede citar la [página web](<https://nmorandeira.netlify.app/es/post/2020-08-02-representar-islas-malvinas-en-r-y-qgis/>).

- Para referirse a los protocolos para R o QGIS se puede citar la versión 1.0.0. de este repositorio: 

Morandeira, NS. 2020. Uso de cartografía oficial del Instituto Geográfico Nacional para representar a las Islas Malvinas en R y QGIS. v.1.0.0. DOI: 10.5281/zenodo.3972477  

[![DOI](https://zenodo.org/badge/282126861.svg)](https://zenodo.org/badge/latestdoi/282126861)

- Para referirse al uso de Argenmap en HTML, referenciar el aporte específico de [José Mourglia](https://github.com/jmourglia) (jmourglia@gmail.com).


### A quiénes está dirigido
Este material está dirigido a todas aquellas personas que quieran hacer mapas en R o QGIS (dos entornos con software libre) y que entiendan del reclamo de Argentina de soberanía sobre las Islas Malvinas.

A su vez, el documento está dirigido a quienes ya conozcan el mapa base Argenmap v2 del Instituto Geográfico Nacional (IGN) y quieran promover su uso en R o QGIS.

Si bien no proveo una solución explícita para Python ni para otros softwares/lenguajes libres (*), invito a contribuir a quienes lo deseen: posiblemente algo de lo aquí documentado pueda ser de utilidad. Para páginas web en las que se use Leaflet, la solución documentada para R es válida. Por otro lado, en los softwares privativos de Sistemas de Información Geográfica muy probablemente podrá utilizarse la solución provista para QGIS, basada en XYZ tiles.

_(*) Edición del 13 de agosto de 2020:_ se incorporan archivos tipo para páginas web (HTML, Java y CSS), aporte de José Mourglia.

### Qué contiene este repositorio
Se provee:
- Documentación con una discusión sobre el problema de representación de las Islas Malvinas y la solución de visualización provista por Argenmaps v2 del IGN, con instrucciones para R y QGIS 3.xx. Esta documentación y script de RMarkdown está en los archivos IGN_Malvinas.rmd y su compilado IGN_Malvinas.html. El documento y tutorial completo se puede leer en el [artículo en la web](<https://nmorandeira.netlify.app/es/post/2020-08-02-representar-islas-malvinas-en-r-y-qgis/>).
- Tanto para R como para QGIS, un ejercicio tipo de visualización de dos capas vectoriales (Áreas protegidas de Argentina y Límites a la zona económica exclusiva), con un mapa base de fondo.
- Breve discusión sobre otro origen del problema: uso de datos vectoriales de fuentes no oficiales.
- Los [scripts de R (.Rmd)](https://github.com/nmorandeira/IGN_Malvinas/tree/master/R) con el ejemplo del ejercicio tipo.
- Un [proyecto de QGIS 3.14 (.qgz)](https://github.com/nmorandeira/IGN_Malvinas/tree/master/QGIS) con el ejemplo del ejercicio tipo.
- Archivos tipo para utilizar el mapa base de IGN en [páginas web: HTML-Leaflet, Java y CSS](https://github.com/nmorandeira/IGN_Malvinas/tree/master/HTML_jmourglia). El aporte fue realizado por José Mourglia @jmourglia. 

### Agradecimientos
El documento fue redactado en julio de 2020, con colaboración de *Malena Libman* (Geochicas OSM) que señaló por dónde iba la solución: usar como mapa base a Argenmap v2, un gran trabajo elaborado por el Instituto Geográfico Nacional (IGN) de la República Argentina.

Agradezco la importante contribución de *José Mourglia* (Subsecretaría de Sistemas y Tecnologías de Información, Ministerio de Hacienda y Finanzas, Provincia de Corrientes), quien aportó archivos tipo para desplegar el mapa base Argenmap v2 en páginas web (HTML + Java + CSS). 

Agradezco también a *Priscilla Minotti* por los comentarios que mejoraron el script de R y por sugerirme escribirlo en RMarkdown y publicarlo online, a *Yanina Bellini* por la ayuda para publicarlo en un sitio web y en general a *R-Ladies* (Buenos Aires, Santa Rosa y General Pico) por varios talleres y por la ayuda con Rmd y Git. Finalmente, agradezco a *Santiago Mouradian*, *Facundo Daelli* y *José Hernández* por los debates que mejoraron este documento.

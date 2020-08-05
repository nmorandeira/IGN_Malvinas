# Cómo representar a las Islas Malvinas en R y en QGIS
## Protocolos para usar el mapa base _Argenmap v2_ del Instituto Geográfico Nacional

Elaborado por Natalia Morandeira (3iA-UNSAM, CONICET; nmorandeira@unsam.edu.ar)

### Documento completo
Para acceder al documento completo, ir a: <https://nmorandeira.netlify.app/es/post/2020-08-02-representar-islas-malvinas-en-r-y-qgis/>

### Cita sugerida
Morandeira, NS. 2020. Uso de cartografía oficial del Instituto Geográfico Nacional para representar a las Islas Malvinas en R y QGIS. v.1.0.0. doi: DOI: 10.5281/zenodo.3972477  

[![DOI](https://zenodo.org/badge/282126861.svg)](https://zenodo.org/badge/latestdoi/282126861)


### A quiénes está dirigido
Este documento está dirigido a todas aquellas personas que quieran hacer mapas en R o QGIS (dos entornos con software libre) y que entiendan del reclamo de Argentina de soberanía sobre las Islas Malvinas.

A su vez, el documento está dirigido a quienes ya conozcan el mapa base Argenmap v2 del Instituto Geográfico Nacional y quieran promover su uso en R o QGIS.

Si bien no proveo una solución explícita para Python ni para otros softwares/lenguajes libres, invito a contribuir a quienes lo deseen: posiblemente algo de lo aquí documentado pueda ser de utilidad. Para páginas web en las que se use Leaflet, la solución documentada para R es válida. Por otro lado, en los softwares privativos de Sistemas de Información Geográfica muy probablemente podrá utilizarse la solución provista para QGIS, basada en XYZ tiles.

### Qué contiene este repositorio
Se provee:
- Documentación con una discusión sobre el problema de representación de las Islas Malvinas y la solución de visualización provista por Argenmaps v2 del IGN, con instrucciones para R y QGIS 3.xx. Esta documentación y script de RMarkdown está en los archivos IGN_Malvinas.rmd y su compilado IGN_Malvinas.html.
- Tanto para R como para QGIS, un ejercicio tipo de visualización de dos capas vectoriales (Áreas protegidas de Argentina y Límites a la zona económica exclusiva), con un mapa base de fondo.
- Breve discusión sobre otro origen del problema: uso de datos vectoriales de fuentes no oficiales.
- Los scripts de R (.Rmd) con el ejemplo del ejercicio tipo.
- Un proyecto de QGIS 3.14 (.qgz) con el ejemplo del ejercicio tipo.

### Agradecimientos
El documento fue redactado en julio de 2020, con colaboración de *Malena Libman* (Geochicas OSM) que señaló por dónde iba la solución: usar como mapa base a Argenmap v2, un gran trabajo elaborado por el Instituto Geográfico Nacional (IGN) de la República Argentina.

Agradezco también a *Priscilla Minotti* por los comentarios que mejoraron el script de R y por sugerirme escribirlo en RMarkdown y publicarlo online, a *Yanina Bellini* por la ayuda para publicarlo en un sitio web y en general a *R-Ladies* (Buenos Aires, Santa Rosa y General Pico) por varios talleres y por la ayuda con Rmd y Git. Finalmente, agradezco a *Santiago Mouradian*, *Facundo Daelli* y *José Hernández* por los debates que mejoraron este documento.

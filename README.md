# Cómo representar a las Islas Malvinas en R y en QGIS
## Protocolo para usar el mapa base _Argenmap v2_ del Instituto Geográfico Nacional

Elaborado por Natalia Morandeira (3iA-UNSAM, CONICET; nmorandeira@unsam.edu.ar) en julio de 2020.

## A quién está dirigido
Este protocolo está dirigido a todas aquellas personas que quieran hacer mapas en R o QGIS (dos entornos con software libre) utilizando un mapa base, y que entiendan del reclamo de Argentina de soberanía sobre las Islas Malvinas.

Si bien este documento no provee una solución explícita para Python ni para otros softwares/lenguajes libres, invito a contribuir a quienes lo deseen: posiblemente algo de lo aquí documentado pueda ser de utilidad. Por otro lado, en los softwares privativos de Sistemas de Información Geográfica muy probablemente podrá utilizarse la solución provista para QGIS, basada en XYZ tiles.

El protocolo fue redactado en julio de 2020, con colaboración de Malena Libman que señaló por dónde iba la solución: usar como mapa base a Argenmap v2, un gran trabajo elaborado por el Instituto Geográfico Nacional (IGN) de la República Argentina.

Se provee:
- Tanto para R como para QGIS, un ejercicio tipo de visualización de dos capas vectoriales (Áreas protegidas de Argentina y Límites a la zona económica exclusiva), con un mapa base de fondo.
- Documentación con una discusión sobre el problema de representación de las Islas Malvinas y la solución de visualización provista por Argenmaps v2 del IGN, con instrucciones para R y QGIS 3.xx. Esta documentación y script de RMarkdown está en los archivos IGN_Malvinas.rmd y su compilado IGN_Malvinas.html.
- Un proyecto de QGIS 3.14 (.qgz) con el ejemplo del ejercicio tipo.

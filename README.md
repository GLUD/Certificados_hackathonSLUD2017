# Certificados hackathon SLUD 2017

## DEPENDENCIAS

* python 2.7

* inkscape 0.91

## USO

El proceso se traduce en coger un SVG y abrirlo como texto, modificar el ID de algún contenedor de texto y guardar esa modificación. Los ID's tienen la forma "parametro_#" donde "#" puede ser 1, 2, 3, 4 ... n.

El más básico soporta el cambio de un contenedor de texto con el ID "parametro_1". Para usarlo bastaría con escribir el comando:

```bash
./SVGtoPDFfromCommaListValuesFile.py -t Certificado\ SLUD\ *.svg -l listfile

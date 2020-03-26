Herramienta de web scrapping para descargar todos los poligonos de https://geo.nyu.edu que contengan informacion administrativa

Para instalar todos los paquetes necesarios ejecutar pip install -r requirements.txt

es necesario instalar gdal en el sistema:

sudo apt-get install gdal (ubuntu)

sudo pacman -S gdal (Arch)


intrucciones:

python geonyu-scrapper.py get-description - retorna el archivo description.ods (país,nivel,tipo de datos)

python geonyu-scrapper.py get-polygons - descarga todos los poligonos como .kml en la carpeta KML 

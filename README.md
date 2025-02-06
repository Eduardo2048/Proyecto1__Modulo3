# Mi primer proyecto Android 
### Proyecto que soporte 4 idiomas Es-En-Fr-Ge 
Esto implica utilizar archivos strings_xx para los distintos idiomas.
### Que presente de fondo una imagen en un archivo nine-patch.
Se debe llevar un archivo *.png a *.9.png ajustando los límites de redimensionamiento
### Que permita ser visualizado en distintos tamaños y orientaciones de pantalla
Esto lleva a utilizar distintos layouts.

## Imagen de fondo.
Se copia la imagen como fondo.png
Se convierte a fondo.9.png
Se modifican los limites de redimensionamiento como se indican en las siguientes imágenes

![image](https://github.com/user-attachments/assets/24ac241f-3fcd-4a02-ac78-d66a65523f66)

![image](https://github.com/user-attachments/assets/8e859fcb-1bcb-45cd-8ca6-dc9bd63c0139)

## Manejo de idiomas.
Se generan cuatro archivos strings conteniendo la descripcion del texto de bienvenida y el boton en cada uno de los idiomas requeridos  

## distintos dispositivos
Se creo un layout para portrait y otro para landscape.
El tamaño del texto de bienvenida se dimensiona con una referencia al recurso dimen que tiene dimensiones para distintas pantallas.

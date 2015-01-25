# eneboo
Eneboo para probar de todo (manuales, extensiones, etc)
titulo1
#titulo2
##titulo3
###titulo4
####titulo5

#COMO COPIAR EL GITHUB EN EL ORDENADOR DE CASA
1. Cuando estas en una pagina de github, ABAJO-DERECHA hay un botón que pone "CLONE IN DESKTOP", entonces le das y empieza a DESCARGAR un ejecutable...
1. Aceptas el ejecutable y se instala.
1. Eliges un directorio de trabajo en el ordenador local
1. Una vez instalado vas a PROGRAMAS-GITHUB y le das a "GITHUB"....se abre una pantalla en blanco....
1. Vas ARRIBA-DERECHA a la rueda dentada y le das a "OPEN IN GIT SHELL", entonces se abre una ventana parecida al MSDOS de windows con unas letras en colores entre corchetes...
1. Escribes: "git clone https://github.com/(y aqui el nombre de la carpeta a copiar)"
 * NOTA: Para COPIAR-Y-PEGAR en la consola GIT-SHELL NO VALE el Ctrl+V, hay que hacerlo con el ratón (botón derecho)
1. Ejemplos: 
 * "git clone https://github.com/eneboo/doc.wiki.git" (texto plano)
 * "git clone https://github.com/eneboo/doc" (fotos-capturas de pantalla)
 * "git clone https://github.com/Miguel-J/eneboo" (este almacén)
 * ...y al darle a ENTER lo pone como subdirectorio en el directorio de descargas elegido...

##COMO INDEXAR UNAS INSTRUCCIONES-PASO-A-PASO
* ...visto que el cambio anterior me lo ha "enganchado" todo, vamos a probar borrando los números que he puesto y añadiendo "1. " delante de cada línea...
* .. y para "puntear" varias lineas ponemos delante: "* "
* OJO: Hay que añadir ESPACIOS DELANTE del "*" para separarlo de la alineación VERTICAL del "1. " porque si no lo interpreta igual que el "1. "

##COMO COORDINAR LA COPIA LOCAL Y LA DEL WEB GITHUB
1. Vas ARRIBA-DERECHA a la rueda dentada y le das a "OPEN IN GIT SHELL", entonces se abre una ventana parecida al MSDOS de windows con unas letras en colores entre corchetes...
2. Escribir: 
 * para "traer" a la copia local los cambios de la copia-"master" del servidor github ponemos: "git pull https://github.com/Miguel-J/eneboo"
 * OJO: El PULL hay que hacerlo DESDE EL DIRECTORIO DONDE QUIERES QUE DESCARGUE los archivos....si no es donde estás poner "cd (subdirectorio)" hasta situarse en el correcto...

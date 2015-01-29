Eneboo para probar de todo (manuales, extensiones, etc). Sobre todo para WINDOWS.
##INDICE
1. [Pagina principio de este repositorio](https://github.com/Miguel-J/eneboo)

1. [Pagina inicio de este wiki](https://github.com/Miguel-J/eneboo/wiki)

    A. [principio2](https://github.com/Miguel-J/eneboo)

####USUARIO:
1. [Primeros pasos-ABANQ](https://github.com/Miguel-J/eneboo/wiki/Primeros-pasos-(sacado-de-ABANQ))

####PROGRAMACION:
1. [Programación 1-ABANQ](https://github.com/Miguel-J/eneboo/wiki/Programaci%C3%B3n-1-(sacado-de-ABANQ))


##COMO COPIAR EL GITHUB EN EL ORDENADOR DE CASA
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
1. Para "TRAER" a la copia local los cambios de la copia-"master" del servidor github ponemos:
 * "git pull https://github.com/Miguel-J/eneboo"
 * OJO: El PULL hay que hacerlo DESDE EL DIRECTORIO DONDE QUIERES QUE DESCARGUE los archivos....si no es donde estás poner "cd (subdirectorio)" hasta situarse en el correcto...
1. Para "SUBIR" la copia local MODIFICADA a la copia-"master" del servidor github ponemos:
 1. Primero hay que decirle al programa quien somos...:
    * "git config user.mail "miguelajsmaps@gmail.com" "(o la cuenta email de cada uno)
    * "git config user.name "Miguel-J" "(o el nombre de usuario de cada uno)
 1. ...luego hay que decirle que hemos cambiado cosas de los archivos...:
    * "git commit -a" (esto solo vale si no hemos creado ningún archivo)
    * "git add (nombre del archivo)" (para cada archivo nuevo)
 1. ...y ahora hay que decirle que SUBA esos cambios:
    * "git push https://github.com/Miguel-J/eneboo master"
    * OJO: hay que añadir esa palabra "master" al final de la dirección para indicarle que el que manda es el del servidor...
    * Habrá que poner el USUARIO y PASSWORD de la cuenta propia en el GITHUB


## EL INDICE DE LA DERECHA
En la parte superior derecha de cada página verás un índice que nos permite acceder directamente a cada una de ellas. Este índice no se genera de forma automática, sino que hay que editarlo.

Podemos hacerlo cuando pulsamos el botón _Edit Page_. Iremos al final de la página y pulsaremos en la flecha hacia abajo que hay junto _Sidebar_. Ahí podemos añadir o modificar los enlaces del índice como hemos explicado en la sección [La barra de botones de edición](#la-barra-de-botones-de-edici%C3%B3n) para el caso de enlaces a páginas del mismo wiki.

**Nota:** Cuando crees una página nueva verás que no aparece el índice. Esto es porque el wiki por defecto crea la página en el directorio raíz del repositorio del wiki, donde no le afecta el archivo _Sidebar.md que contiene el índice, ya que este archivo está en el directorio _standard_. Para que se muestre el índice debes hacer lo siguiente:

1. Bájate con _git_ el repositorio del wiki ejecutando:
 * "git clone https://github.com/eneboo/doc.wiki.git"
1. Mueve la página al directorio _standard_ con:
 * "git mv \[Eneboo-Standard\]-Nombre-de-la-pagina.md standard/"
1. Haz _commit_ y _push_.

Si tienes problemas para hacer esto coméntalo en el [foro](https://groups.google.com/forum/#!forum/eneboo), te echaremos una mano.

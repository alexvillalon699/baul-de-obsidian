[[git]]
working directory
staging area
repository

___

git init, crear un prioyecto nuevo, o para decirle que comienzas a trabajar en uno

git add para pasarlos al staging area


git commit pasar al repositorio (snapshot)

git push para subirlo a un repositorio remoto

git pull para traer los cambios que han hecho los desarrolladores

git clone hacer una copia del proyecto en tu computadora

____

git init
	crea la carpeta .git donde guarda los datos del proyecto git, no se debe tocar

git status
	para ver que archivos estamos trabajando
	aparecen archivos en rojo, pues no se han agregado al stagin area (area de trabajo)

git add (nombre del archivo a agregar) #fazt01012018 19:00


git add .           todos los archivos con subdirectorios 

git commit  pasar los archivos al staging
te manda al editor vin, hay que tipear i para comenzar a escribir escribimos el comentario del snapshot y damos escape :wq para guardar

got commit -m "he agregado algo" pasa los archivos al staging, pero ya con mensaje, ya no me manda al vin

solo la primera vez
	git config --global user.email "alexvillalon699@gmail.com"     configurar el email del usuario que hace los cambios para todo este sistema operativo
	git config --global user.name "alex"

git log me da los datos del snapshot

abrimos github
en el dashboard
new
nombre del repositorio
comentario
publico
create repository

copiar la sexta linea del codigo
git remote add origin https://github.com/alexvillalon699/baul-de-obsidian.git
#developeando120722 como usar github lo que necesitas saber
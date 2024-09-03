# HACK - GIT 2 

##### ### ## ENVIAR UN DIRECTORIO VACIO AL REPOSITORIO REMOTO.

Se crea un nuevo repositorio en github nombre: git_h_2

Crear un repositorio local

-git init

-Registrar el repositorio remoto con tú repositorio local

-git remote add origin (pegar_la_ruta_del_repositorio_local)

-Verificamos la ruta remota

-git remote -v

-Crear 1 carpeta ó directorio con el nombre de "usuarios"

-mkdir usuarios

-Verificar la creación del directorio
-ls -l

-Ahora si haces un status del stage
-git status

-La carpeta no aparece en el stage, es decir la vez creada, pero en git es como que no la reconoce, esto es debido a que git no hace seguimiento a directorios vacios.

En este momento es necesario elaborar un archivo interno en el directorio "usuarios", pero si por los momentos no queremos agregar nada en ella, pero si tenerla en nuestro repositorio debemos crear un archivo oculto dentro del directorio.

-cd usuarios

-touch .gitkeep

-cd ..

-ls -l

-Examinamos el stage y debemos ver la carpeta ó directorio usuarios disponible para el tracking

-git status

-Agregamos el directorio al stage

-git add .

-Se realiza el commit

-git commit -m "feat: add directory usuarios"

-Verificamos el commit
-git log --oneline

-Crear el ambiente main

-git branch -M main

-Hacer push

-git push -u origin main

-Toca ir al repositorio remoto y ver la carpeta en nuestro repo

En este paso ya habra acabado el repositorio.


##  FIN.




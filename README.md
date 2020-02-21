Repositorio sisinformaticos
	1.Crear un repositorio en vuestro GitHub llamado sisinformaticos.
		Creamos un repositorio en nuestro perfil.
	2.Clonar vuestro repositio en local.
		git clone https://github.com/davidantoniol/sisinformaticos-2.git
README
	1.Crear (si no lo habéis creado ya) en vuestro repositorio local un documento README.md.
		touch README.md

Commit inicial
	1.Añadir al README.md los comanddos utilizados hasta ahora y hacer un coomit inicial con el mensaje commit inicial.
		git add README.md
		git commit -m "commit inicial"
Push inicial
	1.Subir los cambios al repositorio remoto.
		git push -u origin master
Ignorar archivos
	1.Crear en el repositorio local un fichero llamado privado.txt.
		touch privado.txt
	2.Crear en el repositorio local una carpeta llamada privada.
		mkdir privada
	3.Realizar los cambios oportunos para que tanto el archivo como la carpeta sean ignorados por git.
		touch .gitignore
		dentro de este archivo ponemos el nombre del archivo que queramos
		git add .gitignore
		git commit -m "git ignore"
Añadir fichero 1.txt
	1.Añadir fichero 1.txt al repositorio local.
		touch 1.txt
Crear el tag v0.1
	1.Crear un tag v0.1.
		git tag -a v0.1 -m "v0.1"
		para ver si esta subido git tab
Subir el tag v0.1
	1.Subir los cambios al repositorio remoto.
	git add .
	git push -u origin master
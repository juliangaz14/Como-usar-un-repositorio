Datos:
- El repositorio se crea y se elimina solamente en GitHub.
- Rama main o principal
- Rama Master o de origen es cuando realizamos el proyecto de raiz por remoto, cuando conectas por primera vez el proyecto
en el repositorio. Cuando agregas con "git remote add origin y el enlace".
Puedo crear ramas nuevas para trabajar de manera paralela. Y si creo ramas nuevas, ahi si uno puede usar "git push" y no
"git push origin master".
- Para poder descargar el proyecto de otro lo que tenemos que hacer es ir a "code", copiar el enlace del proyecto, ir
a la consola de "git", en la consola ir al directorio o carpeta donde queremos descargar el proyecto, poner el comando
"git clone y pegar el enlace del proyecto" y asi descargamos todo el proyecto.

Comandos:

git init (para inicializar git en el proyecto)

git remote add origin y el enlace que copias del repo (es para conectar el proyecto
de la compu con GitHub)

git add . (si quiero registrar o mandar todo los archivos al repositorio, la cual, no es recomendable si no estas seguro
de todo lo que hiciste o si tenes archivos a medio hacer).

git add "cualquier archivo" (para agregar cualquier archivo en especifico, registrar lo que quiero enviar como
actualizacion al repo desde PC)

git status (para saber que archivos registré con el git add [para ser eventualmente pusheadas]). Si yo registro una carpeta
o archivo para despues commitear,cuando ponga"git status" me lo va a registrar en color verde. Si yo despues de registrar,
creo otra carpeta o archivo y vuelvo a poner "git status" sin antes registrarlo con "git add ""...", me va a aparecer el
archivo en color rojo como "untracked file" sin quedar registrado para luego commitear.

git clone (te permite clonar caulquier proyecto que esta en un repositorio a tu PC y te bajas todo el proyecto). Ahora, si 
ya tenes el proyecto descargado y queres descargarte nuevos cambios, ahi se utiliza otro comando.

git commit -m "titulo" (es para confirmar el archivo que está listo para ser empujado a nuestro repositorio o para
guardar version segura [backup])

git push (es para empujar o impulsar las modificaciones o nuevos cambios al repositorio
que no van a una rama de origen, es decir, una vez que commiteas un archivo, luego debemos poner el comando "git push"
para que aparezca en el repositorio. Sino, no aparece).
Como ahora estamos trabajando con la rama master de origen, no alcanza solo con "git push". Esto es para cualquier rama
que no es la de origen. En la rama git push de origen, tenemos que poner el comando "git push origin master" siendo 
"master" nuestro nombre de la rama.

git push origin master (se utiliza para empujar archivos solamente con la rama de origen).

git pull (sirve para poder descargar los cambios que hace otro usuario o compañero si estoy trabajando en un proyecto
en comun, sino, no voy a poder ver los cambios que realiza mi compañero con su "git push").

git clone y pegamos el enlace (es para clonar y descargar todo el proyecto que querramos. Lo usamos en la consola Git).

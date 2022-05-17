# CURSO DE GIT (FAZT)

## <center> En **GIT** hay 3 estados </center>

1. *Working directory*
    * Es donde se trabaja con los acrhivos.
2. *Staging area*
    * Es donde se agregan los archivos que se preparan para el guardado.
3. *Repositoriy*
    * Cuando los cambios están listos para guardarse.

## <center> Comandos basicos de **GIT** </center>

* **git init**
    * Es como indicar "Voy a empezar a usar git en este proyecto".
* **git add nombreDelArchivo o un "."**
    * Es para pasar los archivos del **working directory** al **staging area**.
    * El punto es para agregar todos los archivos, en lugar de añadirlos de uno en uno.
* **git commit**
    * Es para pasar del **staging area** al **repository**. (Como crear el primer "Snapshot")
* **git push**
    * Para subirlo al repositorio remoto.
* **git pull**
    * Traes los cambios que han hecho otros desarrolladores.
* **git clone**
    * Crea una copia desde el servidor central a la computadora local para poder trabajar con el.

## <center> Para corroborar cambios y estados </center>
* **git status**
    * Es para ver en que estado se encuentran los archivos actualmente.
* **git checkout -- nombreDelArchivoModificado**
    * Para revertir los cambios de un archivo recientemente modificado.
* **git diff nombreDelArchivo**
    * Para ver los cambios recientes del documento.
* **git log**
    * Para mostrar en lista el historial de commits hechos.

> *consulta el libro en git-scm.com para mas información* :smile:

## <center> Comandos de ramas </center>

* **git branch**
    * Para corroborar las ramas existentes.
* **git branch nombreDeRama**
    * Para crear una rama nueva con el nombre escrito luego del comando.
* **git checkout nombreDeRama**
    * Para entrar a la rama con el nombre escrito luego del comando.


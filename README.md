# Speaking Hands
soy dios automatizando ( Manuel)

# How to Create Speaking Hands Conda Enviroment

## Via Anaconda Navigator Launcher

* Paso 1. Abrir Anaconda Navigator
* Paso 2. Pestaña Enviroments
* Paso 3. En la lista de Enviroments click en create
* Paso 4. Crear 'SpeakingHands' con python 3.9.16

## Via Terminal

* Paso 1. Abre la terminal o línea de comandos en tu sistema operativo.
* Paso 2. Ejecuta el siguiente comando para crear el entorno con el nombre SpeakingHands y Python 3.9.16: `conda create -n SpeakingHands python=3.9`
* Paso 3. Después de crear el entorno, activa el entorno SpeakingHands con el siguiente comando:
  * Windows: `conda activate SpeakingHands`
  * Linux/Mac: `source activate SpeakingHands`

# Install Libraries

* Paso 1. Comprobar si `requirements.txt` e `imagen.jpeg` se encuentran en la ventana *SHARED*  del one drive de la ucm. En caso de no tener el onedrive conectado al pc, descargarlos.
* Paso 2. En anaconda navigator, clickar en el botón `play` del enviroment `SpeakingHands` y abrir el terminal
* Paso 3. En el terminal, escribir:
    * En Mac: si tenemos los archivos en el onedrive: `pip install -r /Users/{usuario}/Library/CloudStorage/OneDrive-UniversidadComplutensedeMadrid\(UCM\)/SHARED/requirements.txt`. Reemplazar `{usuario}` por vuestro usuario. En caso de no tener reemplazar por la ruta correspondiente
    * En Windows: 


> En caso de no tener `pip`, instalar.

**Para comprobar si se han descargado correctamente, ejecutar el archivo `requirementsCOMPROBACION.ipynb`.**




  

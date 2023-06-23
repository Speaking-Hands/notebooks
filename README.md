# Speaking Hands

## Onboarding - Prepare environment

### How to Create SpeakingHands Conda Enviroment

#### Via Anaconda Navigator Launcher

1. Abrir Anaconda Navigator
2. Pestaña Enviroments
3. En la lista de Enviroments click en create
4. Crear **SpeakingHands** con python 3.9.16

#### Via Terminal

1. Abre la terminal o línea de comandos en tu sistema operativo.
2. Ejecuta el siguiente comando para crear el entorno con el nombre SpeakingHands y Python 3.9.16: `conda create -n SpeakingHands python=3.9.16`
3. Después de crear el entorno, activa el entorno SpeakingHands con el siguiente comando:
   * Windows: `conda activate SpeakingHands`
   * Linux/Mac: `source activate SpeakingHands`

### Install Libraries

1. En anaconda navigator, clickar en el botón `play` del enviroment `SpeakingHands` y abrir el terminal
2. En el terminal, escribir `pip install -r requirements.txt` desde la carpeta del proyecto.

> En caso de no tener `pip`, instalar.

### Check installation

Para comprobar si se han descargado correctamente, ejecutar el archivo `requirements_comprobacion.ipynb`

## Useful links

### Review changes in notebook

- [reviewnb](https://app.reviewnb.com/AngelEscudero4/TFM_speaking-hands/)

### Data
- [Google - American Sign Language Fingerspelling Recognition
](https://www.kaggle.com/competitions/asl-fingerspelling/overview)
- [Google - Isolated Sign Language Recognition
](https://www.kaggle.com/competitions/asl-signs/overview)
- [ASLFR - Prepocessing Dataset](https://www.kaggle.com/datasets/markwijkhuizen/aslfr-preprocessing-dataset)

### Notebooks
- [EDA](https://www.kaggle.com/code/mahakpreetkaurvirdi/american-sign-language-recognition-eda)
- [ASLFR - Transformer Training + Inference](https://www.kaggle.com/code/markwijkhuizen/aslfr-transformer-training-inference)
- [(TOP) EDA + ASLFR - Animated visualization](https://www.kaggle.com/code/leonidkulyk/eda-aslfr-animated-visualization)
- [Understanding the Competition | ASL](https://www.kaggle.com/code/ayushs9020/understanding-the-competition-asl)

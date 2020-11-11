# Machine Learning Practico Grupo 5 - Edición Noviembre 2020

Grupo de trabajo del curso "Machine Learning Práctico", en su edición de Noviembre 2020.

## Integrantes

- [Leonardo U. Spairani](https://github.com/LUS24)

## Recursos generales

- [Web del curso](https://elsonidoq.github.io/machine-learning-practico/)
- Tutorial de [Git](https://rogerdudler.github.io/git-guide/index.es.html)
- Tutorial de [GitHub](https://guides.github.com/activities/hello-world/)
- Pequeño tutorial de [Markdown](https://guides.github.com/features/mastering-markdown/) para manejarse en github cómodamente

## Setup (configuración inicial) PYTHON

### Instalar python

Para windows: [descargar el instalador](https://www.python.org/) y asegurarse de poner el ejecutable en el PATH

### Configuración de entorno de trabajo LOCAL usando pip

#### 1. Crear entorno virtual

1.1. Instalar el paquete para crear entornos virtuales (yo uso este pero hay otros)

```pip install virtualenv```

1.2. Crear el entorno virtual

```virtualenv venv```

1.3. Iniciar el entorno virtual

```virtualenv venv```

#### 2. Instalar librerías para trabajar

De acuerdo a lo visto en clase las librerías hasta el momento son:

Esenciales:

- [numpy](https://numpy.org/)
- [pandas](https://pandas.pydata.org/)
- [scikit-learn](https://scikit-learn.org/stable/)

Opcionales:

- [juptyerlab](https://jupyter.org/): para poder ejecutar el código de python paso por paso
- [seaborn](https://seaborn.pydata.org/index.html): para gráficos mas bonitos


Instalar librerías

```bash
pip install numpy pandas scikit-learn juptyerlab seaborn
```

o desde el archivo `requirements.txt`

```bash
pip install -r requirements.txt
```

#### 3. Iniciar jupyter lab para comenzar a trabajar

```bash
jupyter lab
```

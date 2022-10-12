# Desafio LATAM

![badge1](https://img.shields.io/badge/language-Python-blue.svg)

## Predicción de la probabilidad de atraso de un vuelo con origen Santiago de Chile

Este desafío consiste en predecir la probabilidad de atraso de un vuelo con origen Santiago de Chile y múltiples destinos.
Para mayor información, ver detalles del desafío en el documento [Challenge](https://github.com/jdpinedaj/desafio_latam/blob/master/document/Challenge%20-%20Data%20Scientist.pdf).

## Setup

### Windows setup

- Descarga Python de https://www.python.org/, se recomienda usar una de las versiones más estables (3.7.3, 3.8.10, 3.9.5), click [aquí](https://www.python.org/ftp/python/3.9.5/python-3.9.5-amd64.exe) para descargar.
- Ejecute el archivo .exe

  ![install-1](./readme-resources/python_install_1.png)

- Dale click a `Add Python 3.9 to PATH` y luego a `Install Now`
- Cuando la instalación termine correctamente, deberás ver la siguiente pantalla:

  ![install-2](./readme-resources/python_install_2.png)

- Abra una ventana de PowerShell y presione `Shift + right click` en cualquier carpeta o la pantalla de escritorio.

  ![install-3](./readme-resources/python_install_3.png)

- Si escribe `python -V` en la consola, deberás ver la siguiente salida:

  ![install-4](./readme-resources/python_install_4.png)

- Instala pipenv que es necesario para crear virtual environments, más información [aquí](https://pipenv.pypa.io/en/latest/) escribiendo `pip install pipenv` en la consola.

### Project Setup

- Descarga el repositorio usando git o como un archivo zip como se muestra a continuación:
  - Alternativa 1: git: si estás familiarizado con git, simplemente copia el https path aquí y en powershell corre `git clone https://github.com/jdpinedaj/desafio_latam.git`. Puedes leer más sobre git [aquí](https://git-scm.com/).
  - Alternativa 2: zip: Simplemente dale click a `Download ZIP` y descomprime los archivos.

![project-setup-1](./readme-resources/project_setup_1.png)

- Abre una consola en la raíz del proyecto, y corre:
  - `pipenv shell`
  - `pipenv install`

### 2. Correr la solución

Para ver la solución, debes revisar el siguiente [jupyter notebook](https://github.com/jdpinedaj/desafio_latam/tree/master/notebooks)

### 3. GitHub Actions

Si estás familiarizado con GitHub Actions, puedes triggear la ejecucion del jupyter desde Actions (actualmente está configurado para que se ejecute una vez mensual). Este procedimiento correrá nuevamente el notebook y guardará una nueva versión del modelo en el repositorio.

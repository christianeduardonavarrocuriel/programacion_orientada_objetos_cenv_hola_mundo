# Ejemplos de Programación Orientada a Objetos

## 1. Crear el archivo **.gitignore**
Se crea el archivo **.gitignore** para configurar los archivos que no se sincronizarán con el repositorio

````shell
* .pyc
_pycache_/
.venv/
````


## 2. Crear el **Virtual environment**

Se crea el ambiente virtual de trabajo de python

````shell
python3 -m venv .venv
````


## 3. Iniciar el **Virtual Environment** para instalar las librerias necesarias para el proyecto

````shell
source .venv/bin/activate
````

## 4. Actualizar **pip** dentro del **Virtual Environment**

Se actualiza la versión instalada de **pip** para poder descargar las ultimas versiones de las librerias

````shell
pip install --upgrade pip
````

## 5. Verificar las librerias instaladas

Se verifica que librerias y versiones se tienen instaladas

````shell
pip freeze
````

## 6. Instalar librerias

Se instalan las librerias que se van a ocupar

````shell
pip install web.py
````

## 7. Crear el archivo **requirements.txt**

Se crea el archivo **requirements.txt** con las librerias y el número de versión utilizadas.

````shell
pip freeze > requirements.txt
````

## 8. Crear el archivo **runtime.txt**

Se crea el archivo **runtime.txt** con la versión de Python3 que se esta utilizando en el proyecto

````shell
python3 -V > runtime.txt
````

## 9. Indexar los archivos creados con **git**

Se indexan los archivos y cambios realizados en el proyecto

````shell
git add .
````
## 10. Generar un **commit**

Se realiza un **commit** con un texto que describa los cambios realizados en el proyecto

````shell
git commit -m "CREATED configuracion basica"
````

## 11. Realizar un **push**

Se realiza un **push** para subir los cambios realizados al repositorio de **Github**

````shell
git push -u origin main
````

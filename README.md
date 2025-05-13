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
sorce .venv/bin/activate
````

## 4. Aztualizar **pip** dentro del **Virtual Environment**

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


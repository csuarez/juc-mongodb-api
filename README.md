# juc-mongodb-api

API creada para las **II Jornadas Técnicas UEx – CIEMAT. Introducción a NoSQL con MongoDB**. Versión completa de [csuarez/juc-mongodb-api-template](https://github.com/csuarez/juc-mongodb-api-template).

## Instalación

1. Instalando dependencias
  ```sh
  sudo apt-get install git python-dev python-pip
  sudo pip install pymongo Flask
  ```

2. Bajamos la plantilla
  ```sh
  git clone https://github.com/csuarez/juc-mongodb-api-template.git
  ```

3. Añadimos datos de prueba
  ```
  mongoimport --db shop --collection catalog --file catalog.json --host 0.0.0.0
  ```

4. Arrancamos la API
  ```sh
  python api.py
  ```

**NOTA**: El servicio se levanta en el puerto `443`.

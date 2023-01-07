# python-flask-mysql-CRUD

En este proyecto se tiene un CRUD funcional con interfaz grafica, en donde se pueden generar usuarios, modificar y eliminarlos.

# Paso para implementarlo

Clone el repositorio:
```sh
git clone https://github.com/ec4m/python-flask-mysql-CRUD.git
```

Creé y encienda el ambiente virtual (venv):
```sh
python3 -m venv env
source env/bin/activate
```

Instalar dependencias desde el archivo requirements.txt
```sh
pip3 install -r requirements.txt
```

Generé una base de datos en MySql por medio de PhpMyAdmin llamada 'users' con los campos:
```
id       | smallint - auto incremento
username | varchar(100)
name     | varchar(100)
password | varchar(300)
```

Ejecute la aplicación desde Vscode o con el comando:
```sh
python3 src/app.py
```
Ingrese al link: http://localhost:4000/ para visualizar el funcionamiendo de la aplicación.
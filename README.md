# python-final 

Hoy vamos a hacer actividad en Python en un día como programadores:

1. Abrir la terminal de Git Bash o terminal en Linux, debe ser como administrador en Window

2. Creamos una carpeta o directorio:
   
```bash
mkdir python-final
```

3. Entramos en ella:

```bash
cd python-final
```

4. Iniciamos el repositorio:

```bash
git init
```

5. Creamos un archivo:
   
```bash
touch finales.py
```

6. Abrimos VSC:

```bash
code .
```

7. En terminal ingresamos el comando para saber la versión de Python que tenemos instalada:
   
```bash
python -V
```

```bash
python3 -V
```


8. Creamos el entorno virtual en Python:

```bash
python3 -m venv venv
```

9. Activamos el entorno virtual:

```bash
source venv/bin/activate #Activamos el entorno virtual en Linux
```

```bash
venv/scripts/activate #En windows
```

10. Hacemos actualización del pip de Python

```bash
python3 -m pip install --upgrade pip #Actualizamos el pip
```

11. Investigar ¿Qué es el pip y porque lo actualizamos?

    Pip es un sistema de gestión de paquetes utilizado para instalar y administrar paquetes de software escritos en Python. Muchos paquetes pueden ser encontrados en el Python Package Index (PyPI). Python 2.7.9 y posteriores (en la serie Python2), Python 3.4 y posteriores incluyen pip (pip3 para Python3) por defecto.

13. Hacer al primer commit de este trabajo y unirlo al repositorio remoto.

14. Enviar el enlace del repositorio remoto donde tiene que tener un README.md con todos los detalles de lo que les fui mostrando en comandos, y las respuesta del punto 11 de más arriba.

# python-final

Actividad clase 11
Hoy vamos a hacer actividad en Python en un día como programadores:
1. Abrir la terminal de Git Bash o terminal en Linux, debe ser como administrador en Window
2. Creamos una carpeta o directorio: 
**mkdir python-final**
3. Entramos en ella: 
**cd python-final**
4. Iniciamos el repositorio:
**git init**
5. Creamos un archivo:
**touch finales.py**
6. Abrimos VSC:
**code .**
7. En terminal ingresamos el comando para saber la versión de Python que tenemos instalada:
**python -V**
**python3 -V**
8. Creamos el entorno virtual en Python:
**python3 -m venv venv**  #Creamos el entorno virtual
9. Activamos el entorno virtual:
**source venv/bin/activate** #Activamos el entorno virtual en Linux
**venv/scripts/activate** #En windows
10. Hacemos actualización del pip de Python
**python -m pip install --upgrade pip** #Actualizamos el pip
11. Investigar ¿Qué es el pip y porque lo actualizamos?
12. Hacer al primer commit de este trabajo y unirlo al repositorio remoto.
13. Enviar el enlace del repositorio remoto donde tiene que tener un README.md con todos los detalles de lo que les fui mostrando en comandos, y las respuesta del punto 11 de más arriba.
# Actividad del punto 11
Pip es el gestor de paquetes de Python, utilizado para instalar y gestionar bibliotecas y dependencias que no forman parte de la biblioteca estándar de Python. 
El nombre "pip" es un acrónimo recursivo que significa "Pip Installs Packages".

Funciones principales de pip:
Instalación de paquetes: Puedes instalar paquetes desde el Python Package Index (PyPI) y otras fuentes.

pip install nombre_paquete

Actualización de paquetes: Puedes actualizar paquetes instalados a sus versiones más recientes.

pip install --upgrade nombre_paquete

Desinstalación de paquetes: Puedes desinstalar paquetes que ya no necesitas.

pip uninstall nombre_paquete

Listar paquetes instalados: Puedes ver una lista de todos los paquetes instalados y sus versiones.

pip list
Gestión de dependencias: Pip puede manejar las dependencias de los paquetes, instalando automáticamente cualquier biblioteca requerida por los paquetes que estás instalando.

¿Por qué actualizamos pip?
Seguridad: Las versiones más recientes de pip pueden contener parches de seguridad que corrigen vulnerabilidades encontradas en versiones anteriores.
Nuevas funcionalidades: Las actualizaciones de pip pueden incluir nuevas características y mejoras que hacen que el gestor de paquetes sea más fácil de usar o más eficiente.
Corrección de errores: Las versiones nuevas de pip corrigen errores que pueden haber existido en versiones anteriores, mejorando la estabilidad y el rendimiento.
Compatibilidad: Actualizar pip asegura que sea compatible con las versiones más recientes de Python y con los paquetes que estás utilizando.
Para actualizar pip a su versión más reciente, puedes usar el siguiente comando:

pip install --upgrade pip

Este comando descarga e instala la versión más reciente de pip desde PyPI. Es una buena práctica mantener pip actualizado 
para aprovechar las últimas mejoras y mantener tu entorno de desarrollo seguro y eficiente.

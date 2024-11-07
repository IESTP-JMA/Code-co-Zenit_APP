# PASOS PARA CREAR UNA CARPETA PARA MI PROYECTO
📗 Abre Git Bash y navega hasta la ubicación donde deseas crear tu proyecto.
Utiliza el comando mkdir para crear una nueva carpeta:


**mkdir mi-proyecto**

📗Inicializa un repositorio Git:
Navega dentro de la carpeta de tu proyecto:


**cd mi-proyecto**

📗Inicializa un repositorio Git:

**git init**



📗Utiliza el comando touch para crear los archivos que necesitas para tu proyecto. Por ejemplo, para crear un archivo llamado main.py:


**touch main.py**

📗Puedes crear varios archivos al mismo tiempo separando los nombres con espacios:


**touch archivo1.txt archivo2.js archivo3.css**

📗Agrega los archivos al repositorio:
Utiliza el comando git add para agregar los archivos que has creado al repositorio:


**git add.**

Esto agregará todos los archivos de la carpeta actual al repositorio.

📗 Si solo deseas agregar un archivo específico, puedes usar el nombre del archivo en lugar de .:


**git add main.py**


📗Utiliza el comando git commit para confirmar los cambios que has realizado:


**git commit -m "Mensaje de confirmación"**

📗Reemplaza "Mensaje de confirmación" con una descripción breve de los cambios que has realizado.


**git remote add origin url del repositorio remoto**

Reemplaza <url del repositorio remoto> con la URL del repositorio que has creado.

📗Envía los cambios al repositorio remoto:
Utiliza el comando git push para enviar los cambios al repositorio remoto:

**git push origin main**
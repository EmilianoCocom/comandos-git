## Comandos git
Git es un sistema de control de versiones

**git --version** : muestra la versión de git que tenemos instalado 

![IMG-1](/images/IMG-1.png "git version")

**git help** : nos da una ayuda sobre los comandos de git

![IMG-2](/images/IMG-2.png "git help")

**git help commit** : en las versiones más recientes de git, en el sistema operativo windows, abre en el navegador el manual, del comando del cual hemos solicitado la ayuda

![IMG-3](/images/IMG-3.png "git help commit")

![IMG-4](/images/IMG-4.png "navegador")

**git config --global user.name "Nombre de usuario"** : con este comando le decimos a git, quien somos

![IMG-5](/images/IMG-5.png "config user name")

**git config --global user.email "Email de la cuenta de Github"** : debemos tener una cuenta de github u otro servicio de la nube, para almacenar repositorios, es el correo que debemos ingresar de preferencia

![IMG-6](/images/IMG-6.png "config user email")

**git config --global -e** : muestra la configuración del usuario y alias si existen, para salir de la vista se utiliza < :q! > o para escribir y salir < :wq! >

![IMG-7](/images/IMG-7.png "view config")

![IMG-8](/images/IMG-8.png "view config")

**git init** : inicializa el repositorio

![IMG-9](/images/IMG-9.png "git init")

**git status** : muestra el status de los archivos que tienen o no seguimiento y cambios

![IMG-10](/images/IMG-10.png "git status")

**git add nombre_del_archivo** : agregar un archivo, para ser versionado

![IMG-11](/images/IMG-11.png "git add")

**git add .** : agrega todos los archivos para que sean versionados

![IMG-12](/images/IMG-12.png "git add .")

**git reset nombre_del_archivo** : sirve para quitar del stage, un archivo que no queramos versionar

![IMG-13](/images/IMG-13.png "git reset")

**git commit -m "mensaje para identificar cambios"** : se utiliza para confirmar cambios

![IMG-14](/images/IMG-14.png "git commit")

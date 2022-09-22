# **Git Cheat-Sheet**

## <center>**Indice**

1. ¿Que es Git?
2. Configuracion inicial
3. Inicializacion 
4. Area de preparacion
5. Inspeccionar
6. Compartir y actualizar

## **¿Que es Git?**
Git es el sistema de control de versiones distribuido gratuito y de código abierto que es responsable de todo GitHub
relacionado que ocurre localmente en su computadora. Esta hoja de trucos presenta los más importantes y comúnmente
usó comandos de Git para una fácil referencia.

## **Configuración**
Configuración de la información del usuario utilizada en todos los repositorios locales
~~~
git config --global user.name “[firstname lastname]”
Establece el nombre con el que te identificaras
~~~
~~~
git config --global user.email “[valid-email]”
Se usa para establecer el correo con el cual se vinculara cada marcador de historial
~~~

## **Inicializacion**
Configuración de información de usuario, inicialización y clonación de repositorios
~~~
git Init
Permite inicializar un directorio existente como un repositorio de Git
~~~
~~~
git clone [url]
Clona un repositorio completo desde una ubicación alojada a través de URL
~~~

## **Area de preparacion**
Se sube informacio a la area de preparacion ()
~~~
git add [file]
Permite agregar archivos al área de preparación
~~~
~~~
git reset [file]
Elimina un archivo conservando los cambios en el directorio de trabajo
~~~
~~~
git commit -m “El mensaje que acompaña al commit va aquí”
El git commit creará una instantánea de los cambios y la guardará en el directorio git.
~~~

## **Inspeccionar**
Muestra el registro de cambios
~~~
git log
Muestra el historial de cambios en la rama actualmente activa
~~~

## **Compartir y actualizar**
Recupera actualizaciones de otro repositorio y actualizar repositorios locales
~~~
git remote add [alias] [url]
Agrega un URL de git como alias
~~~
~~~
git merge [alias]/[branch]
Fusiona una sucursal remota en su sucursal actual para actualizarla
~~~
~~~
git push [alias] [branch]
Transmitir cambios de la rama local a la rama del repositorio remoto
~~~


# **Git Cheat-Sheet**

<br>

<img src="https://cdn-icons-png.flaticon.com/512/25/25231.png" width="200" height="auto" >

<br>
<br>
<br>

## <center>**Indice**

1. ¿Que es Git?
2. Configuracion inicial
3. Inicializacion 
4. Area de preparacion
5. Inspeccionar
6. Compartir y actualizar

 <br>
 <br>

## **¿Que es Git?**
Git es el sistema de control de versiones distribuido gratuito y de código abierto que es responsable de todo GitHub
relacionado que ocurre localmente en su computadora. Esta hoja de trucos presenta los más importantes y comúnmente
usó comandos de Git para una fácil referencia.

[Codigos Basicos](https://education.github.com/git-cheat-sheet-education.pdf)

<br>

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

<br>

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

<br>

## **Area de preparacion**
Se sube informacion a la area de preparacion
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

<br>

## **Inspeccionar**
Muestra el registro de cambios
~~~
git log
Muestra el historial de cambios en la rama actualmente activa
~~~

<br>

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


<br>

## <center> **Glosario**

### **Repository**  
Un repositorio es el elemento más básico de GitHub. Es más fácil imaginarlos como carpetas de proyecto.

<br>

### **Commit**  
Un commit se puede entender como la confirmación de una modificación individual en un archivo (o serie de archivos). Es como cuando guardas un archivo

<br>

### **Push**
Se refiere a enviar tus cambios confirmados (tus commits) a un repositorio remoto, como por ejemplo un repositorio alojado en GitHub

<br>

### **Pull**  
Literalmente, tirar. Se refiere a traer los cambios del servidor remoto y combinarlos con tu copia local

<br>

### **Branch**  
Un branch o, literalmente, rama, es una versión paralela de un repositorio. Está contenido dentro del repositorio, pero no afecta al branch principal

<br>

### **Merge**  
Literalmente, combinar. Hacer merge toma los cambios de un branch (en el mismo repositorio o también desde un fork), y los aplica en otro.

### **Fork**  
Un fork o, literalmente, tenedor, es una copia personal de un repositorio de otro usuario que se aloja en tu cuenta. Los forks te permiten modificar libremente cualquier proyecto sin alterar el original.
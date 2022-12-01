# Exámen-entornos
## PARTE A. (6 PUNTOS). Repetir "insitu" la tarea 1 (únicamente relativa a github).
### Paso 1. Creamos un repositorio en el ordenador.
Para ello hacemos uso del comando
```
git init
```
![image](https://user-images.githubusercontent.com/114769152/205109381-14ace732-b147-4ba6-a59e-1b70884a53ef.png)

Con este comando creamos un nuevo repositorio en una carpeta, la cual tenemos que elegir antes de comenzar el proyecto.

Si queremos revisar que todo el proceso se haya realizado correctamente, hacemos uso del:
```
git status
```
Gracias a este comando, somos capazes de comprobar cual es el estado del repositorio en el que estamos trabajando en cualquier momento.
![image](https://user-images.githubusercontent.com/114769152/205110607-fa33f194-1aa2-467c-98ec-e2c5e883221e.png)

### Paso 2. Creamos y añadimos un archivo al repositorio.
Si queremos crear y añadir al repositorio un elemento, sea html o txt, lo que tenemos que hacer primero de todo es crear dicho documento.
![image](https://user-images.githubusercontent.com/114769152/205111644-c9eac93e-b86b-42e4-9f80-bceb0fc1b66b.png)
En este caso, estot haciendo uso de un documento html que tenía por mi ordenador. Una vez que lo tenemos preparado y tengamos los documentos hacemos uso del comando:
```
git add
```
Este comando nos permite añadir en el área de ensayo los archivos que se encuentran en nuestra carpeta de trabajo, antes de añadirlo en el repositorio.
![image](https://user-images.githubusercontent.com/114769152/205112648-9f6ba486-5388-4ef4-8555-c9186f2679cd.png)
Una vez que tengamos el documento añadido en nuestra área de ensayo si tratamos de comprobar el estado de nuestro repositorio podremos comprobar que de pasar a tener tres interrogantes cuando poniamos el comando, ha pasado a aparecer una **A**.
![image](https://user-images.githubusercontent.com/114769152/205113345-ec8f6b3b-de77-4968-9b65-7a420f5f1660.png)

### Paso 3. Añadir el elemento al repositorio.
Finalmente, con el comando
```
git commit -m "Comentario asociado a este commit"
```
somos capazes de añadir efinitivamente el archivo al repositorio. Gracias a este comando, el cual es el mas importante de todos, se añade una nueva versión al historial de versiones de nuestro archivo.
![image](https://user-images.githubusercontent.com/114769152/205114722-0be2523a-aeda-46c4-9676-e87e2bd63de7.png)
Hay que decir que, una vez que el archivo ha sido añadido al repositorio, si usamos el comando _git status_ no aparecerá ningún archivo.
![image](https://user-images.githubusercontent.com/114769152/205115559-3aca6658-becd-45b2-9c8e-e1623496f26f.png)
También cabe decir que, si añadimos algún, cambio tenemos que repetir todo el proceso que hemos hecho previamente.  
También está la oción de usar el comando:
```
git commit -am "Comentario asociado a este commit"
```
Así podemos hacer un doble proceso: añadir el archivo al área de ensayo y crear una nueva versión para el historial.
![image](https://user-images.githubusercontent.com/114769152/205117156-aaa5e840-7747-40fc-8250-5669f3072eaa.png)
![image](https://user-images.githubusercontent.com/114769152/205117389-f628ad83-1bb2-4e7d-ab64-c60125d8dc5c.png)

### Paso 4. Transportar el repositorio a la plataforma GitHub.
Para esto usamos el comando:
```
git remote add origin [url]
```
Así, podemos subir todos los archivos y el historial de cambios de nuestro repositorio local al repositorio de GitHub.
![image](https://user-images.githubusercontent.com/114769152/205118183-d3f0aee2-531d-484d-a528-7d2b5e136c60.png)
Si todo va correctamente, en el momento en el que actualizemos la página los archivos y los historiales aparecerán en GitHub.

##PARTE C. (2 PUNTOS). Áreas de un repositorio Git.
* **Directorio de trabajo (Working directory)**: Es el campo en el que usamos todos los comandos sin afectar el repositorio en absoluto.
* **Área de preparación (Staging area)**: un archivo sencillo, generalmente almacenado en el directorio de Git, que recopila información acerca de lo que va a estar presente en la próxima confirmación.
* **Repositorio local (Directorio .git)**: donde se almacenan los metadatos y la base de datos de objetos para un proyecto. Es la parte más importante de Git, y es lo que se copia cuando se clona un repositorio desde otra computadora. El directorio de trabajo es una copia de una versión del proyecto.

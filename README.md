Esto es un readme hecho para una practica de una actividad de empresa es un pequeño formulario solo con una funcionalidad casi nula solo te dira que se envia el formulario.

Documentación en Formato hackmd:
https://hackmd.io/@DVSSEJMaTZm7YsjD8a974w/rJS9XLlR6

Documentación en formato README:
# Uso básico de Github

## Crear un repositorio en Github

Daremos una rapida forma de como crear un github que es tremendamente facil , despues de crear una cuenta te aparecera esta pagina e iremos al simbolo mas para crear un nuevo repositorio:

![image](https://hackmd.io/_uploads/SJwdVIgRT.png)

Crearemos un nuevo repositorio y este lo haremos publico o privado a su preferencia yo lo hare publico:

![image](https://hackmd.io/_uploads/HJUpNIxRT.png)

Ahora vamos a colocar la guia que nos da github para subir uno de sus respositorios a su pagina :

![image](https://hackmd.io/_uploads/HyLBOIeAa.png)


Iremos uno por uno , **git init** es un comando para decirle a github donde se encuentra nuestro repositorio dentro del ordenador:

![image](https://hackmd.io/_uploads/BkYF_UxAa.png)


A continuación confirmaremos que el codigo a sido actualizado con el comando **git status** y sino lo esta usaremos el **git add .** para actualizar los datos:

![image](https://hackmd.io/_uploads/BJx3KUeAp.png)

![image](https://hackmd.io/_uploads/H1I6YLxCa.png)
 
Lo mas importante es colocar los comentarios sino tenemos comentarios esto no funcionara con el comando **git commit -m "Comentario"**:

![image](https://hackmd.io/_uploads/H1yx68x0T.png)


Ahora crearemos la **rama** donde se va a encontra nuestro codigo aunque ahora mismo este seria nuestro **Tronco** ya que es la primera ves que subimos este codigo esto sgit branch -Me hara mediante la linea de comando **git branch -M (nombre de la rama)**:

![image](https://hackmd.io/_uploads/rkBOcLxRp.png)


Despues de esto  se usara el comando **git remote add origin (nombre del repositorio)** para decirle a github en cual repositorio se subira este codigo:

![image](https://hackmd.io/_uploads/ryuMiIxR6.png)


Por ultimo tendremos el comando que es para subir el codigo a github este sera **git push -u origin (nombre de la rama)**:

![image](https://hackmd.io/_uploads/HkRr0IeR6.png)


## Hacer varios Commits

### Consola 

Desde la consola se hace mediante un comando basico que es solo **git commit -m "lo que quieras poner"** y despues subimos otra vez el codigo con un **git push -u origin main**:

![image](https://hackmd.io/_uploads/HyDF4wx0a.png)


![image](https://hackmd.io/_uploads/HJdqNvgA6.png)

### Desktop

Ahora lo voy hacer el desktop que es una aplicación de github modificamos las cosas abriendolo desde el desktop  el visual estudio despues hacemos un comentario y le damos a subir : 

![image](https://hackmd.io/_uploads/rkvKIwx0a.png)


## Firmar Commits: 

### Software 

Debes tener algun Sistema operativo como por ejemplo : Windows , Linux , MacOS .

Instalar en la pagina que tedan despues de eso se te instalara el Kleopatra una aplicación para la GPG:


![image](https://hackmd.io/_uploads/ByronvgCT.png)

### Generar una nueva GPG keys:

Con kleopatra podremos generar claves GPG para esto lo mostrare todo mediante capturas : 

![image](https://hackmd.io/_uploads/SJIUaPeC6.png)




![image](https://hackmd.io/_uploads/ry56TDlCT.png)


Es importante tener una contraseña y que esta la guardes y la apuntes para no olvidarte para ella : 

![image](https://hackmd.io/_uploads/rJ3kAvgR6.png)


![image](https://hackmd.io/_uploads/r1UmRwxRp.png)

Ahora deberemos poner una contraseña y no te olvides de guardarla:

![image](https://hackmd.io/_uploads/HJ2iAweAa.png)
 
Aqui tenemos ya la contraseña Creada : 
 
 ![image](https://hackmd.io/_uploads/ryTCAvxRa.png)


Crearemos un nuevo usuario : 

![image](https://hackmd.io/_uploads/SJiEyOlA6.png)

Tendremos que poner la contraseña para que confirme que somos nosotros:
![image](https://hackmd.io/_uploads/SkauJ_e0p.png)

Veremos que se añadio el nuevo usuario con acceso a la clave:

![image](https://hackmd.io/_uploads/B1H6J_eRT.png)


Generamos el certificado de revición y lo guardamos:

![image](https://hackmd.io/_uploads/rkYCZdgRa.png)


Ahora mostrremos el codigo y quitaremos lo de comment:

![image](https://hackmd.io/_uploads/SyHRGOl0T.png)

### Línea de comandos o terminal

Para generar tus nuevas claves tienes dos opciones:

* Ejecutar la configuración por defecto.
* Ejecutar la configuración completa que le permite definir algunas especificaciones adicionales como el nivel de cifrado.

### Configuración por defecto:

Abrir la terminal o consola de comandos como administrador y esccribiremos un comando y dentro de este al ejecutarse tendremos que poner nuestro nombre y email : 

![image](https://hackmd.io/_uploads/rkXM4ulCa.png)


A continuación tendremos que poner la contraseña que creamos para esta clave:

![image](https://hackmd.io/_uploads/Byzq4ugAT.png)


 Despues te dira si a sido aceptado o no, como se puede ver si fue aceptado : 
 
![image](https://hackmd.io/_uploads/S1I3Vde0p.png)


### Configuración completa

Esta opción le permite:

* Definir el nivel de cifrado hasta 4096.
* Insertar un comentario.
* Definir el tipo de clave (RSA, DSA, Elgamal, etc.).

Genera automáticamente también un certificado de revocación en la ubicación por defecto que se indica en el último paso.

Abra la línea de comandos como administrador y escriba:

![image](https://hackmd.io/_uploads/BkBXLdeRa.png)


Elegiremos la opcion numero 1 : 

![image](https://hackmd.io/_uploads/r13A8deAa.png)




![image](https://hackmd.io/_uploads/S1hjv_gRp.png)




### Definición del ID de usuario para identificar la clave

Pondremos , que nunca se caduca  , Nombre , email y un comentario : 

![image](https://hackmd.io/_uploads/HJBluOeCT.png)


La contraseña la tendremos que meter otra vez para que se haga lo que hemos hecho : 

![image](https://hackmd.io/_uploads/B1j5w_gCa.png)


### Pantalla final con la ubicación del certificado de revocación

![image](https://hackmd.io/_uploads/SktJ0sgRp.png)


## Como Conectar la GPG keys a  Github  

Lo Primero sera Abrir una consola y escribir un comando para ver la **lista de claves** que hay:

![image](https://hackmd.io/_uploads/ByWRr3WR6.png)

Despues tendremos que colocar el comando que nos dara la **clave publica** de la clave que hayamos elegido : 

![image](https://hackmd.io/_uploads/BkPZU3WC6.png)

Copiamos la **clave publica**  , vamos a settings al apartado llamado GPG KEYS y en ese pondremos el titulo y la clave publica:

![image](https://hackmd.io/_uploads/S1WuD2bA6.png)


Ahora haremos que se suba a git modo global nuestro nombre y email ademas tambien pondremos la clave que hayamos elegido para el proyecto : 

![image](https://hackmd.io/_uploads/SyGhw3ZCT.png)

![image](https://hackmd.io/_uploads/Syzavhb0a.png)

A continuación pondremos que cuando haya un commit se active la gpg y que los tag se activen y tambien la dirección donde se encuentran las gpg : 

![image](https://hackmd.io/_uploads/Sk5eOnZAT.png)

![image](https://hackmd.io/_uploads/HkBG_n-A6.png)

Por otra parte ahora comprobaremos que se ha subido y es funcional con este **comando**:

![image](https://hackmd.io/_uploads/r1o9O2W0p.png)


Bien ahora haremos la parte mas sencilla solo tendremos que subir un nuevo commit y confirmar que es funcional: 

![image](https://hackmd.io/_uploads/BJxC_3-R6.png)


Ahora miraremos en github si se ha verificado y tiene nuestra clave  que esta deberia ser( CFF7CB940758653C) : 

![image](https://hackmd.io/_uploads/rJA-K2ZCa.png)


![image](https://hackmd.io/_uploads/rycGKn-0a.png)

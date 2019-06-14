# Mensajes entre Corporativos

Los Corporativos necesitan intercambio de información de datos y procesos de clientes que requieren un encriptamiento de seguridad, debido al tipo de cuentas que se manejan.

Los principales usuarios son integrantes del equipo de Gerencia.

Se incorporo un cifrado segun las posiciones que la Gerencia introduzca.

### Definición del Sistema

 Es un Sistema que identificara que Gerencia genero el mensaje y la clave a utilizar:

* Principales usuarios del Sistema: Gerencias
* Objetivos de usuarios de Gerencia: Tener intercambio de informacion de clientes en forma segura.

El sistema utiliza un cifrado que requiere de clave, la cual solo la conoceran la Gerencias que intercambiaran esa información, se podra cambiar las claves las veces que asi lo requieran las Gerencias, este campo se establecio como password.

## Diseño
El diseño esta conformado por 3 Pantallas:

 `Primera Pantalla` Incluye 3 campos:
*  `Gerencia` El usuario escribe la Gerencia a la cual pertenence.
*  `Clave` La Gerencia escribe las posiciones a desplazarse, estas pueden ser negativas.
*  `Enviar` Se envia la información a la segunda Pantalla

`Segunda Pantalla` Incluye 4 campos:
*  Al inicio de pantalla se mostrara el `Nombre de la Gerencia` escrita por el usuario.
*  `Cuadro de Texto` Aqui se introducira el mensaje
*  `Cifrar` Se cifra el  mensaje, o 
*  `Descifrar` Se descifra el mensaje.

`Tercera Pantalla` Incluye 4 campos:
*  Al inicio de pantalla se mostrara el `Nombre de la Gerencia` escrita por el usuario.
*  `Cuadro de Texto` Aqui se introducira el mensaje
*  `Menu` Se re
*  `Salir` Se cifra el  mensaje, o 




### Interfaz de usuario (UI)

La interfaz debe permitir al usuario:

* Elegir un desplazamiento (_offset_) indicando cuántas posiciones queremos que
  el cifrado desplace cada caracter.
* Insertar un mensaje (texto) que queremos cifrar.
* Ver el resultado del mensaje cifrado.
* Insertar un mensaje (texto) a descifrar.
* Ver el resultado del mensaje descifrado.

### Scripts / Archivos

* `README.md`: debe explicar cómo descargar, instalar y ejecutar la aplicación
  así como una introducción a la aplicación, su funcionalidad y decisiones de
  diseño que tomaron.
* `src/index.html`: este es el punto de entrada a tu aplicación. Este archivo
  debe contener tu _markup_ (HTML) e incluir el CSS 





## Pistas sobre cómo comenzar a trabajar en el proyecto

1. Antes que nada, asegúrate de tener un :pencil: editor de texto en
   condiciones, algo como [Atom](https://atom.io/) o
   [Code](https://code.visualstudio.com/).
2. Para ejecutar los comandos a continuación necesitarás una :shell:
   [UNIX Shell](https://github.com/Laboratoria/curricula-js/tree/v2.x/topics/shell),
   que es un programita que interpreta líneas de comando (command-line
   interpreter) así como tener [git](https://github.com/Laboratoria/curricula-js/tree/v2.x/topics/scm/01-git)
   instalado. Si usas un sistema operativo "UNIX-like", como GNU/Linux o MacOS,
   ya tienes una _shell_ (terminal) instalada por defecto (y probablemente `git`
   también). Si usas Windows puedes usar [Git bash](https://git-scm.com/download/win),
   aunque recomendaría que consideres probar :penguin: GNU/Linux.
3. Haz tu propio :fork_and_knife: [fork](https://help.github.com/articles/fork-a-repo/)



Diseño de experiencia de usuario (User Experience Design):

* Ideación
* Prototipado (sketching)
* Testeo e Iteración



### Avances esperados

* [ ] `README.md` incluye info sobre proceso y decisiones de diseño.
* [ ] `README.md` explica claramente quiénes son los usuarios y su relación con
  el producto.
* [ ] `README.md` explica claramente cómo el producto soluciona los
  problemas/necesidades de los usuarios.

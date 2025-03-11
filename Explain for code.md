# Descripción del código - Directorio Telefonico
Este programa es un diseño solicitado para la asignatura **Sistemas Digitales II**, consiste en el desarrollo de un directorio telefónico a través del uso de listas y diccionarios, además de introducir diferentes métodos y crear funciones para:

1. **Llamar El menú**
2. **Añadir Nuevo Contacto**
3. **Buscar contacto por número de celular**
4. **Borrar contacto del directorio**

Básicamente Se diseño una lista como **contenedor de textos** en esta se guardaron los mensajes de bienvenida, las solicitudes de ingreso de datos por el usuario y el mensaje de despedida, posterior a ello se crea una función de menú que siempre que este dentro del menú de opciones 1 a 4 le retornará a la función **MENU()**, luego se crea la funcion **NUEVO_REGISTRO()** que en simples palabras contiene un diccionario para el ingreso de los datos del nuevo contacto, este apunta con el método **.append** a una lista vacía llamada **Directorio** la cual va a almacenar los diccionarios o en este caso los contactos completos, mientras en la funcion simplemente tan pronto se llame se agrega un nuevo contacto, para evitar mejorar la incorporacion de los datos en el caso particular de los nombres se utilizo el método **title()** para que las cadenas de caracteres ingresadas se visualizaran de una sola manera, como el trabajon lo solicitaba se utilizo la lista de mensajes para el ingreso de estos datos, solamente llamando al espacio reservado de la lista que contenie los mensajes especificos para cada solicitud de ingreso de información.

Posterior se crea la funcion de buscar contacto, en esta se solicita el ingreso del número de telefono a buscar, para guardarlo en la variable objeto **telefono**, se crea un 

**for** persona **in** Directorio

Este ayuda a buscar dentro de la lista **Directorio** la variable objeto **persona** que dentro del for

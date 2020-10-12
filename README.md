# PROGRAMA 1. CLASES DE ENTIDAD Y DAO PARA LA BASE DE DATOS controlconcursos.

## INSTRUCCIONES PARA INICIALIZAR TU PROYECTO DEL PROGRAMA 1

1.	Copie el proyecto IntellijIDEA de la Práctica 08 haciendo lo siguiente:
    - Teniendo abierto el proyecto de la Práctica 08, dé click con el botón derecho en el ícono de Gradle que se encuentra en el borde derecho, expanda Tasks -> build y dé doble click en la opción Clean
    - Dé click con el botón derecho en el nombre del proyecto (en la sección Projects que se encuentra en la parte izquierda) y seleccione la opción Copy -> Copy
    - Dé click con el botón derecho en el nombre del proyecto (en la sección Projects que se encuentra en la parte izquierda) y seleccione Paste, en el cuadro de diálogo que aparece ponga como nombre del proyecto Programa 1 POO2 asegurándose que en el campo Directory está su directorio de proyectos de IntellijIDEA (con el formato C:\Users\NomUsuario\IdeaProjects en Windows donde NomUsuario es su nombre de usuario en Windows) y dé click en OK
    - Cierre el proyecto actual (que es el de la Práctica 08)
2.	Abra el proyecto nuevo y haga modificaciones a su contenido:
    - Dé click en la opción Open or Import para abrir el nuevo proyecto
    - Seleccione en el cuadro de diálogo la ruta del proyecto que acaba de copiar en los pasos anteriores
    - Si al abrirlo le marca el error Invalid VCS Root Mapping , dé click en Configure, seleccione el directorio de la lista que aparece, dé click en el - que está a la derecha para eliminarlo, y dé click en OK
    - En la vista Project Files (en la extrema izquierda superior), expanda el proyecto y elimine la carpeta .github y el archivo README.md
    - En la vista Project (en la extrema izquierda superior), expanda el proyecto y edite el archivo settings.gradle para que el nombre del proyecto sea Programa 1 POO2
    - Edite el archivo .gitignore dentro de la carpeta .idea para que la ruta al DataSources sea la correcta (cambiar la parte donde dice Practica 08 Lab POO2 por Programa 1 POO2)

3.	Habilite la integración con Git, combinando lo que tiene el repositorio remoto con el código que copió de la Práctica 8:
    - Dé click en la opción Version Control Integration del menu VCS, seleccione Git y de click en OK
    - Entre al menú VCS -> Git -> Remotes..., de click en el + para agregar el URL del repositorio remoto (que es el proporcionado al aceptar la tarea en el botón Code), dar click en Ok
    - Entre al menú VCS -> Git -> Fetch
    - Entre al menú VCS -> Git -> Pull seleccionando el branch master y dé click en el botón Pull
    - Haga un primer Commit con el mensaje "Inicializacion de Codigo para Programa 1" incluyendo solo los archivos de las carpeta src, .idea (de este desmarque el archivo .gitignore) , y gradle\wrapper además de los archivos de la carpeta raiz del proyecto (dar click en el icono Group By, el que tienen cuatro cuadritos, y seleccionar By Directory para que aparezcan por directorio y pueda seleccionar tales carpetas y archivos más fácilmente)
    - Entre al menu VCS -> Git -> Push... y en el cuadro de dialogo que aparece de click en el botón Push


## REQUERIMIENTOS

La lista de requerimientos que deben cumplirse en este programa los puede encontrar en el archivo **POO2_Progr1AgoDic2020.pdf**


## CALIFICACIÓN

La calificación para esta se calculará de manera automatizada al hacer push, recuerde que es necesario ir actualizando las pruebas conforme el instructor se lo indique.

## NOTAS IMPORTANTES

1. Recuerda que el proceso que debes estar haciendo es:
   - Crea la clase DAO correspondiente y/o implementa alguno de los métodos que debe tener, prueba que compile.
   - Si ya compila avisa a tu repositorio local que registre esos cambios dando los comandos `git add NombreArchivo.java` y `git commit -m "MENSAJE"` donde MENSAJE es un texto que describe brevemente, pero de manera clara los cambios que realizaste desde el último commit. 

2. Ve integrando y ejecutando las pruebas que se te van a ir entregando durante la semana para verificar que tu programa cumple con los requerimientos. 

3. Si la parte que ya tienes pasa las pruebas correspondientes, súbelo al repositorio remoto dando `git push`. De otra manera, corrige los errores (haciendo las compilaciones, git add y git commit correspondientes)

4. Recuerda que cada vez que hagas `git push` se realizarán automáticamente pruebas sobre tu código para verificar si funciona correctamente. Para esta práctica en particular no se te proporcionará una calificación de manera inmediata pues debe ser revisada con mayor detalle. Recuerda que en la página de tu repositorio en la sección **Pull Requests**, se encuentra una subsección de nombre **Feedback**, donde podrás encontrar los resultados de las pruebas en la pestaña denominada **Check** (expandiendo la parte que dice **Run education/autograding@v1**), y cualquier comentario general que el profesor tenga sobre tu código en la pestaña **Conversation**. 

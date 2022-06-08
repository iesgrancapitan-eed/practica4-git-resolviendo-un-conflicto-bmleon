## Tarea 4.11. Practica4. Git.Resolviendo un conflicto

Documenta los siguientes pasos:
Asegúrate de que tienes configurado el editor Visual Studio Code como tu editor de Git. (git config --global core.editor "code --wait")
Crea un repositorio local y avanza en la rama "master" añadiendo un fichero "index.html" con la estructura básica html. El body estará vacío
Crea y salta a "rama-1". Avanza en un commit con tu nombre de pila en un párrafo dentro del body
Vuelve a la rama master
Crea y salta a "rama-2". Avanza en un commit con tu apellido en un párrafo dentro del body
Muestra el estado del repositorio de forma gráfica y resumida
![Estado del repositorio en la rama actual](estadodemirepositorio.PNG)
Haz un merge a rama-1. Intentas fusionar ambas ramas. Aparecerá un conflicto porque ambos commits trabajan en la misma porción <body></body> de un mismo archivo index.html. Git no será capaz de fusionarlas directamente. 
El editor VS Code reconoce los conflictos de fusión. Las diferencias se resaltan y hay acciones en línea para aceptar los cambios. Deja un único párrafo con tu nombre de pila y apellido.
Una vez que se resuelto el conflicto confirma el archivo en conflicto para que pueda realizar esos cambios
![Provocando el conflicto](conflicto.PNG)
Muestra de nuevo el estado del repositorio de forma gráfica y resumida
![Mostrar de forma grafcica](grafico.PNG)
Vuelve a la rama master y realiza otro merge. Es una fusión fast-forward. Los dos commits a fusionar tienen relación de ancestro. Entonces el merge no produce un commit nuevo, sencillamente avanza la rama, "avance rápido"
![Avance rapido](avance%20rapido.PNG)
Visualiza las ramas que han sido fusionadas con la rama master
![Ramas fusionadas](ramasfusionadas.PNG)
Elimina las ramas correctamente fusionadas (sin asterisco) para quedarte SOLO con la rama master. 
Realiza una copia a este repositorio remoto
Recuerda añadir estas instrucciones con los pantallazos en el fichero README.md
En GitHub entra en Insights/network y visualiza el gráfico del repositorio con los merge y cinco commits  # practica4-git-resolviendo-un-conflicto-bmleon

# Como actualizar el repositorio
Esta es una guía rápida para agregar cambios al repositorio usando VS Code.
## Descargar el repositorio
En el botón **code** se copia el enlace al respositorio.

![Descarga del repositorio](md_images\how_to_git\image.png)

En una nueva ventana dentro de VS Code se pega el enlace y se selecciona la carpeta de destino, el respositorio se descargará como una carpeta con el nombre del mismo.

![Importar a VS Code](md_images\how_to_git\image-1.png)

## Trabajar en un issue
La forma de colaborar en el repositorio es tomar una incidencia (*issue*) y trabajar sobre el problema descrito. Para ello nos desplazamos a la pestaña de la extensión de GitHub en la sección *Issues>Created Issues* y seleccionar la incidencia.

![Selección de incidencias](md_images\how_to_git\image-2.png)

Automáticamente los cambios hechos al repositorio serán agregados bajo la etiqueta de la incidencia.
## Subir los cambios
Una vez hecho los cambios necesarios es momento de actualziar el respotiorio subiendo los avances. Para ello, en la pestaña *Source control* se hace *stage*

![Stage changes](md_images\how_to_git\image-3.png)

Esto indica que los cambios hechos están listos para ser actualziados en el repositorio. Esta acción se peude deshacer si no se está seguro o surge un cambio de último momento, haciendo click en el mismo lugar pero con el signo menos. Esto no elimina ningún cambio o archivo del repositorio original.

Una vez preparado con *stage* los cambios, es momento de *empujarlos* al repositorio, mediante el comando *push*.

![Push](md_images\how_to_git\image-4.png)

Luego de hacer *push* a los cambios, es necsario escribir un pequeño mensaje o *commit* para identificar o describir rápidamente los cambios.

![Commit](md_images\how_to_git\image-5.png)

Finalmente sincronizaremos los cambios con el repositorio original, esto actualziará el archivo original con nuestros cambios.

![Sync](md_images\how_to_git\image-6.png)

# :boom: CONCEPTOS IMPORTANTES PARA EL MANEJO DE GITHUB :boom:

## :cloud: Repositorio en l�nea: 
* Es el repositorio que est� guardado en el servidor de github.

## :computer: Repositorio local: 
 * Es una copia del servidor en l�nea dentro de nuestro ordenador.

## :satellite: Repositorio remoto: 
 * Se trata del repositorio en l�ea de un tercero al cual hicimos un fork.

## :bust_in_silhouette: Fork: 
* Crear una copia del repositorio en l�nea de otro perfil en nuestro perfil de github. Desde este repositorio, podemos colaborar y sugerir cambios en el repositorio original.


## :bust_in_silhouette: Pull request:
* Se trata de una solicitud de incluir cambios en el repositorio de un tercero realizados en un repositorio en l�nea surgido a partir de realizarle un fork.

## :bust_in_silhouette: Proceso para actualizar nuestro repositorio remoto una vez hecho el Fork de alg�n otro compa�ero: 

* Una vez que tenemos la "copia" en nuestro repositorio remoto, debemos primero clonarlo a nuestro repositorio locas:
`$git clone url ` donde la url es de nuestro repositorio remoto.

* Teniendo la copia, dentro de nuetro repositorio local nos movemos a la carpeta del repositorio 

* Una vez ah�, actualizamos nuestro repositorio local desde el repositorio original:

`$git remote add --track master NICKNAME url` donde el NICKNAME es un identificador que puede ser cualquier nombre y la url es del repositorio remoto original

* Si modificamos alguno de los acrhivos dentro de nuestro repositorio local, debemos agregarlos y comentarlos

```
$git add README.md
$git commit -m "Ejemplo"

```

* Nos movemos a la rama que queremos actualizar y subimos los cambios con pull

`$git pull NAME RAMA`

* Finalmente actualizamos la respectiva rama en nuestro repositorio remoto

`$git push origin RAMA`

# UT2-P4

Comienzo creando un rpyecto java en "CarpetaCasa" (repositorio local) y lo subo al repositorio web.
Desde el repositorio remoto clono los ficheros en "CarpetaInstituto".

2. 
  En CarpetaCasa, creo una nueva variable "B" en el main del fichero java y lo subo al repositorio web.
  En CarpetaInsitutot, creo un nuevo fichero java.
  Al modificar la última carpeta e intentar subir la del instituto, se nos genera un error, e indica que el repositorio web contiene información nueva que no consta en mi repositorio local. 
  Para solucionar esto, ejecutamos un “pull” y así sincronizamos ambos repositorios.
 
3. 
  En CarpetaCasa y CarpetaInstituto, creo una nueva variable llamada "C".
  En este caso me vuelve a dar el mismo error: intentamos subir algo al repositorio web cuando no lo tenemos sincronizado con el local. 
  Por consiguiente, hay que volver a hacer un “pull”.
  
4.
  Esta vez creamos una nueva variable llamada "D", pero en CarpetaCasa obtiene el valor 10 y en la del instituto 12.
  En este caso, al hacer distintas modificaciones en cada carpeta, nos da error. Para poder subir los nuevos ficheros, hemos de hacer lo siguiente:
    •	Crear un nuevo commit (añadiendo las nuevas modificaciones) en CarpetaCasa y subirla al repositorio web.
    •	Hacer un pull desde CarpetaInstituto para adoptar la última modificación de la otra carpeta. Una vez sincronizadas, podemos subir la carpeta del instituto con “push”

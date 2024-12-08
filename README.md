# Práctica 3 - GESPRO
## Miembros del equipo
  -Víctor de Marco Velasco  
  -Pablo Sainz Pino

## Guía de cómo se realiza toda la secuencia de acciones desde que nos posicionamos en un nuevo commit del repositorio Go Bees hasta que pasa a estar visible en nuestra rama master local.

Lo primero que debemos hacer es posicionarnos en el commit del repositorio de Go Bees en GitKraken. Una vez encontrado el commit, pulsamos click derecho --> reset master to this commit --> hard

![image](https://github.com/user-attachments/assets/67f876e3-2c74-4c38-aa8c-7f93bc3a6dea)

A continuación, vamos al repositorio de la práctica 3 en GitKraken y nos aseguramos de tener la rama MASTER al día. Nos posicionamos en ella y hacemos Fetch All.

Una vez realizados estos pasos, vamos a nuestro repo en GitHub y buscamos el issue al que queremos hacer commit. Clickamos en él,vamos a development --> create branch y ponemos el nombre correspondiente al commit que aparece en Go Bees.

![image](https://github.com/user-attachments/assets/e56abcd1-31f7-4f05-bab1-656397054c18)

Esta rama aparecerá en GitKraken en remoto. Para bajarla a local, hacemos doble click sobre ella y aparecerá en local. Nos posicionamos sobre ella.

![image](https://github.com/user-attachments/assets/b9f8bcdb-1690-4c7d-ab14-d31bb99e5505)


Después vamos al directorio donde se encuentra nuestro repositorio de Go Bees clonado en GitKraken, copiamos todo y lo pegamos en el directorio clonado de la Práctica 3. Reemplazamos todos los archivos si nos lo pide.

Ahora veremos una nueva línea en nuestro repo de la Práctica 3 de GitKraken donde se indican todos los cambios realizados, damos stage all changes, ponemos un nombre al commit y pulsamos Stage Changes to Commit.

![image](https://github.com/user-attachments/assets/f49b6ae3-ff97-4441-828c-64c0827537d2)

Podemos ver que en la rama donde estamos haciendo el commit hay un cambio, hacemos fetch all. Si hay cambios hacemos primero un pull y luego push, si no directamente hacemos push.

![image](https://github.com/user-attachments/assets/f372464e-cb3d-47e1-8db3-a9631893080a)

A continuación debemos crear un pull-request, para ello vamos a GitHub, creamos un nuevo pull-request y seleccionamos correctamente los repositorios y ramas con los que estamos trabajando. Si hemos hecho correctamente los pasos anteriores, nos saldrá algo parecido a lo siguiente .

![image](https://github.com/user-attachments/assets/4accbd9c-0ac5-4b33-8bcb-1658c28ff221)

Damos a create pull request y confirmamos el merge pull-request.

![image](https://github.com/user-attachments/assets/a4c7e6cb-5aa8-4ba9-8dc7-ae8a1b7cde33)

![image](https://github.com/user-attachments/assets/f59e6058-1789-407e-81c3-416096ceb87c)

Podemos observar el nuevo pull-request en GitKraken.

![image](https://github.com/user-attachments/assets/8c3579b9-f612-4175-814a-711ce28638ad)

Para finalizar, observamos que master en local tiene cambios, para ello hacemos fetch all y pull para subir master en local a la altura de master en remoto. Podemos observar que ya se encuentran a la par.

![image](https://github.com/user-attachments/assets/ff9fdb18-4a36-44ba-8144-b98d09255dda)

En GitHub también podemos observar que el pull-request se ha cerrado correctamente.

![image](https://github.com/user-attachments/assets/815bfeef-7db9-4aeb-989d-66004c240e1e)


## Capturas GitKraken

## Capturas GitHub

# repo-launch
# Repo launch


## Hardware

Cualquier máquina con un OS Linux.

##  ¿Cómo instalarlo?

```git clone https://github.com/Luis23310/repo-launch.git```

## ¿Cómo correrlo?

## Forma larga pero simple
Primero se inicia el ros de la siguiente forma en la consola de Ubuntu:

``roscore``

Luego se busca el lugar exacto donde se encuentra el proyecto descargado.

Lo que se hace es buscar la carpeta, cuando se ubica la carpeta se procede a abrirlo en la terminal, dando click derecho en la carpeta, se seleccione "Open in terminal". 

Ya que se tiene la dirección donde se guarda la carpeta se ejecutan ambos códigos .py, el cual el primero en ejecutarse es``talker.py`` y luego el ``listener.py ``.

Ya al momento de ejecutar ambos códigos se estarán comunicando entre ellos.

## Forma corta pero difícil
Volvemos a buscar la carpeta, y abrimos "Open in terminal".  Se busca con el comando ``ls``  y buscamos el archivo ``launch.sh``.

Ya al ubicarlo se coloca el siguiente comando:
	``sudo chmod -x launch.sh``
Con esto se de la administración directa al código para ejecutar el ``ROS``, ``talker.py`` y ``listener.py ``.

## Autor:
Luis Duarte.

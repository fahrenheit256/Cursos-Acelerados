# Curso acelerado de GIT & GITHUB 


## ¿Como configuro git?

Necesitamos registrar nuestra credenciales de usuario en el archivo .gitconfig a
nivel global para que estas valgan para todos nuestros repositorios.

### `git config --global user.name <name>`

### `git config --global user.email <email>`


> [!IMPORTANT]
> Solo necesitamos configurar git un unica vez despues de instalarlo.

## ¿Como clono un repositorio?

### `git clone <url>`

:::image type="content" source="Images/CicloGitClone.jpg" alt-text="Git push en el flujo de trabajo":::

> [!CAUTION]
> Descargar un respositorio no es lo mismo que clonarlo. El primero obtenes una copia del ultimo estado de los archivos, cuando clones obtenes todo el historial de cambios que tuvo los archvios.


## ¿Que debo hacer antes de empezar a trabajar?

Suponiendo que no acabas de clonar tu repositorio, si es asi salta este punto. Antes de comenzar a trabajar debemos actualizar nuestra version del respositorio. 

### `git pull`

:::image type="content" source="Images/CicloGitPull.jpg" alt-text="Pull":::

> [!TIP]
> Mantener nuestro repositorio actualizado, hace que los conflictos entre versiones sean pocos y pequeños, por lo tanto faciles de resolver.


## ¿Cual es el flujo de trabajo ideal?

A continuacion describiremos cual es flujo de trabajo ideal, es ideal proque suponemos que no ...

### Del area de trabajo hacia el area de staging



### Del area de staging hacia el area de repository


### Subiendo mis cambios a Github

## Cometi un error, ¿Como lo resuelvo?

- Si agregaste a tu area de staging un archivo que no querias puedes sacarlo utlizando el siguiente comando.
- 


# <span style="color:red"> Aldo Manuel Castañon Garcia <span>

- ***Matrícula:*** 2630174
- ***Nombre de la práctica:*** Creación y sincronización de repositorios con Git y GitHub
- ***Objetivo de la práctica:*** Crear un repositorio local utilizando Git, sincronizarlo con un repositorio remoto en GitHub y comprobar el flujo de trabajo en ambos sentidos, para asi poder ser capaz de crear y administrar un repositorio local con Git, utilizar el Staging Area, realizar commits, vincular un repositorio local con GitHub y sincronizar cambios utilizando git push y git pull.

---------

## Descripción del procedimiento realizado:

**1.-** Primero **inicie el PowerShell y meti el comando** [cd ~] para asi moverme de manera rapida a la ruta de mi usuario despues al escritorio donde cree una carpeta llamada [practica-git-Aldo-Castañon]

**2.-** Despues con el comando **[git init] inicialice esa carpeta como un repositorio** 

**3.-** Luego **configure la rama principal** con el comando [git branch -M main] pero como mi rama principal no es main si no Master tuve que cambiar el **codigo [git branch -M master]**

**4.-** **Cree los archivos datos.txt y README.md** con el comando [New-Item datos.txt/New-Item README.md] y con el comando [ls] **confirme que estuvieran creados**

**5.-** Ingrese el comando [git status] y **confirme** que efectivamente aun no agregaba ningun **archivo a la zona de STAGING**

**6.-** Entonces los **añadi a la zona de STAGING** [git add ] despues con [git status] confirme su pocicion y **los hice commit** con [git commit -m "mi Primer commit"]

**7.-** Ahora **vincule mi repositorio local con el de GITHUB** con [ git remote add origin https://github.com/ElCald0/Practica-Git-Aldo-casta-on.git] 

**8.-** **Lo confirme** con el comando [ git remote -v]

**9.-** Luego **mande mis commits a GITHUB** con el comando [git push -u origin master]

**10.-** **Desde GITHUB hice un cambio** en el archivo de "datos.txt" y con el comando [cat .\datos.txt] **confirme que el cambio se habia aplicado**

**11.-** Me di cuenta que no porque **ocupaba meter este comando primero** [git pull origin master] para bajar lo de GITHUB a mi pc, y **si se habia realizado el cambio** ya cuando lo confirme con el comando [cat .\datos.txt] 

**12.-** Luego lo hice a la inversa y** modifique el archivo de GITHUB desde mi computadora** ["Este archivo fue modificado desde el repositorio local, ala menchis mira nadamas le meti mas texto desde la consola alabestia chat impresionante como avanza la tecnologia" >> datos.txt] y **lo subi a GITHUB otra vez** para luego confirmarlo con el comando [ cat .\datos.txt]

**13.-** Con el comando [ git status] me di cuenta que mi **modificacion estaba en UNTRACKED** files entonces volvi a poner [git add] luego [git commit -m "Actualización desde repositorio local"]

**14.-** Ya una vez hecho commit **lo mande a GITHUB** [git push] y verifique los cambios en GITHUB (lo mimo que hare  o ya hice con este archivo)

---

##  Comandos de Git utilizados y explicación breve de la función de cada comando

```git init``` Inicializa la carpeta como repositorio de GIT

```git branch master```Configura la rama principal con el nombre master  (es la que yo tengo)

```git status```Verificamos el estado del repositorio

```git add ```Agregamos archivos de toda la carpeta al area de STANGING

```git commit -m "mi Primer commit"```Creas el primer commit local

```git remote add origin https://github.com/ElCald0/Practica-Git-Aldo-Manuel.git``` Vincula el repositorio local con el de GITHUB

```git remote -v```Verifica que este vinvulados correctamente 

```git push -u origin master```Envia por primera vez nuestro repositorio local a GITHUB

```git pull origin master```Envia los cambios realizados en nuestro repositorio local a GITHUB

------------

## Explicación de cómo se creó el repositorio local y explicación de cómo se vinculó el repositorio local con GitHub

El repositorio local **se creo** con el comando [git init] en la carpeta llamada [practica-git-Aldo-Castañon] y **se vinvulo** con los comandos [git remote add origin https://github.com/ElCald0/Practica-Git-Aldo-casta-on.git] desde PowerShell **verificando** la correcta vinculacion de este con el comando [git remote -v]

----

## Explicación de la sincronización Local → GitHub y explicación de la sincronización GitHub → Local

Una vez ya vinculados con los comando [git add] [git commit -m "mi Primer commit"] y [git push -u origin master] **agregre mis commits locales a GITHUB** y entrando a la pagina podia verlos e incluso editarlos desde ahi ahora de **GITTHUB > a local** habri mis repositorios de git donde tenia esta practica y dentro los archivos "README.md y datos.txt" abri el de "datos.txt" y lo **modifique** como pidio el profe despues le di a guardar cambios de "datos.txt" en la misma pagina de GITHUB y **desde PowerShell baje el archivo modificado** con el comando [git pull origin master] y con el comando [cat .\datos.txt] **verifique que los cambios estuvieran de manera local** en mi archivo.
 
-------------

## Descripción de los archivos contenidos en el repositorio y conclusión personal sobre lo aprendido

En el repositorio de GITHUB **encontraras dos archivos** uno **"datos.txt"** donde meti lo que el profe pidio y donde hice los cambios que el pidio y otro llamado **"README.md"** donde esta la info que despues pidio el profesor acerca de esta tarea. 

En conclusion aprendi un poco mas acerca de los comandos de **GIT** y a moverme de forma rapida en el **PowerShell** y **GITHUB** descubri que puedo modificar archivos desde GITHUB y **como bajar esas modificaciones** diractamente a mi pc, tambien repase algunos codigos de la consola, repase como subir archivos a **STAGING area** y hacerlos **commit**, tambien como subirlos y como **vincular repositorios locales a GITHUB** para asi tener un respaldo de ellos.  
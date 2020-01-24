# Prepara tus herramientas principales de curso: Github y Python.

## GITHUB

  1.- (Se realiza una sola vez!) Accede al siguiente link:https://classroom.github.com/a/aurYOjly  para crear tu repositorio para el curso. Si no eres usuario de github, primero deberas crear tu cuenta de usuario.

  2.- Desde la terminal accesa al directorio donde crearas tu espacio de trabajo para la clase (e.g. $HOME/Documentos/Cursos/analisis_datos/). Sigue las instrucciones dadas en clase respecto al manejo de terminal. Es practicamente lo mismo para MAC y Linux. Si trabajas en Windows, lo siento no podré ayudarte demasiado... Es importante que fuera de la clase practiques el uso de la terminal, ya que te será muy útil. https://www.ubuntupit.com/the-50-best-linux-commands-to-run-in-the-terminal/

  3.- Clona tu repositorio en el directorio que hayas elegido para trabajar: 

  `git clone [añade el link que aparece en pagina de github que se abrio en el paso 1.]`
  
  (Tipicamente se realiza una sola vez, a menos que quieras clonar nuevamente tu repositorio en otra maquina, directorio, etc...)
  
  4.- Sincroniza tu repositorio. Este paso si se realiza continuamente. Siempre, antes de iniciar a trabajar, actualiza tu repositorio a cambios que hayas hecho directamente en la página web:

`git pull`

  Cada clase asegurate de actualizar contenido que haya añadido yo:

`git pull https://github.com/alxogm/DCIDA2020I`

  5.- Cuando quieras actualizar tu repositorio, para que contenga los cambios locales que hayas hecho en tu directorio de trabajo, debes primero añadir los archivos a rastrear:

`git add .`(Si todos los cambios se añaden) ó 

`git add [nombre de archivo]` (si solo quieres añadir cambios en archivos especificos).

  Posteriormente debes añadir/confirmar los cambios realizados: 

`git commit`(Te pedira añadir una breve descripción del cambio realizado)

  Finalmente empuja los cambios al repositorio:

`git push`

  6.- Si no recuerdas en que status está tu directorio de trabajo, puedes revisarlo en cualquier momento:

`git status`

  7.- En resumen las instrucciones básicas son:
  

`git pull
 git pull https://github.com/alxogm/DA2019 master
 git status
 git add
 git commit
 git push
`
  Hay muchas mas opciones para manejar tu repositorio. Hablaremos de ellas conforme las usemos, de cualquier forma aquí hay link a los comandos mas comunes: https://education.github.com/git-cheat-sheet-education.pdf
  
  
  ## PYTHON
  
  1.- La distribución que recomiendo de python es "miniconda". La instalación la haremos en clase...pero para futura referencia dejo los dos siguientes puntos. 
    
  2.- Usaremos la version 3.7, sigue las instrucciones de instalación en https://docs.conda.io/en/latest/miniconda.html  para tu sistema operativo. En particular para MAC y Linux, al momento de instalar pon atención en el último paso. Te pedirá añadir los ejecutables a las variables de ambiente. Yo recomiendo no hacerlo sobretodo para evitar conflictos si ya tienes otras instalaciones de python. Es preferible activarlo manualmente. 
    
  3.- Recomiendo el uso de ambientes. Para ello una vez instalado miniconda, deberas crear el ambiente de trabajo:
        
        `conda create -n [nombre_del_ambiente]`
        
   Una vez creado, activaremos el ambiente:
        
        `conda activate [nombre_del_ambiente]`
        
   Cada vez que cierras tu terminal y la vuelves a abrir deberas volver a activar el ambiente. 
        
  4.- Finalmente instalaremos las primeras librerias que usaremos: 
    
       `conda install numpy matplotlib jupyterlab`
       
  5.- Estamos listos para empezar a trabajar. Inicia jupyter-lab:
  
      `jupyter lab `
  
    
    
   

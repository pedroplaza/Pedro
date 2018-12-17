    #Ejercicios del curso de Confección de Páginas Web #

    ##Configuración del Entorno ##

    - Navegador: Chrome, Firefox... (usando F12)
    - Editor de código: Visutal Studio Code
        https://code.visualstudio.com/
    - NodeJS / npm
        https://nodejs.org/es/
    - Servidor web de desarrollo: por ejemplo http-server
        npm install -g http-server
    - Instalar Git
        Git
        https://git-scm.com/

    ### Configuración de Git ###
    - Definiri usuario / correo
    git config --global user.name <userName>
    git config --global user.email <usermail>
    - Comprobar la configuración 
    git config -l --global

    Crear un repositorio:

    - De local a remoto
            - git init <carpeta>
        - Opcionalmente, hacemos un primer commit desde Visual Studio Code
        - Comprobamos el commit
            git log
        - Creamos un repositorio vacío en GitHub, preferiblemente con el mismo nombre que el repositorio local
        - Siguiendo las instrucciones de GitHub, sincronizamos los repositorios
            git remote add origin https://github.com/pedroplaza/Pedro.git
            git push -u origin master

    
    - De remoto a local
        - Clonamos el repositorio desde git <copiando la dirección> y desde el simbolo del sistema:
            git clone <pegar direccion de git>
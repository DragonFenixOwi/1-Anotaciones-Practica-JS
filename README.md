# Plantilla_Front_2020
    - Plantilla para proyectos de FrontEnd = HMLT5 + CSS3 + SASS + JAVASCRIPT
## Desarrollo de la Práctica 
 1. Descargando Plantilla de Fronted.
 2. Configurando-Git-y-Github.
 2. Ejercicios de crear Repositorios con "Hola Mundo"

## Notación Básica Inicial de git_bash
 1. git clone https://github.com/PalmaActiva-2020-JS/Plantilla_Front_2020.git
 2. git remote remove origin
    - Se remueve la ultima conexión push-pull. Que sirve para subir repositorio a github o traer un repositorio de github
 3. git remote –v
    - Se verifica que no existe una conexion (push-pull) con el respositorio
 4. git remote add origin https://github.com/DragonFenixOwi/
    - Se crea una conexión "remota" con el nuevo repositorio creado
 5. git init
 6. git status
    - Buenas Prácticas. Verificar el estado de cambios del respositorio
        - En rojo se indica los que hay que añadir. Al staging con "git add"
            - modified:   css/estilos.css
            - modified:   index.html
        - git add 
            - index.html  
            - css/estilos.css
 7. Git status              
    - Nuevamente para verificar el estado de cambios
 8. git commit –m
    - Agregamos al repositorio local
 5. git push -u origin master
    - Enviamos al respositorio o hacemos un push al respositorio  


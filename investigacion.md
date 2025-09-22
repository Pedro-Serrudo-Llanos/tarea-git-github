# investigacion
Estudiante: Pedro Serrudo Llanos

1. ¿Qué es Git y para qué se utiliza?
Git es un sistema de control de versiones que me permite llevar un historial de los cambios en mis proyectos. Se utiliza para trabajar en equipo, guardar diferentes versiones del código y evitar perder el trabajo al poder regresar a versiones anteriores.

2. ¿Qué diferencia hay entre Git y GitHub?
Git es la herramienta que funciona en mi computadora para manejar versiones de código.  
GitHub es una plataforma en la nube donde puedo subir esos proyectos y compartirlos con otras personas.  
En resumen: Git = herramienta local, GitHub = servicio en línea.

3. Explica en tus palabras qué es un repositorio.
Un repositorio es como una carpeta especial donde guardo mi proyecto con todo su historial de cambios. Puede estar en mi computadora (local) o en GitHub (remoto).

4. ¿Qué significa hacer un commit en Git?
Un commit es como tomar una “foto” del proyecto en un momento específico. Sirve para registrar los cambios que hice con un mensaje que explique qué modifiqué.

5. Comandos básicos de Git
  - git config --local user.name "<GitHub user name>" 
    Configura el nombre de usuario solo para ese repositorio.
  
  - git config --local user.email "<GitHub email>"  
    Configura el correo de GitHub para identificar mis commits.
  
  - git init
    Inicializa un nuevo repositorio Git en la carpeta donde estoy.
  
  - git add  
    Prepara los archivos que quiero guardar en el próximo commit.
  
  - git commit 
    Registra los archivos agregados en el historial de Git con un mensaje.
  
  - git push
    Sube mis commits al repositorio remoto en GitHub.
  
  - git clone  
    Descarga un repositorio desde GitHub a mi computadora.
  
   - git init --initial-branch=main  
    Crea un repositorio nuevo con la rama principal llamada “main” (en vez de master).
  
   - git remote add origin https://github.com/<user-name>/tarea-git-github.git  
    Conecta mi repositorio local con el remoto en GitHub.
  
  - git add .  
    Agrega todos los archivos modificados o nuevos al commit.
  
  - git commit -m "Initial commit" 
    Crea el primer commit con el mensaje “Initial commit”.
  
  - git push --set-upstream origin main  
    Sube el proyecto a GitHub y define que la rama principal sea “main”.

6. ¿Qué es un archivo README.md y por qué es importante?
El archivo README.md es el documento principal de un repositorio. Sirve para explicar de qué trata el proyecto, cómo usarlo y quién lo hizo. Es importante porque cuando alguien entra a mi repositorio, lo primero que verá será el README.md.

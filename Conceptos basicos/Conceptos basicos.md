# Introducción a Git

**Git** es un sistema de control de versiones diseñado para rastrear los cambios realizados en archivos, facilitar la colaboración entre desarrolladores y gestionar proyectos de manera eficiente. Es una herramienta esencial en el desarrollo de software, que permite a los equipos trabajar simultáneamente en un proyecto sin sobrescribir los cambios de los demás.

Git también te da la posibilidad de regresar a versiones anteriores, crear ramas para probar nuevas ideas y sincronizar tu trabajo entre diferentes máquinas o con repositorios remotos, como GitHub.

---

## 10 Conceptos Clave de Git

1. **Repositorio (Repository)**  
   Es el lugar donde se almacena tu proyecto y su historial de versiones. Puede ser local (en tu máquina) o remoto (en plataformas como GitHub).  

2. **Commit**  
   Es un punto en el historial de tu proyecto que guarda los cambios realizados. Cada commit tiene un mensaje descriptivo y un identificador único.  

3. **Rama (Branch)**  
   Una línea de desarrollo independiente. Las ramas permiten trabajar en nuevas características o correcciones sin afectar la versión principal del proyecto.  

4. **Merge**  
   Combina los cambios de una rama en otra. Es común fusionar ramas de características en la rama principal (`main` o `master`).  

5. **Área de staging (Staging Area)**  
   Es un espacio intermedio donde los cambios se preparan antes de ser confirmados (committed). Permite revisar qué se incluirá en el próximo commit.  

6. **Repositorio remoto (Remote Repository)**  
   Es un repositorio alojado en la nube o en un servidor que permite compartir tu trabajo y colaborar con otros. Ejemplo: GitHub, GitLab, Bitbucket.  

7. **Clonar (Clone)**  
   Descarga una copia de un repositorio remoto en tu máquina local, incluyendo su historial de cambios.  

8. **Pull**  
   Trae los últimos cambios desde el repositorio remoto a tu repositorio local.  

9. **Push**  
   Envía tus commits locales al repositorio remoto, actualizando el proyecto compartido.  

10. **Conflicto (Conflict)**  
    Sucede cuando Git no puede combinar automáticamente los cambios realizados en un archivo. Los conflictos deben resolverse manualmente antes de continuar.  

---

Git es una herramienta poderosa que, una vez dominada, se convierte en un compañero esencial para cualquier desarrollador o equipo que desee gestionar su trabajo de manera eficiente. 🚀


# COMANDOS MÁS UTILIZADOS

| Comando       | Descripción                                                                 | Ejemplo                        |
|---------------|-----------------------------------------------------------------------------|--------------------------------|
| `git init`    | Inicializa un nuevo repositorio de Git en el directorio actual.            | `git init`                     |
| `git clone`   | Clona un repositorio remoto en tu máquina local.                           | `git clone <url>`              |
| `git status`  | Muestra el estado actual del repositorio: archivos modificados, no rastreados o en staging. | `git status`       |
| `git add`     | Agrega archivos al área de staging (preparación).                          | `git add <archivo>`            |
| `git commit`  | Crea un commit con los cambios del área de staging.                        | `git commit -m "Mensaje del commit"` |
| `git push`    | Envía los commits locales al repositorio remoto.                           | `git push origin main`         |
| `git pull`    | Descarga y fusiona los cambios del repositorio remoto con el local.        | `git pull origin main`         |
| `git branch`  | Crea, lista o elimina ramas en el repositorio.                             | `git branch <nombre_rama>`     |
| `git checkout`| Cambia entre ramas o revisiones específicas.                               | `git checkout <nombre_rama>`   |
| `git merge`   | Combina los cambios de una rama en la rama activa actual.                  | `git merge <nombre_rama>`      |


## Recursos adicionales

Puedes descargar la guía de referencia creada por GitHub en formato PDF desde el siguiente enlace:

[Descargar guía básica Git](github-git-cheat-sheet.pdf "target="_blank"")

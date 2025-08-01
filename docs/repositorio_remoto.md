# Repositorio Remoto

Para trabajar con un repositorio remoto en GitHub y sincronizarlo con nuestro repositorio local, debemos seguir una serie de pasos que incluyen la creación del repositorio en GitHub, la conexión desde nuestra máquina y la subida de cambios.

- Crear repositorio en GitHub:

Ingresa a github.com y crea una cuenta si no tienes.

Haz clic en "New repository" y completa el nombre y detalles.

No inicialices con README ni .gitignore (opcional).

Copia la URL del repositorio remoto (HTTPS o SSH).

- Aquí un breve listado de los comandos más usados para crear y sincronizar un repositorio remoto:

git remote add origin [URL]: conecta el repositorio local con el remoto de GitHub
git push -u origin main: sube los cambios iniciales a la rama principal y establece el seguimiento remoto
git pull origin main: sincroniza los cambios del repositorio remoto con el local
git status: verifica el estado de los archivos en el repositorio local

![En esta imagen se observan comandos de guardado de checkpoints en git ](/images/git%20add%20git%20commit.png)
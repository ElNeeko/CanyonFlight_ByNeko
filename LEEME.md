# Canyon Flight en GitHub Pages

## Qué hay acá
- `index.html`: portada con el botón **Jugar**
- `jugar/`: el juego (build web de Unity, versión PC + versión celular)
- `img/`: capturas de la portada
- `.nojekyll`: evita que GitHub procese el sitio con Jekyll (no lo borres)

## Importante
- **No subas el zip**: GitHub no lo descomprime.
- **No uses "Upload files" en la web de GitHub**: acepta hasta 25 MB por archivo, y los dos `.data.unityweb` pesan 62 MB.
  Usá **GitHub Desktop**, que acepta hasta 100 MB por archivo.

## Cómo subirlo con GitHub Desktop
1. Abrí GitHub Desktop → **File → Add local repository…**
2. Elegí la carpeta `D:\GameOnlyMe\Builds\GitHubPages` → **Add repository**.
   Te va a decir que no es un repositorio: tocá **create a repository**. **Dejá el nombre que propone (`GitHubPages`)** y la ruta como está, sin tildar README → **Create repository**.
3. Abajo a la izquierda, en *Summary*, escribí "Primera versión" → **Commit to main**.
4. Arriba tocá **Publish repository**. Ahí sí poné el nombre que quieras (ej. `canyon-flight`). **Destildá "Keep this code private"** (Pages gratis necesita repo público) → **Publish repository**.
   Si avisa que hay archivos de más de 50 MB, es solo un aviso: seguí.
5. En la web de GitHub, en el repositorio: **Settings → Pages → Build and deployment → Source: Deploy from a branch**, rama `main`, carpeta `/ (root)` → **Save**.
6. En uno o dos minutos queda en `https://TU_USUARIO.github.io/canyon-flight/`.

## Para actualizar el juego
Reemplazá la carpeta `jugar/` por la build nueva, y en GitHub Desktop: **Commit to main** → **Push origin**.

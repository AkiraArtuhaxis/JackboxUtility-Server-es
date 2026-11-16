# Jackbox Utility Server - Jackbox en español

Este repositorio contiene la información del servidor de Jackbox en español para Jackbox Utility, que ofrece la fácil instalación de todos sus parches.
Se listan los archivos relevantes para su mantenimiento, y sus contenidos.

## info.json 

Este archivo contiene la información general del servidor. En principio, ninguno de estos contenidos cambia seguido.

- `name`: El nombre del servidor ("Jackbox en español")
- `description`: La descripción del servidor ("¡El servidor de la comunidad de Jackbox en español!")
- `image`: La imagen que se muestra como ícono del servidor ([esta](https://raw.githubusercontent.com/AkiraArtuhaxis/JackboxUtility-Server-es/main/assets/news_images/logo.png))
- `urls`: Enlaza a la api y assets que hay en este repositorio.
- `controller`: El controlador utilizado por el servidor, que se muestra en la aplicación (jackbox.lol)
- `languages`: El lenguaje que utiliza la aplicación al utilizar el servidor ("es" = español)
- `links`: Incluye los enlaces que se muestran debajo del servidor en ajustes. Cada enlace presenta los siguientes atributos:
  - `icon`: ícono que se muestra a la izquierda.
  - `url`: Enlace al que lleva al clickear.
  - `text`: Texto que se muestra al lado del ícono.

## api/welcome.json

Muestra carteles de bienvenida, con una fecha asociada. Utilizado principalmente para el anuncio de novedades.
- `news`: Contiene todas las novedades encontradas en el servidor.
  - `id`: Fecha y hora de la novedad. Utilizadas para definir si se debe mostrar a un usuario dicha novedad o no.
    - En nuestro caso, dejamos tres novedades fijas: Un enlace a Discord, una bienvenida a la Utility, y una que muestra la única novedad del momento.
    - En principio, esta última es la única que se cambia seguido.
  - `title`: TBD
  - `smallDescription`: TBD
  - `content`: TBD
  - `image`: TBD

- **packs.json**: Contiene los datos de los parches ofrecidos.

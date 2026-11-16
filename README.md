# Jackbox Utility Server - Jackbox en español

Este repositorio contiene la información del servidor de Jackbox en español para Jackbox Utility, que ofrece la fácil instalación de todos sus parches.

Archivos relevantes:
- **info.json**: Contiene la información del servidor.
  - _name:_ El nombre del servidor ("Jackbox en español")
  - _description:_ La descripción del servidor ("¡El servidor de la comunidad de Jackbox en español!")
  - _image:_ La imagen que se muestra como ícono del servidor ([esta](https://raw.githubusercontent.com/AkiraArtuhaxis/JackboxUtility-Server-es/main/assets/news_images/logo.png))
  - _urls:_ Enlaza a la api y assets que hay en este repositorio.
  - _controller:_ El controlador utilizado por el servidor (jackbox.lol)
  - _languages:_ El lenguaje soportado por el servidor ("es" = español)
  - _links:_ Incluye los enlaces que se muestran debajo del servidor en ajustes. Cada enlace presenta los siguientes atributos:
    - icon: ícono que se muestra a la izquierda.
    - url: Enlace al que lleva al clickear.
    - text: Texto que se muestra al lado del ícono.
- **welcome.json**: Muestra un mensaje de bienvenida, con su título (title), una breve descripción, contenido y una imagen.
- **packs.json**: Contiene los datos de los parches ofrecidos.

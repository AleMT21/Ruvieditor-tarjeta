# Editor de Tarjeta de Héroe - Overwatch

Una aplicación web ligera e interactiva diseñada especialmente para la comunidad de Ruviz. Permite a los jugadores crear, personalizar y descargar una tarjeta de presentación (Hero Card) con sus estadísticas, rangos, preferencias y niveles de maestría con cada héroe.

## Uso de la Herramienta

No es necesario descargar ni instalar ningún archivo para utilizar el editor. La aplicación está alojada y lista para usarse directamente desde cualquier navegador web moderno.

**Accede a la herramienta aquí:** https://alemt21.github.io/Ruvieditor-tarjeta/

## Características Principales

* **Generador en Tiempo Real:** Visualiza los cambios en la tarjeta al instante gracias a la renderización dinámica con la API de Canvas.

* **Personalización Completa:**
  * Información del jugador (BattleTag, pronombres, edad, país, etc.).
  * Preferencias del juego (Mapas y héroes favoritos/odiados).
  * Registro de horas jugadas por rol (Tanque, DPS, Apoyo) y por modo de juego.

* **Rango Competitivo:** Selecciona fácilmente tu Peak. Los iconos de rango (Bronce a Champion) se actualizan automáticamente.

* **Tops de Héroes Inteligentes:** Registra tus 10 héroes más jugados y los 10 menos jugados. El sistema inyecta automáticamente el icono del héroe seleccionado, las horas y su nivel en los hexágonos de la tarjeta.

* **Grid Interactivo de Maestría:** Haz clic directamente sobre la cara de los héroes en la tarjeta para asignar tu nivel de habilidad (Main, Puedo jugar, Necesidad, Practicando, Nunca) usando un menú flotante intuitivo. Incluye personajes recientes como D.Mon.

* **Exportación en Alta Calidad:** Descarga tu tarjeta terminada en formato PNG con un solo clic, lista para compartir.

* **Privacidad Total:** Toda la ejecución ocurre del lado del cliente (Frontend puro). No se requiere base de datos y la información no sale del navegador del usuario.

## Tecnologías Utilizadas

* **HTML5 & CSS3:** Estructura semántica y diseño responsivo adaptado a dispositivos móviles y de escritorio. (Tipografía oficial: Barlow y Faster Stroker).
* **JavaScript (ES6+):** Lógica pura (Vanilla JS) sin librerías externas.
* **HTML Canvas API:** Motor principal para la estampación de textos e imágenes sobre la plantilla base.

## Despliegue Local (Opcional)

Si deseas clonar el código fuente para realizar copias de seguridad o pruebas locales, el proyecto es totalmente estático:

1. Clona este repositorio en tu máquina local.
2. Entra en la carpeta del proyecto.
3. Abre el archivo `index.html` en tu navegador web.

## Estructura de Directorios Clave

* `index.html`: La estructura del panel de control de la aplicación.
* `style.css`: La hoja de estilos para la interfaz y el lienzo.
* `script.js`: El motor interactivo que gestiona los eventos de clic y el renderizado del Canvas.
* `/iconos/`: Contiene las imágenes PNG de los héroes con recorte hexagonal (usados en los menús desplegables de la web).
* `/iconos_blancos/`: Contiene las imágenes PNG de los héroes con contorno blanco (usados para estampar en la plantilla final).
* `Plantilla.png`: La imagen base sobre la que se dibujan los datos del usuario.

## Licencia

Este proyecto está creado por y para la comunidad de Ruviz. (Overwatch y los recursos visuales del juego son propiedad de Blizzard Entertainment).

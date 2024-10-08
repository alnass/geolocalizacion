# Geolocalizacion
Aplicación en flutter para obtener la geolocalización de un usuario. 

- **Google Maps Integration:** Utiliza la API de Google Maps para mostrar un mapa interactivo en la aplicación.
- **Ubicación en Tiempo Real:** Rastrea y actualiza la ubicación de los usuarios en tiempo real.
- **Marcadores Personalizados:** Muestra marcadores personalizados para cada usuario, que pueden ser imágenes estáticas o cargadas desde una URL.

## Tecnologías Utilizadas

- **Flutter:** El proyecto está construido usando Flutter, un framework de UI de Google para crear aplicaciones natively compiladas.
- **Google Maps Flutter:** Para integrar Google Maps en la aplicación.
- **HTTP:** Para cargar imágenes de marcadores desde URLs.

## Estructura del Proyecto

El proyecto está organizado en varias carpetas clave:

- `/lib`: Contiene el código fuente Dart del proyecto.
  - `/models`: Define los modelos de datos, como `User`.
  - `/services`: Incluye servicios que manejan la lógica de negocio, como la carga de imágenes y la obtención de ubicaciones.
  - `/views`: Contiene las UIs, como la pantalla del mapa.
  - `/widgets`: Componentes UI reutilizables.
- `/assets`: Almacena recursos locales como imágenes.

## Configuración

Para ejecutar este proyecto, necesitarás configurar algunas claves API y permisos:

1. **Google Maps API Key:** Debes obtener una clave API de Google Maps y configurarla en tu proyecto para utilizar los servicios de mapas.

## Instalación

Para empezar con este proyecto, clona el repositorio y ejecuta los siguientes comandos en tu terminal:

```bash
flutter pub get
flutter run

🍽️ CucharealoApp
CucharealoApp es una aplicación móvil desarrollada en Kotlin que muestra los mejores restaurantes de una ciudad, junto con su plato más destacado, una imagen referencial y su ubicación en Google Maps.

📱 Características principales
Visualización de restaurantes destacados en una lista interactiva.

Fotografía representativa del restaurante o plato (almacenada en drawable).

Visualización del mejor plato ofrecido por cada restaurante.

Integración con Google Maps para mostrar la ubicación exacta del restaurante.

Al tocar un restaurante, se abre un mapa con un marcador indicando su ubicación.

📦 Estructura del proyecto
pgsql
Copiar
Editar
com.angelbustamante.cucharealoapp/
├── MainActivity.kt
├── MapsActivity.kt
├── model/Restaurante.kt
├── adapter/RestauranteAdapter.kt
├── res/
│   ├── layout/
│   │   ├── activity_main.xml
│   │   ├── activity_maps.xml
│   │   └── item_restaurante.xml
│   └── drawable/
│       ├── burger.jpg
│       ├── sushi.jpg
│       └── ceviche.jpg
🚀 Cómo ejecutar el proyecto
Clona este repositorio:

bash
Copiar
Editar
git clone https://github.com/tu-usuario/cucharealoapp.git
Abre el proyecto en Android Studio.

Asegúrate de tener una API Key válida de Google Maps con el SDK habilitado:

Agrega esto a tu AndroidManifest.xml dentro del <application>:

xml
Copiar
Editar
<meta-data
    android:name="com.google.android.geo.API_KEY"
    android:value="TU_API_KEY_AQUI" />
Ejecuta la aplicación en un emulador o dispositivo físico.

# 🍽️ CucharealoApp

**CucharealoApp** es una aplicación móvil desarrollada en **Kotlin** que muestra los mejores restaurantes de una ciudad, junto con su plato más destacado, una imagen referencial y su ubicación en Google Maps.

## 📱 Características principales

- Visualización de restaurantes destacados en una lista interactiva.
- Fotografía representativa del restaurante o plato (almacenada en `drawable`).
- Visualización del mejor plato ofrecido por cada restaurante.
- Integración con Google Maps para mostrar la ubicación exacta del restaurante.
- Al tocar un restaurante, se abre un mapa con un marcador indicando su ubicación.

## 📦 Estructura del proyecto

```
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
```

## 🚀 Cómo ejecutar el proyecto

1. Clona este repositorio:
   ```bash
   git clone https://github.com/tu-usuario/cucharealoapp.git
   ```

2. Abre el proyecto en **Android Studio**.

3. Asegúrate de tener una API Key válida de Google Maps con el SDK habilitado:
   - Agrega esto a tu `AndroidManifest.xml` dentro del `<application>`:

   ```xml
   <meta-data
       android:name="com.google.android.geo.API_KEY"
       android:value="TU_API_KEY_AQUI" />
   ```

4. Ejecuta la aplicación en un emulador o dispositivo físico.

## 📸 Capturas de pantalla

![Imagen de WhatsApp 2025-07-30 a las 09 20 54_3e8b4210](https://github.com/user-attachments/assets/407af26d-8f27-4e83-b31a-47b02f94995b)

![Imagen de WhatsApp 2025-07-30 a las 09 21 20_2ceb874c](https://github.com/user-attachments/assets/7e8dcbf6-751c-4c6c-acbc-956acbf5899a)


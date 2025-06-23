> [Ver en ingles/See in english](https://github.com/LuisMiSanVe/AndroidClickWidget/blob/main/README.md)
# 👆 Widget de Clics para Android
[![image](https://img.shields.io/badge/java-%23ED8B00.svg?style=for-the-badge&logo=openjdk&logoColor=white)](https://www.java.com/)
[![image](https://img.shields.io/badge/Android_Studio-3DDC84?style=for-the-badge&logo=android-studio&logoColor=white)](https://developer.android.com/studio)
[![image](https://img.shields.io/badge/Android-3DDC84?style=for-the-badge&logo=android&logoColor=white)](https://developer.android.com/studio)

Proyecto de plantilla simple para implementar Widgets con respuesta a clics.

## ⚙️ Explicación de uso del proyecto
Monta e instala la aplicación en tu dispositivo.

Deja presionado en la pantalla de inicio y busca por `ClickWidget` en la Lista de Widgets y añadelo.

Si le das clic, por defecto, cambiará su texto (esto puede ser modificado en el método [onReceive](https://github.com/LuisMiSanVe/AndroidClickWidget/blob/main/ClickWidget/app/src/main/java/com/luismisanve/clickwidget/MyWidgetProvider.java#L27)).

> [!IMPORTANT]
> Ya que esta App no incluye ninguna actividad, no saldrá en el típico cajón de aplicaciones, por lo que en caso de querer desinstalarlo, deberás buscarlo en la Lista de Aplicaciones de los ajustes.

## 📂 Archivos
Los archivos claves para mostrar el Widget son:
- [Manifest](https://github.com/LuisMiSanVe/AndroidClickWidget/blob/main/ClickWidget/app/src/main/AndroidManifest.xml#L15): En el manifesto, deberás incluir la etiqueta de `<receiver>`.
- [Layout](https://github.com/LuisMiSanVe/AndroidClickWidget/blob/main/ClickWidget/app/src/main/res/layout/activity_main.xml): El diseño del Widget.
- [Widget Info](https://github.com/LuisMiSanVe/AndroidClickWidget/blob/main/ClickWidget/app/src/main/res/xml/widget_info.xml): Archivo de configuracion XML con los ajustes del Widget.
- [Widget Receiver](https://github.com/LuisMiSanVe/AndroidClickWidget/blob/main/ClickWidget/app/src/main/java/com/luismisanve/clickwidget/MyWidgetProvider.java): Clase principal responsable de la creación y funcionalidad del Widget.

## 💻 Tecnologías usadas
- Lenguaje de programación: [Java](https://www.java.com/)
- Plantilla: No Activity
- API de Android: 24
- IDE Recomendado: [Android Studio](https://developer.android.com/studio)

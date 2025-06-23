> [See in spanish/Ver en español](https://github.com/LuisMiSanVe/AndroidClickWidget/blob/main/README.es.md)
# 👆 Android Click Widget
[![image](https://img.shields.io/badge/java-%23ED8B00.svg?style=for-the-badge&logo=openjdk&logoColor=white)](https://www.java.com/)
[![image](https://img.shields.io/badge/Android_Studio-3DDC84?style=for-the-badge&logo=android-studio&logoColor=white)](https://developer.android.com/studio)
[![image](https://img.shields.io/badge/Android-3DDC84?style=for-the-badge&logo=android&logoColor=white)](https://developer.android.com/studio)

Simple Template project to implement Widgets with click responsiveness.

## ⚙️ Project Usage Explanation
Build and install the app in your device.

Long press in the home screen and search `ClickWidget` in the Widget List and add it.

If you click it, by default, it will change its text (this can be changed in the [onReceive](https://github.com/LuisMiSanVe/AndroidClickWidget/blob/main/ClickWidget/app/src/main/java/com/luismisanve/clickwidget/MyWidgetProvider.java#L27) method).

> [!IMPORTANT]
> As this App doesn't include any activity, it won't display in the regular App Drawer, so in case you want to uninstall it, you must search it through the App list in the settings.

## 📂 Files
The key files that display the widget are:
- [Manifest](https://github.com/LuisMiSanVe/AndroidClickWidget/blob/main/ClickWidget/app/src/main/AndroidManifest.xml#L15): In the manifest, you must include this `<receiver>` tag.
- [Layout](https://github.com/LuisMiSanVe/AndroidClickWidget/blob/main/ClickWidget/app/src/main/res/layout/activity_main.xml): The Widget's design.
- [Widget Info](https://github.com/LuisMiSanVe/AndroidClickWidget/blob/main/ClickWidget/app/src/main/res/xml/widget_info.xml): XML config file with the Widget's settings.
- [Widget Receiver](https://github.com/LuisMiSanVe/AndroidClickWidget/blob/main/ClickWidget/app/src/main/java/com/luismisanve/clickwidget/MyWidgetProvider.java): Main class responsible of the creation and functionality of the Widget.

## 💻 Technologies Used
- Programming Language: [Java](https://www.java.com/)
- Template: No Activity
- Android API: 24
- Recommended IDE: [Android Studio](https://developer.android.com/studio)

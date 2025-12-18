# Custom Image Editor (Flutter)

A powerful and customizable **Flutter-based Image Editor** that allows users to **crop, paint, add text, and rotate images**.  
This project is suitable for learning purposes as well as for integrating basic image editing functionality into Flutter applications.

---
[Here’s the Complete Guide to Build an Image Editor in Flutter with Crop, Rotate, & Filter.](https://www.sevensquaretech.com/create-flutter-image-editor-crop-rotate-filter-github-code/)

## ✨ Features

- 📐 Crop images
- 🔄 Rotate images
- 🎨 Paint / draw on images
- 🔤 Add custom text overlays
- 🖼 Pick images from gallery or camera
- 💾 Save edited images locally
- 📱 Android support

---

## 📦 Package Information

- **Name:** custom_image_editor
- **Version:** 1.0.5
- **SDK:** Flutter (>=2.18.6 <3.0.0)
- **Platform:** Android

---

## 🔗 Repository Links

- **Homepage:** https://github.com/SevenSquare-Tech/image_editor.git
- **Repository:** https://github.com/SevenSquare-Tech/image_editor.git

---

## 🛠 Dependencies

This project uses the following Flutter packages:

- flutter
- cupertino_icons ^1.0.2
- uuid ^4.0.0
- provider ^6.0.5
- path_provider ^2.0.15
- image_picker ^1.0.1
- permission_handler ^11.0.1
- device_info_plus ^9.1.1

### Dev Dependencies

- flutter_test
- flutter_lints ^2.0.0

---

## 🚀 Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/SevenSquare-Tech/image_editor.git
   ```

2. Navigate to the project directory:

   ```bash
   cd image_editor
   ```

3. Install dependencies:

   ```bash
   flutter pub get
   ```

4. Run the app:
   ```bash
   flutter run
   ```

---

## 🔐 Permissions

Make sure to add the following permissions in your **AndroidManifest.xml**:

```xml
<uses-permission android:name="android.permission.READ_EXTERNAL_STORAGE"/>
<uses-permission android:name="android.permission.WRITE_EXTERNAL_STORAGE"/>
<uses-permission android:name="android.permission.CAMERA"/>
```

---

## 🎯 Use Cases

- Photo editing apps
- Profile picture editors
- Image annotation tools
- Learning Flutter canvas & gestures

---

## 🧩 Customization

You can extend this editor by adding:

- Filters
- Stickers / emojis
- Undo / redo stack
- Export to cloud (S3, Firebase, etc.)

---

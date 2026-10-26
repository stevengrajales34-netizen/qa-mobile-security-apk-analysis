# Análisis Estático de Aplicaciones Android (APK)

## Descripción
Este proyecto documenta la metodología para la inspección, descompilación y análisis de seguridad de aplicaciones Android (archivos .APK), como parte de mi formación en QA Engineering en TripleTen.

## Objetivo
Explorar las herramientas de ingeniería inversa para entender cómo se estructura una app, identificar posibles vulnerabilidades y preparar el terreno para auditorías de seguridad móvil.

## Metodología y Herramientas
El análisis se divide en dos rutas:
1. **Ejecución (Ruta 1):** Instalación de APK en emuladores (Android Studio / AVD) usando `adb install` para observar el comportamiento dinámico.
2. **Análisis Estático (Ruta 2):** 
   - **JADX:** Descompilación de archivos DEX a código Java legible.
   - **apktool:** Extracción de recursos y modificación de código SMALI.
   - **Android Studio (Profile or Debug APK):** Inspección y depuración de código SMALI.

## Aprendizajes Clave
- Comprensión de la estructura interna de una aplicación Android.
- Identificación de limitaciones al recompilar código descompilado.
- Base fundamental para pruebas de seguridad móvil (Mobile Security Testing).

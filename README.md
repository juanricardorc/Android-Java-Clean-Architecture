Clean Architecture, Android Java
================================

## Nueva versión disponible escrita en Kotlin:
[Clean Architecture, Android Kotlin](https://github.com/Juan-Ricardo/Clean-Architecture-Android-Kotlin)

Introducción
-----------------
Zineema es una aplicación para sistemas operativos android, usa minSdkVersion: 21, targetSdkVersion: 28, compileSdkVersion: 28. Fue construido utilizando el enfoque de la Arquitectura Limpia del tío Bob.

<a href="https://www.themoviedb.org/">
  <img alt="https://www.themoviedb.org/"
       src="https://www.themoviedb.org/assets/2/v4/logos/primary-green-d70eebe18a5eb5b166d5c1ef0796715b8d1a2cbc698f96d311d62f894ae87085.svg" width="124" height="124"/>
</a>

Para probar Zineema se requiere una cuenta de usuario TMDb para solicitar una clave API.
https://www.themoviedb.org/

## 1. Configuración de Clave API.
**Agregue la Clave API a su archivo gradle.properties:**
```javascript
# The setting is particularly useful for tweaking memory settings.
org.gradle.jvmargs=-Xmx1536m
# When configured, Gradle will run in incubating parallel mode.
# This option should only be used with decoupled projects. More details, visit
# http://www.gradle.org/docs/current/userguide/multi_project_builds.html#sec:decoupled_projects
# org.gradle.parallel=true
# AndroidX package structure to make it clearer which packages are bundled with the
# Android operating system, and which are packaged with your app's APK
# https://developer.android.com/topic/libraries/support-library/androidx-rn
android.useAndroidX=true
# Automatically convert third-party libraries to use AndroidX
android.enableJetifier=true

#Themovie
themovieApiKey=YourThemovieApiKey
```
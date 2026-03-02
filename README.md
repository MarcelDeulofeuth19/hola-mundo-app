# HolaMundoApp

Aplicacion Android basica desarrollada como evidencia de la actividad 2.2 (Programacion Movil).  
El proyecto implementa una pantalla inicial con el mensaje **"Hola Mundo"**, construida con **Kotlin** y **XML** en **Android Studio**.

## Repositorio oficial

GitHub: [https://github.com/MarcelDeulofeuth19/hola-mundo-app](https://github.com/MarcelDeulofeuth19/hola-mundo-app)

## Objetivo del proyecto

- Configurar un entorno de desarrollo Android.
- Crear una primera app funcional tipo Hola Mundo.
- Integrar control de versiones con Git y GitHub.
- Documentar estructura, archivos clave y flujo de trabajo.

## Tecnologias usadas

- Android Studio
- Kotlin
- Android SDK (compileSdk 34)
- Gradle Kotlin DSL
- Git + GitHub

## Requisitos

- Android Studio instalado (version reciente recomendada)
- JDK 17
- SDK de Android configurado
- Emulador Android o dispositivo fisico con depuracion USB

## Como ejecutar la app

1. Clona el repositorio:

```bash
git clone https://github.com/MarcelDeulofeuth19/hola-mundo-app.git
```

2. Abre la carpeta `HolaMundoApp` en Android Studio.
3. Espera la sincronizacion de Gradle.
4. Ejecuta la app con `Run` sobre un emulador o celular.

## Estructura del proyecto

```text
HolaMundoApp/
|-- app/
|   |-- build.gradle.kts
|   `-- src/main/
|       |-- AndroidManifest.xml
|       |-- java/com/example/holamundo/MainActivity.kt
|       `-- res/
|           |-- layout/activity_main.xml
|           `-- values/strings.xml
|-- build.gradle.kts
|-- gradle.properties
`-- settings.gradle.kts
```

## Archivos clave

- `MainActivity.kt`: actividad principal donde se inicializa la interfaz con `setContentView`.
- `activity_main.xml`: layout principal con `TextView` centrado.
- `strings.xml`: recursos de texto (`app_name` y `hola_mundo`).
- `AndroidManifest.xml`: declaracion de la actividad principal y configuracion general de la app.

## Flujo Git usado en esta actividad

```bash
git init
git add .
git commit -m "Proyecto base Hola Mundo"
git branch -M main
git remote add origin https://github.com/MarcelDeulofeuth19/hola-mundo-app.git
git push -u origin main
```

## Evidencia academica

Este repositorio acompana el informe de entrega con:

- Evidencias del codigo fuente.
- Evidencias de estructura del proyecto.
- Evidencias de configuracion con Git/GitHub.
- Documento final en Word/PDF.

## Contribucion

Si deseas proponer mejoras:

1. Crea una rama nueva desde `main`.
2. Realiza cambios pequenos y descriptivos.
3. Ejecuta `git add .` y `git commit -m \"mensaje\"`.
4. Sube la rama con `git push origin nombre-rama`.
5. Abre un Pull Request hacia `main`.

## Autor

- mdeulofeuth@alocredit.co

## Licencia

Uso academico.

# AndroidPokeDex

Aplicación Android desarrollada con Kotlin y Jetpack Compose que consume la API de Pokémon para explorar información detallada sobre tipos, estadísticas, habilidades y evoluciones.

## 🚀 Objetivo del proyecto

Este proyecto nace como una aplicación de portfolio para profundizar en el desarrollo Android moderno, aplicando buenas prácticas de arquitectura, testing, calidad de código y automatización mediante CI/CD.

## 📱 Características previstas

* Listado de Pokémon
* Búsqueda por nombre
* Detalle de Pokémon
* Información de estadísticas y habilidades
* Cadena evolutiva
* Gestión de favoritos
* Caché local para uso offline
* Diseño adaptado a Material 3

## 🛠️ Stack tecnológico

* Kotlin
* Jetpack Compose
* Material 3
* Navigation Compose
* Coroutines
* Flow
* ViewModel
* Retrofit
* Room
* Coil
* Hilt

## 🏗️ Arquitectura

La aplicación seguirá una arquitectura basada en principios Clean Architecture y separación de responsabilidades.

```text
UI
│
ViewModel
│
Use Cases
│
Repository
│
Data Sources
```

## 🧪 Calidad

El proyecto incorpora procesos automáticos para garantizar la calidad del código:

* GitHub Actions
* Pull Requests obligatorias
* Validación automática de compilación
* Ejecución de tests automatizados
* Análisis estático de código (próximamente)

## 🔄 CI/CD

Actualmente la pipeline verifica automáticamente:

* Compilación del proyecto Android
* Ejecución de pruebas durante el proceso de build

Próximamente:

* Detekt
* Cobertura de tests
* Generación de artefactos APK
* Firebase App Distribution

## 📦 Instalación

```bash
git clone <repository-url>
```

Abrir el proyecto con Android Studio y ejecutar:

```bash
./gradlew build
```

## 📚 API

Los datos se obtienen desde la PokéAPI:

https://pokeapi.co

## 👨‍💻 Autor

Diego Gómez Pulgarín

# ComposeCoroutinesExample

Esta es una aplicación sencilla desarrollada con Jetpack Compose y Kotlin que utiliza corutinas para simular la carga de datos en segundo plano.

## Características

- **Jetpack Compose** para la UI.
- **Kotlin Coroutines** para manejar operaciones en segundo plano.
- Una interfaz interactiva con:
  - Circulo de carga (`CircularProgressIndicator`).
  - Botón que inicia la tarea en segundo plano.

## Requisitos Previos

- **Kotlin 1.8+**.
- **Android Studio**.

## Dependencias
```gradle
    implementation(libs.androidx.core.ktx)
    implementation(libs.androidx.lifecycle.runtime.ktx)
    implementation(libs.androidx.activity.compose)
    implementation(platform(libs.androidx.compose.bom))
    implementation(libs.androidx.ui)
    implementation(libs.androidx.ui.graphics)
    implementation(libs.androidx.ui.tooling.preview)
    implementation(libs.androidx.material3)
    testImplementation(libs.junit)
    androidTestImplementation(libs.androidx.junit)
    androidTestImplementation(libs.androidx.espresso.core)
    androidTestImplementation(platform(libs.androidx.compose.bom))
    androidTestImplementation(libs.androidx.ui.test.junit4)
    debugImplementation(libs.androidx.ui.tooling)
    debugImplementation(libs.androidx.ui.test.manifest)

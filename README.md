# 📱 SafePass 2026 - Sistema de Gestión de Check-in

Repositorio oficial para el examen práctico de **Programación Móvil (RDA-1)**. Esta aplicación demuestra la implementación de un sistema robusto de gestión de asistentes, aplicando principios de programación segura en **Kotlin** y diseño de interfaces con **Jetpack Compose**.

---

## 🚀 Descripción del Proyecto
**SafePass 2026** es una solución móvil diseñada para el registro y validación segura de asistentes a eventos. El desarrollo se enfocó en la integridad de los datos y la gestión de estados reactivos, garantizando una experiencia de usuario fluida y libre de errores de ejecución mediante el uso de operadores de seguridad de Kotlin.

---

## 🛠️ Tecnologías y Conceptos Implementados

Esta aplicación integra buenas prácticas de desarrollo moderno bajo los estándares solicitados:

*   **Arquitectura de Datos:** Uso de `data class` inmutables para la representación de asistentes.
*   **Gestión de Estados:** Implementación de `sealed class` (`RegistroState`) para un manejo de estados seguro y exhaustivo (`when` expression).
*   **Programación Funcional:** Uso intensivo de:
    *   **Scope Functions:** `let`, `apply`, `run` para manipulación contextual de objetos.
    *   **Extension Functions:** Para mejorar la legibilidad y modularidad del código.
    *   **Higher-order functions:** Para lógica de negocio desacoplada.
*   **Seguridad:** Validación robusta de entradas mediante `toIntOrNull()` y `toDoubleOrNull()` junto con operadores de seguridad de Kotlin (`?.`, `?:`).
*   **UI Moderno:** Interfaz desarrollada con **Jetpack Compose** utilizando `Scaffold` y `Column` para una arquitectura de componentes escalable.

---

## ⚙️ Especificaciones Técnicas
*   **Lenguaje:** Kotlin
*   **IDE:** Android Studio
*   **JDK:** Java 21
*   **Target SDK:** API 36 (Android 16)
*   **UI Framework:** Jetpack Compose

---

## 📋 Estructura del Informe
El desarrollo del proyecto incluyó un informe académico detallado que cubre:
1.  **Arquitectura:** Diagramación del flujo de datos y manejo de estados.
2.  **Seguridad de Interfaz:** Análisis del uso de `sealed class` para evitar estados inconsistentes en la UI.
3.  **Evidencia de Pruebas:** Capturas de pantalla de los estados *Idle*, *Success* y *Error* en el emulador.

---

## 🎓 Autoría
*   **Materia:** Programación Móvil (RDA-1)
*   **Institución:** [Inserta el nombre de tu Universidad]
*   **Integrantes:**
    *   [Tu Nombre]
    *   [Nombre de tu compañero/a]

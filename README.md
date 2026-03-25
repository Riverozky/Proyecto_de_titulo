# 🌊 Sistema de Evacuación ante Tsunamis - Chile

## 📌 Resumen del Proyecto

Chile se encuentra en el "Cinturón de Fuego del Pacífico", siendo uno de los países más sísmicos del mundo. Ante la amenaza constante de tsunamis, la información oficial actual (ONEMI/SHOA) a menudo se presenta en formatos PDF enrevesados o poco accesibles durante una emergencia.

Esta solución propone una **plataforma web centralizada** que despliega mapas interactivos, simplificados y de carga veloz, permitiendo a los usuarios identificar zonas de evacuación y puntos de encuentro en cuestión de segundos, optimizando el tiempo de respuesta vital.

## 🎯 Objetivos

  * **OE1:** Facilitar el acceso a información crítica de evacuación.
  * **OE2:** Garantizar compatibilidad con dispositivos móviles (objetivo \>80%).
  * **OE3:** Diseñar una interfaz minimalista y fácil de usar bajo estrés.
  * **OE4:** Eliminar la saturación de información innecesaria en los mapas.

-----

## 🛠️ Tecnologías y Herramientas

  * **Desarrollo Web:** Google Sites (Host/Frontend), HTML/CSS.
  * **Sistemas de Información Geográfica (GIS):** \* Google Earth Pro (Modelado de polígonos de alta precisión).
      * Google My Maps (Visualización interactiva).
  * **Gestión de Proyecto:** Metodología **Scrum** (Sprints bi-semanales).
  * **Versionamiento:** GitHub.

-----

## 📋 Requerimientos Destacados

### Funcionales (RF)

| ID | Nombre | Descripción |
| :--- | :--- | :--- |
| **RF01** | Selección de Región | Navegación por zonas geográficas de Chile. |
| **RF03** | Mapas Interactivos | Visualización de capas de seguridad sobre mapas base. |
| **RF04** | Colaboración | Módulo para que usuarios aporten nuevos mapeos verificables. |
| **RF05** | Descarga | Exportación de mapas en formato `.KMZ` para uso offline. |

### No Funcionales (RNF)

  * **Desempeño:** Tiempo de respuesta menor a 10 segundos.
  * **Compatibilidad:** Operativo en el 90% de sistemas Android actuales.
  * **Accesibilidad:** Interfaz simplificada siguiendo directrices de Google.

-----

### Gestión de Calidad (ISO-9126)

Se evaluaron 6 pilares fundamentales:

1.  Adaptabilidad (Multi-dispositivo).
2.  Comportamiento temporal (Velocidad).
3.  Conformidad.
4.  Facilidad de aprendizaje.
5.  Capacidad de modificación.
6.  Operabilidad.

-----

## 📱 Entornos de Prueba

El sistema fue testeado exitosamente en:

  * **Gama Alta:** Samsung A51 (Android 12).
  * **Legacy:** Samsung Galaxy Core 2 (Android 4.4.2 KitKat).
  * **Tablet:** iPad 7ma Gen (iOS 15.5).

-----

## 👤 Autor

**Rodrigo Ignacio Rivero Esparza**

  * Estudiante de Ingeniería en Computación e Informática.
  * Universidad Andrés Bello.

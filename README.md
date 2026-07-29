# TriEspañaApp ⚽🇪s

## Orientación del Proyecto
Esta aplicación móvil está orientada a mostrar información básica y estilizada de la Selección Española de Fútbol ("La Es"). Está diseñada como un proyecto educativo y práctico para comprender la estructura moderna de desarrollo móvil híbrido, enfocándose en la identidad visual de Ecuador (Amarillo, Azul y blanco) mediante una interfaz limpia, atractiva y fácil de explicar.

---

## Tecnologías y Herramientas Utilizadas

Para la construcción de esta aplicación se utilizaron las siguientes tecnologías y conceptos clave de desarrollo móvil:

* **React Native con Expo Go (SDK 51+):** Plataforma para el desarrollo de la aplicación permitiendo la visualización en tiempo real en un dispositivo físico.
* **TypeScript:** Lenguaje de programación tipado para garantizar un código limpio y libre de errores en los componentes.
* **Expo Router (File-based Routing):** Sistema de navegación basado en archivos dentro de la carpeta `app/`, estructurado mediante un contenedor de pila (`Stack`) que gestiona el flujo entre pantallas de forma nativa.
* **Componentes Fundamentales de React Native:**
  * `View`: Contenedor base para estructurar los bloques de la interfaz.
  * `Text`: Renderizado de títulos, fichas técnicas y etiquetas informativas.
  * `Image`: Despliegue de recursos visuales locales (como el escudo oficial de la FEF).
  * `ScrollView`: Implementación de desplazamiento vertical responsivo para la pantalla principal.
  * `ActivityIndicator`: Componente nativo de carga animada dentro de la pantalla de bienvenida.
* **Diseño y Estilos (`StyleSheet`):** Uso de Flexbox (`flexDirection`, `justifyContent`, `alignItems`) junto con propiedades de sombreado (`elevation`, `shadowColor`) para construir una tarjeta de información moderna y adaptable a pantallas de diversos tamaños.
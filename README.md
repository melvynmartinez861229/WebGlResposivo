# Proyecto Unity WebGL - [Nombre del Proyecto]

## Descripción

Este proyecto es un juego desarrollado en Unity y exportado para WebGL. El objetivo es proporcionar una experiencia de usuario fluida y responsiva, manteniendo la relación de aspecto de 1920x1080 (Full HD) sin importar el tamaño de la ventana del navegador. Este README proporciona instrucciones sobre cómo configurar y ejecutar el proyecto.

## Requisitos

- Unity 2020.3 o superior
- Navegador web moderno (Chrome, Firefox, Edge, etc.)

## Configuración del Canvas en Unity

### Canvas Scaler

1. **Configura el Canvas**:
   - Selecciona tu Canvas en la jerarquía de Unity.
   - Asegúrate de que el componente **Canvas Scaler** esté presente.
   - Configura el **UI Scale Mode** a **Scale With Screen Size**.
   - Establece la **Reference Resolution** a `1920 x 1080`.
   - Ajusta el **Screen Match Mode** a **Match Width Or Height** y ajusta el slider según tus necesidades (puedes empezar con 0.5).

### RectTransform

2. **Ajusta los RectTransforms**:
   - Asegúrate de que todos los elementos UI dentro del Canvas tengan sus **RectTransforms** configurados correctamente.
   - Utiliza anclajes para que los elementos se posicionen y escalen adecuadamente en relación con el Canvas.

## Ejecución del Proyecto
Abre el archivo index.html en un navegador web.
Asegúrate de que el Canvas mantenga la relación de aspecto de 1920x1080 y que los elementos de la escena se escalen correctamente.

Notas
Asegúrate de probar el juego en diferentes tamaños de ventana y resoluciones para verificar que el Canvas y los elementos de la escena se ajusten correctamente.
Puedes ajustar los márgenes y paddings en el CSS según sea necesario para mejorar la apariencia de la UI.




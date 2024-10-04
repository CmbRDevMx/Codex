Aquí tienes una etiqueta `<iframe>` de YouTube que es completamente responsiva y tiene bordes 3D y sombras azules. He incluido los estilos dentro de la etiqueta para que puedas añadirla directamente a tu página:

```html
<div style="position: relative; padding-bottom: 56.25%; height: 0; overflow: hidden; border-radius: 15px; box-shadow: 0 4px 30px rgba(0, 0, 255, 0.5);">
    <iframe 
        src="https://www.youtube.com/embed/VIDEO_ID" 
        title="YouTube video player" 
        frameborder="0" 
        allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" 
        allowfullscreen 
        style="position: absolute; top: 0; left: 0; width: 100%; height: 100%; border-radius: 15px; border: 5px solid rgba(0, 0, 255, 0.7);"
    ></iframe>
</div>
```

### Instrucciones
1. Reemplaza `VIDEO_ID` con el ID del video de YouTube que deseas mostrar.
2. Puedes ajustar los valores de `border-radius` y `box-shadow` para personalizar la apariencia según tu diseño.

### Descripción de los estilos:
- **Responsividad:** El `<div>` con `padding-bottom: 56.25%` permite que el `<iframe>` mantenga una relación de aspecto de 16:9, lo que lo hace completamente responsivo.
- **Bordes y sombras:** Se han agregado bordes azules con un efecto de sombra que da una sensación de profundidad y estilo 3D.
- **Border-radius:** Se aplicó un radio de borde para suavizar las esquinas del video.

Aquí tienes una etiqueta `<img>` con estilos similares para que las imágenes sean responsivas y tengan bordes 3D con sombras azules. Incluí los estilos dentro de la etiqueta para que puedas añadirla directamente a tu página:

```html
<div style="position: relative; overflow: hidden; border-radius: 15px; box-shadow: 0 4px 30px rgba(0, 0, 255, 0.5);">
    <img 
        src="IMAGE_URL" 
        alt="Descripción de la imagen" 
        style="width: 100%; height: auto; border-radius: 15px; border: 5px solid rgba(0, 0, 255, 0.7);"
    />
</div>
```

### Instrucciones
1. Reemplaza `IMAGE_URL` con la URL de la imagen que deseas mostrar.
2. Modifica la descripción en `alt` para que sea relevante a la imagen que estás utilizando.

### Descripción de los estilos:
- **Responsividad:** Al establecer `width: 100%` y `height: auto`, la imagen se ajustará al ancho de su contenedor mientras mantiene su relación de aspecto.
- **Bordes y sombras:** Se aplican bordes azules y una sombra que le da un efecto 3D a la imagen.
- **Border-radius:** Se aplica un radio de borde para suavizar las esquinas de la imagen, dándole un aspecto más elegante. 

Puedes usar esta estructura para añadir imágenes a tu página con un estilo atractivo y moderno.

# Insiders Clinic — Disfruta el viaje

Propuesta de sitio web en español para Insiders Clinic, basada en su perfil público de Instagram y en el directorio de Alastin México. Investigación: 9 de octubre de 2026.

## Experiencia

- Cuatro páginas independientes: Healthcare, Insiders Core, Uniqueness y Longevity Journey.
- Colorimetría plata, gris, azul petróleo y aqua; Journey transforma toda la página a vino y rojo suave.
- Logo original suministrado por el usuario y fotografías/referencias de sus historias.
- Home con planeta 3D y conexiones internacionales. Healthcare con membrana de sérum, Core con núcleos metálicos, Uniqueness con cinta continua y Journey con órbitas rojas. Cada destino tiene composición propia, respuesta al cursor, arrastre y pausa.
- Healthcare integra aparatología, medicina estética, medicina funcional y regenerativa, y farmacia.
- Etapas interactivas de Journey, contacto por WhatsApp y espacio conceptual 3D.
- Navegación móvil, diálogos accesibles y respeto a movimiento reducido.

## Ejecución

Sitio estático sin build. Servir la carpeta del repositorio con cualquier servidor HTTP:

```sh
python3 -m http.server 4173
```

Abrir http://localhost:4173. Los archivos Three.js se incluyen localmente; no se requiere npm para servir. Fuentes Google Fonts cuentan con tipografía alternativa local. WebGL es necesario para el modelo 3D; existe alternativa visual para el hero.

## Investigación y límites

- https://www.instagram.com/insiders_clinic/ — perfil leído mediante navegador: “INSIDERS | Viaje a la longevidad”, “Aesthetics l Longevity Clinic”, GDL, “By @dra.alexcastro”, “@longevity.speakeasy”, enlace WhatsApp 3319045014. Las publicaciones se revisaron posteriormente en Safari con la sesión del usuario: protocolos personalizados de piel, Programas Origen y Origen Gastro, Fullface Regenerativo, Botox, HydraFacial y medicina regenerativa.
- https://alastin.mx/pages/store-locator — Insiders Clinic: C. Palermo 2976, INT.1, Prados Providencia, Guadalajara, Jalisco 44670; teléfono 3319045014.

Los tratamientos mencionados proceden de publicaciones de Insiders; no se inventaron precios, credenciales, testimonios ni resultados clínicos. La dirección debe confirmarse al agendar. Las descripciones son editoriales y la disponibilidad actual de los programas debe confirmarse con la clínica. La imagen y el recorrido 3D no representan las instalaciones reales. Esta propuesta no se presenta como el sitio oficial de la clínica. No hay relación con Apple.

## Identidad e imágenes

El logo original y las cinco referencias de historias fueron proporcionados por el usuario. Los encuadres se realizan mediante CSS. Las imágenes conceptuales generadas de la primera propuesta se conservan en assets como archivo y no se muestran en la versión actual. La procedencia se documenta en ASSETS.md.

## Dependencias

Three.js, licencia MIT en `assets/THREE-LICENSE.txt`. Los modelos se construyen por código en `app.js`. No se recopilan datos personales, no existe backend de reservas y no se confirma ninguna cita desde la web.

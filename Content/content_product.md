
# 🎯 Objetivo del Prompt
Eres un experto en desarrollo de negocios y marketing digital. Tu tarea es analizar la información estratégica y de marca proporcionada sobre una empresa o individuo, y generar 4 ideas realistas y accionables de productos o servicios, alineadas con su identidad, propuesta de valor y presencia SEO.
La salida debe ser un objeto JSON que contenga un array de 4 objetos. Cada objeto debe tener las siguientes claves:

## 🧠 Instrucciones Claras
Lee cuidadosamente la representación y el contenido SEO proporcionado:

{{content_avatar}}: Describe cómo se presenta o personifica la marca.

{{content_seo}}: Contenido orientado a posicionamiento, nicho o intenciones del usuario.

Genera 4 ideas de productos o servicios:

Deben ser viables según la industria y el contexto SEO.

Orientados a aportar valor, resolver un problema o escalar la presencia digital.

Cada uno debe tener título, imagen y descripción clara en markdown.

Formato de salida estructurado:

JSON con un array de 4 objetos.

Cada objeto debe tener exactamente las siguientes propiedades (ver estructura esperada más abajo).

---
## Output

```Template ```

[
  {
    "name": "Producto_1",
    "nombre_producto_o_servicio": "Título breve y claro del producto o servicio",
    "imagen_url": "https://placehold.co/600x400/png?text=+",
    "descripcion_comercial": "Genera una descripcion con una orientacion de venta o comercial con esta estructura en formato markdown ## Título del producto o servicio\n\n* Punto 1 que explique una característica clave\n* Punto 2 que indique un beneficio concreto\n* Punto 3 sobre el público al que va dirigido o un uso destacado\n\n---",
    "descripcion_tecnica":"Genera una descripcion orientada al aspecto tecnico del producto, los puntos clave para el desarrollo de este",
    "problema_principal": "",
    "escenario_real": "",
    "audiencia_objetivo": "",
    "solucion_resumida": "",
    "caracteristicas_clave": [],
    "diferenciador": "",
    "modelo_negocio": "",
    "modo_validacion": "",
    "potencial_escalado": "",
    "nivel_innovacion": "",
    "elevator_pitch": "",
    "hecho_por": "Generado por IA"
  },
  {
    "name": "Producto_2",
    "nombre_producto_o_servicio": "Título breve y claro del producto o servicio",
    "imagen_url": "https://placehold.co/600x400/png?text=+",
    "descripcion_comercial": "Genera una descripcion con una orientacion de venta o comercial con esta estructura en formato markdown ## Título del producto o servicio\n\n* Punto 1 que explique una característica clave\n* Punto 2 que indique un beneficio concreto\n* Punto 3 sobre el público al que va dirigido o un uso destacado\n\n---",
    "descripcion_tecnica":"Genera una descripcion orientada al aspecto tecnico del producto, los puntos clave para el desarrollo de este",
    "problema_principal": "",
    "escenario_real": "",
    "audiencia_objetivo": "",
    "solucion_resumida": "",
    "caracteristicas_clave": [],
    "diferenciador": "",
    "modelo_negocio": "",
    "modo_validacion": "",
    "potencial_escalado": "",
    "nivel_innovacion": "",
    "elevator_pitch": "",
    "hecho_por": "Generado por IA"
  },
  {
    "name": "Producto_3",
    "nombre_producto_o_servicio": "Título breve y claro del producto o servicio",
    "imagen_url": "https://placehold.co/600x400/png?text=+",
    "descripcion_comercial": "Genera una descripcion con una orientacion de venta o comercial con esta estructura en formato markdown ## Título del producto o servicio\n\n* Punto 1 que explique una característica clave\n* Punto 2 que indique un beneficio concreto\n* Punto 3 sobre el público al que va dirigido o un uso destacado\n\n---",
    "descripcion_tecnica":"Genera una descripcion orientada al aspecto tecnico del producto, los puntos clave para el desarrollo de este",
    "problema_principal": "",
    "escenario_real": "",
    "audiencia_objetivo": "",
    "solucion_resumida": "",
    "caracteristicas_clave": [],
    "diferenciador": "",
    "modelo_negocio": "",
    "modo_validacion": "",
    "potencial_escalado": "",
    "nivel_innovacion": "",
    "elevator_pitch": "",
    "hecho_por": "Generado por IA"
  },
  {
    "name": "Producto_4",
    "nombre_producto_o_servicio": "Título breve y claro del producto o servicio",
    "imagen_url": "https://placehold.co/600x400/png?text=+",
    "descripcion_comercial": "Genera una descripcion con una orientacion de venta o comercial con esta estructura en formato markdown ## Título del producto o servicio\n\n* Punto 1 que explique una característica clave\n* Punto 2 que indique un beneficio concreto\n* Punto 3 sobre el público al que va dirigido o un uso destacado\n\n---",
    "descripcion_tecnica":"Genera una descripcion orientada al aspecto tecnico del producto, los puntos clave para el desarrollo de este",
    "problema_principal": "",
    "escenario_real": "",
    "audiencia_objetivo": "",
    "solucion_resumida": "",
    "caracteristicas_clave": [],
    "diferenciador": "",
    "modelo_negocio": "",
    "modo_validacion": "",
    "potencial_escalado": "",
    "nivel_innovacion": "",
    "elevator_pitch": "",
    "hecho_por": "Generado por IA"
  }
]


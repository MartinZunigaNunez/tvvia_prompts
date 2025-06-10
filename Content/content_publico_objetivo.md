🎯 Prompt optimizado para generar perfil de público objetivo

## 🎯 Objetivo

Eres un experto en análisis de mercado y segmentación de audiencias. Respira hondo y piensa paso a paso.

Tu tarea es analizar el perfil empresarial y, a partir de él, construir un perfil completo, coherente y accionable del público objetivo de la empresa **{{company_name}}**.

- **Personificación de la empresa**:  
  ```text
  {{content_avatar}}

🧠 Instrucciones
Usa toda la información disponible para inferir características demográficas, psicográficas y comportamentales del cliente ideal.

Si algún dato está incompleto o es ambiguo, infierelo de forma creativa y coherente con el contexto de la empresa.

Usa tono profesional y una estructura clara para que el resultado sea útil en estrategias de comunicación, contenidos o IA generativa.

Sigue estrictamente el siguiente template JSON. No añadas ni omitas campos ni cambies su estructura o nombres.

El campo resumen_mkd debe estar en formato markdown, siguiendo exactamente la estructura que se indica.

## Template output JSON
{
  "name": "Genera un nombre genérico y apellido común, por ejemplo Juan Pérez o Camila Soto",
  "resumen_mkd": "## {{name}}\n`Palabra1` `Palabra2` `Palabra3`\n\n---\n### Ubicación:\nDescripción resumida de la ubicación\n\n### Edad:\nDescripción resumida de la edad\n\n### Género:\nDescripción resumida del género del público objetivo\n\n### Preferencias:\nResumen breve de las preferencias del público",
  "ubicacion": "Define la ubicación y áreas geográficas clave del público objetivo",
  "descripcion_demografica": "Describe el perfil demográfico del público objetivo",
  "edad": "Rango de edad principal del público objetivo",
  "genero": "Género predominante o mixto",
  "nivel_socioeconomico": "Segmento socioeconómico predominante (ej: medio, medio-alto, ABC1)",
  "items": [
    {
      "clave": "caracteristicas_psicograficas",
      "titulo": "Características psicográficas",
      "icono": "mdi:user",
      "body": "## Características psicográficas\n[Texto en prosa con mínimo 330 caracteres, sin markdown embebido]"
    },
    {
      "clave": "preferencias_compra",
      "titulo": "Preferencias de compra",
      "icono": "mdi:local-mall-outline",
      "body": "## Preferencias de compra\n[Texto en prosa con mínimo 330 caracteres, sin markdown embebido]"
    },
    {
      "clave": "valores",
      "titulo": "Valores",
      "icono": "mdi:approval",
      "body": "## Valores\n[Texto en prosa con mínimo 330 caracteres, sin markdown embebido]"
    },
    {
      "clave": "necesidades_y_motivaciones",
      "titulo": "Necesidades y motivaciones",
      "icono": "mdi:emoticon",
      "body": "## Necesidades y motivaciones\n[Texto en prosa con mínimo 330 caracteres, sin markdown embebido]"
    },
    {
      "clave": "factores_de_influencia_compra",
      "titulo": "Factores de influencia en la compra",
      "icono": "mdi:shopping-bascket-plus-outline",
      "body": "## Factores de influencia en la compra\n[Texto en prosa con mínimo 330 caracteres, sin markdown embebido]"
    }
  ],
  "producto_servicio_asociados": [
    {
      "clave": "producto_1",
      "descripcion": "Descripción de un producto o servicio asociado a la empresa que sea relevante para el público objetivo",
      "id": "1",
      "titulo": "Nombre del producto o servicio 1"
    },
    {
      "clave": "producto_2",
      "descripcion": "Descripción de un producto o servicio asociado a la empresa que sea relevante para el público objetivo",
      "id": "2",
      "titulo": "Nombre del producto o servicio 2"
    }
  ]
}


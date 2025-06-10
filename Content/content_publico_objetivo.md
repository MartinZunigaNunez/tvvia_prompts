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
  "resumen_mkd": "## {{name}}\n`Palabra1` `Palabra2` `Palabra3`\n\n---\n### Descripcion resumida de las aristas mas importantes y destacables del segmento generado (formato markdown maximo 550 aracteres)",
  "ubicacion": "Define la ubicación y áreas geográficas clave del público objetivo",
  "descripcion_demografica": "Describe el perfil demográfico del público objetivo",
  "edad": "Rango de edad principal del público objetivo",
  "genero": "Género predominante o mixto",
  "nivel_socioeconomico": "Segmento socioeconómico predominante (ej: medio, medio-alto, ABC1)",
  "comportamiento_estilo_de_vida": "Genera una descripion precisa y detallada de el comportamiento y el estilo de vida del segmento en formato markdwn con la siguinte estructura (max 1000 caracteres):
  ## Estilo de vida (salto de linea) detalle del estilo de vida (salto de linea)
  ## Interes (salto de linea) detalle de los intereses (salto de linea)
  ## Comportamiento de compra (salto de linea) detalle del comportaminto de compras (salto de linea)
  ## Proceso de toma de decisiones de compra (salto de linea) analisis del proceso que realisaria el segmento para realizar una compra 
  "items": [
    {
      "clave": "caracteristicas_psicograficas",
      "titulo": "Características psicográficas",
      "icono": "mdi:user",
      "body": "## Características psicográficas\n[formato markdown mínimo 330 caracteres maximo 800 caracteres]"
    },
    {
      "clave": "preferencias_compra",
      "titulo": "Preferencias de compra",
      "icono": "mdi:local-mall-outline",
      "body": "## Preferencias de compra\n[formato markdown mínimo 330 caracteres maximo 800 caracteres]"
    },
    {
      "clave": "valores",
      "titulo": "Valores",
      "icono": "mdi:approval",
      "body": "## Valores\n[formato markdown mínimo 330 caracteres maximo 800 caracteres]"
    },
    {
      "clave": "necesidades_y_motivaciones",
      "titulo": "Necesidades y motivaciones",
      "icono": "mdi:emoticon",
      "body": "## Necesidades y motivaciones\n[formato markdown mínimo 330 caracteres maximo 800 caracteres]"
    },
    {
      "clave": "factores_de_influencia_compra",
      "titulo": "Factores de influencia en la compra",
      "icono": "mdi:shopping-bascket-plus-outline",
      "body": "## Factores de influencia en la compra\n[formato markdown mínimo 330 caracteres maximo 800 caracteres]"
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


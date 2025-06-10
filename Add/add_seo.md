# 🧠 Prompt para Generación de Nuevas Palabras Clave SEO

## 🎯 Objetivo

Eres un estratega SEO especializado en contenido digital con alta intención de búsqueda.  
Tu tarea es **generar nuevas palabras clave relevantes y específicas**, acompañadas de frases asociadas y ejemplos útiles para planificación de contenido, campañas o posicionamiento en buscadores.

---

## 📝 Instrucciones

1. Genera palabras clave de **alta intención** (informativa, transaccional o de navegación), orientadas a usuarios reales.  
2. Por cada palabra clave, incluye un grupo de **frases relacionadas** (búsquedas comunes o queries).  
3. Incluye además **ejemplos de uso en contexto**, como títulos de blog, preguntas frecuentes o ideas de contenido.  
4. **Evita palabras genéricas o sin foco claro.**  
5. La salida debe ser exclusivamente un `array JSON`, con esta estructura exacta:

 ## Input

{
  "tema_principal": "nutrición deportiva",
  "enfoque": "personas que hacen deporte de forma amateur y quieren mejorar su rendimiento",
  "cantidad_palabras": 5
}

---

## 📤 Output esperado

```json
[
  {
    "palabra_clave": "automatización marketing pymes",
    "frases": [
      "cómo automatizar marketing para pequeñas empresas",
      "mejores herramientas de automatización de marketing",
      "automatización de correos para pymes"
    ],
    "ejemplos": [
      "Guía completa: Cómo automatizar tu marketing si eres una pyme",
      "Top 5 herramientas de automatización que toda pyme debería usar",
      "¿Vale la pena automatizar el marketing siendo pequeño?"
    ]
  }
]
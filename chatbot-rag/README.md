# Chatbot RAG con Documentos

Chatbot de inteligencia artificial que responde preguntas basándose únicamente en documentos propios, usando la técnica RAG (Retrieval Augmented Generation). El modelo no inventa información — solo responde con lo que encuentra en los documentos cargados.

## Cómo funciona

1. Carga el documento y lo divide en fragmentos
2. Guarda los fragmentos en ChromaDB (base de datos vectorial)
3. Busca los fragmentos más relevantes según la pregunta del usuario
4. Genera una respuesta basada solo en esos fragmentos usando LLaMA 3.1

## Resultados

- Responde preguntas con información del documento
- Reconoce cuando no tiene información suficiente (no alucina)
- Funciona en modo interactivo de conversación

## Tecnologías

- Python
- ChromaDB (base de datos vectorial)
- Groq API (LLaMA 3.1 8B)
- Google Colab

## Casos de uso reales

- Chatbot para manuales internos de empresas
- Asistente para documentos legales o médicos
- Soporte al cliente basado en documentación propia

## Estructura

```
chatbot_rag.ipynb   # Notebook principal con todo el código
utah_info.txt       # Documento de prueba
```

## Próximos pasos

- Soportar archivos PDF reales
- Agregar interfaz web con Streamlit
- Mejorar el prompt para eliminar alucinaciones

---
*Proyecto desarrollado como parte de mi preparación para trabajar en AI/ML en EE.UU.*

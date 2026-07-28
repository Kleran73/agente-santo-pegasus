# Agente Inteligente - Santo Pegasus Soluciones
Challenge Alura - Agente de IA con documentos internos

## Descripción
Agente de inteligencia artificial capaz de responder preguntas sobre la documentación interna de **Santo Pegasus Soluciones**.

Los documentos utilizados son:
- Manual de Onboarding para Nuevos Desarrolladores
- Arquitectura de Microservicios y Mapa de Dominios
- Protocolo de Respuesta a Incidentes y Post-Mortems
- Guía Oficial de Ingeniería Back-end
- Guía Oficial de Ingeniería Front-end

## Arquitectura
1. Carga de los 5 documentos PDF oficiales
2. División del texto en chunks
3. Generación de embeddings con sentence-transformers
4. Base vectorial FAISS
5. Cadena RetrievalQA con LangChain
6. Modelo de lenguaje de Hugging Face
7. Despliegue en Oracle Cloud Infrastructure (OCI)

## Tecnologías utilizadas
- Python
- LangChain + LangChain Classic
- Hugging Face (flan-t5 / Mistral)
- FAISS
- PyPDF
- Sentence-Transformers
- Oracle Cloud Infrastructure (OCI Compute)

## Cómo ejecutar
```bash
pip install -r requirements.txt
# Luego abrir el notebook en Google Colab o ejecutar el código

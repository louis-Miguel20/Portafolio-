<div align="center">

# Luis Miguel Rambao Sánchez
### Machine Learning Engineer · MLOps · RAG Systems · Conversational Agents

📍 Córdoba, Colombia &nbsp;|&nbsp; 📧 lmiguelrambao@gmail.com &nbsp;|&nbsp; 📱 (+57) 305 401 3772

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](#)
[![Email](https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:lmiguelrambao@gmail.com)

</div>

---

## 👨‍💻 Sobre mí

Machine Learning Engineer con experiencia comprobada en el diseño y despliegue de modelos ML en producción — desde el concepto hasta el deploy. Especializado en **pipelines end-to-end, RAG Systems, LLMs, MLOps y observabilidad**. Construyo soluciones que generan impacto medible: menos latencia, más precisión, costos reducidos.

> Cada sistema que entrego incluye monitoreo, CI/CD, pruebas y métricas reales de negocio.

---

## 🧰 Stack Tecnológico

```
Lenguajes        Python · Rust · SQL
IA & ML          TensorFlow · Scikit-learn · HuggingFace · LangChain · LangGraph · LLMs · RAG
MLOps            MLflow · Kubeflow · BentoML · Seldon · GitHub Actions · CI/CD
Infra & Cloud    AWS · Docker · Kubernetes · Grafana · Prometheus
```

---

## 💼 Experiencia Profesional

### 🔬 Machine Learning Engineer — Universidad de Córdoba
**Jun 2023 – Feb 2024 · Smart Document Processing System**

Pipeline de clasificación documental con fine-tuning de **BERT** y flujos multi-agente en **LangGraph** para extracción automática de datos no estructurados.

| Resultado | Métrica |
|---|---|
| Reducción de revisión manual | **67%** |
| Precisión de extracción | **91%** en 8 tipos de documentos |
| Aceleración en recuperación de información | **5×** |
| F1-score final (desde 0.78) | **0.92** — 12 iteraciones con MLflow |
| Latencia de inferencia | **200 ms** por documento |

---

### ⚙️ Machine Learning Engineer — Universidad de Córdoba
**Mar 2024 – Nov 2024 · RAG Platform con A/B Testing**

Diseño y despliegue de dos pipelines RAG (dense vs. hybrid retrieval) con evaluación sobre 1,200 consultas, dashboards de monitoreo personalizados y alertas de drift automático.

| Resultado | Métrica |
|---|---|
| Mejora en precisión de respuestas | **+37%** |
| Reducción en tiempo de respuesta | **28%** |
| Disponibilidad del sistema | **99.3% uptime** |

---

### 🚀 Machine Learning Engineer — Universidad de Córdoba
**Dic 2024 – Jun 2025 · Real-time MLOps**

Pipeline ML escalable en **AWS + Kubernetes + Kubeflow** con CI/CD completo (GitHub Actions, BentoML, Seldon) y observabilidad full-stack con Grafana y Prometheus.

| Resultado | Métrica |
|---|---|
| Reducción de latencia | **42%** |
| Aumento de throughput | **3×** |
| Ciclo de release (de 7 días a) | **1 día** · rollback en 5 min |
| Reducción de costos de infraestructura | **26%** |
| Disponibilidad | **99.9% uptime** |

---

## 🗂️ Proyectos

---

### 🏥 [Audifarma Agenda Assistant](https://github.com/louis-Miguel20/audifarma-agenda-assistant)
**Agendamiento médico por lenguaje natural — sin formularios, sin llamadas**

![Python](https://img.shields.io/badge/Python_3.12-3776AB?style=flat-square&logo=python&logoColor=white)
![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=flat-square&logo=chainlink&logoColor=white)
![LangGraph](https://img.shields.io/badge/LangGraph-FF6B6B?style=flat-square)
![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?style=flat-square&logo=streamlit&logoColor=white)
![OpenAI](https://img.shields.io/badge/OpenAI-412991?style=flat-square&logo=openai&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)

Agente inteligente con **LangChain + LangGraph** que interpreta instrucciones en lenguaje natural y las ejecuta sobre una agenda real persistida en Excel.

```
Usuario:   "Agrega 'Reunión de optometría' el 2025-12-21 a las 09:30"
Asistente: "✅ Evento agregado para el 21 de diciembre a las 9:30 AM."

Usuario:   "¿Qué tengo el 21?"
Asistente: "Tienes 1 evento: Reunión de optometría a las 09:30."
```

**Impacto para el sector salud:** agendamiento en < 60 segundos, memoria conversacional por sesión, resiliencia ante corrupción de datos, CI/CD y Docker listos para producción.

`LangChain` · `LangGraph` · `Streamlit` · `OpenAI GPT` · `Docker` · `pytest` · `GitHub Actions`

---

### 🧠 [RAD Advanced — Sistema RAG Fullstack](https://github.com/louis-Miguel20/rad-advanced)
**Convierte documentos corporativos en conocimiento consultable con IA**

![Next.js](https://img.shields.io/badge/Next.js_15-000000?style=flat-square&logo=nextdotjs&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL+pgvector-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![MLflow](https://img.shields.io/badge/MLflow-0194E2?style=flat-square&logo=mlflow&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)

Sistema RAG híbrido fullstack — sube un documento, pregúntale en lenguaje natural, recibe respuestas con citación exacta de fuentes.

```
Next.js 15 + Vercel AI SDK  →  FastAPI (Python)  →  PostgreSQL + pgvector
                                                  →  OpenAI GPT-4o + Embeddings
                                                  →  MLflow (tracking & feedback)
```

**Impacto empresarial:** búsqueda semántica sobre documentación interna, monitoreo de calidad de respuestas con MLflow, infraestructura completa con Docker Compose y CI/CD.

`Next.js` · `FastAPI` · `pgvector` · `GPT-4o` · `LangChain` · `MLflow` · `Docker` · `TypeScript`

---

### 💬 [Asistente Conversacional RAG](https://github.com/louis-Miguel20/Asistente-conversacional-IA)
**API REST + interfaz web para consultar cualquier documento técnico con IA**

![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=flat-square&logo=chainlink&logoColor=white)
![FAISS](https://img.shields.io/badge/FAISS-00599C?style=flat-square)
![HuggingFace](https://img.shields.io/badge/HuggingFace-FFD21E?style=flat-square&logo=huggingface&logoColor=black)
![OpenAI](https://img.shields.io/badge/GPT--4o--mini-412991?style=flat-square&logo=openai&logoColor=white)

Asistente que indexa PDFs y TXTs con embeddings locales (HuggingFace + FAISS) y responde preguntas con citación precisa de fuentes — sin enviar datos sensibles a la nube.

**Impacto para equipos técnicos:** API REST integrable con cualquier sistema (`/upload`, `/ask`, `/health`), arquitectura modular con LangGraph, frontend responsive nativo sin frameworks extra.

`FastAPI` · `LangChain` · `LangGraph` · `FAISS` · `HuggingFace` · `GPT-4o-mini` · `Python`

---

## 🎓 Educación

**Ingeniería de Sistemas** — Universidad de Córdoba · 2020 – 2024

---

<div align="center">

**¿Tu empresa tiene datos sin explotar, procesos manuales o documentación que nadie consulta?**
**Eso es exactamente lo que resuelvo.**

[![Contactar](https://img.shields.io/badge/Hablemos-6E40C9?style=for-the-badge&logo=gmail&logoColor=white)](mailto:lmiguelrambao@gmail.com)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](#)

</div>

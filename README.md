<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0D1117,50:1F6FEB,100:238636&height=190&section=header&text=Angel%20Salazar&fontSize=52&fontColor=ffffff&fontAlignY=38&desc=AI%20Engineer%20%7C%20RAG%20Systems%20%7C%20LLMOps%20%7C%20AI%20Agents&descSize=18&descAlignY=60" alt="Angel Salazar" width="100%"/>

<img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=600&size=18&duration=3000&pause=900&color=58A6FF&background=00000000&center=true&vCenter=true&width=820&height=50&lines=No+solo+uso+modelos%3A+dise%C3%B1o%2C+eval%C3%BAo+y+protejo+sistemas;RAG+%E2%86%92+Eval+%E2%86%92+Gates+%E2%86%92+Agentes+%E2%86%92+Seguridad;Python+%7C+FastAPI+%7C+Docker+%7C+AWS+(arquitectura)" alt="Typing" />

<br/>

![RAG](https://img.shields.io/badge/RAG_Systems-1F6FEB?style=for-the-badge)
![LLMOps](https://img.shields.io/badge/LLMOps-238636?style=for-the-badge)
![AI Agents](https://img.shields.io/badge/AI_Agents-F78166?style=for-the-badge)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=for-the-badge)

</div>

---

### `$ whoami`

```python
from dataclasses import dataclass, field

@dataclass
class AngelSalazar:
    role: str = "AI Engineer | RAG Systems | LLMOps | AI Agents"
    location: str = "Lima, Perú"
    education: list = field(default_factory=lambda: [
        "Maestría en Inteligencia Artificial — UNI",
        "Ingeniería de Sistemas — UTP (CIP 404730)",
    ])
    focus: list = field(default_factory=lambda: [
        "Evaluación y calidad de sistemas RAG",
        "LLMOps: gates, costos, observabilidad",
        "Agentes con abstención y escalamiento",
        "Seguridad de prompts (injection / jailbreak)",
    ])
    principles: list = field(default_factory=lambda: [
        "Medir antes de cambiar el modelo",
        "Citar o abstenerse — no inventar",
        "Datos sintéticos en público; cero secretos",
    ])

    def current_mission(self) -> str:
        return "Investigar, diseñar, evaluar y optimizar sistemas inteligentes."
```

---

### `$ ls flagships/`

Seis proyectos Nivel 3 (evaluación, ops, agentes, seguridad, compliance). El resto son labs satélite.

| Repo | Problema que ataca |
|---|---|
| [rag-eval-platform](https://github.com/Angelzaki/rag-eval-platform) | ¿En qué etapa se rompe el RAG cuando crece el corpus? |
| [llm-ci-gates](https://github.com/Angelzaki/llm-ci-gates) | ¿Cómo bloquear regresiones de IA en el merge? |
| [knowledge-ops-console](https://github.com/Angelzaki/knowledge-ops-console) | Ingesta → ask con citas → gold eval en una consola |
| [support-copilot-lab](https://github.com/Angelzaki/support-copilot-lab) | Responder con evidencia o escalar a humano |
| [prompt-firewall](https://github.com/Angelzaki/prompt-firewall) | Injection / jailbreak antes del LLM |
| [doc-compliance-local](https://github.com/Angelzaki/doc-compliance-local) | Checklist vs docs: evidencia, score y brechas |

```text
rag-eval ──metrics JSON──▶ llm-ci-gates (PASS/FAIL)
prompt-firewall ──valida input──▶ knowledge-ops / support-copilot
```

---

### `$ ./pipeline.sh --end-to-end`

Me encargo del ciclo completo de un producto con IA, no solo de una parte.

```mermaid
%%{init: {'theme':'dark','themeVariables':{'primaryColor':'#161B22','primaryTextColor':'#E6EDF3','primaryBorderColor':'#1F6FEB','lineColor':'#A371F7','fontFamily':'monospace'}}}%%
flowchart LR
    A[Análisis y<br/>levantamiento] --> B[Extracción<br/>de ideas]
    B --> C[Diseño de<br/>arquitectura]
    C --> D[Datos y<br/>modelos de IA]
    D --> E[API y<br/>backend]
    E --> F[Frontend e<br/>integración]
    F --> G[Deploy<br/>CI/CD]
    G --> H[Monitoreo y<br/>mejora continua]
    H -. feedback .-> A

    style D fill:#1F6FEB,stroke:#A371F7,color:#fff
    style E fill:#161B22,stroke:#238636,color:#fff
    style G fill:#161B22,stroke:#F78166,color:#fff
```

| Etapa | Qué hago |
|---|---|
| **Análisis** | Entender el problema, los usuarios y los datos disponibles |
| **Ideas** | Convertir necesidades en requerimientos y casos de uso con IA |
| **Diseño** | Definir arquitectura (Clean Architecture, microservicios, SOA) |
| **Modelos** | Diseñar, entrenar y evaluar modelos de Deep Learning y GenAI |
| **API** | Exponer los modelos como servicios (FastAPI, Node.js, .NET) |
| **Integración** | Conectar frontend, bases de datos, colas, WebSockets y automatizaciones |
| **Deploy** | Contenedores con Docker, cloud y pipelines de entrega |
| **Operación** | Monitorear, medir y mejorar el sistema en producción |

---

### `$ pip list --stack`

<div align="center">

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?style=flat-square&logo=tensorflow&logoColor=white)
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white)
![n8n](https://img.shields.io/badge/n8n-EA4B71?style=flat-square&logo=n8n&logoColor=white)

![React](https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB)
![Angular](https://img.shields.io/badge/Angular-DD0031?style=flat-square&logo=angular&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![Tailwind](https://img.shields.io/badge/Tailwind-06B6D4?style=flat-square&logo=tailwindcss&logoColor=white)

![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=nodedotjs&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![.NET](https://img.shields.io/badge/.NET-512BD4?style=flat-square&logo=dotnet&logoColor=white)
![PHP](https://img.shields.io/badge/PHP-777BB4?style=flat-square&logo=php&logoColor=white)

![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=flat-square&logo=mongodb&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white)
![Firebase](https://img.shields.io/badge/Firebase-FFCA28?style=flat-square&logo=firebase&logoColor=black)
![Supabase](https://img.shields.io/badge/Supabase-3ECF8E?style=flat-square&logo=supabase&logoColor=white)

![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![AWS](https://img.shields.io/badge/AWS-232F3E?style=flat-square&logo=amazonaws&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)
![RabbitMQ](https://img.shields.io/badge/RabbitMQ-FF6600?style=flat-square&logo=rabbitmq&logoColor=white)

</div>

---

### `$ cat model_card.md`

| | |
|---|---|
| **Model** | Angel Salazar v2026 |
| **Type** | Ingeniero de IA, arquitectura Full Stack |
| **Trained on** | Salud, educación, comercio y mucho código |
| **Strengths** | De prototipo de IA a producto desplegado |
| **Inference** | Español nativo, inglés técnico |
| **Limitations** | Depende de café; se distrae con una buena arquitectura |
| **License** | Open to collaboration |

---

### `$ git log --stats`

<div align="center">

<img src="https://github-readme-stats.vercel.app/api?username=Angelzaki&show_icons=true&theme=tokyonight&count_private=true&hide_border=true&bg_color=0D1117" alt="GitHub stats" height="165"/>
<img src="https://github-readme-stats.vercel.app/api/top-langs/?username=Angelzaki&layout=compact&theme=tokyonight&hide_border=true&bg_color=0D1117&langs_count=8" alt="Top languages" height="165"/>

<img src="https://github-readme-activity-graph.vercel.app/graph?username=Angelzaki&theme=tokyo-night&hide_border=true&bg_color=0D1117&area=true" alt="Activity graph" width="97%"/>

</div>

---

### `$ ping angel`

<div align="center">

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/angel-salazar-maylle-36236b198/)
[![Portafolio](https://img.shields.io/badge/Portafolio-1F6FEB?style=for-the-badge&logo=vercel&logoColor=white)](https://portafolioangel-mu.vercel.app/)
[![Email](https://img.shields.io/badge/Email-A371F7?style=for-the-badge&logo=gmail&logoColor=white)](mailto:angel.salazarmaylle@gmail.com)

<br/>

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:A371F7,50:1F6FEB,100:0D1117&height=100&section=footer" alt="footer" width="100%"/>

</div>

# LangGraph Agents

Este repositorio contiene dos notebooks enfocados en el uso y comprensión de agentes (agents) en el contexto de
LangGraph. Los notebooks están diseñados para servir como una introducción conceptual y práctica, y cubrir tanto el uso
básico como avanzado de agentes con estado.

## Contenido del Repositorio

1. **`agent_introduction.ipynb`**  
   Este notebook sirve como una introducción para entender qué son los agentes y cómo funcionan en LangGraph. En este
   archivo, aprenderás:
    - Cómo configurar un agente.
    - Los conceptos básicos detrás de la interacción de un agente con el entorno.
    - Ejemplos de implementación sencilla.

   Resulta ideal para usuarios que desean tener una primera aproximación a los agentes.

2. **`agent_with_state.ipynb`**  
   En este notebook se exploran agentes con capacidad de mantener un estado entre interacciones. Aquí se cubren:
    - Conceptos sobre estado en agentes.
    - Cómo implementar y gestionar la persistencia de dicho estado.
    - Ejemplos prácticos para modelar flujos más complejos de datos:
      - Paralelización
      - Routing
      - Orchestrator Workers
      - Evaluator - Optimizer

   Este archivo es perfecto para usuarios que buscan patrones avanzados de implementación de agentes.

## Requisitos Previos

Antes de ejecutar los notebooks, asegúrate de contar con las siguientes herramientas instaladas:

- < Python 3.10
- Las dependencias necesarias están en el archivo `requirements.txt`. Instálalas usando:
  ```bash
  pip install -r requirements.txt
  ```

## Uso

1. Clona el repositorio:
   ```bash
   git clone https://github.com/tu-usuario/langgraph-agents.git
   ```
2. Navega al directorio del repositorio:
   ```bash
   cd langgraph-agents
   ```
3. Ejecuta Jupyter Notebook:
   ```bash
   jupyter notebook
   ```
4. Abre cualquiera de los dos notebooks (`agent_introduction.ipynb` o `agent_with_state.ipynb`) y sigue las
   instrucciones en cada uno.

## Referencias

- [LangGraph Tutorials: Evaluator - Optimizer](https://langchain-ai.github.io/langgraph/tutorials/workflows/#evaluator-optimizer)
- [Anthropic Engineering: Building Effective Agents](https://www.anthropic.com/engineering/building-effective-agents)

---

Espero que disfrutes trabajando con agentes en LangGraph. Si tienes preguntas o comentarios, no dudes en contactarme.

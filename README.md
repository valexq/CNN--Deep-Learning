# Implementación y comparación de modelos LLM(Large language model) y SLM(Small language model) 

## Integrantes

| Nombre | Correos |
| --- | --- |
| Franco Moncayo | francomoncayo123@gmail.com
| Vanessa Alfaro | valexq11@gmail.com
| Carlos Moreno| admmoreno.david@gmail.com
| Santiago Villada | villadasantiago13@gmail.com

## Objetivo del proyecto

Este proyecto implementa, evalua y comparar modelos de lenguaje a gran escala(LLM) y modelos compactos(SLM) utilizando arquitecturas Transformer para tareas de conversación de lenguaje natural
El proyecto analiza desempeño conversacional, coherencia contextual, velocidad de inferencia y consumo computacional.

## Modelos implementados

### Large Language Models (LLM)

| Modelo | Parámetros | Tipo |
|---|---|---|
| DialoGPT-medium | 345M | Conversacional |
| GPT-Neo 1.3B | 1.3B | Generación de texto |
| Gemma 2B | 2B | Instrucciones |

### Small Language Models (SLM)

| Modelo | Parámetros | Tipo |
|---|---|---|
| Qwen 2.5 0.5B | 0.5B | Instrucciones |
| Phi-2 | 2.7B | Razonamiento |

## Estructura del repositorio

```text
Proyecto/
│
├── modelos/
│   ├── dialogpt.py
│   ├── gptneo.py
│   ├── gemma.py
│   ├── qwen.py
│   └── phi.py
│
├── notebooks/
│   ├── 01_dialogpt.ipynb
│   ├── 02_gptneo.ipynb
│   ├── 03_gemma.ipynb
│   ├── 04_qwen.ipynb
│   ├── 05_phi.ipynb
│   └── 06_comparacion_final.ipynb
│
├── informe/
│
└── README.md
## Instalación



## Ejecución




## Metodología experimental

Todos los modelos fueron evaluados usando:

- Los mismos prompts
- Parámetros de generación equivalentes
- Conversaciones multi-turno
- Métricas homogéneas

Parámetros utilizados:

- temperature = 0.7
- top_p = 0.92
- top_k = 50
- max_new_tokens = 100

## Métricas evaluadas

- Coherencia conversacional
- Tiempo de respuesta
- Fluidez textual
- Mantenimiento de contexto
- Consumo computacional
- Longitud de respuesta

## Resultados generales

| Modelo | Calidad | Velocidad | Coherencia |
|---|---|---|---|
| DialoGPT |  |  |  |
| GPT-Neo |  |  |  |
| Gemma |  |  |  |
| Qwen |  |  |  |
| Phi-2 |  |  |  |


## Conclusiones


## Referencias 

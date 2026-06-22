# LangGraph desde Cero: construye una Aplicación de IA Real

Repositorio oficial del curso **LangGraph desde Cero**, una serie práctica en español donde aprenderemos los fundamentos de LangGraph construyendo paso a paso una aplicación de IA real.

El objetivo de este repositorio no es solo mostrar código, sino ayudarte a entender cómo diseñar flujos de IA con una estructura clara: **estado, nodos, aristas, condiciones, memoria, intervención humana y una aplicación final funcional**.

> Este curso está pensado para desarrolladores, estudiantes, docentes y profesionales de datos/IA que quieren pasar de ejemplos simples con LLMs a aplicaciones más organizadas usando grafos.

---

## ¿Qué vas a aprender?

En esta serie construiremos una base sólida para trabajar con LangGraph desde cero, cubriendo los conceptos principales de forma progresiva:

- **Nodos:** acciones o responsabilidades dentro del flujo.
- **Aristas:** conexiones que definen el camino entre pasos.
- **Aristas condicionales:** decisiones dinámicas dentro del grafo.
- **Estado:** información compartida que viaja entre nodos.
- **Memoria:** contexto para mantener continuidad en la conversación.
- **Human in the Loop:** interrupciones y revisión humana dentro del flujo.
- **Proyecto final:** una aplicación práctica de IA usando LangGraph.

---

## Enfoque del curso

Este curso está diseñado para aprender construyendo.

Trabajaremos principalmente en **Google Colab**, por lo que no necesitas preparar un entorno local complejo desde el inicio. Cada notebook estará pensado para ejecutarse paso a paso, con explicaciones claras y código progresivo.

La idea es que puedas concentrarte en entender cómo funciona LangGraph y cómo se diseña una aplicación de IA basada en grafos.

---

## Requisitos recomendados

Para completar el curso de forma ideal, se recomienda contar con:

- Conocimientos básicos de Python.
- Una cuenta de Google para usar Google Colab.
- Una cuenta de OpenAI con acceso a API Key.
- Crédito disponible o plan activo para consumir modelos de OpenAI.
- Conocimientos básicos sobre LLMs, prompts y aplicaciones de IA.

> Nota: Puedes revisar los notebooks aunque no tengas una API Key activa, pero para ejecutar los ejemplos completos necesitarás configurar tus credenciales.

---

## Tecnologías utilizadas

Durante el curso trabajaremos con:

- **Python**
- **LangGraph**
- **LangChain**
- **OpenAI API**
- **Google Colab**
- **Notebooks prácticos**
- **Estructura progresiva de proyecto**

En futuras versiones o una segunda parte, este repositorio podrá extenderse o actualizarse.

---

## Estructura del repositorio

```text
langgraph-desde-cero-app-ia-real/
├── notebooks/
│   ├── 01_nodos.ipynb
│   ├── 02_aristas.ipynb
│   ├── 03_aristas_condicionales.ipynb
│   ├── 04_memoria.ipynb
│   ├── 05_human_in_the_loop.ipynb
│   └── 06_proyecto_final.ipynb
│
├── slides/
│
├── docs/
│   └── imagenes/
│ 
├── proyecto/
│
├── requirements.txt
├── .env.example
└── README.md
```

---

## Contenido del curso

| Módulo | Tema | Descripción |
|---|---|---|
| 01 | Nodos | Aprenderemos cómo representar acciones dentro de un grafo. |
| 02 | Aristas | Veremos cómo conectar los pasos del flujo. |
| 03 | Aristas condicionales | Agregaremos decisiones según el estado de la aplicación. |
| 04 | Memoria | Mantendremos contexto entre interacciones. |
| 05 | Human in the Loop | Incorporaremos interrupciones y revisión humana. |
| 06 | Proyecto final | Integraremos todo en una aplicación práctica de IA. |

---

## Proyecto final

El proyecto final será una aplicación práctica de un flujo de IA 

---

## Configuración de variables de entorno

Para ejecutar los ejemplos que usan modelos de OpenAI, crea una variable de entorno con tu API Key.

En Colab podrás usar:

```python
import os
from getpass import getpass

os.environ["OPENAI_API_KEY"] = getpass("Ingresa tu OpenAI API Key: ")
```

También se incluirá un archivo `.env.example` como referencia:

```env
OPENAI_API_KEY=tu_api_key_aqui
```

> Importante: Nunca subas tu API Key real a GitHub.

---

## Cómo usar este repositorio

Puedes seguir el curso de dos formas:

### Opción 1: Usar Google Colab

Abre cada notebook desde la carpeta `notebooks/` y ejecútalo paso a paso.

Esta es la forma recomendada para quienes están empezando o quieren evitar configuración local.

### Opción 2: Ejecutar localmente

Clona el repositorio:

```bash
git clone https://github.com/macespinoza/langgraph-desde-cero-app-ia-real.git
cd langgraph-desde-cero-app-ia-real
```

Crea un entorno virtual:

```bash
python -m venv .venv
source .venv/bin/activate
```

> En Windows puedes activar el entorno con:
>
> ```bash
> .venv\Scripts\activate
> ```

Instala las dependencias:

```bash
pip install -r requirements.txt
```

Configura tus variables de entorno y ejecuta los ejemplos.

---

## Roadmap

Este repositorio está preparado para crecer.

### Parte 1: Fundamentos

- Nodos
- Aristas
- Aristas condicionales
- Estado
- Memoria
- Human in the Loop
- Proyecto final básico

---

## Comunidad y contribuciones

Este proyecto es abierto y nace con el propósito de compartir conocimiento práctico sobre IA aplicada.

Si encuentras un error, tienes una mejora o quieres proponer una nueva sección, puedes abrir un **Issue** o enviar un **Pull Request**.

Las contribuciones son bienvenidas, especialmente si ayudan a que el contenido sea más claro, útil y aplicable.

---

## Autor

**Miguel Ángel Cotrina Espinoza**  
Arquitecto de Datos & IA | Docente | Founder & CTO de ArkanyAI

Comparto contenido sobre inteligencia artificial aplicada, agentes, arquitectura de datos, GenAI y soluciones reales con IA.

---

## Conecta conmigo

Gracias por revisar este repositorio.  
Si te interesa colaborar, aprender más o invitarme a dar una charla, puedes escribirme o seguirme en LinkedIn:

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Miguel%20Cotrina-blue?logo=linkedin&style=flat-square)](https://www.linkedin.com/in/mcotrina/)

> IA & Data con propósito

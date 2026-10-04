<h1 align="center">Jairam Hegde</h1>
<h3 align="center">AI Engineer: agents, retrieval, and the plumbing that keeps them honest</h3>
<p align="center">
  <em>Engineering since April 2021. Still suspicious of anything that works on the first try.</em>
</p>

<p align="center">
  <img src="assets/pico-wave.gif" width="140" alt="Pico the penguin, waving">
</p>

<p align="center">
  <a href="https://jairamshegde.github.io/thearchitectsmind/"><img src="https://img.shields.io/badge/The_Architect's_Mind-000000?style=for-the-badge&logo=astro&logoColor=white"/></a>
  <a href="https://linkedin.com/in/jairamshegde"><img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white"/></a>
  <a href="mailto:devjairamish@gmail.com"><img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white"/></a>
</p>

## What I'm working on

| Track | What's happening |
| --- | --- |
| **Building** | `mingraph` phase 7 — the agent loop, where state and streaming stop being optional |
| **Shipping** | `LinkMark` — chat-first bookmark manager; backend and RAG agents land next week |
| **Learning** | Agent evals. "It feels better" is not a metric |
| **Writing** | One post per phase — the design decisions, and the things that broke |

## Things I've built

**[mingraph](https://github.com/jairamshegde/mingraph)** rebuilds LangChain and LangGraph from scratch in plain Python, one design pattern per phase. Six done: provider wrappers, messages, tools, memory, composable steps, retrieval. Each phase has a writeup.

**[active-learning-skills](https://github.com/jairamshegde/active-learning-skills)** is a set of three Claude Agent Skills that turn what I read and watch into notes I retain. The model handles compression and fact-checking. It also quizzes me, which is the only reliable way to find what I forgot.

**LinkMark** rethinks bookmark management chat-first: you ask for the thing you half-remember instead of digging through folders, in one unified UI. Frontend is complete locally; the FastAPI backend and multi-agent RAG layer land next week. Recommendations and an Obsidian-style graph view come after. *Repo link soon.*

## What I actually do

I'm an AI engineer who likes understanding how things work — usually by building them, breaking them, and rebuilding them slightly better. That instinct is most of why `mingraph` exists.

Day to day it's agents, retrieval and the architecture holding them together, mostly in enterprise settings where "the model said so" won't survive an audit. The interesting part is rarely the model. It's what goes into the context window and why, where retrieval quietly fails, how you know a change helped, and what happens on the bad day.

## Tech Stack

<table>

  <tr>
    <th align="left">Category</th>
    <th align="center">Tool</th>
    <th align="center">Tool</th>
    <th align="center">Tool</th>
    <th align="center">Tool</th>
  </tr>

  <!-- AI & LLMs -->
  <tr>
    <td><strong>AI &amp; LLMs</strong></td>
    <td align="center">
      <a href="https://www.anthropic.com/">
        <img src="https://raw.githubusercontent.com/simple-icons/simple-icons/master/icons/anthropic.svg" width="32"/><br/>
        Claude
      </a>
    </td>
    <td align="center">
      <a href="https://docs.anthropic.com/en/docs/claude-code">
        <img src="https://registry.npmmirror.com/@lobehub/icons-static-png/latest/files/dark/claude-color.png" width="45"/><br/>
        Claude Code
      </a>
    </td>
    <td align="center">
      <a href="https://openai.com/chatgpt">
        <img src="https://registry.npmmirror.com/@lobehub/icons-static-svg/latest/files/icons/openai.svg" width="45"/><br/>
        ChatGPT
      </a>
    </td>
    <td align="center">
      <a href="https://github.com/obra/superpowers">
        <img src="https://github.com/obra.png" width="40"/><br/>
        Superpowers
      </a>
    </td>
  </tr>

  <!-- Agent & Web Frameworks -->
  <tr>
    <td><strong>Agent &amp; Web Frameworks</strong></td>
    <td align="center">
      <a href="https://python.langchain.com/">
        <img src="https://raw.githubusercontent.com/simple-icons/simple-icons/master/icons/langchain.svg" width="45"/><br/>
        LangChain
      </a>
    </td>
    <td align="center">
      <a href="https://langgraph.langchain.com/">
        <img src="https://registry.npmmirror.com/@lobehub/icons-static-png/latest/files/dark/langgraph-color.png" width="45"/><br/>
        LangGraph
      </a>
    </td>
    <td align="center" width="96">
      <a href="https://the-pocket.github.io/PocketFlow/" target="_blank">
        <img src="https://raw.githubusercontent.com/The-Pocket/.github/main/assets/title.png" width="50"/><br/>
        PocketFlow
      </a>
    </td>
    <td align="center">
      <a href="https://fastapi.tiangolo.com/">
        <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/fastapi/fastapi-original.svg" width="45"/><br/>
        FastAPI
      </a>
    </td>
  </tr>

  <!-- Data & Retrieval -->
  <tr>
    <td><strong>Data &amp; Retrieval</strong></td>
    <td align="center">
      <a href="https://qdrant.tech/">
        <img src="https://qdrant.tech/img/brand-resources-logos/qdrant-brandmark-red.svg" width="32"/><br/>
        Qdrant
      </a>
    </td>
    <td align="center">
      <a href="https://supabase.com/">
        <img src="https://raw.githubusercontent.com/simple-icons/simple-icons/master/icons/supabase.svg" width="32"/><br/>
        Supabase
      </a>
    </td>
    <td align="center">
      <a href="https://huggingface.co/">
        <img src="https://huggingface.co/front/assets/huggingface_logo-noborder.svg" width="32"/><br/>
        Hugging Face
      </a>
    </td>
    <td align="center">
      <a href="https://ollama.com/">
        <img src="https://ollama.com/public/ollama.png" width="32"/><br/>
        Ollama
      </a>
    </td>
  </tr>

  <!-- Cloud & Ops -->
  <tr>
    <td><strong>Cloud &amp; Ops</strong></td>
    <td align="center">
      <a href="https://azure.microsoft.com/">
        <img src="https://www.vectorlogo.zone/logos/microsoft_azure/microsoft_azure-icon.svg" width="40"/><br/>
        Azure
      </a>
    </td>
    <td align="center">
      <a href="https://azure.microsoft.com/en-us/products/ai-services/ai-foundry/">
        <img src="https://registry.npmmirror.com/@lobehub/icons-static-png/latest/files/dark/azureai-color.png" width="40"/><br/>
        Azure AI Foundry
      </a>
    </td>
    <td align="center">
      <a href="https://www.docker.com/">
        <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/docker/docker-original.svg" width="45"/><br/>
        Docker
      </a>
    </td>
    <td></td>
  </tr>

  <!-- Evals & Observability -->
  <tr>
    <td><strong>Evals &amp; Observability</strong></td>
    <td align="center">
      <a href="https://arize.com/phoenix/">
        <img src="https://github.com/Arize-ai.png" width="32"/><br/>
        Arize Phoenix
      </a>
    </td>
    <td align="center">
      <a href="https://deepeval.com/">
        <img src="https://github.com/confident-ai.png" width="32"/><br/>
        DeepEval
      </a>
    </td>
    <td align="center">
      <a href="https://github.com/explodinggradients/ragas">
        <img src="https://github.com/explodinggradients.png" width="32"/><br/>
        Ragas
      </a>
    </td>
    <td></td>
  </tr>

  <!-- Dev & Tooling -->
  <tr>
    <td><strong>Dev &amp; Tooling</strong></td>
    <td align="center">
      <a href="https://www.python.org/">
        <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/python/python-original.svg" width="32"/><br/>
        Python
      </a>
    </td>
    <td align="center">
      <a href="https://git-scm.com/">
        <img src="https://www.vectorlogo.zone/logos/git-scm/git-scm-icon.svg" width="32"/><br/>
        Git
      </a>
    </td>
    <td></td>
    <td></td>
  </tr>

</table>

## How I work

- I run feature work as subagent-driven development with Superpowers. A plan goes first, each task gets a fresh subagent, and every change clears two reviews: spec compliance, then code quality. Delivery is faster because the review sits inside the loop instead of at the end.
- I spend more time on the harness than on the prompt: the skills and scaffolding the model runs inside. `active-learning-skills` is one I built for myself.
- I rebuild things small until I can explain them. Now that the agent writes most of the code, being able to explain it matters more, not less.
- I treat a RAG system as a search product. A chunk that was never retrieved can't be recovered downstream, so I score the two halves separately: context precision and recall on retrieval, faithfulness and answer relevancy on generation. A bad answer then points at a cause instead of a vibe.
- I reach for an agent last, not first. If the steps are knowable at design time it's a pipeline, and a pipeline is cheaper, faster and testable against fixed inputs. An agent earns the nondeterminism it adds only when the next step depends on what the last one returned.

## Elsewhere

- **Blog** — [The Architect's Mind](https://jairamshegde.github.io/thearchitectsmind/)
- **LinkedIn** — [Jairam Hegde](https://linkedin.com/in/jairamshegde)
- **Email** — [devjairamish@gmail.com](mailto:devjairamish@gmail.com)

<p align="center">
  <i>Open to conversations about agents, retrieval, and graphs.</i>
</p>

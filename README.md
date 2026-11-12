# LangChain Learnings

Personal practice notes and hands-on experiments exploring LangChain, local models (Ollama), cloud APIs, tools, agents, and structured outputs.

## Topics & Notebooks

- [`langchain-intro.ipynb`](mylangchain/langchain-intro.ipynb): Getting started with Google Gemini (`gemini-3.8-flash`) and basic tool-calling agents.
- [`ollama.ipynb`](mylangchain/ollama.ipynb): Running local LLMs with Ollama (`llama3.2:1b`) and building `@tool` agents.
- [`messages.ipynb`](mylangchain/messages.ipynb): Core message types (`SystemMessage`, `HumanMessage`, `AIMessage`) and role prompting.
- [`structure-output.ipynb`](mylangchain/structure-output.ipynb): Structured outputs with Pydantic (`BaseModel`, `Field`, and nested schemas).
- [`typedict.ipynb`](mylangchain/typedict.ipynb): Lightweight structured outputs using `TypedDict` and `@dataclass`.
- [`middleware.ipynb`](mylangchain/middleware.ipynb): Agent memory via LangGraph (`InMemorySaver` checkpointer) and `SummarizationMiddleware`.
- [`githubtools.ipynb`](mylangchain/githubtools.ipynb): Custom agent tool connecting to the GitHub REST API to fetch open pull requests.
- [`tools.ipynb`](mylangchain/tools.ipynb): Scratchpad for model invocations and quick experiments.
=

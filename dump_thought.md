AI agent to automate Pilot -> Sales Agent -> tech Production Manager -> tech chain of flow task

**important areas to read**
Software Architecture (SE745)
Requirements Engineering (SE651)

**change in scope of work**
input(Sales Order) -> process -> outputs
                    - Step-by-step task
                    - Removal
                    - Wiring DIagram
                    - Parts Required
                    - Tools Required
                    - Travellere details
                    - install task and things to watchout
udemy course agentic AI
- 16 weeks coding agentic AI from scratch.
- the SDK is cursor
note
- Agent vs workflow
"AI agents are programs where LLM outputs control the workflow"
5 understandings about "agents"
- Multiple LLM calls
- LLMs with ability to use tools
- An environment where LLMs intract
- A planner to coordinate activities
- Autonomy

Agentic System according to Antropic

Workflows - systems where LLMs and tools are orchestrated through predefined code paths

Agents - systems where LLMs dynamically direct their own processes and tool usage, maintaining control over how they accomplish tasks

5 workflow design patterns

1. prompt chaining - decompose into fixed sub-tasks
2. Routing - Direct an input into a specialized sub-task, ensuring separation of concerns
3. Parallelization - Breaking down tasks and running multiple subtasks concurrently
4. Orchestrator-worker - complex tasks are broken down dynamically and combined
5. Evaluator-Optimizer - LLM Output is validated by another

By contrast, Agents

1. Open-ended
2. Feedback loops
3. No fixed path
-> guardrail and robustness is concern 

Risks of Agent Frameworks
- Unpredictable path
- Unpredictable output
- Unpredictable costs
- Monitor
- "Guardrails ensure your agents behave safely, consistently and within your intended boundaries"

the cast of characters

OpenAI:gpt-4o-mini(gpt-4o,o1 nad o3-mini)
Anthropic: Claude-3-7-Sonnet
Google:Gemini-2.0-flash
DeepSeek AI:DeepSeek V3, DeepSeek R1
    -powerful training technique to train Deepseek is what made it unique.
Groq: open-source LLMs including Llama3.3 -> not twitter's
Ollama: local open-source LLMs including LLama3.2

the Vellum leaderboard gives a comparison of costs and performance

Agentic AI Frameworks

- not having a framework is most recommended
MCP - model context protocol -> models be connected to datas
In terms of complexity
1. **LangGraph** | **AutoGen**
2. **OpenAI Agents SDK** | **CrewAI**
3. **No framework** | **MCP**

we can provide an LLM with resources to improve its expertise

Basically, just means shoveing data relevant to the question into the prompt

* there are techniques like RAG (Retrieval Augmented Generation) to get really smart at picking relevant content
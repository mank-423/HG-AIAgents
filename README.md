### Workflows 
Automations or systems where the output is predefined by LLM and tools 

### AI Agents
LLM dynamically decides the tool and output. For one task we have AI agents.

### Agentic Systems
Multiple AI agents together, one parent node combines all the outputs to take decision. Collaboration together of those agents.

### How it works
An Agent is a system that leverages an AI model to interact with its environment in order to achieve a user-defined objective. It combines reasoning, planning, and the execution of actions (often via external tools) to fulfill tasks.

Brain: LLM, decides reasoning and execution steps
Body: Tools: 

Brain splits the task into actions: those actions need tools to complete or not that is decided by brain also.
reAct framework is used right now to build agents. Reason + Action.
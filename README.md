## Notes AI Agents

### Workflows 
Automations or systems where the output is predefined by LLM and tools 
<img width="563" height="130" alt="image" src="https://github.com/user-attachments/assets/9eaf411a-e63b-4ead-b92b-fd17b4da84e2" />


### AI Agents
LLM dynamically decides the tool and output. For one task we have AI agents.

### Agentic Systems
Multiple AI agents together, one parent node combines all the outputs to take decision. Collaboration of agents.

<img width="448" height="453" alt="image" src="https://github.com/user-attachments/assets/6425a396-669a-4cd1-8b81-4ff245c0e1fd" />


### How it works
An Agent is a system that leverages an AI model to interact with its environment in order to achieve a user-defined objective. It combines reasoning, planning, and the execution of actions (often via external tools) to fulfill tasks.

Brain: LLM, decides reasoning and execution steps
Body: Tools: 

Brain splits the task into actions: those actions need tools to complete or not that is decided by brain also.
reAct framework is used right now to build agents. Reason + Action.

## Overview

An agent is born when you initiate llm to inner thinking process. `Tools` allow agent to interact with outside world.

```mermaid
graph TD
    Task --> Agent
    Agent-->Agent
    Tools --> Agent
    Agent --> Answer
```

`Multiagent systems` consists of agents interacting with each other to accomplish a particular goal.

Agents can be connected to any llms.

Agents in `crew-ai` have 3 elements: `Role`, `goal` and `backstory`.

```python
Agent(role="",goal="",backstory="")
```

Agents perform better in roleplay.

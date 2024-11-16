```
# ./RSChatGPT-shell.py
from langchain.chat_models import ChatOpenAI
from langchain.agents.initialize import initialize_agent
from langchain.tools import Tool
```
使用[langchain-ai](https://github.com/langchain-ai/langchain),Agents allow an LLM autonomy over how a task is accomplished. Agents make decisions about which Actions to take, then take that Action, observe the result, and repeat until the task is complete.

文档地址：
1. https://api.python.langchain.com/en/latest/langchain_api_reference.html#module-langchain.agents
2. https://api.python.langchain.com/en/latest/agents/langchain.agents.initialize.initialize_agent.html#langchain.agents.initialize.initialize_agent
3. https://api.python.langchain.com/en/latest/tools/langchain_core.tools.base.BaseTool.html#langchain_core.tools.base.BaseTool
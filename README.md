# Composable AI systems: Building and AI Stylist Specialist selling our products
## What's a composable AI system
LLMs are great at answering general questions. However, general intelligence alone isn't enough to provide value to your customers.

To be able to provide valuable answers, extra information is required, specific to your business and the user asking the question (your customer contract ID, the last email they sent to your support, your most recent sales report etc.).

Composable AI systems are designed to answer this challenge. They are more advanced AI deployments, composed of multiple entities (tools) specialized in different action (retrieving information or acting on external systems).

At a high level, you build & present a set of custom functions to the AI. The LLM can then reason about it, deciding which tool should be called and information gathered to answer the customer need.

## Building Composable AI Systems with Databricks Mosaic AI agent framework
Databricks simplifies this by providing a built-in service to:

- Create and store your functions (tools) leveraging Unity Catalog. 
- Execute the functions in a safe way. 
- Reason about the tools you selected and chain them together to properly answer your question.  

At a high level, here is the AI system we will implement in this demo:
<img src="https://github.com/databricks-demos/dbdemos-resources/blob/main/images/product/llm-tools-functions/llm-tools-functions-flow.png?raw=true" width="900px">
# Azure OpenAI Accelerators and Demo Assets

The following is a list of Repeatable IP and learning resources to quickly build an initial Azure OpenAI solution, developed by different individuals and teams at Microsoft.

## Accelerators and Workshops

### Official Azure OpenAI Accelerators 

Below is a summary list of the official Azure OpenAI Accelerators and workshops:
<br/>


| Name      | Description   | Link   |
| ----------- | ----------- | ----------- |
| Azure OpenAI in a Day workshop | This technical workshop will provide an introduction to OpenAI and an overview of Azure OpenAI Studio. Participants will be prompted to complete engineering exercises and use OpenAI to access company data. They will also learn about embedding solution accelerators and prototyping one use case from start to finish.| [Link](https://github.com/microsoft/azure-openai-in-a-day-workshop)
| Azure OpenAI Workshop |  In this workshop, you will learn how to use the Azure OpenAI service to create AI powered solutions. You will get hands-on experience with the latest AI technologies and will learn how to use Azure OpenAI API. | [Link](https://github.com/Azure/azure-openai-workshop)
| Business Process Automation solution accelerator | Creates pipelines to analyze text and audio datasets, across multiple cognitive services, and the HuggingFace library. The accelerator deploys all of the resources, and transforms the input data at each step, allowing multiple Cognitive Services to be called and deployed within a single, end-to-end pipeline. Includes capabilities like Azure OpenAI (summarization or custom prompts) and integration with CosmosDb, Cognitive Search, and RediSearch for Vector Search  | [Link](https://github.com/Azure/business-process-automation)
|ChatGPT + Enterprise data with Azure OpenAI and Cognitive Search | This sample demonstrates a few approaches for creating ChatGPT-like experiences over your own data using the Retrieval Augmented Generation pattern. It uses Azure OpenAI Service to access the ChatGPT model (gpt-35-turbo), and Azure Cognitive Search for data indexing and retrieval. **NOTE: sample created by Product Group**| [Link](https://github.com/Azure-Samples/azure-search-openai-demo/)
|Knowledge Mining with Azure OpenAI| The purpose of this repo is to accelerate the deployment of a Python-based Knowledge Mining solution with OpenAI that will ingest a Knowledge Base, generate embeddings using the contents extracted, store them in a vector search engine (Redis), and use that engine to answer queries / questions specific to that Knowledge Base. The repo includes the use of MRKL/ReAct Prompts and the ability to ask questions of different stores (including mathematical operations). | [Link](https://github.com/MSUSAzureAccelerators/Knowledge-Mining-with-OpenAI)
| OpenAI workshop | Workshop materials to build intelligent solutions on Open AI | [Link](https://github.com/microsoft/OpenAIWorkshop)
|Semantic Kernel |Semantic Kernel (SK) is a lightweight SDK enabling integration of AI Large Language Models (LLMs) with conventional programming languages.| [Link](https://github.com/microsoft/semantic-kernel)
|Visual ChatGPT |Visual ChatGPT connects ChatGPT and a series of Visual Foundation Models to enable sending and receiving images during chatting. | [Link](https://github.com/microsoft/visual-chatgpt)

<br/>

### Microsoft Community Contributions
Below is a summary list of Azure OpenAI Microsoft Community Contributions:
<br/>

| Name      | Description   | Link   |
| ----------- | ----------- | ----------- |
| Athena - Generate Synapse queries with Azure OpenAI  | We know that LLMs can generate SQL code from Natural language. The challenge in adopting this to empower all skill levels to query big data is many fold. From LLM perspective: For a correct SQL query generation from natural langugae, LLMs not only need to understad the context but also have an understanding of the database schema. Passing schema to prompts could be an approach here but this is not scalable. In this repo we showcase using prompt engineering approaches from chain of thought modelling we can make this approach scalable. This project shows LLMs working from natural language to query a star schema in data lake (via Synapse) without the need to know the DB schema before hand. | [Link](https://github.com/Ritaja/Athena)
| Azure OpenAI Embeddings QnA | A simple web application for a OpenAI-enabled document search. This repo uses Azure OpenAI Service for creating embeddings vectors from documents. For answering the question of a user, it retrieves the most relevant document and then uses GPT-3 to extract the matching answer for the question. | [Link](https://github.com/ruoccofabrizio/azure-open-ai-embeddings-qna)
|Azure OpenAI Example Prompts |This repository shares example code and example prompts for accomplishing common tasks with the Azure OpenAI API.| [Link](https://github.com/jakeatmsft/AzureOpenAIExamples)
|Azure OpenAI integration with Azure Cognitive-Search for document analysis | Azure OpenAI integration as a custom skillset in Azure Cognitive Search | [Link](https://github.com/Anaig/OpenAI-and-Cognitive-Search/)
|Azure Cognitive Semantic Search with OpenAI enrichment |Azure Cognitive Semantic Search that works on large documents, with OpenAI enrichment. | [Link](https://github.com/MaheshSQL/cognitive-semantic-search-openai-accelerator)
|ChatGPT with Enterprise Data |This sample demonstrates a few approaches for creating ChatGPT-like experiences over your own data. It uses Azure OpenAI Service to access the ChatGPT model (gpt-35-turbo and gpt3), and vector store (Pinecone, Redis and others) or Azure cognitive search for data indexing and retrieval. | [Link](https://github.com/akshata29/chatpdf)
|Document Analysis using OpenAI GPT-3 |This repository provides a set of examples in Jupyter Notebooks/Python for performing document analysis using Azure OpenAI's GPT-3 | [Link](https://github.com/ryubidragonfire/document-analysis-using-gpt-3)
|GPT-Azure-Search-Engine | This repo shows how you can use Azure OpenAI + Azure Cognitive Search to have a Smart and Multilingual Search engine that not only provides links of the search results, but also answers the question. | [Link](https://github.com/pablomarin/GPT-Azure-Search-Engine)
| GPT3 Prompt Examples | GPT-3 examples using mostly text-davinci-003 | [Link](https://gist.github.com/csiebler/d137386c4a63cc34810151bcdf150d54)
|Podcast Synopsis with OpenAI GPT|This repo illustrates how to use OpenAI GPT to generate a synopsis from a podcast transcription into multiple languages, generate 2-3 tag lines based on the podcast content and generate search engine optimised (SEO) keywords.|[Link](https://github.com/ryubidragonfire/generate-podcast-synopsis-OpenAI-GPT)
| Simple Chatbot using Azure OpenAI service | Step-by-step  article describing  how to create a  chatbot based on the Azure OpenAI text-davinci model.| [Link](https://github.com/michalmar/openai-demos-bot-webapp)

<br/>

<br/>

**NOTE**: Please make sure to check the terms of use for each. Some are only provided for demonstration purposes and not mean for as-is production use.

## Learning Resources 

Below is a summary list of some learning resources:
<br/>


|Description | Link   |
|----------- | ----------- |
| Azure OpenAI Documentation |  [Link](https://learn.microsoft.com/en-us/azure/cognitive-services/openai/)
| OpenAI Cookbook  |  [Link](https://github.com/openai/openai-cookbook)

<br/>

**NOTE**: If you are a Microsoft employee and would like to add an asset to this list, please contact the Specialized AI CSA team.

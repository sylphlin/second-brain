# second-brain

### Objective
This project is a demo project that leverage Google Cloud Vertex AI and Langchain to provide response based on the linked Google Drive Folder.

### Background
The idea comes from a real case of the insurance customer. They need to provide an easy way to their agents which can easily answer the inquiries. However, most of the insurance documents are based on PDF and not easy to transform to the structure data and make it easy to create the search feature by database. They want to have a Q&A system which can answer the inquiry based on the documents they provided.

I extended the requirements to a general purpose one and created the Second Brain demo. The customer can upload their documents into the Google Drive Folder and let LLM consume the documents in this folder and answer the questions based on that.

The Second Brain not only can answer the question based on the specific document but also can answer the question which needs to be combined from multiple documents.

### System Architecture
![Architecture Diagram](https://github.com/sylphlin/second-brain/blob/main/architecture.jpg?raw=true)

### Recognition
This works is inspired by How to build a ChatGPT + Google Drive app with [LangChain and Python](https://www.haihai.ai/gpt-gdrive/?ref=emergentmind)

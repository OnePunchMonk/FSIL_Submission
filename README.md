#### Information Extraction and Analysis from SEC Filings
This project focuses on extracting key information from filings submitted to the Securities and Exchange Commission (SEC) by public companies.

### Current Progress
## Data Download
Task_1.ipynb contains code to download 10,000 filings and save them as text documents.
## Information Extraction
The same notebook provides functionalities to process the downloaded text files and extract relevant data points.
## Prompts
Prompts.txt stores prompts that will be used to query a large language model (LLM) API to retrieve specific information from the extracted text.
## Extracted Data
- Task1.1/dataset folder holds the extracted text files for filings related to Tesla.
- Task1.2/dataset folder contains JSON files generated after pre-processing the extracted text for Tesla filings. This pre-processing involves information extraction and association with relevant entities.
### Future Objectives
## Search with Elasticsearch
Integrate Elasticsearch to enable Retrieval-Augmented Generation (RAG) based search functionality on the extracted JSON reports.
## Prompt Response Storage
Develop a mechanism to store the responses obtained from querying the LLM API with the prompts.
## Data Visualization
Utilize a plotting library like Charts.js or D3.js to visualize the extracted data points in an interactive browser interface.
## Backend Application
Design and implement a simple backend application that allows users to submit input and receive relevant information.

# Company-Compliance-Evaluator

This notebook is designed to automate the evaluation of a company's compliance with various industry standards and best practices in data security, intellectual property, confidentiality, and more. By utilizing advanced NLP models and data retrieval systems, this tool queries internal documents and external sources to generate responses to predefined compliance questions. The responses are then automatically scored against a rigorous set of criteria to assess how well the company meets the specified requirements.

### Features:

1. LangChain: Used for leveraging large language models to perform complex retrieval and question-answering tasks.

2. RetrievalQA: Used RetrievalQA to retrieve relevant information from documents or sources.

3. OpenAI Embeddings and Chroma: These are utilized for embedding questions and retrieving the most relevant information from a vectorized database.

Each question is categorized under topics such as Access Control, Data Security, Subcontractors, and more. The tool evaluates answers based on the documentation provided or retrieved, scoring each on a scale from 0 to 10. A score of 0 indicates no evidence of compliance, while a score of 10 signifies comprehensive and consistent adherence to the requirements.

### Setup

1. Run the notebook [compliance_evaluation.ipynb](https://github.com/isabeljohnson001/Company-Compliance-Evaluator/blob/main/Company_Compliance_Evaluator.ipynb).

2. Follow the instructions in the notebook to input questions and evaluate compliance.

### Results
The notebook provides a detailed assessment of how well a company meets various compliance requirements. The automated scoring system offers quantifiable metrics for identifying strengths and areas needing improvement.

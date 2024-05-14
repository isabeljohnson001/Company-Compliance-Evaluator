# Company-Compliance-Evaluator

This notebook is designed to automate the evaluation of a company's compliance with various industry standards and best practices in data security, intellectual property, confidentiality, and more. By utilizing advanced NLP models and data retrieval systems, this tool queries internal documents and external sources to generate responses to predefined compliance questions. The responses are then automatically scored against a rigorous set of criteria to assess how well the company meets the specified requirements.

The notebook integrates several cutting-edge technologies:

LangChain: Used for leveraging large language models to perform complex retrieval and question-answering tasks.

Pandas: Provides robust data structures and operations for manipulating numerical tables and time series.

OpenAI Embeddings and Chroma: These are utilized for embedding questions and retrieving the most relevant information from a vectorized database.

Each question is categorized under topics such as Access Control, Data Security, Subcontractors, and more. The tool evaluates answers based on the documentation provided or retrieved, scoring each on a scale from 0 to 10. A score of 0 indicates no evidence of compliance, while a score of 10 signifies comprehensive and consistent adherence to the requirements.

This automated assessment aims to streamline the compliance review process, making it more efficient and consistent. It's particularly useful for compliance officers, auditors, and management teams seeking to ensure that their company practices align with legal and ethical standards.

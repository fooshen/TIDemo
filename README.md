# TIDemo
Demo solution for TI - SDA and TSCC use case

Solution is provided as-is, and is not for any production use. This is strictly a demo solution and is intended to illustrate specific examples using AI in Power Platform to extract a given document with its relevant information. 
Solution uses Prompts in AI Builder. Any tuning will require changes to the prompts. Changes to type of documents may require changes to the extraction orchestration process in Power Automate.
Solution consists of:
1. Model Driven App - this is the primary app to upload the relevant documents and trigger the extraction process. Extracted result will also be showed in this app.
2. Dataverse tables - a set of tables to capture the uploaded documents and the relevant extracted fields.
3. Power Automate cloud flows - the main orchestrator that performs the text extraction and use GPT prompts to summarize the extraction results.
4. AI Builder prompts - a set of prompts based on the required extractions.

Download unmanaged solutions:
(Note: Unmanaged solutions are not to be imported into Test/UAT/Prod environments. Please only import to Dev or personal environments. For more information about unmanaged vs managed solutions: https://learn.microsoft.com/en-us/power-platform/alm/solution-concepts-alm)


# Prompt-flow examples

[![code style: black](https://img.shields.io/badge/code%20style-black-000000.svg)](https://github.com/psf/black)
[![license: MIT](https://img.shields.io/badge/License-MIT-purple.svg)](../LICENSE)

## Prerequisites

- Bootstrap your python env. 
  - e.g: create a new [conda](https://conda.io/projects/conda/en/latest/user-guide/getting-started.html) environment. `conda create -n pf-examples python=3.9`.
  - install required packages in python environment : `pip install -r requirements.txt`
    - show installed sdk: `pip show promptflow-sdk`


## Examples available
**Tutorials** ([tutorials](tutorials))
path|status|description
-|-|-
[quickstart.ipynb](tutorials/get-started/quickstart.ipynb)|[![batch-score-rest](https://github.com/Azure/azureml-examples/workflows/cli-scripts-batch-score-rest/badge.svg?branch=main)](https://github.com/Azure/azureml-examples/actions/workflows/cli-scripts-batch-score-rest.yml)| get started
[deploy.ipynb](tutorials/flow-deploy/deploy.ipynb)|[![batch-score-rest](https://github.com/Azure/azureml-examples/workflows/cli-scripts-batch-score-rest/badge.svg?branch=main)](https://github.com/Azure/azureml-examples/actions/workflows/cli-scripts-batch-score-rest.yml)| deploy flow as endpoint
[pipeline.ipynb](tutorials/flow-in-pipeline/pipeline.ipynb)|[![batch-score-rest](https://github.com/Azure/azureml-examples/workflows/cli-scripts-batch-score-rest/badge.svg?branch=main)](https://github.com/Azure/azureml-examples/actions/workflows/cli-scripts-batch-score-rest.yml)| flow as component in pipeline
[run.ipynb](tutorials/advanced-run-management/run.ipynb)|[![batch-score-rest](https://github.com/Azure/azureml-examples/workflows/cli-scripts-batch-score-rest/badge.svg?branch=main)](https://github.com/Azure/azureml-examples/actions/workflows/cli-scripts-batch-score-rest.yml)| advanced flow run management

**Flows** ([flows](flows))

[Standard](flows/standard/) flows

path|status|description
-|-|-
[basic](flows/standard/basic/flow.dag.yaml)|[![batch-score-rest](https://github.com/Azure/azureml-examples/workflows/cli-scripts-batch-score-rest/badge.svg?branch=main)](https://github.com/Azure/azureml-examples/actions/workflows/cli-scripts-batch-score-rest.yml)| a basic flow with prompt and python tool.
[basic-with-connection](flows/standard/basic-with-connection/flow.dag.yaml)|[![batch-score-rest](https://github.com/Azure/azureml-examples/workflows/cli-scripts-batch-score-rest/badge.svg?branch=main)](https://github.com/Azure/azureml-examples/actions/workflows/cli-scripts-batch-score-rest.yml)| a basic flow using custom connection with prompt and python tool
[basic-with-builtin-llm](flows/standard/basic-with-builtin-llm/flow.dag.yaml)|[![batch-score-rest](https://github.com/Azure/azureml-examples/workflows/cli-scripts-batch-score-rest/badge.svg?branch=main)](https://github.com/Azure/azureml-examples/actions/workflows/cli-scripts-batch-score-rest.yml)| a basic flow using builtin llm tool
[intent-copilot](flows/standard/intent-copilot/flow.dag.yaml)|[![batch-score-rest](https://github.com/Azure/azureml-examples/workflows/cli-scripts-batch-score-rest/badge.svg?branch=main)](https://github.com/Azure/azureml-examples/actions/workflows/cli-scripts-batch-score-rest.yml)| a flow created from existing langchain python code
[flow-with-symlinks](flows/standard/flow-with-symlinks/flow.dag.yaml)|[![batch-score-rest](https://github.com/Azure/azureml-examples/workflows/cli-scripts-batch-score-rest/badge.svg?branch=main)](https://github.com/Azure/azureml-examples/actions/workflows/cli-scripts-batch-score-rest.yml)| a flow created with external code reference
[web-classification](flows/standard/web-classification/flow.dag.yaml)|[![batch-score-rest](https://github.com/Azure/azureml-examples/workflows/cli-scripts-batch-score-rest/badge.svg?branch=main)](https://github.com/Azure/azureml-examples/actions/workflows/cli-scripts-batch-score-rest.yml)| a flow demonstrating multi-class classification with LLM. Given an url, it will classify the url into one web category with just a few shots, simple summarization and classification prompts.


- [Evaluation](flows/evaluation/) flows

path|status|description
-|-|-
[basic-eval](flows/standard/basic-eval/flow.dag.yaml)|[![batch-score-rest](https://github.com/Azure/azureml-examples/workflows/cli-scripts-batch-score-rest/badge.svg?branch=main)](https://github.com/Azure/azureml-examples/actions/workflows/cli-scripts-batch-score-rest.yml)| a basic evaluation flow.
[classification-accuracy-eval](flows/standard/classification-accuracy-eval/flow.dag.yaml)|[![batch-score-rest](https://github.com/Azure/azureml-examples/workflows/cli-scripts-batch-score-rest/badge.svg?branch=main)](https://github.com/Azure/azureml-examples/actions/workflows/cli-scripts-batch-score-rest.yml)| a flow illustrating how to evaluate the performance of a classification system.

[Chat](flows/chat/) flows
path|status|description
-|-|-
[basic-chat](flows/standard/basic-chat/flow.dag.yaml)|[![batch-score-rest](https://github.com/Azure/azureml-examples/workflows/cli-scripts-batch-score-rest/badge.svg?branch=main)](https://github.com/Azure/azureml-examples/actions/workflows/cli-scripts-batch-score-rest.yml)| a basic chat flow.
[chat-with-wikipedia](flows/standard/chat-with-wikipedia/flow.dag.yaml)|[![batch-score-rest](https://github.com/Azure/azureml-examples/workflows/cli-scripts-batch-score-rest/badge.svg?branch=main)](https://github.com/Azure/azureml-examples/actions/workflows/cli-scripts-batch-score-rest.yml)| a flow demonstrating Q&A with GPT3.5 using information from Wikipedia to make the answer more grounded. 

**Connections** ([connections](connections))
path|status|description
-|-|-
[connection.ipynb](connections/connection.ipynb)|[![batch-score-rest](https://github.com/Azure/azureml-examples/workflows/cli-scripts-batch-score-rest/badge.svg?branch=main)](https://github.com/Azure/azureml-examples/actions/workflows/cli-scripts-batch-score-rest.yml)| connections sdk experience

## Reference

* [Documentation](https://promptflow.azurewebsites.net/)
# Granite Guardrails for LLMs
This repository demonstrates how to integrate Granite Guardrails into your workflow to enforce safety and governance on both prompts and responses for Large Language Models (LLMs).

## Overview
Granite Guardrails provide a robust mechanism to govern both input prompts and output responses when working with LLMs. By leveraging these guardrails, you ensure that your application remains within defined safety and usage boundaries.

Additionally, MAAS is used to host the LLMs and so obtain the actual keys required for accessing and securing the LLMs from there.

## Key Features

- **Prompt Safety:** Validate and filter user inputs before they reach the LLM.
- **Response Governance:** Check and enforce safety policies on the responses generated by the LLM.
- **Key Management via MAAS:** Retrieve and manage secure keys for LLMs using MAAS.

## Getting Started

1. **Obtain LLM Keys via MAAS:**  
   Use your MAAS instance to retrieve the actual keys for your LLMs. Follow your organization's MAAS documentation to securely access and manage these keys.

2. **Setup Granite Guardrails:**  
   Follow the examples provided in this repository to integrate Granite Guardrails into your workflow. The guardrails will automatically validate both prompts and responses according to your defined policies.

3. **Run the Example Workflow:**  
Check out the notebook in this repo for a complete, step-by-step usage guide.

## Reference
For more detailed instructions and to see Granite Guardrails in action, please refer to:

[Granite Guardian Cookbook](https://github.com/ibm-granite/granite-guardian/blob/main/cookbooks/granite-guardian-3.1/usage_governance_workflow_vllm.ipynb).

[LLM GuardRails with Granite Guardian
](https://github.com/rh-aiservices-bu/llm-on-openshift/blob/main/examples/notebooks/langchain/Langchain-Granite-Guardian.ipynb)
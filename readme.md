# Azure AI Foundry SDK Chat Application

This repository contains the starter code and completed exercise for building a generative AI chat application that connects to a model deployed in Microsoft Foundry. It demonstrates how to utilize the OpenAI SDK and the Responses API to create an interactive chat interface.

## Application Preview

Here are the step-by-step screenshots demonstrating the application configuration, environment setup, and the final interactive chat interface in action:

| Screenshots ||
| --- | --- |
| ![Initialization](screenshots/Screenshot%202026-07-11%20at%2011.42.29%E2%80%AFpm.png) | ![Portal Configuration](screenshots/Screenshot%202026-07-11%20at%2011.43.23%E2%80%AFpm.png) |

| --- | --- |
| ![Deployment Setup](screenshots/Screenshot%202026-07-11%20at%2011.46.05%E2%80%AFpm.png) | ![Endpoint Integration](screenshots/Screenshot%202026-07-11%20at%2011.46.48%E2%80%AFpm.png) |

| --- | --- |
| ![SDK Integration](screenshots/Screenshot%202026-07-11%20at%2011.49.50%E2%80%AFpm.png) | ![Application Test](screenshots/Screenshot%202026-07-11%20at%2011.50.27%E2%80%AFpm.png) |

| --- |
| ![Completed Execution](screenshots/Screenshot%202026-07-11%20at%2011.52.40%E2%80%AFpm.png) |

---

## Prerequisites

Before running the application, ensure you have the following:

- An active **Azure subscription** with permissions to create AI resources.
- **Visual Studio Code** installed.
- **Python 3.13.x** installed.
- **Git** installed and configured.
- **Azure CLI** installed and authenticated via `az login`.
- A project and model deployment configured in the **Microsoft Foundry portal**.

## Setup Instructions

1. **Clone the Repository:**
   ```bash
   git clone [https://github.com/svempeny-gpsw/azure-foundry-sdk-chat.git](https://github.com/svempeny-gpsw/azure-foundry-sdk-chat.git)
   cd azure-foundry-sdk-chat
2. **Configure Environment Variables:**
   Create a .env file in the root directory and populate it with your project credentials obtained from the Azure Foundry portal:
    ```bash
    AZURE_AI_FOUNDRY_ENDPOINT="your-project-endpoint"
    AZURE_AI_FOUNDRY_KEY="your-project-key"
    MODEL_DEPLOYMENT_NAME="gpt-5.2"
3. **Install Dependencies:**
   ```bash
       pip install azure-identity openai
**Running the Application**
Authenticate your Azure CLI context and execute the main chat script:
```bash
    az login
    python chat.py

   
   

# Lab 2 - Expand Your Multi-Agent Capabilities

**Expected Duration:** 120 minutes


## Introduction

Now that you know the basics of Multi-Agent scenarios, it's time to build your own! Don't worry, you are not alone, your coaches will steer your boat in the right direction. 

Now you might be wondering,  <em>where do I even start? </em>

**Accelerating 🚗💨!** Microsoft has built some accelerators to help you on your journey. We will start from a sample app that will aid you on having the basic setup created. Today we will be using the [Multi-Agent Custom Automation Engine Solution Accelerator (MACAE)](https://github.com/microsoft/Multi-Agent-Custom-Automation-Engine-Solution-Accelerator), that provides a ready to go application to use as the base of the MVP, or as a reference, allowing you to hit the ground running.

This is an open-ended exercise, which means there is no ground truth, as what you need is different from other teams' use cases. Therefore, this exercise will require you to consult documentation, ask for help and brainstorm as a team.

### Agenda

1. First and foremost we will run this application with dummy data (with a basic example only as a baseline) locally. Please make sure you are still using Github Codespaces  for ease of implementation. 
2. Your team will think of a strategy to implement your use case. Feel free to use the good old pen and paper to draw some ideas and brainstorm. 
3. Implement your ideas! Go to the source code of your app and build the Python code to personalize your agents, actions, communication among them and so on. 

Let's get started! 🚀


## Step 1 - Local Deployment 💻

1. **Copy your `.env` file:**

- Navigate to the `src` folder and copy your `.env` file from root on this section.

2. **Install requirements:**

- In each of the frontend and backend folders -
Open a terminal in the `src` folder and run:
```bash
pip install -r requirements.txt
```

3. **Run the application:**
- First, we run the backend:
```bash
cd Challenge2/src/backend && python app.py
```
- In a new terminal, run:
```bash
cd Challenge2/src/frontend && python frontend_server.py
```

4. Open a browser and navigate to `http://localhost:3000`
5. To see swagger API documentation, you can navigate to `http://localhost:8000/docs`

Great! If you've made it this far you should be able to see an empty app that looks something like this:

![image](https://github.com/user-attachments/assets/e5c6fb4d-e615-46fb-ba6e-a7ddfb7714e0)


Now we need to populate it. 

[add data]

## Step 2 -  The Ideation of Customization 💡

This solution is designed to be easily customizable. You can modify the front end site, or even build your own front end and attach to the backend API. 

You can further customize the backend by adding your own agents with their own specific capabilities. Deeper technical information to aid in this customization can be found in this [document](./documentation/CustomizeSolution.md).

### Additional resources

- [Python FastAPI documentation](https://fastapi.tiangolo.com/learn/)
- [AutoGen Framework Documentation](https://microsoft.github.io/autogen/dev/user-guide/core-user-guide/index.html)
- [Azure Container App documentation](https://learn.microsoft.com/en-us/azure/azure-functions/functions-how-to-custom-container?tabs=core-tools%2Cacr%2Cazure-cli2%2Cazure-cli&pivots=container-apps)
- [Azure OpenAI Service - Documentation, quickstarts, API reference - Azure AI services | Microsoft Learn](https://learn.microsoft.com/en-us/azure/ai-services/openai/concepts/use-your-data)
- [Azure Cosmos DB documentation](https://learn.microsoft.com/en-us/azure/cosmos-db/)
  

## Step 3 -  Customization comes to Fruition  🍎


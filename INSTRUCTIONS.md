# VS Code for the Web - Azure AI Foundry

We've generated a simple development environment for you to play with sample code to create and run the agent that you built in the Azure AI Foundry playground.

The Azure AI Foundry extension provides tools to help you build, test, and deploy AI models and AI Applications directly from VS Code. It offers simplified operations for interacting with your models, agents, and threads without leaving your development environment. Click on the Azure AI Foundry Icon on the left to see more.

Follow the instructions below to get started!

## Open the terminal

Press ``Ctrl-` `` &nbsp; to open a terminal window.

## Run your agent locally

To run the agent that you created in AI Foundry, and view the output in the terminal run the following command:

```bash
dotnet run run_agent.cs
```

## Update your agent configuration

In the left hand activity bar:

- Open the Azure AI Foundry tab in the navigation bar
- Under "Resources", expand the "Agents" section and click on the corresponding agent name
- Click "Open YAML File"
- Make any changes to the agent definition
- Update the agent in Azure AI Foundry

## Continuing on your local desktop

You can keep working locally on VS Code Desktop by clicking "Continue On Desktop..." at the bottom left of this screen. Be sure to take the .env file with you using these steps:

- Right-click the .env file
- Select "Download"
- Move the file from your Downloads folder to the local git repo directory
- For Windows, you will need to rename the file back to .env using right-click "Rename..."

## More examples

Check out [Azure AI Projects client library for .NET](https://github.com/Azure/azure-sdk-for-net/blob/main/sdk/ai/Azure.AI.Projects/README.md) for more information on using this SDK.

## Troubleshooting

- If you are instantiating your client via endpoint on an Azure AI Foundry project, ensure the endpoint is set in the `run_agent` script as `https://{your-foundry-resource-name}.services.ai.azure.com/api/projects/{your-foundry-project-name}`

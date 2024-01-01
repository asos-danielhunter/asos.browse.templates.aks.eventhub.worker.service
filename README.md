# .NET EventHub Worker Service Template for AKS

This is a .NET template for creating an EventHub worker service that can be deployed to Azure Kubernetes Service (AKS). The template includes the necessary configurations for interacting with Azure EventHub.

## Prerequisites

Before using this template, make sure you have the following installed:

- [.NET SDK](https://dotnet.microsoft.com/download)
- [Docker](https://www.docker.com/products/docker-desktop)
- [kubectl](https://kubernetes.io/docs/tasks/tools/install-kubectl/)
- [Azure CLI](https://docs.microsoft.com/en-us/cli/azure/install-azure-cli)

## Getting Started

1. Clone this repository:

    ```bash
    git clone https://github.com/asos-danielhunter/asos.browse.templates.aks.eventhub.worker.service.git
    ```

2. Navigate to the project directory:

    ```bash
    cd asos.browse.templates.aks.eventhub.worker.service
    ```

3. Build the Docker image:

    ```bash
    docker build -t asos.browse.templates.aks.eventhub.worker.service .
    ```

5. Deploy to AKS:

    ```bash
    #Todo: replace with pipeline location
    ```

6. Monitor logs:

    #Todo: replace with AppInsights location

## Configuration

Update the `appsettings.json` file with your Azure EventHub connection string and other configurations.

```json
{
  "EventHubName": "<EventHubName>",
  "StorageAccountContainerName": "<StorageAccountContainerName>",
  "StorageAccountConnectionString": "<StorageAccountConnectionString>",
  "EventHubConnectionString": "<EventHubConnectionString>"
}

<!-- This is a template you can use for quick progress days. It removes a lot of the steps we encourage you to share in the longer template 000-DAY-ARTICLE-LONG-TEMPLATE.MD-->

# Overview of Azure Services, Building a Website and Cloud Shell

## Cloud Research

- Went through an overview of what Azure provides

- Setup a test Wordpress website and went over the different scaling/pricing models available

- Cloud Shell is a browser-based command line for managing and developing Azure resources

  - Cloud Shell provides two experiences to choose from: Bash or PowerShell
    - Both of these include access to Azure CLI (Command Line Interface)
  - You can easily start and stop websites from here
    Some Commands: 1. List all Resource Groups in a subscription:
    az group list --output table 2. List all resources in the "learn" group
    az resource list \
     --resource-group learn-a0d0a5a4-aac4-4a7b-911b-e65e166ccbd2 \
     --resource-type Microsoft.Web/sites 3. Stop webapp
    az webapp stop \
     --resource-group learn-a0d0a5a4-aac4-4a7b-911b-e65e166ccbd2 \
     --name <web app name>

        4. Start  WebApp
        az webapp start \
            --resource-group learn-a0d0a5a4-aac4-4a7b-911b-e65e166ccbd2 \
            --name <web app name>

## Social Proof

[Twitter](https://twitter.com/SpencerGarth19/status/1305568790495793152)

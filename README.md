# Azure Minecraft Server

A simple ARM template to quickly setup a minecraft server on azure

[![Deploy to Azure](https://aka.ms/deploytoazurebutton)](https://portal.azure.com/#create/Microsoft.Template/uri/https%3A%2F%2Fraw.githubusercontent.com%2Fdanspark%2Fazure-minecraft-server%2Fmaster%2Ftemplates%2Fitzg-minecraft-server.json)

## What does it create

- One storage account with a file share to storage the server files
- One azure container instance with the [itzg/minecraft-server]([https://link](https://hub.docker.com/r/itzg/minecraft-server)) image

## How to use

1. Click the "Deploy to Azure" button.
2. Sign in with your Azure account.
3. Select your subscription and resource group to deploy, the resources will be created on the resource group's region. If you're creating a new resource group, you'll have to select a region, select the region closest to your location.
4. Click Review + Create, then Create. Your server will be created shortly.

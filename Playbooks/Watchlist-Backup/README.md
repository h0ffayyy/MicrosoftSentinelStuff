# Watchlist-Backup


This playbook is designed to perform regular backups of your Microsoft Sentinel watchlists and store the backups in Azure blob storage.

## Requirements

This playbook utilizes an Azure AD app registration to authenticate to the Azure API. You'll want to create a new app registration before deploying this template.

## Resources

This playbooks deploys the following resources:

* The logic app
* A key vault which stores the client secret for your AAD app registration
* A storage account and blob storage container to hold the Watchlist backups

## Screenshot

![playbook visual overview](./images/watchlist-backup.png)

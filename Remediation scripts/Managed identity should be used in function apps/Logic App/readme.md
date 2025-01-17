# Logic Apps sample playbook to remediate

This sample playbook allows you to add System Managed Identity to Function App to remeidate "Managed identity should be used in function apps" Microsoft Defender for Cloud recomendations.
The playbook leverages a "Managed Identity" which needs to be configured after deployment. This "Managed Identity" also requires the appropriate permissions on the resources that you would like to remediate.

[![Deploy to Azure](https://aka.ms/deploytoazurebutton)](https://portal.azure.com/#create/Microsoft.Template/uri/https%3A%2F%2Fraw.githubusercontent.com%2Fnoendscripting%2FMicrosoft-Defender-for-Cloud%2Fmain%2FRemediation%20scripts%2FManaged%20identity%20should%20be%20used%20in%20function%20apps%2FLogic%20App%2Fmdc-logicapp-MSI-template.json)

# Contributing

This project welcomes contributions and suggestions.  Most contributions require you to agree to a
Contributor License Agreement (CLA) declaring that you have the right to, and actually do, grant us
the rights to use your contribution. For details, visit https://cla.microsoft.com.

When you submit a pull request, a CLA-bot will automatically determine whether you need to provide
a CLA and decorate the PR appropriately (e.g., label, comment). Simply follow the instructions
provided by the bot. You will only need to do this once across all repos using our CLA.

This project has adopted the [Microsoft Open Source Code of Conduct](https://opensource.microsoft.com/codeofconduct/).
For more information see the [Code of Conduct FAQ](https://opensource.microsoft.com/codeofconduct/faq/) or
contact [opencode@microsoft.com](mailto:opencode@microsoft.com) with any additional questions or comments.

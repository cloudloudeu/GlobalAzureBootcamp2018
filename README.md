# Global Azure Bootcamp 2018

![gablogo][gablogo]

All around the world user groups and communities want to learn about Azure and Cloud Computing!

On **April 21, 2018**, all communities will come together once again in the fifth great [Global Azure Bootcamp](https://global.azurebootcamp.net/) event!

You will find included in this repository all materials use during the demos so you can try them at home.

## Prerequisites

* Azure Subscription. Azure Pass will be handed out for every attendee. Otherwise get Free account (https://azure.microsoft.com/en-us/free/)
* Microsoft Account (Live ID) https://signup.live.com/
* Visual Studio Community 2017 (https://www.visualstudio.com/thank-you-downloading-visual-studio/?sku=Community&rel=15)
* GitHub account (https://github.com/join)
* Git agent (https://git-scm.com/download/win)
* Azure Powershell (https://docs.microsoft.com/en-us/powershell/azure/install-azurerm-ps?view=azurermps-5.7.0)
* Azure SDK (https://www.microsoft.com/en-us/download/details.aspx?id=54289)


## Workshop. Contoso - Life after initial deployment.
Life has been going very well at *Contoso* as they just released the first version of their latest product in production.

Yesterday, *Contoso* lack of visibility in production bite them back as issues started to appear, the support & development teams didn't have much information to help troubleshoot the errors. After a long retrospective meeting, they decided to improve their maturity in troubleshooting and management of their cloud infrastructure.

At the end of their meeting they agreed on the following:

* Use an Application Performance Management (APM) tool to improve the visibility of their application
* Centralize the logs of their application and activities in Azure
* Have an audit logs of VMs remote access in production
* Better control the network traffic reaching virtual machines
* Be better at troubleshooting hard to diagnose problems like high CPU or memory leaks
* Reduce the noise to ensure people are not flooded by emails when a problem occurs
* Ensure only the right people have access to the cloud infrastructure
* Allow people to create/maintain cloud resources which are aligned with the company new governance.

The team has been assigned a couple of days to find tools & put new processes in place to check all the action items of the list above. Excited, the team will actively start documenting themselves and working on this tomorrow.

## Overview of the day

Step | Tittle | Description
-----|--------|------------
[Step 1](./Step1/README.md) | Provision Log Analytics | Deploy Log Analytics artifacts using an ARM template that we'll use throughout the day using the Azure Portal.
[Step 2](./Step2/README.md) | Provision environment | Deploy base artifacts using an ARM template that we'll use throughout the day using the Azure Portal.
[Step 3](./Step3/README.md) | Application Insights 1 | Learn how to use Application Insight to find problem in a running solution.
[Step 4](./Step4/README.md) | Log Analytics | Configuring Key Vault Analytics solution and creating alerts.
[Step 5](./Step5/README.md) | Azure Security Center |
[Step 6](./Step6/README.md) | App Service | How to configure remote debugging for Web Apps & Visual Studio 2017 and how to edit in production.
[Step 7](./step7/readme.md) | Application Insights 2 | How to enable exception snapshot, App profiling and Snapshot debugger (optional)
[Step 8](./Step8/README.md) | Azure Monitor | Explore monitoring and troubleshooting with Azure Monitor.
[Step 9](./Step9/README.md) | ARM Governance | Learn how to use and configure Azure policies


[gablogo]: ./media/logo-2018-500x444.png "Global Azure Bootcamp logo"

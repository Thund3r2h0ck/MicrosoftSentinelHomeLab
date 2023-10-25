<h1>Creating a Home Lab for Microsoft Sentinel</h1>


<h2>Description</h2>
Project consists of creating an enviorment in Microsoft Azure for practical experience with Microsoft Sentinel.
<br />

<h2>What I have Learned</h2>

- Navigating through the Microsoft Azure Portal
- Creating a Workspace for Microsoft Sentinel in Azure
- Assigning the Microsoft Sentinel Training Lab Solution from Azure Marketplace to the Created Microsoft Sentinel Workspace 

<h2>Languages and Utilities Used</h2>

- <b>Microsoft Sentinel</b>
- <b>Microsoft Sentinel Training Lab Solution </b>

<h2>Environments Used </h2>

- <b>Microsoft Azure</b>

<h2>Prequesits</h2>

- <b>An existing Microsoft Azure Subscription (The Azure Free Trial is enough for this project)</b>

<h2>Steps taken:</h2>

<h3>Creating a Sentinel Workspace</h3>

- Within the Azure Portal, I had to create a new Microsoft Sentinel workspace. (Microsoft allow a 31 day free trial and what I will be using)
- Needed to assign a resource group with the subscription for the workspace (I had to create a new resource group)
- Ensure Validation passed and waiting for Deployment to finish
- Added the newly created workspace into Microsoft Sentinel and is ready for use.

<h3>Deploying Microsoft Sentinel Training Lab Solution</h3>

- Searched for the Microsfot Sentinel Training Lab Solution in the Azure Portal from Marketplace
- According overview for the Training Lab Solution, Upon deployment it will add pre-recorded data into a Microsoft Sentinel Workspace and allows simulated scenarios that showcases Microsoft Sentinel features
- Just like creating the Microsoft Sentinel Workspace, A subscription and a resource group will be needed. An added requirement is assigning a Microsoft Sentinel Workspace to the Training Lab Solution (I used my newly created Workspace)
- Wait for deployment to finish after validation.

<h2>Resources Used</h2>

- <b><a href='https://github.com/Azure/Azure-Sentinel/blob/master/Solutions/Training/Azure-Sentinel-Training-Lab/Modules/Module-1-Setting-up-the-environment.md'>Azure Sentinel Training Lab Module 1 - TristankMS</a></b>


<!--
 ```diff
- text in red
+ text in green
! text in orange
# text in gray
@@ text in purple (and bold)@@
```

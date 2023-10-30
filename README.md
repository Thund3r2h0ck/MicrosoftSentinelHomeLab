<h1>Creating a Home Lab for Microsoft Sentinel</h1>


<h2>Description</h2>
Project consists of creating an enviorment in Microsoft Azure for practical experience with Microsoft Sentinel.
<br />

<h2>What I have Learned</h2>

- Navigating through the Microsoft Azure Portal
- Creating a Workspace for Microsoft Sentinel in Azure
- Assigning the Microsoft Sentinel Training Lab Solution from Azure Marketplace to the Created Microsoft Sentinel Workspace
- Authorizing an API Connector 
- Adding Data Connectors through the Content Hub in Microsoft Sentinel

<h2>Languages and Utilities Used</h2>

- <b>Microsoft Sentinel</b>
- <b>Microsoft Sentinel Training Lab Solution </b>

<h2>Environments Used </h2>

- <b>Microsoft Azure</b>

<h2>Prerequisite</h2>

- <b>An existing Microsoft Azure Subscription (The Azure Free Trial is enough for this project)</b>

<h2>Steps taken:</h2>

<h3>Creating a Sentinel Workspace</h3>

- In Microsoft Azure, search for Microsoft Sentinel
<img src='https://i.imgur.com/UPuQDKV.png'>
  
- Within the Azure Portal, I had to create a new Microsoft Sentinel instance and workspace. (Microsoft allow a 31 day free trial and what I will be using)
<img src='https://i.imgur.com/nQcouxw.png'>
<img src='https://i.imgur.com/z0r9pTT.png'>

- Needed to assign a resource group with the subscription for the workspace (I had to create a new resource group)
<img src='https://i.imgur.com/3SomKpt.png'>
  
- Ensure Validation passed and waiting for Deployment to finish
- Added the newly created workspace into Microsoft Sentinel and is ready for use.

<h4>Deploying Microsoft Sentinel Training Lab Solution</h4>

- Searched for the Microsfot Sentinel Training Lab Solution in the Azure Portal from Marketplace
<img src='https://i.imgur.com/ggnfwBV.png'>

- According overview for the Training Lab Solution, Upon deployment it will add pre-recorded data into a Microsoft Sentinel Workspace and allows simulated scenarios that showcases Microsoft Sentinel features.
- Just like creating the Microsoft Sentinel instance, clicked on create and fill in the required Subscription, Resource, and Workspace.
<img src='https://i.imgur.com/PNOBX3p.png'>
<img src='https://i.imgur.com/kN2CA06.png'>

- Clicked on <b>Review + create</b> for validation, and wait for deployment to be completed.

<h3>Attaching an API Connector</h3>

- In the Resource Group I have created, an API connection was deployed from the Training Lab Solution.
<img src='https://i.imgur.com/V7BGzxh.png'>

- When clicking on the API Connection, clicked on <b>Edit API connection</b> under <b>General</b> and clicked authorized the API connection.
<img src='https://i.imgur.com/R5xDwny.png'>
<img src='https://i.imgur.com/wZUwSAI.png'>

- Clicked on save 

<h3>Installing and Enable Data Connectors</h3>

<h4>Connecting Azure Activity Data Connector</h4>

- In Microsoft Sentinel, clicked on my Sentinel workspace to access the overview.
<img src='https://i.imgur.com/QJra9w6.png'>

- Clicked on <b>Content Hub</b> under <b>Content Management</b> to access the Data Connector.
<img src='https://i.imgur.com/q8CXa4t.png'>

- Searched for Azure Activity in the Content Hub search bar, click on Azure Activity and install.
<img src='https://i.imgur.com/mJ033N0.png'>

- In <b>Data connectors</b> under <b>configuration</b>, I can confirm that Azure Activity has been installed.
<img src='https://i.imgur.com/gP1vRgX.png'>

- After clicking on <b>Open connector page</b> and <b>Launch Azure Policy Assignment wizard</b>, 
<img src='https://i.imgur.com/fS2d77F.png'>

<h2>Resources Used</h2>

- <b><a href='https://github.com/Azure/Azure-Sentinel/blob/master/Solutions/Training/Azure-Sentinel-Training-Lab/Modules/Module-1-Setting-up-the-environment.md'>Azure Sentinel Training Lab Module 1 - TristankMS</a></b>
- <b><a href='https://github.com/Azure/Azure-Sentinel/blob/master/Solutions/Training/Azure-Sentinel-Training-Lab/Modules/Module-2-Data-Connectors.md'>Azure Sentinel Training Lab Module 2 - TristankMS</a></b>

<!--
 ```diff
- text in red
+ text in green
! text in orange
# text in gray
@@ text in purple (and bold)@@
```

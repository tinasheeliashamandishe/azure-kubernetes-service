<h1>Deploy an Azure Kubernetes service Cluster</h1>

<h2>Description</h2>
This lab will Deploy an Azure Kubernetes service Cluster.<br /><br />
Azure Kubernetes Service (AKS) is a managed Kubernetes service provided by Microsoft Azure. Kubernetes is an open-source container orchestration platform that automates the deployment, scaling, and management of containerized applications.
<br /><br />
With Azure Kubernetes Service, developers can deploy, manage, and scale containerized applications using Kubernetes without having to manage the underlying infrastructure. AKS abstracts away the complexity of managing Kubernetes clusters, allowing developers to focus on building and deploying their applications.<br />

<h2>Environments Used </h2>

- <b>Microsoft Azure</b>
- Credits  to <b>Virtual TechBox</b> for the Container image

<h2>Lab walk-through:</h2>

<p align="center">
<h4>Step 1</h4>
Create a  Azure Kubernetes Cluster.<br/>Link it to your Container image registry, if you want to deploy images in your registry.br/>
<img src="https://i.imgur.com/zza8qtD.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<img src="https://i.imgur.com/xyXZVgN.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />

<h4>Step 2</h4> 
Confirm the deployment.<br/>
<img src="https://i.imgur.com/Ukg7jyw.png" height="80%" width="80%" alt="Disk Sanitization Steps"/><br/>
<br />

<h4>Once the cluster has been deployed. Lets add a container to it.<br />We are going to deploy the container in our azure registry.</h4><br />


<h4>Step 2</h4> 
Once resource is deployed, go to workloads and services. Insert YAML definitions which will deploy the images in the container registry and run it as a container.<br/>
<img src="https://i.imgur.com/f7DizvF.png" height="80%" width="80%" alt="Disk Sanitization Steps"/><br/>
<img src="https://i.imgur.com/ksNLFsN.png" height="80%" width="80%" alt="Disk Sanitization Steps"/><br/>
<br />

<h4>Step 2</h4> 
Confirm the deployments are up and runnning.<br/>
<img src="https://i.imgur.com/K3sbLbI.png" height="80%" width="80%" alt="Disk Sanitization Steps"/><br/>
<img src="https://i.imgur.com/3Dcwyv1.png" height="80%" width="80%" alt="Disk Sanitization Steps"/><br/>
<br />

<h4>Step 2</h4> 
Click on the IP address and you will be directed to your application.<br/>
<img src="https://i.imgur.com/vGW0Jca.png" height="80%" width="80%" alt="Disk Sanitization Steps"/><br/>
<br />




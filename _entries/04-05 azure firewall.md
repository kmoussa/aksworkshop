---
sectionid: azurefirewall
sectionclass: h2
parent-id: advancedclustersetup
title: Use Azure Firewall to lockdown cluster North/South traffic.
---

It's very important to secure the traffic going in and out of your AKS cluster, there are multiple tools to implement this kind of secure lockdown for your cluster, in this task we will use (Azure firewall)<https://docs.microsoft.com/en-us/azure/firewall/overview> which is a managed fully statefull firewall as a service, cloud based network security service that protects your Azure Virutal Network resources.

In this task, you are required to integrate your AKS cluster implementation with Azure firewall and create the right rules to allow only what is needed for your cluster to work properly.

(Optional recommended addresses and port for AKS clusters)<https://docs.microsoft.com/en-us/azure/aks/limit-egress-traffic#optional-recommended-addresses-and-ports-for-aks-clusters>

<% Collapsible %>

<% endCollapsible %>
---
title: "Network"
description: ""
lead: ""
draft: false
images: []
menu: 
  docs:
    parent: "electric-blocks"
weight: 8
toc: true
---

Your location, workspace and environment ready, the next step is to create your network.

{{< img src="net.png" alt="Minecraft Creative Menu" caption="<em></em>" class="border-0" style="width:40%;" >}}

## What’s a network?

A network deploys the nodes that make up a blockchain network. These nodes can be part of a Consortium, a private or public network, or a Tesnet with:

* Bootnode
* RPC node
* Regular Nodes
* Block explorer
* Prometheus
* Grafana

Access endpoints can be secured using JWT or API KEY.
According to the need, private permissioned, private or public networks can be created.

Depending on the type of technology chosen, the type of consensus can be configured, Ethash (Proof of work), Clique (Proof of authority), IBFT 2.0 (Proof of authority).
Depending on the case, you can configure all the options manually in advanced options


## Creating a network
On the sidebar click on Create Network and fill in the required fields. 
Start by selecting an environment by clicking on change on the top right-hand.
A popup window will open, select the environment that you want.
{{< img src="select.png" alt="Minecraft Creative Menu" caption="<em></em>" class="border-0" style="width:40%;" >}}

After you have selected your environment, close and proceed to fill the required fields. 


The required details and what they do are explained below:
{{< img src="image7.png" alt="Minecraft Creative Menu" caption="<em></em>" class="border-0" style="width:40%;" >}}
* Alias: You'll be able to identify the network by the alias in the dashboard, choose an alias short but representative
* Type: Choose the type of network from the pop-up window that suits your needs. Every network comes with a preset of advanced options that you can edit.
* Authentication: Choose the type of authentication you prefer (JWT | API KEY). 
* Options: It allows changing the parameters of the genesis file that determines the characteristics of the network that is deployed.

**Note**:  Clicking on the toggle shows advance setting which resets your values to default.

Once your required fields are filled correctly click Create

Your network would be created and would automatically open up in your environment Detail.

{{< img src="neted.png" alt="Minecraft Creative Menu" caption="<em></em>" class="border-0" style="width:40%;" >}}
Clicking on the network you have created reveals the network details.

{{< img src="netd.png" alt="Minecraft Creative Menu" caption="<em></em>" class="border-0" style="width:40%;" >}}
Note: You can click on the link below to send an email to us to join an external network.


After creating the network, its data can be viewed as:

* Public keys
* Private keys
* DNS
* TCP/UDP ports
* Enode
And all the necessary data to join an existing network.
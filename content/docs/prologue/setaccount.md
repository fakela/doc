---
title: "Setting up your account"
description: "Setting up your account"

lead: ""
second: ""
draft: false
images: []
menu:
  docs:
    parent: "prologue"
weight: 3
toc: true
---

### Downloading RSK Enterprise Cloud on Azure

<!-- {{< img src="quick.png" alt="Minecraft Creative Menu" caption="<em>Welcome to RSK Enterprise Cloud</em>" class="border-0" >}} -->

The first step to make use of RSK Enterprise cloud is to download it from [Azure Marketplace](https://portal.azure.com/#home).  
Sign into your Microsoft Azure account with the different sign in options available or create an account if you don't have one. 

{{< img src="signin.png" alt="Minecraft Creative Menu" caption="<em></em>" class="border-0" >}} 

Once you are signed in, on Azure Services  click on Marketplace.

{{< img src="azure.png" alt="Minecraft Creative Menu" caption="<em></em>" class="border-0" >}} 

Once you are on the Marketplace, with the search bar search for RSK Enterprise cloud, alternatively you can check the left side navigation and under Categories, click on Blockchain, then select RSK Enterprise Cloud.

{{< img src="market.png" alt="Minecraft Creative Menu" caption="<em></em>" class="border-0" >}} 

On the RSK Enterprise Cloud, select a plan you want and click on **Set up and Subscribe**.

{{< img src="MicrosoftTeams-image.png" alt="Minecraft Creative Menu" caption="<em></em>" class="border-0" >}}

Under the Basics tag, you should see your **Plan details**. You can now fill the fields by selecting the type of **Subscription** you want.

In your **Resource Group** you can select an existing resource group according to your needs or create one.

Your **Resource Group Location** changes based on the Resource Group you select.

Input your name and click on **Review and Subscribe**. 

{{< img src="MicrosoftTeams-image3.png" alt="Minecraft Creative Menu" caption="<em></em>" class="border-0" >}}

Review the terms of use and the information you provided,then  click on the checkbox and proceed to **Subscribe**.

{{< img src="MicrosoftTeams-image5.png" alt="Minecraft Creative Menu" caption="<em></em>" class="border-0" >}}

It takes some seconds to complete your purchase.

{{< img src="MicrosoftTeams-image6.png" alt="Minecraft Creative Menu" caption="<em></em>" class="border-0" >}}

At this point you have completed your purchase of the RSK Enterprise Cloud subscription on the Azure Marketplace. Once  your subscription is complete you can now configure your account by clicking on the **Configure account now**.


You will get redirected to RSK Enterprise Cloud landing page where you  sign in with your Microsoft account

{{< img src="MicrosoftTeams-image7.png" alt="Minecraft Creative Menu" caption="<em></em>" class="border-0" >}}

After the sign in is complete, you will be given a form to fill to finish the linking process of your RSK Enterprise Cloud with your Azure subscription.


On the form complete the following fields: Name, company, Email, Phone Number, Country, Region, Additional Info.

Once the fields are properly filled click on Submit .

{{< img src="m8.png" alt="Minecraft Creative Menu" caption="<em></em>" class="border-0" >}}

Once you submit, you will get a link to download the **platform installer** and the **activation code**.

{{< img src="m9.png" alt="Minecraft Creative Menu" caption="<em></em>" class="border-0" >}}

Download and execute the install package in the target Virtual Machine on your Azure Tenant. Follow the readme install instructions to install rskec-installer-tar.gz.


* Unzip the package: tar zxvf rskec.tar.gz
* Go to the installer directory: cd rskec-installer
* Open the README.md file.

Access the newly installed RSK Enterprise Cloud instance using the public IP of the linux virtual machine.
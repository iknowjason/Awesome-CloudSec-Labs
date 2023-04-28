# Awesome Cloud Security Labs

A list of free cloud native security learning labs. Includes CTF, self-hosted workshops, guided vulnerability labs, and research labs. 

## Sorted by Technology and Category


| Name        | Technology         | Category  |  Author  |  Notes  |
| :------------- |:-------------:| :-----:| :-----: | :------: |
| [AWS CIRT Workshop](https://aws.amazon.com/blogs/security/aws-cirt-announces-the-release-of-five-publicly-available-workshops/)    | AWS | Self-hosted, guided lab |  AWS CIRT | Build with Cloudformation, explore 5 common incident response scenarios observed by AWS CIRT |
| [CloudGoat](https://github.com/RhinoSecurityLabs/cloudgoat)    | AWS | Self-hosted, guided vulnerability lab |  Multiple, [Rhino Security Labs](https://rhinosecuritylabs.com/) | Python orchestration of terraform |
| [Attacking and Defending Serverless Applications](https://attack-defend-serverless.sanscloudwars.com/)    | AWS | Self-hosted, guided vulnerability lab |  [Ryan Nicholson](https://twitter.com/ryananicholson) | Attack and defend a Lambda that you build in your own AWS account with author provided terraform |
| [flaws.cloud](http://flaws.cloud)    | AWS | Author-hosted, CTF challenge |  [Scott Piper](https://twitter.com/0xdabbad00) | Challenge style with levels and clues |
| [flaws2.cloud](http://flaws2.cloud)    | AWS | Author-hosted, CTF challenge |  [Scott Piper](https://twitter.com/0xdabbad00) | Challenge style Attacker and Defender paths |
| [Sadcloud](https://github.com/nccgroup/sadcloud)    | AWS | Self-hosted |  Multiple, [NCC Group](https://www.nccgroup.com) | Terraform code; not guided like CloudGoat |
| [Broken Azure](https://www.brokenazure.cloud/)    | Azure | Author-hosted, CTF challenge |  [Secura](https://github.com/SecuraBV/brokenbydesign-azure) | Provides hints, self-host in your own Azure account using terraform |
| [PurpleCloud Azure AD Workshop](https://lab.purplecloud.network/)    | Azure | Self-hosted, guided vulnerability workshop |  [Jason Ostrom](https://twitter.com/securitypuck) | Guided vulnerability lab requires PurpleCloud and  terraform; username and password is ```sec588``` |
| [Mandiant Azure Workshop](https://github.com/mandiant/Azure_Workshop)    | Azure | Self-hosted, guided commands |  Multiple | Vulnerable by design Azure lab with two scenarios; build with terraform |
| [AzureGoat](https://github.com/ine-labs/AzureGoat)    | Azure | Self-hosted, attack and defense manuals |  Multiple, ine-labs | Bring your own Azure tenant, Build with terraform, one module, provides attack and defense  manuals |
| [XMGoat](https://github.com/XMCyber/XMGoat)    | Azure | Self-hosted, guided labs |  Multiple | Build with terraform, 5 scenarios, solution docs provided |
| [GCP Goat (Josh Jebaraj)](https://gcpgoat.joshuajebaraj.com/index.html)    | GCP | Self-hosted, mdbook lab guide |  [Josh Jebaraj](https://joshuajebaraj.com/) | Host in your own GCP account, build with provided scripts, nice guided lab workbook |
| [GCPGoat (ine-labs)](https://github.com/ine-labs/GCPGoat)    | GCP | Self-hosted, attack and defense manuals|  Multiple, ine-labs | Bring your own GCP account, Build with terraform, one module, provides attack and defense manuals |
| [Bustakube](https://www.bustakube.com/)    | Kubernetes | Self-hosted, import VMs|  [Jay Beale](https://twitter.com/jaybeale) | Vulnerable K8S cluster, Download the VMs to build cluster and import into VMWare, run it |
| [Kubernetes Goat](https://github.com/madhuakula/kubernetes-goat)    | Kubernetes | Self-hosted, multi-cloud, K3S|  [Madhu Akula](https://twitter.com/madhuakula) | Create and host in your own cloud account (GKE, EKS, AKS) or K3S and attack, has a guided workbook |
| [Kubecon NA 2019 CTF](https://securekubernetes.com/)    | Kubernetes | Self-hosted in GKE|  Multiple | Create GCP account, has a guided workbook with two attack and defense scenarios plus bonus challenges|
| [Contained.af](https://contained.af/)    | Container | Author-hosted Challenge|  [Jessie Frazelle](https://twitter.com/jessfraz) | A container escape challenge, break out of it and email the author|
| [TerraGoat](https://github.com/bridgecrewio/terragoat)    | Terraform | Self-hosted multi-cloud (AWS, Azure, GCP)|  Multiple, [Bridgecrew](https://www.bridgecrew.io/) | Vulnerable by design terraform repository|
| [PurpleCloud](https://www.purplecloud.network)    | Azure | Research Lab |  [Jason Ostrom](https://twitter.com/securitypuck) | Using python and terraform, build your own Azure security lab|
| [SimulLand](https://github.com/Azure/SimuLand)    | Azure | Research Lab |  [Roberto Rodriguez](https://twitter.com/Cyb3rWard0g) | Using Azure RM templates, create your own Azure security lab|

## AWS

[AWS CIRT Workshop](https://aws.amazon.com/blogs/security/aws-cirt-announces-the-release-of-five-publicly-available-workshops/):  Build in your own AWS account and explore 5 common incident response scenarioas seen by the AWS CIRT team.

[CloudGoat](https://github.com/RhinoSecurityLabs/cloudgoat):  Vulnerable by design AWS security labs with guided walkthrough.

[Attacking and Defending Serverless Applications](https://attack-defend-serverless.sanscloudwars.com/):  Attack and defend a Lambda that you build in your own AWS account with author provided terraform and scripts.

[flaws.cloud](http://flaws.cloud):  Challenge style with levels and clues.

[flaws2.cloud](http://flaws2.cloud):  Challenge style with both Attacker and Defender paths.

[Sadcloud](https://github.com/nccgroup/sadcloud): Create vulnerable AWS services.


## Azure

[Broken Azure](https://www.brokenazure.cloud/):  A vulnerable by design Azure infrastructure that you can attack.
 
[PurpleCloud Azure AD Workshop](https://lab.purplecloud.network/):  Guided vulnerability workshop simulating an enterprise Azure customer.  It requires PurpleCloud and terraform; username and password is ```sec588```

[Mandiant Azure Workshop](https://github.com/mandiant/Azure_Workshop): Vulnerable by design Azure lab with two scenarios that you build in your own Azure tenant.

[AzureGoat](https://github.com/ine-labs/AzureGoat): Build one module with terraform and walk through the provided attack and defense manuals.

[XMGoat](https://github.com/XMCyber/XMGoat):  Build 5 scenarios in your Azure tenant and walk through solution docs provided.

## GCP

[GCP Goat (Josh Jebaraj)](https://gcpgoat.joshuajebaraj.com/index.html): Host in your own GCP account and build with provided scripts.  It has a nice guided lab workbook.

[GCPGoat (ine-labs)](https://github.com/ine-labs/GCPGoat): Bring your own GCP account and build one module with terraform.  Provides attack and defense manuals.

## Kubernetes

[Bustakube](https://www.bustakube.com/):  Download a vulnerable K8S cluster as VMs that you can import and run locally in VMWare.

[Kubernetes Goat](https://github.com/madhuakula/kubernetes-goat): Create and host in your own cloud account (GKE, EKS, AKS) or K3S and attack.  Includes a guided workbook.

[Kubecon NA 2019 CTF](https://securekubernetes.com/):  Awesome CTF that you create in your GCP account.  Has a guided workbook with two attack and defense scenarios plus bonus challenges.

## Container
[Contained.af](https://contained.af/): A container escape challenge, break out of it and email the author.

## Terraform
[TerraGoat](https://github.com/bridgecrewio/terragoat): Vulnerable by design terraform repository.


## Research Labs

[PurpleCloud](https://www.purplecloud.network): Using python and terraform, build your own Azure security lab.

[SimulLand](https://github.com/Azure/SimuLand): Using Azure RM templates, create your own Azure security lab.


# Awesome Cloud Security Labs

A list of free cloud native security learning labs. Includes CTF, self-hosted workshops, guided vulnerability labs, and research labs.

## Sorted by Technology and Category


| Name        | Technology         | Category  |  Author  |  Notes  |
| :------------- |:-------------:| :-----:| :-----: | :------: |
| [CloudFoxable](https://github.com/BishopFox/cloudfoxable)    | AWS | Self-hosted CTF Challenge | [Seth Art](https://twitter.com/sethsec)  | Create your own vulnerable by design AWS penetration testing playground  |
| [Pwned Labs](https://pwnedlabs.io) | AWS | Author-hosted Guided Labs, CTF | [Ian Austin](https://www.linkedin.com/in/ian-austin-a42002156/) | Requires account registration; Commercial paid subscriptions; free hosted labs for learning cloud security |
| [The Big IAM Challenge](https://bigiamchallenge.com/)    | AWS | Author-hosted CTF Challenge | [Wiz](https://www.wiz.io)  | CTF challenge to identify and exploit IAM misconfigurations |
| [CloudSec Tidbits](https://github.com/doyensec/cloudsec-tidbits/) | AWS | Self-hosted Challenge | [Doyensec](https://doyensec.com/)  | Three web app security flaws specific to AWS cloud, self-hosted with terraform  |
| [Pentesting.Cloud](https://pentesting.cloud/)    | AWS | Self-hosted, Author-hosted CTF labs | [Nicholas Gilbert](https://www.linkedin.com/in/nicksecurity/)  | 17 free labs, requires registration, some labs are bring your own AWS account and use cloudformation to create |
| [AWS CIRT Workshop](https://aws.amazon.com/blogs/security/aws-cirt-announces-the-release-of-five-publicly-available-workshops/)    | AWS | Self-hosted, guided lab |  AWS CIRT | Build with Cloudformation, explore 5 common incident response scenarios observed by AWS CIRT |
| [CloudGoat](https://github.com/RhinoSecurityLabs/cloudgoat)    | AWS | Self-hosted, guided vulnerability lab |  Multiple, [Rhino Security Labs](https://rhinosecuritylabs.com/) | Python orchestration of terraform |
| [Attacking and Defending Serverless Applications](https://attack-defend-serverless.sanscloudwars.com/)    | AWS | Self-hosted, guided vulnerability workshop |  [Ryan Nicholson](https://twitter.com/ryananicholson) | Attack and defend a Lambda that you build in your own AWS account with author provided terraform |
| [IAM Vulnerable](https://github.com/BishopFox/iam-vulnerable)    | AWS | Self-hosted, guided vulnerability lab |  [Seth Art](https://twitter.com/sethsec) | IAM-focused priv esc playground with 31 pathways, create in your own AWS account using terraform, solid docs |
| [flaws.cloud](http://flaws.cloud)    | AWS | Author-hosted, CTF challenge |  [Scott Piper](https://twitter.com/0xdabbad00) | Challenge style with levels and clues |
| [flaws2.cloud](http://flaws2.cloud)    | AWS | Author-hosted, CTF challenge |  [Scott Piper](https://twitter.com/0xdabbad00) | Challenge style Attacker and Defender paths |
| [CI/CDon't](https://hackingthe.cloud/aws/capture_the_flag/cicdont/)    | AWS | Self-hosted CTF walkthrough |  [Nick Frichette](https://twitter.com/Frichette_n) | Host with terraform in your own AWS account, vulnerable CI/CD CTF infrastructure |
| [AWSGoat](http://https://github.com/ine-labs/AWSGoat)    | AWS | Self-hosted, attack and defense manuals |  Multiple, ine-labs | Bring your own aws account, Build with terraform, two modules, provides attack and defense  manuals  |
| [Sadcloud](https://github.com/nccgroup/sadcloud)    | AWS | Self-hosted |  Multiple, [NCC Group](https://www.nccgroup.com) | Terraform code; not guided like CloudGoat |
| [DVCA](https://github.com/m6a-UdS/dvca)    | AWS | Self-hosted demo lab | [Maxime Leblanc](https://medium.com/@mleblanc_82306) | Deploy a Damn Vulnerable Cloud Application in your own AWS account to practice privilege escalation  |
| [lambhack](https://github.com/wickett/lambhack)    | AWS | Self-hosted lab | [James Wickett](https://twitter.com/wickett) | Deploy a very vulnerable AWS lambda serverless application in your AWS account |
| [BadZure](https://github.com/mvelazc0/BadZure)    | Azure | Self-hosted lab |  [Mauricio Velazco](https://twitter.com/mvelazco) | Powershell Graph SDK script that spins up your own Azure AD (Entra ID) lab with attack paths.  Currently no walk through or guide. |
| [Broken Azure](https://www.brokenazure.cloud/)    | Azure | Author-hosted, CTF challenge |  [Secura](https://github.com/SecuraBV/brokenbydesign-azure) | Provides hints, optionally self-host in your own Azure account using terraform |
| [Mandiant Azure Workshop](https://github.com/mandiant/Azure_Workshop)    | Azure | Self-hosted, guided commands |  Multiple | Vulnerable by design Azure lab with two scenarios; build with terraform |
| [AzureGoat](https://github.com/ine-labs/AzureGoat)    | Azure | Self-hosted, attack and defense manuals |  Multiple, ine-labs | Bring your own Azure tenant, Build with terraform, one module, provides attack and defense  manuals |
| [XMGoat](https://github.com/XMCyber/XMGoat)    | Azure | Self-hosted, guided labs |  Multiple | Build with terraform, 5 scenarios, solution docs provided |
| [CONVEX](https://github.com/Azure/CONVEX)    | Azure | Self-hosted, CTF |  Multiple | Spin up three Capture the Flag environments in your Azure tenant using powershell |
| [GCP Goat (Josh Jebaraj)](https://gcpgoat.joshuajebaraj.com/index.html)    | GCP | Self-hosted, mdbook lab guide |  [Josh Jebaraj](https://joshuajebaraj.com/) | Host in your own GCP account, build with provided scripts, nice guided lab workbook |
| [GCPGoat (ine-labs)](https://github.com/ine-labs/GCPGoat)    | GCP | Self-hosted, attack and defense manuals|  Multiple, ine-labs | Bring your own GCP account, Build with terraform, one module, provides attack and defense manuals |
| [Thunder CTF](https://thunder-ctf.cloud/)    | GCP | Self-hosted, CTF|  Multiple | Bring your own GCP account, 6 levels, practice attacking vulnerable cloud projects on GCP |
| [K8s Lan Party](https://www.k8slanparty.com/)    | Kubernetes | Author hosted, CTF challenge|  [Wiz ](https:www.wiz.io) | To dive into a network full of misconfigurations and exploit vulnerabilities with the goal of conquering a Kubernetes cluster |
| [EKS Cluster Games](https://eksclustergames.com/)    | Kubernetes | Author hosted, CTF challenge|  [Wiz ](https:www.wiz.io) | Vulnerable EKS pod with flag challenges across environment, with leaderboard and requires registration |
| [Bustakube](https://www.bustakube.com/)    | Kubernetes | Self-hosted, import VMs|  [Jay Beale](https://twitter.com/jaybeale) | Vulnerable K8S cluster, Download the VMs to build cluster and import into VMWare, run it |
| [Kubernetes Goat](https://github.com/madhuakula/kubernetes-goat)    | Kubernetes | Self-hosted, multi-cloud, K3S|  [Madhu Akula](https://twitter.com/madhuakula) | Create and host in your own cloud account (GKE, EKS, AKS) or K3S and attack, has a guided workbook |
| [Kubecon NA 2019 CTF](https://securekubernetes.com/)    | Kubernetes | Self-hosted in GKE|  Multiple | Create GCP account, has a guided workbook with two attack and defense scenarios plus bonus challenges|
| [Kube Security Lab](https://github.com/raesene/kube_security_lab)    | Kubernetes | Local, kubernetes in docker|  [Rory McCune](https://twitter.com/raesene)  | An awesome local lab to create 14 vulnerable Kubernetes clusters using Docker, Ansible, and Kind.  Attack them after building, then destroy.  Includes walkthroughs.|
| [Container Security 101](https://jonzeolla.com/labs/container-security-101.html)    | Container | Self-hosted, guided workshop|  [Jon Zeolla](https://twitter.com/JonZeolla) | A guided vulnerability workshop, host in your AWS account, provided CloudFormation|
| [Contained.af](https://github.com/genuinetools/contained.af)    | Container | Self-hosted Challenge|  [Jessie Frazelle](https://twitter.com/jessfraz) | A container escape challenge, break out of it and email the author|
| [TerraGoat](https://github.com/bridgecrewio/terragoat)    | Terraform | Self-hosted multi-cloud (AWS, Azure, GCP)|  Multiple, [Bridgecrew](https://www.bridgecrew.io/) | Vulnerable by design terraform repository|
| [PurpleCloud](https://www.purplecloud.network)    | Azure | Research Lab |  [Jason Ostrom](https://twitter.com/securitypuck) | Using python and terraform, build your own Azure security lab|
| [SimuLand](https://github.com/Azure/SimuLand)    | Azure | Research Lab |  [Roberto Rodriguez](https://twitter.com/Cyb3rWard0g) | Using Azure RM templates, create your own Azure security lab|
| [CNAPPgoat](https://github.com/ermetic-research/cnappgoat)    | AWS, Azure, GCP | Research Lab | [Ermetic Research](https://ermetic.com/blog/cloud/cnappgoat-multicloud-open-source-tool-for-deploying-vulnerable-by-design-cloud-resources/) | Using Pulumi, modularly provision vulnerable-by-design components in AWS, GCP, Azure|
| [CI/CD Goat](https://github.com/cider-security-research/cicd-goat)    | CI/CD | CTF, local docker |  [Palo Alto](https://www.paloaltonetworks.com/prisma/cloud/cloud-code-security) | Deliberately vulnerable CI/CD environment, hacking CI/CD pipelines with CTF.  Host locally with docker.|
| [Github Actions Goat](https://github.com/step-security/github-actions-goat)    | CI/CD | Self-hosted Github |  [StepSecurity](https://www.stepsecurity.io/) |  Deliberately vulnerable Github Actions CI/CD environment, hosted in your own Github account.  Includes threat scenario descriptions mapped to vulnerabilities.|


## AWS

[CloudFoxable](https://github.com/BishopFox/cloudfoxable): Create your own vulnerable by design AWS penetration testing playground.

[Pwned Labs](https://pwnedlabs.io):  Requires a login.  Offers paid subscriptions.  Free hosted labs for learning cloud security.

[The Big IAM Challenge](https://bigiamchallenge.com/): CTF challenge to identify and exploit IAM misconfigurations.

[CloudSec Tidbits](https://github.com/doyensec/cloudsec-tidbits/):  Three web app security flaws specific to AWS cloud, self-hosted with terraform.

[Pentesting.Cloud](https://pentesting.cloud):  17 free labs.  Requires site registration.

[AWS CIRT Workshop](https://aws.amazon.com/blogs/security/aws-cirt-announces-the-release-of-five-publicly-available-workshops/):  Build in your own AWS account and explore 5 common incident response scenarios as seen by the AWS CIRT team.

[CloudGoat](https://github.com/RhinoSecurityLabs/cloudgoat):  Vulnerable by design AWS security labs with guided walkthrough.

[Attacking and Defending Serverless Applications](https://attack-defend-serverless.sanscloudwars.com/):  Attack and defend a Lambda that you build in your own AWS account with author provided terraform and scripts.  Very educational with workshop style feel.

[IAM Vulnerable](https://github.com/BishopFox/iam-vulnerable): Use Terraform to create your own vulnerable by design AWS IAM privilege escalation playground with 31 privilege escalation attack pathways.  Very solid documentation.

[flaws.cloud](http://flaws.cloud):  Challenge style with levels and clues.

[flaws2.cloud](http://flaws2.cloud):  Challenge style with both Attacker and Defender paths.

[CI/CDon't](https://hackingthe.cloud/aws/capture_the_flag/cicdont/):  A vulnerable CI/CD CTF challenge hosted in your aws account with terraform.  Includes a walkthrough.

[AWSGoat](http://https://github.com/ine-labs/AWSGoat): A damn vulnerable AWS infrastructure with two attack and defense manuals.

[Sadcloud](https://github.com/nccgroup/sadcloud): Create vulnerable AWS services without a guide showing vulnerabilities.

[DVCA](https://github.com/m6a-UdS/dvca): Deploy a Damn Vulnerable Cloud Application in your own AWS account to practice privilege escalation.

[lambhack](https://github.com/wickett/lambhack): Deploy a very vulnerable AWS lambda serverless application in your AWS account.


## Azure

[BadZure](https://github.com/mvelazc0/BadZure): Powershell Graph SDK script that spins up your own Azure AD (Entra ID) lab with attack paths.  Currently no walk through or guide.

[Broken Azure](https://www.brokenazure.cloud/):  A vulnerable by design Azure infrastructure that you can attack.

[Mandiant Azure Workshop](https://github.com/mandiant/Azure_Workshop): Vulnerable by design Azure lab with two scenarios that you build in your own Azure tenant.

[AzureGoat](https://github.com/ine-labs/AzureGoat): Build one module with terraform and walk through the provided attack and defense manuals.

[XMGoat](https://github.com/XMCyber/XMGoat):  Build 5 scenarios in your Azure tenant and walk through solution docs provided.

[CONVEX](https://github.com/Azure/CONVEX):  Spin up three Capture the Flag environments in your Azure tenant using powershell.

## GCP

[GCP Goat (Josh Jebaraj)](https://gcpgoat.joshuajebaraj.com/index.html): Host in your own GCP account and build with provided scripts.  It has a nice guided lab workbook.

[GCPGoat (ine-labs)](https://github.com/ine-labs/GCPGoat): Bring your own GCP account and build one module with terraform.  Provides attack and defense manuals.

[Thunder CTF](https://thunder-ctf.cloud/): Bring your own GCP account, 6 levels, practice attacking vulnerable cloud projects on GCP.

## Kubernetes

[K8s Lan Party](https://www.k8slanparty.com/): To dive into a network full of misconfigurations and exploit vulnerabilities with the goal of conquering a Kubernetes cluster, with leaderboard and requires registration.

[EKS Cluster Games](https://eksclustergames.com/):  Vulnerable EKS pod with flag challenges across environment, with leaderboard and requires registration.

[Bustakube](https://www.bustakube.com/):  Download a vulnerable K8S cluster as VMs that you can import and run locally in VMWare.

[Kubernetes Goat](https://github.com/madhuakula/kubernetes-goat): Create and host in your own cloud account (GKE, EKS, AKS) or K3S and attack.  Includes a guided workbook.

[Kubecon NA 2019 CTF](https://securekubernetes.com/):  Awesome CTF that you create in your GCP account.  Has a guided workbook with two attack and defense scenarios plus bonus challenges.

[Kube Security Lab](https://github.com/raesene/kube_security_lab): An awesome local lab to create 14 vulnerable Kubernetes clusters using Docker, Ansible, and Kind.  Attack them after building, then destroy.  Inludes walkthroughs.

## Container

[Container Security 101](https://jonzeolla.com/labs/container-security-101.html):  A guided vulnerability workshop that is hosted in your AWS account.  Author has provided a nice lab you follow on the webpage and you build a VM with CloudFormation and then create a container.

[Contained.af](https://github.com/genuinetools/contained.af): A container escape challenge, break out of it and email the author.

## Terraform

[TerraGoat](https://github.com/bridgecrewio/terragoat): Vulnerable by design terraform repository.


## Research Labs

[PurpleCloud](https://www.purplecloud.network): Using python and terraform, build your own Azure security lab.

[SimuLand](https://github.com/Azure/SimuLand): Using Azure RM templates, create your own Azure security lab.

[CNAPPgoat](https://github.com/ermetic-research/cnappgoat):  Using Pulumi, modularly provision vulnerable-by-design components in AWS, GCP, Azure.  The vulnerabilities are modular scenarios with no guided walkthrough existing yet.

## CI/CD

[CI/CD Goat](https://github.com/cider-security-research/cicd-goat):  Deliberately vulnerable CI/CD environment, hacking CI/CD pipelines with CTF.  Host locally with docker.

[Github Actions Goat](https://github.com/step-security/github-actions-goat):  Deliberately vulnerable Github Actions CI/CD environment, hosted in your own Github account.  Includes threat scenario descriptions mapped to vulnerabilities.

<h1 align="center">Hi 👋, I'm Emad Adel</h1>
<h3 align="center">Cloud Solution Architect</h3>

<p align="left"> <a href="https://twitter.com/emadadel2008" target="blank"><img src="https://img.shields.io/twitter/follow/emadadel2008?logo=twitter&style=for-the-badge" alt="emadadel2008" /></a> </p>

- 📫 How to reach me **me@emadadel.com**

### Blogs posts
<!-- BLOG-POST-LIST:START -->
<!-- BLOG-POST-LIST:END -->

<h3 align="left">Connect with me:</h3>
<p align="left">
<a href="https://twitter.com/emadadel2008" target="blank"><img align="center" src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/twitter.svg" alt="emadadel2008" height="30" width="40" /></a>
<a href="https://linkedin.com/in/emadadel" target="blank"><img align="center" src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/linked-in-alt.svg" alt="emadadel" height="30" width="40" /></a>
<a href="https://fb.com/emadadel87" target="blank"><img align="center" src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/facebook.svg" alt="emadadel87" height="30" width="40" /></a>
<a href="https://www.youtube.com/c/emadadel2008" target="blank"><img align="center" src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/youtube.svg" alt="emadadel2008" height="30" width="40" /></a>
<a href="/https://www.emadadel.com//feeds/posts/default" target="blank"><img align="center" src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/rss.svg" alt="https://www.emadadel.com//feeds/posts/default" height="30" width="40" /></a>
</p>

# Line-of-business application migration

Fabrikam Fabrics is a major manufacturer and distributor of clothing and soft furnishing materials. The CTO, James Lynch, was hired 6 months ago with a mandate to address ever-increasing IT costs. He has identified a sprawling IT estate, including a substantial legacy server footprint with 448 servers and VMs identified to date. There is a complex web of dependencies between servers and no-one has a clear view of the entire estate.

The board has approved a plan to migrate as much existing infrastructure as possible to Azure, to eliminate IT infrastructure overheads and 'clean house'. Your team has been tasked with planning and executing this migration.

February 2022

## Target audience

This workshop is applicable to any technical role with a responsibility or involvement in Azure migration
- IT Professional
- Database Engineer
- Application Developer or DevOps Engineer
- Cloud Solution Architect

## Abstracts

### Workshop

In this workshop, you will learn how to design a migration strategy for on-premises environments to Azure, including the migration of virtual and physical services as well as databases.

At the end of this workshop you will be better able to rationalize the migration of various workloads to Microsoft Azure as well as understanding how to determine the cost of hosting migrated workloads in Azure. 

### Whiteboard design session

In this whiteboard design session, you will look at how to design an Azure migration for a heterogenous customer environment. The existing infrastructure comprises both Windows and Linux servers running on both VMWare and physical machines, and includes some legacy servers. Throughout the whiteboard design session, you will look at the various options and services available to migrate heterogenous environments to Azure.

At the end of this workshop, you will be better able to design and implement the discovery and assessment of environments to evaluate their readiness for migrating to Azure using services including Azure Migrate and Azure Database Migration Service.

Continue to the [Whiteboard design session](https://github.com/microsoft/MCW-Line-of-business-application-migration/tree/master/Whiteboard%20design%20session) documents folder.

### Hands-on lab

In this hands-on lab, you will learn how to assess and migrate a multi-tier application from Hyper-V to Azure. You will learn how to use Azure Migrate as the hub for executing a migration, together with accompanying tools.

After this hands-on lab, you will know the role of Azure Migrate and related migration tools and how to use them to successfully migrate an on-premises multi-tier application to Azure.

Continue to the [Hands-on lab](https://github.com/microsoft/MCW-Line-of-business-application-migration/tree/master/Hands-on%20lab) documents folder.

## Azure services and related products

- Azure Migrate
- Azure Site Recovery
- Azure Database Migration Service
- Microsoft Data Migration Assistant

## Related references

- [MCW](https://microsoftcloudworkshop.com)
- [Azure Migration Center](https://azure.microsoft.com/migration)
- [Azure Database Migration Guide](https://aka.ms/datamigration)
## Resource Links
- [Azure Migrate Overview](https://learn.microsoft.com/en-us/azure/migrate/migrate-services-overview)
- [Support matrix for physical server discovery and assessment](https://learn.microsoft.com/en-us/azure/migrate/migrate-support-matrix-physical#physical-server-requirements)
- [Metadata discovered by Azure Migrate appliance](https://learn.microsoft.com/en-us/azure/migrate/discovered-metadata#software-inventory-data)
-  Azure Migrate Tools
- - [Azure Migrate: Database Assessment](https://learn.microsoft.com/en-us/sql/dma/dma-overview?view=sql-server-2017)
- - [Azure Migrate: Web App Assessment](https://www.microsoft.com/en-us/download/details.aspx?id=53595)
## Help & Support

We welcome feedback and comments from Microsoft SMEs & learning partners who deliver MCWs.  

***Having trouble?***
- First, verify you have followed all written lab instructions (including the Before the Hands-on lab document).
## How to reset Azure Migrate Appliance

![Alt text](https://example.com/path/to/image.png).

in public cloud
Azure Migrate appliance is a simple tool to move VMware virtual machines to Azure. But it has limitation to migrate VMs on multiple vCenter servers. In other words, you have to deploy multiple appliances to support multi-vCenter. This is a time-consuming task. In fact, there is a way to reset the Azure Migrate Appliance.

There is a file appliance.json in Azure Migrate appliance. It stores the key information of the Azure Migrate project. The credentials, vCenter server, and key vault information are all stored in the file. Also the registration status.

The file is located in C:\ProgramData\Microsoft Azure\Config\. It’s a JSON file. The variable IsApplianceRegistered indicates if the appliance registered or not.

Change the value from True to False will reset Azure Migrate appliance status. Of course, you still need to reboot the appliance.

This reset is no impact to stored credential and vCenter server data.
- Next, submit an issue with a detailed description of the problem.
- Do not submit pull requests. Our content authors will make all changes and submit pull requests for approval.  

If you are planning to present a workshop, *review and test the materials early*! We recommend at least two weeks prior.



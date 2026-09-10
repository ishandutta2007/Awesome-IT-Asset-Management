# Awesome-IT-Asset-Management

## Top IT Asset Management (ITAM) Platforms Ecosystem

**Curated List of SaaS Products & Open-Source GitHub Projects**

*Focused on Hardware & Software Inventory, Discovery, License Management, Lifecycle Tracking & CMDB Integration*

**Last updated: September 2026**



This repository tracks notable **SaaS platforms** and **open-source projects** for **IT Asset Management (ITAM)**. These systems discover, inventory, track, and optimize hardware, software, and cloud assets across their lifecycle — supporting compliance, cost control, and operational visibility.



**Examples** include Flexera, Snow Software, Device42, Asset Panda, ManageEngine AssetExplorer, InvGate, Freshservice, SysAid, ServiceNow ITAM, and Lansweeper (the category leaders).



**Open-source emphasis**: ITAM has a mature open-source ecosystem. **Snipe-IT**, **GLPI**, **OCS Inventory NG**, **Ralph**, and related projects provide production-ready asset tracking, discovery, and license management. This section is heavily expanded with these tools.



Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.



## Table of Contents

- [SaaS/Hosted Platforms](#saashosted-platforms)

- [Open-Source GitHub Projects](#open-source-github-projects)

- [How to Contribute](#how-to-contribute)

- [Disclaimer](#disclaimer)



## SaaS/Hosted Platforms

| Platform | Description | Starting Pricing | Free Tier / Trial Limits |
| :--- | :--- | :--- | :--- |
| **[Flexera](https://www.flexera.com/)** | Enterprise ITAM and technology intelligence platform covering SAM, hardware, cloud spend, and license optimization. | ~$2,500/month (Annual plans start at ~$30,000–$50,000/year based on spend under management) | 14-day free trial (available for select modules like Flexera One Select; custom PoC on request; no permanent free tier) |
| **[Snow Software](https://www.snowsoftware.com/)** | Specialized SAM and ITAM platform (part of Flexera) with deep software recognition libraries and compliance audits. | ~$1,200/month (Base tiers start at ~$14,400/year or ~$2.50–$5.00/device/year in volume) | 30-day proof-of-concept (PoC) evaluation via sales; 14-day trial for Snow Commander (no permanent free tier) |
| **[Device42](https://www.device42.com/)** | Discovery-driven ITAM and CMDB platform strong in data-center, hybrid infrastructure, and dependency mapping. | $120/month ($1,449/year starting tier for up to 100 devices; ~$20–$25/device/year) | 14-day free trial (up to 100 devices scanned, no credit card required; no permanent free tier) |
| **[Asset Panda](https://www.assetpanda.com/)** | Flexible, cloud-based asset tracking platform with customizable workflows across IT and fixed physical assets. | $125/month (Starts at $1,500/year for up to 250 assets with unlimited users) | 14-day free trial (full access to core tracking features, no credit card required; no permanent free tier) |
| **[ManageEngine AssetExplorer](https://www.manageengine.com/products/asset-explorer/)** | Comprehensive ITAM tool covering auto-discovery, software license compliance, and CMDB integration. | $955/year (On-premises, 250 assets) or $115/month ($1,245/year Cloud, 250 assets) | Free forever plan (up to 25 nodes on-premises / 50 nodes cloud); 30-day free trial (up to 250 nodes) |
| **[InvGate](https://invgate.com/)** | ITAM (InvGate Insight) and ITSM platform focused on asset visibility, network discovery, and change tracking. | $0.21/node/month (Insight ITAM, billed annually) or $17/agent/month ($1,499/year for up to 5 Service Desk agents) | 30-day free trial (full access to network discovery and asset inventory features; no permanent free tier) |
| **[Freshservice](https://www.freshworks.com/freshservice/)** | IT service and asset management platform with automated discovery, contract management, and CMDB integration. | $19/agent/month (Starter tier, billed annually) or $29/agent/month (billed monthly) | 14-day free trial (full access to ITSM/ITAM features, up to 100 asset units, no credit card required; no permanent free tier) |
| **[SysAid](https://www.sysaid.com/)** | ITSM platform including comprehensive IT asset management, network discovery, and AI-driven service desk workflows. | $89/agent/month (Professional tier, billed annually, includes up to 250 assets) | 14-day free trial (access to asset management and service automation; no permanent free tier) |
| **[ServiceNow ITAM](https://www.servicenow.com/products/it-asset-management.html)** | Enterprise hardware and software asset management natively integrated with the ServiceNow CMDB ecosystem. | ~$100/user/month (Estimated fulfiller seat starting tier; annual enterprise commitments typically start at $10,000+) | Free Personal Developer Instance (PDI with full sandbox ITAM/SAM access for non-production use); 30-day enterprise guided PoC |
| **[Lansweeper](https://www.lansweeper.com/)** | Network discovery and IT asset intelligence platform known for agentless scanning and deep hardware/software inventory. | $239/month ($2,868/year Starter plan for up to 2,000 assets, unlimited users) | Free forever plan (up to 100 assets scanned, limited features); 14-day free trial (unlimited assets with full features) |



## Open-Source GitHub Projects

- **[Snipe-IT](https://github.com/grokability/snipe-it)**  

  Leading open-source IT asset and license management system (AGPL) — track hardware, software licenses, consumables, check-in/check-out, and custom fields. Mature, actively maintained, and widely deployed.



- **[GLPI](https://github.com/glpi-project/glpi)**  

  Comprehensive open-source ITSM + ITAM platform (GPL) combining asset inventory, CMDB, ticketing, and help-desk features in one system.



- **[OCS Inventory NG](https://github.com/OCSInventory-NG)**  

  Open-source agent-based hardware and software inventory / discovery solution that feeds detailed asset data into GLPI or other systems.



- **[Ralph](https://github.com/allegro/ralph)**  

  Open-source asset management and DCIM-oriented platform (Apache 2.0) strong for data-center and infrastructure tracking.



- **[iTop](https://github.com/Combodo/iTop)**  

  Open-source CMDB and ITSM tool with solid configuration and asset management capabilities.



- **[FusionInventory](https://github.com/fusioninventory)**  

  Open inventory and discovery agents commonly paired with GLPI for automated network and endpoint scanning.



- **[NetBox](https://github.com/netbox-community/netbox)**  

  Open-source infrastructure resource modeling tool often used alongside or as a foundation for network and data-center asset tracking.



- **[Open-source barcode / label and checkout extensions](https://github.com/)**  

  Community modules that add scanning, labeling, and reservation workflows to Snipe-IT and similar systems.



- **[Custom discovery + CMDB pipelines](https://github.com/)**  

  Scripts and agents that push inventory data from networks, cloud APIs, and endpoints into open asset databases.



- **[License compliance open calculators and reports](https://github.com/)**  

  Tools that help reconcile installed software against purchased entitlements using open inventory data.



### Additional Strong Open-Source Options

- Starting with **Snipe-IT** for clean, focused hardware and license tracking with an excellent user experience.

- Choosing **GLPI + OCS/FusionInventory** when you want assets, CMDB, and a full service desk in one open stack.

- Using **Ralph** or **NetBox** for data-center and infrastructure-centric environments.

- Combining open discovery agents with any asset database for continuous inventory accuracy.

- Accepting that deep software recognition libraries, advanced SaaS/cloud license optimization, and large-scale enterprise SAM still favor commercial platforms (Flexera, Snow, ServiceNow, etc.).



**Frameworks for building custom systems**: Deploy Snipe-IT or GLPI → add automated discovery with OCS Inventory or network scanners → track licenses and assignments → integrate with ticketing or CMDB → report on compliance and lifecycle. This stack is fully open and production-proven for many organizations. Commercial platforms (Flexera, Snow, Device42, Lansweeper, ServiceNow ITAM, ManageEngine, etc.) remain the practical choice when you need sophisticated software recognition, cloud cost governance, or tight enterprise ITSM integration at scale.



## How to Contribute

1. Fork the repo.

2. Add/edit entries in `README.md` (follow existing format).

3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.

4. Submit PR with a short explanation.



Star the repo if you find it useful!



## Disclaimer

- This is a **community-curated** list — not exhaustive and not an endorsement.

- IT asset data underpins security, compliance, financial reporting, and audit readiness. Inaccurate inventories can lead to license penalties, security gaps, or poor decision-making. Self-hosted open-source deployments require proper access control, backups, and regular updates. Always validate discovery coverage and reconcile against procurement records. This list is not compliance, licensing, or audit advice.



---

**Made for IT operations, asset managers, and FinOps teams who need accurate visibility into every asset.**

Let's keep inventory complete, licenses under control, and the tooling as open as practical.

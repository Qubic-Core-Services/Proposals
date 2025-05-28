# **Ecosystem Services \- Grants & Incubation New Governance Model Proposal**

* Option 0: No, don't approve  
* Option 1: Yes, approve the new Grants & Incubation New Governance Model

## **1-Introduction**

The Grants and Incubation Funds are two key initiatives designed to foster development within the Qubic ecosystem, each with a distinct focus and funding origin:

* The Grants Program was funded through a 100 billion QUBIC donation, and its objective is to support the development of open-source tools and utilities that provide clear benefits to the ecosystem but are difficult to commercialize. These typically include infrastructure, libraries, documentation, and other public goods. The grants are paid out in milestones, and progress is monitored directly by the Ecosystem Services team. An overview of expenses and allocations can be found [here](https://docs.google.com/spreadsheets/d/1zvda8WZzVljbu6LKMxdTnNlt2Fj5T65xlH6FSOvO33k/edit?gid=0#gid=0)  
* The Incubation Fund, in contrast, is backed by ecosystem funds donated by the Arbitrator. Its purpose is to provide initial capital to commercially viable projects that need help launching. These projects are required to present a clear business plan and show commercial potential. Like the grants, funding is distributed in milestones and is closely monitored by the Ecosystem Services team. Details on the usage of these funds are available here [here](https://docs.google.com/spreadsheets/d/1ncuM_LT8HFMuD5D7FXHGrXITACNgD2W17FZqxygz58A/edit?pli=1&gid=0#gid=0)

To ensure transparent and informed decisions, the Grants Committee was established. Its responsibilities include approving grant proposals, conducting first-round approvals of incubation applications, and participating in dispute resolution when needed.

## **2-Rationale**

This proposal aims to restructure the current governance model used for evaluating Projects, the Grants Committee. Some of the challenges we are facing:

* Low participation: Since the start of 2025, the Grants Committee has demonstrated a very low level of engagement, missing meetings and polls, which represents a severe bottleneck in project onboardings and execution. On average, only 50% of Grants Committee members voted in the last polls since 2025\.  
* Opacity: Current Grant Committee decisions are invisible to computors and the broader community, eroding trust.  
* Long-term vision misalignment: The Ecosystem Services team’s long-term vision for project development lacks alignment with the Committee. Currently, it is not clear what the technical priorities are, or how the Incubation Funds should be allocated strategically.

## **2- Proposal**

Dissolve the grants committee and move approvals to a public voting process, where the community represents a major part of the final decision being:

* 50% Community weighted vote  
* 20% Core-tech unified vote  
* 20% Ecosystem unified vote  
* 10% Marketing\&Operations unified vote

**Weighted vote:** Every community member is allowed to vote their preferred choice once, meaning the votes are not aggregated in a single decision. Final results will be weighted as mentioned above. This approach prevents the dilution of minorities’ decisions, allowing everyone certain voting power in the final result.

**Unified vote:** Every workgroup vote will represent the agreed decision of all its members, which means every workgroup votes one time (which weight is mentioned above). This approach aims at creating consensus internally, given workgroups act as one team, not individual representatives.

Threshold is fixed at 51% for a proposal to be accepted within Grants & Incubation programs

We propose that the community participates via a voting system based on wallet holdings. The higher a wallet is funded with QUBIC, the more weight it has in the voting process.

The Ecosystem Services team is currently developing a decentralized application (dApp) to coordinate on-chain voting based on wallet holdings. The main goal is to enable the community to vote using Qubic tokens (not just Qubic — e.g., MSVault, QX, etc.). We are currently evaluating whether using locked funds in Qearn can be used for voting

The way it works is simple: one of the existing SC like Qutil, will be upgraded to include voting functionality. Proposals will be created and published regularly, and voting periods will typically last one week, usually closing at the end of each epoch (for example, from Wednesday to Wednesday).

Voting can be done either via CLI or through a web interface we’re building. Just like how miners currently vote on CCF, any holder of Qubic will be able to cast their vote as “Yes,” “No,”. For now, all official votes regarding ecosystem development will be conducted in Qubic.

We are finalizing the rules around how proposals are submitted and approved, as we don’t want to become gatekeepers, instead we will take on a more prominent role as facilitators of growth in the areas that both the community and the workgroups identify as most needed (for example, derivative DEXs, bridges, AI computing power, SSI, DeFi,..) Our plan is to open this up so that any team can submit a proposal for funding. However, disbursement of funds will always be tied to milestone completion. No funding will be released unless clear deliverables have been met. Future versions of the app may include additional features such as the ability to comment on proposals or submit feedback, but for now, the focus is on getting a clean and usable voting system live.

We expect the first version of the voting app to be launched by June 2025\. The votes will be published online in the dApp itself, and we will also announce the results on Discord.

The development of the dApp is not part of this proposal decision. This proposal is only focused on the governance model, regardless of the tool we finally use to execute this plan.

This dApp does not require funding given it was already included in the past approved proposal [Ecosystem Services May \- June 2025 funding CCF proposal](https://github.com/Qubic-Core-Services/Proposals/blob/0609a7e178e4e744f1cd19354e0d54d3175dffde/Qubic%20Ecosystem%20Services%20CCF%20proposal%20\(May-%20June2025\).md)

The end-to-end process will be:

* Ecosystem Services will keep working as the first filter, analyzing and evaluating whether a project is subject for Grants\&Incubation programs (i.e. it is aligned with the roadmap, the proposal is mature enough, etc)  
* (New) Once the Ecosystem Services team proposes a project, the Community will decide whether to fund it or not using the dApp. This will represent 50% of the final decision.  
* Finally, the workgroups will also vote the proposal (via poll) to get the final result  
* Ecosystem Services team will onboard and work with the development team to accomplish the delivery plan (milestones). This includes the creation of a public channel per project where devs and Ecosystem Services will regularly update the community  
* Payments (Treasurer stays the same) will be made upon QA (Ecosystem Services team)

The new governance structure doesn't impact relation/account management of existing projects.

Example: Assume there is a proposal with voting options A, B and C. If the voting process goes as in the table below, the chosen option would be B 

|  | Voting share | Step 1  |  |  | Step 2 |  |  | Final result |  |  |
| ----- | ----- | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: |
|  |  | Opt. A | Opt. B | Opt. C | Opt. A | Opt. B | Opt. C | Opt. A | Opt. B | Opt. C |
| Community | 50% | 50% | 30% | 20% | 50% | 30% | 20% | 50\*0,5+100\*0,1 \= **35** | 30\*0,5+100\*0,2+100\*0,2= **55**  | 20\*0,5 \= **10** |
| Core-tech | 20% |  |  |  |  | 100% |  |  |  |  |
| Ecosystem | 20% |  |  |  |  | 100% |  |  |  |  |
| Marketing | 10% |  |  |  | 100% |  |  |  |  |  |

## **3- Deliverables and KPIs**

Ecosystem Services team commits to replace the Grants Committee with the Community (proposed dApp or other) in the evaluation process of Incubation Projects. We will closely track community engagement metrics, broken down into overall participation and the voting weight in decision-making processes.

## **4- Proposed Ecosystem budget detail (USD)**

No budget is needed for this proposal as the costs were included in the [Ecosystem Services May \- June 2025 funding CCF proposal](https://github.com/Qubic-Core-Services/Proposals/blob/0609a7e178e4e744f1cd19354e0d54d3175dffde/Qubic%20Ecosystem%20Services%20CCF%20proposal%20\(May-%20June2025\).md)


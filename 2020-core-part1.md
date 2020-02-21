---
language: en
layout: worker
type: budget
category: Core Development
bfid: 2020-bitshares-core-part1
workerid: 
title: BitShares Core Development 2020 (part 1/2)
name: Milos Preocanin
company:
 name:
 url:
status: 
discussions:
 - name:
   url: 
 - name: 
   url: 
price: 8,493,810 BTS
duration: 6 months
Start: 2020/02/29
End: 2020/08/28
paymentaccount: 
---

Background
==========

Throughout 2019, there was very low activity within the BitShares ecosystem, which led to extreme depreciation of the BTS token price.    In order to cut losses to the reserve pool, shareholders voted to halt all ongoing blockchain development, in late 2019.   The purpose of this deferment was, ostensively, to await a more value conscious developer proposal to be put forth by the community.    BitShares-Core is the primary software which underpins the BitShares protocol.  Therefore, it is a priority to tighten the budget, while keeping seasoned, competent developers on the Core team, wherever possible.  The ultimate aim is to provide the vital elements of Core development at a lower cost.  

Worker Intent
==========

The intent of this worker is to provide funding for development, testing, and deployment of clearly defined BitShares Improvement Proposals (BSIPs) along with maintenance, improvements and releases. Our expectation is to complete development of the targeted BSIPs within 6 months and at significant cost-reduction to the previous Core development worker. Upon completion of each BSIP, the worker provides for funding to update corresponding documentation. This will include changes to User, Dev, GitHub, and Wiki documentation.    To keep our commitments, and provide consistency in the quality of code and other deliverables, this worker will be treated as a corporate agreement with the blockchain. As such, it will be fully performed and executed by specific individuals (freelancers) working as a team. This core worker will not outsource work to 3rd party contractors or offer bounties.


Detailed Roadmap and Estimates
==============================

- Bug fixing, review, re-testing and release of BitShares Mainnet 4.0 (60-80 hours)
- Development for [BSIP 62: Close short position](https://github.com/bitshares/bsips/blob/master/bsip-0062.md) (up to 115 hours)
- Development for [BSIP 64: Operational HTLC preimage length, HASH160 addition, and memo field](https://github.com/bitshares/bsips/blob/master/bsip-0064.md) (up to 12 hours)
- Development for [BSIP 69: Additional Assert Predicates](https://github.com/bitshares/bsips/blob/master/bsip-0069.md) (up to 25 hours)
- Development for [BSIP 70: P2P Lending](https://github.com/bitshares/bsips/blob/master/bsip-0070.md) (up to 400 hours)
- Development for [BSIP 73: Match Force-Settlement Orders with Margin Calls and Limit Orders](https://github.com/bitshares/bsips/blob/master/bsip-0073.md) (up to 280 hours)
- Development for [BSIP 74: Margin Call Fee Ratio](https://github.com/bitshares/bsips/blob/master/bsip-0074.md) (up to 60 hours)
- Development for [BSIP 77: Require Higher CR When Creating/Adjusting Debt Positions](https://github.com/bitshares/bsips/blob/master/bsip-0077.md) (up to 80 hours)
- Development for [BSIP 80: Short-term memberships](https://github.com/bitshares/bsips/blob/8deb9aa98af5a9b8cbd692da6b7d93f8a1f36a55/bsip-0080.md) (up to 225 hours)
- Development for [BSIP 81: Simple Maker-Taker Market Fees](https://github.com/bitshares/bsips/blob/master/bsip-0081.md) (up to 100 hours)
- Development for [BSIP 85: Maker Order Creation Fee Discount](https://github.com/bitshares/bsips/blob/master/bsip-0085.md) (up to 100 hours)
- Development for [BSIP 86: Share market fee to the network](https://github.com/bitshares/bsips/blob/master/bsip-0086.md) (up to 60 hours)
- Final Development for NanoLedger BTS Integration and testing (up to 30 hours)
- Legal submission for official NanoLedger listing (legal representative estimate)
- Bug fixes and Maintenance (Revisions up to 400 hours)
- Testnet Deployment and Testing (up to 300 hours)
- Documentation (BSIP, User and Dev) and GitHub/Wiki maintenance and updates (up to 600 hours for entire team)
- Collaboration with UI Team and bitshares.org on synchronized releases/updates without long delays (up to 50 hours)
*(The desired situation would be BSIP 70: P2P lending released in the Staging UI, with testnet core release.  This would be available for testing through the testnet API and linted.  Additionally it would be launched on Wallet UI, along with the mainnet core release)*
- 5.0 Mainnet Release (up to 10-20 hours via automation)

BitShares Core Team Members, Roles and Budgeted Effort
======================================================
BitShares Core Team constitutes a small, dedicated, and seasoned group of professionals.  These are highly-skilled engineers, some with doctorate level education in the programming and logic design industry.  As such, they are prized assets of the BitShares community who should be retained.   Understanding the aforementioned devalued state of the chain, these committed members of the BitShares community are prepared to accept substantially lower hourly rates than previously contracted.  


 **Table 1. BitShares Core Team Positions, Availability and Rates (Weekly)**

| Roles (described below)           | Rate (USD)| (BTS) Value @ $0.03 USD | Team Member             | Available Hours   |
|:--------------------------------- | ---------:|:----------------------- |:----------------------- |:----------------- |
| Worker Manager                    | $40/hour  | 1333 BTS                | Milos Preocanin         | 20 hours weekly   |
| Documentation specialist          | $40/hour  | 1333 BTS                | ---------------         | 20 hours weekly   |
| Audit/Senior Core Developer       | $80/hour  | 2667 BTS                | Abit More               | 20 hours weekly   |
| Senior Core Developer             | $80/hour  | 2667 BTS                | Christopher Sanborn     | 20 hours weekly   |
| Senior Core Developer             | $80/hour  | 2667 BTS                | John Jones              | 30 hours weekly   |
| Senior Core Developer/BA          | $80/hour  | 2667 BTS                | Michel Santos           | 30 hours weekly   |
| ZHS Translation specialist        | $40/hour  | 1333 BTS                | Linda Tian              |  5 hours weekly   |

Total max. team hours available: **3770 hours** *(Manager 520, Doc Spec 520, Audit/Core 520, Core Devs 520 + 780 + 780, Translations 130)*

Total max. project estimate: **~3000 hours** *(without safety buffer 15% and potential issues with final releases/production)*

New Schedule for Releases
===================

As two main consensus affecting releases per year are too much to be expected from a small-sized team and worker duration of just 26 weeks, we propose to instead introduce:  
- 1 Testnet Release (aim: 15th of July) `test-5.0.0`
*requires consensus update*
- 1 Mainnet Release (aim: 10th of August) `5.0.0`
*requires consensus update*
- Additional revisions of sub-releases and new builds through maintenance.
*not require consensus update* 

Disclaimer: the format legend `5.0.0` means `release(5).sub-release(0).build(0)`. Hence, `Build` cannot be planned or scheduled given that random bug fixes and necessary changes to the code may be found or discovered upon actual production.  This applies to both testnet and mainnet.  

**Team Roles and Rates**

| Roles (described below)         | Rate (USD) | 
|:------------------------------- | :---------:|
| Manager                         |  $40/hour  | 
| Senior Core Developer           |  $80/hour  | 
| Quality Assurance Auditor       |  $80/hour  | 
| Documentation Specialist        |  $40/hour  | 
| ZHS Translation specialist      |  $40/hour  |


**Hardcap definition:**
This Worker reintroduces payouts in BTS, instead of fiat equivalent BitAssets. As such, in the case of appreciation in value of the BTS token over time, this worker will cap employee pay at the value of 0.05 USD per 1 BTS token. The worker begins at lower core rate for hours in concessions to the depreciation of the BTS token value.  BTS payouts are considered fixed (per table 1) as long as the price is <0.05 USD per 1 BTS token. In case of the price >0.05 USD, amount of BTS used for payout will be capped such that:  Maximum USD = BTS fixed rates defined in this worker * 0.05.  

Terms of Worker/Agreement
==================

1) Team hour reports and code audit will be done once every 3 weeks. A single collective team invoice will be issued by the Worker Manager (Milos Preocanin) with previous approval by the Audit Manager (Abit More).

2) This worker max budget is calculated by the max amount of hours available by each team member. All unspent BTS core token will be returned to the reserves.

3) Milos Preocanin will be held as the principal responsible contact for this worker, on behalf of “Zavod Premik”.

4) Hourly estimates, given by the developers for the pre-defined list of BSIP's to be delivered, have ~15% additional buffer to be distributed by the worker manager. In this manner, both developers and shareholders are protected in terms of deliveries by providing additional budget, if needed, for any unexpected events.

5) “Zavod Premik” will uphold this agreement with the BitShares Blockchain for 6 months, providing warranty on the declared structure and intent as being consistent to its purpose and fully transparent to the BTS token holders and BitShares Ecosystem.

6) If at any point the price of BTS:USD is beneath $0.015, each member of the team individually reserves the right to cease their contribution to development, process audit and their outstanding invoices to for all work to date, and exit the contract without any further constraints. (Worker Manager position excluded)

6.1. In case of Point 6), Worker Manager will look for alternative resources to join the team in order to deliver release.

6.2. Releases will not be postponed in case of Point 6), but just exclude missing deliveries.

7) This worker's agreement is crafted as a middle path between the desires of BTS core token holders, priorities for the blockchain and technology, as well as availability of core development team. 

8) Any additional requests from BTS token holders upon first activation of this worker will result in additional estimate and budget for integration and development (a new milestone worker).

9) This worker budget has no defined escrow and/or includes escrow fees.


## IMPORTANT NOTICE

This worker approves development of the listed BSIP's and other improvements, but not their inclusion within release of BitShares Core software as result of this worker. To make sure BSIP's are included in the upcoming release, BTS Core token holders must have vote in all BSIP's planned for release before 1. June 2020. Any BSIP voted afterwards may be excluded from release.

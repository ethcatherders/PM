# Ethereum Cat Herders Meeting 78 Notes <!-- omit in toc -->

### Meeting Date/Time: Tuesday, Feb 15, 2022 15:00 UTC <!-- omit in toc -->
### Meeting Duration:  55 min. <!-- omit in toc -->
### [GitHub Agenda](https://github.com/ethereum-cat-herders/PM/issues/268) <!-- omit in toc -->
### [Video of the meeting](https://www.youtube.com/watch?v=kTKknkUTmTw) <!-- omit in toc -->
### Moderator (and presenter unless otherwise noted): Pooja Ranjan <!-- omit in toc -->
### Notes: Viktor Shepelin <!-- omit in toc -->

---

# **Summary:** <!-- omit in toc -->

## Actions, Decisions, Requests for Help <!-- omit in toc -->

Action Item | Description
-|-
**78.1** | Pooja to provide update on merge testing discussions between KTH Royal Institure of Technology in Stockholm and Ethereum dev 
**78.2** | William to post the ECH monthly report for Jan on Mirror (currently on Medium)
**78.3** | William to clarify with multisig signers where the ENS domains should be transferred
**78.4** | Pooja to request client meetings to be made available via Permacast
**78.5** | Pooja to push through outstanding funding requests




Request for Help | Description
-|-
**Web Hosting** | Looking for community members with web hosting / management experience to help address outstanding stability issues and take community ownership over the website
**ECH Engineering** | Number of outstanding bugs/feature requests for EIPBot 
**Documentation** | More documentation help is needed to ensure meeting minutes are made available within 72 hours (bounties available) 
**Event Representatives** | Looking for anyone attending conferences and interested in representing ECH



--

# Contents <!-- omit in toc -->

- [1. Ethereum network upgrades](#1-ethereum-network-upgrades)
- [2. ECH updates](#2-ech-updates)
- [3. New tasks / brainstorming](#3-new-tasks--brainstorming)
- [4. Events and Hackathon](#4-events-and-hackathon)
- [5. ECH funding](#5-ech-funding)
- [6. Discuss and close the ECH GitHub Issues/PRs](#6-discuss-and-close-the-ech-github-issuesprs)
- [7. Review of outstanding action items from previous ECH meetings](#7-review-of-outstanding-action-items-from-previous-ech-meetings)
- - [Appendix](#appendix)
  - [Attendees](#attendees)
  - [Next Meeting Date](#next-meeting-date)

---

Before the meeting, yokulguy.eth introduced himself. 


# 1. Ethereum network upgrades

Video | [0:05](https://youtu.be/kTKknkUTmTw?t=5)
-|-

- Merge is approaching and is expected to be the first upgrade this year.
- Kiln merge devnet is available - [Spec v1](https://hackmd.io/@n0ble/kiln-spec). This will be the last devnet before merge testnet fork.
- Merge Community Meeting #3 was held prior week ([Recording](https://www.youtube.com/watch?v=65Pt6oS3kDM), [Notes](https://github.com/ethereum/pm/blob/74a74a9931f46030d040211004e72ab60d32fc50/Merge/CommunityCall_Meeting_03.md)) with robust community attenance and participation.
- PhD group from KTH Royal Institute of Technology in Stockholm approached ECH regarding testing research they have done that might be relevant for the merge. Pooja is coordinating an introductory meeting later this week and will provide updates at future ECH meetings.
- Developers looking for help with merge testing are encouraged to reach out to ECH for help.
- Shanghai is expected to be the first upgrade after the merge. [Shanghai EIPs](https://github.com/ethereum/pm/issues) are being actively discussed with some being moved into Proposal to Include stage. More updates expected as initial shortlist formalizes.

# 2. ECH updates

Video | [3:50](https://youtu.be/kTKknkUTmTw?t=230)
-|-

[ECH website](ethereumcatherders.com) - 
- Website has been down since hosting service provider's planned maintenance on Feb 3. 
- Pooja is following up with the service provider and exploring other hosting options (e.g. GitHub). Currently seeking greater community ownership.
- William provided overview of other potential hosting alternatives.

[ECH Engineering](https://github.com/ethereum-cat-herders/PM/issues/266) - 
- A number of EIPBot bugs and feature requests need attention. Contact Alita Moore if interested in helping.
- George: [Learn2Earn](https://github.com/ethereum-cat-herders/L2E) content is being finalized for direct sharing (email, Discord, etc). Dapp development is kicking off with repository and tasks being set up for open source, community development. Initial documentation has been made in the repo for review. Currently, participation will be tracked using POAPs with onchain / smart contract support being discussed for a later phase. [Project Board](https://github.com/ethereum-cat-herders/L2E/projects/1) available for those interested in following / contributing.

Cat Blazers - ECH Podcast - William
- Published 2 episodes so far in February - [Rotki App with Lefteris Karapetsas](https://open.spotify.com/episode/3ULiE90kOhP9MzWkrX0Trr?si=37QJLfPfTCabUJqzAy-ZSg) and [Nodes as a Service with Alchemy](https://open.spotify.com/episode/2FvUOphZ8oVSOEoaIUlp3K?si=378pIjpPS4mYjIFBe6neMw).
- No podcast planned for this week given limited availablity because of ETHDenver. Planning to resume next week with a new podcast every 1-2 weeks.
- Started migration of [ECH to Mirror](https://ethcatherders.mirror.xyz/) with first publication. Pooja and William discussed the plan moving forward to get all content available via Mirror.
- ECH ENS names (EthereumCatHerders.eth and ETHCatHerders.eth) have recently expired. William has purchased those names (along with ECH.ETH which is more expensive given it is only 3 characters) to prevent losing them to external parties. William is waiting for confirmation on the appropriate location to transfer the names. He is requesting gas reimbursement and will raise this in Discord (this is not a pre-requisite of transferring the names back to ECH). 
- Pooja and William discussed other uses for the ENS domain - e.g. moving ECH website to the parimary ENS domain. More research on use cases is required.
- Brent is working on setting up email address for the podcast on the main ECH webdomain (replacing current Gmail address). 
- William and Pooja discussed whether ECH should maintain multiple wallets (e.g. main one with limited access and one for Mirror posting with broader access). No decision / action at this time, but left for consideration by the members at a future time.

ECH Operations
- Next new joiner meeting is on Feb 17 16:00UTC
- Events currently being planned for March to celebrate International Women's Day (Mar 8)

[EIP Insight](https://hackmd.io/@poojaranjan/EthereumImprovementProposalsInsight/https%3A%2F%2Fhackmd.io%2F%40poojaranjan%2FEIPsInsightFebruary2022%23New-proposals-Draft)
- 3 new proposals added as draft and 2 moved to Final in February
- [EIP-2098](https://eips.ethereum.org/EIPS/eip-2098) is past its Last Call deadline but is on hold from moving to final to allow review of its change from Informational to Standard Track (ERC).

[PEEPanEIP](https://www.youtube.com/playlist?list=PL4cwHXAawZxqu0PKKyMzG_3BJV_xZTi1F)
- Above mentioned EIP-2098 was discussed in a recent [video](https://www.youtube.com/watch?v=Cn2C4PzOuV0&list=PL4cwHXAawZxqu0PKKyMzG_3BJV_xZTi1F&index=1) with Richard Moore
- Next meeting currently scheduled for Mar 2 to discuss merge testnets with Marius Van Der Wijden and Parithosh Jayanthi. [Latest Schedule](https://github.com/ethereum-cat-herders/PM/projects/2)

Meeting notes and action items
- Meeting minutes are available for all meetings (with a small handful of exceptions that are being followed up on)
- Looking for help with documentation, especially with All Core Dev and ConsenSys meetings. Bounties are available. Currently only 3 people work on meeting minutes. Viktor volunteered to make notes for today's meeting. 
- [Danksharding](https://www.youtube.com/watch?v=e9oudTr5BE4) video with Dankrad Feist and Vitalik Buterin now available. Recommended for researchers interested in contributing to the next major effort following the merge.

# 3. New tasks / brainstorming

Video | [44:45](https://youtu.be/kTKknkUTmTw?t=2685)
-|-

- ECH website hosting discssed earlier in the meeting
- There has been a request to make client meetings available via non-video platforms. Pooja to follow-up on whether Permacast can be used as it is for ECH and All Core Dev meetings.
- Pooja raised the question of whether client meetings should be made available through ECH podcast page. William suggested maintaining clear separation of the content to keep things simpler for listeners
- [EL Merge Client Release Naming](https://ethereum-magicians.org/t/el-merge-client-release-naming/7928/14) - meeting being planned for late Feb / early Mar


# 4. Events and Hackathon

Video | [50:45](https://youtu.be/kTKknkUTmTw?t=3045)
-|-
- [ETHDenver](https://www.ethdenver.com/) currently in progress (Feb 11-20)
- [Ethereum.Rio](https://www.ethereum.rio/) scheduled for Mar 11-20
- [DevConnect](https://devconnect.org/) scheduled for Apr 18-25

 # 5. ECH funding

Video | [52:00](https://youtu.be/kTKknkUTmTw?t=3120)
-|-

- Pooja is following up on Gitcoin Round 12 CLR Matching to get remaining funds transfered to ECH wallet. More multisig signers might be needed to expedite future transactions 

# 6. Discuss and close the ECH GitHub Issues/PRs

Video | [52:58](https://youtu.be/kTKknkUTmTw?t=3178)
-|-

- Multiple funding requests pending. Expected to go through this week.

# 7. Review of outstanding action items from previous ECH meetings

Video | [53:25](https://youtu.be/kTKknkUTmTw?t=3205)
-|-

- Gitcoin CLR Multisig signer item resolved. No other open action items

---

# Appendix

## Attendees

- Pooja Ranjan
- William Schwab
- Brett Allsop
- George Hervey
- Viktor Shepelin

## Next Meeting Date

Mar 1, 2022, 15:00 UTC.

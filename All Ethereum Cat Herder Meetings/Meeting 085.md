# Ethereum Cat Herders Meeting 85 Notes <!-- omit in toc -->

### Meeting Date/Time: Tuesday, May 25, 2022 15:00 UTC <!-- omit in toc -->
### Meeting Duration:  30 min. <!-- omit in toc -->
### [GitHub Agenda](https://github.com/ethereum-cat-herders/PM/issues/287) <!-- omit in toc -->
### [Video of the meeting](https://youtu.be/ZZZTU9aYmAY) <!-- omit in toc -->
### Moderator: Pooja Ranjan <!-- omit in toc -->
### Notes: Edson Ayllon <!-- omit in toc -->

---

# **Summary:** <!-- omit in toc -->

## Actions and Decisions <!-- omit in toc -->

Action Item | Description
-|-
85.1 | Create criteria for distributing GitPOAPs
85.2 | Decide on Github backup solution
85.3 | Decide on Youtube backup solution
85.4 | Go over ECH website backup procedure with contributor
85.5 | Add page to ECH website for the podcast

--

# Contents <!-- omit in toc -->

- [1. Ethereum network upgrades](#1-ethereum-network-upgrades)
  - [The Merge](#the-merge)
  - [Merge Community Call #4](#merge-community-call-4)
  - [Ropsten Beacon Chain](#ropsten-beacon-chain)
  - [Shanghai specs, Tracker](#shanghai-specs-tracker)
- [2. New initiatives](#2-new-initiatives)
  - [GitPoap badges](#gitpoap-badges)
  - [ECH GitHub backup](#ech-github-backup)
  - [ECH YouTube backup](#ech-youtube-backup)
  - [Actions](#actions)
- [3. Events & hackathon](#3-events--hackathon)
- [4. ECH updates](#4-ech-updates)
  - [ECH website](#ech-website)
  - [ECH engineering](#ech-engineering)
  - [Learn2Earn](#learn2earn)
  - [Cat blazers](#cat-blazers)
  - [ECH Podcast](#ech-podcast)
  - [ECH Operations](#ech-operations)
  - [EIP Insight](#eip-insight)
  - [PEEPanEIP](#peepaneip)
  - [Meeting notes and action items for ECH](#meeting-notes-and-action-items-for-ech)
- [5. Review of outstanding action items from previous ECH meetings](#5-review-of-outstanding-action-items-from-previous-ech-meetings)
  - [Actions](#actions-1)
- [Annex](#annex)
  - [Attendees](#attendees)
  - [Next Meeting Date](#next-meeting-date)

---




# 1. Ethereum network upgrades

Video | [0:00](https://youtu.be/ZZZTU9aYmAY)
-|-

## The Merge 

What's new in Eth2 contains most of the updates on the merge.

Mainnet shadow fork 5 deployed last Thursday. All clients survived the merge. There was equal split on EL and CL side. On EL side, Geth Nethermind and Besu participated. On CL side, all clients participed.

The foundation security team are running an analysis tool. Hoping to get some updates on this.

## Merge Community Call #4

Organized on June 3rd, at 14:00 UTC. Will be recorded and uploaded on ECH youtube.

- https://github.com/ethereum/pm/issues/532

## Ropsten Beacon Chain

Developers decided to fork Ropsten and have the merge there.

Ropsten Terminant Total Difficulty (TTD) expected to reach on June 8th. Will discuss more during the core devs meeting.

## Shanghai specs, Tracker

Discussions for adding any new proposal on hold. Once the merge is complete, discussion will continue on Shanghai.

- https://github.com/ethereum/execution-specs/blob/master/network-upgrades/mainnet-upgrades/shanghai.md
- https://github.com/ethereum/execution-specs/projects/1


# 2. New initiatives

Video | [3:16](https://youtu.be/ZZZTU9aYmAY?t=196)
-|-

## GitPoap badges

Have had discussions with lead developer of GitPoap. The intention it to reward ECH contributors with GitPoap, retroactively.

Repositories included: https://github.com/ethereum-cat-herders/EIPIP/issues/134. 

We need to decide criteria for distribution eligibility.

## ECH GitHub backup

Need to check what options are available. Need an update from William on team Radicle. Also considering Onleave as an option.

There will be some charges for a backup, but hoping ECH will cover those expenses.

## ECH YouTube backup

Arweave has come up as an option, as well as Swarm, IPFS. 

So far, we already have the meeting and podcast versions. But no backup for stateless meetings, as well as other meetings.

## Actions

- 85.1 - Create criteria for distributing GitPOAPs
- 85.2 - Decide on Github backup solution
- 85.3 - Decide on Youtube backup solution

# 3. Events & hackathon

Video | [8:13](https://youtu.be/ZZZTU9aYmAY?t=493)
-|-

[EthPrague June 10-12, 2022](https://ethprague.com/)
[ETH Shanghai Hackathon 2022 May 20, 2022 – June 3, 2022](https://gitcoin.co/blog/eth-shanghai-hackathon-2022/)

The hackathon channel on the ECH discord can be a good place to find hackathon team members for hackers.

# 4. ECH updates

Video | [9:20](https://youtu.be/ZZZTU9aYmAY?t=560)
-|-


## ECH website

Unsure of progress. Skipping for now, as member isn't on the call.

## ECH engineering

Some PRs have been merged the past few days.

We're about to merge a few more today. Pushing 2-3 more.

Review, coding, and testing is easier with smaller PRs. 

## Learn2Earn

Checkout meeting to follow with progress: https://github.com/ethereum-cat-herders/L2E. 

Developing a project to take in a quiz form. Based on presentations from ETH developers on PeepAnEIP. Finishing these quizzes rewards you with a POAP.

So far, done with the frontend, and working on the UI part of the admin view. 

## Cat blazers

William not yet on the call.

## ECH Podcast

Last week we published a PeepAnEIP podcast. An audio only version. Requesting guests to be more descriptive, so they can understand with just audio.

There will still be a link shared to the youtube video and the slides.

## ECH Operations

Member not on call, so skipped.

## EIP Insight

In May, 30 new proposals for Core, 1 networking, and 8 ERC proposals as draft, merged. There are 5 other potential proposals available as pull requests. 

There are 12 EIPs moved to review.

4 EIPs moved to stagnant due to inactivity.

2 EIPs moved to last call.

1 final EIP, EIP-1967.

## PEEPanEIP

Last week did a video on Shanghai proposals. 

Recorded an episode on voting standards. Also preparing one for the merge readiness of Ethereum clients.

Upcoming meetings can be found on [PEEPanEIP schedule](https://github.com/ethereum-cat-herders/PM/projects/2).

## Meeting notes and action items for ECH

URL/URI standard working group meeting organized yesterday. Only 1 proposal in final status. Purpose is to identify proposals for use cases. To make a consensus to push to final. [Recording and highlights](https://hackmd.io/@poojaranjan/URLWorkingGroup). Next meeting planned 2 weeks from that monday.

All Core Dev meeting notes 138
Consensus meeting notes 87
EIP Improvement Process meeting 56
EIP editors apprentice meetings 18 Agenda

Still waiting on notes for Consensus meeting 87.

We are looking for support on the consensus layer meeting and the ACD meeting.

# 5. Review of outstanding action items from previous ECH meetings

Video | [21:07](https://youtu.be/ZZZTU9aYmAY?t=1267)
-|-

Some edit needed for the ECH meetings. The number was incorrect. The person documenting it will have it updated.

Pooja checked with EF, so they will be having a backup for EIP repository.

ECH website needing backup. Discussed backup with contributor. Will need to get in touch again, to share the process.

Decentralized video streaming options, will be proceeding with Arweave option only.

Working on adding a page to ECH website for the podcast. No updates yet.

## Actions

- 85.4 - Go over ECH website backup procedure with contributor
- 85.5 - Add page to ECH website for the podcast

---

# Annex

## Attendees

- Pooja Ranjan
- Jose
- Viktor


## Next Meeting Date

June 7, 2022, 15:00 UTC.

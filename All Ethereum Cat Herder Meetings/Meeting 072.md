# ECH Meeting 72

## Meeting Date/Time: Tuesday 31 August at 15:00 UTC

### Meeting Duration: 0.50 hour

### [GitHub Agenda Page](https://github.com/ethereum-cat-herders/PM/issues/249)

### [Audio/Video of the meeting](https://youtu.be/Hyzj5XZwi9s)

### Moderator: Pooja Ranjan

### Notes: Kenneth Luster aka "Texas Farmer"

----

## DECISION ITEMS

New users on ECH Discord and/or contributor's introduction

**DECISION 72.1**:
I. [Network Upgrade](https://youtu.be/pgwqySjLwIs)
    • [Arrow Glacier](https://github.com/ethereum/execution-specs/blob/master/network-upgrades/mainnet-upgrades/arrow-glacier.md)
    • [EF Blogpost](https://blog.ethereum.org/2021/11/10/arrow-glacier-announcement)
    • [The Merge](https://ethereumcatherders.com/the_merge.html)
      o [Kintsugi🍵 In Progress](https://blog.ethereum.org/2021/11/22/finalized-no-32)
      o [Nimbus + Nethermind: Kintsugi Merge Tutorial](https://our.status.im/kintsugi-merge)
      o [Merge Community Call #2](https://github.com/ethereum/pm/issues/419)
      o [Post-Merge MEV Breakout Room](https://github.com/ethereum/pm/issues/423)

**DECISION 72.2**:
II. [ECH Update](https://github.com/ethereum-cat-herders/ech-website-v2/issues)
    • [ECH Website Updating](https://github.com/ethereum-cat-herders/ech-website-v2/issues)
    • [ECH Engineering](https://github.com/ethereum-cat-herders/PM/issues/245)
    • [Cat Blazers](https://medium.com/ethereum-cat-herders/catblazer-chronicles-july-21-2c0c22bc8827)
    • [EIP Insight](https://hackmd.io/@poojaranjan/EthereumImprovementProposalsInsight)
    • [Peep an EIP](https://www.youtube.com/playlist?list=PL4cwHXAawZxqu0PKKyMzG_3BJV_xZTi1F) • [Upcoming Meetings can be found on PEEPanEIP Schedule](https://github.com/ethereum-cat-herders/PM/projects/2)
    • [Meeting Notes](https://docs.google.com/spreadsheets/d/1axM1KaKc-GCcoPbAnYTOhgLnxXsBVoO5XRjTN3CLnck/edit#gid=0) and action items for ECH
      o [All Core Dev Meeting 126](https://github.com/ethereum/pm/blob/master/AllCoreDevs-Meetings/Meeting%20126.md)
      o [Consensus Meeting 76](https://github.com/ethereum/pm/issues/418)
      o [EIP Improvement Process Meeting 44](https://github.com/ethereum-cat-herders/EIPIP/issues/91)
      o [EIP editor apprenticeship Meeting - Recording](https://youtu.be/pgwqySjLwIs)

**DECISION 72.3**:
III. [New Initiatives - Brainstorming](https://github.com/ethereum-cat-herders/ech-website-v2/issues)
    • [NFT for EIP Authors (Final EIPs)]()
        o eipnft[EIPNFT.io](https://eipnft.io)
    • [OpenEthereum Client Support](https://youtu.be/Hyzj5XZwi9s?t=1067)
    • [ECH year end video](https://youtu.be/Hyzj5XZwi9s?t=1135)

**DECISION 72.4**:
IV. [Events & Hackathon](https://www.ethdenver.com)
      • [ETHDenver 2022](https://www.ethdenver.com) (Feb 11-20)

**DECISION 72.5**:
V. [ECH Funding](https://github.com/ethereum-cat-herders/funding/issues)
    • Funding via ESP, Gitcoin, CLR & Moloch

**DECISION 72.6**:
VI. [Discuss and Close the ECH GitHub Issues/PRs](https://github.com/ethereum-cat-herders/PM/issues)
    • [ethereum-cat-herders/PM](https://github.com/ethereum-cat-herders/PM/issues)
    • [ethereum-cat-herders/funding](https://github.com/ethereum-cat-herders/funding/issues)

**DECISION 72.7**:
VII. Review of outstanding action items from previous ECH meetings
     • [Meeting 71](https://github.com/ethereum-cat-herders/PM/blob/master/All%20Ethereum%20Cat%20Herder%20Meetings/meeting%20071.md)
     • Anything else?

## AGENDA

[Pooja Ranjan](https://twitter.com/poojaranjan19)
I. [Network Upgrade](https://youtu.be/Hyzj5XZwi9s)
Alright, I just have shared the agenda in chat.
Welcome to the [Ethereum Cat Herders Meeting](https://github.com/ethereum-cat-herders/PM/issues/249)[72](https://youtu.be/Hyzj5XZwi9s?t=3), I’m [Pooja Ranjan](https://medium.com/@poojaranjan19), and we are going to start with the first item [Network Upgrade](https://youtu.be/Hyzj5XZwi9s?t=14) on the agenda that is [Network](https://ethereumcatherders.com/network_upgrades) [Upgrade](https://youtu.be/Hyzj5XZwi9s?t=15).
As many of you may know that [Arrow Glacier](https://youtu.be/Hyzj5XZwi9s?t=18) is approaching recently, [Ethereum Foundation](https://ethereum.foundation
 ) released a [Blogpost](https://youtu.be/Hyzj5XZwi9s?t=23), stating, the latest client version. The network will be upgrading on, [December 8th](https://medium.com/@poojaranjan19).
The block number decided is 13.773 million. This is just an estimated date and time because this is on the proof of work chain. The time can be changed and so can be the date, but it's better to get their nodes updated sooner rather than later so, anyone who is running the Ethereum Execution Layer Node, or earlier as we yust to call it as One Dot O Node, please upgrade their node as early as possible. You can find the latest version that you might want to upgrade to in the blog post, shared by Ethereum Foundation link is added in the agenda [EF Blogpost](https://youtu.be/Hyzj5XZwi9s?t=73).
The next Network Upgrade that we are expecting is t[The Merge](https://youtu.be/Hyzj5XZwi9s?t=84), [Kintsugi🍵 in progress](https://youtu.be/Hyzj5XZwi9s?t=85) is the latest, Developers Testnet that we are running at a started in the month of November. It's a month-long sprint. The specs and milestones are already shared by Danny Ryan. The goal here is to do the experiments with Inter Op and release, persistent Testnet in the first week of December.
Danny recently shared a blog post [Kintsugi🍵 in progress](https://youtu.be/Hyzj5XZwi9s?t=114) telling all about the Kintsugi Testnet[].
We also have a couple of [tutorials](https://youtu.be/Hyzj5XZwi9s?t=120) available, thanks to the members team.
In relation to merge, we are going to have two calls.
One is [Merge Community Call](https://youtu.be/Hyzj5XZwi9s?t=129).
Another one is [Post-Merge MEV Breakout Room](https://youtu.be/Hyzj5XZwi9s?t=131).
The agenda is shared in the [Ethereum slash PM](https://youtu.be/Hyzj5XZwi9s?t=136). People interested, please follow the agenda and you will find out a zoom link in the appropriate channels for that. Alright, I see a couple of new people joining in today.
Thanks everyone for joining.
I quickly want to check with the [Blaine](https://youtu.be/Hyzj5XZwi9s?t=157).
I know you did mention that you had a conflict, so if you would like to bring up the item right away, we can do that. Otherwise, we can do it later.
Part of the talk.

 III. [New Initiatives - Brainstorming](https://youtu.be/Hyzj5XZwi9s?t=170)
 [Blaine Malone](https://twitter.com/blainemalone)
Oh, of [course](https://youtu.be/Hyzj5XZwi9s?t=170),
Thanks Pooja, Hello everyone.
My name is Blaine, I'm an engineer at Generally Cryptocurrency Exchange, I've kind of recently started like, trying to help build out Ethereum in my own time.
I was a Co-Author of [EIP-2981](https://eips.ethereum.org/EIPS/eip-2981) the Royalty Standard and, I suppose off the back of that, I built this like kind of side project that loads that allows, EIP Authors to who have Authored or Co-Authored in it EIP to mint an NFT if the EIP[NFT for EIP Authors (Final EIPs)] is finalized.
It was just a fun kind of side experiment of that I ran but I was hoping maybe that it might dip its toes into the area of, retroactive kind of public goods funding that if someone mints say seven, the [EIP 721](https://eips.ethereum.org/EIPS/eip-721), or [ERC 721](https://eips.ethereum.org/EIPS/eip-721) token, then like the market might decide that this is an important piece of work for the ecosystem.
Someone might put a bid on that NFT for the Author.
Yeah, like I said, if that doesn't come to fruition, I think it's just nice to have these badges kind of distributed anyway to, people who have helped bring [Ethereum](https://ethereum.org/en), push it along. I'm like, I know it's not all the Co-Authors of the Editors volume effort it’s between people just in the discussion.
Yeah, I did post accidentally post the link in the chat if you want to check it out it's called [EIPNFT.io](https://eipnft.io), I'll just preface this with like, it's a non-profit, there's no hidden costs, I'm not making any money from this site, I just wanted to build an NFT project that wasn't the cash crop like there's a lot right now.
I was just wanted to see, where it could be used by being in this kind of workflow that Pooja is constantly working on so, thank you.

[Brent Allsop](https://youtu.be/Hyzj5XZwi9s?t=315)
Could you put a link to that in the chat?

[Blaine Malone](https://youtu.be/Hyzj5XZwi9s?t=320)
Yeah, I did.
I’ll post it again if it got lost.

[Brent Allsop](https://youtu.be/Hyzj5XZwi9s?t=324)
Oh, I see it now.
Sorry I missed.

[Blaine Malone](https://youtu.be/Hyzj5XZwi9s?t=329)
I suppose like, yeah, any feedback, just letting me know, you can drop me a DM on Twitter](<https://linktr.ee/akalabs>) at [@blainemalone](https://twitter.com/blainemalone), and, yeah, I'd like to maybe iterate on this a few more times to see what else I can add in, and yeah.

[Pooja Ranjan](https://youtu.be/Hyzj5XZwi9s?t=358)
I'm sorry we are hearing some music

[Brent Allsop](https://youtu.be/Hyzj5XZwi9s?t=364)
Usually the sound highlights.
[Trenton Van Epps]*(<https://youtu.be/Hyzj5XZwi9s?t=370>)
It was Thomas.

[Brent Allsop](https://youtu.be/Hyzj5XZwi9s?t=371)
Oh,

[Trenton Van Epps](https://youtu.be/Hyzj5XZwi9s?t=372)
Thanks Thomas.

[Pooja Ranjan](https://youtu.be/Hyzj5XZwi9s?t=373)
Thank you, Thank you, Blaine for sharing the project.
Yes, I have been really interested in kind of having some, reward to the EIP Authors and were kind of exploring ways, and obviously the NFT was the first idea that we should be awarding the EIP Authors for continuously pushing, to make a final start to the Ethereum Blockchain.
So, thanks for that, and I'm hoping, the support that you are looking from the [Community](https://ethereumcatherders.com) will get for this project.
Thank you for sharing with us.

[Blaine Malone*]*<https://youtu.be/Hyzj5XZwi9s?t=408>)
Yeah. Thank you.
I just posted a link today, the [collection](https://linktr.ee/akalabs), so we've already got like EIP Authors who have minted, and you can kind of go in and see at what they look like.
It's, it's all there.
Thanks again.

[Pooja Ranjan](https://youtu.be/Hyzj5XZwi9s?t=422)
Right, we also have recorded a [PeepanEIP](https://youtu.be/Hyzj5XZwi9s?t=424) Episode with Blaine, on the [EIP Standards](https://youtu.be/hTbcw0rhLto).
Please check out his video for people who are looking into NFTs, [Moving on](https://youtu.be/Hyzj5XZwi9s?t=437).
The next item listed on the agenda is [ECH Update](https://youtu.be/Hyzj5XZwi9s?t=438).

1. [ECH Updates](https://youtu.be/Hyzj5XZwi9s?t=438)
The first one is [ECH Website](https://youtu.be/Hyzj5XZwi9s?t=439).
We recently have moved from a V 1.5.0 to V 1.6.0 to the changes that we have done in the latest version of the [website](https://ethereumcatherders.com) is we have upgraded our Network Upgrade Page, now it provides the information of all the upcoming latest upgrade.
We have created a page dedicated to Merge in which you can find all the Resources that we are collecting for Merge Testnet and other Merge [Educational](https://youtu.be/Hyzj5XZwi9s?t=474) [Resource](https://ethereumcatherders.com/the_merge).
There are certain videos that those are the good explainers for what Community can expect from this particular upgrade, and please check out the blog posts and the tutorial that we discussed in the morning today, that will be added on the page soon.
If you find anything related to Merge and you would like that to be shared with the rest of the Community Members, please create an issue or the pull request on the [Ethereum Cat Herders GitHub](https://github.com/ethereum-cat-herders/PM/tree/master/All%20Ethereum%20Cat%20Herder%20Meetings), that is where we collect all information for the [Website Updating](https://github.com/ethereum-cat-herders/ech-website-v2).
On the [ECH](https://youtu.be/Hyzj5XZwi9s?t=536)
[Engineering](https://github.com/ethereum-cat-herders/PM/issues/245).
I'm not sure I see Alita on the call, so let's skip that for now.
The next item is [Cat Blazers](https://youtu.be/Hyzj5XZwi9s?t=550).
I don't see William Schwab on the call, William.

[William Schwab](https://youtu.be/Hyzj5XZwi9s?t=554)
I am here, having Mic issues though, You can probably tell my...
A few seconds... to be able to comment...

[Pooja Ranjan](https://youtu.be/Hyzj5XZwi9s?t=547)
No problem, no problem.
[Moving on](https://youtu.be/Hyzj5XZwi9s?t=550), the next one is, [EIP Insight](https://youtu.be/Hyzj5XZwi9s?t=552), this [EIP Insight](https://youtu.be/Hyzj5XZwi9s?t=552) is a bulletin that we are running to provide the information what's going on the EIP Side, like people are content and actually pushing their Proposals to create a Standard.
There'll be a trying to capture the work that is being done by the EIP Editors and the Authors, and of course the Community Members.
So, as per the [EIP Insight](https://hackmd.io/@poojaranjan/EthereumImprovementProposalsInsight) for November 2021, we have three [new drafts](https://youtu.be/Hyzj5XZwi9s?t=590), that is, [EIP-3770](https://eips.ethereum.org/EIPS/eip-3770), [EIP-4444](https://eips.ethereum.org/EIPS/eip-4444), [EIP-4396](https://eips.ethereum.org/EIPS/eip-4396).
These are the three new Proposals that have been Merged.
The updates that I'm, reading following are on or before November 21st.
[One Proposal](https://youtu.be/Hyzj5XZwi9s?t=607) have been resurrected from Stagnant to Draft and the two from Stagnant to Review, the Bot have moved the three Proposals to stand in this time because most of the work has already been done in the earlier months, like in the [the month of](https://youtu.be/Hyzj5XZwi9s?t=622) September, October, we had over 200 EIP that were moved to Standard.
We are seeing more EIP is getting back on track like Authors are trying to update it so we can pursue the Proposals.
We have a t[two Proposals](https://youtu.be/Hyzj5XZwi9s?t=642) in the last call [EIP-2464](https://eips.ethereum.org/EIPS/eip-2464), and [EIP-2364](https://eips.ethereum.org/EIPS/eip-2364), both are [EIP-64](https://eips.ethereum.org/EIPS/eip-2364), and [65](https://eips.ethereum.org/EIPS/eip-2465).
I suppose the [Last Call Ethereum](https://youtu.be/Hyzj5XZwi9s?t=651) must have been over by now. These are going to be in the Final Status.
There is only one Proposal that was withdrawn and couple of non-normative changes are there.
We also have made certain changes to [EIP-One](https://youtu.be/Hyzj5XZwi9s?t=667) because the [EIP-One](https://eips.ethereum.org/EIPS/eip-1) is the only working document that is always under the Review Status, and sorry on the Living Status and it is always being reviewed, people can expect changes, please refer to [EIP-One](https://eips.ethereum.org/EIPS/eip-1), whenever you are working on any EIP or try to document a new Proposal to become a Standard.
[Moving on](https://youtu.be/Hyzj5XZwi9s?t=690), the next item is a [PeepanEIP](https://youtu.be/Hyzj5XZwi9s?t=697), this December we have a lot of... to Contribute, tomorrow we are going to get an overview of [EIP-3722](https://eips.ethereum.org/EIPS/eip-3722) Poster, with [Auryn Macmillan](https://youtu.be/Hyzj5XZwi9s?t=713).
This is a very simple ERC and it's in the Review Status. Please stay tuned for more information on how to join the Meeting if you are interested.
If you are working on something, implementing this or something, a project, which is like, which can implement this Proposal, you are more welcome to join the Meeting.
The information is always provided on ECH Discord General Channel.
Later in the month of November, we have Beacon Chain Lifeline, but a [DAP Lion](https://youtu.be/Hyzj5XZwi9s?t=749) on November 30th.
In December we have a handful of a recording for the Merge.
The first one is on [December 8th](https://youtu.be/Hyzj5XZwi9s?t=755), that is with Parrotosh and Burruto on the Merge Testnet.
I'm hoping that people who are interested to contribute and trying to run their own Testnet, this particular talk would help them how to set up the Merge Testnet.
Again, in December, we have a Meeting for sharing the [Secret of EIP Editing](https://youtu.be/Hyzj5XZwi9s?t=777),with Matt Burnett and that's plan on [December 14th](https://eips.ethereum.org/EIPS/eip-4399), [EIP-4399](https://youtu.be/Hyzj5XZwi9s?t=779), which is another important EIP for the Merge. We are going to discuss that with [Mikhail Kalinin](https://youtu.be/Hyzj5XZwi9s?t=790), the Author of the Proposal on December 21st, because we are discussing NFTs a lot.
We thought that it's good that we should provide an [overview of](https://eips.ethereum.org/EIPS/eip-721) [EIP-721](https://youtu.be/Hyzj5XZwi9s?t=800), we have invited William and Tricon to talk about the, this, NFT Standard, [the first episode in 2022](https://youtu.be/Hyzj5XZwi9s?t=811),that is going to be on January 4th, stay tuned for more Proposals, more discussions, and more informative episodes coming up on [PeepanEIP](https://youtu.be/Hyzj5XZwi9s?t=821).
So that's all, and, now coming up [Meeting Notes](https://youtu.be/Hyzj5XZwi9s?t=831), we have a Meeting Notes up for, [ACD Meeting 126](https://youtu.be/Hyzj5XZwi9s?t=837).
There have been some significant changes in the place hold of a [Consensus Meeting](https://youtu.be/Hyzj5XZwi9s?t=839).
I know the Note is already ready. We just have to upload it over there. Now all the earlier Meeting Notes can be found on [Ethereum slash PM](https://youtu.be/Hyzj5XZwi9s?t=850).
We have moved, we have archived the[Eth2 PM Repo](https://youtu.be/Hyzj5XZwi9s?t=853).
You can find all the earlier Meetings, as well as the Meeting 76[Meeting 76](https://youtu.be/Hyzj5XZwi9s?t=857), on [ECH slash PM](https://youtu.be/Hyzj5XZwi9s?t=857).
There was this, there was this[EIP Editor Apprenticeship](https://youtu.be/Hyzj5XZwi9s?t=864) Meeting that we planned last week.
I shared the link for [recording](https://youtu.be/Hyzj5XZwi9s?t=871), we did not have any Notes, but this is like an interesting Meeting.
A Community Meeting where many people participated and tried to share their interest to contribute any EIP Editing, Matt Burnett one of the EIP Editor, try to answer most of the questions for people who are interested and they might, and they may have missed joining the Meeting, they can follow the [recording](https://youtu.be/pgwqySjLwIs?t=33) [EIP editor apprenticeship meeting](https://github.com/ethereum-cat-herders/EIPIP/issues/93) If you still have any for the question, there is this Channel EIP Editors on Ethereum Cat Herders Discord, please post your questions there.
We hope to see your contribution in the [EIP](https://github.com/ethereum/EIPs) [repositories](https://youtu.be/Hyzj5XZwi9s?t=907), but we are getting the [EIPIP Meeting Notes](https://youtu.be/Hyzj5XZwi9s?t=911) up very soon, have been informed that the, it will be available very soon.

[Brent Allsop](https://youtu.be/Hyzj5XZwi9s?t=921)
Working on that.
Sorry, we got distracted there, but where we're on it.

[Pooja Ranjan](https://youtu.be/Hyzj5XZwi9s?t=925)
Alright, I see William Schwab has listed all his progress in the chat.
I don't know, William would you like me to read it out or we can just add it in the [Note Section](https://youtu.be/Hyzj5XZwi9s?t=935)?
I can probably read it, that would help for people who are listening.
I'm gonna, read it in point wise.
(1. KERNEL Block 4 ended - I've been providing support as a mentor there

  1. I've regrouped with EthernautDAO to work with a group I formed there on onboarding
    1. I've reestablished contact with a group working on creating a wallet "PlugFest", or testing across a number of service providers and integrators in order to try to find common problems and their solutions
    2. I've been working a bit with lightclient and Pooja on a bit of EIP editing, and also reaching out to various authors of ERCs to try to get their Proposals moved forward
    3. I've been working with Supreet Gupta on an initiative to try and involve ecosystem members in the ERC process, he's doing most of the work, and we are beginning to make some progress. If anyone is interested in joining this (on comms), additional help is welcome)  

[Number one](https://youtu.be/Hyzj5XZwi9s?t=944) KERNEL Block 4 ended up he has been providing support as mentor there.
[Number two](https://youtu.be/Hyzj5XZwi9s?t=958)
Yes, he has re-grouped with [EthernautDAO](https://youtu.be/Hyzj5XZwi9s?t=961) to work with a group to form there onboarding.
He has reestablished contact with a group working on creating wallet [“PlugFest”]( https://youtu.be/Hyzj5XZwi9s?t=971) or testing across a number of service providers and integrators in order to try to find a common problem and their solutions.

[Fourth one](https://youtu.be/Hyzj5XZwi9s?t=985) is he has been working a bit with the LightClient and me on [EIP Editing](https://youtu.be/Hyzj5XZwi9s?t=986), and also reaching out to various Authors of ERC to try to get their Proposal moved forward.
He has been working with Superette [Gupta](https://youtu.be/Hyzj5XZwi9s?t=1001) on an initiative to try to involve ecosystem member in the ERC process is doing most of the work.
Superette is doing most of work and we are bringing, sorry I just lost the chat, and they are beginning to make some progress.
If anyone is interested in joining the additional help is always welcome, but generally William Schwab helps out with anyone coming to the Ethereum Cat Herders or in the Ecosystem on Onboarding.
If you are interested, please reach out to William Schwab.
He's available on the ECH Discord.

[Brent Allsop](https://youtu.be/Hyzj5XZwi9s?t=1041)
Wow, that's impressive.
William doing a lot of stuff.

[Pooja Ranjan](https://youtu.be/Hyzj5XZwi9s?t=1046)
Right, Alright.
I'm moving on.
The next one is a [New Initiatives and Brainstorming](https://youtu.be/Hyzj5XZwi9s?t=1058)
We did hear about the NFT for EIP orders. The, the talk that were having from the past couple of Meetings on the project EIP NFT, once again, thanks again.
Once again, thank you very much to Blaine for that.
The next one is [OpenEthereum Client Support](https://youtu.be/Hyzj5XZwi9s?t=1067).
I don’t know, I see Spore on the call.
Britton, do you have any updates on that, or you would like to share something with the Community?

[Spore Druid Bray](https://youtu.be/Hyzj5XZwi9s?t=1074)
Yeah. No major updates, essentially, other than, yeah.
Tim did his post about the upcoming [Arrow Glacier](https://youtu.be/Hyzj5XZwi9s?t=1082). I think you've got to mention that today they had Merged it.
We haven't heard back from Igor as to the [State of POA](https://youtu.be/Hyzj5XZwi9s?t=1089) supporting it or not, I'm not too sure.
They said they were going to at least look into it.
I think they might be a bit busy with the potential Gnosis [Merge](https://youtu.be/Hyzj5XZwi9s?t=1097).
Other than that, no real update and yell come back if there is one.

[Pooja Ranjan](https://youtu.be/Hyzj5XZwi9s?t=1105)
Thank you very much.
Yeah. I think Ronan did mention about the POA Meeting and as I understand that it is not clear yet, let's wait for some more time to get more update on that.
Alright, [the next item](https://youtu.be/Hyzj5XZwi9s?t=1117) is with the help of Ken we met with this team who are a part of BanklessDAO and they are trying to support us [create a video(](https://youtu.be/Hyzj5XZwi9s?t=1135) for the Ethereum Cat Herders in which we are trying to share with the Community what the Ethereum Cat Herders are, and what are the tasks we are involved with, what are the other areas that people can contribute to?
So, we are just at the initial stage we are trying to document what all needs to be added to the video.
If you or if anyone has any idea any talk that they would like to help out with this reach out to Ken or [me](https://youtu.be/Hyzj5XZwi9s?t=1162) and we'll put you in touch with the team so we can have this great video providing all the information about this, I think it's going to be helpful for people who are new and they are wondering like where to go, and how we can actually step in the world of Ethereum Ecosystem, if they are not very technically skilled or they are looking to contribute in some other way than development.
I think the Ethereum Cat Herders is a good start, with the help of this video our goal is to provide more, and more information so people can join us.
[Pooja Ranjan](https://youtu.be/Hyzj5XZwi9s?t=1197)
The next one is [Events and Hackathon](https://youtu.be/Hyzj5XZwi9s?t=1197).
Note, this is planned in the month of February.
This is [Eth Denver](https://www.ethdenver.com) [2022](https://youtu.be/Hyzj5XZwi9s?t=1211);I suppose they have started accepting the participation so, please check out the [Website](https://www.ethdenver.com).
The link is [provided]<https://www.ethdenver.com>) [in here](https://youtu.be/Hyzj5XZwi9s?t=1211).

[Brent Allsop](https://youtu.be/Hyzj5XZwi9s?t=1211).
Anyone else gone to [Eth Denver](https://www.ethdenver)?
I think I'm going to try and go.

[Pooja Ranjan](https://youtu.be/Hyzj5XZwi9s?t=1224)
I'm not sure if I go, but if a situation is better, like COVID is under control, I can try.
[Brent Alsop](https://youtu.be/Hyzj5XZwi9s?t=1232)
Cool...

[Pooja Ranjan](https://youtu.be/Hyzj5XZwi9s?t=1236)
Alright, the next one is [ECH Funding](https://youtu.be/Hyzj5XZwi9s?t=1239).
I’m in touch with the [Moloch Team](https://youtu.be/Hyzj5XZwi9s?t=1243) and I'm working with them, with the RBP team to put the Grant On Chain right now it is on Discord and it is up for the Moloch Members to discuss and assess the Proposal.
We hope the Proposal to be On Chain I think of as early as December if it gets passed, I think by the end of December we should be having the results of that we hope the Proposal will go through because we have been receiving quite good feedback on that but let's see, I'll keep everyone posted on it.
We are reaching to the end of the Meeting.
I see a lot of [open](ethereum-cat-herders/funding) [issues](https://youtu.be/Hyzj5XZwi9s?t=1291) on [Funding](ethereum-cat-herders/funding), I'll try to close them today, I'm sorry, I tried.
I thought that I'd be doing it early morning, but I didn't get a chance to do that, but I'll finish it up today and on the Ethereum Side, I think it looks good.
Yeah, right on the [Meeting Notes](https://youtu.be/Hyzj5XZwi9s?t=1313) from the last Meeting.
Well Gentlemen, we created an issue in [EIP GitHub Bot](https://youtu.be/Hyzj5XZwi9s?t=1320) for 2070 for Alita to refer to.
Yeah, I think I had a chat with Alita on that and she's looking into it, Pooja Ranjan will add more people to [EIP Interns and Writing Meeting](https://github.com/ethereum-cat-herders/EIPIP/blob/master/All%20EIPIP%20Meetings/Meeting%20043.md).
Yes, we did invite a lot of people or the Meeting was completed last week, and the recording is available on [Ethereum Cat Herders YouTube](https://youtu.be/pgwqySjLwIs), please refer if you couldn't join the Meeting please refer to [the video](https://youtu.be/pgwqySjLwIs) and that's all from items listed here.
Anyone else want to bring up anything today?
I see a couple of new names on the [screen](https://youtu.be/Hyzj5XZwi9s?t=1359).
If anyone would like to introduce, please do.

[Brent Allsop](https://youtu.be/Hyzj5XZwi9s?t=1368)
Yeah, it's exciting.
What, how many people is it? 1, 2, 3, 10, 14 people, almost 13, I guess, cool.

[Trenton Van Epps](https://youtu.be/Hyzj5XZwi9s?t=1379)
There's an incredibly exciting, but whoever runs the Fireflies Bot, is there a way to remove my email from receiving notifications from that?

[Texas Farmer](https://youtu.be/Hyzj5XZwi9s?t=1392)
The group emailed, and I don't have control of the emails.
Yes, the Fireflies Bot is the recording transcribed and it just dictates the transcription, other than that's all it does.
I don't even see any emails, It comes to me directly with just saying information only and it provides a complete audio transcribed into words, that is all it does, other than that I have no idea who, or why you gotten an email from it because I don't have to know your email.

[Trenton Van Epps](https://youtu.be/Hyzj5XZwi9s?t=1437)
Yeah, I think it's probably just because it's invited to the event and then its maybe other people aren't having this.
I assumed it would send to everybody who's on the event.

[Pooja Ranjan](https://youtu.be/Hyzj5XZwi9s?t=1449)
Yeah, rite Joshua

[Trenton Van Epps](https://youtu.be/Hyzj5XZwi9s?t=1450)
Thanks, Joshua. I'll look at that.

[Pooja Ranjan](https://youtu.be/Hyzj5XZwi9s?t=1454)
Yeah rite, I think this is a send to everyone on the invite.

[Texas Farmer](https://youtu.be/Hyzj5XZwi9s?t=1458)
Yeah, I tried to remove it before we started but it came in as were starting.
So, I do apologize for that.

[Pooja Ranjan](https://youtu.be/Hyzj5XZwi9s?t=1470)
Anything else?
This week is a Thanksgiving week, so thank you everyone.
I'm trying to tie into everyone on the Community who listens to these calls or participate in these calls.
I hope to keep getting your support and we as Ethereum Cat Herder would try to keep supporting the Ethereum Foundation. Thank you everyone for joining us today, Have a good one.

## Attendees

•    ECH - Pooja Ranjan (Host)
•    Tim Beiko
•    Brent Allsop
•    William Schwab
•    Texas Farmer
•    Blaine Malone
•    George Hervey

### The date for the next meeting - Dec 07th at 1500 UTC

#### Zoom Chat Notes:

From Pooja Ranjan:
    <https://github.com/ethereum-cat-herders/PM/issues/249>

From Blaine Malone:
    <https://eipnft.io>

From Blaine Malone:
    Here’s some examples of already minted NFTs on the project

From Blaine Malone:
    <https://opensea.io/collection/ethereum-improvement-Proposal-nfts>

From Blaine Malone:
    SVG on chain generation.

From Blaine Malone:
    <https://eipnft.io/about> has more information about the project

From William Schwab:
    I suppose I'll give a little update in chat though, why not (I don't want to disturb the flow though).
Over the last two weeks:
    I. KERNEL Block 4 ended - I've been providing support as a mentor there
    II. I've regrouped with EthernautDAO to work with a group I formed there on onboarding
    III. I've reestablished contact with a group working on creating a wallet "PlugFest", or testing across a number of service providers and integrators in order to try to find common problems and their solutions
    IV. I've been working a bit with lightclient and Pooja on a bit of EIP editing, and also reaching out to various authors of ERCs to try to get their Proposals moved forward
    V. I've been working with Supreet Gupta on an initiative to try and involve ecosystem members in the ERC process, he's doing most of the work, and we are beginning to make some progress. If anyone is interested in joining this (on comms), additional help is welcome.

From Texas Farmer:
    How do I stop receiving emails from fireflies.ai?  

From Joshua Douglas:
    <https://guide.fireflies.ai/hc/en-us/articles/360020108217-I-don-t-want-to-receive-the-recap-emails>

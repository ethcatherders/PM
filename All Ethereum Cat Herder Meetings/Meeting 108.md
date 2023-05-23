# Ethereum Cat Herder Meeting # 108  
### Meeting Date/Time: May 09, 2023 at 14:00 UTC
### Meeting Duration: 24:37
### [GitHub Agenda Page](https://github.com/ethereum-cat-herders/PM/issues/349)
### [Audio/Video of the meeting](https://www.youtube.com/watch?v=JJie_JoKKcE) 
### Moderator: Pooja Ranjan
### Notes: Metago


# 1. Ethereum Network Upgrades

## [Cancun]( https://github.com/ethereum/execution-specs/blob/master/network-upgrades/mainnet-upgrades/cancun.md) and Deneb Upgrade, [Meta Thread]( https://ethereum-magicians.org/t/cancun-network-upgrade-meta-thread/12060) 

**Pooja**
Welcome to Ethereum Cat Herders meeting 108. I have shared agenda in chat. We have usual items, usual updates related to network upgrade and what Cat Herders have been doing. So starting with item number one Cancun and Deneb upgrade. So for Cancun, there is a meta thread at Fellowship of Ethereum Magicians. I have added a link to the meta thread here. So this meta thread basically talks about what proposals are getting in and what are the latest update from the client dev meeting. I'd highly recommend people to check this thread at Fellowship of Ethereum Magician so we can follow the latest update of upgrade. As we know, this upgrade will be mostly centered around EIP 4844. 

## EIP-4844 Implementers call 21 [Recording]( https://youtu.be/M2pYYEtM3Gw) & [Readiness checklist]( https://github.com/ethereum/pm/blob/master/Breakout-Room/4844-readiness-checklist.md) 

So 4844 is currently in Devnet 5. I have added link to Readiness checklist here, also linked to the last implementers call. In Readiness checklist, you can find all the earlier devnets update and where we are with respect to the progress with EIP 4844 and its client implementation both on consensus and execution side. As per the latest client dev meeting, we do have a short list of EIPs which are already included in the sense like client team have agreed to work on implementation of those proposals, along with 4844, and there are four proposals for that: [EIP 1153: Transient storage opcodes]( https://eips.ethereum.org/EIPS/eip-1153), [EIP 4844: Shard Blob Transactions]( https://eips.ethereum.org/EIPS/eip-4844), [EIP 6475: SSZ Optional]( https://eips.ethereum.org/EIPS/eip-6475), and [EIP 6780: SELF-DESTRUCT only in same transaction]( https://eips.ethereum.org/EIPS/eip-6780). 

There are three more proposals which are up for discussion. There is no consensus, probably we did not get enough time to discuss and have it included for the next upgrade and we should expect a discussion in the upcoming ACDE meeting this Thursday at 14:00 UTC and those proposals are [EIP 2537]( https://eips.ethereum.org/EIPS/eip-2537) which is a BLS 381 curve operation. 

This proposal was also considered for earlier upgrades but we could not have included it in any of the earlier upgrades so we should be expecting a discussion on this. 

## [EIP 4788]( https://eips.ethereum.org/EIPS/eip-4788) 

It is a recent proposal proposed by Alex Stokes. It's for beacon block route in the EVM. Mostly client dev meeting consensus suggest that they are in agreement of including. We should be getting feedback from execution clients and then the decision will be taken and [6493 SSZ Transaction Signatures Scheme]( https://eips.ethereum.org/EIPS/eip-6493) .We should be expecting a brief discussion about this to know whether this would be a part of Cancun or not. I have also added a list of useful resources. 

We have recorded a PEEP video and podcast for some of the proposals which are included for Dencun that is [1153 with Moody Salem](https://youtu.be/9YMEYTzzKtI and [EIP 4844]( https://youtu.be/4lyb02wZQQ4) with Casey and Terence. These are one hour deep down into the proposal and that will give you a very good idea of what changes you should be expecting with this upgrade. We hope to get authors of other proposals as we get a decision whether they would be included or not and yeah we should be getting more talks on PEEPanEIP. Check out the link is already added on the agenda. 

## Curated Deneb Updates

In addition to that I have also added a list to [curated Deneb updates](https://etherworld.co/2023/04/29/ethereum-dencun-upgrade/). Ether world team has reported multiple changes those are expected with this upgrade, for example mitigating Ethereum chain reorg scenario and how we can prevent Slash validator from becoming block proposers. These are the changes mostly on the Deneb side of the upgrade so I highly recommend reading out these blog posts to learn more about what changes we can expect on the Deneb side and the curated list is added in the agenda.

## EOF

So this set of proposals from the last all core dev meeting have now been moved to Prague upgrade. They would not be a part of Dencun anymore, however implementers meeting will continue to happen so we can make progress in terms of finalizing like providing a better respect to EOF proposals and come up with the final proposals that we would like to be included in Prague. I have added the link to the last [implementers meeting](https://youtu.be/D2_aVNqCLuk) and [notes]( https://docs.google.com/document/d/1w_yoxm0O-RwX7cguBRSjMYs5qv40uYoh3961MNS1sEg/edit#) for that.  that's on a network upgrade. We have less participation for this meeting but I hope that we would be able to share the information for people to follow later on.

# 2. Events & Hackathons [05:59]( https://youtu.be/JJie_JoKKcE?t=359) 

Moving on to the next section that is event fellowship and hackathon. [ETHPrague](https://ethprague.com/) is scheduled from June 9 to 11. A user shared information about ETHPrague hackathon and also a [DeFi Summit]( https://praguedefisummit.com/) which would be around the same time, around the same place, so if anyone interested to participate in either of those, please check out the information shared on the Cat Herders Discord - off topics and I believe it should also be in hackathon. 

[Edcon](https://edcon.io/) is coming up that is planned from May 19 to May 23. I am unable to visit there in person, however I'm hoping to give a talk on Ethereum governance remotely, so if you are around please follow that and if not then we should be having a recording for that very soon, right after the event of course. And [Devconnect](https://blog.ethereum.org/2023/04/20/announcing-devconnect-ist) is already announced for the month of November. If you have any events, fellowship and hackathon that you would like to share with the community please feel free to share it on cat herders discord at hackathon channel. So anyone from the community interested to participate may get relevant information.

Any question comments so far? I mean mostly those are information but yes if there are any question comment? 

**Santosh**
No.

**Pooja**
No problem. Probably we can move ahead this is going to be one of the quick meeting but let's go ahead with all the information that we have and we would like to share with the community. 

# 3. General Updates & Discussion [08:00]( https://youtu.be/JJie_JoKKcE?t=480) 

## ECH STATS

So in the next item here is General updates and discussion and we have shared the stats of cat herders. So we have over 65000 followers. People, if you haven't followed Twitter Discord YouTube and Linkedin of Cat Herders, please follow us, that would help you be updated with what's going on in Ethereum community. We try to share all the information that we have on all our social media platform for information related to meetings like PEEPanEIP meetings and EIP editing meetings. 

It's a good idea to follow us at YouTube because that way you will also get notification of whenever we upload any new recording.

###ECH Engineering

#### ECH Website

Next is ECH engineering and the website. I think the page for [Dencun]( https://www.ethereumcatherders.com/dencun_upgrade) is already up yeah right, and I remember there was a
pull request to update the page with the latest changes. For some reason I'm not seeing the changes on the page maybe I will have to check back. I remember there was a mention of a test process before everything could be deployed on the page. So I don't see George on the call to provide more information but yeah I hope
that we should have more information by next week. 


The idea of this page is to provide all relevant EIPs and resources for those EIPs on Ethereum Cat Herder's website so people wanting to follow the upgrade may get information at one place. 

The other task listed here is open source project list, in a similar direction yesterday we had a meeting with the team EIPisFun I guess and they have shared their idea of creating a page to provide more information related to EIPs that looks good on a high level and we hope that the team sometimes shows up on Cat Herders meeting and share more about their project and how they would like to proceed with that, but thank you Bruce for joining us yesterday. I know it's not the best time for you but thanks for sharing all the information with us.

### ECH Operation

Next is ECH Operation. We have noticed a few bugs on 4337
telegram integration. We hope to like fix those things Just let me quickly check, I think it is fixed now, and let me see, testing of it was going on, I saw some testing going on. Okay I do not have the exact information on this. I can see there are some test messages, but I will check back with the resource and hope to come up with the information on where we are with this integration.

The next one is splitting the ECH meeting video to create a general community update video and share it with the community. I think Santosh shared a few video clips with me in the past week and we hope to continue working. 

Santosh if you would like to add something on that like what do we plan to do next?

**Santosh**
I did get some feedback from you so I'll work on it and I'll
Retreat and I'll share an updated video uh like you said more than a text we'll try to have a video as well right?

That is one way and other ways with the text will write both variation and see what works best for us which gets us more views and more community, in which it reaches more of a community members but find that I am based on that really try to continue doing it so this is one of the initiative we have started we look forward to it here. 

**Pooja**
Awesome thank you so much. yeah I think it's a good idea to share these things in small clips so people can easily digest that but yeah I think a couple of more iterations would be needed before we can come up with the final version of it that can be shared. 

### [ECH Podcast]( https://open.spotify.com/show/7dgxKMkSyy3HWtQW7OfqXA) 

All right, moving ahead on ECH podcast, we should be expecting next episode this Thursday on ERC 4804. I remember Zeke mentioning that he's working on it and it should be live this
Thursday. 

### [EIPs Insight]( https://hackmd.io/@poojaranjan/EthereumImprovementProposalsInsight) & [EIPs Insight Website]( https://eipsinsight.com/) 

Next is EIPs insight. I am trying to open the document right here. For the month of May we have received five EIPs as draft out of five one is informational that is 6953 Network upgrade activation trigger and four others are ERC category. ERC 6808, ERC 6809 ERC 6821 and ERC 6900. We have moved the three proposals to the last call. ERC 6672 multi-redeemable nfts and it's last call deadline is May 16th. ERC 5570 digital receipt non-fungible token with a deadline at May 16th and there is one more ERC 5169 client script URI for token contract and the deadline is May 12. People listening to this call, if you have any question comment suggestion last minute changes to be done on these proposal, please reach out to the author at Fellowship of Ethereum magician. 

Once this proposal gets into final status we would not be able to make any further changes so this is the time before the deadline if you can share your thoughts and let the author know about what changes you are expecting in the proposal would be great to have. I have added all the information in the link is added here.

### [PEEPanEIP]( https://www.youtube.com/playlist?list=PL4cwHXAawZxqu0PKKyMzG_3BJV_xZTi1F) 

For PEEPanEIP, we have quite a few PEEPanEIP lined up, we should be expecting one tomorrow that is ERC 5773 context dependent multi-asset token. This is latest standard that is that means it has been finalized and merged as a standard for other projects to follow, will be joined by Bruno Steven to share information about this proposal. If you are adaptable or interested in working on this ERC or planning to implement this ERC in your project, I think it would be a good talk to follow and you are welcome to join the zoom call to ask your question comment directly from the authors of the proposal.

Other than that we have ERC 6672 planned for May 16th, ERC 6059 for May 24 and ERC 6220 planned for May / June. Please check out the schedule added to the agenda for rest of the proposals, which we are considering to have a talk with the author on PEPanEIP.

### [Meeting Notes]( https://docs.google.com/spreadsheets/d/1axM1KaKc-GCcoPbAnYTOhgLnxXsBVoO5XRjTN3CLnck/edit#gid=0)  

Next is meeting notes. So I think we have already received meeting notes for ACDE 160 and yeah I think it should be ACDC 108 we should be expecting this note by today / tomorrow I guess and EIPIP meeting. Okay, I haven't seen the pull request. I'll check with the resource working on this hopefully we should be expecting notes by today. EIP editing office hour meeting and
meeting agenda for next meeting and recording from the past meeting have been added here. 

Editing office hour have been like a good way to talk to authors directly and I have received a lot of good feedbacks about this meeting from new authors especially that they are trying to understand the process, so if you are someone interested in documenting a proposal for Ethereum standard and if you are facing any challenge, please please please join this meeting talk to editor directly and I hope that you should get your queries resolved faster and we get better  standards for Ethereum. 

Okay so that's all about meeting notes.

### 4. New Initiative & Association

The next one is a new Initiative and Association though we have very poor attendance in the call today, but we can still share ideas probably will get more feedback async on discord or we will follow up in the next meeting.

So on new initiative I have considered the list of accesses update like for cat herders, people join the group, they contribute and they move on to new projects. That's the process that we have been following on cat herders since inception so we have been joined by many contributors but time to time we need to revisit and decide on the accesses and update the permits, so as of now here I have listed three social media Discord Twitter and Medium in which we might want to reconsider the access maybe to remove people who have been inactive for over six months and update for people who have been active for past six months or more so we continue sharing information via our social media platform.

Yeah we are also looking for contributors to maybe send a weekly 
tweet or repost it on different social media to increase the reach. I know Santosh you earlier mentioned that you probably would be interested in working in that direction?

**Santosh**
Yeah I'll be sharing a sheet of tweets which we intend to do it in the next few days yeah.

**Pooja**
Okay that would be awesome yeah we are producing content, it would be nice to have increasing reach of these content so information lands on the rights right hand and people make a use
of the information that we are trying to share here about Ethereum Blockchain. 

Other than that if people have new ideas for community engagement you can either share here in the meeting leave them on agenda as a comment or share it on cat herders discord in general channel, would love to brainstorm and come up with new things that may be useful for community.

All right we are joined by George. George we missed you for the website related update I was trying to mention that we have merged the pull request but for some reason I'm unable to see those changes on the website. Are we still following the process of like deploying on test branch and then moving it to the main branch how is it that?

**George**
Ah yeah so I'm late yes that was pushed to the develop branch we don't have a test set up right now so I mean the changes that I made aren't like extreme so we just merge that to the main branch and you'll be able to see the changes on the actual website. When it comes to like future development would probably be nice to do like a test site for it but I mean it's not like required to do it. 

It would be if it was more like a like a web app that does certain stuff but this is more like an informational site so I mean we could kind of bypass that for certain things so.

**Pooja**
That makes sense but I'm wondering like I remember seeing change about like you know the change of URL, so the URL would be ethereumcatherders.com/dencun instead of dencun_upgrade but unfortunately I'm not able to find that change on the website even after it being deployed for over an hour now.

**George**
Yeah that's because it's on the developer…

**Pooja**
Yeah gotcha.

**George**
So yeah I'll do another PR to merge develop branch into Main and then you'll see the changes.

**Pooja**
Okay makes sense totally, thank you for confirming that yeah I was like confused that. Okay no problem thank you. All right any changes specific changes that you would like people to be looking for with the new PR here you would like to mention?

**George**
So I have the upgrades updated with like Chappella in the network upgrades with the epoch number and all that, still need to add the updates to the like dencun page but other than that I mean, I don't have anything specific so.

**Pooja**
No problem, we just will try to add the latest updates and keep sharing here on the Cat Herders website for people to follow Dencun upgrade.

All right yeah thank you thank you for the update so I think we have reached to the end of the meeting, unfortunately I did not see action items from the past meeting. We will have to check with the user but hopefully you know there wouldn't be much because mostly it is all about updates and what we are working on so yeah anyone else has anything to share update or bring up for the next meeting well it was like a short and sweet meeting. Thank you for joining and hope to see you in two weeks have a good one  everyone thanks and again so I'm late no problem thank you that's a good one yeah goodbye.

** Attendees
-	Pooja
-	Santosh
-	George 

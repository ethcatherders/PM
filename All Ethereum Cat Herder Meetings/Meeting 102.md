# Ethereum Cat Herder Meeting # 102  Notes
### Meeting Date/Time: Tuesday  31 January 2023 at 15:00 UTC
### Meeting Duration: 0.5 hour
### [GitHub Agenda Page](https://github.com/ethereum-cat-herders/PM/issues/339)
### [Audio/Video of the meeting](https://www.youtube.com/watch?v=a29d95k3kdc)
### Moderator: Pooja Ranjan
### Notes: Avishek Kumar

----

## DECISIONS & ACTION ITEMS

 102.1: Pooja to look into GitPOAP progress

------------

**Pooja Ranjan**[0:00](https://www.youtube.com/watch?v=a29d95k3kdc&t=0s): Welcome to Ethereum Cat Herders meeting 102. I have shared an agenda in chat.I have a few items to discuss starting from Ethereum Network upgrades,Events & Hackathon and some activities that we are trying to perform as a group here with some general updates. I see a new face on the screen now so maybe I can invite him to say a few words about himself if you would like to introduce yourself   to the Ethereum cat herder community or to the Ethereum ecosystem. so let's start with the brief introduction

**Daniel Gretzke** [0:38](https://www.youtube.com/watch?v=a29d95k3kdc&t=38s): sure. Hi  I'm Daniel. I work together with Will at polygon. He told me about these meetings here and I wanted to check them out. That's pretty much. 

**Pooja Ranjan** [0:52](https://www.youtube.com/watch?v=a29d95k3kdc&t=52s): It's awesome. Thank you Daniel for joining us today. I  hope that you find this group interesting and you'll be able to contribute to the Ethereum ecosystem as we go.

**Daniel Gretzke** [1:06](https://www.youtube.com/watch?v=a29d95k3kdc&t=66s): I hope so as well.

**Pooja Ranjan** [1:09](https://www.youtube.com/watch?v=a29d95k3kdc&t=69s): Very well.

# 1. Ethereum  network upgrades

**Pooja Ranjan**[1:11](https://www.youtube.com/watch?v=a29d95k3kdc&t=71s): Let's move ahead with the first item on the agenda. So the first item is Ethereum Network upgrades. 

- [Shanghai](https://github.com/ethereum/execution-specs/blob/master/network-upgrades/mainnet-upgrades/shanghai.md) & [Capella](https://github.com/ethereum/consensus-specs/tree/dev/specs/capella) 

**Pooja Ranjan**[1:17](https://www.youtube.com/watch?v=a29d95k3kdc&t=71s): We know that the Ethereum developers client team are preparing for Shanghai andCapella upgrade which we are expecting in March sometime. so for a Capella upgrade the public test net would be launched tomorrow I think. 5 Genesis time has 1500 UTC and details are shared by tester Barnabas on Twitter. I do not have the link handy but I will post it later on. There are a few other updates related to Shanghai and Capella. 

The withdrawal mainnet Shadow Fork 1 is now planned to be deprecated probably
Paritosh and team will come up with the next version of that.

The EF devops dashboard link is added to the agenda. So if people want to follow, they can do that on the progress of testnets. After Shanghai we are expecting.

- Cancun & Deneb [2:17](https://www.youtube.com/watch?v=a29d95k3kdc&t=137s): Is this potential discussion on SSZ migration? That's going on within the Ethereum community. So Vitalik has shared a potential roadmap for the migration as of now. we know that the execution layer is using the RLP method for communication however the consensus layer is using SSZ. It would be useful to have a single communication method for both layers. so developers have agreed to migrate but that would not be a part of Shanghai that could be a part of Cancun and we can expect more discussion in the next all core Dev execution meeting that is planned this coming Thursday . Probably Vitalik will share his proposal and there is an EIP for ssz on the execution layer as well. That is by a team member of a status so we hope to get both things discussed in the upcoming meeting. 

- [Shanghai page](https://www.ethereumcatherders.com/shanghai_upgrade/index.html) at ECH website [3:29](https://www.youtube.com/watch?v=a29d95k3kdc&t=209s): We are trying to keep the Ethereum Cat Herders website updated with a Shanghai page. If you find some resources that could be helpful. Please create an issue over there and we'll try to get it added on the website or you can create a pull request as well whatever works. There is a FAQ released by the developers team in the last Community call that was planned. I think it was a week ago on Friday so check out the recording and the notes are available. I think notes are available now so you can check out the notes if you missed the recording.

- EOF Devnets Breakout Room [Recording 6](https://www.youtube.com/watch?v=PKwMCmxHcas) [Notes](https://hackmd.io/@poojaranjan/EOFBreakOutNotes#-Notes-6) [4:12](https://www.youtube.com/watch?v=a29d95k3kdc&t=252s): EOF devnets breakout room meeting is planned next Wednesday 

- EIP-4844 Implementers [notes](https://twitter.com/terencechain/status/1612857882755858435) & [Video](https://youtu.be/FnKOHR92dXU) 

**Pooja Ranjan** [4:21](https://www.youtube.com/watch?v=a29d95k3kdc&t=281s): EIP- 4844 implementers meeting is going on as we are having this meeting right now. It happens every Tuesday so we could expect some latest information after the EF in person Workshop that's all on the Ethereum Network upgrades

# 2. Events & hackathon

**Pooja Ranjan** [4:45](https://www.youtube.com/watch?v=a29d95k3kdc&t=285s): Moving on to the events and hackathon, as we know ETH Denver is approaching. We have an event planned for EIP authors in association with the Fellowship of Ethereum Magicians and Victor from the Cat Herders team are jointly organising that event. We are inviting all EIP authors who are around to join us and share their thoughts on the current process. Any changes they would like to see in future and of course help us with the review process. We are looking for more peer reviewers for ERC category proposals especially if you can support. If you are aware of the process and if you have some bandwidth to share your feedback that would be really appreciated. There are a few other events in Denver one is Interrupt Summit.  I'm hoping to be there  along with Matt Garnett and Danny and Anett for a governance session so if you guys are around anyone who wants to drop by the event is free. There's no ticket for it. I have listed a few other events going all over the world by each Global team. So check out the list added here in the agenda. Anyone has any question comments so far? Very well

# 3. New initiative/association

- Client Diversity [Survey](https://docs.google.com/forms/d/e/1FAIpQLSdxWpN_kcZj4I_43vME2MOKHq3yD5_OFv8Lj-RO14537r1GLA/viewform) & [Announcement](https://medium.com/ethereum-cat-herders/client-diversity-on-ethereum-network-3854b5c3c95f) 

**Pooja Ranjan** [6:19](https://www.youtube.com/watch?v=a29d95k3kdc&t=379s): Moving on the client diversity survey. The Ethereum execution layer is struggling with a decent distribution of a client over the network. This client's diversity survey is to collect information about what is the present note that is being run by node Runners and what are their requirements. If they would like to switch. We also want to share information with the client team like what is users expectations. so if you are running an Ethereum client node whether the execution layer or consensus layer. Please take out this survey. This will provide us a lot of information that could be shared with respective client teams. I'm happy to share that we have already received over 100 responses for this survey so far. I'm hoping to keep it open till ETHDenver or so people know more because I'm hoping that there would be more of solo
validators that we could be meeting and we could encourage them to provide their feedback as well. So if you have already responded please consider sharing it to the group where you think there are people who are running Ethereum node and if you haven't responded yet consider taking out 15 minutes to provide your feedback.

- GitPOAP for EIP Authors

**Pooja Ranjan** [7:57](https://www.youtube.com/watch?v=a29d95k3kdc&t=477s): Next one is GitPOAP so we had a discussion with the GitPOAP team last week. We are planning to launch GitHub rewards for EIP authors. So whose eips are in final status I hope to see the
first batch being rewarded in the month of February that is on the top of our list for the ECH roadmap this year. So yeah it would be interesting to follow the process. I'm hoping that it would be rewarded based on the GitHub handle and the email address that is added on the
EIP for the final proposals. That is on the new initiative and Association I don't think the link is added here in the agenda but I will definitely update it. So  this morning we published.

# 4. General updates
- [ECH Roadmap 2023 & Recap 2022](https://github.com/ethereum-cat-herders/PM/issues/339) 

**Pooja Ranjan** [9:04](https://www.youtube.com/watch?v=a29d95k3kdc&t=544s): Ethereum cat herders roadmap for 2023 with a recap of what we did in 2022. I'd highly encourage you to check out this blog post. This list is like what are our top priorities this year. This is basically based on the upcoming upgrades so as I was talking about client diversity that is the feedback form is already out we are hoping to have a community call today. There is a draw Workshop organised by ETHStaker team and it's going to be a kind of Q&A session with a few guests who would be taking questions from the community. So if you're around I think the meeting is planned at 1 pm EST. So check out ETHStaker YouTube channel for the streaming link and we are doing great with PEEPanEIP. We have almost covered all four of five. Yeah one proposal is a Meta which we haven't covered on our podcast as well as the video series that we run. That's because that proposal was recently added, we hope to have the proposal on our show very soon and there is a few other information related to what we did in the past year. If people have thought suggestion on
what could be added more to the Ethereum cat headers roadmap. Please share your
thoughts with us on cat herder's Discord. Okay

- ECH Stats.

**Pooja Ranjan** [11:03](https://www.youtube.com/watch?v=a29d95k3kdc&t=663s): Moving on some ECH stats, It's just an information of how we are doing. There I would hope to see this number growing up so we get more people involved. There is one open pull request on cathode's website for updating the page of Shanghai. I didn't get a chance to take a look at it. But probably we'll do that soon and I hope that will update the page. very well. Anyone has any question, comment or anything to add so far. Okay I see a comment from William here. I am not sure if it was missed there that Tel Aviv

**Wiliam Schwab** [11:58](https://www.youtube.com/watch?v=a29d95k3kdc&t=718s): I didn't see it on the list. There is an event starting in TelAviv now. I thought I heard you ask if there were other events. So I dropped a link to that event if like you know if you're interested in adding it to the list or anything like that.

**Pooja Ranjan** [12:12](https://www.youtube.com/watch?v=a29d95k3kdc&t=732s): Of course we will do that. I'll go ahead and add that to the agenda so people who are visiting later on can find that link but you know going forward. We can always have that link dropped in the hackathon channel so we will pull it up from there and always add it on Agenda.

**William Schwab** [12:30](https://www.youtube.com/watch?v=a29d95k3kdc&t=750s):  I'll drop it there for sure.

**Pooja Ranjan** [12:31](https://www.youtube.com/watch?v=a29d95k3kdc&t=751s): Yeah that is helpful thank you. Okay that's about it.  I do not see Jose on the call and I don't think there are much on.

- [ECH engineering](https://github.com/ethereum-cat-herders/PM/issues/266)

    - [EIP bot](https://github.com/ethereum/EIP-Bot/issues) & [EIPV](https://github.com/ethereum/eipv/issues)

**Pooja Ranjan** [12:45](https://www.youtube.com/watch?v=a29d95k3kdc&t=765s): Updates on EIP bot and EIPV except for one minor change that we have discussed. I have seen an issue open for that is about the consideration of required EIP so in the last EIP meeting we discussed that requires EIP should not accept any withdrawn EIP in that particular section. This change has to be done on botlevel. The present EIPV bot allows it and we are hoping to disallow it. So that one change I think issue is open to anyone interested can take a look. It would be great to have a PR to get that updated

- Learn2Earn [App](https://l2e.ethereumcatherders.com/), [GitHub](https://github.com/ethereum-cat-herders/L2E)

**Pooja Ranjan** [13:31](https://www.youtube.com/watch?v=a29d95k3kdc&t=811s): On Learn2Earn,we had a meeting yesterday with George. He couldn't make it to today's call but the update and great news is we have released a blog post talking about the latest nft version of Learn2Earn on Polygon earlier. We were working on Mumbai testnet to have that released but I'm happy to share last week. It is on the polygon mainnet the reason why we have it on polygon mainnet. We have discussed it multiple times to make it. You know, simpler for people not expensive to mint an NFT for people who aren't short like how to get tokens for polygons. I think the charge has provided some explanation like how you can get your funds converted which is accepted on polygon blockchain. So please take a look at this
blog post and try the Learn2Earn with NFT. We hope to add a few more quizzes. Yesterday we had a discussion and shortlisted for five more quizzes to be coming soon.So yeah give it a try and if you have the bandwidth to make quizzes for us please reach us. We do have Bounty for making quizzes per episode. So ping me on cat herders Discord and we can talk about that.

- ECH Operations

**Pooja Ranjan** [15:11](https://www.youtube.com/watch?v=a29d95k3kdc&t=911s): ECH operations, we didn't have much backup work done in the past month however ZK mentioned that he would continue working on it. Just as there was some bandwidth constraint after the last discussion, I remember William Schwab mentioning that we should not stop it. So we have tried to like kind of balance it and hopefully we will continue doing the
backups on Arweave. I think the hackMD file here contains the list of all the talks that has already been backed up and you can find its lens tube link as well as Arweave link so anyone interested may check the file linked to the agenda.

  - [ECH Podcast](https://open.spotify.com/show/7dgxKMkSyy3HWtQW7OfqXA)

**Pooja Ranjan** [15:59](https://www.youtube.com/watch?v=a29d95k3kdc&t=959s): On the ECH podcast we released one episode last Thursday. We are hoping to continue doing that. We still have to catch up with the current video series but it is great to know that people have started loving the ECH podcast for the PEEPanEIP series that we are doing. I don't know if I had a chat with William offline about it. We would love to have you back William whenever you get a chance. So yeah do let us know we are being approached by a few projects to have your podcast back.

**William Svhwab** [16:40](https://www.youtube.com/watch?v=a29d95k3kdc&t=1000s): I appreciate it I am hoping to get back to it and I have enough peace of mind to like actually
give it attention.

**Pooja Ranjan** [16:49](https://www.youtube.com/watch?v=a29d95k3kdc&t=1009s):  Sure not a problem I hope sometime this year. you get what you're looking for and then I'll be happy to share the list. Yeah very well.

- [EIPs Insight](https://hackmd.io/@poojaranjan/EthereumImprovementProposalsInsight)WIP [EIPsInsight website](https://eipsinsight.com/)

**Pooja Ranjan** [17:03](https://www.youtube.com/watch?v=a29d95k3kdc&t=1023s): Next one is the EIP Insight, today is the last day of the month and I'm hoping to publish the eips Insight hack MD by tomorrow. The present website of eips inside I have doubts on one particular table that is last call table so I wouldn't say that is correct but on other status. It looks like we have five proposals received in a final status and we have 17 in review and draft status. We do have three last call proposals whose last call has ended. I believe or maybe it will end soon. Yeah nave all ended they were like 25 January so I may request the authors to move the proposal to the final status. I'll update the hack MD and will publish it tomorrow

- [PEEPanEIP](https://www.youtube.com/playlist?list=PL4cwHXAawZxqu0PKKyMzG_3BJV_xZTi1F)

**Pooja Ranjan** [18:10](https://www.youtube.com/watch?v=a29d95k3kdc&t=1090s): For PEEPanEIP we do have a peep planned for proposal 4736 that is CL consensus layer withdrawal production. It is a proposal which is not a part of a Shanghai upgrade but it is important for stickers. so I think this is going to be helpful for people who may not have set up their withdrawal wallet at the time when they were setting up their validated thing. So stay tuned for this one if you are interested in joining the zoom call. The link will be available on cat herder Discord. The meeting is planned for February 1st at 1400 UTC sorry the time on the calendar is off. I was informed recently that the author is currently in Asia so the time would be 1400 UTC instead of 1830 UTC. We do have another meeting plan for 4337 account abstraction using the alt mem pool method. So 4337 has gained recent traction with this new proposal. Earlier it was using a different method for account abstraction and now the team has shifted it using mem pool. So it would be interesting to learn more about the proposal so if your wallet Dev or anyone interested in I kind of projects and want to  implement this proposal for your project. You can join the call on February 15 at 18 30 UTC. If there is any proposal that is not covered so far and you would like to learn more about it. Please drop us a comment on each cat herder's Discord Channel. We'll try to reach out to
authors and have that proposal overview available for the community and that's about PEEPanEIP

- [Meeting notes](https://docs.google.com/spreadsheets/d/1axM1KaKc-GCcoPbAnYTOhgLnxXsBVoO5XRjTN3CLnck/edit#gid=0) and action items for ECH

**Pooja Ranjan** [20:28](https://www.youtube.com/watch?v=a29d95k3kdc&t=1228s): We do have meeting notes available for ACD meeting 153. We didn't have any meeting for consensus Dev last week. But we are expecting the normal cadence from this week onwards. So we will have an ACD meeting on coming Thursday and then an ACD meeting on the following Thursday. Notes for EIPIP meeting 73 isn't available yet but we are hoping to have it added by today or tomorrow. As I mentioned earlier there was a Shanghai Capella Community call. The meeting notes have been added as a pull request this morning so we can find it over there. EIP editing office hour meeting is planned for next Tuesday at the same time. We have the Cat Herders meetings. So, Yeah it's an alternate week. one week we have a Cat herders meeting and one we have an EIP editing office meeting. Anyone interested in learning about the editing process or has a question for the EIP editor or has a pull request and it is not moving please reach us or join the meeting on Alternate Tuesday at 15:00 UTC So that's all from the agenda I don't see any action item from the last meeting. Yeah, anyone has anything to add, share any question that I can answer for anyone today. It's good to see everyone here. Nice to see you Rory. Rory, keep us posted if you get any information or inside information for the next Devcon meeting and yeah we are still looking for more people to be able to contribute to notes writing for consensus meetings and execution meetings. We have only a few contributors so it would be really nice ,if you have some bandwidth to document. We do have bounties for notes writing so reach us to EthCatHerders Discord. Good thank you everyone for joining. Anyone has any questions after this call. Feel free to post on this card Channel and hope to see you in two weeks. Have a good
one everyone

**Willaim Schwab** [23:06](https://www.youtube.com/watch?v=a29d95k3kdc&t=1386s): Thanks Peter, appreciate it.

-------------------------
## Attendees

* Pooja Ranjan
* William Schwab
* Santosh J
* Daniel Gretzke
* Rory

## Next Call - Feb 14, 2023.



# Ethereum Cat Herder Meeting # 109  Notes
### Meeting Date/Time: Tuesday  23 May 2023 at 14:00 UTC
### Meeting Duration: 0.5 hour
### [GitHub Agenda Page](https://github.com/ethereum-cat-herders/PM/issues/354)
### [Audio/Video of the meeting](https://www.youtube.com/watch?v=iy6A8ZUQQs4)
### Moderator: Pooja Ranjan
### Notes: Avishek Kumar
----
## DECISIONS & ACTION ITEMS



------------

**Pooja Ranjan**[0:03](https://www.youtube.com/watch?v=iy6A8ZUQQs4&t=03s): Welcome to Ethereum Cat Herders meeting 109. I've shared an agenda and chat, it's issue number 354 on Ethereum Cat Herders PM Repository. So we have on agenda today ethereum Network upgrades related updates, then we will just share some information about events fellowship and hackathons going around General updates about Ethereum Cat Herders followed by new initiative or Association which we are hoping to have in the community and that will be followed by the outstanding action items if any.

# 1. Ethereum network upgrades

**Pooja Ranjan** [ 0:41](https://www.youtube.com/watch?v=iy6A8ZUQQs4&t=41s):  So starting with the first item listed on the agenda which is the ethereum network upgrade. So we are expecting the Cancun and Deneb upgrade which is also known as Dencon upgrade. Okay before we get into Dencon upgrade, I think there was a mainnet incident that happened about a week ago where mainnet blocks were not finalising in the expected time. Happy to share that the issue has been resolved. There was a new client release done by every client, every continuous client. So people may have updated if you haven't please check out your respective client and update your client note. There was a post-mortem report shared by Prism team and it contains the details of what happened and what were the precautionary measures taken to not have this kind of situation occur in future. 

- [Cancun](https://github.com/ethereum/execution-specs/blob/master/network-upgrades/mainnet-upgrades/cancun.md) & [Deneb](https://github.com/ethereum/consensus-specs/releases/tag/v1.3.0) upgrade

**Pooja Ranjan** [1:41](https://www.youtube.com/watch?v=iy6A8ZUQQs4&t=161s): Moving on to the Deneb, the consensus layer changes the upgrade that we are expecting with Dencon. There were a few proposals for discussion in the last meeting and we are hoping for some of these specs to be added in the release which is probably today or tomorrow. The changes that we would be expecting tonight would be to update blocks or blob size limits to Max blob commitment per block. The issue number is I'm sorry the pull request number here 
is a 3338 at consensus specs people can visit that there is one change related to engine API where validate blog version has excuses, so that is to pass version hashes for El validation consensus specs you can find it on PR number 3359 and there was one more update related to indian-ness of the polynomial commitment. So it seems like people are more interested in going to watch the big Indian rather than the small one. So we can expect these changes in client specs may be released this week. For EIP4788 we could not get any consensus. The Proposal is generally lied by people but there was an alternate proposal shared in the last consensus day of meeting. So just to sum up this proposal hasn't secured airspace and is going to be upgraded so far. Hopefully we'll get it to be discussed more on the execution layer meeting this week to know more if this proposal can be included or not. There was another interesting proposal for Deneb and that was attestation inclusion range
increases to expand attestation slot range that is still under discussion that may not be able to make it to the next spec release.But it could be for the subsequent release on Research side. There was a proposal by shy way for removing merge conditions that was introduced. I think during a capella. So people are mostly in agreement of that so we are hoping to have that removed from the specs,that's all on turn up upgrade that we are expecting.

- EIP-4844 Implementers call 22 [Recording](https://youtu.be/IckYm8ZXZtE) & [Readiness checklist](https://github.com/ethereum/pm/blob/master/Breakout-Room/4844-readiness-checklist.md)

**Pooja Ranjan** [4:24](https://www.youtube.com/watch?v=iy6A8ZUQQs4&t=264s):  I have added the recording to EIP4844 implementers called 22 which was uh the last call that happened I believe last two weeks if I have not mistaken.

- Changes included in the Network Upgrade.

**Pooja Ranjan** [4:39](https://www.youtube.com/watch?v=iy6A8ZUQQs4&t=264s):  Yeah there is a no change in the existing list of proposals we still have seven proposals out of these seven it seems to be four into accepted by client so probably will be part of Devnet whenever it is launched.

- EIPs Considered for Inclusion

**Pooja Ranjan** [5:01](https://www.youtube.com/watch?v=iy6A8ZUQQs4&t=301s):   Three 
proposals are still into consideration. They haven't been included yet. Check out for proposal 2537 which is pre-compiled for BLS 12 381, Proposal 4788 beacon block route and a proposal 6493 that is SSC transaction signature scheme. 

- Useful resources

**Pooja Ranjan** [5:26](https://www.youtube.com/watch?v=iy6A8ZUQQs4&t=326s):   We have some useful resources with respect to these proposals  check out PeepanEIP. I have added a link to the agenda.

- Moved to Prague

**Pooja Ranjan** [5:34](https://www.youtube.com/watch?v=iy6A8ZUQQs4&t=334s): Similarly we know that the eof proposals have been moved to Prague and the recording from the last meeting and notes are added to the agenda, so that's all about Network upgrade.

# 2. Events, Fellowship, Hackathon

**Pooja Ranjan** [5:48](https://www.youtube.com/watch?v=iy6A8ZUQQs4&t=348s):  Next section is events fellowship and hackathon Edcon  is going on right now. I have shared virtual talks for the community who are there for Edcon. Unfortunately I could not make it to Montenegro in person. So I hope the information shared with the talk with respect to the elements of ethereum governance will be useful for people. We are expecting ETHPrague hackathon in the month of June, June 9 to 11 and there are a list of other events which we are expecting this year down the line.

# 3. General updates/discussion

- ECH Stats.

**Pooja Ranjan** [6:35](https://www.youtube.com/watch?v=iy6A8ZUQQs4&t=395s):  
coming to the next item on the agenda which is the General updates and discussion section.These are General stats for different social media and we encourage people to start following that way. We will be able to share more information about what updates we are expecting with ethereum. What research work are going on and many more information with respect to the upcoming Network upgrade.

- ECH engineering

- ECH Website

**Pooja Ranjan** [7:08](https://www.youtube.com/watch?v=iy6A8ZUQQs4&t=428s):  On ECH engineering yeah I see we are joined by George. George if you have any updates on a website and yeah there is one other topic open source project list that you would like to share.

**George** [7:24](https://www.youtube.com/watch?v=iy6A8ZUQQs4&t=444s):  Yeah so when it comes to the ECH website I finished the Dencun page. So that's up on the website and you can check it out. When it comes to the other project, we've been thinking about
creating a directory for ERCs as well as other kinds of ERPs. So we are in the planning stage right now and we love like additional contributors to help out whether that's for design
development or just you know contributing when it comes to the ideas. We really want to make this an open source group effort. So if you're interested at all please message either in the Discord or one of us. Happy to have you join.

**Pooja Ranjan** [8:36](https://www.youtube.com/watch?v=iy6A8ZUQQs4&t=516s):  Thank you George so the idea here is like we are looking for implementation of EIPs and right now. There is no Central repository where people can find what are the implementations of any existing standard of ethereum Repository, so projects of whoever have implemented any of EIPs their open source and they would like to let people know about the implementation of that EIP and probably open to share their quotes because open source projects are generally helpful for other new developers, new application developers as well as for students to probably use that in hackathons and we hope that this page would be a good placeholder for this kind of information and projects would be able to share their information with the rest of the community. So please share your thoughts on how you would like to see this page to be and if you are open to help reach us. Any question comments so far for any of us.

- ECH Operations

 - ERC-4337 Telegram integration

**Pooja Ranjan** [9:51](https://www.youtube.com/watch?v=iy6A8ZUQQs4&t=591s):  Okay moving on next one is erc4337 telegram integration so the telegram integration was done and it was working properly but after the big part issue we have tried to restart it. It seems  we are struggling with it for some reason. The script that was originally written is not working for anyone here or listening to the call if you have expertise to help out with discard management and maybe web hooks related information so they can help us get this integration done properly. Please reach out to me. I'm available on Ethereum Cat Herders Discord. It is Discord.IO/ethcatherders. Please reach out and we'll be happy to have you engaged here.

- Splitting the ECH meeting video to create a general community update video and share it with the community

**Pooja Ranjan** [10:43](https://www.youtube.com/watch?v=iy6A8ZUQQs4&t=643s):  The next one is the ECH meeting video. I don't know Santosh if you have anything to add for that.

**Santosh** [10:53](https://www.youtube.com/watch?v=iy6A8ZUQQs4&t=653s):  I am finding it a little difficult with the video version but on the text version it's coming out well. If you're comfortable, maybe we can upload one or two text versions this week and see how it progresses. If it really doesn't work then I think we'll look for a video version happy to take it off yeah

**Pooja Ranjan** [11:13](https://www.youtube.com/watch?v=iy6A8ZUQQs4&t=673s):  Yeah sounds good to me. Maybe tomorrow we will sit together and  talk about it. If we fix, publish one.

**Santosh** [11:26](https://www.youtube.com/watch?v=iy6A8ZUQQs4&t=686s):  Got it I can have two weeks, two to three videos ready before our discussion tomorrow. 

**Pooja Ranjan** [11:30](https://www.youtube.com/watch?v=iy6A8ZUQQs4&t=690s): Okay sounds good thank you so much.

- [ECH Podcast](https://open.spotify.com/show/7dgxKMkSyy3HWtQW7OfqXA)

**Pooja Ranjan** [11:36](https://www.youtube.com/watch?v=iy6A8ZUQQs4&t=696s): Moving on to the ECH podcast so I believe we have published our last podcast this Thursday. I mean on the last Thursday of course and we will be hoping to get another episode released this Thursday. There is a page at ethereum Cat herders website. So it's an ethereumcatherders.com podcast. Please check out that page and you will find the link to all podcast platforms where we have published our podcast with respect to people or earlier conversation with the ethereum community Developers.

- EIPs Insight & EIPsInsight website

**Pooja Ranjan** [12:18](https://www.youtube.com/watch?v=iy6A8ZUQQs4&t=738s): Excuse me then next section here is a PEEPanEIP or EIPs insight. Okay fine for Insight I think in the month of May we have received 12 EIPs as draft and four EIP so far in the final status. There are six EIPs which were moved to the last call out of those six one proposals which were extended. I mean the last call period was completed but there were major changes on the proposal. so EIP editor decided to extend the period of last call and the new deadline is May 27th The Proposal number is 6454 minimal transferable nft detection interface so if you are an nft  application developer and you are hoping to make use of this proposal you find this proposal good useful or if you find that. There is something that can be changed to help out with your project. I think this is your second chance, second last chance that you are getting to get this proposal updated. Please share your feedback comments with the author by the end of May, that is May 27th. Once the proposal moved to final status it would be really hard to make any further changes. So please if you have any comments reach out to the author drop a comment at Fellowship of ethereum magician in the link added to the agenda. You can find the entire list of proposals which were added in the month of May and statuses of different EIPs

- [PEEPanEIP](https://www.youtube.com/playlist?list=PL4cwHXAawZxqu0PKKyMzG_3BJV_xZTi1F)

**Pooja Ranjan** [14:13](https://www.youtube.com/watch?v=iy6A8ZUQQs4&t=853s): Next is PeepanEip. I believe we have published episode 108 which is erc6672 multi redeemable nft last week and tomorrow we have. I am trying to find out the name of The Proposal.  So tomorrow we have a recording for EIP 6059 parent government nestable NFT tokens. Yeah with Bruno and Stephen time is 1830 UDC. You can check out the schedule for upcoming proposals, upcoming talks. We are hoping to have a conversation with Mikhail and some of the new developers.  I'm saying relatively new because they are a fresh patch from ethereum protocol fellowship and they have contributed to this proposal. We are looking forward to have a chat with these people on eip6110 on June 27th. Check out. The calendar for rest of the proposals which we have scheduled and if you have missed any past talk. Please subscribe to ethereum Cat herders, YouTube and follow the playlist, so that is all about PEEPenEIP 

- [Meeting notes](https://docs.google.com/spreadsheets/d/1axM1KaKc-GCcoPbAnYTOhgLnxXsBVoO5XRjTN3CLnck/edit#gid=0) and action items for ECH

**Pooja Ranjan** [15:49](https://www.youtube.com/watch?v=iy6A8ZUQQs4&t=949s): Yeah I'm happy to see looks like we have received all the notes we have for all core Dev execution 161 all core Dev consensus 109 eipip meeting 81. So yeah great job team thank you so much for having the submission in time. Any question comments from anyone so far ?

# 4. New initiative/association

- [Stader Labs](https://www.staderlabs.com/)

**Pooja Ranjan** [16:21](https://www.youtube.com/watch?v=iy6A8ZUQQs4&t=981s):  Very well so the next item here is a new initiative and Association. We are joined by stader Labs team here and yeah I would invite them to probably give their introduction and let us know how they are interested to help ethereum Canada's community

**Anoothi** [16:43](https://www.youtube.com/watch?v=iy6A8ZUQQs4&t=1003s):  Thanks Puja and hi everyone super excited to be interacting with these Union caterer Community. I will be very happy to share some details about you know what we are doing in terms of liquid staking and also more than happy to be in a continuous engagement with the community to answer any questions with respect to either node operations on ETH or liquid staking from the user side as well. I will start with sharing a few slides so that you know it's easy to follow through and let's get going from there. Can you guys see the slides? Okay great! So  hi everyone I am Anoothi. I am the head of ethereum business at Stader. We are a multi-chain liquid staking solution. Currently present across its different blockchains, those being the likes of polygon, BNB, Hedera, Fantom near anterior 2.0. We are super thrilled to share that we are soon coming to ethereum and the launch is scheduled for the mid of next month and so far you know in our multi-chain journey. We have had a great track record. We reached over a billion dollars in TVL during the time that we were on Terra and even post that  continued a really strong momentum across major chains and our current TVL is north of, you know, 107 million dollars. We have 70000 stickers who have stayed with us so far and we have a really strong social community of 250k Plus members and we really want to Leverage this momentum and keep growing and adding value for both our users and node operators on ethereum. So currently the opportunity to become a homes staker on ethereum is really a great opportunity. so you know if you're somebody who is interested on the Tech side of things and  can potentially evaluate this, it could be a really great experience and financial opportunity for you. Some of the things you could tap into are flexible cloud and Hardware options for running your nodes, so if you are somebody who wants to run multiple nodes in the range of hundreds then you can opt for a hardware solution like Avado or Dappnode and if you're somebody who wants to play it a little small to begin with and would want to run maybe even a single node then alternative options. All nodes are great options . Also if you don't want to go through the headache of managing a hardware and still want to run large-scale node Ops then other large cloud service providers like AWS and Google Cloud are also very strong options.  so the infra is all set up for you to tap into. Also there are multiple options through which you could become a node operator on ethereum. Obviously the standard option of solos taking exists. It's a really great option where you can become a node operator on ethereum by staking 32 each of your own and you will then accrue the El and the CL rewards which is the execution consensus LED rewards on your entire 32 each. However there are alternative ways to become node operators on ethereum through liquid staking platforms like centralized Solutions like Lido  and then decentralized protocols like RPL and then now stader. So each of them have their own value propositions and you need to choose what's the best solution for you in the centralized Solutions. Users need to deposit their ease and get steamed across a set of permissioned node operators.Currently you know in a basket of 20 to 30 validators whereas decentralized Solutions required node operators to bond a minimum amount of ETH in order to be eligible to become a node operator and the balance amount is fulfilled from users funds. Happy to discuss this in detail over subsequent sessions and then you know there is a very strong Community Support as you guys already might know through communities like the etherum cat herder  order each stickers the protocol communities where you often get. You know continuous support on Discord for any questions that you might have and you know for in at state of. We are trying to ensure that you have the product Tech and you know Community nodes who are supporting you with any guidance that you might need even in terms of node Ops. So that if you're somebody who has not done this before, you can still make this opportunity work for you and then lastly you know needless to say your node operations come with attractive rewards in the form of uh execution and consensus layer rewards on your bonded ETHs or the eth that you stake on the Chain directly plus commissions that come in from users funds and while the opportunity to become a node operator on ether is really you know out there and attractive. it is important to understand the landscape of uh staking that is currently you know facing Eth and then evaluate what could be the best opportunity for you as an aspiring or existing node operator so um the current liquid staking landscape on ETH. In fact staking in particular is fairly centralized with 50% of the ETH being staked with the top three players in Nephrology. In particular it lies  with the predominant uh player and they own 90% of the share. While there has been a strong focus on decentralization. Decentralized protocols on the other hand have faced this challenge of high Capital requirement. So if you're a solo staker then you need to give in 32 ETH and if you partner with decentralized protocols. Then the best available solution right now is 8 ETH and 2.6 ETH worth of governance token requirement and lastly there is a significant amount of untapped DeFi potential for liquids staking currently and ethereum. you know it's the second largest blockchain with a really thriving DeFi ecosystem and the possibilities to make LST a high utility token here is really Limitless and that is an opportunity that you know protocols have not been able to really double down on in a big way recently. So all these three,  you know situations and  status quo required for some intervention and this is exactly what we are trying to do with our upcoming solution which is ethics. So ethics is going to be the liquid staking token that stator will bring to ethereum and as I mentioned you know while the liquid is taking landscape currently is fairly centralized we are coming up with a hybrid model of a multi-cool architecture where we will have a set of permissionless validators and permissioned validators. 70% of our stake is going to the permissionless validators and so as you look on the slide these permissionless valid readers will be able to spin up a node on ethereum with only 4 ETH this is the lowest capital requirement in the ecosystem so far and it is magnitudes learned compared to solo staking. So 85% lower capacity required to solos taking and even a significant reduction compared to existing Solutions, so 50% reduction compared to the alternative solution. This low Capital requirement also helps you build leverage and hence results in higher rewards because of the 8x leverage of the four reads Bond.  Users node operators are basically able to earn 35% higher returns compared to solo sticking and in addition to this for each Bond there is a requirement of an SD Bond. SD is Traders native governance token and we have really tried to keep it. you know the lowest possible which is only 0.4 ETH worth of SD per validator the alternative Solutions require 6X of this requirement in governance token bonding requirements and lastly you know we are also reading this option of access to socialising pool for the node operators so that you guys can benefit from the consistent MEV rewards and don't have to really wait for becoming a block proposal to tap into the meet rewards, so this value proposition basically you know in a TLDR is that you come you spin up a node with the lowest capital required in the network which is just four reads and 0.4 ETH worth of SD and we will really help you max out on your rewards so the Blended rewards that you will earn on eth plus SD is going to be significantly, you know higher than alternative Solutions and at a 200 million dollar TVL Mark that still comes to 11.11 for our node operators. If you can come to underscore and leverage underscore to understand the rewards and lastly I would just leave you guys with this information and if you have any further queries feel free to reach us out on the Discord Channel and we will share all the resources with you and also happy to keep joining the Discord to share more information. If there are topics that you would want us to talk about more than happy to discuss those and contribute. Thank you so much guys.

**Pooja Ranjan** [26:11](https://www.youtube.com/watch?v=iy6A8ZUQQs4&t=1571s): Thank you so much Anoothi. This was a great presentation. I was very excited to see the capital investment here is less than anyone could have for a solo staking and a reward they are expecting could be higher with respect to other providers. Here it's always good to have a healthy competition as well as we would want to have more node operators getting online to support the ecosystem. yeah anyone on the call if you have any question for Anoothi or anyone for this stader lab either you can share here and I hope you guys are also available on our Discord if they have questions. Probably they can reach out to you.

- Octant, a new project built by Golem Foundation

**Pooja Ranjan** [27:06](https://www.youtube.com/watch?v=iy6A8ZUQQs4&t=1626s): Well thank you for moving on to the next item which is another project. It's a project by Golem foundation called octant. They are also taking  staking Services and they have recently shared some information about the public good funding and they are hoping to add support to us. The ethereum cat herders on a note that they have shared. They are working on the special pre-launch and the voting for public good findings would be taking place in ECC on somewhere in between July 17 to July 20th. I'm happy to share that they have also  considered ethereum cat herders . We hope to hear more about this project in the upcoming Cat herders meeting. We hope to have some representation and may be able to learn more about this project.

- Update ECH access

- nDiscord, Twitter, Medium

**Pooja Ranjan** [28:10](https://www.youtube.com/watch?v=iy6A8ZUQQs4&t=1690s): Next item here is update on ECH access. I believe I have updated access on medium. I'm still working on Discord and Twitter.

- Contributors to send weekly Tweets or repost on social media to increase reach

**Pooja Ranjan** [28:23](https://www.youtube.com/watch?v=iy6A8ZUQQs4&t=1703s): Next is a contributor to send weekly tweets. I am not sure if we have made much progress. Santosh I'm aware that you have a preposition yeah.

**Santosh** [28:35](https://www.youtube.com/watch?v=iy6A8ZUQQs4&t=1715s): Yeah I started with it. I do add about one or two tweets, that's  two draft tweets. I have but before we meet tomorrow I'll make sure we create at least four to five so that we can plan, we can schedule it for this whole week .

**Pooja Ranjan** [28:53](https://www.youtube.com/watch?v=iy6A8ZUQQs4&t=1733s): Sounds good to me now we can probably discuss it offline and get it done for that okay 

- Any new ideas for community engagement?

**Pooja Ranjan** [29:02](https://www.youtube.com/watch?v=iy6A8ZUQQs4&t=1742s): And the last sub item for this particular section is any new idea for Community engagement.If people on the call are maybe hearing to this call later on from the community if you have any thoughts suggestions how we can extend our support to the ethereum community, please do not hesitate reach out to us either on Discord on Telegram or on Twitter. Just drop us a comment so that's pretty much all about it and I'm just taking a quick look from the meeting notes if we have any action items for this meeting. Hopefully not but let me just take a quick look now. I think it's more on the update side so I think we are all good for today. Anyone
Would you like to add or share anything before we wrap up? Very well thank you so much, thanks everyone for joining today and we hope to see you in the next two weeks till then if you have anything to share please feel free to make use of channels available on each cat herder's  Discord. Have a good one everyone.

**Anoothi** [30:25](https://www.youtube.com/watch?v=iy6A8ZUQQs4&t=1825s): Thanks everyone was great interacting.

-------------------------
## Attendees

* Pooja Ranjan
* William Schwab
* Santosh J
* Anoothi
* Daniel Gretzke
* GeorgeHervey
* JA
* Kevin Hein	

## Next Call - June 6, 2023.





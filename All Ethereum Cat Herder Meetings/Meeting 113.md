# Ethereum Cat Herder Meeting # 113  Notes
### Meeting Date/Time: July 18, 2023 at 14:00 UTC 
### Meeting Duration: 0.5 hour
### [GitHub Agenda Page](https://github.com/ethereum-cat-herders/PM/issues/360)
### [Audio/Video of the meeting]([https://youtu.be/Be7mojkj6RE))
### Moderator: Pooja Ranjan
### Notes: Alen(Santhosh)

----

## DECISIONS & ACTION ITEMS
**DECISION/ACTION ITEM 113.1**:  Santhosh to share video shorts and start with twitter engagements.

----
# Intro
**Pooja Ranjan**
* Welcome to Ethereum Cat Herders 113. The issue number is 363 at Ethereum Cat Herders Repo. On our agenda today, we have a project demo by Octant, and we have, our guest speaker James. Then we will discuss a little bit about Ethereum network upgrades, the upgrade that is coming up, and perhaps what will happen after that, followed by, some other protocol development and research update.
* We'll talk about event fellowship and hackathons, and some general discussion of on how we are maintaining our websites and what are the other key contribution to the ecosystem. So, let me invite James to first maybe introduce himself and then talk about Project Octant. Welcome, James. 

**James | Octant**
* Hi, thanks Pooja. I really appreciate the, the opportunity to, to share with that. We're everyone here that, this new project that I'm gonna be introducing today called Octant, should I share my screen right now? Would that be, would that be helpful? Cool. So, as Pooja said that, I'm James. My name, or my, title at Golem Foundation is Head of Community and Partnerships. And, I'm really excited here to share with you this new initiative that, Golem Foundation has built called Octant.
* So as you can see the title here, it's, staking in Public Goods Funding. And so we, we've designed this mech mechanism for sustainable and participatory funding of public goods projects. so you can pretty much understand the setup like this. So, if you remember Golum from, a long time ago, we had a very successful crowdfunding round, even before the ICOs, were a popular thing back in 2016, raised about 820,000 eth if I remember correctly, in a, in a very short amount of time. the initial idea around this was to build a peer-to-peer marketplace for computing power. with the, rapid rise in Ethereum and it, and its value, this obviously led to us having a significant amount of funding.
* And so in 2019, Golum separated into two different entities. So there's Golum Network, which is still building this marketplace for computing power, and I work on Golum Foundation side, which is also, or which is additionally pursuing different ventures, outside of that initial mission, while hopefully adding both value to the Golum ecosystem and more broadly the Ethereum ecosystem. And so we think that, Octant does both that. So with that in mind, the basic setup is this with Octant, is that we're gonna be staking 100,000 ETH and then using the rewards to power the application Octant. 
* And so if you look in the middle of this diagram right here, any user of Octant who locks 100 G L M, which is about a $20 buy-in, so pretty minimal amount of, of, capital needed to participate here. Every three months, you're gonna be presented in Ethereum reward relative to how much, or I'm sorry, I should say proportional, proportional to how much you stake, into the application.
* Now, this is totally non-custodial. You, you retain full control over your funds at all times, and you can withdraw at any time. It's totally up to you. but every three months, as I mentioned, you're gonna be receiving this reward. Now, what you can do is take that reward, it's yours, you can do whatever you want with it. But as you can see in this arrow in the bottom right hand corner, there's also the ability to donate to different public goods projects that are whitelisted through the application. And so what we're trying to incentivize by donations is there's going to be a, matching reward fund.
* So your donations are gonna be multiplied, meaning that your money goes further if you donate versus if you, claim that reward for yourself. So in a way, we're hoping to, incentivize, participation and self-imposed taxation, but ideally we would love to see, some meaningful funding going to, various public goods projects. Now, some small but important details that matter. So, you, you have to lock GLM, otherwise you, you get nothing. So there's an aspect of, of taking action here. And then there's this magic of the square root that my two founders who are, who are economists have, have, have developed. And so it's a, it's a really unique way in where, the less amount of our total supply that's locked, there's actually a larger reward pool that that is generated and the entire mathematics and how it breaks out. 
* You can see this in our documentation that I'll share at the end of this presentation. But essentially people,if a lot of people who are, are claiming rewards for themself, the few that choose to donate, have even more impact over this matching reward pool. So their donations are multiplied even more. So it's  pretty neat mechan mechanism design. Where we further want to take this after this initial stage MVP that I'm describing to you right now, is that we see this as a unique, sandbox for experimentation.
* So what we're hoping to provide is, an ability for developers. because we're doing this in every, 90 day windows or what we call epochs. We're hoping to provide this platform to where builders who are developing some kind of coordination mechanism, maybe it's an anti civil tool, maybe it's a delegation framework, whatever it may be. We're hoping to provide this area to where a developer can deploy their tool in our environment, for any given epoch. And with users having real money at stake, we can hopefully provide them much more tangible feedback about what they're building, if it actually works in a real life environment. So we see this as, we see Octant as an experimentation across a few different fronts. Experimentation in, funding of public goods via community driven action, and then also experimentation around different coordination mechanisms and, hopefully finding out what actually works, in this decentralized space that we're all, working in.
* And so we haven't launched yet. We're gonna be launching in August.
* And so to kick things off before we launch, we have this, initiative we're calling EPOCH Zero. And Epoch Zero essentially breaks down to, there's going to be $1 million worth of ETH that we're gonna be donating to to in different projects, including Ethereum Cat Herders
* And so the way that that distribution is going to work is, a vote that takes place on Snapshot, which begins on, July 21st. And it's, gonna be running, or the poll is gonna be open for a week long from July 21st to July 28th. And everyone who votes on snapshot via weighted vote voting mechanism, meaning you can spread your vote amongst any of the 10 projects or as many of the 10 projects as you'd like, that that vote is essentially going to decide the distribution of this 1 million, worth of Eth.
* And so, the way that we're gating this vote is we're handing out POAP to, community members who care about funding public goods. So we've been trying to get the word out at Eth CC at funding the Commons and other virtual events such as the one we're doing right now. And so we're just looking to raise awareness around Octant and hopefully driving some impactful funding to these 10 different public goods projects, including ECH, and hopefully from there, kickstarting, Octant, and, moving into this, I guess you could say this, continual evolution of experimentation in, in governance and funding. So here are the, the, different projects. As I mentioned, obviously ECH is one of them, but we also have Supermodular Protocol Guild, giveth, GI Coin, Colonel Clear Fund, Dow Drops, drips, and ETH Stakers. So these are the 10 projects, that you can distribute your voting power amongst.
* And so if you would like to find out more, you can find out, how Octant works and, a lot more useful information. Our docs are, in my opinion, very well explained in a, in a concise manner, by visiting docs.octant.app. 
* And so, I'm happy to, answer any questions, obviously, Pooja or you know, if anybody else has any. But, this is the basic gist of both Octant and what we're trying to do, via EPOCH zero and, and building awareness around Octant. 

**Pooja Ranjan**
* Very well. Thank you so much, James, for giving this presentation, and I'm really happy that rads are part of, this, grant public good funding ground that we are having. And, again, I'm happy that we are being considered with one of, not one, actually nine of the best, ecosystem projects. So it's a great honor for me. I'm hoping people on call, they already have the POAP , so they can get voting power and with that POAP, you could be able to vote to any of those 10 products, right? Or maybe multiple 10 products, multiple, votings. Yeah. 

**James | Octant**
* Yeah. So, for example, like if you like, you, you wanna be able to support Ethereum Cat Herders, and Protocol Guild and Giveth or Eateth Staker, yeah, you can, you can select those three or four projects and, and distribute the, your, your weighted vote, yeah. amongst as many as as you'd like. So, there's no, I guess rivalrous way in which, in which you're able to vote. 

**Pooja Ranjan**
* That's awesome. That gives, like even voters more flexibility. They do not have to stress a lot. Like I can wait to vote only one project, right? So that's a very good point. right? And people who do not have the POAP, they may reach out to me or to James directly. We both are on the ATM chat card to get the link to the POAP. And I think, still Friday till what date it is, like people can get home. 

**James | Octant**
* Yeah. So, so the way that Snapshot works is it takes, takes a snapshot of the blockchain. So we could still hand out POAP after Friday, but with the poll open, it's gonna be taking a snapshot of who has it at that cutoff point. So unfortunately, if you got the POAP after the, the poll is launched, snapshot wouldn't recognize you as a holder. So yeah, getting this POAP into your hands, prior to Friday would be, would be the ideal scenario. 

**Pooja Ranjan**
* Awesome. And I have also, added the link to the announcement blog post on today's meeting agenda people may follow. And feel free to reach out to us. Anyone has any other question for James today? 

**James | Octant**
* Great. 

**Pooja Ranjan**
* I'm getting off easy, Yeah, I'm sure the documentation that you have prepared for us have been very helpful. It's very clear how to and when to do things, so I'm sure this is going to be a great event. 

**James | Octant**
* Awesome. Well thank you so much. 

**Pooja Ranjan**
* Thank you so much for joining James. you are welcome to stay back if you would like to. Otherwise feel free to drop off and we can go ahead and continue with our, usual updates. We'll try to have, I'm, I'm recording of this. Yeah, we'll try to have a separate recording of this as well so we can circulate it even more within the community. Alright, moving on to our Cat Herders meeting. 

# 2. Ethereum network upgrades [10.59](https://youtu.be/cF7VWr0M6XE?t=659)
# Cancun & Deneb upgrade
* Then first item listed here is which is Cancun and Deneb upgrade. We all know that Deneb, the combination of Cancun and Deneb is expected in Q4 2023. Currently we are testing and we have Devnet-7 open. There's a hope that Devnet-8 will have all spec changes included till Devnet-7. It's only 4804 if I mention it correctly. The blob proposal is there. But for rest of the proposals which are listed here on the agenda, I think there are five proposals on EL side and there are two proposals on CL side.
* This would be the first time that CL side have, specific EIP to be included in the spec. so it was really interesting to talk to authors who have documented, these proposals. We are about to share the first talk on 704 for perpetually valid signed voluntary exit, which we recorded with, and that's very short and sweet proposal. But it was interesting to follow how client team, like how consensus layer client team are trying to follow the EIP process.
* On the similar note, EIP 7045 documented by Danny Ryan, which, is to increase max attestation inclusion slot will be, recorded tomorrow at 1830 utc. So should you have any question, if you're validated and it would be interested in learning about what does increase max at attestation inclusion slot means, please feel free to join us on the recording. 
* Otherwise, the episode will be live on the following Monday. people can also follow 4844 implementers call recording and Tends tweet. There's a readiness checklist because 4844 is the biggest EIP that is getting into the DA Canone upgrade. So, we are trying to make sure that we are following the checklist. Please check out and that will help you understand the status of readiness. 

# Cancun Readiness checklist [13.01](https://youtu.be/cF7VWr0M6XE?t=781)
* Similarly, we have a Cancun Readiness checklist. We are hoping to have a Deneb readiness checklist as well 

# Useful resources [13.12](https://youtu.be/cF7VWr0M6XE?t=792)
* For some useful resources. We have recorded multiple episodes on PEEPanEIP Playlist. people may follow it on YouTube or EthereumCatHerders podcast. This last shift podcast on whatever your  favorite platform for podcast is. some 

# Other Protocol Development & Research
* More updates on protocol development and research side. As we know that, in the Shapella upgrade there was a meta EIP announcing that, we would be making some changes and, people were discussing about the SSD and R L P thing, like how we are gonna implement SSD better in Ethereum blockchain.
* So there are different proposals on SSD two of them, EIP 6404 and EIP 6466. they were analyzed by a third party called Datateam. They had an impact study on the transition to SSZ because as we know, the EL client, they were using RLP method, but CL they started with SOV.
* So if there is a transition to be happening, it's important that we need to find out if anything is breaking or everything is all right. As per the conclusion reported in that report, they find that out of all the contract transaction and protocol they observed, there was no evidence of reliance on transaction route. 
* And they have categorized the disruption that this EIP may create either of this of course. so for 6466, it is moderate but manageable. However, for 6404, it is insignificant and very low. So there are high chances that 6404 will be selected over 6466, but none of them are considered in CFI yet. We hope to hear more about it in upcoming call. that is on Thursday at 1400 UTC. Apart from that, we are having Oracle implementation call. People may find the recording of that, on EthereumCatHerders, YouTube, and we did have a EOF implementers meeting last Wednesday. 
* So please follow recording if you have missed it. I also joined the EPF Ethereum Protocol Fellowship program. There was this very interesting meeting people who are interested to be a contributor to Ethereum an ecosystem. So how this protocol fellowship worked there, there were certain people who were selected at the time this Protocol Fellowship was announced, but people have kept it open and non-perishable way.
* So even if you are not selected, you can follow the meeting, you can follow the Discord communication and the GitHub. You are also allowed to propose your own project at the end of this fellowship program. 
* Even if you are not a part of the, cohort fourth, which is going on, that will allow us to get more people involved. And if your project is selected, perhaps you will be supported with, some financial aid to reach out to Istanbul and have a presentation over there. 
* So anyone interested in protocol development, even if they missed the opportunity to join the 4th cohort, please, please, please check out the GitHub repository. 
* Reach out to me. I will be happy to point you towards the EPF team if you're not aware otherwise. EPF team mostly hangs out on E&D Discord. There is a specific channel for EPF people. 

# 3. Events, Fellowship, Hackathon [16.44](https://youtu.be/cF7VWr0M6XE?t=1004)
* Okay, moving on. Next is event fellowship hack. As I was talking about DevConnect Istanbul people, are expecting this, event to be happening in November, November 13 to 19. I suppose the announcement is already out. Yes. I have added the blog post of Ethereum.org. Please check out, there is another scholar program that they are organizing and the application is open till July 23rd.
* Please check out the link added on agenda and you'll be, able to apply if you haven't done it already. Any question, comments so far? Very well, let's move on.

# 4. General updates/discussion [17.29](https://youtu.be/cF7VWr0M6XE?t=1059)
* As we are trying to build a community, we are also keeping a track of, the social media and how we can grow it. I have added link to all our social media and, the numbers showing like how many people are there. I would request, everyone listening to this call, like, share as much as you can.
* We want people to learn about Ethereum want people to know more. And also we would like to extend our support to whoever is interested in contributing to the Ethereum ecosystem.
* You can take a look at the stats, add it to the agenda here. 

# ECH engineering [18.05](https://youtu.be/cF7VWr0M6XE?t=1085)
* Next one is ECH engineering and ECH website. Unfortunately I could not make it to yesterday's call. I wasn't feeling very well. I wondered if, George, do you have, you may have any update that you would like to share? 

**George**
* Yeah, just a brief update. So, added some updates on the Dencun page where now we include the most recent, DevNet, which is DevNet-6 and DevNet-7. there's a PR for that and, ready to be merged anytime. 

**Pooja Ranjan**
* Awesome, thank you so much. And I'm hoping that we also have these two EIPs, which were part of, consensus client, not the execution. which ones 7044 and 7045? 

**George**
* Yes. Okay. Yeah, I'll add those too. 

**Pooja Ranjan**
* Okay, that would be great because, you know, these are new proposals on CL side. It'll be interesting to get some feedback. Moreover, I found that their discussion tool link is almost empty, so it would be good idea to collect some feedback from community. Alright, we did the page for Deneb. 

# ECH Operations [19.31](https://youtu.be/cF7VWr0M6XE?t=1171)
* Okay. it's such Operation YouTube shots. for now we have created a shorts out of the PEEP episode that we are creating and that those are being added to Community Playlist. People may check out the community playlist for shorts. I know Santhosh wanted to work on separating the videos. 
* Unfortunately he's not in the meeting today is traveling. but he would also be owning, the responsibility of writting newsletter and doing this, clip created for a community. So we should see something in action very soon. But in the meantime we have multiple shorts available in Community Playlist on ECH podcast. 
* If I remember correctly, we are good episode 111 and, ZK is working on uploading more podcasts there. 

# EIPs Insight & EIPsInsight website [20.23](https://youtu.be/cF7VWr0M6XE?t=1223)
* Keep EIPs Insight, if I remember correctly, let me just quickly take a look at it. find it. Okay, so we have 5 EIP on final status and we do have, one in last call, which I think last call has already passed. 
* There are three proposals in review and three proposal in draft for last call proposal. Which number is 6066 signature validation method for NFTs? I would recommend. okay, how is that happening? Something is not right here because it says that status is already final, so proposal might have moved. Okay, great. If it has moved, then very well. I don't think any action is needed on side if he has already created the PR. 
* And for details, please check out the Hackmd or the EIP is inside website. Both links are added to the agenda. 

# PEEPanEIP [21.32](https://youtu.be/cF7VWr0M6XE?t=1292)
* Moving on to PEEPanEIP, we have multiple talks on Deneb  lined up for the, next week, I mean next few weeks. Of course, it's not just one. So tomorrow we are going to have, EIP 7045, but Danny Ryan and after that we will have 6780 self-destruct only in the same transaction. 
* This proposal is also up for, Deneb  and the talk is organized with ILLA on August 2nd, 4788, which is like recently added to the specs. It's a beacon block route in the evm and it would be explained by Alex Sto, who is the author of the proposal on August 8th. There are furthermore on Deneb  testing and the, new Testnet Holisky Testnet, that will perhaps replace the Gourley testnet. 
* So we are expecting launch of Hoki somewhere on 15th September because that is our Merge day and people found that it would be really interesting to have a launch of another Testnet public Testnet on the March day. updates on the development of this Testnet is also discussed on, the coder meeting.
* So if you want to follow it closely, please check out the notes left by Parithosh and the highlights provided by him on the coder meeting. 
* If there is anything else that you would like to learn about the upcoming upgrade and you think it would be helpful for you to maybe as a node operator, you would, learn how to run it and how to make sure that nothing is gonna break at the time of upgrade, please let us know. 
* I'll be happy to invite the, developers to explain that proposal or the concept for you so it becomes easier for you to participate in here. 

# Meeting notes and action items for ECH [23.28](https://youtu.be/cF7VWr0M6XE?t=1408)
* Other than that, we have meeting notes. I see we have meeting notes for every meeting except for EIPIP #85 and the Ethereum Cat Herders 112. Okay, I'm gonna have to follow up with these resources to make sure those are submitted as soon as possible. But for other meetings, like all core dev execution, notes for 165 is available. All core dev for consensus notes for 113 is also available. 
* We do organize e aap editing office hour, every other Tuesday. So if not this Tuesday, it has to be on the next Tuesday. But the time is 1500 UTC. All new EIP authors are invited to join us and, ask your question with the editor. it's a very interactive process, like any kind of question related to process or what is blocking your pull request to get merged. And the in the folder, you may ask everything, from the editor Samuel, but if there are any change with respect to a proposal which are already in final, this meeting will not be helpful.
* Today. I was approached by an author that they have submitted the proposal and it has moved to final, but they want to make small changes for authors who want to make small changes to the final EIP. First of all, this is not, a good practice to have. We don't encourage, this kind of practice, but if the changes are very small and it's not affecting the original spec, which was documented as a standard, perhaps there are chances that it may get, updated.
* But for that it would require more than one editor's approval and we would like to discuss that in EIPIP meeting. So please find which one, which meeting is best for you so you can show up and explain your part and let editors decide what to be done with that.

# 5. New initiative/association [25.22](https://youtu.be/cF7VWr0M6XE?t=1522)
* Moving on, the next return is new initiative and association. So yeah, as we mentioned in the last meeting, we are working on the, Twitter thing. Like we are hoping to have more Twitter reach and increase on social media outlook, outreach. 
* Santhosh is not in today, so I'm not sure if I have more updates on that. We may perhaps hold and have it in the next meeting. But, if people have any new idea for community engagement, please feel free. 
* Either you can drop a comment in this agenda or reach out to me. We'll be happy to discuss in the next meeting. And I think that's all that has been concluded, for the, that has been added for the meeting today. Anyone has anything to add? Share. 
* All right, I think it was great. We wrapped it on time here. Thank you so much James, for joining and explaining thanks to us. We hope to send some more people towards you so you can, send the appropriate and thank you William George joining for today. Yeah, thank you for having me. You're very welcome. All right, see you guys in next two weeks. Have a great one, everyone. 


----
# Attendee
* Pooja Ranjan 
* Edson ayllon
* George
* JA
* James

----
# Next meeting [Aug 01, 2023 at 14:00 UTC](https://github.com/ethereum-cat-herders/PM/issues/364)

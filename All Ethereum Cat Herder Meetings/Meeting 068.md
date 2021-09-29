### ECH Meeting #68 Notes
Meeting Date/Time: Sep 28, 2021, at 15:00 UTC

Meeting Duration: ~0.5 hours

[Agenda](https://github.com/ethereum-cat-herders/PM/issues/230)

Recording of the Meeting: https://www.youtube.com/watch?v=xx1TgBsNoB0

Moderator: Pooja Ranjan

Notes: George Hervey

---
##  DECISION/ACTION ITEMS

**DECISION 68.1**: Alita will focus on adding simple features and more bug fixes in eth-bot.

**DECISION 68.2**: Ken & Pooja will coordinate for DefiCon2022. 

**DECISION 68.3**: Pooja will organize another new joiners meeting. 

---


## New users on ECH Discord and/or contributor's introduction

Pooja: Welcome to Ethereum Cat Herders meeting #68 and I shared the agenda in chat. For people watching on YouTube, you may find the agenda and the description section of this YouTube meeting notes. Before we get into the agenda, we have one new member joining in on the call today. George. George, if you would like to go ahead and introduce yourself.

George: Yeah, sure. Hi everybody. My name's George. I'm a full-stack blockchain developer, working on solidity and doing a lot of dApps and getting more into the protocol level as well. I'm excited to get more involved with cat herders and the entire Ethereum ecosystem as a whole. 

Pooja: Thank you so much, George. Excited to have you. Sorry. I think I promised to introduce you to William. Unfortunately he could not join the call today, but I'm sure he's going to hear this recording and we'll get in touch with you, but thank you anyway for joining us today. So let's get into the agenda for today.

# 1. Altair upgrade

*Summary*
- Expecting upgrade to Mainnet on October 27th (~10:56 UTC)
- Public announcement from Ethereum Foundation blogpost expect around October 4th.
- Validator nodes should expect to update their beacon chain client on first week of October

Pooja: The first item here is Altair upgrade. Altair is the first big on chain upgrade, which we are expecting very soon. It is already activated on a Testnet and we are expecting the mainnet upgrade on October 27th, about a month from now. The epoch number is 74240. We are expecting this somewhere around the 10:56 UTC.

The team tried to get a palindromic epoch like 74247, but because of some technical reasons, we could not get that as the first upgrade. The finalized epoch is 74240. Users running validator nodes may expect the client release for mainnet for Altair this week. There would be an Ethereum foundation blog post coming out as a public announcement. We could expect that somewhere on October 4th. That's all about the Altair upgrade. People who are running nodes, please plan to update your beacon chain client in the first week of October. 

# 2. ECH updates

Pooja: Next item on the agenda is the ECH updates. We have a few people looking after different tasks. In this section, we try to get the updates from people like what they did in the past two weeks. 

### ECH website updating

*Summary*
- Removed “.html” from URL for most pages
- Updated EIP resources and pages
- Added links to resources
- Other bug fixes

Pooja: And let's start from ECH website updating. 

Unfortunately, I do not see anyone on the call for this, but I think I had some updates on that side. In the past two weeks, we worked to close a handful of open issues. The noticeable changes are now: the “.html” from the address bar has been removed from most of the pages, we updated some EIP resources, pages, and added links to resources, such as Verkle Tree, Merge EIP 3675, the consensus upgrade proposal and other bug fixings were done. We are looking to add more information on the March side. 

If you're aware of any resources that you would think would be useful for people to follow along, you can just create an issue on the GitHub repository for the ECH website and the website support team will be picking it up from there and add that to our resources. 

That's on the ECH website. I know we have a few technical people. Also, if you are comfortable, you can simply create a pull request as well. If not, you can drop us an email at support@ethereumcatherders.com.

### ECH engineering

*Summary*
- Fixed bugs and arguments for EIP bot
- Will focus on adding simple features and more bug fixes

Pooja: Going on to ECH engineering, Alita is looking after the ECH engineering task and you can find the issue added to the PM repository. Other than that, mostly what we worked on was working on EIP bot, fixing up some of the arguments for bots. We can move the proposals to the right statuses. 

Later in the call (at around 16 minutes in call)
Pooja: I see someone joining it. Alita from the ECH engineering. Alita, I don't know if you would like to talk about it. I just have provided an overview of some of the work that you are working on, but is there anything specific you would like to mention?

Alita: No, I mean, it's just kind of a continued work. Moving forward, I think my primary focus, I mean, at this point hopefully the stagnant bot is done for awhile. My primary focus is just going to be implementing some easy features and fixing bugs, for the next meeting on the main EIP bot on a merger. 

Pooja: Right. That sounds good. Yeah. I see 80, 85 proposals, I think. 88 EIPs have been moved to stagnant. Some of this, some of them may be revived to other statuses later on, but we'll look into that in the coming weeks. But I think the bot did a great job moving them to stagnant so we have a clear picture of what are the active proposals now. Thank you so much for that.

Alita: Yeah, of course.

### Cat blazers

*This section was skipped.*

Pooja: I'm going to talk about it in the later part about cat blazers. I don't see William on the call, so we can skip this for this time.

### EIP Insight

*Summary*
- Over 80 EIPs moving to stagnant status
- 9 new proposals coming up

Pooja: Moving on to EIP insight. So, as I was mentioning the bot, they have made a lot of pull requests to move EIPs, which were not having much interaction. They were not active for a while. It was a six month period of time. So, we have over 80 EIPs moving to stagnant status, which is not good, but we would like to review these proposals later on. For now, the idea is to clear up the statuses. We want to provide users with the right proposals, which are actually a standard and that can be used in different projects. We are trying to move proposals to the right statuses. I have started this monthly bulletin on EIP insights. 

The link is provided in the agenda. According to this, so far in the month of September, we have nine new proposals coming up. There is one change like one proposal was moved from a networking category to the core category. There are many other proposals which moved their statuses. All the details are available in this EIP insight.

### Peep an EIP - Upcoming meetings can be found on PEEPanEIP schedule
	New one for beacon chain on September 29, 2021 scheduled at 18:30 UTC
	

Pooja: Next one is a Peep an EIP. We are going to have one Peep an EIP meeting today that is scheduled for beacon chain metrics and benchmarking with Leo and Parithosh. That is scheduled at 18:30 UTC. I would like to invite people with more ideas or more topics that they would like to hear in Peep an EIP. We'll try to get authors and developers and researchers working on the topic to make that information available for you.

### Meeting notes and action items for ECH

*Summary*
- Notes for All Core Dev meeting #122 is available.
- Notes for Consensus meeting #73 are coming soon.
- Notes for EIP Improvement Process meeting 41 are coming soon.

Pooja: The last one here is meeting notes. We have All Core Dev meeting #122 available. That is merged, I believe. For Consensus meeting #73 and EIPIP meeting #41, we would be expecting the notes going up very soon. That's all from the ECH update side.

# 3. New ideas - brainstorming

*Summary*
- How to incentivize EIP authors for pursuing proposals
- Give a reward via NFT or tip for authors
- Open to other ideas
- Volunteers are welcome to help with this initiative
	
Pooja: Moving on to the next item on the agenda, it's about new ideas and brainstorming. In the past two weeks, I had a few one-on-one meetings with new people running in. And one of them of course is George who has joined today, and you will be documenting the notes for today's meeting. Thank you, George. I had another meeting with Alchemy NFT team. It's about NFTs for EIP authors. 

We were just discussing about how we can incentivize EIP authors to pursue with their proposals if they think that it is good for Ethereum to become a standard so others can use that. We were just discussing some ideas that can motivate them. One of those were, how about, providing the EIP authors who finish their EIPs, like in final status, with some kind of NFT or some kind of reward or some kind of tip? 

I don't know. I'm just sharing what we discussed the other time. This was inspired by EDCON conference that happened, I think, a few days ago. The team from the alchemy NFT, they actually provided an autograph NFT to every speaker, which is also added to virtual event board. 

It was just a simple gesture of appreciation and for people to know that these people were the participants of EDCON speakers. We're thinking if something similar can be done for EIP authors. We can add some tip, as low as 0.05 ETH, maybe to just cover the transaction cost of minting that NFT or something like that. Or if we would like to get more, we can have some Gitcoin grant or some separate idea that is something to be decided later on. But I'll be curious to hear thoughts of participants on this call. What do they think if they have any other suggestions to encourage EIP authors to move their proposals to final status? 

Brent: Sounds like a good idea. Just NFT. That sounds like a good idea. 

Pooja: Yeah. Like I mentioned, this is in very early stages of discussion. And, I would like to discuss with a few more people. I have a call this week to talk more about it. And, maybe I will try to get some volunteers here who are good. Like we did for the London upgrade. I know we had this community contributor who worked for minting of the NFTs for London upgrade and distribution and all. If anyone is interested in volunteering for this job, or look after working with the team, please reach out to me. 

We have this very interesting comment on that chat. I don't know. Would you like to speak for yourself Joshua? If you have a microphone, of course. 

Okay. So I'm gonna read the text. Yes. It says it, 

“I like the idea. To play devil’s advocate we might want to worry about having the right incentives (i.e. we don’t want people pushing half-hearted EIPs to get NFTs)

“I actually don’t think it will be an issue because the bar to submit an EIP is already technically quite high.”		- Joshua Douglas (from chat)

Of course, that is something that needs to be taken care of. We have good editors here who are doing their job diligently. We are so proud that in this month we have worked a lot. I mean, if you look at EIP insight, you'll realize that a lot of work has been put into and more proposals are getting shipped. So yes, we just want to incentivize. Of course we'll take care of that. The standard must meet the standards of Ethereum blockchain. Thank you for your comment.

For people listening to this call, I just want to mention that this section I have added in biweekly cat herders meeting just to invite people to come and share more thoughts. If there is any initiative that you think you would like to do for the Ethereum ecosystem, and you might want some support from cat herders, please reach out to us on the ECH discord and we'll try to help you as much as possible.
	
# 4. Events & Hackathon

*Summary*
- ETHOnline - Sep 17 - Oct 15, 2021
- ETH Atlanta - October 1 - October 3, 2021
- Liscon - October 20-21, 2021
- hackCBS 4.0 - October 29th-31st, 2021

Pooja: Moving on. The next section is events and hackathons. In the past two weeks, there're quite a few blockchain events. I spoke at Meta Gamma Delta, introduced the cat herders, like the basics of what cat herders are and what do we do and where to reach out. Other than that, we spoke at the Messari Mainnet conference and there was this Wyoming hackathon. Edson from the cat herders was also in New York at the mainnet event. Thank you Edson for representing the cat herders there. 

I was participating virtually, but I'm happy to see that we inspired some of the people there. And we have some users joined in the cat herders discord, post-doctor even. Thank you, new people for joining in. I hope you will find a way to contribute. If you have any questions or concerns or any suggestion for us that is going to be useful for a larger community, please share with us. In the coming week, there are quite a few hackathons planned. One is ETHOnline, which is actually ongoing, and we expect it to be till October 15th. There are few more like ETH Atlanta starting from October 1st to October 3rd. It's just an even then, it's a good, what we can say that people, we are going to have good speakers there. Follow the website, the link is provided in the agenda. 

There are a couple of more coming up. One is Liscon. This is more closer to Devcon. And, the other one hackCBS 4.0, is organized by students from India. This is their first student-led hackathon. If you are interested to participate, please check out the #hackathon channel on Ethereum Cat Herder's discord.

# 5. ECH funding

*Summary*
- Funding via ESP, Gitcoin, CLR & Moloch
- Received contributions from 532 participants and most amount in 2021
- Received airdrop of 508 BRIGHT tokens from the BrightID team

Pooja: Moving on about the ECH funding. I want to time all the 500+ Gitcoin contributors. In this Q3 for 2021, we received the contributions from 532 users. This was the highest participant so far in 2021. In addition to that, there was an airdrop of BRIGHT tokens. We have received 508 BRIGHT tokens, so thank you, BrightID team.

# 6. Discuss and close the ECH GitHub Issues/PRs

*Summary*
- ethereum-cat-herders/PM: No new issues
- ethereum-cat-herders/funding: Some open issues will be closed this week

Pooja: And right. We are very close to the end of the agenda that is just to discuss and close the CHP issues and pull requests. Just want to open this floor for now. Anyone, if they have anything to share or talk about. 

Looking into the PM issues, we do not have any new issues. However, you can always follow what the Ethereum Cat Herders engineering team is doing. We have an issue created for that. If you would like to add some ideas, feel free to share with us. In the funding sections, there are some open issues. I'll try to close them this week.

# 7. Review of outstanding action items from previous ECH meetings

*Summary*
- Reach out and send info for meeting with new members
- Community building led by Kenneth Luster
- Plan to get approval done for open funding request by end of this week

Pooja: Moving on to the last item of the agenda, review of outstanding action items. So we don't have- okay, just one. Alright. Yeah, I'm supposed to plan when more newcomers meeting to engage more participation. We have received quite a few new forms. We have to reach out to those people. We'll try to plan one meeting coming Monday. 

I will send out the information for this new joiners meeting very soon. And, yeah, the other thing was like a community building. I know Ken is already working on that. I'll be helping out with that too. 

So, that's all about it for the cat herders updates. Yeah. Anyone have any final thoughts? 

Alita: There's some open funding requests. Is that something we're going to be doing soon? 

Pooja: Yeah, I think I'm going to do it. I mean, at least I will initiate it by today or tomorrow. I know a few people are on vacation, so it might take some time, but we'll try to get it done before the end of this week, to the second approval because most of them are on vacation. 

Okay. Yeah. There is this another comment by Ken:
“Yes. We have to meet with the organizer of DefiCon 2022.”  - Kenneth Luster

Okay. I'm going to talk to you offline about that. We can plan it like on this Friday or maybe, coming Monday or the coming week, whatever works for you. We'll get it done, too. Thank you for reminding, Ken. 

Yeah. So thank you all for joining us. I'm happy to see a few new faces here at the meeting today, and I hope to have listened to the new ideas and suggestions and people joining us. Thank you so much. Have a good one, everyone. 

*- End of Call -*

# Attendees (8 in Total)

Pooja

Brent

Kenneth

Alita

George

Joshua

*Apologies for missing name of others who were in attendance*

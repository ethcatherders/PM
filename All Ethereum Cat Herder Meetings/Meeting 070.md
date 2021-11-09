# ECH Meeting 70 Notes
## Meeting Date/Time: Tuesday 28 October at 15:00 UTC
### Meeting Duration: 0.5 hour
### [GitHub Agenda Page](https://github.com/ethereum-cat-herders/PM/issues/242)
### [Audio/Video of the meeting](https://youtu.be/XaDj6b9GuiA)
### Moderator: Pooja Ranjan
### Notes: Jim Bennett

----
## DECISION ITEMS

**DECISION 70.1**: Add DEGEN bot to the ECH Discord server.[see 17:07](https://youtu.be/XaDj6b9GuiA?t=1603)

**DECISION 70.2**: Submit the grant proposal for the next round of Moloch DAO funding. [see 26:43](https://youtu.be/XaDj6b9GuiA?t=1603)

----

## AGENDA

**Pooja Ranjan**
Alright, let's go ahead and start. Good morning everyone. This is Ethereum Cat Herders meeting 70. I just have added [the agenda](https://github.com/ethereum-cat-herders/PM/issues/242) to the chat.

# 1. [Network Upgrade](https://youtu.be/XaDj6b9GuiA)

The first item listed here is Network Upgrade. So first we'll talk about Altair, which is expected in less than 24 hours. As we mentioned earlier, it's expected on block 74240 at 10:56 AM UTC. As per node watch.io, about 71% of nodes are already in sync and ready for an upgrade, yet we have less than 30% to be updated. So if you're a validator and listening to this recording, please upgrade your node now. Information on the upgrade ready client version for your upgrade is available on the Ethereum Cat Herders website as well as on the EM blocks. Tomorrow, the Ethereum stakers community are organizing a livestream party. We hope to be there to represent Cat Herders. And they have also shared some instructions on how to upgrade. So watch for the blog post and check out the EthStake on YouTube. And the next to upgrade that we will be expecting before the end of this year is Arrow Glacier. We shared some detail in the last meeting. And since the last meeting, there have been some changes. The proposal is still 4345. But the difficulty bomb adjustment has been moved to June 2022. Earlier it was supposed to be pushed 1.5 million blocks, but now it is 1.7. And TJ Rush has been added as quarter for the proposal. So the upgrade is expected on December 8, and is planned on 13,773,000 block number. So that's all about the upgrades that we are expecting in execution layer and consensus layer chain. I'm using these terms, because very soon we'll be having merge. So we already have listed here the merge Amphora testnet, some information around the Pithos testnet that's been activated on October 14. So Amphora Client Milestone Tracker has been shared by Trenton. It's coming up from the interop workshop that happened earlier this month in Greece. And Pithos is the M5, the fifth milestone for the Amphora testnet. There is this guide for people who are interested to set up a validator for Ethereum staking on Pithos testlet. It is shared by CoinCashew. I suppose [the link](https://www.coincashew.com/coins/overview-eth/guide-or-how-to-setup-a-validator-for-ethereum-staking-on-pithos-testnet-in-10-minutes-or-less) is added to the agenda. So if anyone is interested, please give it a try.

That's all on the upgrade side. Anyone have any question or comment to be added here?

# 2. [ECH Updates](https://youtu.be/XaDj6b9GuiA?t=208)
Alright, in that case, we'll move on to the next item listed here. It's the Cat Herders update. The first one is [ECH website](https://github.com/ethereum-cat-herders/ech-website-v2/issues). So we have updated the Cat Herders website with the information related to Altair upgrade and Arrow Glacier. We have added a couple of resources where people can follow these upgrades and learn more about it. A few hours of downtime were reported last week. The website was back up in less than 24 hours, so it was not gone for very long. Small bug fixes were done. And currently, we are having the version 1.4.0 with all the recent updates.

Alright, so the next one is [ECH engineering](https://github.com/ethereum-cat-herders/PM/issues/231). I see Alita Moore on the call - over to you, Alita.

**Alita Moore**
Hey, so since the last time, I have solved several bugs, and I'm still working on solving some stuff, and it's just kind of moving steady. So there's not much of an update, other than moving forward and continuing with bug fixes and starting to implement some of these features.

**Pooja Ranjan**
Awesome, and I see that the bot has been added to the issue section of the EIP GitHub.

**Alita Moore**
Yes. Okay. So in the past In two weeks, I added the bot issue section - super easy, by the way -  but anyway, yes, that's done, it should be done. And then there's now the ability to set custom authors based off of the EIP type.

**Pooja Ranjan**
Awesome. All right. The next one is Cat Blazers. William just mentioned that he is running late, so maybe he'll join in the later half of this meeting. We'll come back to it later on.

And the next one is [EIP insight](https://hackmd.io/@poojaranjan/EthereumImprovementProposalsInsight). So, so far, in the month of October, 115 EIPs have been moved to Stagnant by the bot. three proposals have been introduced as Draft, two are moved to Review. And there is this one proposal, EIP 3076, that is Slashing Protection Interchange Format. That is a proposal which is coming from the beacon chain. Earlier, it was in the Core category. But now that has been moved to interface, because it is not directly a part of any upgrade. It's not directly a Core category. This proposal has been moved to Last Call. And we saw that one of the proposals, EIP 1523, has been resuscitated from the Stagnant status. The author is trying to push the proposal forward. There are some other non-normative changes and improvements made to the existing EIPs. One of the noticeable updates is to update the list of EIP editors. So we did one round of updating. We made an Emeritus Editor section, they moved some of the editors there, but I believe this needs more pruning. We are discussing this on EIP GitHub issue number 4368. Actually, it's not an issue, it's a pull request that we created for the first pruning. And we are expecting to update this list with more it will be moving into the Emeritus EIP Editors list. So that's all about EIPs insight.

Moving on to [Peep an EIP](https://www.youtube.com/playlist?list=PL4cwHXAawZxqu0PKKyMzG_3BJV_xZTi1F), in the upcoming meetings of the Peep an EIP, we are expecting the executable specs with Sam Wilson on November 2, a technical deep dive with Piper Mirriam on November 10. And we'll have some information on Pithos and Merge testnet with Santhosh on December 8. Yesterday, we recorded our 50th episode of Peep an EIP. I couldn't believe we came so far. So it was really great that we experienced a lot of information exchange during this one year. And we're so grateful for the Ethereum community to receive this information very well. Yesterday, the conversation was with Paul from Lighthouse. We recorded this episode on Merge and what the chains would look like post merge, like thinking post merge. He explained the architecture really well.  I can't wait to see this recording going public, Hopefully it will be available by early next week. That's all on the Peep an EIP.

And on [meeting notes](https://docs.google.com/spreadsheets/d/1axM1KaKc-GCcoPbAnYTOhgLnxXsBVoO5XRjTN3CLnck/edit#gid=0), so far, we have meeting notes for All Core Dev meeting 124. We do not see notes up for consensus meeting 74 or the EIPIP meeting. I don't know anyone present here from the group, if they have any further information when we can expect the notes?

**George Hervey**
Yeah, I'm almost done with the consensus notes. I'm sorry for the holdup. It should be done by the end of today or tomorrow.

**Pooja Ranjan**
All right, no problem. Thanks for the update. And about the EIPIP meeting, I think there was something wrong with the recording. The recording did not show the names of the speakers. So the resource shared it with me to just make sure that the speakers names are correct. We have approved it, and I think that we can expect the notes up by today, end of the day I suppose. So that's all from the listed overview of the Cat Herders tasks and responsibilities that we have been doing. Anyone else want to share something here?

**Brent Allsop**
Just a quick question  - that video you've talked about. So I wasn't listening completely, but it's a video about the your said that's going to go up this week. And it's about post merge stuff like that? Anyway, I'd like to get a ping, I wonder if you could post to the Cat Herders channel when that goes up or direct message me or something, because I'd like to see that when that goes up.

**Pooja Ranjan**
That's right. So I was talking about a Peep an EIP recorded with Paul. And I hope to see this video going up early next week, maybe Monday. In the meanwhile, we'll try to make some small clips, because he had demoed it really well. And I'm hoping that it's going to be helpful for people who are trying to understand what's going on with two chains of Ethereum and how they are connected or not connected. So it's a good watch. And if people can subscribe to [Ethereum Cat Herders YouTube](https://www.youtube.com/channel/UCD9iiIwTRtLDYcEWONs2Q3A), there will be a notification going out every time we upload a new video.

**Brent Allsop**
Okay, yeah, thanks.

**Pooja Ranjan**
Alright, so that's on the update side.

# 3. [New ideas - brainstorming](https://www.youtube.com/channel/UCD9iiIwTRtLDYcEWONs2Q3A)

The next section is about new ideas and brainstorming. Open Ethereum client support is the first topic listed here. So we have been informed that the Mycelium research team is considering supporting the Open Ethereum for short term. I suppose Brayton, who dropped a message on the ECH Discord team that they might look for some help and guidelines to continue supporting -  Drayton, over to you to speak more on that. What kind of support are you looking at, and how can it be supported for the company?

**Spore_Druid_Bay**
Yes, the first step would be that we just submit a PR, and then we'll try to test out to see whether we could support - I think it's 3634. Or maybe it's 3436, the expanded click rules just to see whether or not we're cut out for it, essentially. And then if that goes ahead, and we're able to do that, then I think we'd be probably in a position where - we just sort of want to suss out and also receive advice as to how large of an undertaking it would be. It wouldn't be too bad in our eyes if we were to just push Arrow Glacier forward for Open Ethereum and then after that, it's deprecated rather than being deprecated after London. I'm not sure whether this is a social taboo as well, in the sense of, like, it was previously scheduled to die, but at the same time, a fairly large portion of the network is still on there. So that's just sort of our line of thinking as well. But then in terms of further ongoing support, it would really just be contingent on the extent to which it is a very large undertaking, which it seems to be naturally but at the same time, I think we might be able to do it. So yeah, we'd definitely be very receptive to advice in terms of what it really takes to essentially maintain a client for future layers. So what's one question for a merge interop -  is that the kind of thing where there's minimal execution client changes to make versus - and we will have time to be able to catch up so that yet for the next feature fork for Shanghai, we would actually be able to make changes in time for that versus if it's almost too late, in some sense, to be able to support the merge would be another question.

**Pooja Ranjan**
So as per my understanding, I believe that team was supporting until the Arrow Glacier upgrade, but there is no information on how to support with the merge part. I don't know, Tim, if you may have any information.

**Tim Beiko**
Sorry, what team is that, exactly?

**Spore_Druid_Bay**
Oh, yeah, so that's called Mycelium. Mycelium is essentially an Australian based company. We've got an office in Brisbane, at least, but a few around other spots. And yeah, we've just got a couple of Rust devs that had sort of put up their hand and thought that they might be able to do it, but we're not really too sure, just the scale of the endeavor and to support open Ethereum to see what it would take in some sense.

**Tim Beiko**
My short answer is it's probably months of engineering, just because maybe doing the merge spec itself is a few weeks, but there's a lot of technical depth in Open Ethereum. I think a lot of things probably break at the networking level. So I'd say yeah, months is like the right order of magnitude. It's not going to be, like, a few weeks to get it in a good spot.

**Spore_Druid_Bay**
In terms of people months, would it be, say, just like a couple of experienced Rust devs would probably good, yeah?

**Tim Beiko**
Yeah, exactly. If I had to plan for it, I would assume a couple of experienced devs work on it for a quarter or something, and you kind of see where you get. Yeah. And I think that the challenge is also then you can probably have minimal merge support, but then there's a lot of bugs, and the list of bugs is growing. So I think you're kind of signing up to also just improve the overall quality of the codebase and at least stop it from degrading. And I suspect that's the actual hard part rather than just implement the merge spec.

**Spore_Druid_Bay**
Yeah, that makes sense. Do you think it's a fool's errand in some sense to support Arrow Glacier if you're not intending to maintain long term?

**Tim Beiko**
I think Arrow Glacier is fine. It's literally a two-line change, right? Like one line in the code, one line in the tests. So I can see value in that. But for the merge, it's a much bigger effort. I think you can get Arrow Glacier done in less than a week with one person if they're not familiar with the codebase, but they are a senior kind of Rust engineer.

**Spore_Druid_Bay**
Yeah, that was definitely our impression. The question was really just whether or not it's worth just killing or deprecating OE first, versus to continue. But yes, we'll keep going with Arrow Glacier, then, if that's all cool with everyone.

**Tim Beiko**
Yeah, I think that's valuable. The thing is, with the merge anyway, like, you need to change your infrastructure and all that, you know, like, if you're running, you need to run a consensus client, so there's going to be a lot of changes around the merge with Arrow Glacier. Realistically, if you're using Open Ethereum today, you should be able to just do that change, and it'll kind of keep chugging along. So I think there's probably a value in that. So I would suggest going for that.

**Spore_Druid_Bay**
Beautiful. I'll get back to everyone as well on any updates.

**Pooja Ranjan**

Awesome, thank you. Moving on.

The next sub item listed here is adding DEGEN bot to the ECH Discord server. So I had a chat with a Bankless DAO community member  - thanks to Kenneth for introducing - and the proposal here is to invite the DEGEN bot to the Cat Herders server. As per my understanding, the POAP team is planning to phase out the POAP bot. And this Bankless DAO team is working closely with Michael and rest of the POAP team on this, and they are trying to whitelist some of the server who are already using the POAP bot. And we are. We did use it for one of the earlier network upgrades community calls. So the idea here was to add the DEGEN bot. And this is just a way to increase the collaboration. I wanted to share with this group and see if there are any thoughts or concerns before we go ahead and add this bot.

Well, I was hoping for the member to join today, but it looks looks like it's very early for him here. So I'm keeping this option open. But if there is any concern, please reach out to me and let me know, or Ken, and we'll try to look into that. And if there is no concern, we can go ahead and invite the bot. The team would be around to provide any support and setup of this and hopefully, this should not be any any trouble to any of the existing channels or anything.

Moving on, the next one is NFT for EIP authors. So we propose that to create NFT for final EIPs. So unfortunately, I could not hear back from the Alchemy team on this, so there is no progress on building and deploying the NFT as such. We have been approached by another team. It's led by one of the consensus members. They are working on NFT and DAO space and they are looking for some collaboration with Cat Herders. I am yet to receive more documents on that. And we will be updating if we get to have any progress on that side. I'm open for any of the groups to work on that. Now currently Alita and William aren't there who showed interest to work on any of these NFT projects that that we are planning from the Cat Herders side. If anyone else is interested, do let me know. And if anyone thinks that they can help designing and deploying the NFT on their own and help out with this particular task that we are planning for, please feel free to reach us.

That's on the third item, the New Ideas and Brainstorming. Before we jump into the next one, Events and Hackathon, I see William Sharp has joined. William, if you would like to talk about the Cat Blazers or the new initiatives, anything. We can come back after going to the Events and Hackathon. But if he would like to go ahead before that.

**William Schwab**
I could do that right now. Sure. The primary focus of the last couple of weeks has still been onboarding. There are a number of people, I don't know the count off the top of my head right now who I've been speaking with, either through EthernaughtDAO, through GitCoin Colonel, independently. And I feel like there might have been something else that was funneling to me a little bit, not recalling what right now. There are also a couple of initiatives that I have been working on. So Pooja and I have been working on trying to create a spinoff in the Peep an EIP series. So we're putting in some work on that, as we mentioned briefly in the last call, and we're hoping we'll be able to start working on that probably in early November. There's also another EIP ERC involvement initiative that we've been putting in some initial work on which I could give more details on a bit later, maybe put in an article. And that has been my personal focus of the last couple of weeks.

**Pooja Ranjan**
Thank you. So that was on the updates on the Cat Balzers and William's side. We have have been helping out some of the new people who we have recently met through the community calls, helping out with the onboarding on EIP Editors interns program as well. So if anyone is listening and interested to be a future EIP editor or want to contribute on any of the EIP editing side, please reach out to William or me. We are happy to engage you here.

# 4. [Events and Hackathon](https://youtu.be/XaDj6b9GuiA?t=1368)

Moving on to Events and Hackathon. Last week, Ken and Jamil from ETH Builders NYC and Blockchain New York, we had this community call with the Ethereum Cat Herders community call where we went through the EIPs, the process, and what's coming up with Ethereum network upgrade. It was a great meetup. Thank you, Ken, for organizing all that. It has good resources on the EIP process side and people who are interested to contribute as an author or just as a developer. We discussed about ERC processes. So it's [the recording of the meeting is added there](https://www.youtube.com/watch?v=d1FuHbbGJwM). I just wanted to share that if people are willing to have this kind of talk, please feel free to reach us, and thank you very much, Ken, for helping organize these meetups

**Fireflies.ai Notetaker Kenneth**
You're most welcome.

**Pooja Ranjan**
About the [hackCBS 4.0](http://www.hackcbs.tech/) we were hoping to be official community partner, but unfortunately we couldn't be. The event was totally sponsored by Polka Dot, and because of the contract, they could not partner with any other blockchain, meaning the Ethereum Cat Herders could not be the partner for that. Nonetheless, we hope to look for future collaboration, maybe next year.

**Texas**
That'll be great.

**Pooja Ranjan**
Yeah, I hope so. We try to partner with different hackathons and events to keep talking about Ethereum and let people get on board and help them get away in the Etherium community.

# 5. [ECH funding](https://youtu.be/XaDj6b9GuiA?t=1504)

Moving on to the ECH funding.

**Brent Allsop**
One quick question I have on that. Does anyone have any information further out in advance? Is there going to be a DevCon, any talk about the next DevCon, is there gonna be EthBerlin or anything like that next year? Anyone know any information about further out stuff?

**Texas**
No, I haven't heard anything just yet on that.

**Brent Allsop**
Okay, thanks for the update.

**Pooja Ranjan**
Yeah, I heard that Eth less con, that was like very close to DevCon. But yes, so there is no official information on DevCon so far.

**Brent Allsop**
Cool. Thanks for the update on that.

**Pooja Ranjan**
No problem. On ECH funding. Currently CLR.fund round eight is live. It's live for another less than 12 hours. We are participating in that. So if anyone is interested to support Cat Herders, you can donate, and the donation will be complimented with the quadratic funding. They have this special matching formula for every donation that is received by any project over there. So hurry up if you're interested to support Cat Herders, CLR.fund is running their round eight. On the second part, the Moloch DAO, we have been asked to submit the new funding request for Moloch DAO that they are planning to consider for the next round of Moloch grants that is expected in the month of November. We are yet to submit the proposal. I hope to finish up the formalities real soon. And we'll update in the next meeting.

**Brent Allsop**
Could we get some information on how to vote for those things and some links and stuff like that? Would that be good to include in the notes? I would like to have that information. And can you maybe post a link to where to go to vote for those Cat Herder funding issues? So find more information of how we might get more involved with that kind of stuff?

**Pooja Ranjan**
So if I understand correctly, Moloch has their own DAO and the members of the DAO are the only people who can vote for any proposal that is proposed there. So the first thing would be to get a membership of Moloch

**Brent Allsop**
And get some of their currency, right?

**Pooja Ranjan**
No, actually no currency. They haveshares, there's the concept of shares, but shares, they can support any project.

**Brent Allsop**
Okay, yeah, I have to study that. And but was that the first one you mentioned we could vote on or is that the only one?

**Pooja Ranjan**
Moloch is the only one in which any member of Moloch can vote. CLR fund is very similar to get GitCcin funding. It is just that we are trying to make use of whatever resourc is available to get funding for Cat Herders.

**Brent Allsop**
So is it Moloch that's doing the quadratic voting and stuff like that?

**Pooja Ranjan**
No. CLR fund is doing quadratic voting, and Moloch has their own DAO, they provide DAO decision. I'd be happy to send you some resources on that.

**Brent Allsop**
I'd like to get those include in the notes too. So yeah, thanks.

**Pooja Ranjan**
Sure.

All right, any questions so far?

# 6. [Discuss and close the ECH GitHub Issues/PRs](https://youtu.be/XaDj6b9GuiA?t=1729)

On the next item, discuss and close ECH GitHub issues, I see there are a couple of open issues. The one that has been recently posted about some help that we are looking for updating Eth 1.x and p market folders to archive, we have opened a bounty of 100 DAI for that. So anyone who is interested to work on this particular task, please respond to the issue and let us know if you have any questions. I'll be happy to help on that. Other than that, there are a couple more. I see number 238 - webpage to curate resources on the merge. I don't know, someone from the Cat Herders - George?

**George Hervey**
crazy I actually just sent me a message on Discord about it.

**Pooja Ranjan**  
I will look into that. No problem. That's it. and the third one is Rinkeby Faucet. So I see the number is 241. I see there is this proposal. Maybe they are planning to manage the Rinkeby Faucet, and I don't know if people have any question comments, or they know who is managing. The feeling that I get from there is that there are projects who are planning to use Rinkeby test Ether, but they are unfortunately not getting any help in this direction. I don't know anyone from the CoreDev team. So maybe, Tim, if you are aware of how Rinkeby Faucet is managed? I don't know.

**Tim Beiko**
So the Rinkeby Faucet is managed by Peter, basically. I think he shared on Twitter that he doesn't want to give like tons of Rinkeby Eth. So I think if people want a large amount of Rinkeby Eth, they should use another testnet, basically.

**Pooja Ranjan**  
Right, so I'm not sure if there is a demand of large amount of Rinkeby. My understanding was management was a concern, like if it is being managed.

**Tim Beiko**
I think so. Yeah, Geth team basically manages it.

**Pooja Ranjan**   
Maybe we can point them towards the care team.

**Tim Beiko**
Yeah Geth Discord is probably the right place for that.

**Pooja Ranjan**  
Sure. Thank you. Thank you for that. Alright, and other than that, I think we are good on the issue part on the funding section, I see one open issue. We'll try to close it by the end of this week.

# 7 [Review of outstanding action items from previous ECH meetings](https://youtu.be/XaDj6b9GuiA?t=1905)

Looking into the meeting notes from the last meeting,

* 69.1 - Add better resources for the merge in the ECH website. George is working on that. We'll come back on it later.

* 69.2 - William's podcast initiative, we did announce yesterday as well. And hopefully we'll start recording it soon.

* 69.3 - Continue NFT for EIP final status authors, I'm looking for some more help and support there. Unfortunately, we could not continue with the team we started with. But if there is someone who knows NFT well and is willing to help us design and deploy for Cat Herders, please reach us.

Alright, I think that concludes all of the items listed here. Anyone wants to bring up anything to share or discuss today? Well, in that case, thank you so much for joining. I hope to see you all in two weeks on November 9. Have a good one everyone.


# Attendees

* Alita Moore
* Brent Allsop
* Fireflies.ai Notetaker Kenneth
* George Hervey
* Jim Bennett
* Pooja Ranjan (Host)
* Santhosh
* Spore_Druid_Bay
* Texas
* Tim Beiko
* William Schwab




# Date for Next Meeting: November 9 at 1500 UTC

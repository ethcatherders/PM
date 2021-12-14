# ECH Meeting 73 Notes

**Meeting Date/Time**: Thursday, 7th December, 2021 at 15:00 UTC

**Meeting Duration**: 37 minutes, 28 seconds

**[GitHub Agenda Page](https://github.com/ethereum-cat-herders/PM/issues/250)**

**[Audio/Video of the meeting](https://www.youtube.com/watch?v=5wrplqG6V0w)**

**Moderator**: Pooja Ranjan

**Notes**: Shashank

----

## DECISIONS / ACTION ITEMS

**DECISION/ACTION ITEM 73.1**: Shubhangi will work with the team to create an Year-end ECH video.

**DECISION/ACTION ITEM 73.2**: Share [Discord incident](https://github.com/ethereum-cat-herders/PM/blob/master/DiscordIncidentReport.md) report with community.

**DECISION/ACTION ITEM 73.3**: Pooja will add "Migrating to Mirror from Medium" as one of the agenda items to be discussed in the next meeting. Suggested by William Schwab.

----

## Introductions

**Pooja Ranjan**: Welcome everyone to Ethereum Cat herders meeting 73. I just have shared agenda in the chat for people to refer to. Before we get into the agenda items, we have someone new to this call. He is generally going by *alphaK3Y* on the Discord channel. So, I would like to invite him to kind of introduce yourself to the group.

**alphaK3Y**: Yeah. Sure. So, yeah my name is Mike and I've been interested again in Ethereum. Since early this year. I started learning about on-chain data which was provided through glass node. And yeah, I've become like really interested in DeFi and like how to make that space really transparent and open and take advantage of like the the plug and play nature of DeFi. I have probably like 6 years doing like DevOps type work. I really enjoy building things for people I'm not necessarily going to be the guy that's writing the actual software. But, I... though I could do that. I prefer writing things to people's specifications and automating things. I'm just starting to dip my toes, a little bit, in machine learning. Though I feel it's kind of like not always super useful because, ultimately it's, everything is controlled by humans, right. So yeah, I'm starting out my contributions to the Ethereum project by actually having an automated way to review the Ethereum proposals (Ethereum Improvement Proposals). I was actually going through eip-1559 **[1]** this morning and I noticed that the sections that are in eip-1 **[2]** some of those are actually missing in eip-1559. So, I think there's a big opportunity to improve like sort of the workflow for capturing the Ethereum proposals and yeah I'm hoping to contribute a good amount to that.

**Pooja Ranjan**: That's pretty interesting. I have seen you being active on **Discord [3]** as well as on the github repository thank you for all your contribution.

**Brent Allsop**: Yeah, that's nice.

**Pooja Ranjan**: And we have one more participant. She is also from the attendance that we got from the EIP Apprenticeship Meeting **[4]**. Shubangi, if you would like to take the opportunity and introduce yourself.

**Shubhangi**: Hello everyone. Thank you for having me in the wonderful community. I've been interested in Ethereum for quite some time. But, I recently got... was available and I was very excited to contribute. And I've been able to help out a little bit with the eip editing. But, I'm also hoping to contribute in other non-technical areas for example, I'll be talking about the ECH year-end video, later in the meeting. And I have a background in International Law and Academics. And a few years back I used to hold meet up groups regarding blockchain and Ethereum in South Korea. And currently I'm still based in East Asia. So anyway, thank you so much for having me.

**Pooja Ranjan**: Well thank you so much for joining us. It's been great working with you in the past two weeks. I hope that we continue working together for a very very long time.

**Brent Allsop**: Yeah. Welcome. That's great.

**Shubhangi**: Thank you.

## 0. [ECH Discord Incident](https://github.com/ethereum-cat-herders/PM/blob/master/DiscordIncidentReport.md)

**Pooja Ranjan**: All right. Let's get into the agenda items. The item number zero here, because that's not something usual but it happened, it's an incident and we need to report it. So, I have added an incident report to the ECH github about what happened with our discord. So, like in summary, on friday night est time, our server got hacked and we could not get back to our server. It was late because it was friday and I wasn't aware that something like this has happened. Only late when I received notification from couple of people that, they are not able to receive... they are not able to access the server. We started looking into it. We filed the report to the discord support group and all. And the sequence of events I have described in this incident report. Thanks to many cad herders who helped set up this new discord. So now we have been interacting with each other with the help of this new server. We didn't want that community should be left out in absence of communication, especially during the upgrade time. So thank you very much to everyone who has supported and the detailed report is attached to the agenda anyone interested can go through that. If anyone has any questions please feel free to reach out to me. You can ask me now or later on too.

**William Schwab**: Have we tweeted out the incident before?

**Pooja Ranjan**: I have reported it just morning and I am preparing to report the newsletter **[5]** today. Maybe after this call or the EIP call that we have after that. And with that I'm gonna do all like sharing it with the community.

**William Schwab**: Okay. We should... Yeah we should... Sorry, I think my audio... So yeah we could talk about that.

**Pooja Ranjan**: Yeah. I'm planning to share this report in the newsletter **[5]** that will be sent out today.

## 1. Network upgrade

**Pooja Ranjan**: All right. That's about that. Moving on to the first item of the agenda that is network upgrade. So we are expecting Arrow Glacier in less than two days I can say. We have EF's blog post and the Cat Herder's blog post. I am assuming that most of us may have updated the node. Though we saw it yesterday that there were about 35% nodes those were not upgraded. So people if you are running a node and you want to be a part of the network, please upgrade the node as soon as possible. And the link to the client version that you should be upgrading to is available in the Ethereum foundation blog post. I have shared the link in this agenda.

### [Arrow Glacier](https://github.com/ethereum/execution-specs/blob/master/network-upgrades/mainnet-upgrades/arrow-glacier.md) - EF [blogpost](https://blog.ethereum.org/2021/11/10/arrow-glacier-announcement/)

**Pooja Ranjan**: The first one is arrow glacier, so Arrow Glacier is the third network upgrade plan for the proof-of-work chain of Ethereum in 2021 and the block number and the estimated time of arrival was shared in the last all code and meeting and it's expected to be on december 8th. Cat Herders have published a blog post with related information and the history of a difficulty bomb proposals that that we have seen so far the link to the blog post is added to the agenda and this network upgrade is just similar to the new glacier upgrade that was I believe in 2019 that included only one improvement proposal for pushing the difficulty bomb and even in the arrow glacier. We are going to see just one eip that is eip-4345 **[6]** difficulty bomb delay to June 2022. This will push the difficulty bomb until next summer and we hope to have another big release emerge before that. We can expect an upgrade ready client release. This week followed by an announcement blog post by the Ethereum foundation.

### The Merge - [Kintsugi](https://notes.ethereum.org/@djrtwo/kintsugi-milestones)

**Pooja Ranjan**: About The Merge - Kintsugi. Kintsugi is the latest testnet that we are having for the merge. Right now it is in the devnet stage like it's for the developers who are building the client only. But it has been recently announced that there would be a public testnet for infrastructure provider and other people who want to experiment with this new merge and that would be somewhere around 14th and 15th of the of december. It will be available. And we will have Paritosh, who is the mastermind behind all this Kintsugi the devnet..., talk about setting up the testnet. I suppose the meeting is planned on PEEP An EIP, on december 15th at 1830 UTC. So, if anyone is interested in running the merge testnet and and or participate in testing in any possible way, please reach out to paritosh or you can also join us in the meeting **[7]**. So we can have your questions get answered there.

## 2. ECH updates

### [ECH website updating](https://github.com/ethereum-cat-herders/ech-website-v2/issues)

**Pooja Ranjan**: On ECH website side we have updated with the latest link to the merge related resources. As we mentioned earlier we have a dedicated page to merge **[8]** and obviously the new discord link has also been updated on the Ethereum Cat Herder's Website.

### [ECH engineering](https://github.com/ethereum-cat-herders/PM/issues/245)

**Pooja Ranjan**: Unfortunately, I don't see anyone from the ECH engineering team so I'm going to skip it for now.

### [Cat blazers](https://medium.com/ethereum-cat-herders/catblazer-chronicles-nov-21-224cae682df3)

**Pooja Ranjan**: And we'll move on to the next sub item. It's Cat Blazers. William has recently shared Cat blazers post. William if you have any more update to share.

**William Schwab**: I don't have... Oh wait my audio... might be having... it takes a bit of time for it to kind of... But, ... like you mentioned just make a post detail over november. The one thing I mentioned there is some of the things that we might be looking for that might be able to help us. Anyone who might be able to help with podcasting like skills and like kind of the editing... and things like that, would probably be of great use to us. I know I had at least one other thing on my mind also but it's slipping right now. As always if there's anybody who has anything they'd like to contribute or anything like anyone who thinks that there might be some way that I'm able to help them feel free to reach out. My twitter and discord are on any of the posts that I've put on medium. And I think that's probably about it for me. Anything else you think I should specifically mention Pooja.

**Pooja Ranjan**: No, I think that's about it. And thanks for the great post. It provides a lot of information that what team you are working with. And if anyone is interested to contribute to that particular section, please feel free to reach out to William Schwab.

### [EIP Insight](https://hackmd.io/@poojaranjan/EthereumImprovementProposalsInsight)

**Pooja Ranjan**: The next sub item is EIP Insight. We have shared the monthly report for the month of November that is added here in the agenda link. And in december, so far, we have one new eip that is eip-4488, transaction call data gas cost reduction with total call data limit. This was introduced last week by Vitalik Buterin and it is under discussion, to be considered for upcoming upgrades. Other than that, there are a few changes to status:

- One eip, eip-1967 **[9]** has been moved to review
- eip-4345 has been moved to last call
- There are five EIPs. Those are moved to stagnant by the bot
- Two proposals are in unstagnant state the eip-634 **[10]** and eip-2569 **[11]**
- And one major change that is there for the eip-1 is removing the bibliography section from the eip-1

So in the last EIPIP meeting we discussed that it is a section that is kind of obsolete and we are not reusing the link in the document. So I have updated the text with appropriate link and finally we decided to remove this bibliography section from the eip-1. All these will be added to the EIP Insight for december. I'm hoping to publish that very soon.

### [Peep an EIP](https://www.youtube.com/playlist?list=PL4cwHXAawZxqu0PKKyMzG_3BJV_xZTi1F) - Upcoming meetings can be found on [PEEPanEIP schedule](https://github.com/ethereum-cat-herders/PM/projects/2)

**Pooja Ranjan**: Moving on to PEEP an EIP. We have quite a few *PEEP an EIP planned for the month of December*:

- The first one is a tomorrow eip-4345 difficulty bomb delay **[12]**, to June 2022. That is with Thomas J. Rush, he is the co-author and he has very well explained how we calculated the difficulty bomb in a blog post. So it would be interesting to learn more about the calculations of these difficulty bomb and why the Ethereum developer decided to push it till june than May 2022 which was like on the initial proposal.
- Following this we have "The secrets of EIP editing" with Matt Garnett on 14th December **[13]**.
- The merge testnet that I mentioned with Paritosh and proto on December 15th. And there is one another eip very important for merge that is eip-4399 **[14]** supply and difficulty opcode with random. We will be talking with Mikhail Kalinin, the author of the proposal, how that is implemented in clients.

So far anyone has any question?

### [Meeting notes](https://docs.google.com/spreadsheets/d/1axM1KaKc-GCcoPbAnYTOhgLnxXsBVoO5XRjTN3CLnck/edit#gid=0) and action items for ECH

**Pooja Ranjan**: All right. This is just the update section so I think I can keep going. We have a notes available for [All Core Dev meeting 127](https://github.com/ethereum/pm/blob/a04a823119807dc7115b344fa68827e651a6cee3/AllCoreDevs-Meetings/Meeting%20127.md) and [EIPIP meeting 45](https://github.com/ethereum-cat-herders/EIPIP/blob/09315ba72e8fbb69c8647b972d848b397ec5cdf7/meeting%20045.md). We are waiting on the notes for the Consensus Meeting 77. But I hope that we would be having it real soon. For all the resources, who are working on documenting notes, it's a gentle reminder that we would like to have the notes up and ready within the first three days of the meeting and if something is like a little longer, we expect that to have it within the first five days. So if we can make it available to community to follow along with the meetings.

### [ECH newsletter 51](https://medium.com/ethereum-cat-herders/ethereum-cat-herders-update-51-c526de9e12f6)

**Pooja Ranjan**: The ECH newsletter, I'll be sharing it right after this meeting. So it will be going into your inbox if you have already subscribed to Ethereum Cat Herders' Medium. If not then you can always find it on the Medium.

### Merge Community [Call #2](https://github.com/ethereum/pm/issues/419)

**Pooja Ranjan**: There was this merged community call last week and I am hoping to get its notes by today, end of the day.

### EIP Editor Apprenticeship Meeting

**Pooja Ranjan**: About the EIP Editor Apprenticeship Meeting, the second meeting is planned for today, right after this call. So, anyone who has been to earlier meeting and they have started contributing or they are willing to contribute and they have questions. Please join the meeting, which is right after this meeting at 1600 UTC.

### Post-Merge [MEV Breakout Room](https://github.com/ethereum/pm/issues/423) & [EIP-4444 breakout room meeting](https://github.com/ethereum/pm/issues/432)

**Pooja Ranjan**: There are a couple of breakout room announcements. All these meetings are added to Ethereum protocol calendar. So if you can subscribe to Ethereum protocol calendar these meetings will automatically be added to your google calendar as of course. In the upcoming weeks we have MEV breakout room and eip-4444 breakout room both are scheduled on thursday. That's about ECH updates, anyone else has anything to add here?

## 3. New initiatives / brainstorming

**Pooja Ranjan**: All right moving on to the next section. We have started this section to keep on adding new things, new tasks that we are undertaking or if anyone has any new suggestion.

### OpenEthereum client support

**Pooja Ranjan**: I don't know if we have anyone on the call to talk about open Ethereum client support. I see Ronin here on the call. Ronin, I don't know if you have a microphone or if you would like to provide an update on Open Ethereum Client support.

**Ronin**: Hello. Can you hear me?

**Poojan Ranjan**: Yeah we can.

**Ronin**: The latest news I got is that Igor Barinov and his crew are preparing all updates for the next few versions and up coming updates to Ethereum mainnet and to implement them into the code base. And to release further on Mac and Linux versions. The Windows versions seem to have stopped as well as all other applications which were normally bundled. But I did not have the chance to reach them personally because they they have to keep their thing with the gnosis chain. And so on and so on there's some politics behind it. I don't want to touch in and I don't have to time to get... I'm reaching out since I know that they're releasing new versions and I repeated also to offer assistance in any way but they did not respond, yet. But they know that they have also supporters from some other crew and they are about to gather and to join and to co-work. I got from both groups no recent updates but there is ongoing development with each chain with, each with xDAI and Ethereum for sure. This is what Mycelium, the other guy, from the Mycelium team told me that they want to offer support for this and they are implementing and if they have trouble I was invited to join and to review any any incoming prs and I will do as visible. We don't all don't know, how it has been continued until Igor is answering what his plans are. That's it for me.

**Poojan Ranjan**: Well, thank you so much Ronin for the updates. I am aware that OpenEthereum is being supported for the Arrow Glacier update and we have added the client version on the announcement channel. If you're running a node on OpenEthereum you can upgrade to that client version that would at least support you till this network upgrade, that we are expecting in next two days.

### ECH year end video

**Pooja Ranjan**: Moving on the next item is ECH year end video. We're trying to create a video for Ethereum cat herders. I know we have Shubhangi on the call she can talk about it.

**Shubhangi**: Hello? Can you hear me?

**Pooja Ranjan**: Yeah, we can please go ahead.

**Shubhangi**: Hi. So for the ECH year end video we have two documents that that we can use as material for the video, one is a ECH short video outline and we have some accompanying pictures and media to flush out what kind of imagery we want for the video. We have been working with the Bankless DAO, the team from Bankless DAO regarding creating a... not just this video but maybe future videos for ECH. And it seems that it's still... we haven't decided oh how to move forward with them. But in any case we want to make a short video in the next few weeks that can kind of encapsulate what ech has been doing in the past year. And we are going to look at some other some other ways in which we can maybe at least have some media content that we can publish by the first week of January. Maybe it won't be exactly a three-minute long video. But we are looking at various ways in which we can publish like a short year end media content about what ECH did this year. If anyone is interested and has the bandwidth-energy to help out with making the year end video that would be great. If you you can contact me on discord and we are talking about basically a three... a two-three minute video with most of the content material that we will use already prepared. So please if you have any ideas or you would like to contribute, please reach out to me and that would be great.

**William Schwab**: How should we have... how can we reach out to you?

**Shubhangi**: You can reach me on discord. My username is `metago`, so you can contact me on discord. And we can... I can send you the files.

**William Schwab**: Awesome! Thanks a bunch.

**Shubhangi**: Thank you

**Pooja Ranjan**: Thank you for that update.

### B-star naming

**Pooja Ranjan**: And I see the next item is B-star naming. Which I have added like in the last minute. So if you can't see it in the origin item please refresh it. I know you have been working with the team. Would you like to provide some more update on that too?

**Shubhangi**: I'm sorry are you... I can't hear you.

**Pooja Ranjan**: The B-star naming with the Ethereum foundation team that they are looking for consensus layer codename.

**Shubhangi**: ah yes I reached out to *hsiao-wei* on... and she was able to contact us and she's really interested in creating more momentum for people... people's feedback to choose a star name for merge and for later upgrades. And I'm going to do a reddit post related to that and ECH has already... I think Pooja already posted a link on twitter and she's deciding... she and... I think, Pooja we're talking about, whether we should have a POAP voting or we should have a breakout room related to discussing the final decision. And if you could get some feedback from the ech community as well if you think POAP voting is is a good way to go forward or do you think a breakout room would be better for making a decision regarding the star naming system. Oh, so that's something we're discussing right now and your input would be oh appreciated.

**Poojan Ranjan**: Thank you for that. I just have shared the Twitter link in which we have invited community participation where we can collect some names and the idea here is to go ahead with either POAP voting or the decision by the developers that's still under discussion. But if you have a name that you would want to be used as code name  for this upgrade, please add it over there.

## 4. ECH funding

**Pooja Ranjan**: All right. The next item listed here is funding.

### Funding via [Gitcoin Round 12](https://gitcoin.co/grants/782/ethereum-cat-herders-community-fund), CLR & Moloch

**Pooja Ranjan**: Gitcoin round 12 has started and we have received over 130 when I checked it was last. Let me quickly check it. Oh my god! We have received received contributions from 199 contributors. I'm so happy to see this number increasing every day. It suggests that we are loved by users in this Ethereum ecosystem. Really appreciate that and I would like to give a shout out to one specific donor, Ivan Martinez for the biggest contribution of 500 DAI. Although, for this kind of round we expect a dollar or two I mean a die or two because that helps us getting matching funds but a contribution of 500 die is great. Thank you so much Ivan for that. On the other hand, I have been working with the Moloch team for the funding for the next year and we have our proposal live on the on chain voting. Voting is active for next six days. So, if anyone listening to this meeting call is a Moloch member and they would like to support Ethereum Cat Herders, please go ahead and vote for us. That's all about funding.

## 5. Discuss and close the ECH GitHub Issues/PRs

### [ethereum-cat-herders/PM](https://github.com/ethereum-cat-herders/PM/issues) & [ethereum-cat-herders/funding](https://github.com/ethereum-cat-herders/funding/issues)

**Pooja Ranjan**: The next item is *Discuss and Close the ECH github issues and PRs*. On funding side, I believe we have finished the transaction for all the open issues so I suppose the second confirmation went through this morning. And I have to just close the issues. And on PM side I'm not sure if we have anyone new I don't think... I don't, yeah.

### Re-discussion of [ECH Discord Incident](https://github.com/ethereum-cat-herders/PM/blob/master/DiscordIncidentReport.md) with Tim

**Pooja Ranjan**: That's almost close to the end of the meeting, I see Tim Beiko joining the call. Welcome Tim. So...

**Tim Beiko**: Hey... yeah. Sorry go ahead. Yeah.

**Pooja Ranjan**: Yeah. Sorry I mean I know we wanted to discuss the incident report so I have filed this incident report just morning. And there we have described the sequence of events that took place and how we are with the new server. Last night I received a notification from the discord team that it's unfortunate but discord staff does not interfere with the individual server management and it seems like the server is deleted so there is no way to restore that. In the report I have tried to add the snapshot of like what gave us the impression that it is still online the image that I have added there was post the incidents which shows that 394 are still online. So I was in a hope that I will get it back but unfortunately it doesn't look that way. So maybe we will have to proceed in the direction of getting our users directed to the new server.

**Tim Beiko**: Yeah that makes sense. Is the incident report on the Cat Herders' Github?

**Pooja Ranjan**: That's correct. And I'm also adding that in today's newsletter I'm gonna publish a newsletter out oday and the link is added to the agenda for today.

**Tim Beiko**: Thank you.

**Pooja Ranjan**: I know this is like very unfortunate event we lost a lot of members. But I hope that with everyone's help we can spread the word out for the new discord server. And yes for security, I have enabled 2fa which I was missing bad on my part but I look forward to, you know, more improvement suggestions to make this community a safer place for all our users.

**Tim Beiko**: Yeah I think one thing I would add is like for anyone on the multisig. If you have a hardware wallet to use it because that would suck more than the discord. So yeah that's probably the other kind of low hanging fruit. Yeah.

**William Schwab**: I'm loath to mention this on a zoom call, that's being recorded, that yes I'm on a hardware wallet.

**Time Beiko**: Yeah

**Pooja Ranjan**: Thank you. Sorry you were saying something Tim.

**Tim Beiko**: No that's it. Yeah and I guess. Yeah do you have in the incident document like screenshots of like you said it was like a message a link that you clicked or something. If there's any...

**Pooja Ranjan**: No.

**Tim Beiko**: No? Okay yeah.

**Pooja Ranjan**: I mean I don't know if anyone else has it because I was just closing I was just deleting but I didn't realize until I am assuming couple of hours when I got this notification on my telegram.

**Tim Beiko**: Right. It might also just been that somebody got your password right? They... it might be that the two things are just...

**Pooja Ranjan**: Coincidence...

**Tim Beiko**: Related yeah yeah.

**Pooja Ranjan**: Either of it. Because I don't know..

**Tim Beiko**: Yeah yeah.

**Pooja Ranjan**:  I mean it's something that I couldn't have ever imagined I was running three servers and I lost all of them.

**Tim Beiko**: Oh my god! It sucks. I'm sorry.

**Pooja Ranjan**: well anyway

**Tim Beiko**: Yeah. Yeah new server I guess.

**Pooja Ranjan**: Yeah that's the new way forward. I would invite more participation as like you know active moderators  for this group I think that would be helpful. And obviously we have done the 2fa and I have other suggestions that I have received and I would like to implement them all to make it a more secure server. All right that's about it.

## 6. Review of outstanding action items from previous ECH meetings

**Pooja Ranjan**: And... moving on to the last item here.
  
### [Meeting 72](https://github.com/ethereum-cat-herders/PM/pull/251)

That's our meeting notes. I'm just trying to quickly check if we have any action item from the last meeting. I don't find that section here. But I think that would be all for today. I'll recheck the document. It was a last minute entry so I might have to review the entire notes one more time. And thank you by the way *Ken* for submitting it before the meeting. And I think that's it for today's meeting that the item those were listed on agenda.

### Anything else?

**Pooja Ranjan**: Although I see a couple of more items on the ECH discord that people were interested in discussing. Don't know if anyone has anything?

**William Schwab**: I do. I was interested in bringing up as a conversation, something I've been talking a little bit with cucho about, right now the ECH uses a Medium for our blog posts, which has I mean the useful kinds of analytics and metrics, that are useful for knowing engagement and things like that. I was wondering what level of like, what the thoughts yeah texas farmers has it. I was wondering what the thought of the thoughts of those in the ECH right now and also of the wider community that might listen to this would be about maybe moving to something more web3 centric like mirror **[15]**. Whereas, before you needed to kind of win the right race or be able to publish on mirror and while that would still be useful at the same time your publishing is now open and personally. I would like to see the ECH move more towards kind of dog fooding web3 and using web3 tools for what we can when there's not a significant disadvantage to doing so. The big concern is that we would lose analytics and the ability to kind of zone in on what's working and what isn't. But on the bright side it would be more web3. There's also the ability to release simultaneously on both or to use one as the primary. But I was really interested in kicking off a conversation about that maybe seeing where that would go.

**Tim Beiko**: I think that's a great idea. Yeah. The one thing I would recommend is not using mirror to save drafts of articles. I've... it's still a new product and I've had problems in the past where like my drafts didn't save. So I would just draft everything something else and then post it in the Medium when it's ready. Sorry, to mirror when it's ready but yeah I think that's a really really good idea.

**William Schwab**: Cool. It happens to be I have tested out the import thing like importing articles in from Medium and it actually works surprisingly. Well, I was expecting it to be a big mess. Any of my reports, the cat blazer chronicles, I've ported over so they're also in your in mirror, addition to kind of like a primary listing medium.

**Tim Beiko**: Yeah and I think if you're gonna move. Like if people agree we should move, it's probably better to just use mirror. So that like people kind of migrate there. Like you don't need to migrate the old content but like to only post the new content on mirror or something. So there's only like one official blog.

**William Schwab**: I'm all for it if the community. I jumped in to mirror, first of all I don't want like you know if Pooja doesn't want to lose the analytics or if there's other people who are worried about other parts of that. Then you know don't wanna take that away. Like I definitely don't think we should make just like make a decision right here right now. But, like I am at the very least interested in at least starting a conversation about it.

**Pooja Ranjan**: Yeah I think it makes sense. Because more people are moving towards mirror. Yeah as William, as well, described my concerns about the analytics. And if that is being taken care of or we have we are okay with it. I personally don't mind.

**William Schwab**: So I'd say let's leave it... I wouldn't want to make a decision this fast. Let's leave it for like two weeks maybe we'll revisit it in the next.

**Pooja Ranjan**: Yeah that makes sense. I can add it as a particular item so people are aware of it and they can have their due diligence done and come back. And share more thoughts on it.

**William Schwab**: Cool.

**Tim Beiko**: Yeah that seems like a good idea. Really good suggestion.

**William Schwab**: Thanks.

**Pooja Ranjan**: Indeed. Thank you so much William. All right so that is all for today I suppose. Unless anyone have to bring up anything... Well thank you everyone we have another call right on top of the hour for the EIP Apprenticeship. If you're around and interested to learn more about EIP editing please do join us over there. Thank you everyone for joining us today here.

**Brent Allsop**: Thanks... Pooja.

**Shubhangi**: Thank you.

**William Schwab**: See ya

----

### Attendees

- Pooja Ranjan
- Brent Allsop
- William Schwab
- Shubhangi
- Ronin
- Tim Beiko

### Next Call: Dec 21, 2021

### Links to resources mentioned in the discussion

[1] [eip-1559](https://github.com/ethereum/EIPs/blob/master/EIPS/eip-1559.md)

[2] [eip-1](https://github.com/ethereum/EIPs/blob/master/EIPS/eip-1.md)

[3] [ECH Discord](https://discord.io/EthCatHerders)

[4] [EIP Apprenticeship Meeting / EIP Editor Apprenticeship Meeting](https://www.youtube.com/watch?v=pgwqySjLwIs&list=PL4cwHXAawZxr020waJCI0dZAfPAW2naK1&index=4)

[5] [ECH Medium](https://medium.com/ethereum-cat-herders/ethereum-cat-herders-update-51-c526de9e12f6)

[6] [eip-4345](https://github.com/ethereum/EIPs/blob/master/EIPS/eip-4345.md)

[7] Keep an eye out for **The Merge testnets** in the [PEEP An EIP YT Playlist](https://www.youtube.com/playlist?list=PL4cwHXAawZxqu0PKKyMzG_3BJV_xZTi1F). Link to the [event details](https://github.com/ethereum-cat-herders/PM/projects/2#card-67015776)

[8] [Ethereum Merge](https://ethereumcatherders.com/the_merge/)

[9] [eip-1967](https://github.com/ethereum/EIPs/blob/master/EIPS/eip-1967.md)

[10] [eip-634](https://github.com/ethereum/EIPs/blob/master/EIPS/eip-634.md)

[11] [eip-2569](https://github.com/ethereum/EIPs/blob/master/EIPS/eip-2569.md)

[12] [PEEP An EIP for eip-4345 difficulty bomb delay](https://www.youtube.com/watch?v=qy81t7bZ-4Q&list=PL4cwHXAawZxqu0PKKyMzG_3BJV_xZTi1F&index=3)

[13] [PEEP An EIP for The secrets of EIP editing with Matt Garnett](https://github.com/ethereum-cat-herders/PM/projects/2#card-71383178)

[14] [eip-4399](https://github.com/ethereum/EIPs/blob/master/EIPS/eip-4399.md)

[15] [mirror](https://mirror.xyz/)

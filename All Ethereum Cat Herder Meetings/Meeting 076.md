# Ethereum Cat Herders Meeting 76 Notes <!-- omit in toc -->

### Meeting Date/Time: Tuesday January 18 at 15:00 UTC
### Meeting Duration: 1/2 hour
### [GitHub Agenda Page](https://github.com/ethereum-cat-herders/PM/issues/263)
### [Audio/Video of the meeting](https://youtu.be/v1G7jiTHpJ4)
### Moderator: **Pooja Ranjan**
### Notes: Jim Bennett

----
## DECISION ITEMS

**ACTION 76.1**: Anyone interested in helping with the ECH podcast should contact William Schwab[see 6:06](https://youtu.be/v1G7jiTHpJ4?t=366)

**ACTION 76.2**: Contact Shubhangi Gokhale if interested in participating in the meeting on January 27 for new community members. [see 9:33](https://youtu.be/v1G7jiTHpJ4?t=573)

**ACTION 76.3**: William Schwab to follow up with Trent on ECH Medium to Mirror. [see 18:41](https://youtu.be/v1G7jiTHpJ4?t=1121)

**ACTION 76.4**: Suggest or vote for a name for the [EL Merge Client Release Naming](https://ethereum-magicians.org/t/el-merge-client-release-naming/7928/14). [see 25:52](https://youtu.be/v1G7jiTHpJ4?t=1552)

**ACTION 76.5**: Pooja to get in touch with Jared to see about closing of JSON RPC issue. [see 29:29](https://youtu.be/v1G7jiTHpJ4?t=1769)

**Pooja Ranjan**  00:00
Welcome to Etherium Cat Herders meeting 76. Thank you, everyone, for joining us today. I see good attendance, as well as some new faces. So before we get into the agenda, I would like to invite Eric, who is here for the first time to introduce and share his thoughts with us.

**Eric/CryptoShine**  
Hey, everyone, thanks. Thanks for running this meeting, Pooja and everyone for starting this awesome community. So background of myself - I'm based in Cambridge, Massachusetts, born in New York, had been following Ethereum for a while but didn't really dive in until last summer. I used to work in trad fi. I was in investment banking. And I worked at a pretty large public equities fund where I studied and researched fintech payments, software, gaming, SAS. So it was pretty hard to avoid the topic of crypto. I decided to leave my job and do this full time. And so now I'm starting a hedge fund with a partner of mine and where I'd say we operate pretty much like a traditional hedge fund, do a lot of research. I will say the thing that we do, my partner and I, feel very strongly about is supporting the ecosystems that we invest in. And so I spend almost all my time in Ethereum. And so we're forming the fund now. And we're making a pledge in our documents and very publicly to reinvest a lot of the fees that we generate back into funding open source software and public goods. And so I'm quite active in GitCoin and initiatives like that, and funding protocol development, something I'm very passionate about. It's shocking how little funding goes into protocol development given how important it is to the success of everyone. And so I'm very much a believer and aligned with the mission that the broader Ethereum ecosystem. So - glad to be here!

**Pooja Ranjan**
Thank you so much. Happy to have you on the Discord as well as in this meeting. We hope to see you around with the other communications going on and of course, the support that protocol team may require.

## AGENDA

## 1. [Network upgrade](https://youtu.be/v1G7jiTHpJ4?t=146)

Moving on to the agenda items, I just have shared [the agenda](https://github.com/ethereum-cat-herders/PM/issues/263) in chat for people to refer to, and the first item listed here is Network upgrade. So as we all know, that we are expecting one big upgrade this year. That is [The Merge](https://ethereumcatherders.com/the_merge/), and currently Kintsugi, the first public test net is live. Some updates from [unclear], Kintsugi encountered a fuzzer bug, and the issue is that because of that, it stopped finalizing for some time. But the good news is the issue has been resolved. And it started finalizing again since last Thursday, I suppose. And there are a couple of announcements from the developers team, we could be expecting some spec changes in Kintsugi specs very soon. And also, there would be a new testnet. It's not clear yet if it will be called Kintsugi or would be with some other name. But we can expect this new testnet sometime this week. So that's on the march.  

## 2a. [ECH Updates - a. ECH website updating](https://youtu.be/v1G7jiTHpJ4?t=226)
The next item listed here is [ECH website updating](https://github.com/ethereum-cat-herders/ech-website-v2/issues). And so it looks like since the last upgrade, the website could use some updating. If anyone finds any resources that you think could be useful to the community related to anything like EIPs, upgrades, or any other research topic that you think that the community can make use of, please feel free to create an issue in the ECH website GitHub, or you can even let us know on the website update channel that is there on the ECH Discord. We have a team that can pick it up and maybe add the resource.  

## 2b. [ECH Updates - b. ECH engineering](https://youtu.be/v1G7jiTHpJ4?t=274)
The next item is [ECH engineering](https://github.com/ethereum-cat-herders/PM/issues/261). So I have a small announcement here. We are growing our engineering team, and this week we have onboarded three new contributors. Two of them are on the development side. We will be talking more about these projects in the later part of this meeting, but just for an introduction, we have George and Stefan joining the team. We already know that Shashank, he joined the engineering team recently. So now we will have three here in addition to Alita who is already supporting the engineering team. So, welcome onboard, Stefan and George.

**Stefan West**  05:30
Thank you.

**Pooja Ranjan** 05:32
And thank you for joining, and we'll be talking about the project in the later part of the meeting.  

## 2c. [ECH Updates - c. Cat blazers](https://youtu.be/v1G7jiTHpJ4?t=339)

The next one is Cat Blazers. Cat Blazers has some great announcements, and I see William Schwab on the call. So over to you, William.

**William Schwab**  05:58
So the news is we chose to launch an [ECH podcast](https://open.spotify.com/show/7dgxKMkSyy3HWtQW7OfqXA), the first episode with Andre Cronje about contracts was released last Thursday. We're targeting a cadence of releasing probably every two weeks. We've got another two recorded episodes right now, though. So there's a decent chance that we'll release one a week for the next couple of weeks. We have recordings from Tomasz Kajetan Stańczak, actually I'm not sure I'm pronouncing his last name right. But in any event, the founder and head of Nethermind, and then also with Samczsun, the famous white hat. So we're hoping that we can release episodes for those two this week, next week. It seems to be getting pretty well received. Right now, it's on Spotify. I've been having a lot of issues personally, just trying to work out Google podcasts where I do think it is live, and Apple podcasts which I can't get to work at all. But I am hoping to add more platforms as time goes by. If anyone is interested in just helping out on the technical end of things, like maybe thumbnail design for episodes, or just kind of helping with the processing after we have a recording or something like that, I could definitely use the hand. Other than that, we've got some interesting stuff coming up.

In terms of general Cat Blazer work, we've got some interesting stuff coming up with the EIP awareness initiative that we've been a part of. There should be some platforms getting back to us this month about EIPs they're interested in working on. We're looking also - we've done some initial work on maybe trying to start an initiative centered around emergency protocols, just getting good documentation out there for platforms to know how to prepare before an incident. And of course, we all hope that there never is one, but also what to do in the unfortunate event that there is one. I'm being helped on those two by [unclear - Super Gupta?] And both seem to be going pretty well. Also, just the usual kind of onboarding, stuff, like people reaching out, wanting some help, asking some questions, things like that. Kernel block 5 I believe starts next month. I might be mistaken on the times, That'll probably keep me pretty busy on the onboarding front, also.

**Pooja Ranjan** 08:26
Awesome. You have covered pretty much everything that is going on in the ecosystem. It's not just Cat Herders. But yeah, a lot is going on. Thank you so much for all the contributions here. And yeah, we could definitely use some help on the podcast side. I'm sorry for the delay for the third recording. I'm trying to process it. We'll try to finish it today and share it with you, but we'll follow the cadence that you just have shared with the community.  

## 2d. [ECH Updates - d. ECH operations](https://youtu.be/v1G7jiTHpJ4?t=533)
Moving on. Next is ECH operations. So we have another announcement here - some good news. We are trying to onboard more people. And this week we have onboarded Shubhangi Gokhale. She is joining the ECH ops team that some of the tasks I would hope to speak for it, but we could expect a couple more contributors joining the team very soon. So, yeah, over to you, Shubhangi

**Shubhangi Gokhale**  09:28
Hello, everyone, and thank you for welcoming me to the group. So I'm working on a few things. I will have a new community members meetup on January 27, 11am EST, and we have 12 people who have joined the group since December and January so far, and I will be sending everybody information about the onboarding process. And I hope that the newly rolled out signed up voting form can come to the meetup. So even though I'm not based in the US timezone, I've chosen the EST timezone because I would like to invite other members of ECH to join the group and maybe talk about their experience in the Cat Herders group. And I think the new members may be interested in asking some questions about how they can contribute. So I think that it would be a great way to introduce them to the community. So I would like to invite, if you're interested in joining that meeting, please let me know.

And I hope to have an agenda for the meeting by the end of this weekend. I've asked Santosh, who's also part of the new ops team, to add it to the event calendar so that other people who joined the group can also see the event pinned to the Discord event channel. And, yes, so please reach out to me if you are interested in the meeting and would like to join. And I'm also working on writing a blog post about new contributors. So this month, I will be writing about Santosh, and next month, I hope to add a new blog post on upcoming people interested in joining the group. And I hope you'll look forward to it. And I think then we'll be working on events related to International Women's Day. So I hope to help contribute for that event as well. And yeah, that's what I have so far. I will also be writing a small blog with some information that Pooja can use regarding ECH's anniversary. So I hope to give her some information about that by tomorrow. Yep, that's all. Thank you.

**William Schwab**  12:14
Did you mention what time it would be at? I just I think I missed that.

**Shubhangi Gokhale**  12:22
11am EST.

**William Schwab**  12:26
On what day?

**Shubhangi Gokhale**  12:27
January 27.

**William Schwab**  12:30
January 27, Thursday. Okay, cool. I think I should be able to make that. Personally, I would be interested in attending.

**Shubhangi Gokhale**  12:37
Oh, thank you, that would be great.

**Pooja Ranjan** 12:40
Create an event for that on the Cat Herder's discord so that other people know about it, and we hope to have good participation. Anyway, she mentioned that she will be sending out invites to the all the new people who have just recently submitted their form for ECH onboarding. So we are covering the new people, but people who are already on the ECH Discord, please check out the events section of the Discord and you will get to know about upcoming meetings there. That's a lot. Thank you so much for all these information.  

## 2e. [ECH Updates - e. EIP Insight](https://youtu.be/v1G7jiTHpJ4?t=797)
Moving on to the [EIP Insight](https://hackmd.io/@poojaranjan/EthereumImprovementProposalsInsight). So we have quite a lot going on the EIP side as well. We have received four new proposals as Draft. The numbers are 4521, 4626, 4546, 4341. All these are ERCs.

There is some movement in the Draft proposals to Review as well, like the proposal 4626, which is tokenized world standard has already been moved to Review status. Looks like the proposal is moving pretty fast. And it is available for review. So people who are interested in this proposal, it's an ERC, so projects which may implement these proposals may join here to share their feedback on the proposal. Similarly, we have two proposals in the Last Call, actually three proposal in the Last Call with deadlines January 25 and January 24. So it's very close. It's highly anticipated that if they do not receive any major changes, they may get into Final, so if you have something to share about these proposals, please share on the Fellowship of Ethereum Magicians threads for these respective proposals. These proposals are EIP 3448: meta proxy standard, EIP 3607: reject transaction from senders with deployed code. And last one is EIP 3668: CCIP Read. For this proposal 3668: CCIP Read, we have recently recorded an episode on Peep an EIP where the author Nick Johnson explained the proposal, provided a small demo for the DAP developers to follow. And he is taking questions on how to implement this proposal on projects. So if you think that this can be useful for your project, please reach out to Nick Johnson or respond to the Fellowship of Ethereum Magicians thread.

There are a couple of more proposals which are in Stagnant status, and some changes to EIP 1. All this information is available on EIP Insight for the month of January. The link is available on the agenda. So that's about it for EIP insight.  The next one is Peep an EIP. For the Peep an EIP, as I mentioned, we had recorded an episode with Nick Johnson last week, and that is live for the upcoming weeks. Tomorrow, we have scheduled a recording for EIP 1967: Standard Proxy Storage Slots with Hadrian. That is another interesting proposal. There is a pull request up to move it into the Last Call. So this is also in the almost ready status. It would be interesting to learn about this proposal. And people can follow for upcoming EIPs discussion on the calendar that is shared in the agenda.  O

## 2f. [ECH Updates - f. Meeting notes](https://youtu.be/v1G7jiTHpJ4?t=1004)
On the meeting notes, unfortunately, we do not have notes for ECD 129, or Consensus 79 so far, because the resource say he got sick - COVID . So sorry about the delay, but we hope to have both of the meeting notes available this week. There was some confusion, and we have some new people on board. So we are trying to sort this out. But we do have the notes available for EIPIP meeting 47. That was another very interesting meeting. We came up with some good issues. And there were some solutions to the issues that are being faced by the EIP editors, or the community there on the EIP GitHub, so people interested may refer to the notes. Any questions or comments on any of the topics so far? Alright, I think there is more interesting stuff coming up. So let's keep moving.  

## 3. [Events & hackathon](https://youtu.be/v1G7jiTHpJ4?t=1075)
On Events and hackathon, we already have shared information about ETHDENVER and SCHELLING P0INT. We have some new updates on Devconnect. We are expecting a meeting this week. I think it's on the 20th or somewhere close. To get into the details of that, however, the document provides some of the expected speakers for the event. I'm going to [share the link here](https://devconnect.org/).  And what are the plans for day one and day two, it's already listed here. But we will get more information in the upcoming week. I'll hope to update it.  

## 4a. [New tasks/brainstorming - a. ECH Medium to Mirror](https://youtu.be/v1G7jiTHpJ4?t=1075)
Moving on to the item number four, which is New tasks and brainstorming. The first one listed here is ECH Medium to Mirror. I remember seeing some progress going on. Do you have any updates to share, William Schwab?.

**William Schwab**  19:06
Oh, okay. I had moved a little bit on that, but I had forgotten about it. So the accounts kind of dropped off with it. So I'll get back to try and make that happen. I'll need to be in touch with you. I need to look it up. I remember Trent wanted a few details from me. And I think I just totally forgot about it, to be perfectly blunt. So I guess we'll both try to remember. There's a couple of things I'll need to ping you for. So once we have that, we should be able to get it set up.

**Pooja Ranjan** 19:45
Awesome. I remembered you mentioned that there was something going on. So I was just really curious, no problem. Get in touch after the meeting and we'll try to get answers to Trent.

## 4b. [New tasks/brainstorming - b. ECH anniv blog & video](https://youtu.be/v1G7jiTHpJ4?t=1196)
Yeah, the next one is ECH anniversary blog and videos. We are planning to release some information in the form of a video and a blog. I'll be working with Shubhangi and Ken on that, and this year we will be the completion of three years of Ethereum Cat Herders. So we'll be sharing some information with the community and we hope that it is useful and more people can join the Ethereum Cat Herders community.

**Brent Allsop**  20:31
Is there a specific date you'd set it on? Or is just sometime about three years ago?

**Pooja Ranjan** 20:36
So I'm referring to the first blog that was published on Ethereum Cat Herders Medium as the announcement of formation of that group, because I am assuming the group was decided somewhere in Prague conference, and I wasn't there, but I'm just assuming the day when the public announcement went out as the milestone day.

**William Schwab**  21:02
Alternatively, January 1 2019, as in the question went out in Prague. That's when Lane Rettig said that they were looking for coordinators and things like that. That was late October 2018. Then over the next couple of months, they interviewed people who expressed an interest. I believe, I don't know that we did anything specific on January 1st, but I remember is 2018 was trying to close, the idea is that we'd kick off at the beginning of 2019. I can put on my OG hat and get in the rocking chair and talk about the good old days now.

**Brent Allsop**
Yeah, it's good to hear that history. Thanks for that.

**Pooja Ranjan** 21:44
Yeah. And we are hoping to someday interview William to get all these old stories. So in the absence of all these details and information, what we have as concrete is on the day of the Medium blog post when it was announced. We are assuming that as the foundation day for the Ethereum Cat Herders, and we will be celebrating that. So that's the 21st of January. So when Lane Rettig first published this blog announcing the formation of the group of Ethereum Cat Herders, so we are taking that as a landmark. And we will be sharing all this relevant information, the blog and the video on that date. All right. Yeah, I just read a comment from William Schwab. Yeah, it's interesting, we should be getting all these things.  

# 4c. [New tasks/brainstorming - c. Learn2Earn](https://youtu.be/v1G7jiTHpJ4?t=1363)
Okay. Next is [Learn2Earn](https://hackmd.io/@poojaranjan/Learn2Earn). So we have made quite some progress on this proposal that was shared in the last meeting, Learn2Earn. And earlier in the meeting, I mentioned about onboarding of couple of CoreDevs. So I would like to invite one of them to maybe talk about the Learn2Earn program. We already have [shared the information about Learn2Earn program](https://hackmd.io/@poojaranjan/Learn2Earn). And if you can click on the link that is added to the agenda,  you can get some information of what what has been going on. We had two meetings in the past, and there is some progress. So maybe George or Shashank, if any of you have to share more on that. I'm sorry, we can't hear you properly. Shashank. But I'm just sharing a small introduction. Yeah, Stefan is also working with the team. He would be actually coordinating and documenting what's going on. So Stefan, if you would like to summarize.

**Stefan West**
Yeah, sure. Yeah, what we're doing is we're building a platform where community members can watch videos and learn stuff, and then afterwards take a quiz to earn [unclear] or maintain NFT by answering these questions after watching an educational video. And what we're doing now as Pooja already mentioned, I will do the documenting side and cobble together some sample questions based on Peep an EIP 41, which was about EIP 3675. And George and Shashank will be engaged in the development tasks. So what we're doing is a dry run first and then get it operative. In about two months, we'll do a proposal as well. So you can all see what we're doing and and Pooja will facilitate the piece to logistics and GitHub coordination. So we'll have something ready in the foreseeable future. And then you can all test it and have a look at it.

**Pooja Ranjan** 25:01
And all these things will be added to the GitHub. I'm just wondering, should we make use of the website GitHub, or should we make use of PM GitHub? But definitely, we will figure out which one to go ahead with, but all the contributions would be added there. So if people come up with some other ideas, suggestions, and they would like to contribute to the project, it should be very convenient for them to do that. So that's about Learn2Earn. And we hope to see this coming live very soon. And we it should be helpful for new new developers, new students who would like to get interested in Ethereum or blockchain in general. I am hoping that this education program will help out. So fingers crossed.  

# 4d. [New tasks/brainstorming - d. EL Merge Client Release Naming](https://youtu.be/v1G7jiTHpJ4?t=1552)
Let's move on to the last item listed here, which is the [EL Merge Client Release Naming](https://ethereum-magicians.org/t/el-merge-client-release-naming/7928/14). If we will remember in December, we had organized a community meeting for the CL consensus layer to find a name for the consensus layer. And Bellatrix was the winner. This time, Tim Beiko started a [Magicians thread where people are suggesting names](https://ethereum-magicians.org/t/el-merge-client-release-naming/7928/14) - what can be the codename for execution layer client specs. So if you have a suggestion, or if you would like to vote your vote for any of the available options, please follow the link.  And you can do either - suggest or give a heart to whatever you like. And then we will eventually have a community meeting for voting and deciding what is the final name that could be used for code name for EL merge upgrade. So that's about it.  

# 5. [ECH funding](https://youtu.be/v1G7jiTHpJ4?t=1620)
The next one is ECH funding. Yeah, we have processed the Moloch funds, about GitCoin Round 12, we received some funds like a CLR. I tried to process that, but we encountered some issue. However, yesterday, I received a response from the support team. So I'm hoping to process this again, maybe today.

And yeah, I'm very hopeful that this should be resolved and we can get the funds. On the PM and funding side. I didn't get in touch with Jared yet. Again, it's my bad. I will try to get ahold of him and see if we need to keep that issue open anymore. Otherwise, we can just close it, because we haven't either received any new information from the team or from a new address from the community over there. So it's kind of still an issue there. And on the funding side, I see some of the open issues. We hope to get them closed this week. We have tried to close the the older issues which were there since January. Sorry for the delay, and thank you for the patience. I know because of vacations that was delayed so long. Generally the cadence is we try to get the funding issues every two weeks, but this time it was longer.

# 5. [ECH funding](https://youtu.be/v1G7jiTHpJ4?t=1707)
And the last item here is the [outstanding action items from the previous ECH meeting](https://github.com/ethereum-cat-herders/PM/blob/master/All%20Ethereum%20Cat%20Herder%20Meetings/Meeting%20075.md). So from the last meeting, it seems like we have five decision/action items.  

Number one - going to create a group to develop Learn2Earn concept. We have made quite some progress and we did share in the meeting today.  

Edit the ECH third anniversary video. Yes, we are working on the three year anniversary video and blog both. William to follow up with Trent on Mirror blog migration, it's WIP - work in progress.  

75.4 - Initiate transaction to receive funding from Gitcoin and Moloch. Moloch is processed. GitCoin is in progress. We'll hope to get it done by the next meeting.  

So 75.5 - Pooja to get in touch with Jared to see about closing of JSON RPC issue. No, I couldn't do that. It's going to be outstanding. We'll get back on this issue in the next meeting.  So that's all from the items listed here. We still have some time if anyone would like to talk about anything or bring up.

**Eric/CryptoShine**  29:59
One related effort. Stefan's comment just sparked the idea in my head. I'm working with a couple of friends of mine to basically introduce crypto and blockchain to our alma maters and where we went to school. I just did a quick scan online. There are very few schools that actually have a crypto department. I know some of them like MIT or Stanford have research hubs. But where I went to school, there's nothing quite like that yet. And the goal would be to kind of demystify the technology, the ethos of what is this about, and someday hopefully have students attending schools like Dartmouth or others where you could major in blockchain technology, for example. And I love the interdisciplinary nature of the space. You don't have to be a developer to be part of Ethereum or any other network like it. So I'm working with school administrators and student organizations now to get it started.

**Brent Allsop**  31:14
That's brilliant. I'll need to do that with my alma mater, University of Utah.

**Eric/CryptoShine**  31:18
Yeah. I mean, if you're 20 something today, and you're not interested in crypto, you're probably in the minority. So there's not lack of interest. I think it's just trying to convince professors and school administrators that it's worth studying, which I think, may be an uphill battle, depending on where you go to school, but I know some are very, very receptive to it. They just don't quite know where to start yet, I think is the problem.

**William Schwab**  31:49
If I can help you out with tech, with any technical knowledge, I'm happy to lend that. One of the things that I tried to do on the side, I usually just call onboarding, which is people who need some technical knowledge or trying to get a better understanding of things that are going on. I'm happy to help out where I can. In my other life, I am actually a smart contract developer. So yeah, if there's anything I can help with, definitely, shoot me a DM or anything like that.

**Eric/CryptoShine**  32:16
Yep, for sure. For sure. Thank you.

**Shubhangi Gokhale**  32:19
I just wanted to say that I used to be an academic. Four years ago, I was a research fellow at Yale Law School on blockchain. So I know a few people over there and in Korea and Japan who teach or are related to or doing research on FinTech or blockchain. So if you're interested in connecting to some people, I guess I could reach out to you if you want.

**Eric/CryptoShine**  32:54
Oh, awesome. That'd be great. I just posted our little notion doc that I got up and running over Christmas. So it's very early, very messy. But we're in the info-gathering phase right now, just compiling a database of campuses. I listed the ones I know, but there's many more than the 10 or 15 I've listed here. So any and all help will be super helpful here.

**Shubhangi Gokhale**  33:23
Oh, yes. So I guess I will reach out to you if you are interested.

**Eric/Cryptoshine**  33:28
Yep. Thank you.

**Stefan West**  33:30
And I'll reach out to you as well, about your comment. I noted your Discord. So I will reach out to you as well. And I can share some links as well from my local university University of Basel. They have online crypto lectures, it's called. and they have a Center for Innovative Finance. Vitalik has received an honorary doctor title from them as well. So they work together, I think I can share that as well. Maybe it helps.

**Eric/Cryptoshine**  34:00
That's very helpful. Feel like every school listed here is well ahead of mine. So we need to catch up. Thank you.

**Pooja Ranjan** 34:14
Well, thank you all. This is pretty interesting. One of the key audience of all these programs that we are trying to run here is new people who are joining and starting with universities and colleges. That's an awesome step. And it's a good effort that I can see. I'm just checking the notion that you have shared. It's really nice, and then we can have these people reached out to. It would be a good, good way of engaging new people in the blockchain. So thank you, everyone, for all this great conversation and the effort that you are putting into this ecosystem. And yeah, any final question comment thought, from anyone?

**Eric/CryptoShine**  34:59
Oh, who's gonna ETHDENVER?

**Pooja Ranjan** 35:04
That's a good one. I may not be going there, but maybe I would be speaking for Cat Herders virtually.

**Eric/CryptoShine**  35:15
Awesome. Well, anyone's around, I'm familiar with the Denver area. So I'm happy to be the free tour guide.

**Pooja Ranjan** 35:24
I hope to see you next year maybe then?

**Eric/CryptoShine**  35:28
I hope so. I thought that last yea,r but who knows?

**Pooja Ranjan** 35:38
Seriously, I mean, it's too bad. We have been trying to meet people for the past two years. And it's like, "oh, no, you can't go out." Alright, it was a fun meeting today. And again, now we can continue talking about anything, any topic, anything that you think is relevant that can be helpful to any other fellow community member, please share in our Discord and we'll try to just keep jamming on that. Thank you, everyone for joining today. See you soon. Have a good one everyone.

# Attendees

* Brent Allsop
* Eric/CryptoShine
* George Harvey
* Micah Zoltu
* Pooja Ranjan(Host)
* Shashank Y*
* Shubhangi Gokhale
* Stefan West
* Texas Farmer
* William Schwab



# Date for Next Meeting: February 1 at 1500 UTC

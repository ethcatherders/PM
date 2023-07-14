# Ethereum Cat Herder Meeting # 111  Notes
### Meeting Date/Time: June 20, 2023 at 14:00 UTC
### Meeting Duration: 0.5 hour
### [GitHub Agenda Page](https://github.com/ethereum-cat-herders/PM/issues/358)
### [Audio/Video of the meeting](https://youtu.be/KiIur6Hh7io)
### Moderator: Pooja Ranjan
### Notes: Alen (Santhosh)

# Intro
**Pooja Ranjan**
* All right. Thank you for joining. Welcome to Ethereum Cat Herders 111. I shared agenda in Chad. The first item that we had on the agenda was project demo with the project demo with eips.fun with Mikely, it looks like, there was some miscommunication on the timing of the meeting and, we do not have the team. I take the full responsibility. It was miscommunication on the events part, but nonetheless, we can come back on that. Later on. We can go ahead and start with our regular updates. 

# 2. Ethereum network upgrades [0.45](https://youtu.be/KiIur6Hh7io?t=45)
**Pooja Ranjan**
* So welcome again to the Cat Herders meeting. And on Ethereum network upgrades, we know that we are expecting Cancun & Deneb upgrade. So for Cancun, we have, almost received the final list of EIPs. There are five proposals, which are, included as per the specs available at Ethereum's execution Specs and the proposal numbers are EIP 1153 transient storage ops codes, EIP 4788 Beacon block route in the EVM EIP4844 shard block transactions, EIP-5656 copy memory copying instruction and EIP 6780. Self-destruct only in same transaction. That's on Deneb side.
* However, we do have an extended list of, specs changes, which we are expecting with the Deneb upgrade. it is mostly on light client and, there are some changes with respect to Beacon chain. Fork choice, Fork P2P interface, polynomial commitment and validator. So all these files, would be expecting some changes. Please follow the latest, consensus specs release to update the validator note. And, with the changes which are already merged, I have added the EIP 4844 implementers calls, recording and notes. We do have the readiness checklist as well to follow along. We had recently started a devnet 6 for, testing of EIP 4844, hoping to have a definite specific to this upgrade, activated shortly. we'll get to know more about it in the upcoming all core dev meeting. Okay, that's about the network upgrade. 
* I have also added link to Dencun upgrade, B Penny playlist. We have, multiple recordings on the proposals and, and spec changes. With respect to, Dencun upgrade, we are hoping to talk to more authors for rest of the proposal so far. You can check it for, 4 8 44 and 1153. But we are hoping to have conversation with the rest of the proposals to have this, video available for public information tomorrow. We are expecting a call with, one of our EIP editors who happens to be the, client developer for Java Street and Load Star. And, that is about the Dencun Specs changes. So if you're around, please join us on the call at 1830 UTC
* And, yeah, that, is, all about it. We have also added information about work implementers call. People can find the entire playlist on Ethereum Cat Herders YouTube. And, we do have, mega specs for EUF. We did not have EUF meeting last week, mostly because of, not much updates and some of the contributors were on vacation. So we hope to have next meeting, on next Wednesday. 

# 3. Events, Fellowship, Hackathon [4.32](https://youtu.be/KiIur6Hh7io?t=272)
**Pooja Ranjan**
* Moving on to the next item, which is events, fellowship and Hackathon. I think, the participation for the application date for Ethereum Protocol Fellowship, is closed. However, people who have not submitted the application and still wanted to follow, they can. We do have a dedicated channel At Eth r&D  Discord.
* I have received a few queries, with respect to, EPF, like if they have not done it, how they can do it. I think this is open, and even if you are not enrolled, you can still follow the calls, which will be announced on the channel. And, yeah, you can share your questions and, try to educate yourself with respect to, Ethereum Protocol. And you can seek help from, all client developers available in the channel.
* We already have shared about that, that connect. I think the first agenda, list is out. Please take a look. So far, this is all the updates with respect to protocol development and events fellowship people. If you have any information that you would like to share with the rest of the community, please share it with us. Either you can share it, it on Discord channel, or, you can just leave a comment here and we will include it in the next meeting. On general update section, I have shared the stats with respect to the different social media Ethereum Cat Herders. 
* We are around 6,600 followers on Twitter, over 2000 users on Discord, and over 3,100 YouTube subscribers. Moving on to the ECH engineering side, we did have a meeting yesterday where we discussed the two things. one is, the development of, development with respect to application projects, and one with respect to the development of the present, catalyst website. I do see George on the call. George, if you would like to take a few minutes and talk about, these two updates. 

**George**
* Yeah, sure. So for the, for the first one with the ERCs and ERP basically reference repository that we're working on we started creating a form, so, authors and projects that use some of these ERCs, that have been around for a while can fill it out and basically add some resources like packages that other builders can use to help implement these ERCs into their own projects as well as, other projects that have already implemented it, as examples. So these are focused more towards, existing ERCs. 
* Before, there was a proposal to add implementations to newer ERC proposals. so this is kind of just, filling the gap of older ones. and that's currently in progress when it comes to also, just filling out, the whole list, which sapr and Puja are also helping out with that. when it comes to the website, we are adding, some additional information on the denko page. mainly focused on, the ERPs related to Dene, the consensus layer upgrade,since most of it's focused on Cancun as of right now. and also just updating it since, the last time it was updated since there's been a few there's been a few updates since the last time that the website has been updated.I purposely try to use update as much as possible now. So that's pretty much in terms of my updates. 

**Pooja Ranjan**
* That's interesting to have updates about updates. 

**George**
* Yeah. 

**Pooja Ranjan**
* Yeah. Right. Yeah. 

**George**
* Hopefully Getting confused. Too many people. 

**Pooja Ranjan**
* Yeah, we are used to of hearing words, upgrades, updates, so frequently Yeah. Maybe ecosystem. 

**George**
* Yeah. Maybe I should, maybe I should change it up with upgrades too. 

**Pooja Ranjan**
* So right? Yeah, right. I mean, we do have this, client development developers meeting every week. One week it is execution client another week. It is consensus client, and we do expect some changes to the, updates on upgrade related information. We will, try to do our best to keep this website updated for people to follow. 
* Thank you so much, George, for sharing this information, and I hope that we should, receive a appear soon by the end of this week. Of course and we will be able to update the page. 

**George**
Yep. 

# ECH Operations [10.19](https://youtu.be/KiIur6Hh7io?t=619)
**Pooja Ranjan**
* Very well, let's move on to the next section, which is ECH operations. yeah. We are adding, short of PEEPanEIP in community playlist yesterday. We have shared, shorts of, proposal 4844, Dankard shared, some useful pieces of information with respect to why cases KZZ ceramony are required and why did we do, the KZ ceremony before we started working on the 4844 upgrades. 
* So yeah, I think it's a good way of sharing information in pieces and we hope it is helpful for people. And if it creates interest, we are also sharing the link to follow the full video. 
* So that's on Shorts. And, yeah, one other thing that we, I think I was discussing it with Santhosh. We were hoping to have, shorts from the Ethereum Cat Herders meeting as well. So now that we have started this, project demo thing, like we are hoping to have one project coming up on Ian  meeting to demo and share it with the community. We can probably create shots or shorted video for project specificity and be able to share. Do you have thoughts there Santhosh Do you think it is going to be relatively easier and useful as well? 

**Santhosh**
* Yeah, it'll be much easier to trim because, it's specific to the project update, right? we can definitely take a shot. 
* Yeah, I think, you had told me this in the past to reach out a few folks, who wants to talk about it in the ECH meeting. Maybe I couldn't, I didn't follow up, I didn't get time, but I definitely try to find some time to reach out to few of the folks and see if they're relevant. We'll add them to the ECH call. 

**Pooja Ranjan**
* That's right. Sorry. I was also discussing this with George yesterday. And we hope to have a schedule created just like we have a schedule for PEEPanEIP on public, project board, the ECH project board. We can have it for this meeting as well as project demo so people can reach by themselves to us and we can have them scheduled for the future meeting of Ethereum Cat Herders just to simplify the process. 

**Santhosh**
* Sure. Good. 

**Pooja Ranjan**
* Okay, cool. So we'll start working on this. Maybe we can start with the first project, the stated project, which demoed the other day. Would you like to maybe take a look at it and maybe create the first, video shots? Yeah, yeah. From there. 

**Santhosh**
* I'll, It was in the, last meeting, right? Last video of the Ech, right? 

**Pooja Ranjan**
* I think two, two meetings ago, I guess. 

**Santhosh**
* Okay. I'll figure it out. Yeah. 

## ECH Podcast [13.24](https://youtu.be/KiIur6Hh7io?t=804)
**Pooja Ranjan**
* Okay. so that is something new that we are adding here. Hopefully it'll engage more, involvement. Moving on to ECH podcast. We have been releasing, po podcast episodes every week. Please check out the webpage, Ethereum Cat Herders.com/podcast to get to know about all the platform where we are releasing it. And, please stay updated with, the latest talk on the Ethereum Research and Protocol Development. 
* Okay. The next section is EIPs Insight & EIPsInsight website website. So if we take a look at the website, I think, it is providing us all the latest information about EIPS in the present month for June, we have received 11 EIPs in draft. 
* Two of them are core and rest nine are ERC proposals. We have three proposals in review, one in last call and one in final status. The proposal in last call is 6039. I'm quickly gonna check at the last date for this proposal just to be sure that if this has passed the end date. Yeah, right. the last call deadline here is August 15th. So we do have some time people, if you have a suggestion or changes recommended for this proposal, please, make sure to add it before 15th August on Fellowship of Ethereum Magician. 
* Once the proposal moves to final, we may not be able to entertain any kind of update on the proposal. So yeah, please be sure to, share it with authors or bring it to author's attention. People can check out the HackMD added in the agenda or also you can check out EIPs inside.com/current. month, 
* PEEPanEIP As I mentioned earlier, we have planned a meeting with Gajinder Singh, who is an EIP editor and also contributor to Load Star and Ethereum JS. this call would be dedicated to denus upgrades  and it is scheduled for tomorrow, June 21st at 1830 UTC. It'll be followed by a few other proposals, which we are expecting in upcoming days. #1 is 6110 supply validated deposit chain with KIN Call and the other one is, expected with 6780 self-destruct only in the same transaction. 
* With be stay tuned with, these meetings, you can check out the calendar available on Ethereum Cat Herders GitHub, or you can also follow Ethereum Cat Herders Discord to know about the date and also the Zoom link to join the meeting if you're interested. I'm happy to see that all notes have been added here. So we do have notes available for ACDE 1 63 ACDC 111 EIPIP 82. We do have added recording for, editing Office hour 19 and agenda added for the next meeting, which is expected next Tuesday at 1500 U T C. The next section is about, new initiative and association and updates with respect to ECH Access. I don't think we have made any changes on Twitter access as yet. 

**Santhosh**
* Yeah, maybe, , access was one part the other part was also giving sharing the content,. So I'll try to share something definitely this week for that by we can make at least add some progress before we make next week. 

**Pooja Ranjan**
* Sounds good. So yeah,I mean if anyone else has any other community engagement idea, please feel free to share it with us.We are hoping to have, information about upgrade protocol changes going out as frequent as possible and reach, and have maximum reach there. 
* The last item added for today's discussion is review of outstanding action items from previous meeting.considering this is most of the updates I do not see much of the, you know, action items needed here. And, one other thing that we would like to discuss, there'll be the meeting date, next meeting date.So next meeting is falling on July 4th. 
* Do we wanna keep it? It's going to be shot of course, but's totally up to us to decide.if not then we can skip the other one and move it to July 18th directly. Any thoughts suggestion here? 

**Santhosh**
* I'm fine with it. It's fine if you wanna move it to July 18th. 

**Pooja Ranjan**
* Okay. 

**Speaker: 1**
* Yeah, Yeah, likewise. 

**Pooja Ranjan**
* Alright, so what we do is like we check on, with projects if we get any projects, they're interested in demoing, I remember one project there specifically mentioned that they would be interested in having demo after 29th of June. 
* So if we get any kind of demo organized before that, then we will keep it on July 4th. if not, then we will skip that week and move it to July 18th. The announcement should be done at least a week before the meeting date. Does that sound a reasonable settlement here for the date? 

**Santhosh**
* Yep. 

**Pooja Ranjan**
Okay, cool. Yeah. Alright. I think, that is all. anyone has anything to share for today? Add or suggestion like we can give ourselves 30 minutes back. Thank you, for joining us today. See you in two weeks. Hopefully. Have a good one everyone. Yeah. Thank you. Bye-bye. 

**Speaker: 1**
* Thanks. 

----
Attendee
* Pooja Ranjan 
* Edson ayllon
* George
* Santhosh


----
Next meeting on [July 04, 2023 at 14:00 UTC](https://github.com/ethereum-cat-herders/PM/issues/360)

  


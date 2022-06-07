# Ethereum Cat Herder Meeting # 84  
### Meeting Date/Time: Tuesday  10 May 2022 at 15:00 UTC
### Meeting Duration: 32:25 
### [GitHub Agenda Page](https://github.com/ethereum-cat-herders/PM/issues/284)
### [Audio/Video of the meeting](https://www.youtube.com/watch?v=9PzLdJqyU3I)
### Moderator: Pooja Ranjan
### Notes: Metago
---

## DECISIONS & ACTION ITEMS

**DECISION/ACTION ITEM 84.1**: Pooja will check with Ethereum Foundation regarding backup for EIPIP repository.

**DECISION/ACTION ITEM 84.2**: The following GitHub repositories may need backup: PM, ECH Website, Learn2Earn, and possibly EIPIP depending on Ethereum Foundation's response. Pooja will discuss backup process with ECH contributor that brought up the issue and welcomes community participation in the process.

**DECISION/ACTION ITEM 84.3**: Pooja will contact Chris Hobcroft to get more information regarding decentralized video streaming options (like Arweave and Odysee video platforms) as a backup for ECH Youtube videos.

**DECISION/ACTION ITEM 84.4**: Santosh and maybe Slava and other members will look at adding a podcast page to the ECH website. 

---

## COMMUNITY PARTICIPATION

**GOERLI NODES** : Goerli validators or anyone that has a question / comment / concern related to Goerli, please share it on ECH Discord. 

**GitHub Backup** : If anyone would like to help in the process of creating backups for ECH GitHub repos, and if anyone has experience with radical dot xyz or arweave, please comment on ECH Discord.

**Ruby Dev** : If you are a Ruby Dev and interested in helping the Ethereum protocol, please reach out on ECH Discord.

**Leaern2Earn** : If you are interested in contributing to POAP management and helping with quiz issues related to ECH's L2E app, please reach out on the L2E channel on the ECH Discord.

**Meeting Minutes** : If you are interested in taking meeting notes, especially for All Core Devs and Consensus Layer meeting, please reach out on discord. 

# Agenda

## 1. Ethereum Network Upgrades
### The Merge, Resources

**Pooja** ([0:00](https://youtu.be/HN_SNEC3dfM))
All right, welcome to Ethereum Cat Herders meeting 84. I have shared agenda in the chat. The first item listed here is Ethereum network upgrade, of course the merge, which we are expecting this summer. Latest updates on that are mainnet shadow fork number three was deployed last Thursday. TTD was a hit and the participation rate post TTD was 97.6 percent. Beso and Geth had some issues, otherwise all other client combinations seem to be working fine. There were some issues reported with Prism and Nethermind too, but that are being fixed now. I suppose we may expect at least one more mainnet shadow fork. And on the resources side, Mario from the Ethereum foundation who recently has joined to help out with the EIP bot on the process side as well has released a hackmd file with curated list of useful resources on merge. The link is added to the agenda so please check it out.

### Shanghai Specs, Tracker ([1:17](https://youtu.be/HN_SNEC3dfM?t=77))
The next upgrade, Shanghai. So it was mentioned in the last All Core Dev call that core devs may not be proactively working to defuse the difficulty bomb, however the plan is to further monitor and make decision during May or during forking the testnets if any kind of resetting of the bomb will be required at the time. To get more information on difficulty bomb, and shanghai proposals, tune in for the next All Core Dev meeting, which is scheduled this Friday at 1400 UTC.

### Goerli Nodes ([2:00](https://youtu.be/HN_SNEC3dfM?t=120)) 
Another important information that I think is not listed here on the agenda but may be worth sharing with people. So yesterday some people reported about Goerli  nodes getting down…Ronan who is a cat herder contributor and also a Goerli validator, he confirmed that the issue has been resolved now and nodes are up and running. We would like to encourage more people with any kind of Goerli issue or information to join us on the cat herders discord, so if you're a validator or maybe have a question, comment, concern related to Goerli at all, share with us on Eth cat herders discord. Any question comments so far?

## 2. New Initiatives
### ECH GitHub backup ([2:52](https://youtu.be/HN_SNEC3dfM?t=172))
All right. Moving ahead, number two is about new initiatives. So the first one here is ECH GitHub backup. Briefly raised and discussed in the last meeting about how do we take backup for GitHub? William Schwab suggested radical.xyz and one other contributor suggested Arweave. So I was having this conversation with the other contributor, he kind of specified the cost that may be associated with having GitHub backup. It seems reasonable but the cost will be like every time we will be uploading, so if we are moving in the direction of having a backup, a few question that is there for this group will be like, which tool is most suitable for us, and which repos are we considering for backup. I just want more information here. In my mind, EIPIP could be one of the most useful process related decision placeholder like we have collected all these decisions in the meeting notes that can be one of the important ones so I have tried to reach out to the foundation, if they would be considering having a backup for EIPIP repo though we have not heard anything concrete as such, but yeah, we still have to think about other repos or any thoughts? Questions? 

**Metago** ([4:31](https://youtu.be/HN_SNEC3dfM?t=271))
I had a question, is the Ethereum foundation like some, is it something that they are considering as well? A backup for their GitHub? 

**Pooja** ([4:36](https://youtu.be/HN_SNEC3dfM?t=276))
I think they are already doing it.

**Metago** ([4:43](https://youtu.be/HN_SNEC3dfM?t=283))
I see. On arweave?

**Pooja** ([4:48]](https://youtu.be/HN_SNEC3dfM?t=288))
I’m not sure of that particular because arweave was suggested by one of the cat herder’s contributor not the foundation people.

**Metago** ([5:02](https://youtu.be/HN_SNEC3dfM?t=302))
I see.

**William** ([5:10](https://youtu.be/HN_SNEC3dfM?t=310))
As far as using arweave would go, what would be the exact format? Is there some kind of project on that hand code repositories or get repositories, what would even be the methodology behind…?

**Pooja** ([5:28](https://youtu.be/HN_SNEC3dfM?t=328))
So my high level understanding is, it is like, every time we upload something to arweave and the cost that was mentioned was around 125 MB per dollar, but this will be like every time we would like to update, say for example we do it bi-weekly, then for the changes it will be there, though I do not have full details of it, but I am expecting the person who shared this information may be able to help us more, if we would like to go in this direction. Do you by any chance have any information of radical.xyz William Schwab? I'm sorry to put you on spot, just curious what about it.

**William** ([6:12](https://youtu.be/HN_SNEC3dfM?t=372))
About how it works? What is it?

**Pooja** ([6:17](https://youtu.be/HN_SNEC3dfM?t=377))
Yeah. Backup or if there is any price associated or frequency…all right.

**William** ([6:22](https://youtu.be/HN_SNEC3dfM?t=382))
Nope…its self-hosting. Well okay, it's not exactly self-hosted but it's more or less self hosting on its centralized network, so there is a UI, like they already have their own app that should aid in terms of just like having these easy graphical interface, for, you know uploading things and it's built to handle repositories, so it should not be that hectic of a process. I’d also imagine they have a number of people who are very active in the ecosystem. I would imagine that if we were interested in starting to use them like as a serious backup, I didn't mention they'd be able to spare someone who would be able to help us out a bit with the process but that is speculation on my part.

**Pooja** ([7:06](https://youtu.be/HN_SNEC3dfM?t=426))
All right, so one question that is going to be like open irrespective of which like tool or project we would like to take help for having a backup of this GitHub…which all repositories do we think are worth putting on? Maybe blockchain or any other places for backup…as of now I can see PM, EIPIP, 1559 outreach…I'm not sure how valuable it is after the 1559 is already deployed. There is progpow-audit, same for that, yeah what do people think here?

**Metago** ([7:54](https://youtu.be/HN_SNEC3dfM?t=474))
I would I think even the funding repository would be important just to have that information, like accounts.

**William** ([8:01](https://youtu.be/HN_SNEC3dfM?t=481))
I don't think issues would come over…it happens to this and when you're looking kind of…and I guess this might get into the guts of how something like GitHub works um but with GitHub the issues are probably available through their API, which is something I do not have experience with, but usually when we talk about a repo what we're talking about is the actual Git repository that is then being hosted on GitHub. I don't know if this is like 100 % clear, maybe the easiest way I say like I can try and describe it is actually taking a look at the, like the web page when you're in a GitHub repo, the parts that are more I’d say in your hands, and not fully in Microsoft / GitHub’s are the parts kind of under the menus like where you start seeing the folders and all of that, that's a Git repository that's generally mirrored on some machines somewhere in the world and it's just being hosted there…very sorry it's being mirrored on GitHub from somebody's machine somewhere. Like the issues, the pull requests things like that, those kind of live inside of GitHub and there might be a way to retrieve the information through the API. I don't know one way or the other, but I think no matter where the backup tasks would be that that's probably going to be a bit of a process. You might want to get someone who like knows their web scraping or something like that and see if that's possible. 

**Pooja** ([9:38](https://youtu.be/HN_SNEC3dfM?t=578))
Okay, so my understanding was like the all dot md files or any kind of file and folders available on the GitHub repository will be moved as a backup, and to answer your question Shubhangi, we do maintain a separate spreadsheet for internal purposes for record keeping so we do have a backup for that information.

**Metago**([10:05](https://youtu.be/HN_SNEC3dfM?t=605))
Oh yeah, that makes sense thanks for the clarification.

**Pooja**([10:11](https://youtu.be/HN_SNEC3dfM?t=611))
So at the moment, I was considering that we are actively working on the first thing, our website is being hosted via GitHub so all the codes are available in there, that is one important repository that we may want to save, the other is learn to earn because there we are developing an app, and all the codes are only available on our GitHub so we would like to save that as well. With respect to PM, that is  all the meeting notes, and EIPIP I’ll check out with the foundation, if they are taking care of it then we may not have to, if they don't, then probably that will be also a part of this backup that we would be needing for. Does that sound reasonable to people or if there is any other suggestion? I’ll take it as no objection. So yeah maybe if someone can help out with the process, of the entire process let us know how to proceed in that direction, that would be great. I don't know if anyone from the group would like to take a lead and I will I’m hoping that person who has suggested this may also be one of the contributors so I can maybe talk to him as well after this call, but the first thing that we need to maybe check on would be like should we want to go with the radical or do we want to go with arweave…

**William** ([11:54](https://youtu.be/HN_SNEC3dfM?t=714))
They aren't mutually exclusive also, I mean maybe I’ll even throw this out if there's anybody out there who's listening to this and thinks that they would know like what we would need to do in order to start using our arweave as a backup or to get started with radical like please do reach out we would love to…with us… 

**Pooja** ([12:17](https://youtu.be/HN_SNEC3dfM?t=737))
Yeah, that would be great. Thank you, please reach out and let us know, yeah, we can think of having a backup because all these meeting notes may be of importance for people to refer in future. Okay so that was about GitHub. 

### ECH Youtube Backup ([12:39](https://youtu.be/HN_SNEC3dfM?t=759))
Similarly we received this another request on this card from metago about the YouTube backup so ya, metago if you would like to share about that.

**Metago** ([12:52](https://youtu.be/HN_SNEC3dfM?t=772))
Yeah. I was reading news about some web3 accounts that got banned on YouTube and I saw recent news that they were unbanned and YouTube is working with them to…so that the access is restored but it just got me thinking that it's good to have a backup for the video series since we have so many links referring to it and there's so much educational content on there, so it would be good to have a backup of the videos that ECH puts out. And I think…

**William** ([13:32](https://youtu.be/HN_SNEC3dfM?t=812))
…right there that's a great idea.

**Pooja** ([13:37](https://youtu.be/HN_SNEC3dfM?t=817))
So did you mention arweave would be great there?

**William** ([13:42](https://youtu.be/HN_SNEC3dfM?t=822))
Yeah. I believe that there are already video hosting services on top of that, maybe glass…I think is one of them…do any of us still have contact with Chris, with Chris Hobcroft? I think there's a good chance, you know, yeah, I think there's a good chance he's gonna…I don't think he's been…here for a while from…if I’m not mistaken though I haven't been keeping up…could be still there but I’d suspect just like from his like kind of history dealing with a lot of decentralized video streaming stuff, I would hope that he'd also know something about current state of decentralized video hosting.

**Pooja** ([14:11](https://youtu.be/HN_SNEC3dfM?t=851))
All right. I’ll try to reach out to him. I know he's on our discord server so maybe I’ll try to make a contact and get some more information, however there was another suggestion coming up from Micah, it was Odyssey, Odyssey platform and he suggested that maybe we would like to have a backup of all the recordings, not only for cat herders but also for the foundation. I’m not sure about this…like a foundation and having any backup for their YouTube videos or meetings, but yeah. That's worth exploring. But just for information, like we are already saving all cat herders meeting notes in form of podcast on blockchain but we do not have any content like PEEPanEIP or any other useful content, which I think will be more useful than the meetings for community maybe but yeah. Okay, um thank you for the suggestion William Schwab, I’ll try to get in touch with Chris and see if he may help us in that like if you may know some solution that is working good. I’ll try to bring back whatever information I could collect from him in the next meeting.

### ECH Twitter Spaces ([15:36](https://youtu.be/HN_SNEC3dfM?t=936))
The next one is ECH twitter spaces. So basically this is coming from a chat which I had with the one of the maybe potential contributor. He left some comment, so if you can scroll down the meeting agenda, he left some comments there. He is willing to contribute to Ethereum Cat Herders and he shared some of his suggestion that we might engage community…Chinese community especially, with the help of twitter, making some conversation with the broader crypto community, so he proposes to organize twitter spaces, though it's unclear to me, like he wants to have a different twitter account to handle that, because his point number one suggests that using social forums to distribute content such as creating a Chinese community twitter account so that the latest development can be disseminated. Unfortunately it's not a good time for him so he could not join this meeting, but maybe we can check with him if the proposal is to have a separate twitter account for Chinese community or if the proposal is to make use of the present cat herder’s twitter. Other than that he also has certain suggestions to improve the discord server setting and he has requested to add as a contributor so he can start working on it. I wonder what people think about all these potential ways to engage community. 

**Metago** ([17:18](https://youtu.be/HN_SNEC3dfM?t=1038))
I have also talked before about having like multilingual support to expand the scope of people interested in joining the community and also having like at least one meeting a month that's in the Asian time zone. So actually I had that one meeting last month but I think the timing was an issue so I would like to have another meeting to welcome people based in Asia, and I agree like having multilingual support would be good, but I think having him come and explain a bit more even if he writes in Chinese can be okay, because we can use google translate and I’m sure some members, well I can read a little bit of Chinese, so I can maybe work with him a bit on what he's doing. So I have general support for his ideas but I don't really know the details so I can't really say more.

**William** ([18:26](https://youtu.be/HN_SNEC3dfM?t=1106))
Yeah, and I think maybe just to build on top of what Shubhangi is saying, I think everybody here would love to see…bilingually and also more globally, the only thing that we need to be able to do and I think you just touched on this very nicely also is make sure that there's a certain level of quality to content, like we wouldn't want someone to be able to roll in who might be more dubious or even have malicious intent, and be able to leverage the fact that nobody knows what they're saying on our side anyway to use it as a platform for anything malicious, so just and I think a lot of it's about figuring out how we can kind of ensure quality, how we can ensure trust as we move in to something more global, but I absolutely think that we should try and push that…on this and figure out a way to make it work.

**Pooja** ([19:27](https://youtu.be/HN_SNEC3dfM?t=1167))
That's very good feedback thank you Shubhangi thank you William I did mention about Shubhangi being working from japan maybe in the Asia time and maybe if I can introduce you both so you can get to know more about it. You have been a contributor here for a while so it will be easier to maybe able to convince him to be a part of it. I don't know, but also to maybe evaluate how things work here and let him know more about it and to the part of like building trust I totally agree, William Schwab this is very difficult, when it comes to a different language that many of us may not be able to understand, so it needs to be well vetted and I’m a little bit um skeptical about giving all the permissions even to the contributor level permission right away. I would like to maybe get some more work done or review more of the work before having a permission shared on discord. 

**Metago** ([20:32](https://youtu.be/HN_SNEC3dfM?t=1232))
Yeah I totally agree with you and William about this, like just getting to know each other better would be a good idea right now.

**Pooja** ([20:45](https://youtu.be/HN_SNEC3dfM?t=1245))
Sounds good. So if you are okay maybe I can make an introduction of you both, and definitely, you guys can catch up in your daytime if that helps.

**Metago** ([21:00](https://youtu.be/HN_SNEC3dfM?t=1260))
Yeah, and oh, maybe I can make an office hour, so if he wants to invite anybody they can come and we can record the meeting.

**Pooja** ([21:06](https://youtu.be/HN_SNEC3dfM?t=1266))
Oh yeah that is even better. Okay, maybe we can talk offline a bit more about it and figure out how we want to go ahead with this experiment. Once again, thank you William, thank you Shubhangi.

## 3. Events and Hackathons ([21:27](https://youtu.be/HN_SNEC3dfM?t=1287))
All right. Moving ahead, the next item is events and hackathon. I have mentioned two events. Actually those are hackathons as well. One is Warpspeed that is organized by Devfolio from India, so that is a location constraint, but if people want to join they can. Application is closing soon. The other one is ETHPrague that's starting from June 10th. Check out the link added in the agenda for details and speakers who are speaking on the event.

## 4. ECH Updates
### ECH Website ([22:08](https://youtu.be/HN_SNEC3dfM?t=1328))
The next agenda item is ECH updates, the first one is ECH website. So I know the ECH website is more or less updated these days. We have tried to add more information of all the proposals those are in active discussion. I have created an issue to add a page for ECH podcast, looks like when we started ECH podcast we lost the support from the website development team and we were not able to add the page for podcast. So I don't know…Slava and maybe Santosh, if you can also work on that, anyone who is available to work on that and maybe send a full request, that would be helpful and the merged resources that I just mentioned today in the meeting earlier, we would like to have that added. Plus a couple of other EIP resources, so check out the GitHub and if you can make a pull request, let me know.

**Santosh** ([23:10](https://youtu.be/HN_SNEC3dfM?t=1390))
Sure, I’ll take a look at it. 

### ECH Engineering (Need Ruby Dev, EIP Bot, EIPV, Learn2Earn
**Pooja** ([23:10](https://youtu.be/HN_SNEC3dfM?t=1390))
Thank you. On ech engineering, we are still looking for a ruby dev, we didn't hear from anyone, so if you are a ruby dev listening to the call, want to support Ethereum protocol, please reach out to us. The other are EIPbot in EIPV. I know Jose is not here. The update is for EIPV. Ethereum foundation has introduced a developer who may be helping out. He knows Rust so he may be helping out with the bot that was created by lightclient, the validator bot, and Jose is working on the EIP bot, I think that is in json type script. We are trying to figure out how to close all these issues sooner rather than later and on a side note the people are still discussing the plus and minuses of having a common repository for EIPs and ERCs so if you want to learn more about it, please join the EIPIP meeting on next Wednesday at 1400 UTC. The time has changed recently, sorry about that. and the last one is learn to earn you're making good progress. I see George on the call, over to you George.

**George** ([24:32](https://youtu.be/HN_SNEC3dfM?t=1472))
Yeah we're making some pretty good progress we're pretty much like 95% done. I do some like security stuff we need to do…bug testing and we had like a meeting yesterday, we had some great ideas going on, so I’m excited to possibly implement those things as well, including like interactive video, and we have a few other contributors who could really help us out on the design side, so yeah it looks pretty exciting. 

**Pooja** ([25:12](https://youtu.be/HN_SNEC3dfM?t=1512))
Thank you George. Two things that we may need support there. One is POAP management, like we are looking for someone who can maybe take care of the issue inside and the other is the quiz. So we are trying to have 10 or so questions for each quiz so we can shuffle them and the user may not get the same question, if they are trying to take the quiz for the second time. So yeah, any support we can get in that direction, that would be helpful. You can get all the information, those are available on l2e channel at Ethereum Cat Herders discord. Check out the pinned notifications. That's all on learn to earn. The next one is cat blazers ECH podcast. William Schwab, if you may have any update on there?

### Cat Blazers ECH Podcast

**William** ([26:12](https://youtu.be/HN_SNEC3dfM?t=1572))
I've been in a bit of a lull as far as the podcast has gone, I am trying to get back to it. Some of it's just still settling into a new job and some other stuff with that um other than that, I def I have been still there there's also a certain amount of passive but something close to passive onboarding work, either getting people reaching out to me or things like that, just try and help them kind of find their way in this space, but it has been kind of a quieter month on that front. Also kernel is interactive so that also kind of inherently means that I won't be as upfront.

**Pooja** ([26:52](https://youtu.be/HN_SNEC3dfM?t=1612))
Thank you William for updates and talking about podcast recently, we received some requests from foundation that we are making videos of people, those are educational and many time it happens that because it is only available on YouTube many people are not able to find that or maybe follow that so they have requested if we can probably make a podcast version of this video series that we are running so I’m in touch with zkdoof…

**William** ([27:24](https://youtu.be/HN_SNEC3dfM?t=1644))
What's good we've been talking about the best way to do it like where we're I mean would that be just like audio content of the previous PEEPanEIPs, because like so much of that seems based off of the presentation you know like I know it could that could this could be a conversation we take offline if you want I don't want to necessarily take up time in the meeting over it but I know something I was chatting was just like how do we take something that has this strong visual element and make something useful as well.

**Pooja** ([28:03](https://youtu.be/HN_SNEC3dfM?t=1683))
That was my concern as well and I tried to mention it, the response that I received was like, in the beginning of the podcast we maybe mention it like this is an audio version of a video recorded which is available at Ethereum Cat Herders YouTube, so if you want to follow, you can follow the link and then start the conversation of the earlier videos but for the upcoming PEEPanEIP maybe we would like to let the guest know in advance that there can be possibly an audio version of that so try to be more like using more words to express whatever is there in the presentation. However there is no way to probably show the picture, the chart, and the block diagram that they are explaining, yeah.

**William** ([28:47](https://youtu.be/HN_SNEC3dfM?t=1727))
So I mean for previous episodes like maybe recording something and putting it in the beginning and maybe we used that moving forward also but then also I guess you're saying for future guests just to say there may also be people who listen without watching yeah that makes sense to me.

**Pooja** ([29:06](https://youtu.be/HN_SNEC3dfM?t=1746))
Right, so we are still exploring ways how to get it done for the past episodes because the audio quality was a concern, so we are still working on that maybe for future videos so it might take some time to maybe come up with the concrete plan, but maybe we can take it offline yeah, you me and zkdoof we can think more about it and see how we can have this audio version available for people who want to listen to podcast.

### ECH Operations

**Brent Allsop** ([29:52](https://youtu.be/HN_SNEC3dfM?t=1792))
If we're moving on to ech operations I finally got access to the zoho account so I can now create um anything at ethereumcatherders.url.

Brent, William and zkdoof will communicate on discord to get an email address for Cat Blazers Podcast. 

**Pooja** ([31:27](https://youtu.be/HN_SNEC3dfM?t=1887))
Thank you Brent I was wondering like if it worked out or not because I was also doing it for the first time but it did work. All right any more updates on operations?   

**Metago** ([31:48](https://youtu.be/HN_SNEC3dfM?t=1908))
I was thinking of having the new joiners meeting again this month but we can talk about it offline regarding the date, I think two people signed up on the google, on the onboarding form so and one of them was introduced by Ken and he messaged me about it today. So I’m guessing that at least one person would be interested in joining the meeting so we can talk about it later, but I was thinking around May 27th.

**Pooja** ([32:26](https://youtu.be/HN_SNEC3dfM?t=1946))
Right, all right maybe we can have a chat about this, because if we are having a meeting, we would like to have more than one or two participants joining it, because video recording is always available for people to go back and refer to so if we can try to engage more people with questions. I was also considering like should we kind of make the cat herders meeting part of it like 30 minutes or 15 minutes especially dedicated to all these new joiners. 

**Metago** ([32:50](https://youtu.be/HN_SNEC3dfM?t=1970))
Yeah that's also a good idea since it would be introducing them to the whole group.

**Pooja** ([33:06](https://youtu.be/HN_SNEC3dfM?t=1986))
Right all right maybe we can chat a little bit more about it offline and then update rest of the people here in the group.

**Metago** ([33:12](https://youtu.be/HN_SNEC3dfM?t=1992))
Sounds good.

## EIP Insights

**Pooja** ([33:17](https://youtu.be/HN_SNEC3dfM?t=1997))
Okay moving on and the next item is the EIPs Insight. I have added up till May 9th, till yesterday. This time the Insight has a couple of new charts to display EIPs in different categories and in the status of draft and final, we have got nine new EIPs as draft so far, three potential proposals are yet to be merged and two EIPs of ERC category are promoted to review. Four EIPs are moved to stagnant due to inactivity over six months and one proposal 1967 standard proxy storage slot is in last call. There was some modification to the proposal. Because of that, the because of that it has a new last call ending period and that is 14th of May so anyone if you have any comment question suggestion on this proposal please try to reach author on discussion to link and get that updated. That's all about EIP's Insight. You can find the details in the link that is added to the agenda.

## PEEPanEIP ([34:40](https://youtu.be/HN_SNEC3dfM?t=2080))
Next one is PEEPanEIP and we have released a video talk on EIP 4626 tokenized world standard with Jet Jadeja early this month. Today we have a plan meeting for EIP 3540 and EIP 3670, both are EVM proposals which are expected with Shanghai, and the guests are the co-authors from a team Epsilon. Later this month we have EIP 1202 which is voting standard, and we are also trying to reach out to client teams to check out their preparation for the merge, like the readiness for the merge and the first meeting on that is with basic client on May 31st. Please check out their schedule and that is added here for upcoming PEEPanEIP meetings. 

## Meeting Notes & Action Items for ECH ([35:34](https://youtu.be/HN_SNEC3dfM?t=2134))
Next one is a meeting notes and action items for ech contributors. I know Santosh you mentioned something you wanted to share with us so if you would like to…

**Santosh** ([35:46](https://youtu.be/HN_SNEC3dfM?t=2146))
Yeah sure. Like last time I mentioned right, like it might be really difficult for you to review like 15 pull request alone for yourself. Maybe we can do one is pairing, like for me there'll be one person who will always review my peer and I can review this or appear every time so we can align on that or we can have one person who will ensure that the or she will review all the pr together right it basically needs like two to three hours where you need to go through the entire video and ensure the content is right and if the action items are verified that should be it, and give the suggestions right, so we can do either way, whichever works out. Happy to take suggestion here.

**Pooja** ([36:43](https://youtu.be/HN_SNEC3dfM?t=2203))
So I was  discussing this…with the pm team as well Ethereum pm team as well and their recommendation was like because we are already paying for the notes, documenting of the notes, someone spending another two or three hours going through entire notes may not be that valuable even not for that person worth spending that amount of time so what we can do here is maybe check it out on the high level very high level that the formatting is right, the discussion items and sorry, the decision items and action items are listed, we have the time stamps and the recommendation was we should have time stamp per speaker, and that is easily available because we are now getting captions and captions has the timestamp so if we can add that so even if there is minor mistake in notes and it's not clear to the reader, maybe he can just check out and validate it is so oh yeah that was the idea but um yeah open to other suggestion if people think that's like spending this amount is okay, I don't know let me know.

**Brent** ([38:05](https://youtu.be/HN_SNEC3dfM?t=2285))
Yeah I think that's good especially if people have a way if they if someone sees an issue somewhere and can like get it to us or fix it themselves in a weekly kind of way then that that that could solve a lot of the problems too without a lot of extra work I would think.

**Pooja** ([38:27](https://youtu.be/HN_SNEC3dfM?t=2307))
Right, and I think we maybe want to list all the check items like what all we want to check when we are reviewing notes if that is handy then people can be a reviewer anyone who are already augmenting notes.

**Brent** ([38:40](https://youtu.be/HN_SNEC3dfM?t=2320))
Yeah, thats a good idea. 

**Santosh** ([38:46](https://youtu.be/HN_SNEC3dfM?t=2326)) 
Sure, maybe I’ll add the faq that what needs to be taken care of the time of review and everyone else can add to it.

**Pooja** ([38:53](https://youtu.be/HN_SNEC3dfM?t=2333))
Thank you so I think we have notes for two meetings no in fact three we received the consensus meeting notes this morning so only one EIPIP meeting notes are missing. I have to check with the person documenting that, but again a request to the notes documenting community please try to submit your notes within the first five days of timeline. That is very important so if you are for some reason unable to do that, will be able to engage another community member. It would be an opportunity for other people to learn and may be able to be a regular contributor in future and also it will create a standard that will set people's expectation that notes are available within this period of time frame. That being said, we are looking for more people to document notes especially for all core dev meeting and the consensus layer meetings. These are the important meetings and we have only two contributor on list as of today, so if you are interested in documenting notes please reach out we do have certain bounties associated with a documentation of these notes so reach us. We'll hope to have you on schedule. 

### Review of outstanding action items from previous ECH meetings ([40:39](https://youtu.be/HN_SNEC3dfM?t=2439))

The last item for today's discussion is review of outstanding action item from previous ECH meeting 83. Okay, I think there is only one decision item, there is no action item mentioned and it is like we may use radical.xyz to back up, but it looks like we do not have a concrete decision on that. We may be spending a couple of more weeks to decide like maybe radical or arweave, or both so we'll keep this item on discussion for the next meeting. I think that concludes everything listed here. Anyone has anything else to bring up for today? Well thank you so much everyone for joining us, I hope to see a communication going on the general channel for the Ethereum Cat Herders discord or any specific channel…if that is there…if you are working on a specific project…so yeah nice to have you today. Hope to see you in two weeks. Have a good one everyone, thank you. 

## Attendees

* Pooja Ranjan
* William Schwab
* George Harvey
* Metago
* Brent Allsop 
* Santosh




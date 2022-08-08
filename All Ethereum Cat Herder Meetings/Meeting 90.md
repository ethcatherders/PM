# Ethereum Cat Herder Meeting # 90
### Meeting Date/Time: Tuesday 2 August 2022 at 15:00 UTC
### Meeting Duration: 29:36
### [GitHub Agenda Page](https://github.com/ethereum-cat-herders/PM/issues/305)
### [Audio/Video of the meeting](https://www.youtube.com/watch?v=5JWFS7-zBhc)
### Moderator: Pooja Ranjan
### Notes: Metago

---

## COMMUNITY PARTICIPATION 

**Nodes Upgrade**: If you are running node either on execution layer or on client layer, or you are planning or you are already a validator, please upgrade your node. You will find the latest version of your client in the EF blog post, so check out the blog post and upgrade your nodes accordingly. 

**Ruby Dev**:  If you are a Ruby dev interested in helping out with EIPs and Ethereum proposals, please reach out to us.

---

# Agenda

## 1. Ethereum Network Upgrades

### [The Merge](https://ethereumcatherders.com/the_merge/), [Goerli-Prater Merge Announcement](https://blog.ethereum.org/2022/07/27/goerli-prater-merge-announcement/)

**Pooja**[0:00](https://youtu.be/5JWFS7-zBhc)

Welcome everyone to Ethereum Cat Herders meeting 90. I have shared agenda in chat. Thank you for joining everyone. Let's begin with the first item listed here, and that is Ethereum network upgrades.

As we know, we are very close to Merge. In one of the earlier consensus layer meetings, developers sketched a tentative date for the mainnet merge, which is somewhere in mid-September. The date that was announced or was expected is 19th September, however this is not  a final date, it has to be in week of that, but that will depend on how we are making progress. Two public testnets have already been merged successfully and we are almost set with the third and the final public testnet combination that is Goerli and Prater. 

This is planned in next few days, so a Goerli Prater Merge announcement is released. I have added the link to the EF blog post in our agenda today, so after the merge, the testnet will be renamed as Goerli. It will be merged with Prater, but will be called Goerli post merge. Bellatrix is expected to happen at 112,260 epoch number, which is estimated on August 4th and after Bellatrix is activated, the Goerli Prater merge will happen when the TTD is hit and the TTD announced here is at 10,790,000 and it is expected somewhere in between 6th to 12th of August so definitely in next 10 days, we are gonna see the merge of the third and final public testnet, Goerli Prater. Anyone listening, if you are running node either on execution layer or on client layer, or you are planning or you are already a validator, please please please upgrade your node. You will find the latest version of your client in the EF blog post, so check out the blog post and upgrade your nodes accordingly. That's on the upgrades. 

## 2. New initiatives[2:43](https://youtu.be/5JWFS7-zBhc?t=162)
### ECH GitHub backup & YouTube backup

Moving on, item number two, it is a new initiatives though we are already working on it, the first one is ECH GitHub backup and YouTube backup. I know we made some progress last week and we have zkdoof on the call. zk, if you would like to share update on that side?

**zkdoof**[3:01](https://youtu.be/5JWFS7-zBhc?t=181)

Yeah, so for the GitHub backup, we identified a few pieces of the GitHub like issues etc that would not be backed up to Radical, if we just used the Radical approach, so the web scraper is up and running. We will be scraping those web pages and archiving them onto arweave. Their second portion of it, which is the Radical backup, at that part I still need to talk to William Schwab, and see how we get that up and running and the third part, the YouTube backup, we have identified our solution as lenstube, where we will be doing that backup, or at least testing to make sure everything works as expected. When we get the funds approved, we will upload one video, check to make sure that it falls under the limit of file size that's set by lenstube and make sure that we can retrieve the arweave transaction id directly onto arweave and make sure that we don't need lenstube but we can take advantage of lenstube as a front end so all that testing is going to be starting pretty soon, but the web scraper is already up and running.

**Pooja**[4:16](https://youtu.be/5JWFS7-zBhc?t=256) 

Thank you for the update, just for a general understanding, I understand this can be one time approach for like backing up the content that we have so far. Going forward, what is the frequency that we are expecting for this, like the general backup?

**zkdoof**[4:38](https://youtu.be/5JWFS7-zBhc?t=278)

So I think we can set the frequency to whatever we would like, the largest effort is you know upfront immediately doing the full backup but then it becomes a lot lower of a task to just keep things backed up, you know, every month. We can batch it in quarters if we would like but, you know as long as we identify the information we want to back up we can set the frequency as desired.

**Pooja**[5:05](https://youtu.be/5JWFS7-zBhc?t=305)

Sounds good. Thank you. Let's see how the trial with the first one goes and accordingly we can have our plan set for future backing up. All right so that's on backup.

### [Create an ECH Calendar. #303](https://github.com/ethereum-cat-herders/PM/issues/303)[5:26](https://youtu.be/5JWFS7-zBhc?t=326)

The next item here is create an ECH calendar. So a community contributor, X I N B E N L V, I am trying to call him Xin. So he created a calendar for Ethereum Cat Herders and he has added all the meetings. People can see that on issue number 303, they are already added on calendar and this is a good calendar for people who want to participate in meetings organized by ECH Cat Herders, because we were not having a public calendar. We used to manage using discord event, so now this is something that people can subscribe to, so thank you so much Xin, for creating this calendar. I will pin it on general channel so anyone new can also follow the calendar there. 

## 3. Events & hackathon[6:30](https://youtu.be/5JWFS7-zBhc?t=390)
### [Devcon session ideas](https://hackmd.io/-hWk6rw4QYecUZ0MiJML_Q?view)

The next one is Events and Hackathons. The first one listed right here is Devcon.  Devcon is one big event by Ethereum community and we know there is a lot of preparation needed. For that we are joined by Anett today. Anett has some ideas and she has listed it here in this Hackmd file, which I have added to the agenda. So Anett, if you would like to maybe talk about it?

**Anett**[6:55](https://youtu.be/5JWFS7-zBhc?t=415)

Yeah, thank you for introduction. So hey guys don’t think if you guys remember but last year…not last year, the year before in Osaka, we collaborated with Ethereum Cat Herders on some sessions in Devcon and this year we would love to organize some sessions as well, and we would love to collaborate with Ethereum Cat Herders on that, and let me share a link for the document where it describes more information about our plans, but I mean I have some ideas but there is a hackmd document we just shared with the people at Devcon which we are trying to get some room and host like a full day event sessions. The sessions that are planned right now with cat herders is like Ethereum founding of protocol operations which is like my idea, but I would love to get probably more feedback of like what kind of sessions you guys would like to host and, give me a second I just need to find the link to the document to share it to here, okay, let me one second...

**Pooja**

I have added in the chat. 

**Anett**[8:23](https://youtu.be/5JWFS7-zBhc?t=503)

Okay yeah thank you so much so that's where you guys can find more information but we are very open to learn more feedback of what kind of sessions we should host but we would love to do more of like fishbowl sessions and open sessions as well but also very open to like final discussions and if you guys have idea of what kind of session we should host with Ethereum cat herders, I’m very open to hear that because for example the two years ago we had to get a session with each like Ethereum magicians and Ethereum Cat Herders, from Ethereum Cat Herders, it was Hudson and Tim Beiko and the EEA was the ethereum enterprise…and we've been talking about Ethereum like the community and how we can work with the community itself more which was pretty cool session and did I share with you push a link to the forum post where…okay anyhow I will add it to the GitHub repo of to the issue of today's meeting, the link to the article which is like recap where you guys can sign recordings of the la the two years ago Devcon if you guys want to check it out for inspiration but we would love to know something around the same lens and it's pretty much…thank you. 

**Pooja**[10:09](https://youtu.be/5JWFS7-zBhc?t=609)

Thank you so much Annett for sharing this. I know we have people and we have one contributor who is also one of the organizers of Devcon so yeah people check out the document if you have thoughts on ideas like how we can make this event more entertaining and more information based let us know and we can probably try to add that. Okay so that's on Devcon session. 

### [At Ethereum.org](https://ethereum.org/en/community/events/) [10:47](https://youtu.be/5JWFS7-zBhc?t=647)
[ETHSeoul Aug 05-13, 2022](https://2022.ethseoul.org/)
[DeFiCon Aug 11-12, 2022](https://deficon.nyc/)
[ETHMexico Aug 19-21, 2022](https://mexico.ethglobal.com/)
[DeFi Security Summit Aug 27-28, 2022](https://defisecuritysummit.org/) 

Moving on from the calendar, okay from the calendar of Ethereum.org, I have listed out a few events which is planned for Ethereum community. One is ETHSeoul that is happening from August 5th to August 13th, Deficon, August 11th, 12th, Mexico, August 19-21, Defi Security Summit, August 27 to 28th. Link to all these events are added to agenda. If you are in that location or if you are participating, or if you would want to participate, please check out the link and if you have more information of something happening in your neighborhood, or in your location, geographic location, feel free to share it with Ethereum Cat Herders, and we'll be happy to share it with the rest of the community, so we can get more participants. Any question, comments so far?

## 4. ECH updates 
### [ECH Website](https://www.ethereumcatherders.com/)[12:00](https://youtu.be/5JWFS7-zBhc?t=720)

All right, moving on, the first one is ECH website. So I’m in touch with someone, I’m trying to update the website. You made a pull request, but seems like it wasn't perfect but I have suggested some correction there, let me see if for that is like completed. I hope that we will fix the errors in the first pull request and make either and make another pull request or make another comment but yeah we'll try to update the website as soon as possible. 

 ### [ECH Engineering](https://github.com/ethereum-cat-herders/PM/issues/266) [12:42](https://youtu.be/5JWFS7-zBhc?t=762) 
 #### [EIP bot](https://github.com/ethereum/EIP-Bot/issues) & [EIPV](https://github.com/ethereum/eipv/issues) 
 
On ECH engineering, looks like we made some progress and now we do not have EIPV. I mean obviously EIPV is still there but we are making use of EIPW and yeah we have Jose on the call who has been looking into EIP bot issues, Jose if you would like to share anything? 

**Jose** [13:04](https://youtu.be/5JWFS7-zBhc?t=784)

Yeah, hello, well yes, finally we managed to get a testing environment, now we need to test that environment with the actual pr. We will be doing that in the the couple of, the next couple of days. We have two prs to test. We will start with the PandaPip pr which is…suggestion for the other pr already have the candidate for the EIP that we're gonna use as example. So let's see. We feel optimists. I said we because I need to recognize that Micah has helping me as usual, a lot, but we will get there, we will finally get a clear way to define a testing environment for the boat and we presume that for anything that runs similar with the into the ecosystem let's see but looks like we're gonna get some real progress, that's the bottom line. Thank you. 

**Pooja** [14:21](https://youtu.be/5JWFS7-zBhc?t=861)

Awesome, thank you so much for update and it's really good news that we are finally making progress. We were having a lot of open issues on both sides, hopefully some of them will be resolved soon as we are good with the testing environment. 

#### [Learn2Earn](https://github.com/ethereum-cat-herders/L2E) [14:38](https://youtu.be/5JWFS7-zBhc?t=878)

Now on Learn2Earn, we had this meeting yesterday, yeah 25th meeting for learn2earn. Obviously we made a significant progress, we are close to the quiz master site as well, like it's almost done, currently working on our designing. A few designs were shared yesterday, if people interested they can watch the recording. You can find the link to the meeting notes on channel learn2earn on ECH discord, and yeah you can follow the recording to maybe suggest on design, if you have any suggestion, and yeah, there are few commits made last week on the user front-end side. I don't see George on the call but if you have any question, comment, concern, feel free to drop in the channel and hopefully we'll get answers over there. 

### [ECH Podcast](https://open.spotify.com/show/7dgxKMkSyy3HWtQW7OfqXA) [15:48](https://youtu.be/5JWFS7-zBhc?t=948)

The next item is Cat Blazers, ECH podcast actually. So yeah, I think zk may have some update and I don't know if William, you too do that. 

**zk**[16:07](https://youtu.be/5JWFS7-zBhc?t=967)

So for the podcast we've been uploading the know your client series. People seem to be liking it. There is the lighthouse episode that's going to be going out today at 12 o'clock, other than that I think we're just chugging along. 

**William**[16:26](https://youtu.be/5JWFS7-zBhc?t=986)

I haven't gotten back to my end of things yet I still do hope to do so someday. 

**Pooja** [16:34](https://youtu.be/5JWFS7-zBhc?t=994)

Thank you both for updates but you are definitely helping around William, in the back end with the backups and the funding side and everything else so yeah, but we would love to see you back on like recording and having podcasts like the usual interview model that you started. It was a great hit so we would love to see you back sometime. 

### ECH Operations [17:07](https://youtu.be/5JWFS7-zBhc?t=1027) 

Moving on, next is ECH operations and we have added all wallet tabs meeting here. So the last meeting happened on 27th I guess, and yes the recording is available, it seems like we have three weeks cadence, please correct me but there is some calendar available, ZK, you have more information on that?

**zk** [17:46](https://youtu.be/5JWFS7-zBhc?t=1065)

Yeah, so if you're interested in the All Wallet Devs meeting, I would recommend going into the discord. One of the pinned messages is the calendar and then you can add the calendar, your google calendar, whatever tool you use and see the cadence. I thought it was every three weeks but it's a little bit more sporadic than that. So yeah, recommended, just join the discord. One thing I’d like to add here is that we're still looking for people to join the interoperability test event, it's something that, you know, William Schwab and Heather were trying a while ago…so yeah we'd like to get you know any wallet devs or any middleware devs or any dapps to join in the test event, if you've known anyone you know point them my way I’d be happy to add them. 

**Pooja** [18:43](https://youtu.be/5JWFS7-zBhc?t=1123)

Awesome, thank you. People interested in wallet development, please check out the recording and if you have any points to be discussed you may reach out to zkdoof, Sam Wilson and maybe even drop a line in the discord channel that they have. 

### [EIP's Insight](https://hackmd.io/@poojaranjan/EthereumImprovementProposalsInsight)

Moving on, the next item is EIP’s Insight. In July, the EIP repository received 12 new EIPs as draft and 19 potential EIPs, like this was huge, like a lot of new EIP is coming, most of them are ERC's and they are also making progress. What I mean by that, out of these 19 potential EIPs which were introduced in the month of July, four made it to draft, like they were merged as draft and the EIPs which were added as draft, they were further promoted. Two of them before they promoted to review, eleven EIPs are moved to review status and one of which is like EIP 2400. This was an outcome of a URL URI meeting. We discussed about this proposal and community seems to be looking forward to have this proposal, in…final status so this proposal was resurrected from stagnant and is currently available for review. Two EIPs which were in review status have been moved to last call, so we have what five EIPs and last call and I believe at least for two of them last call period has been completed. Yeah please check out the end and the report for July for the status change of EIPs in the month. There are multiple improvements done on the repository and bot side as well. One major…actually couple of them…the major one are EIPW bot is replaced by EIPV…EIPW bot replaced EIPV bot and travis ci has been migrated to GitHub action. Check out the entire report, I have added the link in the agenda. 

### [PEEPanEIP](https://www.youtube.com/playlist?list=PL4cwHXAawZxqu0PKKyMzG_3BJV_xZTi1F) [21:11](https://youtu.be/5JWFS7-zBhc?t=1271)

For PEEPanEIP, upcoming meeting can be found on the schedule that is added here. We have one meeting planned for Akula. Akula is a rust implementation of Ethereum Blockchain. This is one of the latest implementation and is considered to be one of the fastest. We will be joined by Artem, who is the lead developer for Akula client. It is from the team of Aragon, so people if you are interested to learn more about it, please join the PEEPanEIP meeting tomorrow that is August 3 at 18 30 UTC. We will be having a recording of this meeting available for public in upcoming weeks. So know your client series is available on YouTube and podcast. As zkdoof mentioned earlier, we are almost done with eight clients, yeah ninth client that is deku, we will be sharing recording very soon. So if you are interested in learning about how clients are preparing for merge and what features are there for a client that you may consider to run a node if you aren't running already, please check out the know your clients series on Ethereum Cat Herders YouTube.

### [Meeting Notes](https://docs.google.com/spreadsheets/d/1axM1KaKc-GCcoPbAnYTOhgLnxXsBVoO5XRjTN3CLnck/edit#gid=0) and action items from previous ECH meetings [22:34](https://youtu.be/5JWFS7-zBhc?t=1354)

Okay, the next one is meeting notes and action items for ECH. I see we have received notes for all core dev meeting 143, EIPIP meeting 60, and we are waiting on cl meeting notes 92 but I am informed that it will be submitted by today EOD, so we can expect that to be going up soon. 

### Other Community Meetings

All right, and there are other few meetings. Those were organized by Ethereum Cat Herders. I mentioned about the URL URI meeting standard working group meeting earlier, so that is happening every two weeks. We have a working document in which we try to capture the notes in sense of like what was discussed in the meeting and what are the next items, next steps or you can also propose items for further discussion. In the last meeting we discussed about EIP 831. People are interested in moving this proposal towards final. This was earlier in stagnant, now it has been moved to review. To move this proposal further, there was a requirement for EIP 67 which is created and moved to withdrawn because EIP 831 mentions this proposal so it was needed to have this proposal on the repository. Thanks to Sam Wilson for creating and moving it to the appropriate status so we can further move EIP 831. Among other discussions, there is an ongoing discussion about idea for compact URL proposal, a fem thread is added to agenda, please check out and if you have any thoughts or you would like to participate in the conversation, feel free to leave your feedback and comment in the fem link added here.

We continue discussing EIP 2400 URL format for transaction resets and EIP 4804 which is web3 URL to EVM call message translation. Both of these EIPs are now available in review status so please check out proposal if you are interested in standards for URLs. Other than that we have EIP editors apprenticeship meeting. Recording is added here. Check out the recording in this meeting. We try to go through open pull requests and if there are any question comment or concern from any of the EIP author, we try to address that. So if you are an author, if you have proposed a proposal and if you have any kind of doubts please join us on EIP editor's apprentice meeting which happens alternate Tuesday now that we have the calendar ECH calendar. Thanks to the Victor, we can now refer to the meeting and yeah John, 

**Victor** [25:54](https://youtu.be/5JWFS7-zBhc?t=1554)

Yeah, thank you for mentioning that. Yeah if anyone wants to add any meetings or future I don't know if we have a criteria but I think our meetings definitely seems to be had on the calendar and if we want to we can also add like events and hackathons or other things that is, that we think it's worthy of noting, so yeah we I encourage everyone who have calendar items to add to it, I am happy to share the permission and also [inaudible] permission. 

**Pooja** [26:31](https://youtu.be/5JWFS7-zBhc?t=1591) 

Right well thank you for that and I mentioned earlier in this meeting that I’m gonna pin that calendar on #general Ethereum Cat Herders so anyone can subscribe to the calendar and if you have any requests for any meeting to be added maybe you can share there with us.

We also have a KZG ceremony breakout call number four. Recording for that is added. This is a research update call. People interested in like getting information on what's the progress on KZG side, please check out recording. We have a playlist for KZG ceremony on Ethereum Cat Herders YouTube. 

There's a question, could we share the calendar in discord? Yes I will do that right after this meeting on general channel or Xin, Victor, if you can do it earlier that is also fine. 

**Victor** [27:40](https://youtu.be/5JWFS7-zBhc?t=1660)

All right so can you can you add an action item, I’m not sure if I catch fully that can you add an action item I’ll share the calendar in the discord is that…

**Pooja** 

Yeah

**Victor**

Okay.

**Pooja**

Yeah.

**Victor**

I can do that yeah let me do it yeah 

## 5. Review of outstanding action items from previous meetings [27:59](https://youtu.be/5JWFS7-zBhc?t=1679)

Thank you and the last item is review of outstanding action items from previous ECH meetings. Looks like we don't have the notes and it looks like it was just slip through the cracks, we couldn't follow up on this one. I will try to have the notes available asap and if there is any action item from the past meeting, we will have them added in the next meeting and we'll go over them. So that's all from the items listed here on the agenda. Anyone else want to bring, share anything today? 

## Concluding Remarks

Thank you for messaging. I would have called on you that if you would like to share any information related to the event, but that's all good. Thank you Victor for sharing the link to the calendar and yeah I think we are caught up with everything listed here. Thank you people for joining us today. Hope to see you in two weeks. If there is anything in between please do not hold yourself, share that on cat holders discord and we'll try to get discussed further. Have a good one everyone. 

Everyone thanks Pooja. Call ends. 

## Attendees

* Pooja Ranjan
* Annett
* William Schwab
* Jose
* zkdoof
* Viktor















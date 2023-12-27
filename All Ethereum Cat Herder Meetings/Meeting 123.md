# ETHEREUM CAT HERDERS MEETING #123

### Meeting Date/Time: Dec 19, 2023 at 16:00 UTC
### Meeting Duration:  37 mins
### Moderator: Pooja Ranjan
### [GitHub Agenda](https://github.com/ethereum-cat-herders/PM/issues/382 )
### [ Audio Video of the Meeting](https://www.youtube.com/watch?v=gulaktRAf6U)

### Notes: Meenakshi Singh

# Agenda


**Pooja Ranjan** [0:00](https://www.youtube.com/watch?v=gulaktRAf6U&t=0s): Welcome to Ethereum Cat Herders Meeting #123. This is issue number #382 on Ethereum Cat Herders Github Repository. On agenda we have updates on Ecosystem Project Demo, Ethereum Network upgrades, protocol development and research. And we'll share some information on events Fellowship Hackathons followed by any new initiative or team discussion that people would like to have it here today. We also have a few General updates in terms of how we are doing on social media and the related links are also provided. We'll follow up with the meeting notes update and see if we have all of the notes available where we are on that. 
## 0. [Ecosystem Project Demo] Kurtosis
So starting with the first item actually the item number 0 which is Ecosystem Project Demo. So we are ready with the recording of Kutosis and a conversation done with Team of Kurtosis on what kind of support this project provides to the Etherum Ecosystem. I think the video recording should be ready to publish today. Santhosh quickly want to check with you if there is anything else missing or we we may need to delay the release. 

**Santhosh** [1:25](https://www.youtube.com/watch?v=gulaktRAf6U&t=85s): I think we are good. I saw your note on adding the timeline which it'll go ahead and do it after this call. So we should be good to publish it Today.

**Pooja Ranjan** [1:37](https://www.youtube.com/watch?v=gulaktRAf6U&t=97s): Very well and another related question is like do we need to have a podcast version of it? I remember we had a podcast version of the earlier EPD demo. So do we want to have that. Any thoughts  from anyone? 

**Santhosh** [2:02](https://www.youtube.com/watch?v=gulaktRAf6U&t=122s): Yeah I think if you just want to follow it. We can follow it and I'm okay with you though.

**Pooja Ranjan** [2:14](https://www.youtube.com/watch?v=gulaktRAf6U&t=134s): All right I don't see ZK on the call. I'll quickly check with him. I just think that he would need a wab file to have it processed. And get it uploaded on Ethereum Cat Herders podcast. And that would be easier for people who try to follow on audio only mode. And they are not very much into YouTube because on podcast. We are out several platforms thanks to George. We do have a page at ethereumherders.com/podcast Please check out to find where all you can find ECH related podcast. So I think we should be tweeting about it to today as well. Is that the
correct understanding?

**Santhosh** [3:03](https://www.youtube.com/watch?v=gulaktRAf6U&t=183s): Yeah Pooja.

## 1. Ethereum network upgrades


**Pooja Ranjan** [3:05](https://www.youtube.com/watch?v=gulaktRAf6U&t=185s): Perfect. Thank you so much. Moving on to ethereum network upgrades. So as we know Dencun Deneb and Cancun upgrade is currently on devnet 12. There is an Explorer I think I have added the link to it. People can check it out to follow the progress of Devnet 12. Briefly speaking the Devnet  contains all clients including prysm which was couple of weeks behind. But they are catching up now for testing. They have enabled MEV for most client except prysm. Prysm may not have enabled that this as on now and everything seems to be on track. Paritosh mentioned in the last client developers meeting that Lighthouse reported a bug on MEV. But that has been fixed. There also seem to be an issue on Besu node. They were trying to convert an invalid block to a valid block. But the team is looking into it. It seems like that was some corrupt database issue but that should be under control now. For Shadow For prysm Builder path may not be tested as of now. But it should be ready soon and on hive testing. It is done for all clients except prysm. But that should not be a locker like the overall result can let developers know how comfortable they are with devnet 12. And yeah we have added the block post of Goerli long-term support. As many people may know that Goerli expected to be deprecated by the end of this year.Developers have already launched Holesky testnet to maybe provide an alternate public testnet for people to test the upgrade as well as their daps in future. I hope we have a page for testnets. Please correct me George if I have mistaken it is a ethereumcatherders/testnet where people can find more information with respect to testnets available. 

**George** [5:53](https://www.youtube.com/watch?v=gulaktRAf6U&t=353s): Correct with an of present testnets. 

**Pooja Ranjan** [5:58](https://www.youtube.com/watch?v=gulaktRAf6U&t=358s): Very well. So yeah I mean people can maybe check out this page to get to know which all public testnets are available for usage and how long. Because there is there was this proposal of deprecating testnets at certain period of time to maybe have the advanced featured
enabled for projects to be testing their Adaps. Please check out the blogs published by ethereum foundation on replication of Goerli. 

### Meta EIPs for upgrades

**Pooja Ranjan** [6:33](https://www.youtube.com/watch?v=gulaktRAf6U&t=393s): Next item is Meta EIPs for updates for upgrades. Thank you George for sharing the link of testnets. So many people may know that Meta EIP were there for upgrades but that was deprecated a few years ago. I think after Berlin it was discontinued. And we started saving the list of proposals in a .md file at execution specs under the folder Network upgrade. But developers find it. It's useful to bring the Meta EIP back. And thus for the dencun upgrade. We have EIP 7569 which is hard for meta for Denon it's currently in review status. Obviously because we are still on devnet phase when we move on to public testnet it will be moved on to the last call status. But in order to fill the gap there is also another Meta EIP the number is 7568 which is to provide information that is missing. Since Berlin to Shapella upgrade. I think it is useful to have the list of EIPs at one place. And now after the merge especially we are seeing that proposals, EIPs are not only on the execution side only but they are also on Consensus side. So these Meta EIPs will be useful for people to follow all proposals at one place. And as Ethereum Cat Herders we also have provided information of this. And we do maintain a network upgrade page so people may follow ethereumcatherders.com/dencun to find the list of all the EIPs. Those are included in the Dencun upgrade as well as the devnet specs file which are there for every Devnets. 

### Dencun Interop Testing Call 35, 36
**Pooja Ranjan** [8:58](https://www.youtube.com/watch?v=gulaktRAf6U&t=538s): Moving on, yeah people may know that for Dencun we are having bi-weekly Interop testing call. So recording for call 36 and 35 both are added here. And from the call it seems like we will be moving towards the first public testnet in the month of January. 

### Prague/Electra Network Upgrade Meta Thread

**Pooja Ranjan** [9:26](https://www.youtube.com/watch?v=gulaktRAf6U&t=566s): I have also added the link to the Prag/ Electra Network Upgrade Meta Thread. Prague Electra is the name of the next Network upgrade after Dencun. And developers have started collecting EIPs that means EIPs are open for discussion and the selection of proposal will start happening early next year. So please check out the link if you have thoughts about EIPs feel free to share. And if you have suggestions for any other proposal that should be included in the next Network upgrade. It is always a good idea to share if that hasn't been shared already. There are other useful resources added on the agenda that also includes the list to the PEEPanEIP playlist especially for Dencun Upgrade.

## 2. Other Protocol Development & Research
**Pooja Ranjan** [10:25](https://www.youtube.com/watch?v=gulaktRAf6U&t=625s): On other protocol  development and research the first Roll Call meeting. I mean it is Roll Call 1 meeting happened last week. And in that meeting there was discussion on three proposals. The first one here is EIP 7212 but now it has been moved to Rollup repository. So that would be renamed as RIP 7212 at least that's my understanding. But we are still hoping to get some more clarity on that. This particular proposal is on last call and the next proposal which is RIP 7560 which is about Native account abstraction that's also under discussion. One of the concern that I raised on the call was the category of the Proposal. Both of these proposals at the moment are proposed as standard track core. Which seems inappropriate to me because the standard track course are generally for the Ethereum mainnet discussion is still open and we hope to hear more by the next Roll Call meeting. In the same meeting EIP 3074 Auth and auth call opcode was also brought for discussion. It seems like there is a strong desire to get this proposal implemented on Layer 2. Related developers are collecting feedback from projects. And we hope to see more implementation coming up. Verkle implementers calls are also ongoing. There is a verkle testnet in which the proposals for Verkle tree are being tested. It's not decided whether it will be a part of Prague Electra Network upgrade or not. But it is really interesting to learn about the research work. And the progress those are made towards the EIPs to make sure when they are selected for the upgrade. They are actually ready and partly tested. We do not have any updates from EOF implementers meeting. I think there is another meeting scheduled for tomorrow. Let me quickly check and confirm. Yes another meeting is scheduled for tomorrow December 20th at 1400 UTC. So perhaps we'll get more updates from there. And that completes on the protocol development and research part. Any question comment so far? Anything did I miss? 


## 3. Events, Fellowship, Hackathon

**Pooja Ranjan** [13:33](https://www.youtube.com/watch?v=gulaktRAf6U&t=813s): 
Very well moving on to the third item which is events fellowship and hackathon. As some of you may know that application for next Ethereum Fellowship Cohort 4 is open now. The last date is January 15. This is for protocol development and we are also looking for women participation. So I would request anyone who are interested in supporting Ethereum Protocol Development. Please share this information with as many people or organization or maybe universities and college as you can. We are looking forward to have a fresh Batch of protocol fellows who may be trained to you know be a developer a client developer one day. So it's pretty interesting. And they also have weekly standup if people have questions they can join the Eth R&D channel. Protocol fellowship and their questions can be answered. Last week I had a conversation with students of consenSys Academy with respect to EIP process. So as some of us May know that EIPs are increasing. We are getting a number of proposals. We now have three different repositories. ethereum/EIPs , ethereum/ERCs and ethereum/RIPs under all these three categories as of now we do have about 715 proposals listed. And it is really interesting to learn about the process. And may be able to contribute as a reviewer as an external reviewer. And maybe an aspiring editor. Please reach out to us if you have any interest. We organise meeting as a EIP editing office hour to learn more about the process. And learn more about editing and also EIPIP meeting in which we talk about the governance process. So if there is any interest, reach out to Ethereum Cat Herders or join the meetings. And yeah I have shared this link there they are talking about Network upgrades and other stuff. I find this is useful. This course is free for anyone to join and yeah get the information. 

### ETH CINCO DE MAYO - Feb 2nd-4th, 2024
**Pooja Ranjan** [16:24](https://www.youtube.com/watch?v=gulaktRAf6U&t=984s): 
Last week we were approached by an ethereum contributor. I think he's a contributor from Spain if I have not mistaken and he has shared a Hackathon that is being organised. It's ETH CINCO DE MAYO. I have added the link and they have invited application for Hackathon participants or anyone from Ethereum Cat Herders. If they are around and they are willing to maybe talk about ECH or EIP process please reach out to us. Reach out to me. I'll be happy to put you in touch with the user or with the team. Or if you would want you can directly apply from the website link added here. The event is planned between February 2nd to 4th but there would be side events starting from January 30th. 

### Eth Denver - Feb 23 - March 03, 2024

Similarly ETH Denver is approaching it is planned on during the week of February 23 to March 3rd anyone from the Ethereum Cat Herders team planning to visit Denver. Please let us know. We do have a channel for event collaboration. We can perhaps talk and if possible we can have I don't know Booth Workshop or anything people are interested. Do we have any thoughts around connecting over the ETH Denver anyone from here planning to join at
least. I think last year, not last year 2023 itself, we did have a team dinner. And I would hope to meet more contributors if they would be there. Thank you, George. If we can see more people and more contributors over there. Then it would be really nice to meet people in real life. And yeah we can definitely plan something over there. I don't know William if we can
have a group call if we do then we'll try to make it like camera on call. So at least we can see people there.  

### Eth Berlin - May 24-26, 2024
Similarly there is the link provided for Eth Berlin. The event is planned for May 24th to 26. Anyone around planning to participate for hackathon or represent Ethereum Cat Herders. Please let us know and check out the link for more information.
## 4. New initiative/association/team discussion
**Pooja Ranjan** [19:33](https://www.youtube.com/watch?v=gulaktRAf6U&t=1173s): Moving on to the next item which is new initiatives associations and team discussion. I don't see the contributor with respect to Chinese subtitle of Peep Videos. But I remember receiving the talk I hope this is still work in progress we'll try to get more information and share it with the
Team. 
About the ecosystem project demo as far as I know Kurtosis episode 7 is going to be up today as we discussed earlier. Do we have any planned EPD for upcoming weeks that we can share?

**Santhosh* [20:17](https://www.youtube.com/watch?v=gulaktRAf6U&t=1217s): We have been chatting with one of the dev. Maybe I'll confirm it in a day of time.

**Pooja Ranjan** [20:26](https://www.youtube.com/watch?v=gulaktRAf6U&t=1226s):  It sounds good and I think ZK recorded a conversation with Mika but we are yet to get the video will check with him. So I hope that should be ready for the upcoming week to be added. Okay so that would be episode 8. It's good that we are getting projects information made available for community. On Meet the herders. I don't see haresh on the call but as far as I am aware the video is ready with the conversation with William. Thank you William. And we should be able to release its video podcast and the medium version. Just that Haresh has some limitation he is moving houses. So he will be more active in the month of January but in the meantime we will try to release whatever we have got and yeah he is planning to get interviews with other contributors of Ethereum Cat Herders. And yeah he'll be pushing recording until December 28th sorry January 20th. So for the month of December. I think we have one recording ready that will be going out. And we will get a new recording in the month of
January. That's the update from his side. All right. I think that is it any potential new ideas for Community engagement. We'll be happy to have here anyone has any thought they can share it in this meeting or maybe later on the Discord Channel. Whatever works best.


## 5. General updates/discussion

Moving on to general updates and discussion section. We have shared stats on Twitter Discord YouTube and Linkedin.Recently ZK shared a bunch of stats from the Spotify I guess. And I'm hoping to have a presentation maybe early next year with all these details that we have collected so far. But on highlight side it seems that PEEPanEIP episode 103 which is MEV boost related conversation with Alex Stokes was top of our episodes that has been viewed. And we have about 419% more than average episodes that was streamed during the last quarter. The conversation on ERC 4337 account abstraction using Alt mempool with Yoav Wise was kind of Milestone they started bringing our lessons back. And yeah we are doing really great on that side. I hope to get more stats and a formal presentation on growth metrics by ZK. Maybe in the month of January. So yeah that's good thing. On ECH engineering, I know we are joined by George and also Derigov. Maybe George if you can provide us the updates on Cat Herders website where we are? 

**George** [24:19](https://www.youtube.com/watch?v=gulaktRAf6U&t=1459s): Yeah so MEV PR is basically just making some fixes to part to the website. There's some missing things especially in the navigation, that kind of patches that. Just mainly just quality of life stuff not really like any big updates so.


**Pooja Ranjan** [24:46](https://www.youtube.com/watch?v=gulaktRAf6U&t=1486s):  Very well. Thank you. I think it is PR 132 and I suppose it is merged now. And another thing that I wanted to talk here about the the update of website. We recently had some discussion about migrating and we are joined by Derigov.  So I was wondering if we can get support from him so if he can maybe provide some high level idea of what we are hoping to do here. And may be able to invite some of the contributors to contribute helping move on to this new website sooner. 

**George** [25:26](https://www.youtube.com/watch?v=gulaktRAf6U&t=1526s): Yeah sure I can give like a quick high level overview of kind of like the thought around. I guess you could call it the V3 website. Essentially the look of the website won't change at all. Nothing changing in the design it would just be the architecture in the back where instead of using pure CSS JavaScript and HTML. We move to something like next JS. Where we get have more modular components and be easier to update and maintain in the future. So that should resolve some headaches and a lot of the redundancies that happen right now when it comes to making updates to the website. Where if you make one update to one page especially if it's something with the navigation you're going to have to update every single one of those pages. So if we break this down to more modular components like done in react and next JS
then we only have to change one file. And it's a lot easier and faster. So that's the idea behind it. 

**Pooja Ranjan** [26:44](https://www.youtube.com/watch?v=gulaktRAf6U&t=1604s): Very well thank you for sharing. I hope to get some contributors to maybe help out with this page. And yeah we can start working from January towards it. But in the meantime we should try to look into the L2E if possible. You think you could use some support over there or where we are on 
that front. 

**George** [27:15](https://www.youtube.com/watch?v=gulaktRAf6U&t=1635s): Yeah that's been like a slow start moving it. I think help can be beneficial. I don't have a clear guide on where though so.


**Pooja Ranjan** [27:29](https://www.youtube.com/watch?v=gulaktRAf6U&t=1649s): No worries. Yeah maybe we can pull people on channels. Where we do have on Ethereum Cat herders website Channel and L2E channel we can start pulling people. Anyone interested to contribute on either of the pages? And yeah I do see design available for Meet the Herders but we do not have for EPD yet. We hope to get the design up ready soon. I guess NFT design is ready. Questions are ready. We are working on UI Design site. Anyone interested to contribute on Learn2Earn web page UI design. It is going to be very similar except we are moving out of Morales this time. Please reach out. On ECH operations. Okay before we move ahead I see a message on the chat minor issues that can be easily done. Okay is there any specific issue or peer that you have created or the team has created on the etherum cat herders github that you would like us to. Maybe take a look feel free to add the link here and yeah we'll get it reviewed and merged as soon as  possible. Okay on ECH operations we have been adding YouTube Shorts and Community playlist. We do have ECH podcast that shares the audio version of the meetings that we conduct on EIPs Insight. If we take a look at the website we do have three tabs now. One is for EIPs GitHub repository next is ERCs and RIPs. On EIPs side we have two proposals in last call and two proposals in draft and review respectively. Proposals on last call are 6122 Fork ID checks based on the timestamp and the other one is 6953 that is an informational EIP on network upgrade activation triggers. I personally find this particular proposal really interesting for people who want to follow up our Network upgrade activation process and want to learn more about the blocks. Both on the execution and consensus side this informational EIP provide a lot of
useful information with respect to network upgrade. So please check it out. 

On ERC side we have six drafts, one review, two last call and three proposals in final status. Congratulations to the author of the proposals EIP 3643 that is T-Rex token for regulated exchange EIP 6982 efficient default lockable token and EAP 7066 lockable extension for ERC 721. I'm sorry these can also be called as ERC's instead of EIPs. The good news here is we have organized PEEPanEIP call for ERC 3643 and ERC 6982. So please check out
the schedule for PEEPanEIP meetings. ERC 6982 is planned for tomorrow December 20th at 18:30 UTC. And T-ReX token will be in the following week. We do not have any proposal as such on RPS inside more so because we do not have the formation of particular folder although proposals there are. In early stages that hasn't been merged as a draft and the other proposal that moved from EIPs to RIPs are still to be merged. So we are just waiting and once it is there I hope the website will be updated to provide you the latest information on all the proposals. We already mentioned about the upcoming meeting for PEEPanEIP. So please check out the calendar link added to the agenda. 

### ECH Funding

**Pooja Ranjan** [32:21](https://www.youtube.com/watch?v=gulaktRAf6U&t=1941s): Moving on to ECH funding for octant Epoch 2. I have submitted the application as well as the requirement of providing updates to be participating in Epoch 2. In the last Grant round we received around, it's 8, I guess 8 ETH. Thank you team EPOCH. And I hope the information
provided there may encourage validators to contribute their share of Revenue with us to support Ethereum Cat Herders working. Optimism RPGF 3 round has been completed. I suppose we received support from over 76 ballots. We received generous support. I am not aware of the result yet we will get to know more in upcoming weeks. We haven't participated in Giveth and CLR and even in the Gitcoin Grant 19. Yeah there are some offline chats about the last Gitcoin Grant round. Maybe we can connect in the Ops Channel. Yeah very well. Anything else over here? People have any suggestions any thoughts or any other funding Grant round. They are available where Cat Herders may participate. Please feel free to share with us. 

### Meeting notes and action items for ECH

**Pooja Ranjan** [34:02](https://www.youtube.com/watch?v=gulaktRAf6U&t=2042s): Moving on to meeting notes and action item. I see notes for ACDE 176 is available. We are working on ACDC 124 and EIPIP 96. Hopefully they will be up soon. Recording to last EIP editing office hour and agenda for the next meeting are added here. If you have a proposal and pull request in any of the three GitHub repositories for ethereum proposals. Please share the link in the agenda if you have questions you want to know what's blocking your PR or if you have any questions related to making the PR itself. We are joined by editor Sam Wilson to answer all these basic question to help authors make their proposal move as fast as possible. With that I think we are at the end of the meeting. Anything else anyone would like to bring up. Please feel free to share and also our next meeting is on January 2nd. I wonder if people want to keep that meeting or they want to skip it totally open for both any thoughts ideas.


**William Schwab** [35:54](https://www.youtube.com/watch?v=gulaktRAf6U&t=2154s): Yeah I'm find out way personally. I was just kind of wait waiting to see what other people say. And I'd say keep it then doesn't really seem to be anybody against. Do you want the time off like I mean I don't want to it there if people actually want it off but yeah all right. So let's do it then.

**Pooja Ranjan** [36:17](https://www.youtube.com/watch?v=gulaktRAf6U&t=2177s): Yeah let's keep it. So we are going to keep it at January 2nd 1600 UTC. 

So thank you everyone for joining us here today. I suppose this was the last meeting for this year. So wish everyone a very happy new year and holidays. 


### Next Meeting Date/Time: January 2, 2023 at 14:00 UTC

## Attendees

*Pooja Ranjan
*Santhosh
*George Herbey
*William Schwab



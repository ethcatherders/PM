# Ethereum Cat Herder Meeting # 107  Notes
### Meeting Date/Time: Tuesday  25 April 2023 at 14:00 UTC
### Meeting Duration: 0.5 hour
### [GitHub Agenda Page](https://github.com/ethereum-cat-herders/PM/issues/348)
### [Audio/Video of the meeting](https://www.youtube.com/watch?v=bhtmxpVfr6M)
### Moderator: Pooja Ranjan
### Notes: Avishek Kumar

----

## DECISIONS & ACTION ITEMS



------------

**Pooja Ranjan**[0:02](https://www.youtube.com/watch?v=bhtmxpVfr6M&t=02s): Welcome  to ethereum Cat Herder meeting 107. Today on our agenda our general discussion on Ethereum network upgrades, Event Fellowship and Hackathon progress on initiatives that were discussed in the past meeting and few other stats related updates with respect to Ethereum Cat Herder

# 1. Ethereum network upgrades

- Cancun & Deneb upgrade

**Pooja Ranjan** [0:22](https://www.youtube.com/watch?v=bhtmxpVfr6M&t=22s): Starting with the first one that is the Cancun and Deneb upgrade. We are expecting this upgrade sometime this year. [0:31] 4844 is the centre EIP around which we are hoping this upgrade to be deployed and along with that we would be considering a few other proposals depending upon the bandwidth of the client development team. So proposals are currently under discussion.

0:54
EOF and few other proposals are already under discussion and there is EOF implementers bi-weekly call that  happens. I have added the last meeting recording here. As I mentioned 4844 is also being discussed over the client development team and currently that is closer to
devnet 5 like implementations are being tested on client Devnet in the last ACDC meeting. A few other proposals were discussed to be considered. One of those was EIP 4788 which is the Beacon block route in the EVM. It was proposed by Alex Stokes and a client thought that it is a good proposal. It's a short proposal but there were no decisions taken on the proposal to be added in the upgrade. We are hoping for some more discussion at the ACDE meeting this week. Probably will have some conclusion around that. Another important discussion was on not allowing this last validator to become a proposer. It's a change which will be on the consensus layer side of the chain like the consensus layer team has to make this change in Spec. Looks like there is a general agreement pull request number is 3175 on consensus spec. Mikhail Kalinin will work on it. Maybe clean up and make the expected push to the CL specifications for devnet 5. We should be expecting it sometime this week. Loadstar and Eth JS wants to participate in the dry run and if any other clients want to participate. I think they can reach out to Paritosh. Apart from this there is one other proposal which is highly anticipated, which is with respect to SSZ transaction signature scheme proposal number is
64.93 that's currently under discussion. We hope to see more on that in the next All code Dev execution meeting scheduled for Thursday at 1400 UTC. I found a couple of good blog posts around the latest changes and developments happening on ethereum sites. So yeah please check them out.

# 2. Events, Fellowship, Hackathon

**Pooja Ranjan** [3:30](https://www.youtube.com/watch?v=bhtmxpVfr6M&t=210s):  Next is Events, Fellowship and Hackathon. I have listed Hackathon and events those are happening
around 

- [Next Billion Fellowship Cohort 3](https://blog.ethereum.org/2023/03/16/fellowship-cohort-3-applications)

**Pooja Ranjan** [3:39](https://www.youtube.com/watch?v=bhtmxpVfr6M&t=219s): So Next Billion Fellowship Cohort 3, the submission for application last date is April 28th.

- [ETHBoston](https://www.ethboston.xyz/)

**Pooja Ranjan** [3:49](https://www.youtube.com/watch?v=bhtmxpVfr6M&t=229s): For ETHBoston dates are announced. I think a schedule is also out. I would be talking on ethereum governance and the role of ethereum cat herders in ETHBoston

- [Coindesk's Consensus Protocol Village](https://consensus.coindesk.com/speakers/)

**Pooja Ranjan** [4:04](https://www.youtube.com/watch?v=bhtmxpVfr6M&t=244s):  Similarly for coindesk’s consensus protocol Village. We are representing three different topics. so one is ethereum past present and what to expect in future by Danno Farrin. Then there would be another one with respect to Fellowship protocol Fellowship those are being organised by ethereum foundation and this will be shared by Josh from EPF team and I would be talking about ethereum governance and obviously the role of ethereum cat Herder in the governance process at coindesk

- [Edcon](https://edcon.io/) MONTENEGRO

**Pooja Ranjan** [4:40](https://www.youtube.com/watch?v=bhtmxpVfr6M&t=280s): Edcon is also announced. We are expecting that in the month of May. The dates are May 19th to May 23. If you have information about any other hackathon Fellowship that's happening around please feel free to add them to the Discord Channel and we will like to have it shared with the rest of the community. So that's all on the information so far anyone has any question comment. okay

# 3. New initiative/association

**Pooja Ranjan** [5:21](https://www.youtube.com/watch?v=bhtmxpVfr6M&t=321s): We can probably move ahead I am expecting some more updates from people who have joined us. So starting with the new initiative and Association.

- ERC-4337 Telegram integration

**Pooja Ranjan** [5:32](https://www.youtube.com/watch?v=bhtmxpVfr6M&t=332s): The first one here is ERC-4337 telegram integration. I'm happy to share that this integration has worked out now I mean. We are having a constant feed from the telegram group. The issue was the part that we have created. So we created a web hook and a bot was supposed to sync a message from Telegram and render it at our Discord but WICK bot was all the time, kicking that bot out. So the message was failing like the link was failing and we were not able to do that however that has been fixed. So people interested in learning about the progress of 4337 people who are already implementing them and they are sharing their work can be found on the ERC-4337. I'll add ethereum cat headers Discord so, yeah I mean you can also join the telegram group. If you don't have the invitation or link please reach out to us. Otherwise if you are on the cat or just Discord you are already there.

- ECH Website

**Pooja Ranjan** [6:38](https://www.youtube.com/watch?v=bhtmxpVfr6M&t=398s): Next is ECH website. In the past meeting we discussed having a web page dedicated for Dencun upgrade to share the progress on that. I think I saw some people's requests this morning and I see George on the call. George if you would like to provide more updates on that

**George Hervey** [6:57](https://www.youtube.com/watch?v=bhtmxpVfr6M&t=417s): Yeah sorry meant for the website. Yeah so I created a PR late last night and we just merged today. PR includes a new page for the Dencun upgrade. It is pretty much like 90% complete. It just needs some updates of what's actually happening with Dencun as of right now . It doesn't show the updates but does show the resources as well as a quick explanation of  what the upgrade includes and then there's also another issue that I plan on tackling a bit later that includes  adding web analytics such as Google analytics to the website. So we could actually
track viewership and you know see where we can improve on the website based on like you know data so. Yeah

**Pooja Ranjan** [8:13](https://www.youtube.com/watch?v=bhtmxpVfr6M&t=493s): Thank you George. So we are hoping to add more information about the related Devnets and the timelines of that they should be expecting more on then gone upgrade page very soon on ethereum Cat Herders but so far we have the primary resources available as a George mentioned to get acquainted with what to be expected with the next upgrade.

- Opensource projects

**Pooja Ranjan** [8:40](https://www.youtube.com/watch?v=bhtmxpVfr6M&t=520s): Moving on the next item is open source projects. I think we have not started working on it yet. should we take it after the Analytics

**George Hervey** [8:58](https://www.youtube.com/watch?v=bhtmxpVfr6M&t=520s): Yeah 
**Pooja Ranjan** [8:59](https://www.youtube.com/watch?v=bhtmxpVfr6M&t=520s): Yeah okay, cool. So we should be expecting more on like in upcoming meetings. We'll be sharing about that.

- Splitting the ECH meeting video to create a general community update video and share it with the community

**Pooja Ranjan** [9:07](https://www.youtube.com/watch?v=bhtmxpVfr6M&t=547s): Next is splitting the ECH meeting video to create a general Community update video and share it with the community. I had a chat with Santosh this morning and we have plans. Santosh if you would like to share that with the rest of the group.

**Santosh** [9:25](https://www.youtube.com/watch?v=bhtmxpVfr6M&t=565s): I will  the today's recording. Right what we'll do is we'll commit to trim it down and I have one upload
which talks about the ethereum community updates and we'll upload it to the YouTube along with certain description which will help us with the SEO and see how it works out based on that we can plan it for the upcoming weeks.

**Pooja Ranjan** [9:48](https://www.youtube.com/watch?v=bhtmxpVfr6M&t=588s): Sounds good to me. let's give it a dry run. If it works out if continue doing that so people can get to
know more about it with shorter video clips or probably YouTube shots. Yeah and if there are any other new ideas from the community, please share it with us and we'll be happy to see what can be done to support the protocol upgrade information governance process Improvement. anything that you would liketo share with us please do.

# 4. General updates/discussion

**Pooja Ranjan** [10:25](https://www.youtube.com/watch?v=bhtmxpVfr6M&t=625s): 
next item is Journal updates and discussion.

- [Devconnect - Istanbul](https://blog.ethereum.org/2023/04/20/announcing-devconnect-ist)

**Pooja Ranjan** [10:27](https://www.youtube.com/watch?v=bhtmxpVfr6M&t=627s): Dev connector has been announced. It will be in Istanbul this year. The date is November 13 to 19th. It's a good Meetup for a developer. so people have given good feedback in the past and this would be the second Dev connector event organised by ethereum Foundation.So check out the page and the blog poster added here for more information,  have added some general stats about different social media Twitter Discord. YouTube link LinkedIn and that also contains the link so if you are not subscribed to or if you have not followed us at any of the social media. Please do that we are sharing all sort of information on  social media listed over here

- ECH engineering

  - [EIPw](https://github.com/ethereum/eipw/issues)

**Pooja Ranjan** [11:22](https://www.youtube.com/watch?v=bhtmxpVfr6M&t=682s): Next is EIPw which is a ECH engineering work. I wonder if we have any updates there. Jose if you are speaking you may be muted.

**Jose** [11:43](https://www.youtube.com/watch?v=bhtmxpVfr6M&t=703s): Yeah indeed sorry. Yes we can include two more tests. The tests were passed. I believe that the PR implementation is ready. So I'm just waiting for the sun to come. This was the last weekend I reported to him so he knows that the past and the new tests were passed. So let's
see what else he wants. So, basically all the tests has been performing okay.

**Pooja Ranjan** [12:19](https://www.youtube.com/watch?v=bhtmxpVfr6M&t=739s): It sounds good. Keep us posted if there is any progress. so, I will probably get back in the next meeting.

- ECH Operations

**Pooja Ranjan** [12:29](https://www.youtube.com/watch?v=bhtmxpVfr6M&t=749s): 
next one is ECH operations so  ZK hasn't joined the call but he has been sharing a few ideas in the past. He shared with me the stats of ECH podcast and I'm happy to share that our 
Podcast are very much liked under the technology section and we are getting a good number of hearings from there. We are also trying to add some of our older podcast versions like older recording of PEEPanEIP for which we do not have podcast added so far. People have
requested to have them added in the form of podcasts. So we are planning to do that and he also recorded the all core  Dev meeting that happened last week. I suppose and we are also
discussing similar things like sharing the shots or probably making a smaller version for. I don't know his brother. It was on Tick Tock and Facebook as well. so we can let people
know more about this kind of meeting happening in their community and if anyone interested to come join they can do that and probably they can reach us to support or if they have any query. We will be able to provide them with the right direction. so we should see some more action coming up on the operation site as well.

- [EIPs Insight](https://hackmd.io/@poojaranjan/EthereumImprovementProposalsInsight) & [EIPsInsight website](https://eipsinsight.com/)

**Pooja Ranjan** [13:57](https://www.youtube.com/watch?v=bhtmxpVfr6M&t=749s): Next is EIPs  insight. This month seems to be pretty heavy. we have 11 final proposals so far that's
because we deployed an upgrade and along with that we have some erc's reaching to the final status so we have five erc's and three core eips have been moved to the final status. This month and we have received nine new proposals as draft. Six are moved to review status and eight are listed as the last call. However out of eight four have been moved to the final. This month only so yeah all stats are added in the EIPs insight.com

- [PEEPanEIP](https://www.youtube.com/playlist?list=PL4cwHXAawZxqu0PKKyMzG_3BJV_xZTi1F)

**Pooja Ranjan** [14:56](https://www.youtube.com/watch?v=bhtmxpVfr6M&t=896s): Next is PEEPanEIP. so I think last week we shared about . okay. I'm sorry I'm just quickly trying to take a look here.  so I should remember the number we do have a peep meeting scheduled today at 18 30 UTC for proposal 4804. This is one of those proposals reaching final status from the URL meeting that ethereum Cat Herders has started. So anyone interested to learn
more about it, please join us. The zoom link will be shared on Canada's Discord and last week we shared a proposal 5757 that is for external link policy like how people can add any other link to the proposal document.  What is the process for unapproved link to be made as
approved. so that's an interesting conversation with Sam Wilson. check out if you are an author. 

- [Meeting notes](https://docs.google.com/spreadsheets/d/1axM1KaKc-GCcoPbAnYTOhgLnxXsBVoO5XRjTN3CLnck/edit#gid=0) and action items for ECH

**Pooja Ranjan** [16:08](https://www.youtube.com/watch?v=bhtmxpVfr6M&t=968s): I think that is all there other than that we have received meeting notes for every meeting I saw PR coming in for AC DC 107. This morning, I'll update the link later on. But other than that we do have notes for every meeting. Thank you that everyone who have submitted the notes on time and yeah that's pretty much on the agenda. Anyone has anything to share? Discuss want to bring up today.

**Santosh** [16:49](https://www.youtube.com/watch?v=bhtmxpVfr6M&t=1009s): How are we doing on the backup of the YouTube videos. There was some discussion happening a month back

**Pooja Ranjan** [16:58](https://www.youtube.com/watch?v=bhtmxpVfr6M&t=1018s): Right I do not have update on that. I will check okay , I'm sorry. Okay anyone else if you would like to share anyone new on the call would like to introduce share.

**Kevin** [17:33](https://www.youtube.com/watch?v=bhtmxpVfr6M&t=1009s):  Hi I'm Kevin. I'm brand new. I'm getting into this because my  old roommate was a real believer in ethereum. So I just wanted to see how I could get involved I've been looking online to see how to get involved in like legitimate organisation. So I'm just here to listen to see what everyone's getting into and then see and if there's any way I can contribute. I'm also open to suggestions of how they can contribute  we're just here to learn. Thank you

**Pooja Ranjan** [18:04](https://www.youtube.com/watch?v=bhtmxpVfr6M&t=1009s): Thank you for joining Kevin. I think you have reached out to the right place to learn about ethereum and probably explore how you can be able to contribute in this meeting. We generally try to
summarize what's happening in the ethereum ecosystem and what other cat herders are doing. But you are welcome to follow other channels and participate in other discussions that are happening on different channels. If you have any particular interest like if you find that you would be interested in working in this direction feel free to reach out to us and I think that concludes all our agenda items for today's. Thank you everyone for joining see you in two weeks at 1400 UTC.

-------------------------
## Attendees

* Pooja Ranjan
* William Schwab
* Santosh J
* Daniel Gretzke
* GeorgeHervey
* JA
* Kevin Hein	

## Next Call - May 9, 2023.




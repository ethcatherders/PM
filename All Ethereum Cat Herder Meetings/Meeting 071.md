# Ethereum Cat Herder Meeting # 71  Notes
### Meeting Date/Time: Tuesday  9 November 2021 at 15:00 UTC
### Meeting Duration: 1 hour
### [GitHub Agenda Page](https://github.com/ethereum-cat-herders/PM/issues/247)
### [Audio/Video of the meeting](https://www.youtube.com/watch?v=m2-3GVWu6E0)
### Moderator: Pooja Ranjan
### Notes: Avishek Kumar

----

## DECISIONS & ACTION ITEMS

**DECISION/ACTION ITEM 71.1**: Pooja Ranjan will create an issue in eip-bot GitHub for EIP-2070 for Alita Moore to refer to.

**DECISION/ACTION ITEM 71.2**: Pooja Ranjan will add more people to the EIP interns meeting invite. 

------------

**Pooja Ranjan**: Welcome to Ethereum Cat Herders meeting 71. I am Pooja Ranjan and I  have shared the agenda in chat. So before we get into the agenda, we see some new faces here on the call today. Anyone who would like to take a lead and introduce yourself.

**Mihir**: Hi everyone, so basically I am a researcher at Mycelium. I joined roughly four months ago. I have been looking into the core development side of ethereum. I am currently taking part in the apprenticeship program so yeah nice to meet you.

**Pooja Ranjan**: Nice to have you here. So Mihir mentioned that he is with the Mycelium team. We have some updates coming up from that side related to open ethereum client support that's there on the agenda. I hope to talk more about it in the later part. We have one more new user or contributor. We can say Pradhyuman  but there is some issue with the microphone with him, just to briefly introduce him, he has started looking into NFTs that we were working for the eip authors will get to know more in the later part of the agenda.

# 1. Network upgrade

**Pooja Ranjan**: So, let's begin with the first item listed here that's uh the network upgrade

## [Arrow Glacier](https://github.com/ethereum/execution-specs/blob/master/network-upgrades/mainnet-upgrades/arrow-glacier.md) - ECH [blogpost](https://medium.com/ethereum-cat-herders/ethereum-arrow-glacier-upgrade-e8d20fa4c002)

**Pooja Ranjan**: The first one is arrow glacier, so Arrow Glacier is the third network upgrade plan for the proof-of-work chain of ethereum in 2021 and the block number and the estimated time of arrival was shared in the last all code and meeting and it's expected to be on december 8th. Cat Herders have published a blog post with related information and the history of a difficulty bomb proposals that that we have seen so far the link to the blog post is added to the agenda and this network upgrade is just similar to the new glacier upgrade that was I believe in 2019 that included only one improvement proposal for pushing the difficulty bomb and even in the arrow glacier. We are going to see just one eip that is eip 4345 difficulty bomb delay to June 2022. This will push the difficulty bomb until next summer and we hope to have another big release emerge before that. We can expect an upgrade ready client release. This week followed by an announcement blog post by the ethereum foundation.

## [The Merge](https://ethereumcatherders.com/the_merge/)

**Pooja Ranjan**: So the next sub item listed here is the merge. As I mentioned earlier the merge is expected before the summer 2022. Cat Herders are trying to curate related resources on freedom. Canada's website so please check out our new merch page. I don't see George on the call but thanks George for just adding that page and we are trying to add further information on it. There is this issue created on Cat Herders website github issue number 37 which adds some more resources for all our youtube users if you are listening to this call and if you have some resources to be shared with the rest of the community that's
related to the merge of course, please share it with us. You can create an issue or just add
a pull request to update that resource on catalyst website.

# 2. ECH updates

## [ECH website updating](https://github.com/ethereum-cat-herders/ech-website-v2/issues)

**Pooja Ranjan**: Moving on to the next item is ECH updates. So, we briefly touched on the ECH website updating, I see one open pull request and a few issues. We are reaching out to the website team to look into it and we'll try to close by deploying the latest pull request into it.

## [ECH engineering](https://github.com/ethereum-cat-herders/PM/issues/245)

**Pooja Ranjan**: Next one is ECH engineering. I see Alita on the call. Alita if you have any updates to share on the engineering side.

**Alita Moore**: Yeah I mean nothing super pertinent. I know that there's a plan of bringing someone else on to slowly phase me out so that's kind of that's new that's going to be happening and then as far as the tasks are concerned last month. I primarily focused on fixing up some bugs and other smaller things and so this focus on trying to get some features out that's basically it.

**Pooja Ranjan**: Thank you. Yeah! we have a limited visibility of the eip-bot related tasks so we are trying to add some more tasks to the engineering work like recently we helped out some of the updating to the ethereum foundation Ethereum github and the small task where Cat Herders can help out with. We are trying to add all those in the ech engineering bucket. We will try to have one more person onboard maybe. I mean I am seeing him at
at least two weeks down the line but yes that's a good thing that we will be having more than one resource working on it for some time.

## [Cat blazers](https://medium.com/ethereum-cat-herders/catblazer-chronicles-oct-21-53cf3d8b7f18)

**Pooja Ranjan**: Moving on to the cat blazers I believe William shared the latest post on ECH medium. William I thought I saw you on the police. Are you there? Do you have anything to share with the rest of the team?

**William Schwab**: So yeah the article has I would say some summaries there. I have been doing a lot of onboarding work in ethernet dao and kernel. Also been working on an initiative to try and connect with various platforms to try and get a higher level of participation with ercs with supreme koopa  being getting more involved in the eip process more directly also being involved with people's needs. Since I put that out, someone from lex status reached out to me about maybe working on emergency protocols which is something that I also mentioned in the article and maybe one last thing that I would like to bring up. I did also publish on mirror at the same time and I am interested in at least floating the idea of using mirror for the cat herders in parallel to the efforts on medium. Medium is much more discoverable. I don't think that I would be talking about it going away anytime in the future. But if there's a way that I can try and maybe nudge towards. Also just kind of dog fooding
the various web3 tools that are out there as internally as we can to support the space. Also then I think that would be great. Just to empha a kind of underline “yeah yeah I agree with I agree with you”. I would say just kind of keeping both in parallel. Like right now I am looking for my mirror article and I can't actually find it. It's kind of hard, if I do find it though. I will put it in the chat and that way you can just kind of see what an article over there looks like and that is a discussion that I think we probably should have though not necessarily right now at the second.

**Pooja Ranjan**: Awesome thank you, yeah the only limitation that at the moment I see with the mirror publishing, like having it all together moving from the medium, is a collection of views. I am not sure if we can get the stats properly and so far I have realized that the medium has been more accessible to people. So maybe three to six months down the line if
We have to move over to the mirror completely. We can make that switch otherwise we can continue publishing things in parallel. Maybe if people would like to discuss more or something new comes up and we have some additional information. I am happy to bring it up as an additional agenda item in one of the future calls to discuss properly what people think but if anyone has any opinion right now please feel free to share. I see some comments on the chat. Yeah I think switching to a mirror would be a great idea. Yeah nice and we can continue cross publishing for some time. We will see when we can completely move to one place. 

All right  before we move on to the next sub item. I see George has joined the call just. George just wanted to thank you for the page that you have created for march.There is an issue on the same github repository issue number 37. I found some links broken. You might want to just give a quick link a quick look and fix the broken links over there that would be helpful.

**George Harvey**: Okay yeah sure I will check it out thank you.

## [EIP Insight](https://hackmd.io/@poojaranjan/EthereumImprovementProposalsInsight)

**Pooja Ranjan**: So the next section is the eips insight for the month of November. I see
one proposal is new that has been introduced as draft that is eip 4396 time aware basefee
calculation two proposals moved to stagnant that is eip 2070 and eip 3540. I suppose the issue with 2070 has been addressed. I am not sure Alita if you have any insight on that.

**Alita Moore**: Do you mind repeating that sorry

**Pooja Ranjan**: So the issue with the eip 2070. We saw that pull request was created by the bot but it wasn't moved to stagnant and now that I see that it has already been moved to stagnant, did you do it manually or the path was fixed for it.

**Alita Moore**: Yeah it was most likely the bot so basically like sometimes the  run for the bot will not work because like essentially the token or like the other the authentication that's used for the bot. Excuse me only has so much  bandwidth but then sometimes when it's running it's sort of like an overdose so in this case it ran once. Like two weeks ago and it failed basically before I could reach the merging stage and then this week it ran again and
there was enough like there was a lot. Less stuff going on so it worked, so that's basically why?

**Pooja Ranjan**: I am glad it did not take another six months to check in and come back
Anyway, it's fixed. I am happy about that.

**Alita Moore**: It's not fixed. It's just  something that like I would like to implement a more
thorough fix for but at the current moment. It will be a kind of work eventually if that makes sense. 

**Pooja Ranjan**: All right so if I remember from the last eipip meeting, I was supposed to create a pull request so you can look into that. I am sorry I didn't do it on my end. Do you
still want me to create the pull request so you get an opportunity to look into that later on?

**Alita Moore**: Yeah by pull request you mean like an issue?

**Pooja Ranjan**: Yeah yeah that's correct.

**Alita Moore**:  That would be very helpful, yeah that would because I actually forgot that happened. I  just know the source off hand.

**Pooja Ranjan**: All right I will go ahead and create that issue for you to refer to. All right and there are two proposals which are brought back to life from stagnant to review. Those are 864 and 65. The number is 2364 and 2464. Other than that there were some non-normative changes to a final proposal. The proposal number is eip2124 fork identifier
for chain compatibility checks. There were a couple of edits done to it. so if anyone interested may have a look on that and on other improvements. There are some recent changes to eip1 and addition to eip templates. All of this can be found on the ethereum improvement proposal inside document and the link is available on the agenda.


## [Peep an EIP](https://www.youtube.com/playlist?list=PL4cwHXAawZxqu0PKKyMzG_3BJV_xZTi1F) - Upcoming meetings can be found on [PEEPanEIP schedule](https://github.com/ethereum-cat-herders/PM/projects/2)

**Pooja Ranjan**: Moving on to the next item  is Peep and EIP. So for Peep and EIP the upcoming meetings can be found on the schedule link added to the agenda. Just to summarize, we are going to have a deep dive into the portal network with paper mariam tomorrow november 10 at 18:30 utc. There are a few others that are merge related. Merge test net with proto and paritosh on december 8th and  considering the recent interest in eip editing and we have received a lot of interest from contributors to become an eip reviewer.
We have invited Matt Gannett to talk about the secrets of eip editing on december 14th. So we will keep on getting more ethereum related education resources for you on Peep and keep watching and stay tuned for more information coming on that.

## [Meeting notes](https://docs.google.com/spreadsheets/d/1axM1KaKc-GCcoPbAnYTOhgLnxXsBVoO5XRjTN3CLnck/edit#gid=0) and action items for ECH

**Pooja Rajan**: The next item is meeting notes so I believe we have all the meeting notes
available this time for every meeting. I am not sure if we have anyone to summarize any of these meetings but nevertheless the link to the notes are added here. This time we had this
merge community call.This was the first community call organized by Trent and Tim. It was pretty interesting. It provides a good overview of what the merge is and we took some questions from the infrastructure developer community. It is a good watch though the video recording did not turn out to be awesome because of some zooms issue but we do have a
meeting notes available for that. This recording is available on cathode is youtube in the community playlist. Give it a good one.

# 3. New initiatives - brainstorming

## OpenEthereum client support

**Pooja Ranjan**: Moving on to the next section, new initiative and brainstorming. In the last meeting we discussed client support for open ethereum. I believe we have Mihir and Brayton
joined from the mycelium team they may have some update over to you the team.

**Spore Drvid Bray**: Yeah, Mihir here is still the point of contact. But he's contacted a few people through the discord say like Ronin Kaizen that you linked to pooja and yeah they've provided some tips and things of that sort then following on. Mihir got us into a conversation with xdye and poa and the poa network were essentially saying that they would
continue to provide some support so we are going to work with them on that gnosis have handed over the resources so the github accesses and then also the twitter account. So we should be able to make a community announcement as well which we are just drafting up

**Pooja Ranjan**: Awesome just a small question, do you think the discussion related to this
open ethereum client support is all going on the mycelium discord? Do you want me to share that discord link with the Cat Herders users?

**Spore Drvid Bray**: Yeah actually that would be pretty fair. Yeah if you want  up to you really in terms of the announcement our current plan is yeah so our Glacier gets the support through there. We are gonna try for. I think it's 3436 the proof of authority change that should be a bit of fun and then after that we're gonna try but we're gonna be starting to hire rus devs. So hopefully we can find some way to get that but once we get that going then. Yeah we should be able to support merge. Hopefully I mean it seems like quite the large undertaking but we're definitely keen to support it and with poa we think we could do it.

**Pooja Ranjan**: Sounds good.

**Tim Beiko**: when do you expect to have the arrow glacier support just because we're
planning to put on a blog post tomorrow with all of the other clients and because open ethereum was kind of deprecated. I wasn't planning on including them. Yeah I guess, I am curious to understand what your timeline is for just adding support for aero measure. 

**Spore Drvid Bray**: Oh yeah, I have already done the pr for that.

**Tim Beiko**: Okay and is there a release available. I believe it's okay. So yeah I guess you're saying we should include the release of it's like a supported basically it will be like a supported release that like people can kind of count on and I know it sounds kind of weird to
say that but I guess yeah I am just wondering should we actually make it part of the official
announcement so that people can kind of rely on it or would you rather just be kind of more informal. Yeah what's the best way to?

**Spore Drvid Bray**: If possible it would be good if it could be official but at the same time recently that poa has received access from gnosis. so i'm not sure how much support is involved.

**Tim Beiko**: Okay not not a lot and I see the release is basically the 330 rc14 is the one with arrow glaciers  that's right.

**Mihir**: Yeah that's the one yep.

**Tim Beiko**: Okay so I will add that to the blog post.


## DEGEN bot & POAP on ECH Discord server

**Pooja Ranjan**: Nice and the next item listed here is a pigeon bot and pull up on each discord server. I believe ken is working on that can do you have by any chance any update to share with the group

**Texas**: Yes for the Degen bot and POAP distributions, I will be meeting with the Degen team to go over the distribution of POAP utilizing Degen and that way we can implement it within ECH.

**Pooja Ranjan**: Nice thank you so the idea here is for different meetings and for some important community meetings we are trying to add up and we're trying to manage it with the help of teaching bots. So people who are just trying to you know kind of mine POAP and get it without being in the meeting that can be avoided. We hope to get some more update in
upcoming meetings on how to implement and which meetings would be considered for this distribution. Similar to this there is another chance that we are considering is NFT for eip authors for final eips. I believe  pretty much is working on that, not sure if you have your mic fixed and you have any updates to share. I  believe there is some issue with Peadyuman's mic. So just to provide an update on that he's currently looking for a volunteer to design the nft and working on the codes to make sure we deploy it. We are still considering the chains to be deployed on. There are few work that has to be finalized we have created a small group of people who would be working on co-app and nft and other  kinds of distribution for the community. Participation if anyone is interested to work on that or anyone has any suggestion they know someone who can volunteer for designing the POAP or the nft. Please reach out to us, Ken, William Schwab, Alita Moore and Pradyuman and also me; we are all working together so reach any of us.

# 4. Events & Hackathon

**Pooja Ranjan**: Moving on to the next item is events and hackathons. I am  not sure if we have any other hackathons before the denver. if anyone has information please feel free to share it. ETHDenver is expected from 11th february to 20th february and there is one more which ken is working on it just that date is not decided so we will try to add that in the agenda next time.

# 5. ECH funding
 
**Pooja Ranjan**: On ech funding side we are in talking terms to Moloch. I had a meeting with the rbg group last friday and also on monday (yesterday).  RBG group is the group that helps facilitate Moloch grant proposal and I am happy to share that we have finally submitted the mgp for november as for the grant  timeline. It seems that  the proposal will go on chain on november 29th and  the result with the grace period will be there by december so if we get this grant. We should expect the funds by the end of december 2021 and also on the  Gitcoin side I think the new round of Gitcoin grand will start in december this year. I thought I saw some tweets here.

**William Schwab**:  Yeah yeah it should be early December.

**Pooja Ranjan**: Right so if we need to update our the description or any suggestion is there, please let us know and we can work on that all right so we are getting very close
to the end of the meeting.

# 6. Discuss and close the ECH GitHub Issues/PRs

**Pooja Ranjan**: We just have to cover a couple of more points. The one is the ech pm issue I see. Okay we have one issue about jason rpc spec writer someone reached out to us and my understanding is they are going to have a call today. There was another contributor who reached out to me but I don't see the resource working with the team here on the call today so if we need more people or if the opening is still there. I will update this issue so people can come and share their interest with us. I am keeping it open for the time being till we get further information on it and other than that I think we have covered almost all bounty for documenting notes for the merch community meeting them. The notes have been submitted. So we can close at once the once that is merged on the funding side. We have tried to clear all the fundings last week. Currently I see a couple of new requests. We will try to close all the issues here this week.

# 7. Review of outstanding action items from previous ECH meetings

**Pooja Ranjan**: So that's all mostly from the items. One last item is meeting 70. The decision items or any action item. Let's have a look at it. 
Decision 17.1 our degen bot to the ecs discord server. It's already done and we are trying to make use of that part. Ken is working on that.
17.2 submit the grant proposal for the next round of monitor funding. Oh yes
that's also being done. We submitted the proposal yesterday. So that's all from the agenda item if anyone has any other question or they would want to share something there's the call

**Tim Beiko**: There's a call next week for the eip editors. There were a lot of people that were kind of interested based on the post. Yesterday so I am wondering if we should do anything to just like advertise that call a bit more because we might have a bunch of new potential editors coming on so just making sure that they all  aware of the call and that
they have kind of a link to it. 

**William Schwab**:That would be great, which is about new editors coming up. 

**Tim Beiko**: Yeah so yesterday we posted a thread on twitter asking for you know new eip editors and there's a bunch of them who showed up. So I think there's like five or six people who might be interested and Pooja you said that there's an eip editors intern meeting next week. So I think yeah it would be great to just make sure that like all the people in the discord got to have access or an invite to the call and maybe just make sure that like Micah and our Light client can make it so that  we have an editor who's there who can kind of help answer their questions or something

**Pooja Ranjan**: Right  so this is about the eip apprenticeship meeting. We try to have it bi-weekly and the next meeting is scheduled on november 16th at 11 a.m on my end. So it should be 16:00 utc.Generally Micah does not attend these calls but lightclient is there for sure and lightclient generally tries to walk us through whatever the current  pull request or issues are there. We try to discuss some of those and yeah we'll try to answer questions, I will  share the invite. I mean I already have mentioned in the channel that we have planned this meeting here and I will try to share the zoom link in the same channel. I hope that will happen.

**Tim Beiko**: Yeah and maybe I don't know if you want to maybe ask people for their emails like a calendar invite or something. Okay that might be a good way yeah. Just to make sure that the people who kind of scroll in. We do not like losing them. Yeah because I was surprised we got like over five people interested.

**Pooja Ranjan**: Sure I will mention it in the channel so people can dm me and I will add them to the calendar.

**Tim Beiko**: Cool and yeah somebody also asked Greg from chainsafe asked for a link for this meeting. Is there a calling?  okay no sorry it's not the same thing I think okay so I think he's also asking you about that call so yeah just making sure that maybe we can open like an issue or something on github or just having like an invite where we send people just so people can kind of track it.

**Pooja Ranjan**: Makes sense. Earlier we used to kind of manage it internally because that was for a very small team but now that we are getting more interest in it. Makes sense to create an agenda and then we'll try to invite people. Greg by the way joined the meeting earlier today  but he wasn't sure that this is the meeting he is looking for. I provided the agenda and it worked out and he would be joining the next one he is looking for.

**Tim Beiko**: cool

**Pooja Ranjan**:All right so that's all about it anyone else has any further information or
anything to discuss.

**Texas**: This synthogy they have a hackathon starting november the 8th which is yesterday and it will be in regards to helping web two developers on board to web three. So it doesn't matter what level you are. There is something that you may find to do within this said hackathon and it would be worth checking out.

**Pooja Ranjan**: Nice Ken, can you do us a favor? We have this channel on ecs discord called hackathon if you can provide this link and information over there we might get some people enrolling for that.

**Texas**: Okay we'll do thank you

**Pooja Ranjan**: Awesome so that's all about the cathode rays update and meeting for today. Thank you everyone for joining see you all in two weeks on november 23rd at
1500 utc.

-------------------------
## Attendees

* Pooja Ranjan
* Brent Allsop
* William Schwab
* Antonio Sabado
* Shane Lightowler
* William Xaun
* Trenton Van Epps
* Alita Moore
* Texas
* Spore Drvid Bray
* Mihir

## Next Call - November  23, 2021 .





# Ethereum Cat Herder Meeting # 77  Notes
### Meeting Date/Time: Tuesday  1 February 2022 at 15:00 UTC
### Meeting Duration: 0.5 hour
### [GitHub Agenda Page](https://github.com/ethereum-cat-herders/PM/issues/265)
### [Audio/Video of the meeting](https://www.youtube.com/watch?v=SdR5kAb1He8)
### Moderator: Pooja Ranjan
### Notes: Avishek Kumar

----

## DECISIONS & ACTION ITEMS

**DECISION/ACTION ITEM 77.1**: Pooja Ranjan will talk to other multisig signer this week and see if we have another option to transfer CLR  multisig Funds to wallet.

------------
# 1. Network upgrade

**Pooja Ranjan**: Welcome to Ethereum Cat Herder meeting77. The first item listed here is a network upgrade.

## The Merge 

[Kiln Spec v1](https://hackmd.io/@n0ble/kiln-spec)

**Pooja Ranjan**: As we try to provide updates of what's coming up on the ethereum blockchain. The next upgrade that we are expecting is the merge and with merge, we have seen the kintsugi test net which was made public in the month of december and now we are
having a new spec coming out for Kiln that was released yesterday and in the ef blog post finalised number 33 shared by Danny Ryan. It suggests that Kiln could be the last sprint before launching the pre-production test nets. Currently engineers are trying to adjust the changes that were identified in engine api and at the end of this sprint a production ready implementation will be shared with the community, so in short kiln will be the successor to the kinsuke test net.

Optimistic Sync [#2770](https://github.com/ethereum/consensus-specs/pull/2770), [#2820](https://github.com/ethereum/consensus-specs/pull/2820)

**Pooja Ranjan**: The next sub item here is optimistic sync. So optimistic syncs provide a way for the consensus engine that is the beacon node to follow the head of the chain without verifying the execution payload. This is required for the execution engine to be able to sync most effectively given the visibility of payload hashes from the block in the last meeting. Developers  in the last  consensus layer meeting were discussing how to implement this in the spec and fall on a shared document for client team feedback to decide on the optimistic sync design, so please check out the meeting notes if you are interested to follow and contribute on that part.

# 2. ECH updates
 
**Pooja Ranjan**: Moving on to the item number two that is ech update.

## [Ethereum Cat Herders Update #52](https://medium.com/ethereum-cat-herders/ethereum-cat-herders-update-52-363e8f28a4ee)

**Pooja Ranjan**: So we shared the ethereum cat headers update 52 which is for the summary of the month of January, this morning. Check out for the latest update and you
can find the link in the agenda.

## [ECH engineering](https://github.com/ethereum-cat-herders/PM/issues/261)
 
**Pooja Ranjan**: The next item is ech engineering. For ech engineering the ethereum cat herder team is trying to help the current eip bot. Alita has left some comments for whatever updates were done in the past month of January and there are suggestions for the task priority. She mentions, that I have completed about six tickets in the past month and the key updates are improvement to auto merge reliability or potential path to viable solution in the future custom maintenance you can change who's mentioned when an error occurs by changing the maintainer list in the yml file fixing bugs and PR auto labelling. 

Unfortunately she could not join the meeting, so she left an update and I am hoping these would be also reflected in the monthly task that is added to the ethereum cat herders engineering issue. I personally have no objection to the priorities that she decides but yes anyone else here thinks that anything goes in a particular sequence. Anyone has any thought or opinion on the sequence decided here.I don't see even Shashank who is also the second one who is working on the EIP part stuff but yeah maybe I would take it up with the
engineering group uh in the ech discord.

## Cat blazers - [ECH Podcast](https://open.spotify.com/show/7dgxKMkSyy3HWtQW7OfqXA)

**Pooja Ranjan**: Moving on to the next item is cat blazers. We have William Schwab on the call today. William if you would like to take it up.

**William Schwab**: Sure, so the big thing that I would say really was more or less all of my time for the month. This month was getting the podcast off the ground. I am happy to say that there is now an ethereum characters podcast. We have been primarily using spotify as a platform.

ZK Doof has started helping me out with that kind of thing in the beginning. It was mainly me with some assistance from Pooja which is definitely still assisting. It could be that some of that might move over to zk doof. He's also trying to help me with a lot of the technicalities behind it. Originally we were going to target once every two weeks but for now it looks like even targeting. Once a week release has been working and has been sustainable. So my current plan is to try and keep that up. If I see that it becomes too much of a burden then 
I will probably try and take it down. Once every two weeks is kind of a thing. We have released three episodes so far. The first one with Andre Cronje, the second with Tomasz Stanzack from Nethermind and the third with Samczsun. We have another episode recorded with the Lefteris. Let's see if I can remember his last name correctly, Karapetsas. I hope I got his last name right there from Rotki and should be recording another one with Alchemy today. Yeah so far so good, one thing that would be useful there is if I would be able to get a cat herders domain email just to use for email purposes there. 

We have been looking into that on the side,so just kind of like getting in the groove with that and handling comms. I would say I handled a lot of my capacity pretty well the whole thing this month. Starting next month the kernel is kicking off. So I do expect to be sinking a fair
amount of time into that. I have also been thinking about kind of renewing my efforts with ethernet. Though I would have to be in a position where I feel like I would be able to give it the attention that it kind of deserves, so that one probably will get back burnered in the meantime I am also still working on the kind of erc promotion project that I was working on before to try and get other platforms in the space and more involved in the erc process creating ercs for things that they have created that would be of good use to the ecosystem
at large and have also started another project with them starting to work on creating protocols and platforms in the space both to make sure that they have good security measures in place and about what  to do if there is actually a security event and yeah that's been my month happy January

**Pooja Ranjan**: Pretty awesome, two points that you mentioned in the update about the ech domain email. I talked to Brent Alsop and he mentioned that he would be looking into it. Unfortunately he had some emergency at home so he could not join the meeting today but we hope to have some update for you very soon and one other thing that we we shared on
the twitters. Ethereum catalyst twitter earlier said that we are looking for someone to volunteer their time to kind of make thumbnails for the podcast and all so someone reached out to me.

Unfortunately we are not able to sync for the past two or three months. His time zone is entirely different but I hope to have some conversation this week and will  inform you if he is willing to get onboard.

**william schwab**: What would that be like? What would they be doing?

**Pooja Ranjan**: The thumbnail 

**william schwab**: Oh! got it, okay fine. I didn't hear the first time that would be awesome.

**Pooja Ranjan**: So those are on the podcast and I think we have pretty much covered everything on the cat blazers.

## ECH Operations - [ECH New Joiners Meeting (January 2022)](https://youtu.be/veG3lXSwdkI)

**Pooja Ranjan**: Moving on to the ech operations in the last month. We had our first new
joiners meeting, we have Shubhangi on the call. She has been added recently to the usage ops team. So Shubhanga if you would like to take up this one and talk more about what's coming up.

**Shubhangi**: So we had 17 people who filled out the google doc form and we also had some new interests from the introductions that joined the new joiners meeting. There was some issue regarding actually joining the zoom time zone at the right time, so I will look into that but  the meeting went well. It was pretty short. It's the first meeting so, I am guessing that we may have more people next time and aim for a one-hour meeting, so we have tentatively decided for february 17, 11 a.m est to be the new joiners meeting for february. So we have more time to prepare and email people and get more,get kind of increase the public
awareness of having this meeting and I am hoping that more members can join. I will be sending out calendly invites this time,so people can click on the link easily and find the zoom meeting and yes so I think I will be doing this monthly and hopefully we'll have more people
on boarding through this process.

**Pooja Ranjan**: Cool, Yeah and we will add the event on the ech discord whenever the date is finalised and tentatively we are planning to have it on february 17th but  we will look into some of the logistics and if it is done then we will add it there. So please keep checking the ech discord event section for upcoming meetings

## [EIP Insight](https://hackmd.io/@poojaranjan/EthereumImprovementProposalsInsight)

**Pooja Ranajan**: The next sub item is eip insight in the month of january. EIP 1271 standard signature validation method for contracts is now added as a standard. It is now in
the final status. It's been a long pending proposal so, I am very happy for the projects who have been promoting this proposal to be in the final status for a very long time. And in addition to that there are four new proposals added as draft and more changes all these are listed in the eip inside you can follow the link on the agenda.

## [PEEPanEIP](https://www.youtube.com/playlist?list=PL4cwHXAawZxqu0PKKyMzG_3BJV_xZTi1F) - Upcoming meetings can be found on [PEEPanEIP schedule](https://github.com/ethereum-cat-herders/PM/projects/2)

**Pooja Ranjan**: The next one is PEEPanEIP upcoming meetings can be found on the
people schedule that is added to the agenda this week. We are planning to have a meeting with Wyan Chang for the proposal. EIP4361 that is signed in with ethereum. It's a very interesting proposal and we are hoping to have some project implementation soon so if you are either implementing this project or trying to work on this proposal please try to attend the meeting that is scheduled for tomorrow february 2nd at 18:30 UTC and in the following week. We have got an eip 2098 compact signature representation with Richard. It is an informational eip which is reaching to the final status. We have very few eips which are informational categories and in the final status and this one particularly is interesting for projects to follow. So if you are interested stay tuned.
## [Meeting notes](https://docs.google.com/spreadsheets/d/1axM1KaKc-GCcoPbAnYTOhgLnxXsBVoO5XRjTN3CLnck/edit#gid=0) and action items for ECH
 
**Pooja Ranjan**: Moving on to the meeting notes and action items for ech. We have meeting notes for all core dev meeting 130 that are available in the repository now. Also for eip ip meeting 48. Unfortunately we do not have consensus meeting 80 yet. I will check  with the resources working on it and other than that we had this another meeting eip editor apprenticeship meeting for the last month and we have recording and summary added in the agenda, so that's all from the ech updates.

# 3. Events & hackathon
 
**Pooja Ranjan**:  So moving on to the events and hackathons. We have talked about events and hackathon points that are planned this month. There is this new edition of ethereum. It's another new event. I am just trying to open the link there for you. Yeah I was just forgetting the name of the team so it's by Devfolio India and they are inviting application
for hackathons and the applications are closing on february 17th that's the new addition to this list and other than that we discussed about deaf connect in our earlier meetings. We have Anet on the call, she has probably more updates on that part. Over to you Annet.

**Anet**: Sure hey guys, so regarding Amsterdam and dev connect , there will be events happening from the 18th of April until 27th of April. It will be in Amsterdam and there will be
many events happening during the whole week. For example team is organising some events as well and many others for example like layer two events magicians are going to host their event as well and magicians would like to collaborate with yeah exam controllers
on this event. I am happy to share more details but I am sure that I shared already some but we are going to host today council where we are going to invite many people and many developers and researchers from all kind of different teams and work on ips and discuss
all the issues that are happening in  ethereum but we are going to take in a place.

The other events and respect them as well because they are going to be happening at some layer one researcher event as well. Yeah basically one week many events under in like one huge venue hosted by ethereum foundation and every event will be self-organised and
that will be sort of like a decentralised version of the event sort of. Does it make sense?

**Pooja Ranjan**: Thank you for the update, one thing that we wanted to especially mention here. I am trying to coordinate and help out in every possible way to support this event but I am not travelling. So if anyone here from the ethereum  cat herders is planning to be in real life in their Amsterdam meeting and is interested in representing ethereum cat herders please reach out to me. We may have some tasks for you, if you are interested to help out  in the event planning so please reach out to me

# 4. New tasks / brainstorming

**Pooja Ranjan**: All right,  the next one is a new task and brainstorming. We have been discussing these new activities and I have especially been thinking of these categories as a point of discussion for inviting a new initiative.

##ECH Medium to Mirror
 
**Pooja Ranjan**: We are trying to move the blog from ech medium to mirror. It is going to be
a long process I mean by long here I mean that we are going to have both in parallel for  some time. I know William Schwab has been working to get mirror account setup for ethereum cat herders. William if you may have any update on that.

**William Schwab**: Yeah I have been working with Trenton Van Epps who's also involved with mirror. He told me today, he was going to move the request forward so we should have the ability to create a subdomain on mirror. We have an account separate from the standard characters multisig for this that we'll just kind of informally share just to prevent the need for an entire multi-stick transaction anytime like we want to sign and publish a new article. If you want more details on that you can reach out either to Pooja or myself. I don't know exactly when everything is going to move forward but I am expecting it to be like I am expecting there to be definite progress on that before the next call.

**Pooja Ranjan**: Thank you for this month. We have already shared this newsletter via a medium and if it is done in a day or two like the account is set up. We will try to share it via
mirror as well otherwise from the next blog or the newsletter. We will try to make use of that account.

## [Learn2Earn](https://github.com/ethereum-cat-herders/L2E)

**Pooja Ranjan**: Moving on for learn to earn, so this is a new initiative that we are trying to
make an in-house project with the help of contributors of ech engineering. We had a meeting yesterday and currently this is in the planning phase to share general updates of the meeting
and may be able to help interested contributors make contributions in future. We have created a github repository for this project. Link is added to the agenda. We are making some progress and from the last meeting that happened yesterday. Currently we are planning a dry run. Shashank Yalamanchi would be running a dry run and we will explore the other part of it. We are trying to integrate it with rewards. So charge will be looking into how to integrate with the response of the answers that we are receiving from google form as of now. The details are added in the meeting notes and you can check out the github link added over here. I don't see anyone from that team. So I think that's it on the update side but if you have any questions or if you are interested to contribute to this project please reach out to us on ech discord.

## [EL Merge Client Release Naming](https://ethereum-magicians.org/t/el-merge-client-release-naming/7928/14)

**Pooja Ranjan**: The next sub item is el merge client release naming. So Tim Beiko initiated this thread at the fellowship of ethereum magicians to help. Select a name for
merge upgrade for execution layer client specs. Looking into the thread it appears to me. Serenity has received the most love and signal from the community members who actually responded to the threat. So check out the link in the agenda and vote for your favourite name if you have got any. I don't know.  Tim, you are in the meeting today if you would like to add something up.

**Tim Beiko**: Yeah not really. I think yeah the threat is good.We probably need a call eventually to  discuss the different options. It's not the most urgent thing. We do have  a community call next week so I wouldn't make it then and then there's all core devs,  so maybe  late February early March seems like a good time to have that.

**Pooja Ranjan**: Yeah sure, we organised this one for a um consensus layer client will
try to organise something in a similar fashion in two to three weeks from now.

**Tim Beiko**: Yeah that seems good, yeah.

**Pooja Ranjan**:All right, that's for item number four.

# 5. ECH funding

**Pooja Ranjan**: Moving on to item five ech funding. In the last meeting I did mention that we have received some CLR multisig funds from bitcoin around 12 but unfortunately I am having some issues to have those funds moved to our ethereum cat headers multisig. We are going on communication with the bitcoin team. Looks like there is some issue with my wallet. I don't know but I will keep the team posted on updates for now. The funds haven't been transferred and I know that with the new bitcoin policy of bitcoin. We had to do it before april otherwise it will be moved back to the multisig fund. I don't know maybe I will talk to other multisig signer this week and see if we have other option if there is an issue with my
wallet only, maybe some of the other Multisig  may be able to help me out with that.

# 6. Discuss and close the ECH GitHub Issues/PRs

[ethereum-cat-herders/PM](https://github.com/ethereum-cat-herders/PM/issues)

**Pooja Ranjan**: Moving on to the next item, discuss and close ech github issue and pull requests. The issue for json rpc api is still open but I think it's time to close. We haven't received any response from the case and rpc api team and it looks like that the project is not actively being pursued so we can probably close that issue. 

[ethereum-cat-herders/funding](https://github.com/ethereum-cat-herders/funding/issues)

**Pooja Ranjan**: And on the funding side I have seen a few new requests. I was hoping to put them on a chain before this meeting but unfortunately I could not but that will be done today before the end of the day. At least on chain and then we will try to follow up with the rest of the multi-sex finance to get them approved.
 
# 7. Review of outstanding action items from previous ECH meetings

**Pooja Ranjan**:  Coming to the last item of the  agenda meeting notes.I am trying to look into the decision items on action items from the last meeting.The first one was anyone interested in helping with the ech podcast should contact William Schwab. We did discuss
about it. William is now having help for the technical side and someone reached out to me to help with the thumbnail and all. So yeah that is there contact shubhangi Govclay, if interested in participating in the meeting on january 27th. So the new community members for january 27th are over now but we are planning another one probably on february 17th, so if you are still interested you may reach out to us on the ethereum cat herders. Shubhangi is trying to manage that meeting so yeah you can reach out to her. On 76.3 William Schwab to follow up with Trent on ech medium mirror. We did receive the update. 76.4 suggested a vote for a name for el merge client release naming, this is still open and we are planning to have a community call maybe the second or third week of february. So stay tuned for more information coming out on this item. 76.4 Pooja to get in touch with the generator see about
closing of json rpc issue. I think Jared has officially  moved out of the project, so we might want to close it for now. That's all from the item listed. I am wondering if anyone has anything new to bring up and share.

**William Schwab**: I actually do have a bit of a personality, if everything else is done.

**Pooja Ranjan**: Yeah please go ahead.

**William Schwab**: yeah I  have given notice by my day job so to speak, I am a smart contract dev and work for what a dev studio called linum labs. So I will be sticking around with them in february but should be moving on in March. Currently don't necessarily have
something set up for March so I would put that out there in case anybody's looking for a smart contract of who fights decentralisation coordination costs by night.

**Pooja Ranjan**: Yeah thank you for sharing. Yeah we well we hope to see you around
here definitely in the ethereum cat herder.

**William Schwab**:  Oh I am planning on leaving, don't worry like I'm sticking around over here.This is just day job stuff.

**Pooja Ranjan**: All right, okay I see a new name on the screen so if you would like to go
ahead and introduce yourself and maybe talk about  what brings you here.

**Victor**: Sure thanks uh hi everyone my name is victor.I am a recent uh i guess joiner here
you know I've just been looking for a way to get  involved in crypto blockchain technology and ethereum. Specifically my background is in the traditional finance world. You know I spent about 12 or 13 years helping to build electronic trading systems for equities and options, So I have you know pretty extensive finance background and you know spent my entire career working with developers in a pretty pretty technical  hands-on roles even
though I myself am not  sort of you know  my background is not in engineering or computer science or anything like that but you know  that is something that I very much enjoy and it sounds like most of the items here may be spoken for but you know I would definitely throw my name out there if anybody else is looking for any help. Big or small and you know I would actually request that maybe if you guys can send something my way as a way for me to get more involved and start to kind of get more hands-on with things as that's kind of my preferred way of learning things. So yeah let me know if you guys have any questions or if you know if you're looking for help with anything.

**Pooja Ranjan**: Of course I hope you are available on ech Discord.

**Victor**: I am there.I must admit that I am pretty new to discord. My company did not use  anything. This is sophisticated for messaging so I'm still kind of getting my way through it. But yeah I am there and I am trying to follow you know some of the chats.

**William Schwab**: What would you know specifically what you'd be looking for?

**Victor**: I mean my background is sort of product project management. That's you know kind of getting things organised and you know documentation education. I think I need to help with some email or you know getting you know about website setup or things like that you know I am happy to try to help with that as well.

**william Schwab**: Cool, I will definitely keep that in mind.

**Pooja Ranjan**: Yeah sure I mean on the website side. Probably I can also think of something and maybe reach out to you.

**Victor**: Yeah absolutely,  just let me know. You  know again i'm on that you
know like a web developer technical but like if it's something like setting up an account and
You know, kind of a new platform and things like that. I'm pretty capable.

**Pooja Ranjan**: Sure, thank you so much for joining the call and sharing about you. So people can reach out to you if they have any requirements. Yeah anything else from anyone before we close out for today. Well it sounds like we have covered pretty much everything that was listed on the agenda today and I hope to see you all in two weeks. We can still keep communicating if something comes up, share it on the ech discord we will try to respond to the questions. Those are there and if someone is trying to find a way into the ecosystem ethereum cat herders are there. Thank you everyone for joining us today. Have a good one everyone.


-------------------------
## Attendees

* Pooja Ranjan
* William Schwab
* Shubhangi
* Victor
* Anett
* Tim Beiko

## Next Call - Feb 15, 2022.






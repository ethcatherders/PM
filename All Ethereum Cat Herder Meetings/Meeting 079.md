# Ethereum Cat Herders Meeting 79 Notes <!-- omit in toc -->

### Meeting Date/Time: Tuesday, March 01, 2022 15:00 UTC <!-- omit in toc -->
### Meeting Duration:  36:01 min. <!-- omit in toc -->
### [GitHub Agenda](https://github.com/ethereum-cat-herders/PM/issues/270) <!-- omit in toc -->
### [Video of the meeting](https://www.youtube.com/watch?v=fm3j_h47_ow) <!-- omit in toc -->
### Moderator: Pooja Ranjan <!-- omit in toc -->
### Notes: Metago <!-- omit in toc -->

---

# **Summary:** <!-- omit in toc -->

## Actions, Decisions and Community Participation <!-- omit in toc -->

Action Item | Description
-|-
**79.1** | Pooja will share any KTH related new research at the next meeting
**79.2** | Devconnect related updates will be provided at upcoming ECH meetings
**79.3** | Reach out if interested in working with ECH Cat Weekly Comic team (ECH Discord)
**79.4** | Reach out if interested in ECH website hosting (ECH Discord / Github)
**79.5** | Pooja will confirm EL Merge client release naming meeting
**79.6** | Reach out if interested in working on design for ECH's Learn2Earn platform (ECH Discord / Github)
**79.7** | Pooja to request client meetings be added to Permacast
**79.8** | Pooja to process funding requests
**79.9** | William to publish ECH January newsletter on Mirror

--

# Contents <!-- omit in toc -->

- [1. Network upgrade](#1-network-upgrade)
- [2. Events & hackathon](#2-events--hackathon)
- [3. ECH updates](#3-ech-updates)
- -[1.New initiatives & open tasks](#1-new-initiatives--open-tasks)
- -[2. ECH website hosting](#2-ech-website-hosting)
- -[3. Client meetings in podcast form](#3-client-meetings-in-podcast-form)
- -[4. EL merge client naming](#4-el-merge-client-naming)
- -[5. ECH engineering](#5-ech-engineering)
- -[6. Cat blazers](#6-cat-blazers)
- -[7. ECH operations](#7-ech-operations)
- -[8.EIP Insight](#8-eip-insight)
- -[9.PEEPanEIP](#9-peep-an-eip)
- -[10. Meeting documentation and ECH GitHub Issues/PRs](#10-meeting-documentation-and-ech-github-issues/prs)
- -[11.Review of outstanding action items from previous ECH meetings](#11-review-of-outstanding-action-items-from-previous-ech-meetings)
- - [Appendix](#appendix)
  - [Attendees](#attendees)
  - [Next Meeting Date](#next-meeting-date)

---


# 1. Ethereum network upgrades

Merge devnet 4 is ready. Almost all client teams are participating in devnet 4. The participation is 99.7% percent, which is quite good, but sync committee participation is somewhere around 80%, which is less than expected, so client teams are investigating the reason. Chances are there might be some client bug issue but they are investigating that.
Client teams seem to be on board for a kiln test net launch today or tomorrow as per kiln v 1 spec that was released sometimes ago and this is same as what was available for devnet 4. 

Paritosh will be reaching out to the client teams today and if something is pending then the release will be tomorrow, otherwise it can be later today. Paritosh and Maurice will be on PEEPanEIP tomorrow march 2nd at 18:30 UTC to share the details of how to participate in the kiln test net. The recording will be made available early next week so if you can't join you can always follow the recording.

From the past meeting I mentioned about the KTH royal institute of technology and I am supposed to provide updates on that. About 10  days ago we had a meeting with the KTH team. Ethereum developers, Ethereum engineers, client teams participants, and some people from the testing team were present. The KTH research team shared different presentations, different research work that they have done in relation to Ethereum and it was very much appreciated by the Ethereum team. The Ethereum foundation will be exploring different ways to take this research, which should be helpful with the merge upgrade.

One of their research is about chaos engineering of Ethereum clients. I have added the link in the [agenda](https://github.com/ethereum-cat-herders/PM/issues/270) and published the research work on [ether world](https://etherworld.co/2022/02/21/chaos-engineering-of-ethereum-clients/). This research was basically on GETH and Open Ethereum. GETH developers have requested to do it with GETH versus Aragon because Open Ethereum is no longer supporting specs for Open Ethereum clients. In addition to this chaos engineering, there is another work on client diversity. We have shared the presentation with the relevant team and I’ll be updating if I have something new to share on this topic.

Kurtosis testing the last meeting a team who developed this tool kurtosis that provides a docker support to create much testing environment shared a brief update. Later on. Tim Bieko organized a meeting with the team which was facilitated by Danny Ryan. Cat Herders supported the meeting with recording and other stuff. Last week, we had this meeting in which there was a demonstration by the team regarding how client teams can make use of this kurtosis tool for various testing purposes, creating various testing environments and kind of record their readings. This is a very good watch for people who would like to participate in merge testing and do not want to run both each one any two clients on their own. The recording is available on ECH YouTube and we have added useful links of GitHub which can help you to set up this environment at home. If interested, please take a look. 

Shanghai is probably the next upgrade which we can expect after the merge. Client teams are still discussing the proposal to be included in shanghai and it is being discussed in all core dev meeting. You may find a broader list on Ethereum pm GitHub, however people may also refer to issue 450 created by Tim Beiko, which can give a list of shanghai proposals.

# 2. Events & Hackathons

1. Devfolio, a community of builders from India is working in association with the Ethereum foundation to organize multiple events including following two:
a)	ETHernal: It is an online hackathon (February 25 – March 28, 2022). We are hoping to have Buterin as a guest speaker. 
b)	ETHWMN Fellowship: An ETH women fellowship (February 7 – April 3, 2022). The idea here is to add diversity to the ecosystem so we are providing a fellowship to women there. I’m hoping to support this ETH women fellowship.

2. On the occasion of international women’s day, ECH has planned an event, Future of Inclusion 3.0 in association with Blockchain New York. On behalf of cat headers, I would like to thank Jamiel Sheikh from Blockchain New York for his help with the event and promotion. Jamiel is here with us today.

Jamiel: Hi Pooja, not much to say but the event is on march 8th noon eastern and the topic is how inclusion and the Blockchain web space will look like and how it should look like. So very excited to  to be a part of that, of the talk. 
Pooja: Thank you so much  for providing support, and I would also like to mention from Ethereum Cat Herders, Shubhangi Gokhale and Kenneth Lester have been involved in organizing the event so we look forward to have this panel discussion on march 8 at noon est. 

3. Enterprise Ethereum alliance has planned a March 16 educational webinar. We participated last year and will participate this year too. Tim Beiko and I will be talking on Ethereum upgrades. It will be on upgrade to a proof of stake and the EIPs under discussion. So make sure to tune in to EA webinar on march 16.

4. Ethereum Rio  is planned march 11 till march 16. 

5. Devconnect is an event in amsterdam being planned by Fellowship of Ethereum Magicians and cat herders are helping out in organizing an event of day two that is being planned by FEM. i am in touch with Anett Rolicova and so far we have three confirmed participants. We are still discussing the format of the event. It may be that a room is provided and we will have a workshop or presentation. i do not see Anett on the call today but on a high level we are hoping to have a room for about 50 participants in each room. This is going to be a huge event with over 2000 people expected to participate and we hope to keep providing update with Ethereum catherders meeting upcoming meetings.

# 3. ECH Updates

## 1. New initiatives & open tasks

Cat weekly comic: John and Mark joined the ECH group recently and with some interest in designing came up with an idea of sharing information in form of comics. Because we are cat herders, we thought of having it in cat comic form. We are planning to start a series with this month to publish one comic per week with some cartoons and related links to follow to learn more on a topic. 

William Schwab: Since we're in crypto, can it be a manga? 

Pooja: I think we can take opinion of the cartoonist here. John, welcome. I don't know if you have a microphone with you to share more. 

William: might be an audio issue 

Pooja: Yeah maybe. We have started up a discord channel to look into the work there and he has already shared a couple of cartoons, which we are working on to make sure that all the information are right. I’m wondering if anyone from the group is interested to be you know looking into this before it goes out for publishing. Let me know so we can add you to the channel and yes I would appreciate any kind of suggestion on the topic and any feedback on how we can make it more information rich and more reachable to people would be highly appreciated here. 

William: yeah add me and if you don’t mind.

Pooja: I’ll be happy to add you. I know we can always make use of a fresh brain fresh inside for any topic that we are working on so thank you so much.

## 2. ECH website hosting

I’m extremely sorry to say that the ECH website is still not working and um it is still down and I’m looking for people who can support us with making our website go up as soon as possible we have all the course available on Github it's just that the hosting was provided by a different party but I would love to see everything done with the help of community so if you have capabilities if you have bandwidth to support us run a Github page and get the ECH website live. Please reach out to us on ECH discord.

I’m not sure if anyone from the group may have the bandwidth or ability to fix it up or maybe interested to take a lead on this?

William and Pooja talk about potential solutions, including asking volunteers with full stack experience to reach out and help the ECH community on this matter.

## 3. Client meetings in podcast form

Pooja apologized for the delay and said that she will try to get the cl meeting added to the podcast or at least request the team to add it. 

## 4. EL merge client naming

Tim Beiko has started a fellowship of Ethereum magician thread that has collected all potential names, but the one thing that is a kind of a stoppage so far is decision on what name should be added for the spec for the client and we were hoping to plan a community meeting to just finalize the name. I have a meeting late this week. We'll try to check with Tim Beiko and if we get finalized on a date then we will try to organize this meeting maybe by March third week definitely.

## 5. ECH engineering

There are two items to discuss: the EIP bot and Learn2Earn. 

Shashank: Thank you very much. I currently picked two issues regarding the EIP validator bot (EIP V Bot) and yesterday I had a discussion with Alita regarding a couple of things like the kodiak that we are using to auto merge and any issues around that so just trying to get an understanding. Also there was just a brief discussion on whether we should merge the EIPV bot repo with the  EIP bot  repo because both are different code bases. One is on typescript and other is on rust. The core objective is to have both the bots in the same report to reduce the footprint on tracking all the issues that come up for ECH engineering. That was kind of the main reason. 

Learn2Earn: We have completed the dry run and we got a good understanding how the user flow looks like so how a user would come and try to fill in the quiz and generate the answers. We have moved on to the main application that we are trying to build. I and George will be building and we are looking forward to any designer that might be interested in helping us with design for the learn to earn platform because I primarily am a backend guy and george is more of  front-end guy but doesn't have a good skill set in the design end um so we both are kind of looking forward to having a design person who can draw specific designs required for the different modules that are there in our platform at a high level.

Pooja: well thank you for the update. A couple of people have joined recently I would like to check if they would be interested in the designing part of this project. For people who are interested to be a part of this project or contribute, we are trying to add every information including the meeting notes that we have every week on Monday where all the team members seem contributors sync up and share the information on their part so and also we have listed all the issues you can find that in Github. If you are interested in working on any particular issue you can simply respond to that and we'll be happy to have you on board and provide you necessary support to continue working on the project. Thank you for that. 

## 6. Cat blazers

William: zkDoof, who's come on to help me with a lot of the work involved with the podcast has had a really good few suggestions there and I’m gonna try and put the structure in place to try and make sure that I’ve always got kind of stop gap measures to put out a quicker episode if something falls through or something of that kind. That being said it definitely has still been taking up in the amount of my time. Kernel Block has launched so I’ve been spending some time over there also as part of just general onboarding stuff. 

Also, I’ve been working with Supreet Gupta for a while now on an emergency protocols kind of project trying to get good documentation around about what app layer projects need regarding security also what to do if there is an unfortunate incident. He's been handling the vast majority of the writing. We have a rough draft and are inviting in some security researchers and other people who are very active in that end of the field to give it a look and make sure we're in the right direction at their own suggestions. I’m happy to see that we're at a point already that we can show that to other people which is cool. I think that's it as usual I’m probably missing a thing or two but that would probably be the vast majority of what I’ve been involved with for the last couple of weeks. Pooja congratulated William Schwab on being proposed to be a formal EIP editor. Pooja and William then discussed adding ECH’s January issue that has been published on Medium to Mirror as well and decided to discuss the logistics offline. 

## 7. ECH operations

ECH new joiners meeting is planned on march 17th at 11  a.m EST. This is available on the Ethereum cat herders discord event section so people who have recently filled  the onboarding form or have joined the ECH discord, please check out the event section and we hope to talk to you in the new joiners meeting and welcome all kinds of ideas and suggestions regarding how you can contribute, how we can help you contribute and if there isn't any question in general that you would like to learn about Ethereum ecosystem to be able to start contributing. So it is going to be an open office kind of thing. Not only the new joiners, but anyone who has questions and they have been looking for some answers please reach us in that meeting. 

The women's day celebration event, Future of Inclusion 3.0 is planned on March 8th at noon EST. we will be publishing the blog post later today it is almost ready we were just looking into some cover image part I think that was the wait and it should be done now so we hope to publish the blog post soon.

## 8. EIP Insight

In February, the EIP repository received four new proposals as draft. Three proposals moved to final and four EIPs are available in review status. The complete list of change of EIP status change is available on EIP’s insight for the month of February. We released it yesterday. There is one EIP of note. EIP 2098 completed its last call but has changed from informational to standard track ERC. So we can expect this proposal to get to final status very soon. Please check the proposal and share if you have any thoughts and comments on that. We have initiated onboarding of new eip editors and the process is very simple. In the last meeting, the EIP editor suggested two names, William schwab and Sam Wilson, so we have already received a pull request from Sam Wilson and I think it was merged this morning. I’m not sure of that but if not I’m hoping it to be done very soon and William Schwab, if you do a pull request we can get consensus from the EIP editors and we'll be happy to have you on board as an EIP editor.

## 9. PEEPanEIP

Paritosh and Maurice will be on PEEPanEIP tomorrow march 2nd at  UTC to share the details of how to participate in the kiln test net. The recording will be made available early next week so if you can't join you can always follow the recording. Another meeting is planned on march 15th with Alex stokes and the topic is EIP 4444. This is also an interesting EIP under active discussion with developers, so it will be good to hear what this proposal has to bring for the Ethereum ecosystem. Other meetings are listed in the PEEPanEIP schedule(https://github.com/ethereum-cat-herders/PM/projects/2). The link is available in the agenda.

## 10. Meeting documentation and ECH Github Issues/PRs

Almost all meetings have been documented. Consensus meeting 82’s note was reviewed yesterday and should be uploaded today. Thank you everyone for making it possible that we have all the meeting notes available within the five days’ time period that is suggested by the cat herders. 

We have closed almost every funding request which were open for about two weeks and I see few more few new pull requests open and I hope to address them this week of course these are the new one we hope to address them this week so we are in a position to release the funding soon for the contributors.

## 11. Review of outstanding action items from previous ECH meetings

Update on merge testing discussion between KTH Royal Institute and Ethereum devs. I have shared the updates.

William to post ECH monthly report for January on Mirror. I think we will be working on it. I'll be talking to William um maybe after this call and look into it. William to clarify with multisig signer where the ENS domain should be transferred. I think the discussion has been initiated. We are waiting for response from some of the  multisig signers. Maybe we can get some update this week. 

Pooja to request client meetings to be added to be made available via permacast. I am yet to reach the team I hope to do it this week. Maybe I’ll keep it open and we'll confirm to the meeting if this has been completed. 

Pooja to push through outstanding funding requests. We have addressed all the requests from the long outstanding and we can see a few open this week and may be able to address it. So that kind of concludes the agenda items. 

If anyone has anything else to bring up or if they would want to discuss it in the upcoming meetings, this is the time. In the cat herders meeting we provide most of the updates which are useful for the community. We try to bring them up to the speed with what's going on in the Ethereum ecosystem and provide the highlight of meeting updates that we document, but I would love to hear some thoughts and how we can actually make it more community involved. 

We can brainstorming ideas if people have thoughts and suggestions on that. It would be nice to have it. We have started onboarding new contributors in our recent monthly meetings. They have helped and already started contributing to the ECH community. I’m seeing that as one way to be able to interact with community. People. if you are listening to the call and you would like to reach out to us please try to join us on Ethereum cat herders discord or just show up at our monthly meetings.

Shashank congratulates William Schwab on becoming an EIP editor. Pooja also thanks him and ends the meeting with well wishes. 

# Appendix

## Attendees

- Pooja Ranjan
- William Schwab
- Brett Allsop
- Xuanling11
- Jamiel Sheikh
- Shashank

## Next Meeting Date

Mar 15, 2022, 15:00 UTC.


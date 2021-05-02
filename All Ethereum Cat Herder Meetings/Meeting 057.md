# Ethereum Cat Herder Meeting # 57  Notes
### Meeting Date/Time: Tuesday  27 April 2021 at 15:00 UTC
### Meeting Duration: 1 hour
### [GitHub Agenda Page](https://github.com/ethereum-cat-herders/PM/issues/173)
### [Audio/Video of the meeting](https://www.youtube.com/watch?v=JEA0d64ykuQ)
### Moderator: Pooja Ranjan
### Notes: Avishek Kumar

----

## DECISION & ACTION ITEMS

**DECISION 57.1**: Unvetica will make the discussed updates.

**DECISION 57.2**: Remove LLVM item from agenda for the next meeting

------------

**Pooja Ranjan**:welcome to ethereum cat herders meeting 57. This is Pooja Ranjan, so I have shared the agenda in the chat.

# 1. [ECH website](https://github.com/ethereum-cat-herders/PM/issues/155)

**Pooja Ranjan**: The first item that we see is updates on ECH website so we have uh
we are joined by michael from Unvetica
to provide the updates
michael if you would like to take it

**Unvetica.eth**: Right, I have got a couple updates here we did have a few like alignment and text updates that we pushed to production. One thing I want us to mention or go over and establish before we kind of get into some of the details here.That's the most obvious item that needs to be resolved and that would be securing the domain. So right now one of the issues we had fixed from the last meeting was there was a slight routing issue where if you went to an https domain it would route to the correct site. But if you went to an http try to get to the ethereum cat herders you would route to the old site that's since been resolved. However the way we run about it was may I would probably say or I probably suggested a little bit backwards and technically what it's doing, It's just forwarding the website from the dot site domain over to the dot com domain which from a function standpoint works but that's probably not the best way to go about it. So knowing that the current domain where that's hosted now, I am wondering if it makes more sense to just natively get hosting on that platform and I can set that up. If it's easier it would just require someone to provide delegate access via godaddy and then I can go in and get in there and set everything up. Natively so that the source files are actually running on. Everything in one location that would resolve then we can see up here the non-secure section. So I will put that in the discord as well. Just as a request  but just so you know that's sort of the last big item remaining that I think. We should get resolved, I think we have got to plan for unless  there's any other objections to that the way we do it but there were a couple things added here mainly to the landing page which was the support section, the graphic here. Now I will link to the tv. So when you
click on this. It plays the respective playlist for Ethereum Cat Herders. Next if we go there is a button to make it do automatically. I thought that was all right now if we go to the network
upgrades that's also been updated so that London is showing and that the Berlin section has been archived. We have also changed from a sliding function to more of a graph as to facilitate some of the data for the previous network upgrades. It gives a better visual representation of the data. The cards got a little crowded and visually didn't quite work. So here we have got more of a comprehensive archive of the previous network upgrades and then we have got the calendar. I don't think that was officially tied into but that's now been connected and the same thing I believe here for the EIP resources. We have got the team
calendar now connected there with the correct eips. Now those are all linked. There were some that were missed previously and then for the implementers. The developer meeting the same thing. These additional sections were added and then linked for each of the respective meetings. The only other thing that I could get some information on is about us. Section was updated, so displays a bit more of a card for each member and contributor with their twitter and github profile. I was not sure where we wanted or if there was value in having like this bio button. Right now it doesn't do anything because I  was not sure where to go with it or if just having these links to their respective profiles is enough. I would love to get some input there from the group but otherwise these are the changes that have been done from our end.

**Pooja Ranjan**:  This is great, thank you so much for that Michael. Let me first start with that. Okay fine since we are on this page let's start from here, the last question that you had about the see bio button. So for now I think the excel sheet that we have created a few weeks back to add details. If somebody has added anything in that section as bio then maybe we can display that here. If not then maybe by default it refers to twitter because I believe we have people from different projects and the fields of ethereum, so it would be
good to know more about those people. I am hoping for some more names to be added here. So I think it makes sense from my point of view. I see a value over there but open to other suggestions.

**Unvetica.eth**: Okay yeah I think I would if no other suggestions. i think we can totally go
that route and I will just refer back to the data spreadsheet that was provided and we will just link and whatever date is there we will display

**Pooja Ranjan**: Make total sense thank you so much for that. Next the card visual of the
upgrade section uh can you if you can take us there. So this table format I think this table is already represented in the eth1.0 spec section, so would it be possible to like you know come back with the table section similar to the project meeting sorry the developers meeting or I don't know if you can.

**Unvetica.eth**: Could you specifically link me so I could make sure I am referencing the correct.

**Pooja Ranjan**: So the previous ethereum blockchain upgrades. You are on the right page
and below we see Berlin block number,date when it was deployed and the proposals as well as this thing. The table that we can see here is actually available on the Eth 1.0 spec repository. So I was wondering if this information was there on Eth 1.0 spec repository. If people want to get the details, they can get it from there but we do have the original card that you were proposing earlier.

**Unvetica.eth**: So is this, sorry I just want to make sure I am following correctly. So is this
to say that we also want the eth1 information here too. Is that what this is? I guess I am confusing what that means.

**Pooja Ranjan**: So what I am saying that this okay if you can also open up the ETH1.0 github repository let me share the link with you

**Unvetica.eth**:yeah that would be great.

**Pooja Ranjan**: Because this information is already there. So I am not sure of duplicating the information. So my point here was like  what are the challenges in getting back to the original card model

**Unvetica.eth**:well the original card model the data that we want represented. We have sort of a space. Issue a real estate issue without keeping it on the same page. So we want or at least were suggested that you want the block the date the respective eips and the blog entry and these all together and that to put on a single model gets a little crowded.

**Pooja Ranjan**:  All right so here, can you go a little up sorry go to the main net upgrade section,upgrade folder why I am missing it. Okay I don't know, looks like some changes have been done here. Oh no sorry , can you go back to the note. This section is ethereum/ETH1.0/specs. Yep yeah so you see the table is right here.

**Unvetica.eth**: Are you saying you just want a more defined table represented here so there.

**Pooja Ranjan**: I know I was trying to say that we already have the table right there and we intend to keep it updating there on that github page. So let it be there when somebody wants to go. We can actually direct it to that page and on the cat herders page. What we can
have if you can go to the please go to the meeting thing. I want to come back to the card thing.

**Unvetica.eth**: You want to reduce the amount of content in that table on Cat Herder's site

**Pooja Ranjan**: That's number one and number two I want it to be. I mean like I feel like if it is represented more in terms of like catholic contribution meaning the block that was published with information would be good like the section of blogs here. Base every upgrade that should have the blog section in  the card format. Also I was talking about like, I  don't know maybe I will try to explain it to you offline so that is one thing that I am thinking personally. But what are other thoughts if it is? We should go in this way on the card thing.
I mean obviously whatever is comfortable in real estate as you mentioned on the page
as well but my only concern here was duplication of data.Now if this thing is already available.There we can simply point it towards that

**Unvetica.eth**: Okay 
**Pooja Ranjan**: Okay I will come back to you on this particular thing.

**Unvetica.eth**: Okay

**Pooja Ranjan**: And now I have one more question on tv. So if we can go to the homepage. Yeah so I am wondering if we click on this like say the left tabs people need ECH
meeting. It's fine it will take us to the latest video that was uploaded on the youtube playlist section but what would be shown in the tv by default is it going to be the latest live meeting or whatever is going on so how is it like a design thing .
 
**Unvetica.eth**: Yeah, so it will display whatever the latest recording. The most updated one. So if you were to upload one today it would refresh to that one it did actually have a question on this that I failed to mention previously and I am wondering if there is value to maybe include an a fourth button that maybe says something to the fact of like play all
or see all or alludes to the fact that there are additional playlists and more content. That way a user could peruse the content on their own without sort of having to go in succession with each of these playlists or if you just want to show these as they are.

**Pooja Ranjan**:  I think that's a good idea to have a play of all kinds because there is definitely more information than this. Because we have EIPIP meetings also like ECH meetings. we also have,EIPIP meetings we had some recordings from breakout room meeting, So it is personally I think it makes sense to have play all and let them browse through the  whatever contents are available there. But as of now I am not sure if tv is trying
to reflect this. The updated one because yesterday we had a community event or that was a
community call which was again live. So I wonder why is it not reflecting the updated one?
So, I am just worried if it is hard-coded that this is why by default it is going to show or we have the flexibility over there

**Unvetica.eth**: And the newest recording that was put in the respective playlist. 

 **Pooja Ranjan**: Yeah of course, it was in the community events can you click on the community events? Let's see what it shows. No it's not updated. 

**Unvetica.eth**: Okay then I will look into that a problem.

**Pooja Ranjan**: Because after 1559 we had this Berlin upgrade that also went for community update and then yesterday we had eip3074 that was also again a community event. So, it should be like the latest one is the 3074 community meeting.

**Unvetica.eth**: Okay not a problem then I will add that additional button and then follow up as to the updating of the current links

**Pooja Ranjan**: Yeah, so just to  like it, I tried this. The two rules here would be adding an
additional button to browse all  section of the Ethereum Cat Herders that's going to be
kind of playlist like 123. We have  the fourth button here and on the tv that would be by default. Whatever is the latest upload or the live. Am I correct to understand that.

**Unvetica.eth**:yep that works okay
**Shane Lighthouse**: Is that to say effectively that the tv will default to play all and it will be the latest that displays. 

**Unvetica.eth**: That would be.Yeah that's the way I am going to go about it so for example if I were to click on ,if  that was functioning as expected and correctly today. If I were to click on  community events. It should show I forget what Pooja now said that the

**Pooja Ranjan**: Correct change

**Unvetica.eth**:yep would that would be now displaying instead of the 1559

**Shane Lighthouse**: Yeah and would we um would we default to effectively play all.

**Pooja Ranjan**: For that I think we are going to have a button right, 

**Unvetica.eth**:yes but that does bring up a good question: which one do we want highlighted first? Do we want to maintain because right now it's defaulted to peep and eip or do you want to maintain that or should we have it default to the play all.

**Pooja Ranjan**: So, just to be clear, default here. We are talking about what we are going
to see in the screen of the tv section right.

**Unvetica.eth**:correct yes 

**Pooja Ranjan**: So let's make it the latest one. Whatever is uploaded latest not the
default. People need whatever is uploaded latest, let it be the thing notes or the evening or whatever is the latest should be there if that makes sense.

**Shane Lighthouse**:  Yeah so play all.Should be the default and it will just show the latest.

**Unvetica.eth**: Okay that works.

**Brent Allsop**:  Lots of extra programming.

**Pooja Ranjan**: Sorry about that but this is like a really amazing feature that has been added. I don't know if we are still talking about rotating or if this, I think the tabs also. It is fine but this is really interesting this will give us complete visibility.  If not complete at least enough like very high, to say good level of visibility of what I think.

**Shane Lighthouse**: If you default to play all as you've just discussed then it will constantly rotate through whichever there is the latest. So it will keep it fresh.

**Unvetica.eth**: Love it okay.

**Pooja Ranjan**: And yeah one last thing about the native hosting thing so I don't know if I got it wrong. In the beginning like my understanding is currently if people are typing https
then it goes to the old one but if people are typing http then it comes to the page that we are seeing right now. Right?
**Unvetica.eth**:uh yes but that's that's resolved you know. So the only thing we need left is 
to secure the site so that we get the padlock and the ssl certificate pointed to the correct site and the really the best way to go about that is to eliminate the forwarding altogether and allow the ssl certificate and the digital assets to be hosted in the same location. So I will get with Charles on that in showing or providing instruction on how to give delegate access, which just allows me to use the native ethereum cat herders credentials without having, like purchasing abilities. Essentially, I can go in and at least get cpanel access and then configure that. So that we add a hosting account to it and the system source files as well.

**Pooja Ranjan**: I am not sure. I mean at my end it is still like the old one. Whenever I am
typing https is it because of the conflict that you're just mentioning or I don't know is it something different.

**Brent Allsop**: Just try clearing your cache because when I do that I get not secure.

**Pooja Ranjan**: Yeah that true, I mean that's what I am trying to say like not secure it's coming up with http. Right?

**Unvetica.eth**:correct 

**Pooja Ranjan**: Yeah so even at the moment if I do https it is not reflecting to the
new website it's going back.Your by default is removing yes. Can you click it that's it.

**Unvetica.eth**: That's what I am saying so that was Http here and that seems to be directly incorrect.

**Pooja Ranjan**: Yeah, so I mean If I am adding s then it's taking me to the old one. So I guess because,,

**Brent Allsop**:  I don't get that because when I take https it takes me to the warning
page saying this https certificate is invalid and then if you click on advanced you can proceed and you still see https but there's the big flash red indicator saying it's not valid. I can't go to the old site  Interesting.

**Unvetica.eth**: yeah I think you might  have a

**Pooja Ranjan**: Yeah okay, I will check it. Yeah one more time but either way that'll be. Yeah I am getting there. Please I mean it would be nice to just throw a message in the discord and if you can coordinate the charts on that would be great.

**Unvetica.eth**: Absolutely

**Pooja Ranjan**: Okay so this is all good it looks amazing to me. I will go through the content one more time to see if some links are missing or I mean it is not going to the right
place where we would like to take it. The next important thing integration of the you know
with the github that some part of it. Like not for all but as we discussed earlier like some section if we need to update. So we would like to get it integrated and with the help of pull request how we can update that. So that is something that we might want to discuss if not today maybe in the next meeting or in between these two meetings if you are okay.

**Unvetica.eth**: Yeah if we could do it in between Ithink that would be ideal. I think after I get with Charles to remedy the hosting and ssl issue. It should be quick work I would say a day two at most to get these last little fixes updated that we have already discussed during this meeting and then from there what I would like to do is barring any last little. You know text or link updates. It's effectively you know project completed at that point for the most
part at that point. What I would like to do is some sort of training session if you will and go over exactly what that would mean for the ethereum Cat Herder at large in terms of maintaining and or requesting updates and change. Overall support but that's what I think that'll be the quickest that way we don't have to wait for. You know the next meeting we can kind of expedite. Some of these things regarding the maintenance and support after this has
sort of, you know officially been completed.

**Pooja Ranjan**: Oop no that sounds good too. Please go ahead Brent.

**Brent Allsop**: Yeah on the um this might have to do with the redirect hosting and stuff like that. But I noticed when you click on the about us tab, it doesn't go to a new new url. In other words if you wanted to send a url directly to the about us page, you would have to give them
ethereumcatheters.com and then tell them to click on about us rather than a url directly to
that page. So there's that is there any way we could have an html link directly to the about us
Page?

**Unvetica.eth**: Yep, absolutely and that will. You are absolutely . your suspicions are  correct in that once we resolve and have that we remove the forwarding and are natively hosting on the where the domain is hosted. You will then see preview to the full
url that's really just being masked right now because of the forwarding.

**Brent Allsop**: And also the c bio buttons don't seem to do anything. Is that just something that hasn't been done yet ?

**Unvetica.eth**: Correct, yep that's what we briefly mentioned before with.

**Brent Allsop**:  That's all I had. Looks very nice, thank you

**Pooja Ranjan**: Yeah great, So Michael maybe we can connect this week or sometimes thursday or Friday and we can discuss it whatever is missing to finish it up as early as possible, 

**Unvetica.eth**: Sounds great. I think that's a solid plan.

**Pooja Ranjan**: Thank you so much for the updates.

# 2. [Working group for LLVM catered for blockchain](https://github.com/ethereum-cat-herders/PM/issues/167#issuecomment-813403431)

**Pooja Ranjan**: Moving on the next item on the agenda is working group for
LLVM and creator for blockchain. I am sorry if it is just repeated from the last time or if
you have anything to add here.

**William Schwab**: So I have touched space again. I don't think that there's going to be  much report here. In the meantime, I don't think as of right now the people I am in touch with. Don't think that like there's a couple of things they kind of want to take care of before.
We actually kind of pursue open comps and assembling a working group. So I would recommend taking it off the list for next time. We do realize that if we are going to start something in terms of reaching out to people trying to assemble a group that will probably bring it back up to try and get it under the character substances.

**Pooja Ranjan**: That makes perfect sense to me. 

**William Schwab**: Okay cool

# 3.Events & community call 

**Pooja Ranjan**: Okay the next item on the agenda today is events and community call. So I have listed three events and community calls starting from Berlin that happened like two weeks ago. Not two weeks a week ago I guess. So we had this Berlin community countdown call and it was a good conversation with the eip authors. We learned about reading the folk man and some interesting stories about earlier upgrades so, if people have missed joining the party it's a good watch.  A recording is available on Ethereum Cat Herder youtube. Similarly we had a community called for eip 3074 yesterday. Eip3074 is a proposal that was
up for london but because of the decision of the client team to keep london skinny, this proposal might be seen in shanghai. So the authors of this proposal shared an update. Currently it is on the developer's test net. So what's the latest development, there is a brilliant demo by Anscar. The recording is available on ethereum Cat Herder's youtube. It is a good watch for people especially for the infrastructure provider and wallet people. It's a good piece of information for Coindesk upcoming  consensus 2021 event. We have representations from the ethereum team for both consensus layer and the ethereum1.4 chain . So I am sorry what is the term that we use the execution layer, so yeah recently there is a revision of terms that would be used for ethereum1.0 chain and 2.0 chain. Because merge is very close so we have participation from both the groups. I am going to publish a blog announcing the speakers from our community or very soon maybe this week. And yeah that's all about events and community calls doesn't even have any question comment. I mean it seems fairly simple.

# 4.ECH funding & fund management

**Pooja Ranjan**: Okay in that case we can move on to the next item that is ech funding and
fund management. Funding via eip, so Hudson was in touch with some of the esp people to figure out if we can get funding  from the ecosystem support program. Unfortunately I haven't heard back on that. But on the molok side I believe there is a meeting next week and I am expecting to you know share the latest report. In the past six months since the funding was done. I think November or december 2020. So we have to present the progress report and maybe we will request for future funding. I am not going to handle that. So I am not sure if you would like to talk more about something that you were discussing earlier?

**William Schwab**: Okay fine, did you want to do that after the esp stuff, just because it's pretty much the same topic or what do you think?

**Pooja Ranjan**: I am cool. I am in like yeah you can mention that okay.

**William Schwab**: I have been thinking recently about certain ways that things have been going into characters. I was interested in maybe creating another paid role for myself in a
part-time capacity focusing on external. Basically looking for extra places where they get
or not even necessarily extras looking for places where the cat herders can kind of streamline ecosystem advancement either by getting the right people in touch with the right people. Helping people find the support that they need and basically establishing comms and working groups. Around ideas or eieps or things of that sort that need it. so I have been talking a little bit internally about that and I wanted to present the idea to the wider Cat  Herders here. It would be contingent probably on fundraising that happens in the future for instance the small proposal. ESP which I will talk about and maybe other additional ways we have bringing a little bit of extra revenue into the Cat Herders. I would probably also try and take more of an active role with some of the internal work. Pooja is doing a massive amount of work right now and I would also want to try and step in just to take some of that burden and help the internal management of it. So I wanted to present that idea and see what people have to say about it. You don't have to worry about making a decision right now. There's only five of us on the call but just to kind of get the idea out there and your feedback.

**Brent Allsop**: Sounds great to me.

**William Schwab**: Cool all right and that definitely doesn't sound like there's any excessively strong opposition. So I will see where we can move from here. I will probably be in touch with pooja about first of all things that I can do to help in that capacity. But also ways to try and secure the funding for such a thing and when there's more concrete details we will bring them back here.

**Pooja Ranjan**: Sounds good. So maybe we can discuss I mean it before the next meeting and if you have something to present to the broader audience. I will make sure
to add an item okay.

**William Schwab**: I think that's probably a good idea.

**Pooja Ranjan**: so that's it on this. I don't remember exactly what we decided on the next biting the yield bearing instrument. Did we think that we had enough fun to put on hold? I don't remember.

**William Schwab**:We talked about it in the discord immediately following the meeting. I will try and bring up the discord now. But I am pretty sure the conclusion was that it's not going to be worth it for us until the next round of funding comes in

**Pooja Ranjan**: Right okay that makes sense so I am going to take this item off.
**William Schwab**: Yeah I will double check it. In the meantime if I find something different I will chime in.

**Pooja Ranjan**: sure thank you so much.

# 5.[Meeting notes](https://docs.google.com/spreadsheets/d/1axM1KaKc-GCcoPbAnYTOhgLnxXsBVoO5XRjTN3CLnck/edit#gid=0)

**Pooja Ranjan**:  The next item is meeting notes that's something that Iwant to really discuss. I don't know if we do not have a very good number of people joining the call today but I am sure the recording will help. We are looking for more people to document notes as of now for 90 minutes meeting we have just one person that is shane. Thank you Shane for staying. Yeah I mean Avishek is also doing but he did a couple of ETH to implement his meeting and he is not very keen to take up the all-coordinate meeting. He finds it very
technical and difficult and the other challenge that came up that has been reported by a few resources is like the absence of captions. Capture captions help kind of you know if they are not able to catch up the accent of this speaker because developers are from different parts of the world and the terms that they are using are technical. So sometimes it becomes challenging for the non-technical people or people who are really new to the ecosystem to document it. Having said that I have identified someone to document the ACD meeting 110. But he is still shaky to come forward unless he finishes it up. He did submit me a rough draft but he's not very confident about it. So I am expecting that to be done but in case it is not done,we still have that meeting notes open. We haven't gotten like any confirmation from someone to finish it up and yeah I mean what are the thoughts on how we can engage more
people to document notes.

**William Schwab**: Pooja, do you have a feel for how many people. Ideally you would need on a sort of rusted basis versus how many you have got at the moment.

**Pooja Ranjan**: Yeah for the technical meeting those are of high importance. There are
three at the moment which I consider is all coded ETH 2 and merge and for that if we have at least 3 resources. I mean one so we can schedule one for every meeting right if we get all these meetings in like a gap of 10 to 14 days. Right so that is there and we do not have but for some other not so technical meetings like cat herders and eipip we have fairly good amount of people to document those notes.

**William Schwab**: So we're really only looking for the big three right now

**Pooja Ranjan**: Yeah that would be my priority yes.

**William Schwab**:  Just to maybe try and directly answer your question also shane I think it could be probably a bit hard to measure it in terms of people because you have people who put themselves in all three rosters. Then you have someone who might put themselves in one. So I think each meeting probably needs like four or five dedicated people in a roster for it to really flow well though it could be a little bit less than and still be functional. Especially if people aren't like on a number of meetings which reduces the chance of like you know pulling some kind of impossible scenario where you have to do all three meetings in one week or something like that yeah. Does that sound about right?

**Pooja Ranjan**: Yeah I mean yes precisely so at the least we need three people to document 90 when it's not. I  mean if you have more that's always better.

**William Schwab**: I would think that newcomers to the space who are technical are probably a really good place to try and tap into but I am not sure exactly what the way to do. It would be I mean people who are already technical and looking to get more knowledge in the space.

**Shane Lighthouse**: I am I think college student area if I were to put it out in the various
communities on reddit that I am part of Michael as well. We could get some quite willing
volunteer people are really keen to contribute. So pooja I could say attempt to go to recruit
3 to 4 people say to enter the roster for the technical goals.

**William Schwab**:  I mean more is good too but if like you're saying that's a good number
for you to focus on going for it. What about a twitter tweeting maybe kind of focused around
college students or something or like you know that kind of demographic like maybe even calling that out. You know a college comp side who's looking to get into the ethereum
space and are trying to figure out how to get a more deeper technical understanding like maybe try being an ACD note taker. Do you think we can do something like that.

**Shane Lighthouse**: I think that's a good idea.I will personally don't have that twitter reach.

**William Schwab**: we've got we've got an Ethereum Cat Herders, twitter, so can I
put that to good use.

**Pooja Ranjan**: Yeah definitely  that could be that is something that could be looked into and I also have to look on the part that we should provide more access to twitter. William I am looking into it, that's it to ruin me. I will make a note of that and we will try to add you there, So that these kind of things if it is coming up with multiple people I think would be
helpful and shane yes I think that sharing it on reddit as you were mentioning it earlier would be helpful. So whatever can be done in this direction.

**Shane Lighthouse**: yep no problem I will take that.

**Brent Allsop**: Sorry Brent did I cut you?  you were trying to say something.

**Brent Allsop**: Oh yeah no problem we are just still interested we have got some other higher priorities right now hiring some people for canonizer. But our goal is to still hire and pay a good salary for a full-time cat herder to help with those kinds of things. So someone knows someone who's looking for a job that could do that full-time and we want to pay them a good salary to do that kind of stuff but just fyi.

**Pooja Ranjan**: It's on the sweet of you thank you.In the meantime I am thinking if we can start posting like I did it for a couple of meetings. So creating an issue for people who may be listening to this meeting. Later on I will be creating an issue in the Ethereum Cat Herder  is pm github repository. You can look out for any open notes bound with bounty over  here. Anything more on this topic, oh yeah we do have some notes documented. I believe shane you have already submitted. Will request for last all coder meeting would you like to provide a summary quick summary here?

**Shane Lighthouse**: Most of the discussion was around the date for london which is now sort of targeted for 14th of July from memory and there was a lot of discussion around this. Sort of feature fork shanghai that would be planned in and around the merge but core devs are waiting on the outcome from rayonism before any sort of further calls are made on the merge timing.

**Pooja Ranjan**: Yeah and that's good. We have another all coder meeting coming up this week that was just like an off schedule meeting. So we have next all core dev 112 on this friday. Do we have any more people on the call who have documented any other meeting notesIn the past two weeks I don't think so.

# 6. [Peep an EIP](https://www.youtube.com/playlist?list=PL4cwHXAawZxqu0PKKyMzG_3BJV_xZTi1F)

**Pooja Ranjan**: Okay,so moving on to the next section it's peep and eip. Last week we had  people on eip 3403 that were partial removal of refunds with the vitality. That's quite interesting. We learned a lot about why this proposal is being pushed by the ethereum developers. Why do we need to remove it? But  during the discussion it came up that there are some numbers that they would like to improvise and  for this reason there would be another proposal coming up soon more or less the content is going to be the same. But there would be some changes in the technical specification. So it's highly expected that there will be another which can be considered for the London upgrade. Unfortunately we are not having any meeting this week of the author of the proposal that we were expecting. This week is  unwell. So we have to reschedule it. And yes we are looking for more proposals to be added for peep and eip. If you have any suggestion or any proposal that you would like to see in future episodes. Please do let us know. You can always stop by Ethereum Cat Herders github and a discord. Let us know what would be the interesting proposal that you would like to learn more about.

# 7.Discuss and close the ECH GitHub Issues/PRs
 
**Pooja Ranjan**: Now the next is issues and pull request. I think for pm and funding section
In the pm section, we have just one open issue  for bounty for documenting meeting notes that was for ACD110. If somebody is still interested they can always reach out to us and on the funding sites I believe most of them have been completed. I guess shane you had just won this latest one right so I will look into that. I will try to  initiate the transaction today and yeah that should be good for eip bought. Alita has provided some updates in the discord channel. She mentions that this is almost done. Let me just read out. She mentioned that she probably can't make the meeting today in short what is almost done and just release 
draft of equal plus key block number for Json rpc but that was for Json rpc for what it seems like it is almost done. That's on item number seven.

# 8.Review of outstanding action items from previous ECH meetings 

**Pooja Ranjan**: The last is the meeting  notes from 56. I think the link is broken.

**Brent Allsop**: Yeah I just placed the real link in the chat.

**Pooja Ranjan**: According to this uh the dissociate item script consensus was in favor of having sections on company role or that is related to the about us section. I believe we  discussed it today with Michael. You may have to make some changes there. Number two note takers to update read me pages for meeting when posting notes.Yeah that's very important thing like when we are  submitting the pull request, we should also include the readme changes there I believe I have seen it in the last all called them meeting notes when it was when the request was created so thanks for that.A ction item Pooja to chat William  offline. Working group of general intermediate representation. We are dropping it for a while but there is some other proposal. We will be talking about  next one is to talk about the ech
fund and I probably believe it is related to the different options that we were looking into. But as per my understanding it seems like we do not have enough fun and we have to wait till the next round of funding is done. Anything else for today that people would like to bring up. We made good progress. We are almost on time. All right  thank you everyone for Joining us today.  I hope to see you all in two weeks but in the meanwhile as a Cat writer I have a request to try to engage more and more community people. We need more people not only for documenting but also for sharing more information. Now that we are talking  like we are getting engaged with more number of meetings. So it's better it's a good idea to share more
information of the latest on every section eth 1.2 and the merge size.  So thank you all very much for your contribution. Hope to see you again next week. 

----------------------
## Attendees

* Pooja Ranjan
* Brent Allsop
* William Schwab
* Unvetica.eth
* Shane Lightowler


## Next Call - May 11, 2021 .



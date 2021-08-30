# Ethereum Cat Herder Meeting # 65  Notes
### Meeting Date/Time: Tuesday  17 August 2021 at 15:00 UTC
### Meeting Duration: 1 hour
### [GitHub Agenda Page](https://github.com/ethereum-cat-herders/PM/issues/222)
### [Audio/Video of the meeting](https://www.youtube.com/watch?v=jhO1Qz-vViA)
### Moderator: Pooja Ranjan
### Notes: Avishek Kumar

-----------

**Pooja Ranjan**: welcome to Ethereum Cat Herder meeting 65. I am going to share an agenda in that chat here.

# 1. ECH updates

 **Pooja Ranjan**: So the first item on the agenda is ECH updates.

## [ECH website](https://github.com/ethereum-cat-herders/PM/issues/155) & decide on whether to pay for ECH marketing for the website

**Pooja Ranjan**: The first one listed here is ECH website and decides on whether to pay for ECH marketing for the website. On that I did pass this information to the website development team unfortunately Michael could not join the call. He mentioned that he has schedule conflicts and he would not be able to join. However he provided an update that our system has become much more stable and is reflective of the current of time. We asked them to add some eips as educational resources and that has been done. The current version is the version 1.2.0 which was deployed on august 12th, so for people who aren't aware to maintain this website. What we are doing is we are following a process of making an issue. I am sharing the link here in chat. So if you find anything on the website that needs updating. What you need to do is simply go and create an issue and relevant links and the website support team will try to make the changes which are requested by the ethereum cat  Herders or by the community in general. On the proposal side I haven't received the details of the proposals on that. He would like to propose for marketing of ethereum cat herders, so maybe we will wait, maybe at the next meeting for him to respond back on that.

## [Meeting notes](https://docs.google.com/spreadsheets/d/1axM1KaKc-GCcoPbAnYTOhgLnxXsBVoO5XRjTN3CLnck/edit#gid=0) and action items for ECH

**Pooja Ranjan**: Moving on the next item is meeting notes and action items for meeting in
Cat Herder as far as I know we are good with all but one which I expect to be receiving today. We have ethereum cordev meeting uploaded, ethereum 2 meeting 70 is also submitted, eipip meeting will be submitted by today end of the day I suppose.

**Brent Allsop **: Yeah I just did the pull request on that one this morning.

**Pooja Ranjan**: Thank you so much. Yeah so that is also available now. Anything specific in EIPIP if you would like to share Brent. If not that's fine we can go by the photographer.

**Brent Allsop**: No I hadn't thought of anything, yeah it was kind of a short meeting. Okay all right, not a problem. I think I may have something that I will bring up later in this meeting today.

## ECH engineering ([Alita's comment](https://github.com/ethereum-cat-herders/PM/issues/216#issuecomment-891626343))

**Pooja Ranjan**: So moving on for now. Next is ECH engineering Alita and I see your comment from the last meeting when you were not there. I believe the question was about
you know how to go about next funding. So yeah first if you would like to go ahead and provide any update on your end and then we'll talk about it yeah.

**Alita Moore**: So in the past I guess like since the last meeting I built the bot for the auto withdrawal. Bot that goes through the eips and marks any eips that haven't been changed for a year as withdrawn so that's like what the engineering has been doing. The goal before next meeting is going to be to address like a bunch of bugs and then I think I will try to implement a feature for the bot like maybe being able to look at multiple eip files at once just
like that in a single pear yeah and then I know that I spoke with Pooja about the funding or continued funding and she mentioned that it had been secured for the next three months.

**Pooja Ranjan**: Right I will provide the details. I think we have a specific item on funding. So we will talk about that more. By the way I have a question on this  withdrawn status bond so, is it for github only or is it for ethereum.org?

**Alita Moore**: Yeah, it's for github only. Is there a difference between github and ethereum.org?

**Pooja Ranjan**: So what happens  when it is on github? It will close the pull request that would not be shown but I am not sure if the status is being changed. So you are  saying this part? I mean I am just trying to understand if this part will be able to change the status to withdrawn or just remove it from the pull request section.

**Alita Moore**: So essentially it would change the status of the eip to be withdrawn on github.

**Pooja Ranjan**: Oh if it does on github. In my assumption it will automatically be shown on the eips.ethereum.org. By any chance did you get to check if it does or does not.

**Alita Moore**: No I haven't been able to because I haven't been able to test it on the main repo yet. I am still working with Micah to figure out a few things.

**Pooja Ranjan**: All right, yeah that sounds good to me. We have been waiting for this thing for a while like with the earlier part . The proposals which are there in the  repository are closed and they are marked stale and closed but the status does not change and we would like the status to be changed on eips.ethereum.org as well. So I hope with the working of this part it will be really helpful like we'll be getting a clear picture of which proposals are in active status. I am just asking you don't necessarily have to give up and date for that. But is there any timeline and expectation?  Do you think it would be done in a 10-15 days timeline or whatever?

**Alita Moore**: So it depends on the conversation that I am  currently having with  Micah. Kind of comes to essentially I built like a simple version because like it was the fastest thing to do and Micah might have some suggestions on like better features to implement and so depending on what we come to on that like I could potentially launch it l today or I might need to wait until like a week or two.

**Pooja Ranjan**: All right I am happy at least it is making progress because this was a long wait. We have been waiting for it for a while.

**Alita Moore**: I will try to be more timely in the future.

**Pooja Ranjan**:Oh no worries no, not very bitter. I was just happy about it, like at least this is happening because there's a lot of proposals that are in draft status and we don't know what it is like. It's over 100 .So I am having a hard time reaching out to every author individually. So I am assuming this part is gonna help reduce my workload. Thank you for that.

**Alita Moore**: Of course

**Pooja Ranjan**: All right, thank you for the update.

## Cat blazers

**Pooja Ranjan**: The next sub item is cat blazes. Anything you would like to share with William today?

**William Schwab**: Sure, so for the last couple of weeks I have been involved in trying to get an initiative for basically trying to get a group wallet test. A working group working on wallet testing together in order to kind of streamline finding major kinds of cross-wall issues and also specific recurring  wallet issues. Initiative was suggested by someone in status so we have been trying to find some resources and get comments together for that. I was also involved a bit in trying to get an nft together for the london. Either network upgrade or hard fork whichever nomenclature you prefer started some of the distribution from that got disrupted by London actually because the wallet rollouts for London support were a bit slow and needed to get back to that and finish that up. I have been working with  ethernet dao doing some onboarding work. Their goal is to take senior devs who are interested in other non-blockchain disciplines who are interested in getting into the blockchain ecosystem and training them up so I have been trying to work there. Just lending some skills for onboarding
and I think that's been my main focus for the last two weeks. I might be missing something or two things that are getting to the point  where I have got enough going on. It can be hard to keep track of all of it but that's I would say that's kind of like a rough overview.

**Pooja Ranjan**: Awesome yeah so yeah I was about to say that this wallet testing and working with ethernet data either not to that you just mentioned. I am not sure I am just throwing some ideas like would it be possible for you to do a write-up about it like what you
are doing or maybe if you would like  to invite more people to join the work or testing is being done if you have any thoughts on that.

**William Schwab**: Right up it's a matter of finding time. I am not against what was the second thing you suggested. I didn't catch all of it.

**Pooja Ranjan**: I mean like this wallet testing thing that you are doing like how is it working and now as I am finished so if you need more people like you know about it. What's going on, talk about it.

**William Schwab**: What if I need more manpower?

**Pooja Ranjan**: No more participation there.

**William schwab**: In what way?

**Pooja Ranjan**: Okay so if I understand this correctly you are working with groups who are involved like you know testing certain wallets like different transaction types I believe.

**William Schwab**: Not necessarily transaction types, it's really just I involved integration into the apps can be difficult.

**Pooja Ranjan**: Integration into the app.

**Wiliam**: Oh yeah yeah so more application level than vertical layer.

**Pooja Ranjan**: All right yeah yeah this sounds interesting to me but I know I am not the right audience for that but I am assuming there could be people who are looking out for it. Like that developers who may be looking for some help with the integration into the introduction so in that case maybe  if you would like to do a write-up as  you mentioned that it may be a matter of time.

**William Schwab**: Yeah I can look into making a write-up for that and for ethernet down. I am running behind trying to give a summary for July. So maybe what I will do is I will even kind of roll July and August into like one summary write up and I will try and put some information in there about it. That makes sense.

**Pooja Ranjan**: All right yeah yeah that makes sense. Thank you so much William. 



## London upgrade NFT distribution

**Pooja Ranjan**: All right moving on to the next sub item distribution Thank you William, John for joining. I believe that was your idea originally so if you would like to provide any update on that.

**John**: Well William Schwab is working on distributing them so I mean that's kind of that front. I don't think there's much else to say.

**Pooja Ranjan**: Right I mean it's being done in a very short duration thank you. William Schwab for having the artists like taking the responsibility of distribution. I have added the
wallets of whoever reached out to us or whatever we can collect. I believe this distribution will be completed soon as as William already mentioned that it  was load because of the upgrade itself so we hope that it will be kept answered thank you so much both of you for
working on this.

# 2. [Peep an EIP](https://www.youtube.com/playlist?list=PL4cwHXAawZxqu0PKKyMzG_3BJV_xZTi1F)

**Pooja Ranjan**: The next sub item is a peep an eip in the past two weeks so we released
three  meetings one was on the block calf limit with vitalik returning the number two is the FB2981. NFT loyalty standard with Blake Malone and the third one we released today. It is mkb and flash parts with the mass stanza. So people interested in learning about these technologies and following up with ethereum's new proposals. I think  watching these episodes will be super helpful for eip 2981. I have seen that this proposal is now in final status but there are few proposals and few people coming up with different ideas and they want to make improvements. My recommendation to them would be to start a new fellowship of a keto magician thread and then I think this proposal can be considered as a baseline or if they have entirely different approach to manage their royalty standard for nfd that can be proposed so yeah I also have left comment on the issue if there is any question or any kind of facilitation needed.I suppose they can reach out to ethereum cat herders and Anna Charlie Cooper. She is also managing the NFT groups in the upcoming week so we have one schedule for tomorrow that is the eip 1271 standard signature validation method for contracts that is planned at 18:30 UTC on August 18. That's all on the beep and eip. Sorry it seems I am a little distracted today. Sorry about that.

## EIP/ERC editing
 
**Pooja Ranjan**: I think I missed one sub item from the earlier topic that was eip and erc meeting. So last Tuesday we had this eip editor mentorship meeting with William Schwab lifeline me and we went through several proposals. Kindly shared his tips and tricks and suggestions how we should look into these proposals and we jointly left some comments. There were a couple of issues or special cases that came up. We discussed it and that
were also brought in the following eipip meeting one of those were the title of ERC. So the agreement there should not be duplication of adding  the eip number in that title so it is removed. I believe lifeline created pull request to remove the eip number from title from
whatever was in final status and I have created pull requests for updating the eip1 as well as the readme file of eid's github repository so this is a very small change in process for ERC standards that they don't have to write the eip number or the erc number as they would like to say before the title. So that is one thing I wanted to bring up here. Anything else if I am missing please let me know William

**Wiliam Schwab**: There  were some other menu types like I think that's good somewhere.

**Pooja Ranjan**: All right

# 3. Discord channel

**Pooja Ranjan**: Okay moving on to the next item is the  discord channel. So we're trying to manage ethereum cat herders as discord with different channels and you know try to engage people more into conversations like whatever they would like to discuss if that is not highly
technical or if that is not related to research they can come to the ethereum categories community channel and discuss it. In that process recently we have received a request of
having a governance channel like not governance of ethereum in a specific but ethereum in general. Whatever they would like to think about the process or the changes or if they would like to talk about anything related to governance. If we can provide them a proper placeholder for that. I believe I had this channel created for governance as general discussion but it seems it is not active for all people. It is not being used properly so  what is a thought here like what do people think if we can have it for general discussion.

**William Schwab**: I mean my thought is that it's generally not a good idea to have like too many channels because it gets kind of confusing to navigate and like you spread out the discussion quite a bit

**Pooja Ranjan**: Yeah I would agree that having too many channels is kind of too much for people to look into. But it's my personal thought that having a topic specific channel also gives an opportunity to people to come and join it for that particular topic like for example in our server there are miners. Most miners are talking in a specific channel that is a proper channel. I think it's time to rename it or not. I don't know most of the miners are  talking there and in the eip1559 channel initially now that eip1559 is also released. I don't know if they would like to archive that channel or rename it or like kind of move a different thing. So a topic specific channel is a good one for following if people are interested. People are interested in one particular topic but yeah I am open to suggestions here. What do other people think generally?

**Brent Allsop**: Yeah I am really interested in that topic building consensus and community and stuff like that. But I am not sure if everyone would be interested in my take on that but anyway.

**Pooja Ranjan**: All right yeah because you know I have been, I don't know I was planning to propose one more channel which I am not sure if it is right at this point of time but  anyway I am going to share it generally people come here and look for job opportunities. Right so what my initial take was like to move  them to off topic channels and talk about job opportunities there. I was continuously posting if there is any opportunity I find it anywhere on twitter or any other chat portal so instead of posting it on off topic maybe we can have a 
job channel on vacancy channel or something like that so people can easily
relate. Okay this is related to job opportunities so if someone is looking for it or someone is willing to post an opportunity there that would be a good  one for them. Okay maybe I would like to keep it open for now and we'll try to check with other people if there is any strong opinion on either side we'll try to act Accordingly.

# 4. ECH funding

**Pooja Ranjan**: Moving on the next item is ech funding  where ech bitcoin clr and muller
with eip. I am happy to share that we have secured additional three months of funding from
Then there is this report that we are working on. I am going to publish it right here. So thank you Alita and William for adding inputs to the report and yeah i'm planning to publish it as
as soon as possible so if anyone has any particular comment or thought that they would like to add please feel free to leave a comment and we'll try to resolve it. This is a basically a report for past six months what we did like I wanted to make it like mid-year but it's not
exactly the mid-year but at least it covers q2 and q3.  We hope to publish something similar at the end of the year as well that's on the funding side. I also had a meeting with the Molex team last friday and now they are trying to involve cat herders into more activities and tasks. Maybe they are planning to provide funding for some activities related to ethereum two or the upcoming merge so I am in touch with people and see if we can come up with different
ideas or if we can find a different group that needs support It's a work in progress. I will update in the next meeting

# 5. Discuss and close the ECH GitHub Issues/PRs 

**Pooja Ranjan**: The next item is discuss and close the ECH GitHub Issues/PRs on the project management side. I do not see any new issue and on funding I believe okay. Funding I believe we have closed all the funding requests except for William Schwab which I will try to do today. Oh yeah you have added the ether scan length. Thank you William. So for the reimbursement of gas here we generally try to re reimburse an act and that's why I have requested you to provide the ether scam link that is helpful. I will  try to do that today. Thank you so much for that.

# 6. Review of outstanding action items from previous ECH meetings

**Pooja Ranjan**: Wow we are almost at the last item of the agenda which is review of outstanding action items from previous ech meeting and the number one seems to be here is like investigating collaboration with each stakers on countdown for future upgrades. I did have a chat with Michael on this and we discussed the future collaboration plus the promotion of ethereum cat herders. I will wait  for him to be maybe in the next meeting or if he can leave an update anywhere on both of the items I get in touch with. I  think over discussing handling ex-time. Yeah that's a to-do on me. I haven't got a chance to talk to him. Yet I was planning to meet him but unfortunately I could not manage last week so we'll try to do it in upcoming weeks in the next meeting to discuss whether the people hosting ac's website should be hired to manage easiest social media. Okay in general we did not have any discussion as yet I believe in the last meeting we discussed that let's have the proposal first and then accordingly we'll decide whether to go about it or not. So because we do not
have any proposal and I am not sure if people would like to discuss this. I think that's all on the agenda item listed here today anything else anyone would like to bring up

**Brent Allsop**: Just a quick comment on the meta issue of eip39. Just fyi when I did the pull request the three previous meetings to the eipip. The meeting notes were there except
for 37 which we skipped because there was some other issue on that day and they push that forward to the next meeting  but anyway they're all missing and I fixed all those and also meeting 36 had a broken link in it because of a case issue it worked on windows but it didn't work on the upgraded so I fixed that but anyway all that's fixed just fyi.

**Pooja Ranjan**: Thank you Brent for that  yes I think there was one meeting which
We could not have the recording and it was like a very short meeting of 10 minutes or so so we tried to cover the topic in the  subsequent meeting. So yeah I believe there will be one
missing meeting video as the last notes

**Brent Allsop**: Yeah there was a link to the agenda but no notes or no are known.

**Pooja Ranjan**: All right, thank you so much for taking care of that. Yeah that's all about it. Thank you. I mean if there's nothing we can be released early.

**Brent Allsop**: That's always nice thanks and everyone for all you guys are doing you guys are  doing great stuff

**Pooja Ranjan**: thank you everyone for joining today see
you all in two weeks


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
* John

## Next Call - August 31, 2021 .





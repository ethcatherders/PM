# ECH Meeting 81 Notes
## Meeting Date/Time: Tuesday 29 March at 15:00 UTC
### Meeting Duration: 0.5 hour
### [GitHub Agenda Page](https://github.com/ethereum-cat-herders/PM/issues/275)
### [Audio/Video of the meeting](https://www.youtube.com/watch?v=xNNw-CIrXZg&t=18s)
### Moderator: Pooja Ranjan
### Notes: Jim Bennett

----
## DECISION ITEMS

**ACTION 81.1**: Refer any potential Ruby developers to Pooja.[see 10:35](https://github.com/ethereum-cat-herders/PM/issues/266)

----
## Chat Log

    From Pooja Ranjan to Everyone 09:00 AM
      https://github.com/ethereum-cat-herders/PM/issues/275
    From sanket to Everyone 09:12 AM
      is that event is also in India or not ?
    From Gulnaz to Everyone 09:13 AM
      Hi! Sorry, is this event only for India? Or worldwide?
      Hackathon
    From sanket to Everyone 09:14 AM
      ok
    From Pooja Ranjan to Everyone 09:15 AM
      ETHWMN is for India
      It's a fellowship not a hackathon
    From sanket to Everyone 09:16 AM
      ok mam
    From Jose ’s iPhone to Everyone 09:22 AM
      Cool
      Fine. Either way.
    From tushar desale to Everyone 09:33 AM
      mam you know I asked you a question how to generate NFTs on EIPs
      but actually I still not get a solutions from ETH R & D
    From Jose ’s iPhone to Everyone 09:34 AM
      That would be interesting. What is the proposal number ?
    From Pooja Ranjan to Everyone 09:34 AM
      https://eips.ethereum.org/erc
    From tushar desale to Everyone 09:35 AM
      Yes sir
    From Jose ’s iPhone to Everyone 09:35 AM
      For the nft
      Ok.
    From tushar desale to Everyone 09:35 AM
      thank for providing link mam
    From Jose ’s iPhone to Everyone 09:36 AM
      Ty
    From Shubhangi Gokhale to Everyone 09:37 AM
      Very helpful!
      Thank you for the meeting, Pooja!
    From tushar desale to Everyone 09:37 AM
      is there any mining  proposal regarding web 3 land
----

**Pooja Ranjan**
00:00
Welcome to Ethereum Cat Herders meeting 81. I have just shared the agenda in the chat. Before we get into the agenda items, usually if there is any new member joining in the call, we invite them to introduce themselves. And today we have two new people on the call today. So yeah, Jose, if you would like to go ahead first.

**Jose Alfonso**
00:25
Yeah, that's fine. Thank you. Hi, everybody. Thank you for the opportunity. My name is Jose, Jose Alfonso. I'm originally from Spain. [Unclear from 00:42 tp 00:56] I have been working for the time being in the APIs between cooperation between different clients: Geth, Nethermind, and Besu, specifically between Geth and Nethermind. Having said that, I'd really, really like to get involved deeper and deeper in the Ethereum ecosystem. After that, I received the call from Pooja. I was very, very grateful for that to start to work with the bot and with the Ethereum bot for the GitHub repos. And basically, roughly a week, I have been getting into it, reviewing the code and trying to identify different open pull requests or issues. and trying to find a strategy to do well to start to work on it. Very excited, very motivated. And I'm here for that and for anything that I can contribute. My background, roughly, is I am in computer science, but I used to work in the oil field. Because that's my other degree. I am an oil engineer as well, and then a computer engineer and the petroleum engineer. I was working for the last 20 years in the oil field. And in my spare time working with the coding in science, I started to begin an investigative study about Ethereum and I got hooked. So one more time, really, thank you for the opportunity. And I'm here for anything that I can contribute. I will do all my best. Thank you.

**Pooja Ranjan**
03:18
Thank you, Jose, for joining. Jose will be, as he mentioned, helping out with EIP bot issues. So welcome onboard.

**Jose Alfonso**
03:32
Thank you. Thank you.

**Pooja Ranjan**   
03:36
We have one more new, not very new. He has been here on our Cat Herders Discord for a while, but maybe for the first time on the call. Pradhumna, if you would like to introduce yourself?

**Pradhumna Pancholi**
03:49
Yeah, hi everyone. I'm Prad. I've been in the Web 3.0 space since 2020 and started a startup called Defypedia and have been building things that [unclear 4:05]. I recently completed auditing boot camp at Securian. And now I'm just trying to work as close to the Ethereum ecosystem as I can, so I joined. So thanks

**Pooja Ranjan**
04:18
Welcome again. All right. I see one more new name. I'm not sure if he has a microphone. Not yet. Never mind, we can go ahead with the agenda items. I've shared the link in the chat, but for people who joined recently, I'm sharing it again so you can have it handy.

## AGENDA

## 1. [Ethereum network upgrades](https://youtu.be/xNNw-CIrXZg?t=284)

The first item listed here is [The Merge.](https://ethereumcatherders.com/the_merge/) So as we all know, March is the next Ethereum planned network upgrade for the [Kiln Testnet](https://blog.ethereum.org/2022/03/14/kiln-merge-testnet/), the TTD has been reached about two weeks ago, that means on testnet, Merge is there. There was a live stream two weeks ago by the Ethereum Foundation. The Merge there was generally okay, except a few clients observed some hiccups. Prism and Taiko released their post-incident reports. And the Ethereum Foundation also published a couple of blogs related to the Merge. One was published on March 14 that was announcing the Kiln Merge Testnet. It also includes information related to tooling and infrastructure details. People looking towards participating in testing the Merge can follow the blog post and participate in the testing.

There is this another blog post released by the Ethereum Foundation named Finalized Number 34. That is a consensus layer newsletter run by Daniel Ryan. And that provides additional details on Kiln. Tim Beiko published ACD 10, the newsletter that is there for protocol level updates. And this newsletter contains information about Kiln, Shanghai, some small improvements that people are expecting, and one important thing is Ethereum execution layer specification. So people are now discussing the process for EIPs after the Merge. How do we want to see a generic process for EL and CL level proposals?

The second subpoint there is [Shanghai.](https://github.com/ethereum/execution-specs/blob/master/network-upgrades/mainnet-upgrades/shanghai.md) So for Shanghai, which is an upgrade expected after the Merge, there are six EIPs which are considered for inclusion so far. I suppose four of them are related to EVM: EIP 3540, EIP 3651, EIP 3670, and EIP 3855. These are all EVM related. And there are two more: EIP 3860 - Limit and meter initcode. And the last one that was added last week is EIB 4895 - Beacon chain push withdrawals as operations. So this is a new proposal which suggests a method for withdrawal of staking. So far, beacon chain is just one way people can stake, but the rewards cannot be taken back. But after introduction of this proposal on Mainnet, withdraw will be enabled. So that's on the item number one.

## AGENDA

## 2. [Events & hackathon](https://youtu.be/xNNw-CIrXZg?t=478)

Number two is Events and Hackathons. The first one is [ETHWMN Fellowship](https://ethwmn.devfolio.co/), it's initiative by Devfolio India, where they are providing fellowship to women Web3 developers. This is almost on the last stage. So women have been introduced to the technology, there were some classes, now they are being introduced to new proposals and to work on small projects. It's something new done by the Devfolio people, and I'm happy to share that I'm also part of this ETHWMN Fellowship.

[Devconnect](https://devconnect.org/schedule), which is another big event that is planned in Amsterdam, Netherlands, starting from April 18 to April 25. The tickets for [OG conference](https://www.ogcouncil.com/) are available for participants, obviously they are free. I suppose most of the tickets are free. Please check it out. The [link](https://www.ogcouncil.com/) is provided in the [agenda](https://github.com/ethereum-cat-herders/PM/issues/275). And the [schedule](https://devconnect.org/schedule) for speakers is also available now. The link is added to the agenda.

Any questions, comments so far? Well, these were just pieces of information. So let's move on.

## 3. [ECH updates](https://youtu.be/xNNw-CIrXZg?t=565)
09:25
Number three is ECH updates. The first one is the [ECH website](https://www.ethereumcatherders.com/). As we know, the ECH website is now being hosted with GitHub. We are hoping to keep it updated. I had a conversation with a new contributor - Salwa, I believe. He is not on the call today, but he showed some interest in updating the Ethereum Cat Herders website, and we have also received the first PR to update the Merge page. And with this PR being merged, we will have all the information up to date for the Merge, the testnets, and the information around that. So if people are looking for a place where they can find all information related to Ethereum merge upgrade, I think Ethereum Cat Herders website can be very helpful, lease check it out. The link is available in the agenda. We may need further pull request to keep this page updated.  

10:35
Moving on to [ECH engineering](https://github.com/ethereum-cat-herders/PM/issues/266), we are still looking for a Ruby developer. So if anyone listening to this call has some background and  bandwidth to help out, please reach out to us. If you are a Ruby developer, we are looking for some help on the EIP bot management side for this specific skill.

11:05
The next one is [EIP bot](https://github.com/ethereum/EIP-Bot/issues) & [EIPV](https://github.com/ethereum/eipv/issues). I believe Jose has provided some overview in the beginning of the call that he has recently started looking into the issues there. I don't know, Jose, if you have anything else to add on top of whatever you have shared.

**Jose Alfonso**
11:25
Yes, indeed, but I would like to ask you about the Ruby, because maybe I can speak with a friend. So what is it exactly they need for the for the Ruby there?

**Pooja Ranjan**
11:43
I suppose there is some piece of code which was earlier developed by one of the Ruby developers or contributor when the earlier EIP bot was there. So people are looking for that thing to be updated. If you have someone in mind, please introduce or ask them to reach out to us. I'll be happy to introduce it to the EIP editing team. I know one of the editors, he is looking for some support. Maybe we can introduce them, and they can also have a chat on the next EIPIP meeting.

**Jose Alfonso**
12:19
Okay, okay, good. Well, yes, maybe can share a bit more info. The specific issue that we're trying to accelerate the closing is the issue 53, which is related to the tool editors approvals. They're going to be dropping between, I would say, today or tomorrow in the ETH engineering chat, some ideas. And after that I will be commenting in the PR comment section about what I believe that could help to close this issue. Well, moving forward from there.

**Pooja Ranjan**
13:19
Sounds good. Thank you for jumping in. And if you have any questions, feel free to share it in Discord channels, whatever we have. And obviously on that issue also, you can leave a comment and people may be able to refer back to you. .\

13:42
Moving on, the next sub item here is [Learn2Earn](https://github.com/ethereum-cat-herders/L2E). I know we have people to speak more on that. So Pradhumna has joined recently as a contributor to look into [unclear] design and distribution path. And obviously we have George here. We have George on the call. So please go ahead with any further update.

**George Hervey**
14:01
hey guys, um, so for learn, we're glad to have Prad on board. In terms of updates, we have a PR in our repo, the L2E repo in Ethereum Cat Herders that anyone is free to check out and test to see if it looks good. Any feedback is welcome and highly encouraged. Right at this moment, you do have to create your own Morales server. So what I intend to do this week, which I actually meant to do last week, is actually spin up a testing website where basically anyone could check it out, play with it, and report any bugs or things that just may not seem that great and give us feedback along the way. That way, no one has to create their own developer environment and all that setup stuff that's kind of an annoyance. But pretty much chugging along, and almost done.

**Pooja Ranjan**  
15:24
Nice, thank you. And the pull request that is there for over a week now,I'm hoping to keep it open for a few more days for people to provide feedback on that. So please check it out. And if you have any feedback, share it with us, otherwise, we are hoping to close that by the end of this week. And there are also a few open issues. If you find something interesting in that section that you would like to take it up, you're more than welcome. I don't know, Pradhumna, if you have any update from your end - it's new, but just in case?

**Pradhumna Pancholi**
16:02
No nothing at all, just like roughly 10 things, but not yet any update on the code base itself. I'll probably start on that data tomorrow evening.

**Pooja Ranjan**    
16:16
Sounds good. Thank you. For people, we have started recording meetings and having notes, obviously these are not shared on YouTube. But if you're interested, please reach us. We also have a Discord channel which we are going to make public, so people can look into it, and if they would like to join, feel free to jump in anytime. Reach out to any of us if you if you are interested to contribute to learn to anything on tap that we are working on.

16:53
Moving on, the next one is Cat Blazers. I know there are two podcasts that were released. William Schwab unfortunately could not join today. So he did mention that. So there were two podcasts, one with Christie and the other one is with the product owner of MyCryptoWallet. These are available on Spotify. I suppose the [link](https://open.spotify.com/show/7dgxKMkSyy3HWtQW7OfqXA) is available in the agenda. About the ECH ENS names, I think now we own ethcatherders.ens for ECH ENS. Yeah, so that is done. It was due for a while, but now it's done.

17:44
Next one is ECH operations. Yeah, I see Shubhangi Gokhale is on the call.Shubhangi, if you'd like to take this one?

**Shubhangi Gokhale**  
17:55
Hello, hi. Yes, I would like to talk about having the new joiners meeting on April 21. If it's convenient for other people, I would like to have it around 4pm PST time and have another meeting on April 28 around 3pm East Asia time, because I'm in Japan at the moment. So I wanted to get feedback from the group if you're available for the 4pm time or if another time would be better. Or alternatively, I could put a survey in the general channel if that's more convenient. And yeah, I just wanted to get feedback from the group about the two times: 4pm, around 4pm on April 21, Eastern Standard Time and April 28, around 3pm. Tokyo Seoul time.

Pooja Ranjan  
19:07
So just for a little bit of help, or the Tokyo time you mentioned, can you suggest that in UTC?

**Shubhangi Gokhale**   
19:17
Yeah. Let me figure that out.

**Pooja Ranjan**      
19:21
No, no, that's okay. I just want to make sure that when you are sharing it with people, we have the same timezone or that whatever we are using, either EST UTC or Japan time, any is fine. Just people should be able to have the same reference, right?

**Shubhangi Gokhale**  
19:36
Yes, it would be 6:00 UTC, so 6:00 am UTC. And I checked the Ethereum Cat Herders onboarding form, and we have two new people who have filled out the form, and so I will be sending them an email Regarding the new joiners once we finalize the meeting, and you and some others that may be the Calendly invite may be helpful to get a reminder of the event going forward, or a Google calendar invite.

**Pooja Ranjan**
20:23
Yeah, I think a Google calendar invite is a good idea for new joiners. So they get to know about it, because I'm not sure if they are already on the ECH Discard. Also, we will try to add the events. Whenever the date is finalized, let us know and we can add that event on the ECH Discord. So whoever is joining the Discord server may be able to collect information from there as well. And for the two new joiners, I think one of them is Salva, and he has already started working on it. But thank you Salva. Thank you Shubhangi for interacting. And there is another one of which I believe would be looking into the EIP apprenticeship program. So if you can also add additional information related to apprenticeship, that would be helpful for the new user.

**Shubhangi Gokhale**    
21:15
Oh, yes, I'll do that.

**Pooja Ranjan**
21:19
Sounds good. Any questions? Comments? Feedback so far from anyone else? Well, we can always keep communicating if we have anything to share on the ECH general channel.

**Shubhangi Gokhale**
21:43
Yeah, thank you.

**Pooja Ranjan**   
21:45
Thank you, Shubhangi.

Moving on, the next one is [EIP insight](https://hackmd.io/@poojaranjan/EthereumImprovementProposalsInsight). So in March so far, and still there are a couple of days left, so far, we have one proposal that is moved to the Final status. That is EIP 4626: Tokenized World Standard. It's an ERC. And the repository has received 11 new proposals merged as Drafts. They have Sonatrach core ERC and interface category of proposals listed there. However, there are 12 open pull requests for new proposals. I hope to see some of them being merged, and once they are available on eips.ethereum.org, they will be added as new proposals here. 13 proposals have been moved to Stagnant by the EIP bot this month. And there are two proposals which are available in Review status moved from Draft. And one proposal in Review status moved from Stagnant. EIP 3651, which has been moved from Stagnant to Review, is a proposal that is being considered for inclusion for the Shanghai upgrade. So if you're looking for some information on Shanghai upgrade proposals, it's worth checking out. The proposal is open for review.

There was this new request by a GitHub user to start categorizing the EIP insight report, meaning they are looking for information on EIP Categorywise+, also include proposals which are not merged as Draft, meaning they have been proposed in that month, but they could not be merged maybe because they could not get proper attention, or something is missing, it is still being reviewed. But they want the information that this kind of proposal is still available in the repository. So I have updated the Report for the month of March. And now this report not only includes information about EIP proposed, EIP finalized, changed status, but it also contains information about potential EIPs as draft. So please check out the new EIP insight for March. The link is available in the agenda.

Moving on, the [meeting notes](https://docs.google.com/spreadsheets/d/1axM1KaKc-GCcoPbAnYTOhgLnxXsBVoO5XRjTN3CLnck/edit#gid=0) and action item for ECH. First of all, thanks to all the contributors who have been documenting meeting notes with us. It's been really helpful for people to follow who may not be able to follow the YouTube recording, and the moment they are traveling or anything, they just want to go through the text format of it. So these notes have been super helpful. However, we have received certain feedback, which I think is good in terms of improving to whatever is being delivered by the Ethereum Cat Herders so far. So I'm hoping to introduce some additional guidelines for the current contributors and future contributors. Of course, to document the notes, we already have a template which everyone is following. We just want to make sure that summary and action items are always there. There is this request of adding timestamp to notes. It has been observed that because of different accents, because of different people speaking, and people who are documenting notes, many times they are not that technical that they pick up the right word. Sometimes it is misspelled, or it's not the correct one, and it may change the meaning of the conversation. To avoid this kind of confusion, it is recommended that whoever is documenting notes, please add timestamps especially for any conversation of higher importance wherever we start a different topic. Or if there is a conversation related to something new and people are trying to make decisions, please add timestamps over there. And also, it is recommended to update the respective README file so we have this information listed on the readme page that the notes are available and it is easier to find it. The submission of notes are within three days. Generally, we provide the flexibility of submitting it within five days if notes are longer than expected. Otherwise, we highly recommend to submit the pull request within 72 hours of the meeting. And to be fair with every contributors, we are trying to enforce this thing like in absence of a pull request. At the end of the day four, we will try to open the bounty for other community contributors so that we can have the notes done before the next next meeting. And I'm hoping to update all these guidelines on ETH GitHub for people to follow. So far, for the past fortnight we have received the AllCoreDev meeting notes 134, EIPIP meeting 52, and I don't see the notes for the ECH meeting and the Seal meeting, which I'm hoping to get in a day or two. But going forward, we are trying to get these notes on time so we have everything ready before meetings, before the next meeting of that particular category. Any thoughts, feedback here to how we improve the process? These are just my thought process talking to a few other people on the ecosystem. Please feel free to share.

**Jim Bennett**
I think that's very helpful as someone doing notes. But you mentioned updating the README file. Is that something that you want the notetakers to do?

**Brent Allsop**
That's what I do, Jim, you get me the notes and then I do my link it all in and update. So that's taken care of.

**Jim Bennett**
Oh, okay. Great.

**Brent Allsop**
Also, it helps, um, at the beginning of the meeting, if everyone talks about whose turn it is to take notes for that meeting. And Jim and I are doing notes for this meeting, but it just helps to make sure it's not falling through the cracks and stuff like that.

**Pooja Ranjan**   
Absolutely. That is super helpful. Usually people try to take the recording and do the notes, other than EIPIP and ECH meetings. The other protocol level meetings are done by a note taker which are not there in the meeting. But yes, I try to mention it in the notes channel, and I hope that is helpful, but thanks for the suggestion here, Brent.

## 4. [ Discuss and close the ECH GitHub Issues/PRs](https://youtu.be/xNNw-CIrXZg?t=1779)
Alright, so people can check out the available notes and we hope to get all of them on time. The next item listed on the agenda is Discuss ECH PM and funding issues. I think on PM side we are all good, and on funding sides, I see only two new issues or one is just a swap. So only one - we are good there. We hope to address whatever is open by the end of this month.

**Pooja Ranjan**   
30:07
All right, we are at the last item of the meeting review the outstanding action items from the previous meeting. Unfortunately, I do not see the notes up here. But I'm assuming we may have covered most of it. If there is anything left out, we will try to add it in the next meeting and check out where we do then, for whatever action items are listed over there. Anything else from anyone they would like to bring today?

**Brent Allsop**
Nice short meeting.

**Pooja Ranjan**    
30:46
That's right. I see a comment in the chat about generating NFT on EIPs. I am not sure if I have the right answer for you right now here. There are a few proposals that support NFTs. There are few EIPs, you can check it out on the ERC category. Let me share the link to the website. Yes, you might want to check it out over there, but I am not sure if he ERCs are deployed on any specific proposal. My general understanding is it's an application layer, and you have to deploy in tag for that you might want to use EIP is of your preferences of ERC category what proposal number it would be. So for NFTs there are multiple proposals. The general one is EIP 721, which is a non fungible token standard that is basically used to deploy any kind of NFT and depending upon your choice, your preferences, there are multiple standards available. I think it's basically on individual's choice. However, there are a standard for royalties as well. I believe having a conversation with author Blaine Melania - that's right, EIP 2981: NFT royalty standards. So please check out different NFT related proposals, I have shared the link in the chat that is eips.ethereum.org/erc. There you can find the list of all Final proposals which are there in the ERC category which can be used to work on a project related to NFT. I hope this helps. William Schwab is not here today. He is also engaged in NFT related working group. So if if you have any question you might want to leave it in general channel of Ethereum Cat Herders, just call me. People may be able to respond back to you.

Any final questions? Comment from anyone? Well, this was a short call. But I'm encouraging people to add more items to the agenda if they would like to bring it up for the next meeting or if they want us to discuss in general anything related to Ethereum network upgrade, Ethereum Improvement Proposal, or Ethereum Process Improvement. Ethereum Cat Herders are trying to help in every direction. So feel free to reach us on Cat Herders Discord or in the Ethereum Cat Herders GitHub repository, where you can drop it as a comment and we will try to take it up in the next meeting. Well, thank you so much, everyone, for joining us today.

The next meeting is planned on April 12 at 1500 UTC. See you around. Have a good one everyone. Thanks, everyone.

# Attendees

* Brent Allsop
* George Hervey
* Jim Bennett
* Jose Alfonso
* Pooja Ranjan (Host)
* Pradhumna Pancholi
* Shubhangi Gokhale



# Date for Next Meeting: April 12 at 1500 UTC

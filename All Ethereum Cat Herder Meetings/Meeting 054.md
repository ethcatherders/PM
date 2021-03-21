# ECH Meeting 54 Notes
## Meeting Date/Time: Tuesday 16 March at 15:00 UTC
### Meeting Duration: 0.5 hour
### [GitHub Agenda Page](https://github.com/ethereum-cat-herders/PM/issues/165)
### [Audio/Video of the meeting](https://www.youtube.com/watch?v=CYX0BzZKPH0)
### Moderator: Pooja Ranjan
### Notes: Jim Bennett

----
## DECISION ITEMS

**DECISION 54.1**: Proceeed toward closing issues 103 and 163.[see 9:05](https://youtu.be/CYX0BzZKPH0?t=545)

**DECISION 54.2**: Put an item on the next meeting agenda to discuss using a yield-bearing instrument, either Aave or Compound, to hold fundings. [see 17:50](https://youtu.be/CYX0BzZKPH0?t=1070)

**DECISION 28.3**: Discuss separating ERCs from the EIP repo in the next call. [see 39:53](https://youtu.be/fKQVb-s0Tzs?t=1959)
----
****Pooja Ranjan****
Welcome to EIPIP meeting 28. I'm **Pooja Ranjan**.

## AGENDA

## 3. [Events and community meetings](https://youtu.be/CYX0BzZKPH0?t=8)

**Pooja Ranjan**
Welcome to Ethereum Cat Herders Meeting 54. This is Pooja Ranjan. And the first topic that we are going to discuss is [events and community meetings](https://youtu.be/CYX0BzZKPH0?t=8). Last week we had an announcement for Berlin upgrade, and it is active on Ropsten testnet. I think it's going to be on Goerli in a day or two, maybe tomorrow. So Ethereum Cat Herders [published a blog listing all the proposals which are going into Berlin upgrade](https://medium.com/ethereum-cat-herders/the-berlin-upgrade-overview-2f7ad710eb80). The post is available on [Ethereum Cat Herders Medium](https://medium.com/ethereum-cat-herders). Quick update related to one of the clients that is Besu. Besu client experienced some issue, and they reported a bug for that. They have made another release of their client that is version 21.1.2. We have updated Ethereum Cat Herders blog with that recent version of client. So if you are running any Besu client node, please go ahead and update that. It has fixed the bug. And that is now synced with the upcoming testnet and the mainnet upgrade.

Talking about that, we are planning to have a Berlin upgrade community call. We had arranged a community call for earlier meetings. So I was wondering if we can have something similar for Berlin as well. And I'm curious to know your thoughts on any format that people are interested in or maybe a suggestion on any timeline for this call. And this is, again, a proposal for Berlin, that we can maybe invite EIP authors whose proposal is going in the upgrade, maybe someone from the client team, EIP editors, to have an engaging conversation ongoing from the beginning of the call, or maybe until after the deployment. Or if we plan to have this meeting on the same day and time when it will be mainnet deployed. Otherwise, we can have this meeting maybe a week earlier. Do people have any specific thoughts on that?

**William Schwab**
No specific thoughts. Sounds good.

**Shane Lightowler**
I agree. It would be great to get those sort of standardized for any network upgrade so that people know that's coming.

**Pooja Ranjan**
Okay. Yeah. So I would be obviously getting involved in organizing this meeting. But if anyone from the group is interested, feel free to DM me. We can just get together and brainstorm how to go about that. And, yes, I think it is also very close. The mainnet is expected on April 14, and today is already March 16. So we have less than 30 days time. So we'll expedite the process or whatever we are planning to do. I'll share some updates very soon.

## 4. [Meeting notes](https://youtu.be/CYX0BzZKPH0?t=204)
Our next item is meeting notes. Again, a reminder about the timeline. So I'd encourage people to submit it before the timeline of three to five days, or give us a heads up so that it can be open for other available participants to pick up and submit the meeting notes as soon as possible. And one more point I wanted to mention. I was going through meeting notes from the last AllCoreDev meeting that was submitted by Shane. I found a section - the summary section was  interesting with adding timestamps so people can refer to the major decision taken. So for all other note-documenting people, it would be great if we can follow the same format.

**Shane Lightowler**
Oh, that definitely wasn't my innovation. I'd copied that from an older notes.

**Pooja Ranjan**
Oh, that's good. So if it's already been followed, then it is really super cool. I like the format adding it to there, and it was good.

**Shane Lightowler**
It was one of Abhishek's.

**Pooja Ranjan**
Oh okay. So generally we try to get people here and give a summary of notes. I think out of three we have just one person available. So would you like to go ahead and just summarize the meeting notes, Shane, because I don't see Brent here on the call today. Sorry.

**Shane Lightowler**
The one that I did since the last meeting was the previous AllCoreDevs, where the discussion clearly was around Berlin, and the removal of the EIP that was eventually removed. I forget the number off the top of my head - 2315 perhaps. And then discussion on London and the inclusion of 1559, which was obviously significant.

**Pooja Ranjan**
Right. And the next meeting is planned this Friday. And we hope to see more discussion on the London upgrades proposal. Okay, and we have an EIPIP meeting available in the GitHub repository. And we are still waiting on ETH 2.0 implementers meeting. Okay, that would be fine.

## 5. [Peep an EIP](https://youtu.be/CYX0BzZKPH0?t=204)
Moving on, the next item is [Peep an EIP](https://www.youtube.com/playlist?list=PL4cwHXAawZxqu0PKKyMzG_3BJV_xZTi1F). In the past two weeks, we did three proposals. The first one was [EIP-2315 - simple subroutine for the EVM with Greg](https://youtu.be/c3Zo8vPwtk0). The other one is [EIP-3085: Wallet Add Ethereum Chain RPC Method with Eric Marks](https://youtu.be/nOIl2w33sGU). And the latest one is [EIP-3074: Native Sponsored Transactions with Sam Wilson](https://youtu.be/4A3N8dvdaSk). This proposal, EIP-3074, is also proposed for London. It has now been renamed as [AUTH and AUTHCALL opcodes](https://www.youtube.com/watch?v=4A3N8dvdaSk).

These are all interesting proposals. I would highly encourage people to go ahead and watch. And tomorrow we have a Peep an EIP meeting scheduled for EIP 1474. That is remote procedure call specification. That's mostly for JSON RPC APIs. And many people have requested for this proposal to be explained by the author. So we have invited the author as well as one of the implementers to talk about this proposal. Another upcoming proposal is for ENS. We have invited Nick Johnson to talk about EIP 137. That is the specification of ENS domain. And the other one is EIP 2544. That is relatively a new one that is about ENS Wildcard Resolution. Most of the information related to Peep an EIP are provided in Ethereum Cat Herders Discord. So if anyone is interested to join the meeting, if they have questions, or they want to talk to or interact with the author and want to understand the proposal better, feel free to DM me, and we can send the invite. Otherwise, most of the information are generally available in that ECH Discord section.

## 6. [Discuss and close the ECH GitHub Issues/PRs](https://youtu.be/CYX0BzZKPH0?t=511)
Okay, so that's mostly about the agenda. Now we have a ECH GitHub issues and PRs. Before that, if anyone has anything else that they would like to bring up. Otherwise, we can go ahead and discuss about the open issues. I see two that we can talk about. The one that we had earlier, we had about the following up nodes who are upgrading to the latest version of the clients to be in sync by the time of upgrade. I'm talking about [Issue number 103: Add an option to Ethernodes that accounts for "In process"](https://github.com/ethereum-cat-herders/PM/issues/103). So Ethernodes have recently added the link for tracking the Berlin upgrade. I'm curious if people want something more to be added here, or if that is fine and we can go ahead and close this issue. So if we feel that we would like to have something more added here, we can probably ask these people. Otherwise, we can proceed towards closure of this issue.

One more - [Issue number 163. That was for notes for Ethereum 1559 Community Call](https://github.com/ethereum-cat-herders/PM/issues/163). I think I have added - yes, I did add the PR. So generally, what I'm trying to do here is kind of create a practice. If we are opening a note which could not be done earlier by the scheduled calendar or something comes up, which did not learn it earlier, we'll open the issue and provide the details there. Once you are done submitting the notes, please go ahead and add a comment mentioning that the notes have been documented and here are the link for the PRs if you have already created a funding request. So I think after clearing up the funds, we can close this issue as well. Those were two on the PM side. On the funding side, I believe I have created a request for all of the funding except for Shane. Shane, I have requested you to add maybe a screenshot or a reference link to just show the rate on that particular date and what is the amount that is needed.
2
**Shane Lightowler**
11:20
Yeah, no problem. I'll probably change my request to DAI. But But yes, I'll attend to that today.

**Pooja Ranjan**
Okay, so once it is done, I can like a create a transaction for you as well. Other than that, I believe one more approval is required for rest of the requesters. And we hope to get it done very soon.

Okay, before I go ahead with the last item on the agenda that is reviewing outstanding action items, I just want to quickly talk about EIP bot future ideas. I know Alita hasn't joined today. But if people are interested to know more about the bot, I think she had made quite good progress and also created a pull request in the EIPs GitHub, I have followed some conversation that suggests that there is some interaction going on and iteration on the bot. If people are interested, they can refer to [pull request number 3351](https://github.com/ethereum/EIPs/pull/3351) to follow the bot progress, and if any suggestion is there for her.

## 7. [Review of outstanding action items from previous ECH meetings](https://youtu.be/CYX0BzZKPH0?t=765)

**Pooja Ranjan**
And I think the last item on the agenda today is a review of outstanding action items from previous ECH meetings.

# Interactive demo of the new site to be shown in next meeting.
Unfortunately, Michael from the Invicta team could not join us today. So maybe we hope to get some updates in between this and the next call maybe on the ECH Discord. Or if not, then definitely something would be coming up in the next meeting. That's my hope. In the last meeting, he shared some designs and a logo for Ethereum Cat Herders new website that was very well accepted by the group. So I hope to see the demo soon.

**Edson Ayllon**
Yeah. So something I wanted to talk about was a little more than a year ago, we're thinking of using a DAI savings rate. I know we use Gnosis and no setted Gnosis safe apps. So both Aave and Compound are integrated into Gnosis for the multisig. Is that still something we want to do? Put our DAI into a savings account?

**William Schwab**
Interesting. I know at least before, I was a little bit against moving funds into any kind of yield-bearing instrument. At this point being the device had a little bit of time to be around. I guess we would I'd want at least is kind of a clear understanding of what the risk level for any of them are. You said compounded and who else?

**Edson Ayllon**
Aave.

**William Schwab**
Aave's super audited, I know. I wouldn't want to make a fast decision on that, especially in kind of a low attendance meeting like this, but I'll put it this way, I'd definitely be more willing to hear it out than I was in the past. Anyone else have any thoughts?

**Shane Lightowler**
Are they able to be split across both? Or does it have to be one or the other?

**Edson Ayllon**
Yeah, I mean, you could split it. You'd be getting more in gas fees that way, but you could definitely split it.

**Pooja Ranjan**
I'll be happy to bring it up with the multisig people. But just for information as of now. Yeah, I think we have like quite decent amount in DAI and USAC. But if we go in the direction of putting it in savings, so we can have more Ether...

**William Schwab**
I am thinking it through. I think one of the things that this would need is a very clear proposal on how the system would work. Gas prices are a concern being that there are constant payouts being made out of it. So I definitely do understand the idea that usually we have excess funding that we should be able to get some kind of return on in the meantime, but then the question is it can't be that we'd have to withdraw from it for every notes payout, for instance. So we have to have a clear plan of what's being invested, what percentage is being invested, how often when it gets pulled out, etc. I think a clear proposal there on what the system would be and then kind of figuring out how much we'd come out with we offset it with gas costs, which are impossible to predict. Wwe could discuss exactly how to look at gas prices, I suppose. I think that would probably go a long ways in making it easier to go for something like that.

**Edson Ayllon**
Yeah, obviously wouldn't be 100%. Because then you'd be withdrawing from those platforms every other week.

**William Schwab**
Or more often, because four meetings every two weeks, right?

**Edson Ayllon**
Yeah. So I think we should have at least three months of meeting notes in our normal wallet.

**William Schwab**
And then we'll add every three months for a three month period.

**Edson Ayllon**
Yeah, a withdrawal every three months worth.

**William Schwab**
I kinda want to kick the can down the road on this, if that's okay. Maybe bring it up in the next meeting? Is that okay?

**Pooja Ranjan**
Sure. Sounds good. Just for information, so far, we have not been keeping this gas fees under consideration, because Hudson and Tim have been sponsoring gas.

**William Schwab**
I didn't know that. That's super kind of them.

**Pooja Ranjan**
But from the last meeting, we we have started keeping track of the gas fees. That is added as an additional column in the ECH multisig so people can go refer if they want to. And it was brought up  if this piece is over 50 or $100, or maybe a reasonable amount, then somebody can ask for a refund or something like that. So I think, as William was suggesting, if we can have a proper proposal on that and getting more clarity, we'll have more discussion on that. It will be helpful for the group to decide as it should go in that direction. Maybe I'll bring it up again in the next meeting.

Continue with the notes. We were on actions from the previous meeting.
# 53.2 suggests blog about Berlin to be posted.
It is out and there is a minor correction as I mentioned in the beginning of the call. For Besu client, we have shared the latest version of client if you're running Besu client, please go ahead and update.

# EIP 969 needs a champion.
Yeah, I brought it up in the Discord channel. And I believe there is a proposal up now. Let me quickly look into the proposal number. It's [EIP 3372](https://ethereum-magicians.org/t/eip-3372-minor-modifications-to-break-current-asic-miners-bad-actors-who-threaten-ethereum/5759). They have put it into draft, apply minor modification to the ETH hash algorithm to break current ASIC implementation that is basically EIP 969 resubmission. So if people are interested, they can look into that proposal.

# Have a call with EIP editors answering questions about becoming an EIP editor.
We have this meeting...

**William Schwab**
Sorry, going back to 969. Is there a particular reason why we would push a champion for 969 right now?

**Pooja Ranjan**
Actually, it's not that we are pushing the champion. These people were saying that we should have this 969 included in an upcoming upgrade. So my suggestion was, if you want to get included in any of the upgrades, you may have to follow the formal process of a proposal. And for that, let us know if you have a formal proposal. And we'll help you out with the creation of that and maybe letting you know what is the process.

**William Schwab**
So it's not that we recommend it or are trying to get it included in London or some other hard fork.

**Pooja Ranjan**
No, it's not like we are recommending. It's just that we did mention it in the meeting, and after that in the Discord channel, that if you want this to be proposed, propose it in a formal way. And the formal way is to go ahead with an EIP.

**Pedro Rivera**
What does a champion mean in this context?

**Pooja Ranjan**
So for a proposal, there is an author who actually documents the idea what he or she wants to propose. And we believe that it is improvement for the Ethereum main chain, but for some reason, if the original author is not able to pursue that proposal, if somebody else wants to, then they can champion for the proposal.

**William Schwab**
So in other words, just someone to take it on to AllCoreDevs and try to get approval for it. You know, trying to convince client devs to incorporate it.

**Pooja Ranjan**
Okay, so for our action item 53.4 - EIP editors aspirants question answer session, we had invited all the aspirants to the EIPIP meeting. If someone could not join the last one and they still have some questions, feel free to join in upcoming meeting generally the information about EIPIP meeting is shared in the tedium Cat Herders discards general channel. So follow the channel or maybe the EAP GitHub repository.

The last action item here is Brent to reach out to Hudson and about EIPs.ethereum.org. I do not have much update. But as I heard from Brent in the last EIPIP meeting, he is still working on having a canonical resource for EIPs. We'll have to wait for him and maybe in the next meeting to provide the update. Because this meeting is the first meeting after the time shift, some of the people could not join.

**Jim Bennett**
Brent actually had another engagement and asked me to come, but he is still working on that.

**Pooja Ranjan**
Good. Thank you. Thank you for that update. So that's all I believe we had from the items to be discussed today. If people have any particular thought about having the meeting time the same, 1500 UTC, even after the change of the daylight savings, I'm fine with that. But if they have some inconvenience or they would like to propose some other time, we can definitely consider that. Do let us know.

**William Schwab**
The time's good for me, but I'm here, so...

**Pooja Ranjan**
Right. Okay, so I'll check with the missing participants here. Like, what's their thought and then maybe we'll think about it if needed. If it is just one time and they are fine with adjusting other meetings, that will be very good for us. We'll have to keep our 1500 UTC. Thank you for showing up, everyone. Have a good day/evening. See you all in two weeks. Thank you.

# Attendees

* Edson Ayllon
* Jim Bennett
* Pedro Rivera
* Pooja Ranjan (Host)
* Shane Lightowler
* William Schwab



# Date for Next Meeting: March 30 at 1500 UTC

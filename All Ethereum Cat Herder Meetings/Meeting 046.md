# Ethereum Cat Herders Meeting 46 Notes

### Meeting Date/Time: Tuesday, Nov 24, 2020 15:00 UTC

### Meeting Duration: 20 min.

### [GitHub Agenda](https://github.com/ethereum-cat-herders/PM/issues/146)

### [Video of the meeting](https://youtu.be/ODL29s37_t4)

### Moderator: Hudson Jameson

### Notes: Alita Moore

---

# **Summary:**

## Actions

| Action Item | Description                                                              |
| ----------- | ------------------------------------------------------------------------ |
| **46.1.1**  | Hudson to merge in outstanding meeting PRs and close issues              |
| **46.1.2**  | Hudson to investigate converting PSI to DIE / Multi-sig problem          |
| **46.1.3**  | Hudson and Edson to re-approach the ETH DAO staking, follow up with Lane |

## Decisions

| Decision Item | Description                                                                                       |
| ------------- | ------------------------------------------------------------------------------------------------- |
| **46.2.1**    | ECH team agrees to pursuing hte CLR fund                                                          |
| **46.2.2**    | If the eth magicians don't / can't do moloch funding for EIP Editors then ECH could do a proposal |

## Helpful Links

| Link Item  | Description                                                        |
| ---------- | ------------------------------------------------------------------ |
| **46.3.1** | [ECH Website private repo](https://github.com/alita-moore/ech-web) |

---

# 1. ETH2 Phase 0 genesis

Video | [0:00](https://youtu.be/ODL29s37_t4?t=3)

**Hudson** - Hi this is hudson and i i am running the meeting for ethereum cat herders number 46. the first agenda item is the eth2 phase zero uh genesis starting um Pooja that one you put on there i think so what did you want to talk about

**Pooja** - uh we just wanted to provide a basic information about uh this uh phase zero genesis that we would be expecting on december 1st so minimum deposit has been acquired yesterday um it seemed a bit of ambitious target to achieve but uh it happened and we have like over 150k then that was required to uh trigger this phase zero genesis so that was the information and if anybody else has to add something on it

**Hudson** - is your recommendation to release any kind of post on this or is this just to like post on twitter or what

**Pooja** - i mean if people are interested in having a post on that that would be fine i saw a tweet storm from you that was like prior to this that was also good and we would be adding it in the newsletter that is going to be released today okay perfect

**Hudson** - i think there's a lot of news going around about it so we don't need to put another article a full article out or anything unless anyone really wants to.

# 2. Participate in CLR.fund

Video | [1:39](https://youtu.be/ODL29s37_t4?t=99)

**Hudson** - great okay um the next item participation in the clr fund so uh oren from clr.fund reached out to me and pooja and talked about getting the ethereum cat herders involved in this it's kind of like a i think you might need to explain it more or anyone on the call who can explain it better but i think it's like a git coin grants but it's um has private voting using macy which is a uh a zk snark uh private voting mechanism that barry white had and his team have developed so you basically can participate in uh and like transparent funding of projects without revealing your vote and they've been got they've been given some funding lately and they were looking for projects to public goods projects and like stuff like that to add on to their platform so um we were going to see what everyone else felt about that but we've already started the process just because it's a longer process to get bootstrapped on there um because i anticipate no one's gonna have a problem with us getting more money for free but um if so speak up if you think that's a bad idea or anyone has any opinions either way on it

**Pooja** - just to add a couple of more points here so yes as i had some mentioned that it is very similar to gitcoin grants so uh it would be like matching pool by contributing to groups um like this is live for now like the cat headers have a similar wallet up there we are going to uh release the address of it in our newsletter but if anybody has strong opinion that we should not be participating in this thing um we are open to suggestions

**Hudson** - cool anybody have any uh opinions or any suggestions on it if not we can move on to the next item i i didn't think this would have that much feedback

**Edson** - i think it's a good idea

46.2.1 | Video | [3:00](https://youtu.be/ODL29s37_t4?t=180)

    ECH team agrees to pursuing the CLR fund

# 3. ECH Website

Video | [3:40](https://youtu.be/ODL29s37_t4?t=220)

**Hudson** - great okay the next item up is the ech website um i think that would normally be alita i don't know if uh pooja you have an update otherwise no i don't have i was expecting uh something new if if at all is there so we saw some progress from there i have seen a couple of comments from there uh i'm not sure i'm not that much into technical maybe william or hudson if you can look into that and respond to that

**Hudson** - i've already reached out to Alita a few weeks ago and said if you need anything while this is happening as far as github permissions or whatever just reach out and um so that's that's where we're at on that i think

**Pooja** - great so we'll wait for the next meeting when she comes up with an update on it

46.3.1 | [ECH Website private repo](https://github.com/alita-moore/ech-web)

**William** - i know that she had her own repo that she was working from and i did just find it give me one sec looks like there hasn't been any action there for the last couple weeks but i'll put it in chat okay

# 4. Meeting notes update

Video | [4:40](https://youtu.be/ODL29s37_t4?t=280)

**Hudson** - thanks william um okay meeting notes updates um who wants to go over that one

**Pooja** - i can talk about the break room breakout room meeting but before that if anybody else has to mention anything about any other meeting

**William** - i could summarize the last eth2 if you want but i'd need a couple of minutes to review i forgot to do it beforehand

**Pooja** - yeah sure

46.1.1 | Video | [5:28](https://youtu.be/ODL29s37_t4?t=328)

    Hudson to merge in outstanding meeting PRs and close issues

**Hudson** - there's a lot of pull requests that are open and uh the all core dev uh repo i need to i need to merge these i'll do that right now

**Pooja** - so william you want me to go first or you

**William** - yeah i'd prefer if you go first that way i'm able to like just sort of review quickly

## Breakout room on eip2972

**Pooja** - okay sure so the last breakout room meeting uh was conducted uh um a week back this meeting was arranged to continue the discussion from the previous all core dev meeting on the transaction format specifics with respect to three eips eip2930 optional access list eip2972 wrapped legacy transaction eip2718 typed transaction envelope the questions that were discussed mostly uh were two the number one should legacy transaction be wrapped does the complexity of the client go down by disallowing the unwrap of a legacy transaction the group mostly seemed to be in favor of that eip2972 was mostly supported by people present there although axic was not 100 sure but he said that he would probably go with it the number two question was how do we format the new transaction type it is uh is it the right time to introduce the ssz there were enough support and not uh so strong opposition to use ssz from people who attended the meeting but uh there were some concerns and the group wanted to hear more concerns using ssz for that the next steps decided were like piper medium will reach out to client or devs on discord async to check if they are willing to use ssz implementation from the f2 clients or if they would like to go ahead with the massive amount of testing on their own client teams present get and besu seems to be fine with using ssd open ethereum we're not sure they said that they will confirm later and trinity was of course supporting the proposal uh two points that were like to be discussed in future meetings or maybe in async where potential delays if ssz is chosen to move ahead with and the number two was like figuring out whether or not ethereum clients are okay to have some um you know delay if we are choosing that so yeah that's all about breakout room making five uh the meeting video is available in the github repo and i'm gonna add this summary in the newsletter as well as in that repo

**Hudson** - okay thanks puja william

## Eth 2

**William** yeah um so there was a lot of little stuff that happened in the last eth two meetings so i'm not going to get stuck so much in the weeds here so i'm going to try and summarize this into the major sort of categories um there was some test net talk uh madasha is probably going to be sunsetted uh it could be that there will still be some developers on it who are mainly testing out edge cases and things like that but um the sort of official supported test net is moving over to piermont which has launched since that uh since that call uh most of the client updates had specifically to do with just getting ready for the imminent launch of the beacon chain and congratulations ethereum for hitting the the threshold today um a little bit of talk with the spec ah there was someone who put out a pdf testing performance of the different uh of the major different clients i'll put that in chat but wait a second oh i won't wrong link uh i'll put that in chat momentarily uh i i suspect that that's going to change a lot though one thing that did get reiterated a bunch of times is that there probably will be additional uh releases of all the major clients in the run-up to the actual beacon chain launch next week um uh uh there's talk about uncoupling certain things that were sort of coupled together in the post phase zero um eth2 rollout phase to look at light clients um the merger of f1 eth1 and eth2 data and um and data shards as separate items as opposed to coming in some kind of sequential order of those three light clients seem to be the most trivial and should be able to be rolled out fairly trivially perhaps even in like another half year or so um and i think that is really the major stuff yeah

# 5. Community Call for Account Abstraction

Video | [10:34](https://youtu.be/ODL29s37_t4?t=634)

**Hudson** - great anybody else have notes they want to go over okay in that case we can move on to the number five item community call for account abstraction

**Pooja** - so yeah last week um the cat header organized the first community call for eip2938 account abstraction uh thanks to annette from the fellowship of ethereum magician to help with that uh it was focused mainly on the q and a session like mostly related to account abstraction but we get to know a little bit about roll-ups as well thanks to hudson for moderating it and we hope to organize more such events in near future if anyone from the group has idea about which proposal we should organize next or is interested in volunteering uh please reach out and we can also create a discord channel for this discussion if there is any need for this

# 6. Peep an EIP

Video | [11:30](https://youtu.be/ODL29s37_t4?t=690)

**Hudson** - okay awesome um all right what's next um oh peep an EIP

**Pooja** - sorry yeah so for peep and EIP we had two uh video released since the last meeting one is for eip 2938 account abstraction with um sam wilson and and scott dietrich it was a very good session the proposal is explained but unfortunately we could not take uh all the questions that were there for this proposal so we may be having a part two of peep an EIP for this particular proposal the next was a eip2982 a serenity phase zero with danny ryan that was the first informational eip on the show and we discussed a lot about the process and how we are planning to uh move ahead with the change of statuses as per the latest change that has been introduced in eip1 so this is also a very good watch for people who haven't watched it before please go ahead and watch peep an eip for both of these proposals

# 7. Cat Herders Funding - Moloch DAO & ESP

Video | [12:37](https://youtu.be/ODL29s37_t4?t=757)

**Hudson** - awesome that sounds great um the next item is cat herders funding from moloch down esp today i well or as soon as y'all gets back to me i'm submitting the application for molok dao funding um uh for i think it's for a year uh no is it for a year worth of funding for the uh six months of yeah herder and chief funding so um that is happening soon and then with esp i had like a brief discussion with um an esp person about cat herders and we were going to wait till after the molok dao stuff to reevaluate what they can do to help um so we'll just keep everyone updated on that

**Pooja** - i may have one more update so in one of the uh previous eipip meeting um like it was proposed to have you know funding for eip editors so i was in touch with one of the moloch people and were discussing about that they seem that if we can like uh propose that in our mgp itself like if the plan is in place we know what funding is needed and how it is going to be distributed and if we can come up with that probably cat headers could be people who can request for funding from moloch for this purpose as well

**Hudson** - so i think we could the one thing that i'm hesitant about is us asking for too much funding for too many different things and that's why for eip editors having the fellowship of ethereum magicians get funding and organize the dispersal for the eip editors seems like a better fit because magicians deals with the eips

**Pooja** - yeah yeah i get that part that's all that's cool i mean uh that was just a thought so i wanted to share it

46.2.2 | Video | [14:44](https://youtu.be/ODL29s37_t4?t=884)

    If the eth magicians don't / can't do moloch funding for EIP Editors then ECH could do a proposal

**Hudson** - sure um and if and if like we can definitely if the magicians can't handle it we can take up doing another proposal or something like that um for molech dow or what or clr fund or whatever else um and see what's what can happen there sounds

# 8. Discuss and Close ECH Github Issues / PRs

Video | [15:03](https://youtu.be/ODL29s37_t4?t=903)

46.1.2 | Video | [15:03](https://youtu.be/ODL29s37_t4?t=903)

    Hudson to investigate converting PSI to DIE / Multi-sig problem

**Hudson** - next up um what do we have um discuss and close ech github issues and pr's um converting psi to die i still haven't done anything with that sorry everyone um because i got an error but i that's the thing where i get an error when i try to transfer the last of our ether out of our old multi-sig so i'll i'll work on that um and then the rest of them are the ones that are just always there i don't think there's any updates

**Pooja** - so this i mean like the last one staking in the ETH DAO is it something that we can do anything about it or we would like to just go ahead and close it i'm not sure of that part

46.1.3 | Video | [15:53](https://youtu.be/ODL29s37_t4?t=952)

    Hudson and Edson to re-approach the ETH DAO staking, follow up with Lane

**Hudson** - um let me see we we talked to lane about it and then we kind of just put it on hold i think i forgot why i think his gas prices were high so this would be good to re-approach again me and edson were talking to lane about it so this is something we should get through soon um so yeah i'll bring this back up with them sure all right i put that on my to-do's and then i also i'm gonna put the um uh figuring out multi-sig problem great okay um so that's all is that all the issues we want to talk about from the pm repo

**Pooja** - so now that berlin is approaching would it be the right time to address an issue number 103 or like reaching out to ether nodes about in-process thing

**Hudson** - it's um oh i put this is done wait it's not done wait until berlin is closer to s peter from ether nodes oh okay i see this is something that i think once they launch the site again we should ask about because they're not gonna do anything before then

**Pooja** - uh maybe i mean i have seen uh people in a discord cat herders discord so maybe i would like to mention this issue to just to bring it to their attention and yeah how does that sound

**Hudson** - yeah that sounds good okay

**Pooja** - and about the besu hotfix let me check with tim on that so that we can close it too

**Hudson** - yeah that sounds good all right and then that covers all of them for that the issues in the ethereum cat herders funding repo um i think we did transactions for these recently didn't we yeah i think so too other than the one that is submitted two days ago i think all of them should have been done like people if you can check and confirm the funds are received you may go ahead and close issues

**Hudson** - yeah i can i can do that today so i'm going to say look at multisig and close issues because i think tim approved of a lot of them

**Pooja** - right so we have created and tim has approved only for william that has been open two days back is should not be done but other than that all of them should be

**Hudson** - okay i'll go through and clear those out after the meeting um let's see yeah it looks like they're all successful okay um and

# 9. Outstanding Action Items from Meeting 45

Video | [18:45](https://youtu.be/ODL29s37_t4?t=1125)

**Hudson** - then the next one up is outstanding action items from meeting 45 um action item 45.1 has hold a community called account abstraction we've done that 45.2 is Pooja to create a summary of everything the cat herders have done in 2020. to be completed by the end of november or december

**Pooja** - so yeah i'm working on it and yeah i'll update soon

**Hudson** - reach out to inactive cat herder members and get them to participate possibly means an online job fair that's forty five point three um

**William** - i was supposed to do some of that and i totally forgot

**Hudson** - no problem i don't know if doing it over the holidays is gonna get us the best response and it might be like new year new excitement kind of a thing to do it in january but that's just my inclination

**William** - that's a really cool idea i could i could get on board with that

**Hudson** - cool okay uh that's all the action items um and that is all the agenda items do we have anything else that anyone wants to discuss or add to the agenda

**William** - if we're going this fast i'll ask if anybody's interested in ETH cc talk

**Hudson** - oh yeah um like it's in person right

**William** - it is currently supposed to be in person

**Hudson** - i won't be going unless there's miraculous vaccines that come to my door by then february

**William** - yeah i'm sort of on the fence like it's like trying to that that is basically the whole thing is like trying to project what the state of corona virus is is going to be then and how effective and widespread the vaccines are going to be by then also it's a difficult calculation to make

**Pooja** - if i remember correctly uh that last year it was you william who participated there i mean like you addressed a workshop there right

**William** - tim, helena, and myself

**Pooja** - yeah right right right yeah yeah so i mean like i mean i am for sure not going there not even with vaccines but uh if things get better and if you would be interested um make sense right yeah

**William** - i'll give it a thought

**Pooja** - yeah thanks for bringing this up

**Hudson** - uh anybody else have anything okay the next meeting is going to be december 8th 2020 at 1500 utc and uh thanks everybody for coming and have a great rest of your day

---

# Annex

## Attendees

- Hudson
- Pooja
- Edson
- William

## Next Meeting

December 8th 2020, 1500 utc

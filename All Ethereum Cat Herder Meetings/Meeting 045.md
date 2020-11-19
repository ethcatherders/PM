# Ethereum Cat Herders Meeting 45 Notes
## Meeting Date/Time: Tuesday 10 November at 15:00 UTC
### Meeting Duration: 45 minutes
### [GitHub Agenda Page](https://github.com/ethereum-cat-herders/PM/issues/144)
### [Audio/Video of the meeting](https://www.youtube.com/watch?v=-qK3wq0HjEE)
### Moderator: Hudson Jameson
### Notes: Jim Bennett

----
## DECISION ITEMS

**DECISION 45.1**: Look into ways to have people be able to go in and do pull requests and just markdown updates to the pages on the ECG website.

**DECISION 45.1**: Investigate creating a bounty for a web designer to redo the logo and get a color scheme ironed out.

## ACTION ITEMS
**ACTION 45.1**:  Hold a community call on Account Abstraction on November 20 at 9 AM EST

**ACTION 45.2**: Pooja to create a summary of everything the Cat Herders have done in 2020. Summary to be completed by end of November or December. 

**ACTION 45.3**: Reach out to inactive Cat Herders members and invite them to participate, possibly by means of a virtual online jobs fair.

## AGENDA
**Hudson Jameson**
Hello, everyone! This is Ethereum Cat Herder Meeting number 45.

# 1 [ECH Website](https://youtu.be/-qK3wq0HjEE?t=3)
The first item on the agenda is the Ethereum Cat Herder website. And I think that item is for Alita.

**Alita Moore**
Yeah, so I've been trying to upload the GIF that I shared. I could probably just upload to Discord. Basically, I'm working on fixing the websites, and the websites could use a bit of a renovation. So I just uploaded the current basics. I got the navigation down. You can go between different pages or whatever. The basics of the website, obviously. I have plans right now to continue with what I'm doing and just more or less copy the old website onto the new one, but in a more clean way. I think once I have the basic framework down, I'm thinking maybe we can start with good ideas. Maybe we want to render the markdown within the browser. Maybe we want to do whatever, because the sky's the limit, so it might be fun. It's underway. It's looking good. No idea how long it will take me to finish the website, but I think it looks a lot better than the main website.

**Pooja Ranjan**
Yeah. So I looked into that GIF image that you have created and sharing a link here. So that is about what we would like to see on the page. On high level, whatever you have assigned looks good. But if we can have different buttons for home network upgrade meeting, and this is the layout that I was just having in my mind. Curious to know what other people think about it. For this document, if they feel something should be added or removed, please feel free to do that. This is just high level. What I think would be good for community to know about, to just inform what Cat Herders are doing in general. Every time, we don't have to go and let them know, they can just visit the Cat Herders website, and they'll get all the relevant information that is related to Ethereum mainnet, like Ethereum 1.0 maybe 2.0, or any proposals that we are working or supporting in general.

**Alita Moore**
Yeah. That seems awesome. It all is totally achievable.

**Hudson Jameson**
I have a quick comment. I think something that I've seen that makes it really easy for these type of websites, where there's going to be updates from a variety of people, are having people be able to go in and do pull requests and just markdown updates to the pages. So just have markdown and then that get rendered HTML on the site. For examples of things that do that, I think Jade and Jekyl and Hugo do that. But I'm not sure if yours is just pure HTML or what it is so far.

**Alita Moore**
Do we just want to have like a back end or something?

**Hudson Jameson**
So in the past what I've done, and we can do it however, we can put it on something like Netlify or AWS, or whatever. I don't know if it's free anymore, but there's GitHub Pages that allow you to link up a repo to GitHub Pages, and then it just pushes the website out.

**Pooja Ranjan**
I think our present website is designed in that way. I just shared the link. So according to this, what we need to do is just change one file, index.md, for the contents, and anybody can make a pull request in this particular repository to reflect any changes on their website. Is that something that you were trying to say, HUdson?

**Hudson Jameson**
Yeah, yeah, that's exactly right. That's like it, or that's one example of what we could do. But I was just thinking, that's what I think we're doing so far, and it might be better to change it. I don't know yet. So I'll kind of defer to Alita on that.

**Alita Moore**
Yeah. I mean, it's definitely possible. We could do also is integrate GitHub within the website. I wonder if that'd be like signing with GitHub or whatever. I don't know. That would be painful. The thing is, I'm full stack. So if we want to do a simple back end that just saves the markdowns of the different pages. Or I guess GitHub does that, so...

**Hudson Jameson**
Yeah, and another one to look at maybe - ethereum.org is open source. And I'll paste the repo in here.

**Alita Moore**
But I actually did look at that. But the problem with ethereum.org is that they use something that's not React. I'm primarily comfortable with React. But I don't know if what they're doing is better or much easier than React. Have you ever programmed a website at all?

**Hudson Jameson**
Yes. And I have used React. It's been awhile, though. I use a super old version of React. So yeah, doing something like that would be be cool. I think that'd be fine.

**Alita Moore**
But what's the difference between React and whatever the websites doing?

**William Schwab**
I think they're using View, just for the record, ethereum.org.

**Hudson Jameson**
Oh, VJS?

**William Schwab**
I think so.  If we're just talking about a markdown rendering engine - this ethical reason that you were talking about server side, so that there could be something that could process the markdown?

**Alita Moore**
Yeah. So that way you could just upload stuff on to the website and edit it on the website. That would make life a lot easier for people.

**William Schwab**
[crosstalk - unclear](https://youtu.be/-qK3wq0HjEE?t=446) do that serverless. It wouldn't shock me. But I am just shooting in the dark there. I don't know that for a fact.

**Alita Moore**
Well, we could potentially have a universal PR client or something that interfaces with the website. I'll get to it, but I think that that would be a really ideal setup. So that way, you can just kind of manage stuff on the website.

**Hudson Jameson**
Yeah, that sounds good. And I'll look for a few things after this meeting to try to understand what I'm talking... No, okay. I was completely wrong. What I was thinking is Gatsby. Gatsby uses React and allows you to do the thing I'm talking about where you can just upload to GitHub. And then it has different plugins and things you can do to make it a little easier to build on. So you don't have to build a back end from scratch. It deploys it for you.

**Alita Moore**
Okay, that sounds really interesting. I do know that ethereum.org doesn't even have a back end, right? It's all integrated. I'm not really sure how that works, though.

**Hudson Jameson**
Yeah, well, they're using Netlify right now. Their server side stuff is launched through Netlify. I found the Gatsby site link and I pasted it there. And I'm also going to paste it in the website update communication channel in our Discord. So we can just continue the conversation there.

**Alita Moore**
Sounds good. And then, if Gatsby would be a lot easier to use to set this up, then there's no reason why I shouldn't use it.

**Hudson Jameson**
I'm guessing it'd be easier, but that's just a guess. But check it out. See if you understand what they are doing for it, because it is completely React-based. So that should be familiar to you.

**Alita Moore**
Okay, so it's like a package or...

**Hudson Jameson**
Yeah, it's like you launch it, and you get to put in plugins and different themes. If you want to make your own theme, that's cool, too. But it's a way to where you can do a command that renders the website for you out of markdown and whatever else you want to put in there.

**Alita Moore**
Oh, interesting. So are they associated with WordPress?

**Hudson Jameson**
I don't know.

**Alita Moore**
I'll look into it. I really appreciate that you pointed it out. So I primarily work on this on the weekend, by the way, I'm only putting in a few hours a week, because I'm also doing that stuff with the BLS-12 still. I'm also just putting a couple hours a week or whatever. So might take me a while to fully finish it.

**Hudson Jameson**
No problem.

**Brent Allsop**
Is the markdown all that stuff uses, is that completely different than WordPress markdown? That's the question I've had. Is the markdown at all compatible, or are those completely different markdown languages?
1
**Brent Allsop**
Markdown has different flavors. There's GitHub markdown, WordPress markdown, and other stuff like that that are very similar but have some syntax differences.

**Brent Allsop**
Okay, cool. Thanks.

**Hudson Jameson**
Cool. Is there anything else on that one?

**Alita Moore**
No, I think that's it. Oh, actually, yeah, there is one more thing. We were considering, once the website's more functional and we get a better idea of what we're going to use it for, I'm thinking that we should consider getting funding for a designer so that we can get a bit of a logo redone. Plus a color scheme sort of ironed out. I could create a temporary color scheme.

**Hudson Jameson**
A professional designer would be nice.

**Alita Moore**
Yeah, I think that'd be good. I think it would be good for getting people onboarded with the Ethereum Cat Herders as well. Cool.

**Pooja Ranjan**
Yeah. So on that, as I mentioned the other day in the call with the website, people are working on it. So we may be looking into that if we need, we can go ahead with creating some kind of bounty for that, or maybe if you have any suggestions or recommendations for people here. And about the funding part, yes, that that is being considered. We are trying to get that added in the Moloch requests that we will be putting. So yes, that is there in my mind, but if anybody has any other thoughts on it.

**Hudson Jameson**
Cool. That's a good next step is to get funding. All right, anything else on that agenda item?

# 2 [Community call for Account Abstraction](https://youtu.be/-qK3wq0HjEE?t=805)

Okay, next up is community call for Account Abstraction. That's Pooja.

**Pooja Ranjan**
Yeah. So we are already doing these Peep an EIP sessions for different proposals that are coming up in Ethereum, maybe for the Berlin upgrade or maybe for the future upgrade or in general if they are having some importance, we would like to discuss that. But other than that, we are trying to start these community calls for proposals which are important and which are less known. Maybe they can be useful for different purposes by developers for different use cases. The first in that is Account Abstraction community call, and we are planning to have it on the 28th. So there are certain things that was there in my mind about these calls. I'm going to share that first, and then we can hear everybody and what we can do and we cannot do.

This is the first time we would be having any proposal related to community call, though we already have done related to the upgrade. I avoided it for Istanbul. My thought was if we can get associated with Eth Magician people and start working on it, because they are the ones who are also looking into the proposals. So for this particular community call, the idea was to have it in the form of an event. We can design a banner for the call and then have questions collected, talk about it on at EthMagician Reddit, on Medium posts, Twitter announcement. Hudson has agreed to be the moderator of the call. So we could have him there, we can livestream. And if people think about having a panel discussion, we can also invite different people from the community. And yes, we might want to promotion in the Dev community. So what are other thoughts on how we should go about it?

**Hudson Jameson**
That all sounds good.

**Pooja Ranjan**
Yeah, right. So we are targeting it to be on November 20th at 9 AM EST. So, yeah, we can start working on it.

**Hudson Jameson**
So the ways to get involved, I'm guessing, would be to submit questions or attend it themselves if they're a Cat Herder. Would that be accurate?

**Pooja Ranjan**
Yeah, that is fine. If they are a Cat Herder, yes, they can do that for that. There was just a rough idea in my mind - can we go ahead and create a form, a table form or a Google form and spread it in the community? If they are interested in joining the call, they can fill out the form and then we will send the invite? How does that sound?

**Hudson Jameson**
Sounds good to me.

**William Schwab**
I know I'm just one guy, but Fridays are almost always a difficult day for me to attend.

**Pooja Ranjan**
The whole idea of having it on Friday was Friday, generally people attend for the AllCoreDev meetings, and this week, particularly, was not a meeting, so we thought that that would be a good one. But yeah, see if you can make it anyhow.

**William Schwab**
Yeah, there's no way. Sorry.

**Hudson Jameson**
That's okay. Future ones we can consider a different time, of course.

**Pooja Ranjan**
Yeah, of course we can.

**Alita Moore**
What time was this one this week?

**Pooja Ranjan**
And it's not in this week. It's the coming week, November 20th 9 AM EST.

**Alita Moore**
Okay. I don't think I can make anything before 10 AM.  Anything before 9 PM EST like even this is a bit of a stretch for me.

**Pooja Ranjan**
Yeah, we're generally flexible about time, like even 9 AM, I understand, it can be very early for the people on the West Coast, including Hudson and Brent. But the thing is we need to align with the author's timezone right. Yes, sorry.

**Brent Allsop**
I agree with Pooja that we need to align with the author timezone.

**Pooja Ranjan**
So yeah, that's about it. If anybody would want to get involved, take upon any responsibility creating banners or talking to people or creating a Medium post about it, please do let me know. And yes, we can work together on it.

**Hudson Jameson**
Great. Okay.

# 3 [Peep an EIP](https://youtu.be/-qK3wq0HjEE?t=1117)

Next up, we have Peep an EIP. Any updates on that?

**Pooja Ranjan**
Okay, on Peep an EIP last week, we had recorded proposal 2718 type transaction involved with Micah Zoltu. I think that is one of the very good episodes recorded so far. It has a detailed explanation of what the proposal is, the 2718 including some use cases and how it can be implemented by people who would be using it for making certain changes in their transaction type. So it's a very good watch. I would recommend to go ahead and watch it. This week, we are planning to have recording for [unclear](https://youtu.be/-qK3wq0HjEE?t=1168) itself. It's going to be an high level overview with Sam Wilson and Scott Dietrichs. The recording is scheduled at 1:30pm EST tomorrow, the November November 11. Just a heads up to everyone who was who are interested to join this meeting. It's tomorrow, November 11, at 1:30pm with Sam Wilson and Scott Dietrichs.

**Brent Allsop**
Got it on my calendar.

**Hudson Jameson**
Okay, thanks, Pooja.

# 4 [Meeting notes updates](https://youtu.be/-qK3wq0HjEE?t=1204)
Next up, we have item 4 - meeting notes updates for the four meetings that we take notes in.

**Pooja Ranjan**
So the first one is EIPIP. Brent, would you be able to let us know the summary of the meeting?

**Hudson Jameson**
Or maybe not even the summary but what is the status of the notes? Is that what you mean?

**Brent Allsop**
I'll quickly do both. But basically, the meeting was kind of split in half. And so rather than duplicating everything and transcripts and everything, we're trying to condense that down into, we're going to list Edson's questions and have a summary. And we're going to try and do some summary and stuff like that. So we've got a first draft of that. But Pooja had some additional information she wanted. And so we're working on that. Hopefully, we'll have that finished today.

**Pooja Ranjan**
That's great. So one of the action items that came out of that meeting was publishing a medium blog on the Cat Herders medium account about the network upgrade process, which is not very popular these days, because it's something new that we decided in the EIPIP meeting itself. So we have drafted this blog. Sharing the link in the chat, and yes, any kind of feedback is welcome. If it would be good, we can publish this another day or two.

**Hudson Jameson**
Yeah, I plan to look over this. If I don't look over it before you're planning on publishing it, remind me. Just nudge me for that.

**Pooja Ranjan**
Sure. Okay, so I think that's it, because I do not see the other people who were working on notes, but we have notes ready for AllCoreDev and Eth2 meetings.

**Hudson Jameson**
And 1559 I think, right?

**Pooja Ranjan**
That's not up yet. So we are done with the notes for AllCoreDev and Eth2, and 1559 should be done by today. I hope.

**Hudson Jameson**
Okay, sounds good.

# 5 [Emergency communication group](https://youtu.be/-qK3wq0HjEE?t=1350)

Next item is emergency communication group. For that one, the next step on that is I'm going to talk to some Eth1 security people and get some feedback. I talked to Eth2 security people, and actually, they did bring it up recently about utilizing the Cat Herders for their Google sheet of people to reach out to, and especially in the context of Eth2 staking, if there's a problem, to utilize us to reach out to those groups and make sure that we can communicate messages to them, or get them all in the same place to communicate messages.

**Pooja Ranjan**
Sounds good.

**Hudson Jameson**
So I'll just keep updated in the Telegram channel on that.

# 6 [Cat Herders funding - Moloch DAO & ESP](https://youtu.be/-qK3wq0HjEE?t=1398)

Cat Herders funding - Moloch DAO & ESP. For the Moloch DAO proposal, we'll be submitting that today or tomorrow at the latest. And Pooja and I have been working on that, I think it's for $45,000. And if you're interested in looking it over before we publish it, let us know. And then with ESP, actually, the other day, Pooja, I forgot to mention this when I was talking to you the other day, but I'm talking to someone from ESP again. Because there's been some renewed interest in the Cat Herders and just kind of getting an update of where we're at, more so than anything else, and where our funding's at and what we're doing and what we've accomplished. So I'm starting conversations on that, and then we'll pull people in as needed.

**Pooja Ranjan**
Sure. So I'm planning to have a summary of what we did in this entire year, maybe by the end of November or December. But if you need something before that, some kind of document in which they would like to see what we have done in 2020, I'll be happy to work on that. Let me know.

**Hudson Jameson**
Okay, sounds good. Yeah, I think that'd be a good document in general for us to share with the community and to share with other places that want to fund us and stuff. So yeah, maybe not urgent to make. But if we can morph the MGP document and just add details to that. Or make a second document that's like the MGP document, but more detailed about what we've done up to this point.

**Pooja Ranjan**
Sure. I'll look into that.

**Hudson Jameson**
Okay, anything else on that topic? I forgot to ask on the emergency communication group topic, too. But if there's not on those two, I'll move on to the next one.

# 7 [ Discuss and close the ECH GitHub Issues/PRs](https://youtu.be/-qK3wq0HjEE?t=1510)

All right, the next one, instead of discussing closing GitHub issues, I know William added something a little bit ago to a comment. You wanted to start a conversation about engaging the members who haven't been participating much and increasing participation in general.

**William Schwab**
Yeah, I can talk to that. So we have a lot of members who I still personally look at as members, but I haven't seen a lot of interaction from them. And on the other hand, I know that a lot of times the biweekly meetings, these have a bit of a low turnout. So we've talked a lot and are making efforts in terms of recruiting new members, that I get the feeling, even though I suspect that a model where users sort of wax and wane in terms of how much they're contributing at any given moment, I get the feeling that some of the members probably with a certain level of engagement could come back to being in the meetings and lending their skills to the things that we do. So I wanted to start a conversation just about retention, if we think that we should be reaching out to people who have helped out in the Cat Herders in the past, to see what we can do in order to bring them back into the meetings and get back into the same loop. So I'm curious if that's also the paradigm that other people here operate under. Any thoughts they might have about something like that?

**Brent Allsop**
At least open a communication channel, I would think would be good, because they may have reasons like they've changed their priorities and just basically decided they have other priorities. But it would be nice to know that or, just pinging them might say, "Oh, yeah, I should get more back more involved with that."

**William Schwab**
Yeah. And in terms of priorities, I guess what I would say is I wouldn't really expect that anybody was like, "Oh, and then I just decided the Cat Herders are wrong. And I didn't want to do anything anymore." I get that people get busy with work, schedules change, other things come up. But speaking to the other point you made, I think just every now and then, just that level of "Hey, we're still here. We enjoy your contributions, and we'd love to hear from you." I think that could potentially go a long way.

**Brent Allsop**
Yeah, that's helped me a lot. When I miss a meeting or something, Pooja pings me and says, "Are you doing okay?" That helps me a lot.

**Alita Moore**
I think Pooja reaching out is also a very good thing. It's very nice of you, Pooja. I think that it's easy when it comes to Async stuff to sort of get uninvolved and forget that you're even involved at all. It's really weird. At least, that happens to me. So I think reaching out to people is probably good.

**Brent Allsop**
Yeah, let them know if they're missed.

**Alita Moore**
Yeah. Because they are.

**William Schwab**
So maybe I'll take this Async, then, maybe in the internal channel, maybe I'll start a conversation about who to reach out to, who's gonna reach out to them, and all of that. Unless people think that this is a conversation we should be having here and now.

**Hudson Jameson**
I think Async is fine. I think it's a good idea for new members. I was kind of thinking that maybe we could have something like an open house or almost like a job fair, a virtual job fair ask presentation and recruitment effort, where we have a meeting, a day or maybe a whole day where we're just having people come in and out of the chat room or a call. Or maybe not a whole day, but like a set time that eople can come in, a block of time to talk about Cat Herders with us and we go over the Cat Herders maybe a few different times or something.

**Alita Moore**
That sounds great. I think it's a really good idea. I feel like those normally occur with a big event, because generally people wouldn't really stop by, so is there any sort of virtual job fair type deal thing?

**Hudson Jameson**
There's Eth global events. And I think there's one in December. It's more hackathons. But it's still good to catch people at a hackathon and see what their interests are if they're less technical, or even if they are technical and want to help.

**Pooja Ranjan**
Yeah, I totally agree that involvement is very important. I have been talking about it for the past few meetings, that we are trying to get people onboarded, but the people who are already onboarded, I know that a few of them have filled up the onboarding form for Cat Herders. And they also have joined one of the other meetings. Somebody did notes for us this time, one of the missing meetings notes were done. So sometimes, it's my personal thought that sometimes their level of engagement is limited to a particular task only. So they want to show up for that. But yes, it would be important, and definitely helpful for us to understand how we can get them more engaged. Meeting them personally would be one of those which can be done with the help of hackathon and other meetings too.

**Alita Moore**
I mean, money is really a great motivator as well, especially with the website. You could have a list of money things that people can do.

**Pooja Ranjan**
Yeah, right. We can add that in the website. Also, when we are talking about how to get engaged, we can also highlight the opportunities that we have that also engage with some kind of incentive associated with small bounties or the things. So generally, what we received so far is for note takers. That's my thought.

**Alita Moore**
Yeah, I mean, that's how I got involved, right? I was like, "Oh, yeah, I can just go take notes." And I got inundated with the culture of the Cat Herders. I think that the people are a culture, for sure.
5
**Brent Allsop**
Yeah, it's an anarchic culture. You don't need governance. You just need good communication.

**Alita Moore**
Or you just need Pooja. I think that that's really what it comes down to.

**William Schwab**
I think that's what it comes down to, yeah.
2
**Alita Moore**
32:34
Yeah. Employ Pooja, and we'll be pretty good.

**Pooja Ranjan**
I'm good at chasing people, looks like.

**Alita Moore**
Yeah, well, the fact that I'm here right now, I think is really testament to your ability.

**Pooja Ranjan**
Thank you.

**Hudson Jameson**
Okay. Is there anything else on this topic? Okay.

# 7 [ Discuss and close the ECH GitHub Issues/PRs](https://youtu.be/-qK3wq0HjEE?t=1510)

Next up, we have close and discuss GitHub issues and PRs. For the PM repo issues, there's nothing in there that I see that would probably have updates, I don't think. Does anyone see any issues that would have updates?

**Pooja Ranjan**
Just one thing. Um, and I'm not saying that it has an update. So I may have mentioned it earlier as well. About number 10441. Just wanted somebody to double check if it is good and that is ready to be closed? Because I believe they have started this website again.

**Hudson Jameson**
Yes, they did. And so we can close this. I'll close it. Okay, just closed it. Yea! Anything else?

**Pooja Ranjan**
There was one more I am not very sure that it is closed or not - Number 118. Remember, you did some conversion sometimes back, so is it done?

**Hudson Jameson**
The only thing left is that we have a little bit of money in the old multisig that we're not able to get out, because it keeps producing an error. And I was trying to find someone from Gnosis to help, and I couldn't reach through my contacts. They wouldn't answer, so I'm going to go to their Discord server and ask there.

**Pooja Ranjan**
Okay, okay. No, I just wasn't sure, because I remember that you started working on it. So I wasn't sure of the final status.

**Hudson Jameson**
And then on the funding issues, mostly, it's actually pretty caught up. The earliest one is nine days ago, and we like to batch them.

**Pooja Ranjan**
I think some of them are open, but they are already paid.

**Hudson Jameson**
Oh, good.

**Pooja Ranjan**
So I think there are only a few are new, three or four are new. Yeah, we'll close the rest of them, please go ahead and check if you have received the funding. That issue can be closed.

**Hudson Jameson**
You know, the Eth2.0 beacon chain deposit contract launched. And people need to get their deposits in by the 24th. So the weekend of the 21st 22nd and 23rd, and then the day of the 24th is going to be very congested on the network, primarily the 24th. And then also the day before the first and the day of the first is going to be congested, because that's the launch of the contract, or that could be the launch of the chain Phase 0 beacon chain. And so people have to deposit the week before in order to get in at genesis. Or they can also do it the day of but not be at genesis. So all that being said, just be aware of those days if you're trying to submit transactions for anything.

**Pooja Ranjan**
Yeah, yeah, sure. I'll try to close this and create new transactions maybe in a day or two, by tomorrow, or day after tomorrow. I'll look into that.

**Hudson Jameson**
Okay, great. Anything else on outstanding GitHub issues?

# 8. [Review of outstanding action items from previous ECH meetings](https://youtu.be/-qK3wq0HjEE?t=2208)

Okay, and then meeting 44 notes.

Actions are 44.1 EIP 1559 reach out to more exchanges and wallets. And also 44.2 is publish a second report on 1559.

**Pooja Ranjan**
Yeah, we are working on reaching out to more wallets this time. And we had one meeting last week with one of the project, which is like a high gas user project. But we still need more support on reaching out to exchanges and wallets. We have received very, very few responses from them. So if anybody from Cat Herders has a needed contact in there, please feel free to share with the 1559 group, the outreach group, and we'll get in touch with them.

**Hudson Jameson**
Does that have a Discord or Telegram channel?

**Pooja Ranjan**
It is available in Discord.

**Hudson Jameson**
Oh, perfect. Okay,
3
**Pooja Ranjan**
So we can just mention it over there and we can get in touch with more wallets and exchanges. We need them.
1
**Hudson Jameson**
Okay, sounds good. So, submit a Moloch dow proposal, that we talked about, that's 44.3 action item, and that's happening today or tomorrow.

44.4: Update the ECH website to include the newsletter sign up. We talked about updating the website. I don't know if we have the newsletter set up.

**Pooja Ranjan**
For the newsletter, I have figured out a way in Medium itself. There's a way for publishing it. Whenever the newsletter is published, it automatically gets to the inbox of whoever have followed us on Medium. So that is there. But I believe this particular action item was to have a way to collect emails for other people who are not on Medium, not a follower of Medium but they are still interested in getting our newsletter. So yeah, I think this would be one more thing that we would like to consider, ways we can collect their email addresses.

**Alita Moore**
Okay, that's fine. I can definitely do that. And then also, I was really feeling like a great thing for the website would be a newsfeed where we can have the Medium posts or even just post directly to the website, although posting to the website might just take a while to get working, just because it's not really necessary right now. I just think that's be a nice thing. But would you guys like to have a newsfeed on the website?

**Hudson Jameson**
That does sound cool.

**Pooja Ranjan**
Yeah, it does. So what what is there in your mind? Is it some some RSS feed coming from any particular website? Say, for example, Ethereum Reddit or something? Or do you want it to be coming from the Ethereum Cat Herders medium blog?

**Alita Moore**
Yeah, I was thinking something like the Medium blog, or if we wanted to link anything else as well. I'm not totally sure, so I could use some input/advice from you, Pooja, or anybody else, of course.

**Pooja Ranjan**
So I have added that. If you look into that ECH website doc that I shared some time ago. I have a section of latest newsletters and other blogs. Cat Herders also publishes blogs. So, for example, Edson did some survey on EIP editors and he wrote a blog on that. William arranged a workshop with the help of Tim and Helena, so he wrote a blog. These are featured blogs. So we can have that listed there and the regular newsletter update that we do.

**Alita Moore**
Yeah, that's interesting. Oh, you know what, that's really cool. Because you could just have a blog, a place where it's all just a bunch of articles. And then it's authored, right? That's cool. So we're basically a news agency.

**Pooja Ranjan**
All this information is available with us. The only problem that we have is if anybody's interested, they have to dig deeper to find out this information. And the purpose of having this Cat Herders website is everything is available on the dashboard. You just go and click the right button, and you will get the information that you are looking for. We did a lot in the past two years. But it's sometimes become difficult to explain it to people what we did, so we just want to have it on a page. People can get the information all by themselves.

**Alita Moore**
Do we want to have an infinite page where as you scroll, it just loads? Well, obviously not infinite, because we don't have infinite articles, but something like that?

**Pooja Ranjan**
I am personally okay with that. But I'm willing to hear other thoughts because my website is like that. So I know that's something good.

**Alita Moore**
I think it'll be a bit different. But yeah.
3
**Pooja Ranjan**
If anybody does not have any objection on that, we can do that. Or other thoughts.

**Hudson Jameson**
Mo objection here. Okay, before we go - oh, hey, Edson! Welcome.

**Edson Ayllon**
Hi.

**Hudson Jameson**
Let's see, I think that might be everything. That's all the action items. Was there something else? There was a decision that the next meeting is 1500 UTC on November 24. Oh, that's the deposit contract day for the week before the deposit contract. Cool. Okay. Thanks, everybody.

**Brent Allsop**
I had one more quick question back on the meeting notes. The last meeting notes for the EIPIP was meeting 20. And I'm still not seeing meeting 19. Is there something we need to do to try and get that to happen? Or should we just not not worry about that?

**Pooja Ranjan**
I think that is done. I remember seeing some message on Discord. I did not get a chance to look into the pull request yet. But I remember seeing somebody posted the notes for that.

**Brent Allsop**
Oh, I didn't see the notes there. But maybe the pull requests. I didn't check the pull requests. I'll check that. Thanks.

**Pooja Ranjan**
Yeah, I think it is that in the pull request, I can see that.

**Hudson Jameson**
Okay, is there anything else?

**Brent Allsop**
So when is that pull request going to happen? I guess I'll just update the readme.md. I'm wondering when that pull request will happen.

**Pooja Ranjan**
I think it is already there. I just shared the link in the chat.

**Brent Allsop**
No, I mean, when it's going to be merged.

**Pooja Ranjan**
I can look into it. It was just one day before, so I'll just look into it and close it.

**Brent Allsop**
Yeah, that'll make it easier for me to do my pull request if that's merged before I do that. Thanks.

**Hudson Jameson**
Okay, is there anything else from anybody before we head off? Okay. Thanks, everybody. Have a great day. Thank you.

# Attendees

* Alita Moore*
* Brent Allsop
* Edson Ayllon
* Hudson Jameson (Host)
* Jim Bennett
* William Schwab

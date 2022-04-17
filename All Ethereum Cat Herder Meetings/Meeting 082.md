# Ethereum Cat Herder Meeting # 82  Notes
### Meeting Date/Time: Tuesday  12 April 2022 at 15:00 UTC
### Meeting Duration: 0.5 hour
### [GitHub Agenda Page](https://github.com/ethereum-cat-herders/PM/issues/278)
### [Audio/Video of the meeting](https://www.youtube.com/watch?v=9PzLdJqyU3I)
### Moderator: Pooja Ranjan
### Notes: Avishek Kumar

----

## DECISIONS & ACTION ITEMS

**DECISION/ACTION ITEM 82.1**: William will try to reconnect with earlier ECH members

------------
# 1. Ethereum  network upgrades

- [The Merge](https://ethereumcatherders.com/the_merge/)

  - Mainnet Shadow fork

**Pooja Ranjan** [0:01](https://www.youtube.com/watch?v=9PzLdJqyU3I&t=1s): All right we can go ahead and start welcome to Ethereum Cat Herders meeting 82. I have shared an agenda in the chat. So I see the first item listed here is Ethereum network upgrade as we all know merge is approaching the mainnet shadow fork was a huge success. The ttd was reached yesterday Geth and Erigen Client  are progressing nicely but there were some issues with Nethermind and Besu. They stopped at the transition. A bug is there but it is being fixed and deployed at the Nethermind  client end  and that will allow them to sync up. All the stats for this shadow forking is available at ethstats.mainnetshadowfork1.ethdevops.io . 

- [Pari's Twitter thread](https://twitter.com/parithosh_j/status/1513129881927884801) 

**Pooja Ranjan** [0:56](https://www.youtube.com/watch?v=9PzLdJqyU3I&t=56s): Paritos has shared a twitter thread last week, explaining what testing the merge team has been up to. It's explained all about the shadow forking of mainnet so, please check out the twitter thread and link is added in the agenda the mainnet shadow fork also identified an issue. So this issue was missed on the devnet. I suppose or could have been easily missed on the devnet. The problem was the default cash limit is set to 8 millions but miners voted it up to 30 millions and since most validators  would run the default value the gas limit would quickly drop. This issue is fixed now and Marius shared a tweet explaining what happened with that particular issue and how it is dissolved. So please check it out if you are interested in learning more about shadow forking on mainnet. 

- [Shanghai specs, Tracker](https://github.com/ethereum/execution-specs/blob/master/network-upgrades/mainnet-upgrades/shanghai.md)

**Pooja Ranjan** [2:07](https://www.youtube.com/watch?v=9PzLdJqyU3I&t=127s): The next sub  item is Shanghai. Shanghai is the next network upgrade that we are expecting after the merge. So in the last all core dev meeting client dev discussed some of the Shanghai proposals, we already have about six proposals in cfi and these weeks we are discussing some more proposal to be added or just to be sure that we don't need any further proposal because we are like already in the limit and these proposals are good enough for an upgrade. The two proposals that were discussed in the last meeting were eip 4895 Beacon chain push withdrawal as operations. This particular proposal is already in cfi and we have recorded a peep video with co-author Alex stokes. I have shared the recording this morning, so please check it out on ech in youtube. This is an interesting proposal that will enable a staking withdrawal. People have been able to stake their ether on ethereum mainnet but there was no proposal to make the withdrawal realised by the speakers so this is going to be a proposal which we may be expecting with Shanghai upgrade. Another proposal was a eip1153 transient storage opcodes so Moody from uniswap explained this proposal and generally the client that we're in agreement that this is a good proposal. It received good feedback. However it could not gain a general consensus to be added to the cfi. Some people proposed that it can be considered for Shanghai upgrade. Sorry for the Cancun upgrade but that's nowhere close to a year from today. That's on the network upgrade, if anyone has any question comment on any topic please feel free to chime in and I am just trying to come up with the updates that I have at my end.

# 2. Element Finance airdrop [details here](https://mirror.xyz/0x3fcAf7DDf64E6e109B1e2A5CC17875D4a5993F39/bctuLRkf7oBL4mMJ9lPf0y0blFjBDslTUfUL0CEk1gc)

**Pooja Ranjan** [4:12](https://www.youtube.com/watch?v=9PzLdJqyU3I&t=252s):  The next item is element finance airdrop, so as we know element finance announced the formation of DAOs last month and the airdrop also included contributors to several ecosystem repositories. The good news with the cathode is that whoever have contributed to Ethereum cat herders repository or to any other ethereum repository as a cat herders is eligible for this airdrop more information is available in the post and I have added the link in the agenda for people to refer to. So if you have ever documented notes on behalf of ethereum cat herders for ethereum core dev meeting the consensus layer meeting or any other meeting you are definitely eligible. So please be sure to check out the blog post.

**William Schwab** [5:05](https://www.youtube.com/watch?v=9PzLdJqyU3I&t=305s): Is it still possible to claim an element ?

**Pooja Ranjan** [5:12](https://www.youtube.com/watch?v=9PzLdJqyU3I&t=312s): Yes it is possible, it’s open for a year.

**William Schwab** [5:14](https://www.youtube.com/watch?v=9PzLdJqyU3I&t=314s): Okay fine.

# 3. Events & hackathon

- Devconnect [Schedule](https://devconnect.org/schedule) Amsterdam, Netherlands 18-25 April 2022

**Pooja Ranjan** [5:18](https://www.youtube.com/watch?v=9PzLdJqyU3I&t=318s): All right,  the next item listed here is events and hackathon. So  devconnect Amsterdam event is coming up. It's starting from april 18th till april 25th. I have shared a link of the OG council for which ethereum cat hurdles have been supporting the fellowship of ethereum magicians. These people are organising some events there and we have had out having speakers for those events. There is this governance forum event on 24th of april. So the timing is 10 30 a.m to 12 p.m local time if you are in Amsterdam and you have some thoughts or participated in any form of governance of ethereum. If you can make it to the meeting that would be really awesome. We would love to see you over there. The details of speakers and other events that are being organised are available on the link added to the agenda. 

- Devfolio

**Pooja Ranjan** [6:24](https://www.youtube.com/watch?v=9PzLdJqyU3I&t=384s):Devfolio is an organisation which organises hackathons and events in india. I am happy to share that I have been helping out this women fellowship program that they have started there and helping out the women to be a contributor to the ethereum ecosystem. Help them, learn about ethereum and may be able to build a project. So it's a great initiative by the dev folio and last week. We were watching the demos of the project that they have come up with after the entire week of learning and it was really great. I am so happy to share that the grad students are making good progress there and I am hoping to see more contributors to the ethereum ecosystem joining shortly. There is another event starting from march 30. That is called Manthon.  It will last till may 14.  Please check out the link to get more description of participation. Any question comments so far?

**Brent Allsop** [7:39](https://www.youtube.com/watch?v=9PzLdJqyU3I&t=459s): Yeah, these are activities in india?

**Pooja Ranjan** [7:44](https://www.youtube.com/watch?v=9PzLdJqyU3I&t=463s): That's right.

**Brent Allsop** [7:45](https://www.youtube.com/watch?v=9PzLdJqyU3I&t=464s): Cool I thought because crypto I thought was illegal in india. Do they hold crypto or not? Anyway I didn't mean to just take time up in the meeting but yeah that's cool that stuff's being done in india.

**Pooja Ranjan** [7:59](https://www.youtube.com/watch?v=9PzLdJqyU3I&t=479s): That's right so um blockchain is legal there and they are promoting blockchain. I am personally aware of you. The best institutions there in India that are supporting IIT is one of those and I am in touch with these organisations. I am hoping to help out people who are going to finish up their courses and may be able to get some internship in the ethereum ecosystem. So yeah it's a great initiative and the good news is it is also supported by the ethereum foundation.

**Jose** [8:30](https://www.youtube.com/watch?v=9PzLdJqyU3I&t=510s): May I add something please?

**Pooja Ranjan** [8:33](https://www.youtube.com/watch?v=9PzLdJqyU3I&t=513s): Yeah please go ahead.

**Jose** [8:35](https://www.youtube.com/watch?v=9PzLdJqyU3I&t=515s): It's not just that it is legal, it has been actually completely regulated by law. So it's legal and has a legal frame for taxes and everything. So just to let you know. 

**Brent Allsop** [8:53](https://www.youtube.com/watch?v=9PzLdJqyU3I&t=533s):  So I could start because I have some employees in and I would love to start paying them in ether. So I could start doing that now.

 **Jose**[8:58](https://www.youtube.com/watch?v=9PzLdJqyU3I&t=538s): Yes, as long as you fulfil the tax regulation. you won't have any problem 

**Brent Allsop** [9:05](https://www.youtube.com/watch?v=9PzLdJqyU3I&t=545s): Okay cool well thanks for that.

**Jose** [9:10](https://www.youtube.com/watch?v=9PzLdJqyU3I&t=550s): No problem, no problem, okay cheers.

# 4. ECH updates

- Ethereum Cat Herders Update [(March 2022)](https://medium.com/ethereum-cat-herders/ethereum-cat-herders-update-53-8afadcda6d4a)

**Pooja Ranjan** [9:14](https://www.youtube.com/watch?v=9PzLdJqyU3I&t=554s): Awesome thank you Jose for the update and talking about updates let's
move on to the ethereum cat herders update. So I have shared the updates for the month of March early this month. Please check out the blog post, it contains information about whatever we have contributed the entire month. It talks about different events that we have shared with their community.  Please check out the blog post.

- [ECH website](https://www.ethereumcatherders.com/)

**Pooja Ranjan** [9:46](https://www.youtube.com/watch?v=9PzLdJqyU3I&t=586s): The next is the ethereum cat herders website, so the ethereum cat herders website is now live. Thanks to Ghani for helping us, bring it back online and there is this new contributor Slava who has been helping us maintain the pages. So recently he made some updates to the merge page and now the merge page on the ethereum cat herders website contains most of the information related to all the test nets that we have for this particular upgrade and we are hoping to update this page to provide information about
other upcoming proposals. I don't know Slava if you have anything to add on top of that.

**Slava** [10:34](https://www.youtube.com/watch?v=9PzLdJqyU3I&t=634s): No, I don't really have anything to add. I have just been trying to keep the website up to date, so I have been working on updating all the stuff since. Nothing really has been done since December. So just trying to keep on top of things.

**Pooja Ranjan** [10:46](https://www.youtube.com/watch?v=9PzLdJqyU3I&t=646s): Yeah right thank you so much for that and as I was mentioning in the beginning of this call now that we have successful shadow forking of mainnet, it would be nice to have other related documents and information updated to the merge page. If you have any questions please let me know. Maybe I will be able to share some links that can be updated on the page.

**Slava** [11:14](https://www.youtube.com/watch?v=9PzLdJqyU3I&t=674s): Okay yes, absolutely sounds good. 

**Pooja Ranjan** [11:18](https://www.youtube.com/watch?v=9PzLdJqyU3I&t=678s): Thank you so much.

- [ECH engineering](https://github.com/ethereum-cat-herders/PM/issues/266) 

**Pooja Ranjan** [11:20](https://www.youtube.com/watch?v=9PzLdJqyU3I&t=680s): On ECH engineering, I know Jose has been working with the eip bot and eipv issues and he has been looking into closing issues like if they are duplicate or if that has been done. He has been looking into it. So Jose if you have any updates that you would like to share.

**Jose** [11:38](https://www.youtube.com/watch?v=9PzLdJqyU3I&t=698s): Yeah thank you. Yeah that's basically what you say we we close we managed to close one issue this last week which was duplicated. Precisely 61 was duplicated 50 feet which now has been very much agreed what programming would be recommended to include it into the bot but issues 60, 50a and 53 could be easily closed which were in the process with the editors and I think that for the next call. We will have those three issues closed as well.

**Pooja Ranjan** [12:22](https://www.youtube.com/watch?v=9PzLdJqyU3I&t=742s): Awesome yeah I hope to all these issues being discussed in the upcoming EIPIP meeting with the editors and we may be able to figure out a proper way of revisiting to these issues and close the one which is like in a state where we can close and move on.

**Jose** [12:41](https://www.youtube.com/watch?v=9PzLdJqyU3I&t=761s): yeah sure. Thank you.

**Pooja Ranjan** [12:46](https://www.youtube.com/watch?v=9PzLdJqyU3I&t=766s): All right, about learn2earn, we have made quite a significant progress over there. George who has been helping out in the development of this project have made
some pull requests and we are almost good with the UI part of it now. We are looking into
added courses there. There are few other people Prachiman, Stefan, Mr.Yalamanchi and a few other contributors who have been working and supporting the development of this project. We have listed some of the issues where we are looking for some support in the github repository. So if anyone is interested to contribute to this project please check out ethereum cat herders L2e github repository.

- Cat blazers

**Pooja Ranjan** [13:39](https://www.youtube.com/watch?v=9PzLdJqyU3I&t=819s): On the next sub item we have cat blazers. We have William Schwab on the call. William if you would like to take this one.

**William Schwab** [13:52](https://www.youtube.com/watch?v=9PzLdJqyU3I&t=832s):  Let's see if my mic wants me to take this one. So we have gotten the podcast back and running. We recorded an episode last week with Roman Semenov from Tornado cash which should get released this week and should be recording another episode today which we hope to release in another couple of weeks. We've been putting some effort into that. We have also been trying to up our game a bit. We should be migrating over to Zencaster for recording and we're using a new editing tool also. But I forget it's because I am not the one who does the editing that's zk doof. There are some charges associated with that. At some point I am interested in bringing before the council if we might be able to be reimbursed for just the monthly charges of the tools that we're using. If there's any other like you know if anything else or anyone else here wants to leverage them for recording purposes. Also it doesn't have to only be us. We could kind of open that up for the larger cat herders content generation kind of end but that's also just something I am putting out here now. I don't need an answer on that necessarily the second I had some ongoing onboarding efforts just in terms of the general onboarding that I usually do in the position.I have spoken with some people independently had a bit of work through colonel and I have continued my association with ethernet DAO being that ethernet DAO is looking to independently pay. Its
council members. I will probably stop this work. I do my work with the cat herders just in case there's any kind of conflict of interest or anything like that and yeah that is about it for me.

**Pooja Ranjan** [15:49](https://www.youtube.com/watch?v=9PzLdJqyU3I&t=949s): Thank you William Schwab for the update on a few things on that. I remember a while ago we discussed making an outreach to our older members like the members who actually have started this group and they have got engaged with some of the other projects if that is something that you may be interested in. I have seen a few old members joining our discord so, if you get some time from ethernet and you would be interested in looking into it that would be great.

**William Schwab**[16:24](https://www.youtube.com/watch?v=9PzLdJqyU3I&t=984s):  I would be right now is a bit hard but if I could ask you independently to ping me in like probably about two weeks time, a little bit earlier like in a week and a half or so I would be happy to take it. I would be happy to work on that.

**Pooja Ranjan** [16:39](https://www.youtube.com/watch?v=9PzLdJqyU3I&t=999s): Yeah that would be great, thank you and on the reimbursement part yes I had a chat with zk doof and I was trying to explore what other tasks that can be leveraged with the reimbursement part of it. So for now if it is only for podcasts I was hoping that it can be used for some of the video editing and we are considering a reimbursement on a monthly basis. just trying to look into what all we can do. It's a delay on my part. I apologise for that.
Oh this is certainly under consideration and I don't know if someone has any suggestion on having a very good tool that can help us get the captions for notes that would also be really helpful. Because our present zoom account does not  help us to  record the caption. Though try to look into that part. It looks like they have a higher paid version of zoom that actually allows it. The problem is that they have a minimum requirement which we probably do not have at the moment, so if anyone has any suggestion on this kind of tool please share it.

**William Schwab** [17:44](https://www.youtube.com/watch?v=9PzLdJqyU3I&t=1064s): It's funny that you mentioned it but zencastr actually has the captioning tool built in.

**Pooja Ranjan** [17:51](https://www.youtube.com/watch?v=9PzLdJqyU3I&t=1071s): Oh that would be great. Yeah then maybe we can have a chat with zk doof and you and figure out how to be used with the rest of the group members and make good use of those tools but yes of course the reimbursement is under consideration.

**William Schwab** [18:08](https://www.youtube.com/watch?v=9PzLdJqyU3I&t=1088s): That actually does remind me again is there any progress on trying to get a domain for the podcast or not domain but like a separate email, like a podcast of ethereum cat herders and kind of getting control back over the emails in the domain like the characters.

**Brent Allsop** [18:26](https://www.youtube.com/watch?v=9PzLdJqyU3I&t=1106s):  I am working on it. That's on my things to-do list. Something happened with my credentials and I can't log in and I have tried, I have done it one round with their support trying to get back in but I haven't been able to get in yet so I will bump that up on my things to do lists. If I can get back in so I can create a new email.

**William Schwab** [18:41](https://www.youtube.com/watch?v=9PzLdJqyU3I&t=1121s): Cool thanks.

**Pooja Ranjan** [18:46](https://www.youtube.com/watch?v=9PzLdJqyU3I&t=1126s): All right, thank you and yeah I think that's all on the cat blazer side.

- ECH Operations

**Pooja Ranjan** [18:52](https://www.youtube.com/watch?v=9PzLdJqyU3I&t=1132s):  On ECH operations, we have a new journalist meeting planned for april. Ithink this time Shubhangi is planning to have two meetings. Not sure if she is there on the call. Doesn't look like, nevertheless the information available on the cat herders discord and we have two calendar dates updated for this meeting one and the U.S time zone one is in the asia time zone. So if you are new and you would like to share about you and learn more about ethereum cat herders. Please check out the events and whatever meeting date suits you. We will be happy to have you with us and maybe we can find a way to contribute to the Italian ecosystem.

- [EIP Insight](https://hackmd.io/@poojaranjan/EthereumImprovementProposalsInsight)


**Pooja Ranjan** [19:44](https://www.youtube.com/watch?v=9PzLdJqyU3I&t=1184s): The next sub item is eip insight.  So I have updated the report for eips till 11th of april as of now. We have five new eips of the erc category added to the repository. As a new draft one eip which is of the erc category again 2098 compact signature representation has been moved to final. There is this one proposal which is resurrected from stagnant and currently is in review status eip 1967 standard proxy storage slot is in the last call and the last call is ending on april 24th. So if you have any comments or thoughts on this proposal please participate in the discussion tool link and share it with us before this is marked as final. The link is added to the agenda so you can check out the detailed report there.

- [PEEPanEIP](https://www.youtube.com/playlist?list=PL4cwHXAawZxqu0PKKyMzG_3BJV_xZTi1F)

**Pooja Ranjan** [20:52](https://www.youtube.com/watch?v=9PzLdJqyU3I&t=1252s): On PEEPanEIP in the past two weeks we have recorded three PEEPanEIP and all these three are cfi proposals to Shanghai upgrade eip 3855 eip 3860 and eip 4895. Please check out the upcoming proposals and these are fairly new. Most of the proposals are in review status and they are accepted.  Comments from users or the projects let us know if any of these pro proposals are breaking any of your projects. Please
reach the developers if these proposals are affecting your dap in any way. For upcoming PEEPanEIP please check out the schedule link added in the agenda.

- Discuss issues with meeting notes. [Ref.](https://discord.com/channels/916516304972824576/916713868619833454/960205861991612476)

**Pooja Ranjan** [21:44](https://www.youtube.com/watch?v=9PzLdJqyU3I&t=1304s): Moving on to the next sub item is discussing issues with meeting notes. I would like to invite Brent to talk on that and first of all thank you so much Brent for fixing a lot of issues and a lot of small errors on the ethereum cat herder's pm repository. Over to you 

**Brent Allsop** [22:05](https://www.youtube.com/watch?v=9PzLdJqyU3I&t=1325s): Okay yeah I am going to share my screen if that's okay. So yeah this is just showing the repository here but anyway it looks like some of the media or issues that I wanted to point out have been done by Avishek and it looks like he's not here but he is on notes today. So I am just so basically he'll probably be transcribing these notes so kind of a message to him but one of the 77 meetings got installed instead of down in the cat herders pm. It got stuck  in the wrong directory and also a couple of the meetings like for I think it was. I can't remember which one it was. Let's see it was meeting md. The name was a bad case instead of uppercase m meeting space 080.md it was lowercase meeting 080.md and when you use the wrong case and then you test it on a windows system that works on a windows system but when you submit it. It breaks it on the windows system and it's really hard to fix that because I am on a windows system too and if you change the case it doesn't recognize that change. So you have to change the name, so up here I had to change the name you can see. I had to change the name and then I had to check that in and then I had to change it back with the right case. But anyway yeah just a comment if everyone could watch and make sure they get the case name correct. It should be uppercase m meeting notes and make sure it's in the right directory so yeah that's all I had. So thanks for that well.

**Pooja Ranjan** [23:46](https://www.youtube.com/watch?v=9PzLdJqyU3I&t=1426s): Thank you so much for sharing. This is really valuable for our new contributors because I have seen often that they missed out on smaller details. One of the details that I would like to highlight is adding timestamp for your meeting notes that is helpful for people who would like to refer it later on because sometimes it happens that by mistake it is not captured correctly even a simple word not or can't if that is missed in a meeting note that can change the meaning of the entire decision. So it's always good and helpful for people to follow the recording at that point if they have any confusion. So please be sure to add meeting notes time like a timestamp if you can do it with like the link base that would be awesome to have if not just add the hours and seconds and whatever editing, Brent suggested that is really good to keep the repository healthy and may be accessible for everyone to get all the notes in the right fashion. Thank you Brent for that. So looking into that it looks like we have all core dev meeting notes 135 available yeah. One more thing like whenever you are documenting notes please be sure to update the readme file of that document, so people will be able to find the notes that you have submitted. It's just a addition of a single row; it can be submitted in one pull request with two different comments if you would like to or even the single commit is also fine.

**Brent Allsop** [25:22](https://www.youtube.com/watch?v=9PzLdJqyU3I&t=1522s): Another quick comment on that the link to the reference makes sure it's a relative link to the notes reference and not abs not don't put the https colon on it just have the relative address like the other links to the notes because that makes it easy to test. Because if you put an absolute link you can't test that until you do the pull request but anyway.

**Pooja Ranjan** [25:46](https://www.youtube.com/watch?v=9PzLdJqyU3I&t=1546s):  Yeah that's right I mean that's right. So you can also check out the earlier meeting notes link and try to have it updated with your particular meeting number and more or less it is going to be the same one thank you.

- [Meeting notes](https://docs.google.com/spreadsheets/d/1axM1KaKc-GCcoPbAnYTOhgLnxXsBVoO5XRjTN3CLnck/edit#gid=0) and action items for ECH

**Pooja Ranjan** [25:59](https://www.youtube.com/watch?v=9PzLdJqyU3I&t=1559s): So we have all coded meeting 135 available and yeah that's it. We don't have consensus meeting 85 and eipip meeting 53 yet though we have requested the people documenting these notes to be submitting it as soon as possible. Again a reminder for everyone who is here to document notes in the timeline that we are expecting people to document notes in three days in case of complicated notes. It can be five days I understand the consensus meeting can be complicated because generally they are captioned less and we are unable to generate caption for that so it can be a little like longer for people to follow if they are not so technical but for other meetings if we have captions and if the meeting is within the time period. Please submit it within the first five days at the max we will try to
enforce this, so we can open the meeting notes for other community contributors if not submitted within the five days of timeline.
We had eip editors apprenticeship meeting 15 and the recording is now available. The next meeting is planned on april 19th so, if you are a contributor who is looking to help us with reviewing the proposals that are coming up in ethereum repositories. You are welcome to join the meeting and share your questions even if you are an author and you are having some doubts in the process of documenting the proposal. Feel free to join the meeting, that's all for this particular section I guess.

# 5.Discuss and close the ECH GitHub Issues/PRs


**Pooja Ranjan** [27:47](https://www.youtube.com/watch?v=9PzLdJqyU3I&t=1667s): Discuss and close the ECH github issues and peers. I know a lot of funding requests are open now and I am hoping to put all these requests on chain later today. So I am expecting this to be done by the end of the week. It was delayed because we ran out of eth. So we have to first arrange for that but that is now taken care of and I am hoping that the funding request would be fulfilled soon.

# 6. Review of outstanding action items from previous ECH meetings

**Pooja Ranjan** [28:23](https://www.youtube.com/watch?v=9PzLdJqyU3I&t=1703s): The last item for today is a meeting note that reviews action items from meeting notes and all right so it looks like we have only one action item and that is about a ruby developer. So I had a chat with someone this week and we have shared the requirement with at least two people. I have shared it personally and we are still looking for a ruby developer. We haven't finalised anyone yet. So people if you are listening and you are or you know someone who is a ruby developer. Send him or her my way, we are looking for a maintainer for one of our github repositories. I will be happy to chat more on that. Dm me if there are any questions so that's all I suppose for today's  agenda. Anyone have anything else to bring up today?

**Alita** [29:27](https://www.youtube.com/watch?v=9PzLdJqyU3I&t=1767s): I guess a bit of an update. I'm not sure if anybody provided one for ecs engineering. The repo has kind of stagnated recently um primarily due to my lack of involvement but I do know that several people have been more active so I wanted to give a shout out to some of those people. I am reading their exact usernames but yeah just if you're interested in being involved in the ech engineering and helping maintain it like the eip bot. Feel free to open a pull request for anything and we'll be quick to review and help you get that merged.

**Brent Allsop** [30:15](https://www.youtube.com/watch?v=9PzLdJqyU3I&t=1815s): Hey Alita I will direct you okay. Just to let you know

**Alita** [30:21](https://www.youtube.com/watch?v=9PzLdJqyU3I&t=1821s): Alright, it sounds good. Fine

**Pooja Rajan** [30:29](https://www.youtube.com/watch?v=9PzLdJqyU3I&t=1829s): Alright thank you Alita and thank you Jose. I know Jose is looking into some of the  eipv and eip body issues but  if anyone else is interested. Please join us. We need a lot of support there because there are a lot of open issues and more than marriott. So we'll be able to close it  sooner with more contributors. All right, I think that's all for today.
anything yeah 

**Brent Allsop** [30:56](https://www.youtube.com/watch?v=9PzLdJqyU3I&t=1856s): Yeah I see we have a bit more time so I wonder if I could ask for some more information about the element finance airdrop. What do we have to do, since we are cat herders, what  do we have to do to get in on that airdrop is that available?

**William Schwab**: There's a posted in the issues um it it leads you through it quite well 

**Brent Allsop** [31:14](https://www.youtube.com/watch?v=9PzLdJqyU3I&t=1874s): Okay so I can just read through that then and understand what I need to do.

**William Schwab** [31:19](https://www.youtube.com/watch?v=9PzLdJqyU3I&t=1879s):  Yeah if you haven't already generated the key I don't know if it's still open. I think you may have had to generate the key already. oh it's worth a shot if you run into trouble maybe try and ping me. I will see if I can ping someone over there who does the same contacts I do. I don't mean to offer your services Pooja but I would imagine we'd be thinking of the same person.

**Pooja Ranjan** [31:42](https://www.youtube.com/watch?v=9PzLdJqyU3I&t=1902s): Exactly yeah he's an old contributor to ethereum cat herders. Yes we will be pinging the same person.

**Brent Allsop** [31:49](https://www.youtube.com/watch?v=9PzLdJqyU3I&t=1909s): Okay cool yeah I will see if I can get that done and I will ping if not thanks.

**Pooja Ranjan** [31:54](https://www.youtube.com/watch?v=9PzLdJqyU3I&t=1914s): Alright well thank you everyone for joining us today. I hope to see you guys in two weeks from now and obviously we can keep talking async on ethereum cat herders  thank you everyone. Have a good one

**Jose** [32:13](https://www.youtube.com/watch?v=9PzLdJqyU3I&t=1933s): Thank you right 

**william Schwab** [13:14](https://www.youtube.com/watch?v=9PzLdJqyU3I&t=1934s): Thanks everyone.

-------------------------
## Attendees

* Pooja Ranjan
* William Schwab
* Shubhangi
* Alita 
* Jose
*Brent Allsop
*George 
* Victor
* Slava

## Next Call - April 26, 2022.






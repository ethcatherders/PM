# Ethereum Cat Herder Meeting # 87
### Meeting Date/Time: Tuesday  21 June 2022 at 15:00 UTC
### Meeting Duration: 21:12 
### [GitHub Agenda Page](https://github.com/ethereum-cat-herders/PM/issues/296)
### [Audio/Video of the meeting](https://www.youtube.com/watch?v=wY-6H4EAws0)
### Moderator: Pooja Ranjan
### Notes: Metago

---

## DECISIONS & ACTION ITEMS

**DECISION/ACTION ITEM 87.1**: It may be a good solution to use Arweave as a Youtube backup and Radical as a GitHub backup. 

---

## COMMUNITY PARTICIPATION 

**GitHub Backup on Radical**: If anyone would like to help create a GitHub action / bot to pull changes made to the main or pull the new main to mirror on Radical, please reach out on ECH Discord.

**Youtube Backup on Arweave**: If anyone is interested in helping upload ECH's Youtube videos to Arweave, please reach out on ECH Discord.

**ECH Website Updates**: If anyone is interested in helping with updating the ECH website with the information about Gray Glacier and information about the merge, please reach out on ECH Discord. 

**Ruby Dev**: If you are a Ruby dev interested in helping out with EIPs and Ethereum proposals, please reach out to us.

**Learn2Earn Frontend Dev**: If you are a front-end dev and can provide some support for the Learn2Earn app, there is an issue created on ethereum cat holders pm repository, please respond to that.

# Agenda

## 1. Ethereum Network Upgrades

### [Gray Glacier Upgrades](https://blog.ethereum.org/2022/06/16/gray-glacier-announcement/), [specs]( https://github.com/ethereum-cat-herders/PM/issues/296) 

**Pooja**[0:00](https://youtu.be/wY-6H4EAws0)
Welcome to Ethereum Cat Herders meeting 87. The first item listed here is Ethereum network upgrades. Let's start with Gray Glacier. So Gray Glacier is an upgrade planned to push the difficulty bomb. It is expected on June 29, at block number 15,050,000. The exact date is subject to change, due to variable block times and different time zones, but it is recommended that please upgrade your node on, or before Monday, June 27, just to account for the variable block times. I have added the link to the [EF blog post]( https://blog.ethereum.org/2022/06/16/gray-glacier-announcement/) for clients upgrade ready version, so check out the client node that you are running, and may be able to upgrade it to the latest version. 

### The Merge
[Sepolia Beacon Chain genesis]( https://github.com/ethereum/pm/issues/526) 
[Sepolia Resources]( https://sepolia.dev/), [blogpost]( https://etherworld.co/2022/06/17/sepolia-testnet-merge/) 
[Sepolia faucet]( https://t.co/kgWLwMveBC) 
[Staking Node Operators RFP]( https://github.com/ethereum/requests-for-proposals/blob/master/open-rfps/staking-operator-docs.md) 

The next one is Merge. Sepolia beacon chain genesis happened yesterday, so a beacon chain for Sepolia testnet is now available, and is getting ready for the testnet merge. We will know more about Sepolia testnet merge on the next all core dev call, however from early tweets, it looks like the beacon chain genesis was a success. There are a few resources available. Sepolia.dev has a good list of resources for anyone interested in participating in the testnet. There is also a blog post published that provides more information on the history of Sepolia testnet till the genesis of SBC, Sepolia beacon chain. So Sepolia is one of the tests that is expected to be around even after merge, unlike Ropsten, because Ropsten will be deprecated after the merge. People who are interested for Sepolia eth, there is a Sepolia faucet and that's about Sepolia. In parallel, Ethereum merge testing team is also planning shadow forking, so main shadow forking number seven has been planned for tomorrow, and we are expecting details and updates on this in the next all core dev meeting planned this Friday. On a slightly different note, EF invites RFP for documenting staking node operators so check out the link added to the agenda. If you are interested to submit an RFP for documentation. That's all on the merge. 

### [Shanghai specs](https://github.com/ethereum/execution-specs/blob/master/network-upgrades/mainnet-upgrades/shanghai.md), [Tracker](https://github.com/ethereum/execution-specs/projects/1)
There is no changes to Shanghai upgrade that is expected in maybe after the merge. Any question, comment so far?

## 2. New Initiatives [3:16](https://youtu.be/wY-6H4EAws0?t=196)

[GitPoap Badges](https://www.gitpoap.io/gp/133)
ECH GitHub backup & YouTube backup

GitPoap badges are now ready. I'm excited to announce that the website is ready for claiming poap, so check out the link in the description, and the next topic here is the ECH GitHub backup and Youtube. I don't know if we made any progress. Sorry to put you on the spot, William Schwab, do you have any updates on that? I'm assuming from the last meeting we were supposed to maybe invite community participation to like automate it with GitHub action.

**William**:
Yeah we talked about that. I spoke with Radical, will likely be speaking with them again. It does look like there is easy method…well wait, we're talking about YouTube or about GitHub right now? 

**Pooja**:
I understand radical is for GitHub and YouTube we will come later on.

**William**:
Right. So yes so which one are you asking me about?

**Pooja**:
Either of them whatever you have.

**William**:
Either. Okay, fine. So I mean for YouTube, I think in previous conversations that we've had, it looks like a backup on Arweave just directly or using a service built on Arweave for backing up videos specifically, may be the best. Theoretically we could also make a GitHub repo of the videos themselves, and then back that up on Radical, I wouldn't say it's like necessarily Radical’s use case but it should theoretically be possible. No reason not. As for the GitHub repos, using something like actions, we think would currently…we think would probably be the best way to handle that. It looks like it shouldn't be too bad, like to actually have some kind of bot, or action, or whatnot that just knows how to pull changes anytime anything's getting merged into main, or take the new main and then push that to mirror on Radical, in my personal case it's a question of bandwidth so yeah if there's anybody who knows their way around…knows their way around writing a GitHub action or anything like that, who'd be interested in helping out that would be really really awesome. It shouldn't be that big of a job. 

**Pooja**:
Thank you for that update. I looked into GitHub repo, like how we can add the YouTube or any mp4 video on YouTube. Looks like they have some limitation on the size of the video that can be added and it may not be useful for us to maybe create a folder and add the YouTube videos over there, so probably going directly, via Arweave looks like a good solution here, and we can like use radical for GitHub only.

**William**:
Okay.

**Pooja**:
Okay, so I had a conversation with zkDoof in the past on how to upload it on Arweave, so if anyone else is interested in maybe helping out with that, please reach out, and if not then we will try to get help from zkDoof to have the YouTube video uploaded on Arweave.

## 3. Events & Hackathons [6:39](https://youtu.be/wY-6H4EAws0?t=399)

[DEVCON VI: Applications Online, Participation Details Inside](https://blog.ethereum.org/2022/06/06/devcon-vi-details/)

Cool. Moving on, the next one is Events and Hackathon. So Defcon 6 that is announced, they are inviting application online and tickets are also available, so check out the link added to agenda. Other than that, I think I missed out here, but [EthCC Paris 5]( https://ethcc.io/), they are starting their hackathon from July 19 to 21, so check out the website of EthCC. 

## 4. ECH Updates [7:11](https://youtu.be/wY-6H4EAws0?t=431)

### [ECH Website](https://www.ethereumcatherders.com/)
Moving on, ECH updates, I don't see any updates on the website side, however we need to get the website page updated, because I don't see information of Gray Glacier and there are a bit of merge information that needs to be updated on the website page, so anyone listening if they are interested, please reach out. We have the GitHub repository. You just need to make a pull request to update the page. 

### ECH Engineering [7:40](https://youtu.be/wY-6H4EAws0?t=460) 

[ECH Engineering](https://github.com/ethereum-cat-herders/PM/issues/266) 

#### Need Ruby dev

Next is ECH engineering. The first one is Need Ruby dev. I looked into it and it looks like it is now solvable problem, but I have to confirm it with Micah, and if that is resolved then, probably not, but if we get a Ruby dev as a maintainer for future that is always good to have, so if you are listening and you are a Ruby dev interested to help out with EIPs and Ethereum proposals, reach us.

#### [EIP bot](https://github.com/ethereum/EIP-Bot/issues) & [EIPV](https://github.com/ethereum/eipv/issues) [8:11](https://youtu.be/wY-6H4EAws0?t=491)

**Pooja**:
Next one is EIP bot and EIPV. I don't know Jose, if you have any updates to share in this call today?

**Jose**:
No. Basically, I start with the testing of the bot. I have tried several ways, but no success. To test the co-modifications that Micah and myself basically agree that we're going to fulfill the issues pull requests so I will keep trying to figure it out. There is no documentation, basically there is a written file in the bot repo but at least for me, it's not so clear, but I know that if I keep writing, I will I mean it's exhausting to be fair but the odd grades are stuck due to not proper testing, which is valid what is not supposed to be valid, is that it's so hard to get the environment set up for the testing, but I will get there. If anyone has any idea or suggestion, I will be really really happy and I will really appreciate it…any comment at all…I mean…feel free to contact me and that would be, as I say, I appreciate it. I try to get it forward. I mean…the code is there but need to be tested, as I say, so that's pretty much from the both sides. 

**Pooja**:
Thank you so much for update. Yeah, I understand the bot is, has been recently written, and it's an altogether new bot. We could use some documentation to help at least set up the testing environment before actually pushing them to production. 

**Jose**:
Okay, yep.

**Pooja**:
All right, thank you for that. 

#### [Learn2Earn](https://github.com/ethereum-cat-herders/L2E)[10:36](https://youtu.be/wY-6H4EAws0?t=636)

**Pooja**:
Moving on, Learn2Earn, I don't see George on the call. We had this meeting, a Learn2Earn meeting yesterday, recording and notes are available on l2e channel on ethcatherders discord. Basically, we are very close to the finishing of the application. There were some modifications suggested by iMan and we are trying to have a light and dark mode for user interface. That's the part of integration which is left, I guess. Shubhangi is working on making quiz. Shubhangi, do you have by any chance, any updates on that?

**Metago**:
Yeah, I just submitted a link to the quiz on blog gas limit and I will probably work on the delaying the difficulty bomb lesson for this week.

**Pooja**:
Okay, sounds good. So we are trying to have at least five to ten quizzes ready before the release of the application and the work seems to be in progress, though we are still looking for some help on front-end side, so if you are a front-end dev and you are looking forward to provide some support there is an issue created on ethereum cat holders pm repository please respond to that.

### Cat Blazers[12:06](https://youtu.be/wY-6H4EAws0?t=726)
[ECH Podcast](https://open.spotify.com/show/7dgxKMkSyy3HWtQW7OfqXA)

**Pooja**:
Next is Cat Blazers. On ECH Podcast, we released the episode of PEEPanEIP in audio version podcast version. I'm not sure if there are any further update on it. All right. 

**William**:
No, not on my end, no.

**Pooja**:
Not a problem. I think I will talk to you about stats and everything separately off this call, yeah, I'll reach out to you for that.

**William**:
Okay.

**Pooja**:
But for now we what we are doing is like, there was a request to have an audio only version of PEEPanEIP, so people can learn about proposals and they hear what, what is coming up, so we have started sharing it on ECH podcast, so you can check out and let us know your feedback, and comment, any suggestion on any particular topic that you would be interested to hear about.

### ECH Operations[13:13](https://youtu.be/wY-6H4EAws0?t=792)
[All Wallet Devs meeting Recording](https://youtu.be/0fMUrgdgI_g) 

**Pooja**:
Moving on, the next one is All Wallet Dev meetings. So recently we started this All Wallet Dev meetings. Actually it is an initiative by Sam Wilson and others and there is this discord channel of All Wallet Dev. They have requested for some support from the cat herders side and zkDoof is providing support on recording and publishing of the meeting, so we have created a separate playlist for wallet dev meeting. Check out if you are interested in like any proposal related to wallets, or if you are a project developer working on wallet, so yeah if you haven't joined the discord channel for wallet devs, please do, and follow us for future meeting announcements.

### [EIP Insight](https://hackmd.io/@poojaranjan/EthereumImprovementProposalsInsight) [14:07](https://youtu.be/wY-6H4EAws0?t=847)

The next one is EIPs’ insight. In June, two networking EIPs moved to final. We already have shared this information. EIP 2464 and EIP 2364, which were long pending are now final. We have seven new EIPs in draft added to the repository and seven potential proposals are waiting to be merged. Out of the seven which are added as draft, one important core EIP is EIP 5133, which is to delay the difficulty bomb. Other than that, we have recently been joined by a new EIP editor, Gavin John, whom we know by Pandapip1. The EIP 1 has been updated to reflect this new edition of EIP editor.

### [PEEPanEIP](https://www.youtube.com/playlist?list=PL4cwHXAawZxqu0PKKyMzG_3BJV_xZTi1F) [14:56](https://youtu.be/wY-6H4EAws0?t=896)
[PEEPanEIP Schedule](https://github.com/ethereum-cat-herders/PM/projects/2)

Next is PEEPanEIP. Last week, we recorded EIP 4400 and The Merge (Nimbus). Recording for 4400 is now available on Cat Herders YouTube, and we are hoping to get the recording available for Nimbus sometime later this week or maybe early this week. For next recording, we have it planned for Geth client with Marius and that meeting is planned tomorrow at 18:30 UTC, so if you are 
Interested to learn more about Geth client how it is going to behave after the merge and what is the progress on the merge testing so far, you may join us. The zoom detail will be provided on the cat herder’s general channel and for rest of the upcoming meetings you can check out the schedule. We have scheduled for almost every client to provide information about what that client is going to bring us after the merge.

### [Meeting notes](https://docs.google.com/spreadsheets/d/1axM1KaKc-GCcoPbAnYTOhgLnxXsBVoO5XRjTN3CLnck/edit#gid=0) and action items for ECH
[URL/URI standard working group](https://hackmd.io/@poojaranjan/URLWorkingGroup), meeting 3 [recording](https://youtu.be/83ZY5qrU5M4)
All Core Dev meeting [notes 134](https://github.com/ethereum/pm/pull/557)[16:09](https://youtu.be/wY-6H4EAws0?t=969)
Consensus meeting notes 89
EIP Improvement Process meeting 58
EIP editors apprentice meeting 19 [Recording](https://youtu.be/7hhXX2CfKzQ) 

Well that's it. Any questions so far? If not, maybe we can move on to the meeting notes. I believe all of the meeting notes are available, except consensus meeting 89 and EIPIP meeting 58, of which the scheduled note taker has responded that it will be available in next few hours. 

Other than that, we have recently started this URL URI standard working group. Yesterday we had meeting three for that. So basically this group aims to bring EIPs to final status. We are trying to work together with author, if they have similar proposals, and there are two proposals in active discussion EIP 2400 and EIP 4803. The recording is available on Ethereum cat herders Youtube and the next meeting is planned for July 11th. So if you are an EIP author with any standard proposed for URL and URI related, please try to join the next meeting. We would love to hear your feedback, thoughts, and see how we can progress and pushing good EIPs towards Ethereum standards. Most of the discussion related to this working group happens on cat herders discord channel that is EIP editors. So yeah, reach us and let us know what you think about this working group, and if there is any other suggestion for any similar kind of proposals, we can probably start thinking of having different meetings for that. 

So we have the recording from EIP editors’ apprenticeship meeting from last Tuesday and we are expecting the next one, one week from today. That's all on ECH updates. We are almost close to the last item, but before that, does anyone have anything to maybe share or ask any question?

## 5. Review of outstanding action items from previous ECH meetings [18:42](https://youtu.be/wY-6H4EAws0?t=1122)
[Meeting 85](https://github.com/ethereum-cat-herders/PM/blob/master/All%20Ethereum%20Cat%20Herder%20Meetings/Meeting%20086.md)

**Pooja**:
Okay, the guest for merge is Marius. He is a developer of Go Ethereum client. All right, so looks like it was a quick meeting for today, we are almost on the last item of the meeting that is the meeting notes from the last meeting, and only one item, William will create an issue to explain what help we need to need on the get a backup, looks like this is under control and…

**William**:
I did that even it's in the it's in the discord, like right after I met with them, I put that in the discord.

**Pooja**:
Okay, okay. Sounds good. Thank you so much. So yeah if you're interested to help out with GitHub action to create backup of ECH GitHub reach us. And that concludes everything on the agenda, if anyone has anything else to bring up any suggestion or any new initiative that they would like to take a lead on or help from cat herders…sweet. Then it looks like it's going to be a short meeting. Anyone planning for Paris? Eth Paris or maybe the Defcon? 

**Brent**:
They started selling tickets for Devcon yet?

**Pooja**:
I think so I think so let me check the link here I think they have I remember seeing prices that there are different prices available for different participants and people who are volunteering, it is free. There are no charges, and yes from June 6th, the tickets are being sold and the last date is June 30th. So if you are listening interested to go hurry up.

**Brent**:
I was initially planning but I’m not sure if I’m going to be able to make it this year.

**Pooja**:
Yeah, right. So anyone, if you are planning to join and you think that you can volunteer, tickets are free and for other, like if you want to participate in hackathon or participate as some different form there are different tickets available check it out the blog post and I have added link to the agenda. Well that concludes all our meeting today. It's nice to see you all. I hope to see you again two weeks from now. Have a good one rest of you.

**Brent**:
Yeah, thanks Pooja and everyone.

## Attendees

* Pooja Ranjan
* William Schwab
* Jose
* Metago
* Brent Allsop 
* Viktor
* Texas Farmer









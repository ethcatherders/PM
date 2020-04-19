# Ethereum Cat Herders Meeting 31 Notes


### Meeting Date/Time: Tuesday, 14 April 2020 14:00 UTC

### Meeting Duration:  45:04 min

### [GitHub Agenda](https://github.com/ethereum-cat-herders/PM/issues/116)

### [Video of the meeting](https://www.youtube.com/watch?v=6jtTJ9L5M2o)

### Moderator: Pooja Ranjan    

### Notes: Angela Gilhotra


# **Summary:**

## Decisions Made:

| Decision Item | Description                                                  |
| ------------- | ------------------------------------------------------------ |
| 31.1          | Ideal period for submission of a notes PR is 72hrs (3 days) but if PR is not received by end of day-5, someone else will be allocated to do that notes. |
| 31.2          | Take down the complete scam channel (instead of reporting) masquerading as EF |

## Actions Required:

| Action Item | Description                                                  |
| ----------- | ------------------------------------------------------------ |
| 31.1        | Move EIP 2515 to 'other proposed EIPs', and none of the EIPs to go in 'Tentatively Accepted EIPs' for now (until the next ACD call) |
| 31.2        | Tim to come up with a write-up on EIP2046 over the weekend   |
| 31.3        | Pooja to come up with a draft for Postmortem report for Berlin upgrade |
| 31.4        | Edson to write a draft blog describing EIP-IPs               |
| 31.5        | Hudson and Edson to reach out to EIP editors for the survey  |
| 31.6        | Edson to come up with a few examples of an advertisement by the end of this week or by the next meeting |
| 31.7        | Edson to come up with a few proposals for the advertisement on Ethereum StackExchange |
| 31.8        | Pooja and Hudson to work on bounty for Eth 2.0 note making. To follow up with Danny on one-time payout and tracking with Danny. |
| 31.9        | Hudson to move DAI to his public wallet. Tim to approve the transaction. (this week) |
| 31.10       | Hudson and Edson to work together on taking down the scam streamings of EF |
| 31.11       | Hudson to create an account (name: Ethereum) on twitch for streaming events and community calls |

# 1. Planning Berlin Upgrade

-  ECH Website Update
   -  Pooja suggested to add Upgrade specific information on the website
   -  [Shared](https://docs.google.com/document/d/1DA69jNqli7a4g_hEih52xpA5SrhvR-CC81lXnG9lhxQ/edit#heading=h.oh9ll8dsw4mb) word document to discuss other suggestions for the website update
   -  Need to make this live before Berlin upgrade
-  Update in Meta-EIP for Berlin
   -  Meta EIP has not been updated for a while
   -  Created a [PR](https://github.com/ethereum/EIPs/pull/2589), to update EIPs for Berlin upgrade based on ACD call 84
      -  Considering 5 EIPs, out of which 2 are in condition of 'accepted', 1 in under considerstion - EIP 2537, 2315, 2456, 2515 and 2046
      -  Two more, havent been finalized yet, which would require more clarity
      -  Hudson and Tim suggest, these EIPs that still require more clarity should be categorized in a different segment, and should not be considered 'tentatively accepted'
         -  Let's keep EIP2515 in other EIPs until the next meeting
      -  Change required: None of the EIPs go in the Tentatively accepted EIPs for upgrade
      -  Need to add EIP 2046
      -  EFI EIP isn't a good place to refer EIPs status - hasn't been updated
         -  **Pooja** suggests keeping a track of EIPs on ECH is a good idea since it takes a really long time to understand the current status of EIPs 
         -  Tim volunteers to update the EFI list
-  Writing in ECH blog about EIPs and their discussion, pros and cons
   -  **Brent** agrees, it would be nice to have a source of information
   -  **Tim**: Summarising an EIP can be hard
      -  summarising the pros and cons would take alot of time
      -  **Pooja**, taking information from sources like EthMagicians and putting it together in an understandable language
      -  It might be quite hard to do, but can be tried 
         -  eg., from the accepted EIPs there might be aritcles available (probably better than we could put together, eg., https://medium.com/@ralexstokes/what-eth2-needs-from-eth1-over-the-next-six-months-86b01863746)
         -  But then for EIPs that are technical we might need people researching into it before writing an article. eg., EVM subroutine (EIP 2046)
         -  Only concern is, it might get hard to articulate in a non-technical way, both sides of an EIP
         -  Pooja agrees. Explains the end goal is to use resources, tools, to make material available that isn't easily comprehended from the ACDs
            -  eg., In all ACDs, there is no clear summary of acceptance/rejection of EIPs. There is no consensus. 
            -  End goal would be to bring visibility to such things
         -  But, if the initiative seems complicated, can leave for later
   -  **Tim** suggests the post should not aim to be a discussion place, and should link to discussion forums (eth magicians) 
      -  **Pooja:** It would work as a support to ACD
   -  **Tim** volunteers to write something about EIP 2046 and get it reviewed by the original author, and can be seen where it can fit in the whole idea
   -  **Brent** suggests to use 'Canonizer'
      -  Works like a 'petition' - people can join and sign on a petition (or an EIP in this case). Viewable that how many core devs support it
      -  Trackable number of supporters with the changes made in the petition
      -  Work is in progress (Brent and Jim) to submit a proposal to EIP 1, wherein the responsibility is shifted to the author to build consensus around the community for/against the EIP
      -  Forums polarise people, with back and forth debates
      -  It is important to put out the information out there for the community in an understandable manner for them to be a part of it
      -  Currently, it seems like the core devs have complete control over inclusion of an EIP, which is not infact the case
         -  Something like Canonizer will underline this fact. What would matter would be community support
   -  **Pooja**: already requesting core devs but it is up to the core-devs to adopt Canonizer
-  Arranging a community call before the upgrade
-  Blogs (similar to what was done before testnets, mainnet) before the upgrade
   -  Suggestion for topics to include in the postmortem report 
   -  Likely contribution to these upgrades
      -  No response
   -  Can be discussed in other meetings

| Action Item | Description                                                  |
| ----------- | ------------------------------------------------------------ |
| 31.1        | Move EIP 2515 to 'other proposed EIPs', and none of the EIPs to go in 'Tentatively Accepted EIPs' for now (until the next ACD call) |
| 31.2        | Tim to come up with a write-up on EIP2046 over the weekend   |
| 31.3        | Pooja to come up with a draft for Postmortem report for Berlin upgrade |

# 2. EIP Improvement Process Meeting

## 2.1 EIP Procedure Survey Update

-  **Edson**:
   -  Survey responses: https://docs.google.com/spreadsheets/d/159PjJKNDOwSdwaZiLtX8_YetIp1hiHQNKT2ZnFSYmM0/edit#gid=1438532469, about 8-9 responses
   -  Some patterns showing up, but still require more responses to get a trend
   -  Next step is to share it with EIP authors
-  **Pooja**:
   -  Either Edson/some other volunteer, to write up a blog about EIP IP - end goal being to get the word out about EIP-IPs for the community
   -  Edson volunteers to write up a draft and open for edits/suggestions
-  Summary of the survey responses by **Edson**
   -  Current EIP process being too politicial
   -  Finality:  a hard yes/no is very difficult in the current state
   -  Coming to a consensus is difficult
   -  There aren't enough EIP editors compared to the high volume of incoming EIPs
-  **Tim**, suggestions for blog posts:
   -  Focus on getting the basic mechanics better
   -  Some EIPs cannot avoid debates, and are by nature controversial - to cater to such EIPs as well

| Action Item | Description                                                 |
| ----------- | ----------------------------------------------------------- |
| 31.4        | Edson to write a draft blog describing EIP-IPs              |
| 31.5        | Hudson and Edson to reach out to EIP editors for the survey |

## 2.2 EIP Content Migration

This agenda item wasn't discussed

# 3. Ethereum Cat Herders - Promotions and Positioning (in the Ethereum community) Initiatives

## 3.1 Placing Community Promotion Ads at Ethereum Stack Exchange

-  William not present
-  Questions posed by **Edson**:
   -  Target audience? 
      -  **Pooja**: Ethereum developers and project managers
      -  **Brent**: Anyone technical/non-technical, who wants to get involved, idea is to point them to ECH.
   -  Purpose?
      -  We need more developers at ECH
         -  For things like EIP-IP blogs, website development, etc.
      -  Other aim is to get involved in other EF projects as well - apart from note taking (eg., MakerDAO)
      -  Visilibility would help both ways, getting other projects and getting developers on boarded

| Action item | Description                                                  |
| ----------- | ------------------------------------------------------------ |
| 31.6        | Edson to come up with a few examples of an advertisement by the end of this week or by the next meeting |

# 4. Cat Herders Funding through Ecosystem Support Program & Moloch DAO

(This agenda item was skipped in the call, picked up at 42:53)

-  **Hudson**, having a call with the ESP team today about support and funding, updates after that
   -  depending on how things go, will be making another Moloch DAO request and/or look for other sources of funding

# 5. Events and Conferences

## 5.1 Consensus 2020 event participation update

-  **Pooja**: Shared the list with them, still trying to get another call. No updates/responses as of now.

# 6. Discuss and Close the ECH Issues/PRs

## 6.1 Renew Zoom pro account?

-  Payment has been made, nothing actionable here.

## 6.2 ethereum-cat-herders/funding

-  Tim sent out a bunch of transactions and Charles started adding in a spreadsheet
-  Confirmed that no other transactions are left for note-taking - but Tim suggests a follow-up since the spreadsheet doesn't look like it is 100% done. There might be some transactions left out.
-  If anybody has any outstanding notes, should comment on the issue
-  Official number for EIPIP note taking: 100 SAI

# 7. Review of outstanding action items from previous ECH meetings

-  Pooja, What should be the process for note-making and notes expectation deadline?
   -  Hudson, there should be an expectation of dates
   -  Pooja, until now the window was 72 hours
   -  Tim, Brent and Hudson agree on keeping the window shorter - which should be between 72 hours and 5 days. Post 5 days, the bounty is up for other people to take. - can post in the note-takers channel, for other people's opinion.
-  30.1: Edson create an image for ECH and work with William on placing Community Promotion Ads at Ethereum Stack Exchange
   -  Edson to get back about this soon
-  30.2: Create target audience specific survey
   -  Anyone to volunteer to create a draft for this
-  30.3: William talk to Lane about reclaiming the stake in dxDAO. Edson help with dxDAO dev contact.
   -  No update from Edson. William not present on call.
-  Hudson and Pooja will contact Scott about bounty for Eth 2.0 note making.
   -  Scott reverted that he could not place the bounty because he hasnt received the request from the team since January 9th
   -  Reuested Danny about what is the right thing to do
   -  We can create the bounty but since ECH is the receiving party it won't be the best way to do
   -  Hudson to discuss about this offline with Pooja. Essentially they have a pool of funds for note making, which can be tracked by us but they can do the payout
   -  Pooja suggests taking the payout upfront for x number of meetings - to get back to Danny about this. Reach out to Hudson if Danny doesnt reply by Thursday
-  Diversifying ECH fund: [Sai to Dai Migration](https://docs.google.com/document/d/1gT-T3RYDd3zxV82IFMejXo0mqpcy6n4-Tf48kj4bttA/edit) proposed by Charles
   -  Hudson to move Dai to his wallet this week
      -  To create first multisig transaction to move all the SAI to his personal wallet, Tim will approve it, a new github issue to track it
      -  Hudson to use his public ENS account
-  Edson to work along with Hudson on taking down scam streamings of EF
   -  Hudson currently behind on that. He has the documents from EF about what to do
   -  Problem faced: 
      -  Taking down those streams entail destroying people's channels that got hacked - which have their content on them
      -  One solution, but requires suggestions: reporting the accounts and leaving them alone, hoping they go away - just so people's content isn't destroyed
      -  Order of operations (explained by **Hudson**):
         -  A youtube account hacked by the scammers is used to send out defaming messages and content, trolling masquerading themselves as being a part of the EF
         -  Owner of the channel has lost access to it, and can't get back in, so they come to us for help
      -   Tim: if people have lost their access anyway and compared to the loss in funds the harm is bearable to remove a bunch of content
         -  In most cases it is just trolling, but in funds loss, yes, removing the channel completely makes sense
      -  Edson: Either remove all the videos or let the channel be as is.
      -  Better to take down all the videos then
      -  Edson to send out a list
      -  Hudsona and Edson to work together on this by the end of this week
-  Edson will create an account for streaming the events and community calls on twitch
   -  Hudson's update: name 'Ethereum' is taken, but Edson suggests it is available currently, since the account comes up as not taken. To be done by the end of next week.
-  ECH website update
   -  The document was shared and everyone is encouraged to keep adding content there.

| Decision Item | Description                                                  |
| ------------- | ------------------------------------------------------------ |
| 31.1          | Ideal period for submission of a notes PR is 72hrs (3 days) but if PR is not received by end of day-5, someone else will be allocated to do that notes. |
| 31.2          | Take down the complete scam channel (instead of reporting) masquerading as EF |

| Action Item | Description                                                  |
| ----------- | ------------------------------------------------------------ |
| 31.7        | Edson to come up with a few proposals for the advertisement on Ethereum StackExchange |
| 31.8        | Pooja and Hudson to work on bounty for Eth 2.0 note making. To follow up with Danny on one-time payout and tracking with Danny. |
| 31.9        | Hudson to move DAI to his public wallet. Tim to approve the transaction. (this week) |
| 31.10       | Hudson and Edson to work together on taking down the scam streamings of EF |
| 31.11       | Hudson to create an account (name: Ethereum) on twitch for streaming events and community calls |

# 8. Any Other Business

-  No other business/item for discussion.

-  The date for next meeting: April 28, 2020

## Attendees

- Tim Beiko
- Pooja Ranjan
- Hudson
- Edson
- Brent Allsop
- William
- Angela Gilhotra
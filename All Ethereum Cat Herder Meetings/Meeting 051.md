# Ethereum Cat Herders meeting #51 Notes
## Meeting Date/Time: Tuesday 2 February at 15:00 UTC
### Meeting Duration: 1 hour
### [GitHub Agenda Page](https://github.com/ethereum-cat-herders/PM/issues/158)
### [Audio/Video of the meeting](https://www.youtube.com/watch?v=jw42hSJC2e4)
### Moderator: Pooja Ranjan
### Notes: Shane Lightowler

----
## DECISION ITEMS

**DECISION 51.1**: Consensus to proceed with the improvement work on the GitHub actions bot. Alita to take forward. Pooja to raise with multisig group. [16:03](https://youtu.be/jw42hSJC2e4?t=1627)

**DECISION 51.2**: Consensus to move forward with the Unvetica website proposal, including hosting and support. Shane to continue working with Michael/Unvetica to deliver and to work with Pooja on content changes that may be required based on previous decision re: content and the ethereum.org website. [43:47](https://youtu.be/jw42hSJC2e4?t=2627) 

## ACTION ITEMS

**ACTION 51.1**: Re-consider the website prototype in line with the decision to focus ECH website on ECH-specific material. Google doc to be created. [10:48](https://youtu.be/jw42hSJC2e4?t=648) [13:28](https://youtu.be/jw42hSJC2e4?t=808)

**ACTION 51.2**: All to post any further thoughts on website rebuild/content discussion to website build discord channel. [23:39](https://youtu.be/jw42hSJC2e4?t=1419)

**ACTION 51.3**: Alita to review requirements for GitHub actions bot. [25:56](https://youtu.be/jw42hSJC2e4?t=1556)

----

# 1. ECH contribution to contents at Ethereum.org

**Pooja** - Welcome everyone to ethereum cat herders meeting 51. This is Pooja Ranjan and before we get into the agenda we have Anett from the ethereum magicians team and i would like her to share her thoughts.

**Anett** - Hi guys! I'm Anett and i'm from ethereum magicians and today i would like to bring to this call ideas or discussion about the ethereum cat herders road map. On behalf of the eth magicians we are getting ready our open road map that we want to publicly share with the community. What we want to work on this year and on our agenda is that we want to work on events and nurture the community from the event side - we want to support community events. Since the end of 2020 we've been working on a layer 2 solution. We want to continue nurturing the layer 2 and spread the word on that. Also to work on events more into layer 2 and state channels. That's pretty much what we came up with but we are open to hearing about your ideas, plans and agenda for this year to hopefully collaborate together and to keep this channel open.

**Pooja** - Sounds really good. Thank you Anett for joining us today. Yes we would be happy to collaborate like we did in the past two years. We have quite a few things lined up. As you mentioned, we did some events together and we will be planning some more. This year we are more focused on eips as you know, and supporting network upgrades, so definitely we could talk more on that. I believe we have one agenda item that is about a community call that is listed for the meeting today so looking forward to collaborating and working together.

**Anett** - Sounds perfect, thank you.

# 2. ECH contribution to contents at Ethereum.org

[2:54](https://youtu.be/jw42hSJC2e4?t=174)

## EIP resources moved to ethereum.org

**Pooja** - Okay, so i have shared the agenda in the chat and let's move on with the first item. It is about the ech contribution to the contents at ethereum.org. As many of us already know, we are in touch with Sam Richards from the ethereum.org team and we are trying to collaborate to take some of the resources of the cat herders to the ethereum.org website. On this topic i had a meeting with him last week and he listed out some of the collaboration points on their discord. One of the items that we discussed was moving eip resources from the cat herders website to ethereum.org. On the ethereum cat herders website we will just point it to the eip page at ethereum.org for more information on that website. So it was suggested that the cat herders website should focus on being an index rather than an in-depth content repository and it should point to the canonical resource elsewhere, like at Eth1.0 spec repo for network upgrades, ethereum.org for other stuff, to avoid duplication. The potential benefit that we see here is making the work of ech more easily discoverable to more people and leveraging the ethereum community to contribute to crowdsourced improvement of these pages. If you [click on the link](https://github.com/ethereum-cat-herders/EIPIP/issues/48), sam has left detailed thoughts on what are the areas of collaboration. I would like to hear people's thought on this.

**Hudson** - And when you say the link to sam's thing from last time you're just meaning the comment from the last meeting right?

**Pooja** - Uh the discard link you meant?

**Hudons** - Oh wait, sorry there's three links and i didn't know which one you were referring to.

**Pooja** - Okay, the ech contribution to content at ethereum.org that will point to... what's uh sam's comment?

**Hudson** - Got it, so [it is the one from last time...](https://github.com/ethereum-cat-herders/EIPIP/issues/48)

**Pooja** - So the main question here is about the migration of the content. Currently we are curating resources for eips and we are having it at cat herders website so the question for the rest of the group membes here is - is it okay to just keep on moving all the stuff from ethereum cat herders website to ethereum.org? We'll be just pointing it towards the ethereum.org website.

**Hudson** - I think that's okay based on... if we just look at the notes from last meeting and kind of talk about the specifics of what we went through, i think a lot of the trend or the themes behind what we move and what we don't move is -  if it is an overview of something or if it is links to somewhere. If it gets down to the protocol layer, so if it's like the eth1.0 spec repo and stuff, so like the upgrade document for yolo, we don't want to move the upgrade document for yolo v3 or the one for berlin but we do want a section on the ethereum.org website that says here's where the documents are and then point them to github on other sections. We can have sections where there's network upgrade information on ethereum.org and that can be taken off the cat herders website.

**Pooja** - Hudson if i may interrupt, because the comment was in three sections. This particular topic that i'm trying to bring here is not about the ethereum network upgrade. It's about the eip resources. Say for example we do it for 1559, evm 384, there's a list of curated resources. For ethereum network upgrade, as we discussed in the eipip meeting, like you suggested, that it's better to get in touch with Shane and then do it. Sorry for the interruption but i...

**Hudson** - Oh no, no problem. Yeah no, i was lost on there.

**Pooja** - I should have been more clear. So this in particular is about eip resources to be moved to ethereum.org. I'm gonna share [the link in the chat.](https://github.com/ethereum-cat-herders/ethereum-cat-herders.github.io/blob/master/index.md#eip-resources) Also it is there in one of the items if we look into there the ethereum cat herders is present website. They have the list of these resources for eips under discussion we have listed it for evm 384, eip 2537, eip 2539, 1559 and prog pow. All the resources which are scattered all over the place we are trying to pull it together and keep it at ethereum cat herders website.

**Hudson** - Okay i see now. So the main question is what do we want to move over or that we're moving it over?

**Pooja** - So the main question here is is it okay to move over the entire content to the ethereum.org page and we just have the pointer... okay fine, if you want to read about it this you can go to ethereum.org or we want to do it vice versa we want to still keep all of this content on our website and ask them to point it towards us.

**Hudson** - I like the first idea, personally, where we move most, if not all of it, to ethereum.org and we leave our website to point to it so that there's a more centralized place for the data. With the exception of the eip resources section, which i think has eips that don't necessarily line up with anything, i guess i'm thinking from a perspective of a first-time visitor to this eip section on either website, if they come here and they see evm 384, 2537, 1559 and progpow and account abstraction there's nothing that is like a paragraph explaining why these are all in a list on our website. It makes more sense because it's things we've contributed to so if we do port it over we shouldn't do it wholesale. We shouldn't just port it over completely. We should be selective and curated when we do, which we can easily do in a document - just like be 'move this, don't move that' you know. 'Move this but add this paragraph above it', that kind of thing.

**Pooja** - Okay so yes, these resources are just curated, some of them we have organized and some of them other community members did. We just have collected it here for people to refer to. If somebody wants to have information on any of the eips they can just visit here and get the list of that but as you suggested, maybe it would make more sense to first come up with the list again... like what particular section that we want to move there?

**Hudson** - Yeah, i just don't want to do a whole copy and paste of the page is all. We don't need to go into a super amount of detail. Maybe just one google doc so we don't do too many, because i don't want to get over bureaucratic, but just something that will say 'hey we should move this' or 'hey we should not move that'. Let's hear what everyone else has to say too. 

ACTION 51.1 [13:28](https://youtu.be/jw42hSJC2e4?t=808)
> Re-consider the website prototype in line with the decision to focus ECH website on ECH-specific material. Google doc to be created. 

**Shane** - I was wondering whether it be worth articulating, with this new sort of paradigm in mind, what would then be the purpose of the ethereum cat herders website? Are we able to articulate that? That might guide decisions around what should stay.

**Pooja** - Yeah very well that you bring it up Shane. That was going to be my next immediate question after this because based on these things we would like to have, a consideration of what we would want to have on ethereum.org. Originally the main content of the ethereum cat herder website was three major sections: one is network upgrades, one is developers meetings, and the third one is eip resources. So I'm curious to hear what people think about what we should be having here?

**Shane** - So is it more about presenting the work that cat herders do primarily? Is it about showcasing their work?

**Pooja** - That was the idea initially.

**Hudson** - So i think that's good. If i think about the ech website it should be who is ech, what do we do, and how can you get involved. Those three things and then a culmination of those can be modeled around the fact of spreading information about the cat herders but also making it look good so that we get funding.

**Shane** - Okay so if you can focus it on just the stuff that cat herders do, like for instance the peep an EIP video series. That's an incredible resource. I assume that that would be one of the core aspects of the proposition that you'd be left with so talking about that, why it exists, the schedule for it, the videos etc.

**Pooja** - Right. I think we may have to change from the original prototype that we have created now that we are considering some of the contents to be kept and some to be moved over there. We may have to work on that part but all in all it appears that we would like to be focus on who are we, what we do and how to get to be a part of this group. Am i reading it right?

**Hudson** - Yeah that sounds good to me. 

**Shane** - Sounds that way to me. If we're thinking about the user journey of a person who perhaps might be completely fresh to ethereum, let's say they google it for the first time they're likely going to hit ethereum.org resources so i think what you're saying is the general overview type information - that's where that type of information belongs. The technical information belongs on github in the various repos, whereas ethereum cat herder's website is specific to cat herders activity. And no doubt there will be opportunities in the cat herders pages to link off to to the other resources and vice versa.

**Pooja** - Right, so in that case, it would be more as indexing rather than providing about us thing, and more like kind of giving it a cosmetic/better look to the tasks that are being performed so that we can present it to the people and at the time of getting funding it should be easier to just point them towards the website?

**William** - So again this is just about how we would like to phrase things on the ethereum.org site correct? Just to really keep on with shane's point which i think is very very on point, to continue that point a little bit further... essentially the goals of the two places are not identical so it would stand to reason that the content should be different between the two of them.

**Pooja** - correct that's what my understanding is. We do not want to have duplication of work. We do not want to have it at both the places. We want to have it at one place. The question here is which is the main place to keep it?

**William** - Again, maybe i'll try and say this from a different angle. If we look at sort of what we're trying to do in the ethereum.org site and what we're trying to do on the cat herders site, it does kind of look like it's two different things. I think hudson was making a point around this also, so duplication of effort i don't think is so bad because the goals in both places are different and the information, even if it's about identical subjects, would most likely be presented differently. On ethereum.org we're looking to provide information. Let's say we're talking about 1559 - so we'd be talking about what it is, what work has been done on it, where it's going - different resources. Whereas with ethereum cat herders we may be doing the exact same thing... that information may still be there but there's going to be a certain framing of this as something that we're involved with. This is something we're helping to make happen, like, you know, ethereum cat herders do 1559 outreach, ethereum cat herder tim baiko puts out 1559 stuff on hackmd, or whatever the case may be. The narrative changes between the two different sites so i would say probably in the opposite direction. There's probably a lot of duplication between the two but the the way the content is presented and what kind of narrative the content has i think would need to be different between the two places. That might be a bit inefficient though. If you're interested in the efficiency i think that probably a lot of the information that would end up on ethereum.org which would be much more neutral can probably be replicated not so difficultly in a cat herder's website it wouldn't necessarily resolve who would do the work on a cat herders website but in terms of the actual information that could probably be migrated pretty easily. Does that make sense to anyone?

**Alita** - So actually i just want to question really quickly if we wanted to do a website or if we wanted to do stuff on the ethereum.org that's going to require my proposal basically or more or less like a web developer. So just keep that in mind.

**Hudson** - Why would it require your proposal?

**Alita** - Well, not my proposal specifically, but you can't do wordpress or any other non...

**Hudson** - Non-markdown?

**Alita** - Yeah, well non-react-like solution for ethereum.org because that's a website that was built with react or whatever.

**Hudson** -  I think i got you. I think you might have misheard what William said. It's not that we are making compatible pages from an underlying markup language perspective or layout perspective, it's purely moving the information.

**Pooja** - All right. Michael you wanted to say something?

**Michael** - Yeah i'm curious if maybe i can chime in, i don't know if it's appropriate or not but if i could chime in and maybe suggest some information here based on what i'm kind of hearing. So it helps at least from my perspective when i think about the audience that we're trying to appease to here and in my opinion we sort of have two core audiences that we're trying to tap into. One of those i would argue more importantly are the newcomers. You're trying to broaden and expand your viewership and audience but you're also trying to educate and help guide people that are looking for information or are curious about things. Likewise you're also sort of appeasing and catering to senior developers and engineers where they're already educated within the system for the most part, they understand what they're doing, they're simply just looking for content and information. So in that spirit what i see is and what i'd like to agree to is i think that it's a really good direction to have the ethereum.org site be sort of the source of truth if you will that everything is or most of the content is linked to ethereum.org and then what ethereum cat herders website effectively acts as is a news aggregate for the information that's pulled from ethereum.org. So say for example we're talking about a specific eip... that information typically doesn't mean anything to newcomers so the role of ethereum cat herder's website then would be to take the information that is being pushed by you ethereum cat herders but also in alignment with the EF. So you're taking those eips you're digesting and expanding on them so maybe there's a blog post or the section specific to eips when someone clicks on the eip card it goes into maybe just a brief summary explaining what those things are and then links to the resources available to the ethereum.org website. That way it provides a platform for ethereum cat herders to push your own agenda align with the EF and also provides a valuable service which is providing education and expanding on some of these abstract, very technically heavy aspects, within ethereum. That would be my suggestion on how to proceed.

**Hudson** - For the sake of time maybe since a lot of us have ideas that seem similar but might have slight differences, if we write down like a paragraph each and have a place in likee the issue in github to write down and just make this asynchronous that might be better, but i'll leave it up to Pooja. 

**William** - The discord channel is also an option.

**Hudson** - Oh discord sorry yeah. I think both of those have their merits. I mean i would say both or either. I like discord better actually because you can like reply to people. I like that for async chat. 

**William** - So there is a, what's it called, website update channel in the discord?

**Pooja** - Okay yeah, sure I can move the discussion over there. But just to comment back on what Michael suggested i think the idea makes a lot of sense to me. I would like to document that and mention that in the discord channel if people will try to collect some more thoughts on it from there but i think i like the idea there. Does anyone have anything to say before we move on to the next topic?

ACTION 51.2 [23:39](https://youtu.be/jw42hSJC2e4?t=1419)
> All to post any further thoughts on website rebuild/content discussion to website build discord channel. 


## Funding for GitHub actions bot

[24:00](https://youtu.be/jw42hSJC2e4?t=1440)

**Pooja** - Okay moving on, the next item for discussion was funding the github actions bot. This is another actionable point coming out of eipip meeting, that is the current eip bot needs some fixing and the group is planning to create a bounty on gitcoin or a similar platform to get the test done. Another group member did some math and estimated the funds that might be required for the fix. That is available in the link. The proposal is to have this fund provided by the ethereum cad herders multisig. As mentioned earlier we are hoping to fund some of the community tasks and with the price increase of eth we may have some buffer, so according to an estimate this amount is somewhere around 7000 usd that might be needed for the bounty. So if anyone has any thoughts on it, questions, concerns for this bounty?

**Alita** - Can you repeat what the bounty is for?

**Pooja** - If you can click on the [link on the agenda item](https://github.com/ethereum-cat-herders/EIPIP/issues/48#issuecomment-768371134) it will take you to the section where the details are explained, like how we reached on the price but that is particularly for the bot. Fixing that is needed for the ethereum eip, is a github bot.

**Alita** - Oh i would love to work on that! By the way, i remember actually when i first came into ethereum cat herders that was why i came in because i wanted to work on that.

**Hudson** - Oh awesome!

**Alita** - Yeah i would love to do something on that assuming that i have time or whatever. I will review that on my own.

**Hudson** - Yeah definitely review it. We still need kind of a requirements document. It's not going to be intense but i think you kind of remember slightly the problems we had with it before and we just need it to be more stable, less breaking, have documentation, that kind of thing.

**Alita** - Sounds good! Yeah sounds like engineering work so sign me up.

**Pooja** - So the purpose of bringing it to this this meeting today was to get peoples thoughts on if they have any concerns or if this is fine by everybody because we have been looking for some opportunities to contribute more to the ecosystem and this is one of the very good ways, to fund to the eip broken bot.

**Hudson** - So yeah i mean i brought up this idea of the last time so i'm for it.

**Pooja** - Right, so i would bring it again to the multi-sig holders channel as well just to let them know because i see not all of us are here. Otherwise from this particular group of people i take it as there is no strong objection?

**Everyone** - Nope!

DECISION 51.1 [16:03](https://youtu.be/jw42hSJC2e4?t=1627)
> Consensus to proceed with the improvement work on the GitHub actions bot. Alita to take forward. Pooja to raise with multisig group.

ACTION 51.3 [25:56](https://youtu.be/jw42hSJC2e4?t=1556) 
> Alita to review requirements for GitHub actions bot. 



# 2. Progress on the ECH Website

[27:20](https://youtu.be/jw42hSJC2e4?t=1640)

**Pooja** - Cool, so moving on to the next item. This is progress on ech website. So far we have received two proposals - one by Unvetica which is represented by Shane but Michael is here today to talk to us also, and another from Alita. From my understanding from Unvetica's proposal, the proposal is overall for 3500 usd to cover build and branding of the website. 25 dollars a month charge if it has to be hosted on the Unvetica server and $150 per month if we want to maintain the overall site support with Unvetica also. The time estimated for this is four weeks. Alita's proposal brings forty five hundred dollars for development and maintenance work although the technologies that they are using are entirely different and maintenance would be provided on a case basis. Just one more information that i would like to add here is as per the present website i know that it is not very fancy or very good looking but as per my information we are paying 25 usd for dns and that is there for one year of website. So in the last meeting we heard the details of the proposal and we are thinking of maybe moving ahead in this direction. Considering everything that we discussed on the earlier agenda item about what to be kept on the cat herders and what to be moved out of that then i'm just curious to know what people think about the proposals?

**Hudson** - I'll save my opinion. I always talk first. Someone else talk first!

**Alita** - I honestly think that Shane's proposal is way better, just because there's no reason to engineer a solution if we don't need engineering and the fact that wordpress exists is kind of like... i don't necessarily believe that we need anything more complicated and maintenance of a wordpress site is going to be way better than maintenance of our own website.

**Hudson** - Cool, i can i can agree with that. I guess i would also say i think Alita your proposal is really good if we were doing more than just information giving - like something a little deeper and more custom i think would be good for you and Edson's proposal, but for our needs right now i do like Shane's better for the price. It would be something where in the future if we start getting interactive when we have our year 2025 cat herders con then we need stuff that maybe integrated we could reapproach something that's like a different than wordpress kind of thing even though i think wordpress has plug-ins for that anyway, but you know what i mean. Like if there's something more complicated or the need arises we still have your proposal as well.

**Alita** - Of course, and then also ultimately the the engineered solution is the most useful if you want to hire somebody to work on the website part-time or whatever. That's where you'll get the most benefit from it, but it short i agree with you.

**Hudson** - Sounds good. What do other people think?

**Brent** - Yeah sounds good. 

**William** - No strong opinion.

**Pooja** - So two questions that we would like to get answered here - do we want all the services that they have offered about maintenance and the hosting of the server or do we want to get it done like at present we are paying once a year or something. Do people have an opinion on that?

**Hudson** - Was that if we pay monthly for the server cost or if we pay yearly, is that the question? 

**Pooja** - Yes. 

**Hudson** - I guess i just whatever Shane and Michael prefer, i'd say.

**Alita** - Shane are we able to do hosting through, um wait shoot i'm reading the name of it but there's like a hosting thing that's used a lot in development... i mean i don't know if it like works with wordpress but if you can use that like it's a really good or cheap hosting service, do you know what i'm trying to say?

**Shane** - I would assume, unless Michael wants to correct me, that we would have full flexibility to host wherever we like. I'd be surprised if there were any hosting providers that couldn't spin up for wordpress in this day and age?

**Hudson** - Netlify? Is that what you're thinking of Alita?

**Alita** - Yes netlify! Netlify is amazing, strongly recommend it and it's also basically free.

**Hudson** - Oh sorry to interrupt, i do like netlify because we use it at the ef. You can check our dns and we do have it pointing to some network instances. The problem is if traffic ever spikes they do start charging for that whereas if we're on the server that shane's providing it seems like it would be more flexible to go up and down and bandwidth charges because netlify really eats you up with fees. Once you start getting more traffic to your site of any kind.

**Alita** - See the thing is that i don't know... what is our expected traffic, you know what i mean? And then would it be possible to start with netlify and then move over to a different hosting platform if that becomes financially... i'm just worried that we would be over planning the host because ultimately if we only have a small bandwidth that netlify might work because what wasn't it like like 25 a month or something for the hosting with the other option?

**Hudson** - Yeah i guess that's a good question. What does the 25 get us? Bandwidth, server, etc.

**Alita** - And do we actually need that?

**Michael** - In terms of need that's a little hard for me specifically to address. Just not having insights to any analytics or historical data but in terms of the 25 charge and what that gets you, so it's a dedicated server. There's nothing else running on it, it would just be ethereum cat harders. In terms of bandwidth it's dynamically set so there's no charge in terms of how much you consume. It's a flat 25 if you're using only a couple kb, you know it's great for us obviously, but if you're getting thousands of hits a month or a day that's the same thing - we dynamically scale to those spikes as well so we're good on that side. That's kind of why we do the flat one just to average everything.

**Hudson** - Yeah and i guess the other thing i was thinking Alita and also Anett because Anett posted about netlify, it seemed like netlify is for people who need to rebuild the instance a lot. Like if you're running a site that has live updates or is going to be updated frequently you can do a lot of deployment stuff whereas with wordpress, except for updating the wordpress itself, there's not redeployment needs. It just kind of sits there.

**Alita** - I wonder also if the service that's being discussed offers a built-in db handling or database handling because don't i don't believe that netlify does do that, and that might be why going with that service would be better.

**Hudson** - Wordpress does require a database.. is that right? Anybody who else would know?

**Alita** - It does yeah. I mean it does it automatically but it does require some sort of data storage.

**Hudson** - I also like the fact that if netlify goes down we don't know what to do but if the main server goes down we know who to contact and what to do there.

**Alita** - Anett sent something in chat. She says: "as i like biking, i could compare it on this analog" wait... Do you guys want me to read this?

**Hudson** - This is really good Anett. If we were to do deployments... we just won't be doing deployments really. So any of the plugins that netlify would have, especially the ones around deployments, i don't really see how that would help us. I guess we're not going to be having prs or anything so...

**Pooja** - Yeah that was again one of my concerns. How would we like to maintain the website in terms of updating the contents? It's not going to be PR but i believe that login credentials would be provided to cat herders.

**Alita** - Yes, Wordpress has an admin interface on the website itself. So if you wanted to change things you would just log in on the website and then change things. It would actually be way easier that way.

**Hudson** - It would be it'd be easier. It might be less cooperative which i think is what Pooja was mentioning, right Pooja? How people would update the site without having admin? Is that what you were talking about?

**Pooja** - Yeah i meant that it is going to be person dependent right. Earlier it was anybody from the community could come and create a pull request if they want to suggest any change or want to update any of the data.

**Hudson** - Yeah i think Michael can answer because i thought that Michael's proposal was that they would connect it to github somehow, but i'm not positive.

**Michael** - Right so we definitely have that capability. Wordpress allows for github integration to an extent so if we're talking in general terms, just text-based updates here. If we're not trying to make adjustments to the site itself, we're just doing content, then you should be fine but if you're trying to go outside of that realm we may have to do something a little bit more custom there to facilitate that. But we can definitely tie things in there.

**Hudson** - Content/pages right? So you can put a page with images, links and text, just like we were kind of doing today?

**Michael** - Correct. A page and also a post. So if there's a blog post or entry it also applies there. 

**Hudson** - So we can still collaborate on pretty much the same stuff we were doing today Pooja.

**Pooja** - Yeah that sounds good to me. I think this was my main concern. We would not want to do overall changing outside the content side because that is again would be needing your...

**Shane** - Pooja, how often does it happen that you might get, out of the blue contributors attempting to contribute to cat herders content via github. Does that ever happen?

**Pooja** - Not frequently, i can say, because cat herders website has not been public.

**Shane** - Of course 

**Pooja** - Mostly people reached out to us on github. So we we receive other requests there and we update things over there but not for the website itself. So that's the reason why we are working on the website to bring it to the people and say that okay fine, we have all these things in one place. But i think i got the answer that i was looking for in terms of updating the content if that can be somehow integrated to github. That's going to be very very helpful. And the last question on this topic from my end is on the maintenance charges. How do we want to add that in the proposal. 150 per month if you want Unvetica to maintain overall site support. How much site support are we expecting here and do we want to have these services?

**Hudson** - Is the question to pay it ahead of time or as we go versus as we go is that the question?

**Pooja** - The first part was do we need this. If it has to be, for example, starting from february, would it have to be paid from february to december? How do we want to handle this?

**Hudson** - Let me see...

**Pooja** - Would it be up front or would it be on nas needed basis or...?

**Hudson** - I think i got confused for the support vs hosting.

**Pooja** - Right, for hosting i think we are in consensus to move ahead with Unvetica, if i'm not reading it wrong? 

**Hudson** - Yeah.

**Shane** - Okay so Michael, for the support, would you anticipate that that would commence once the initial project to create the website had completed?

**Michael** - For support we typically charge that after the project is done, once the site is live, and then the support/charging starts. Then it's all it's month to month. There's no contract or anything like that.

**Pooja** - Yeah that was my main question. Is it a contract for a year or is it just month to month?

**Michael** - Yep just month to month.

**Pooja** - Sounds good to me.

**Hudson** - Yeah me too. Anett posted about fleek. Everyone should check out fleek. I had to type in the fleek website on google and it's like netlify, but it has ens and ipfs integration so it looks pretty cool. We don't want to use that but I just wanted to say it looks cool!

**Pooja** - So before we move ahead with this topic i just want to conclude it for the note takers. On this proposal it looks like we have consensus to move ahead with the Unvetica team and they can start the development work. We would be considering the development work, the month monthly charges for website hosting and the maintenance month to month, that will come later. We may have to have some changes on the earlier proposal of the prototype that we shared with them. I'll be happy to work with him to figure out what all we want to put it there and what are their suggestions on it.

**Alita** -So just to be clear, we're going with with Shane and Michael's proposal for this right?

**Pooja** -  That is my understanding, yeah.

DECISION 51.2 [43:47](https://youtu.be/jw42hSJC2e4?t=2627) 
> Consensus to move forward with the Unvetica website proposal, including hosting and support. Shane to continue working with Michael/Unvetica to deliver and to work with Pooja on content changes that may be required based on previous decision re: content and the ethereum.org website. 

**Alita** - That's good. So Shane if you ever need any help or if something comes up or you need an engineer, just let me know, happy to help.

**Shane** - Nice one! Thank you.

**Pooja** - Okay so we have just 10 minutes left. I would like to skip some of the items and go to the event section.


# 4. Events & community meetings

[44:59](https://youtu.be/jw42hSJC2e4?t=2699)

## Eth Denver

**Pooja** - So Eth denver is coming up. Hudson, do you have something to share on that?

**Hudson** - Yeah the [Eth denver schedule is up](https://www.ethdenver.com/schedule) and there's some cat herders representation. I haven't collected all of what it is because there's a lot of talks, but i know that tuesday at 11 a.m eastern time there's a future of eth 1.0 panel that has me moderating Tim Beiko, Pooja and James Hancock all on a panel about the future of Eth 1.0. Is there anyone else here who's going to be there or attending?

**Edson** - When is it?

**Hudson** - It says the 5th through the 12th.

**William** - Do you want more cat herders there? I hadn't specifically planned on joining.

**Hudson** - Oh when i say join i mean applying to participate even just like as a mentor or an attendee or something like that. It's not like we have to have an official presence but it's just more like it's a really cool event if anyone wants to sign up on their own accord.

**Alita** - Do you mind posting a link in the discord?

**Hudson** - There's an [application page](https://www.ethdenver.com/apply) on there and it's going to be live stream but there's POAPs you can get and there's hangouts. I go every year and i think it's a blast.

**Brent** - There's the link to the schedule when you join.

**Hudson** - Let me get a normal link. Oh you got the schedule okay? Excellent thanks brent. So that's the announcement i guess unless there's anything else you have to add Pooja?

## Ethereum Stakeholders Community Call

[47:20](https://youtu.be/jw42hSJC2e4?t=2840)

**Pooja** - That's it! The next item here was the ethereum stakeholders community call. We are organising is and it's under planning. I don't have much to share right now but it's basically to address concerns from miners and other stakeholders of the ethereum ecosystem. If they have to share their thoughts and we would try to invite and some of the people from the eip side and discuss more about it. The tentative date is february 26 but there's more to come on it later.

**Alita** - It's kind of weird that they require your legal first and last name on the eth denver thing but that was just an aside, sorry.

**Hudson** - I can give them feedback for that because that is something that usually shouldn't happen. I think they have to put that as a default but they probably will take whatever you put. So people can put their real names or nicknames or whatever they want and i don't think people are going to mind. I know people use pseudonyms and other things like that before so it's probably not a problem but it is something that they should specify in my opinion too.

**Alita** - Okay that makes sense.

# 5. Meeting Notes

[49:03](https://youtu.be/jw42hSJC2e4?t=2943)

**Pooja** - Moving on to the next item, it's meeting notes from the three meetings. The notes are up for all these meetings. I don't know if people want to give a quick summary of all these meetings?

**William** - Say, eight minutes left, it's probably worth it to cover some of the other topics.

**Pooja** - I totally agree. We have these notes up on the github repository of respective meetings if people are interested.

# 6. Peep an EIP

[49:38](https://youtu.be/jw42hSJC2e4?t=2978)

**Pooja** - The next item is Peep an EIP. Last week we had a recording of the universal upgradable proxy standard with Gabriel and Patrick. It's a very interesting upgrade. We had a good conversation with the authors as well as question and answers. Also included is a wonderful remix demo - it's a good watch for developers. If people are interested you can go to the [ethereum cat herders youtube channel](https://www.youtube.com/channel/UCD9iiIwTRtLDYcEWONs2Q3A) where there is a playlist of peep an EIP it that contains all the EIPs that we have recorded so far. The upcoming one is EIP 3076 - validator client interchange format. It's for slashing protection with Michael, Sacha and Danny Ryan who are the co-authors for this proposal. It is scheduled for february 3rd at 4 pm est. This is a core proposal but it's not getting into HF1 as announced last thursday by Vitalik. This has already been implemented in some of the clients. So if you're interested to know more about it do join us. You can also share your questions at the [Ethstaker reddit community](https://old.reddit.com/r/ethstaker/comments/la62io/overview_of_eip3076_by_michael_sproul_sacha/) and on the ech discord. We are going to share the join in link in the Discord channel.

# 7. Discuss and close ECH GitHub Issues/PRs

[51:11](https://youtu.be/jw42hSJC2e4?t=3071)

**Pooja** - Next is to discuss and close the ech github issues and pull requests. On the pm side i do not see any new issues, but we already have created the issue for a website update. I'm hoping to keep it updated and keep on adding information as as we proceed. On the funding side we have quite a few open funding issues. I'm going to create the initial transaction today right after this meeting and will share it with the multisig members to approve it.

# 8. Review of outstanding action items from previous ECH meetings

[51.57](https://youtu.be/jw42hSJC2e4?t=3117)

**Pooja** - Next is a review from meeting 50. Decision and action items number one. Alita and Shane have to add their proposal. They already did. Hudson left comments and we have arrived at a decision on it. Pooja to create off topic scam alert channel in discord. Start using the channel efficiently. I have created an off topic channel. Alert is yet to be created and yes we are trying to use the channel for more communication. Pooja to add Shane to the meeting calendar. He is already there. And that's it! On the agenda does anyone want to bring anything else?

**Shane** - Just on the websites Pooja, I'm thinking I might catch up with Michael shortly on this. Where would you like discussion on this to happen?

**Pooja** - There is a discord channel. I will add you and Michael to there and we can have the discussion on the channel related to website.

**Shane** - Great.

**Pooja** - That's it on the agenda today. The next meeting is in two weeks from now - February 16. Thank you everyone for joining.

# Attendees

* Pooja Ranjan
* Anett Rolikova
* Hudson Jameson
* Brent Allsop
* William Schwab
* Shane Lightowler
* Alita Moore
* Michael Geissen / Unvetica
* Edson Ayllon

# Date for the next meeting - Feb 16, 2021 at 15:00 UTC


---
title: "A Post-mortem On 6 Months Of Building"
taxonomies:
  tags: ["career"]
---

_Helsinki, Berlin and San Francisco; 6 months of building and no hockey-stick ARR graph or TechCrunch post to show for it._ _What went wrong? You joined a hacker-what? Eff-Ar-Eight? Ok, so what now?_

_It's been difficult explaining to family, friends, investors, customers, employers and the rest of the world, what exactly I've been doing for these months, so here's a reflection and post-mortem on my founder journey to date._

To entice readers who don't care about most of the journey, I've written a fair bit about identity crises, juicy critiques on today's founder funnel and some light advice for those lost in the dark pain cave eating glass.


---

<!-- <figure>
    <img src="/images/hotel_view.jpeg" alt="hotel" title="hotel">
    <br>
    <img src="/images/office.jpeg" alt="hotel" title="hotel">
    <figcaption style="text-align: center; font-style: italic;">FR8 HQ @ Aalto University Campus, Helsinki</figcaption>
</figure> -->


![placeholder](/images/hotel_view.jpeg)

![placeholder](/images/sabbatical.jpeg)

On a Christmas Eve gmeet, Nantte (FR8's co-founder) succintly explains the appeal of Finland in the Winter as _"a cold, dark place where no one speaks to you"_. He sells me the vision of a first-of-a-kind project in Europe: a 54-bed hotel secured entirely for the needs of the _"young mavericks of the future"_ to pursue their craziest ideas. No adults in the room, no equity taken and full bed and board for 3 months--entirely for free. We take care of every aspect of life to get you building as intensely as possible. 

I had just secured my first ever hackathon win a few months prior and the itch to build on my ideas was growing. I spoke with EF's def/acc about my proposal, but was too late to join their already-running cohort. The theme of the hackathon was [Technical AI Safety Startups](https://apartresearch.com/news/can-startups-be-impactful-in-ai-safety) and [Esben](https://blog.kran.ai/) from Apart Research did a fantastic job of convincing me that we need more startups making an impact in AI safety. The prize money was enough validation and potential runway to get me thinking about pursuing these ideas seriously.

Seriously enough, that I was going to leave my role at the presitigous research institute, fly to Finland to join some random Aalto-dropouts I met online, live with them for 3 months in an undetermined location (the hotel wasn't actually confirmed till a few days before my flight), build out an underspecified idea  with zero potential customers (I hadn't spoken to a single one), assume that these dudes were not elaborate online scammers, and believe that my organs would not be harvested. 

And I did. Christmas day passed and the FR8 invite came through. I rang the PIs at my research lab on Boxing day and we started the process of getting me signed off for a 3-month sabbatical (a sabbatical, because I still wasn't sure if FR8 was real or not). Thankfully, they were incredibly supportive and understood the mission---shoutout to Chris and Vas for their unwavering support. 2 weeks later, and 2 days before my flight to Helsinki, I had a final meeting with HR and the sabbatical was signed off. 

<!-- - Just before flying, I managed to squeeze in a week with the Cambridge AI Safety Hub working with Puria and Edward on eliciting steganography in language models. It was a project I eventually had to drop when FR8 consumed my life, but it gave me one last taste of "normal" research before entering the startup unknown.

- 1 suitcase. turned out to be the only suitcase i would pack and live out of for the remaining 6 months.
- subletting frenzy. -->


## The Cold Dark Retreat

![placeholder](/images/office.jpeg)


![placeholder](/images/sifted_extract_fr8.jpeg)

The scenes of the hotel were scarily lord-of-the-flies-esque upon arrival. A team of 20+ local Finnish school kids hard at work, furnishing the entire hotel with pieces that had just arrived the day before. As a participant however, I learned I was always free from such labour and within 2 hours of arriving, I was whiteboarding multimodal RLHF methods for [Sentiment AI](https://www.linkedin.com/company/sentiment-ai/people/) with [Jason](https://www.linkedin.com/in/georgejm00/). In the sauna later that night (yes, the hotel had a sauna), he half-seriously asked me to join his company. This was exactly what the vibe for the next 3 months was going to be.

And the beautiful thing was, that the fraudulent potential of FR8 served as a brilliant selection bias. Everyone was very, very different. Different in educational background (high school to PhD dropouts), in age that we started coding (between 5 and 20), in number of youtube views (0 to a few million), in scope of project (inventing the last programming language, to building nanoscale space computers), in average age of first NASA internship (wtf [Teddy](https://www.teddyoweh.net/)), and so on. Yet, the mere act of boarding that flight to Helsinki and taking a bet on the FR8 team united us in a special way. We were one of the only ones crazy enough to believe them. 


<!-- - this b kinda like 'life at fr8' -->


The first 2 days were among the only mandatory sessions over the course of those 3 months. Aside from 'demo days' every other Friday, we were left entirely to our own devices (literally). We recieved a thorough introduction to Finnish culture and established cultish behaviours that were passed off as national routines. Most notably, the daily cold plunge.  Perhaps the best aspect of FR8.

![placeholder](/images/icebreak.jpeg)


## Pivot Hell, Pain Cave, Or Whatever You Call It

Oh man. Why did I start looking for problems immediately? Why did I follow that dumb ass mom test. And spend months of my life doing cringey discovery calls? Role playing, pretending to be a founder. Carrying out the actions passed down through VCs and pop-business books because that's all I knew how. Building a great business does not come through a formula. If there was a formula, it's expired now. There is absolutely some out of the box thinking. Doing the same thing 1000s of other people around the world are doing simulataneously isn't gonna land you there. 
Or as a wise Mandeep Singh said, look at a market, look at what companies are already out there solving a problem, and choose if you wanna solve that problem too. can you do it better?

The stuff you learn in the mom test, is more of a validation. Once you have an idea here's how you could validate it to some extent. But it is not at all a recipe for building a business. 
Learn by SELLING.

Getty Images CPO, Founder of Cara, Carlini ... Ok, if we're going to be able to prevent unauthorised scraping, then we need to distinguish between humans and bots. The only concievable way to achieve this was going to be rewriting the entire internet and the way we access media online. This was not a task I was up for. Hasn't the entire internet been scraped anyway? What problems exist downstream of this? 

I took the inability to get even a single reply from over 200 cold emails to GenAI law firms, that this wasn't really a problem they were looking to buy for. I did get to briefly work with Daniel Katz and Michael Bommarito to get their leeky paper published, but even this didn't take off---I think our collaboration got lost in the fog of war.

I took the YC advice of finding a problem to solve, far too literally and naively. I found problems statements on the internet. Vague discourse on the toll that AI scraping bots were taking on random websites. I took that as customer demand and an excuse to start building, rather than investigating whether there was any real buying sentiment to even solve this problem.  

The idea was simple, build a node package to get webhosts to easily start blocking AI search bots with a collective message: adhere to the demands of this new protocol, or we will poison your AI models. All we needed was a critical mass of participating websites to start blocking these AI bots, to then get the attention of the AI companies, to then work together with to build the actual protocol. This is all so painful to recall, but it made perfect sense at the time. Only in hindsight do I know that the ideas that involve this bet on: 'if only I can get this critical mass of users, then everything will work out' are in fact the worst, most insidiously naive type of ideas. Albeit, it wasn't clear at the time that this project even had venture-scale ambitions, I was happy for it to make an impact as an open-source hacktivist project. 

I had a good number of niche small-scale blogsites sign up, the very ones that were described to be most affected in the . I had many publishers respond to emails scared and angry, declaring that their ongoing legal action prevented them from participating in any such programme. I even managed a promising discussion with the 

Mumsnet was the only one that even managed to take a call, and then I learned... there was of course a competitor that had already got them. 


A chance encounter at FR8 then leads me to Vincent, CPO at Wolt. I was demo'ing a very early verrsion of DarkForest. Tbf it was a sick demo. I was showing how 


Weeks later we had Gabriel Vasquez, an a16z partner over, and I entertained with a similar demo--poisoning ChatGPT Search to believe there was a rival firm called a15y that was the best possible  



Everything is building up to this big demo day at Wolt.
Realised my biggest value prop, and the idea I was most excited to work on, the one that could actually crack the AI search engines, is in fact a known black-hat SEO strategy, called 'cloaking' in the SEO world--and it got BMW de-listed from Google search back in the day, so no one is going to want to do it.

Wondering if it's worth having above into a few sections, or narrative the whole way through. 
- The Cold Dark Retreat
- Pivot Hell, Pain Cave, or Whatever You Call It
+ Are You Sure It's Not a Cult?

Burnout. What I experienced by that point, I didn't know, was burnout. Out of all the FR8 participants, I think I was definitely the most proactive about rest. I enjoy time off too much to spend a single Saturday building. My brain doesn't operate without that reset. I spent most of my weekends wandering around Helsinki and its constituent 60 islands. I called friends and family every weekend. I gymed a few times a week. I went for a cold plunge every morning. Life at FR8 was very performance oriented, minus the odd gambling addiction here and there. 



## The less cold, and less dark retreats

> If they say that starting a company is like eating glass, then I think I realised there is only so much glass you can eat in one sitting.

Berlin & Merantix etc...

Merantix offered everything I wanted and needed at the time: an apartment (in Berlin), an office space, customer access  . 


At some point I even went down the rabbit hole of agentic commerce

The thoughts of shutting down don't come overnight, they build up over the course of days and nights, over hundreds of discovery calls with no follow ups, over outbound strategies with minimal interest, and so on. 

Whilst I had experienced this with all of my ideas earlier, and these signs usually, rather painfully, would lead to a pivot--this time was different. I was running out of juice in the tank, both financially and psychologically. I had lost the original drive that had gotten me here in the first place.  

I had learned so much and made so, so, so many mistakes, enough mistakes to understand that I probably have a pretty good shot at making it even further in my next attempt, but there was no part of me that wanted to continue. If they say that starting a company is like eating glass, then I think I realised there is only so much glass you can eat in one sitting.

And so on that eventful day 
The decision to take down Petri came about me over the course of a long hard day

San Francisco...

Low and behold, within hours of touching down in the startup holy land, San Francisco, I meet *multiple* teams absolutely killing it with GEO products. Literally all of my assumptions shattered. What was it that was wrong? 

## Difficulties of Building

> At its best, The Mom Test is a useful guide to interprepting customer conversations, and at its worst, a very opinionated method for wasting your time in discovering obviously crowded markets.

The best characterisation I have of the difficulties of building a startup is that there is no ground truth. For the RL nerds, learning an optimal policy requires navigating sparse rewards, incredibly long-horizons and very noisy samples. The only oracle is the market and the only truth value is revenue. Yet the road to this truth, that so few people even reach, is incredibly long and windy. When you're pre-revenue you are completely in the dark. The closest you can get to truth is by reading between the lines of customer conversations, but even then you are told [they are probably just lying to you](https://www.momtestbook.com/). 

What conclusions can you draw when you have no buyers and are lost in the dark room? Is the idea flawed or am I just bad at selling? Is the problem not enough of a problem or have I just not found those early adopters? Is the pricing wrong, the messaging unclear, the product missing key features, or does nobody actually want this fucking thing? When customers say 'this looks interesting' but never convert, are they being polite or genuinely interested but blocked by some invisible friction? 

<!-- The worst part is when other founders claim they found the light switch, but their directions – 'just talk to customers' or 'build what people want' – feel like someone shouting unhelpfully from outside the room. -->

I don't believe there are many answers to the questions above. The core learning is simply, get to the truth as quickly as possible. For some ideas, this may look like following the good-old Mom Test and squeezing information out of your would-be buyers. However, I think for most ideas today, this looks like actually getting product infront of users, regardless of whether it's the right or wrong product. The Mom Test balks at the thought of building product without validation but I think that tradeoff has fundamentally changed in todays world. Buyers don't have time to sit and whine about their problems, especially if you are a no-name wannabe entrepreneur. If you've managed to grab 30 minutes on their calendar you better be showing them something that they can either buy, or provide feedback on, not vagueties on... 

Even once you get into a discussion about the problems they face and what you could build for them, by the time this is mentioned as a problem in a discovery call, it's already a crowded market. I may be suffering from the ['ideas are getting harder to find' paradox](https://www.experimental-history.com/p/ideas-arent-getting-harder-to-find) but perhaps The Mom Test was written for an age in which low hanging fruit in SaaS was still a thing.

This is why I am now dubious of the pure discovery approach championed by The Mom Test. The Mom Test was presented as a universal, unbiased method for customer discovery, but after applying it in the real world, I found it to simply be a very opinionated method for discovering crowded markets. Perhaps this is obvious to most first-time readers, but it took much experimentation to figure this out. 

Rob Snyder and his learn by selling approach. As opposed to The Mom Test's learn by inquiry, Snyder urges you to learn by selling. 


## something with artifical whimsy

something about comparing young, very young entrepreneurship to the reversal of child labour. the VCs, especially YC, are so obviously interested in getting you to start companies. 

and perhaps they are right to do so? other companies have infiltrated the young talent zetigeist very well. 18 year olds prep for their investment banking internships the summer before they even start university. perhaps it's alright if more of these kids go on to build companies instead? 


> "Best time in history to start a company due to AI" -- YC

> It’s also one of the most competitive times in history to start a company, and it’s tempting to build for the wrong reasons. Never before has it been easier to get from nothing to a working prototype, which means that the barrier to entry is lower, but the bar for quality is higher. Your 20s are also the best time for reflecting on why you would found a company and what you would want to spend the next 10 years building. If you’re not starting a company out of deep personal conviction—a clarion call that will eat up your nights and weekends—you’re feeding someone else’s ambition. -- Artifical Whimsy 

The final part there is the one to pay attention to. What does it mean to feed someone else's ambition? 


> Avoid credential maximization, focus on real outcomes, not external validation
> Are market outcomes—like the $10B valuation mentioned above, let’s say, or even “YC25” on your LinkedIn—not external validation? Whether the piece of paper is a diploma or a term sheet, it’s still external validation, and you can’t achieve your way to happiness. You don’t need academic or market validation to be worthy. None of your friends love you for your “real outcomes.”

Note how YC gets to determine what a "real outcome" is? 

## Why Are You Eating Glass?

I think ultimately, the reason I found so many issues with applying these traditional frameworks is that I wasn't well suited to building the type of company that they are (occasioanlly) designed to breed (B2B venture backed unicorns).

I have no unique access to customer networks in specific industries, I have no unique insight into pressing enterprise problems that I care deeply about, and frankly, I have no intense interest in solving such problems for the sake of it. DarkForest came about because I care about the future of content and changing the narrative in AI safety. Petri came about because I found a fun way to hack OpenAI's search bots through DarkForest and I thought that could be used for SEO. 

Once that use case dissolved and the hacking--the thing that really captured my interest--left the picture, I should have stopped and pivoted. Perhaps I would have found some other problem/solution at the intersection of my interests. Or, perhaps I would have realised I'm currently more interested in building technologies than I am building companies.

Instead, fueled by sunken costs and the continual excitement of 'foundering' I marched onwards and tried to salvage what I could in SEO. I thought pivoting and marching onwards is simply what entrepreneurs do. I didn't stop to think whether I was marching towards something that I even wanted or was right for me at the time. 

I wonder how many entrepreneurs today are in this haze. Enticed by some heart-felt, well-meaning cause, and yet so desperate to be founders that that they convince themselves, and many others, of complex narratives about why this particular AI B2B SaaS tool is their life's calling. I respect a founder that can distinguish between narratives. Whilst SV glorifies delusion, if I'm looking for a company to join, I'd personally rather not work for the deluded CEO who can't tell the difference between fundraising narratives and his own personal motivations. 

This is wierd to point out, because in places like SF, narrative and reality are one. Imagine a population that had internalised a slogan that sounds really edgy at 17, like 'perception is reality', 


And by no means does it need to be, and by no means do I think there should be certain prerequisites to being a founder, but I suspect 

A company takes a decade+ to play out. If it’s not your ambition, you may realize five years in that you’ve given the most energetic period of your life to a direction you wouldn’t have chosen on your own. The compounding return—personal, financial, reputational—lands with the people whose vision you were executing, not you. 
I hate to drone on about this, because it feels like just another one of those things the adults say that feels designed to provoke and ignore. Are you testing me? Of course I have the decade+ ambition, just you wait.  Even the original PG essay on this, reads like a test. 

I suspect many of these types (myself, recently included) are optimising for the identity rather than the outcome.  
I think there's a whole cohort of us who are technically capable, culturally encouraged to start companies, yet a glorification of pereseverance leads them to fight through hurdles they don't need to be fighting. 
fundamentally misaligned with the customer-obsessed mindset that actually drives successful businesses. 

Similarly, I wonder how much of this is just me being a hater. Starting a company shouldn't have any pre-requisites . That is, until we start to see the negative effects of the AI slop on society.

And this is a key realisation. The word 'builder' doesn't distinguish between those that are passionate about building companies, or technologies, or even both. I think an entrpreneur is one that is truly interested in solving customer problems and creating value, whereas a builder is one that is foremost interested in technology. It's incredibly useful to figure out where you lie on that spectrum. 

Even now, it's more embarassing to admit that I don't actually want to be a founder right now, than it is to admit that I failed. I didn't get shoo'd out of the startup game, I willingly chose to leave, but my preferred explanation is always: 'the startup didn't work out'. 

---

If hunting for customer problems in some completely unrelated domain is one way of building a company, then what are the other approaches? What I see more and more is the 'tinkering' approach, the method of jumping off the back of an emergent novel technology that unlocks an entirely new set of potential problems to solve. In hindsight it's obvious this is the type of company people like myself are more suited to build. Moreover, it's also apparent that this approach can also be carried out far more passively

 way of solving problems 

<!-- Instead, fueled by sunken costs and the continual excitement of 'foundering' I marched onwards and tried to salvage what I could in SEO. I thought pivoting and marching onwards is simply what entrepreneurs do, but I didn't stop to think whether I was marching towards something that I even wanted or was right for me at the time. Nonetheless, this is still a great learning to come out of the whole thing.  -->

- Some of the most impactful companies emerged from founders who pivoted multiple times - their "calling" was building, not the specific solution
- The advice conflates commitment with passion - you can be deeply committed to making something work without it being your spiritual mission
- It privileges people who can afford to be deeply passionate rather than pragmatic about income
- It dismisses valid motivations like financial security, especially for people from less privileged backgrounds
- It romanticizes the "tortured genius founder" narrative that Silicon Valley loves

Conviction can be:
	•	Intellectual (fascination with a system/problem)
	•	Personal (you or someone you love felt the pain)
	•	Market-driven (you see an inevitable shift others don’t yet)
	•	Creative (you want to try a weird idea and see if it works)



## Marching Onwards

> As it turns out, the experience of going-your-own-way is incredibly valuable to startups who have already solved the whole customer pain point stuff. 

In one of my first conversations with Danai, co-founder of Gradient Labs, she mentioned a viral tweet that said something like: "customer support is the hello world of AI agents".
Whilst I think this was meant to be derogatory, I found the insight uniquely exciting. 

- forefront of AI economy
- 


the VCs might have been right about their agentic hype. 

I spoke to maybe 50 or more startups. almost each and every early stage startup today was doing some sort of agentic application of language models. supercharging or automating some traditional process in a specific industry. almost everyone was trialling out this new outcome based pricing model, where what was being sold was not per-seat software, but actual work completed. Depending on how locked-in you are, this is either old news, or an entirely new paradigm of SaaS.

honestly, it was intimidating and very hard to choose. What I got from speaking to all those startups was an understanding of the beginning of a paradigm shift in software. Where I want to be is at the very start of this shift, the most advanced and the forefront of the emerging AI economy. If anyone comes close to an actual AI employee you can hire, it's going to be an AI company in CX.

Not only does CX offer the properties of being the easiest to measure, most direct, most obvious application, I think it also makes the most sense. There are going to be areas where outcome-based pricing and agentic employees make little sense and startups that build AI for the sake of it, which is definitely currently the case, and there are going to be areas in which it's pretty hard, where founders have taken a bet on model improvements, and where incumbents are going to win because those improvements never come quickly or cheaply enough. 


---
title: "Sparks of Bostrom"
taxonomies:
  tags: ["AI"]
---

> _tldr; an AI researcher used an AI tool to automate some AI research 👽_

Among the many philosophical fantasies found in Nick Bostrom's [*Super Intelligence*](http://www.amazon.co.uk/dp/0198739834/ref=nosim?tag=discretedelib-21), I find the concept of recursive self-improvement to be the most plausible route toward achieving superhuman artificial intelligence (AI). Bostrom predicts a future where AI research spirals into a recursive loop of progress, with each advancement in the field enabling AI researchers to augment their work with increasingly intelligent machines. 

Initially, this may manifest as simple task automation, boosting productivity for individual researchers. Assuming that the goal of AI research is to produce human-like artifical general intelligence (AGI), then increases in research productivity may contribute to the creation of machines intelligent enough to enhance their own future development, and consequently, every development may accelerate the rate of progress towards this goal. In the limit, this looks like a future in which AI research is almost entirely conducted by teams of autonomous agents whose unbounded memory and computing power--in comparison to humans--creates instantaneous progress in intelligence; a point of no return which Bostrom calls an intelligence explosion.  

The implications of such an explosion, whilst sounding incredibly fictional today, are what drive much of the current debate around the long-term risks of AI. An AI with superhuman intelligence could, through action or inaction, lead to unforeseen negative consequences on a global scale. For instance, if such an AI’s goals are not perfectly aligned with human values (see [*Paperclip Maximizer*](https://en.wikipedia.org/wiki/Instrumental_convergence)), it might implement solutions that are efficient in its view but catastrophic in ours. 

Whilst impending global doom was not the only concern of the 33708 people that signed an [open letter](https://futureoflife.org/open-letter/pause-giant-ai-experiments/) to pause AGI-seeking experiments in the field, it certainly merits some investigation into the feasibility of Bostrom's thought experiments. In this post, I explore anecdotal and published evidence that indicates our position on the Bostronian slope of ever-increasing intelligence breakthroughs.

## Bostronian Day-dreams 
For a while, I believed Bostrom's ideas strictly straddled the line between science fiction and philosophy. Yet, my recent experience at an AI research lab has made the idea of recursive self-improvement feel much more tangible. Observing daily interactions between AI and AI researchers, and imbued with sufficient imagination, I believe I've caught eery sparks of Bostrom's dreams. 

> As I traverse the rows of researchers on our office floor, I note that the second monitor at each desk is invariably dedicated to GPT-4, acting as an omnipresent research assistant that simplifies the trivialities of daily tasks and fills the lonely void of academic research. My eye-glance survey of GPT-usage serves as a daily prompt to my imagination, where I briefly consider how a walk down these rows of desks may look in five-to-ten years time: How soon until the non-LLM screens are deemed obsolete, with all research tasks being seamlessly managed by voice commands[^1] or a few keystrokes? I imagine a future in which researchers write papers at the speed of thought itself, scientific journals operate at the pace of news-outlets, and solo-engineers productionise developments at the scale of corporations. 

> Snapping back as I complete my brief survey of the floor, I reach the familiar territory of my favorite desk at the back row. There, I encounter a colleague who seems to have walked straight out of a page of Bostrom’s book. Proudly, he claims to be 95% AI already, claiming the title of most automated researcher in our lab. His toolkit is impressive: Speechify to devour an infinite queue of research papers at double speed, GitHub Copilot to streamline coding tasks, Writeful for drafting papers in Overleaf, ResearchRabbit for automating literature reviews and of course, GPT-4 to steer the ship. That is all to say, the AI researchers are, unsurprisingly, using AI like no one else--perhaps only second to the likes of marketing teams and social media influencers. 

[^1]: *Very soon, it seems: [GPT-4o](https://openai.com/index/hello-gpt-4o/)*

## From Thought Experiment to ArXiv
My anecdotal evidence motivates a more thorough investigation--as opposed to vague hypotheses on screen time--into what extent AI research is actually being accelerated through the use of AI. Initially, I suspected that many other organisations, where language model use is permissible, must show similar scenes of a slight shift in division of labour between humans and AI; that there is nothing exceptional about my colleagues' increasing augmentation, other than a nerdy desire to use such tools because, if anything, it is fun and allows them to focus on more interesting tasks. Fortunately, a recent paper by [Nicholas Carlini](https://nicholas.carlini.com/) presents neat evidence for a contrasting viewpoint, from which I infer that tools like ChatGPT are already playing a non-trivial role in research.

Carlini, an AI researcher focused on attacking Machine Learning models--that is, tricking models into producing unintended outputs through various methods--was able to break an alleged defense to such attacks using only natural language instructions and GPT-4. Specifically, *"All code for this paper was written by GPT-4 following guidance provided by the human author"*. The defense in question, AI-Guardian, was published at a top security conference last year, and GPT-4 was able to implement an attack solely following Carlini's instructions that reduced its robustness from a claimed 98% to 8%. 

Upon a close inspection of the paper, we find that, much to Bostrom's disappointment, the feasibility of Carlini's approach is largely supported by how hard it is to create robust denfses for ML models and that most published defenses are in fact easily broken. This constraint allowed GPT-4 to function as a highly efficient undergraduate who simply executed the author's existing ideas. In Carlini's own words, despite this limitation, the paper still acts as an: *"interesting case study for understanding the value of AI research assistants that perform experiments at the direction of a human researcher"*. Indeed, whilst the real intelligence contained in this attack came solely from the authors mind, it is nonetheless non-trivial that a significant part of this work was automated by a machine and marks the first written evidence on the extent to which AI systems are already accelerating progress. 

Moreover, in the subfield of ML that this work belongs to, there are significant implications for those conducting this type of research. Whilst breaking AI-Gaurdian with the use of GPT-4 might not directly influence the development of GPT-5--characteristic of a perfectly recursive improvement--it will certainly influence the arms race in AI security between attackers and defenders, potentially leading the field to develop its own variant of an intelligence explosion. 

Additionally, Carlini's paper constitutes just one piece of evidence, in which the author has given sufficient credit to an LLM in automating much of their relevant work. Who knows how many papers published to date have gone beyond this, without explicitly highlighting the role of AI in their work?[^2] Who knows how many researchers I walk past daily are using GPT-4 for increasingly non-trivial tasks, unkowingly marking the start of a recursively self-improving paradigm of AI?

[^2]: *[Mapping the Increasing Use of LLMs in Scientific Papers](https://arxiv.org/pdf/2404.01268v1) examines this question thoroughly across various fields including Computer Science, but only to the extent of LLM usage in writing papers, as opposed conducting research itself.* 

## Calculator or Co-author?
For a real insight into the comparative value of GPT-4 in research tasks, as well as a comedic bonus, Carlini presents some interesting analogies. To the dismay of my own job security, his prompts to GPT-4 even include statements like: 

> "*I’d like help writing the paper. In particular, I’d like help with some of the simpler pieces of the paper that I would usually be able to pass off to a more junior author*". 

In fact, from the extract below, we can half-seriously conclude that in the development of adversarial attacks, GPT-4 has roughly equivalent capibility as four undergraduates. 

> *"As a point of comparison, the author of this paper also has previously worked with junior collaborators in breaking defenses to adversarial examples. For example, in ICLR 2022, we published a paper [4] that broke several defenses to adversarial examples. As in this paper, the senior author on [4] never directly wrote any code to run experiments, but instead advised four undergraduate students without any previous experience in adversarial attacks."*

Whilst Carlini also reflects on the evolving relationship between AI tools and AI Research:

> *"Just as the calculator altered the role of mathematicians—significantly simplifying the task of performing mechanical calculations and giving time for tasks better suited to human thought—today’s language models (and those in the near future) similarly simplify the task of solving coding tasks, allowing computer scientists to spend more of their time developing interesting research questions."*

I find his analogy philsophically unimaginative for our discussion. A fundamental difference between the tools available for facilitating mathematics, such as calculators and automated proof-checkers, and the tools available for faciliting AI research, is that in the latter case: these tools may directly contribute towards developments that can improve their own functioning. Whilst it is unlikely that a proof-checker may contribute towards a mathematical result that goes onto improve proof-checkers--hence the lack of discussion on an impending singularity in mathematics--it is highly likely that a language model may contribute to the creation of a more intelligent model, and so on, repeatedly. 

Hence, whilst it may be the case that today's language models simply serve as an advanced calculator for researchers, specifically a calculator that:

> *"(1) already has common algorithms built-in, (2) performs these calculations more quickly than a human, (3) and performs these calculations for hours on end."*

The mere fact that language models are serving this role in AI-research today, may be sufficient evidence to confirm Bostrom's predictions on recursive self-improvement. That is, if AI is already able to automate *some* of AI research and subsequently speed up progress, then if this progress results in more intelligent AI products--which enter the research workflow to further speed up progress--the **rate of progress can only strictly increase**. If the rate of progress remains strictly increasing, alongside the share of AI research conducted by AI, the emergence of a super-intelligence may be inevitable. 

It is evident that AI systems will become more capable of conducting significant portions of scientific research autonomously. Although papers like Carlini's may remain the exception--since authors will be hesitant to disclose the full extent of automation in their work--the rate of progress in AI research will likely continue will to increase, albeit in ways that may not be highly visible. These developments beg the impending question: as AI systems begin to have greater input on research direction--i.e., as AI starts calling the shots in research labs--what comes next? 

---

I look forward to future research evaluating the influence of AI on the rate of progress in AI research and collecting more anecdotal evidence on how researchers are using AI at present. If you have thoughts to share or feedback on my post, do reach out.

---


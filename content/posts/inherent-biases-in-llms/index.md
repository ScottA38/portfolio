---
draft: false
---

[Large Language models](https://www.cloudflare.com/en-gb/learning/ai/what-is-large-language-model/) (LLMs) are everywhere.

Referenced in the news, integrated into [your emails](https://workspace.google.com/intl/en_uk/products/gmail/ai/), cleverly finagled into [online customer support processes](https://corporate.flix.com/flix-tech/), shared in group chats or advertised on Youtube. _Spread on your toast_.

Every day, LLMs are advancing at a rate both astonishing and terrifying - generating responses with information of startling accuracy, producing wordings with marked emotionally tactility and being armed with increasingly up-to-date datasets to draw from. 

In the U.K, [surveys by the UK's Office for National Statistics](https://www.ons.gov.uk/peoplepopulationandcommunity/wellbeing/datasets/publicopinionsandsocialtrendsgreatbritainartificialintelligenceai) show a gradual but consitient optimistic trend towards A.I adoption, wheras a [worldwide independent survey](https://static.googleusercontent.com/media/publicpolicy.google/en//resources/ipsos_google_our-life-with-ai_2024_25.pdf) commissioned by Google reported that between 2023 and 2024, all major economic regions (and developing regions) witnessed at least an 8% increase in A.I usage.

Yet as many of us invite superintelligent algorithms into our decision making processes our lives, how can we keep ourselves accountable to overreliance and over-delegating key decisions in our private and professional lives? What cues can individuals implement to help them realise when they are _off-track_, _lost down a rabbit hole_ and have their _thought processes skewed from handing off their agency to technology? 

This article seeks to strip down the topic of A.I overreliance and help people understand potential risks.

<!--how can we be mindful that we do not offset our own decision-making authority through an overreliance on A.I tools? What subtle factors might be leading us astray in our quest to become more efficient in our work? The crucial term which is emerging in today's research into LLM's is that of bias - both from the machine and in our own minds.-->


### What's an LLM, then?

LLMs (i.e: [Large Language Models](https://www.ibm.com/think/topics/large-language-models)) interpret text written by humans (in their natural style of communication), input the text through a network of nodes in an algorithm known as a ['Neural Network'](https://www.ibm.com/think/topics/neural-networks) and ultimately provide a response to the presented problem question or statement based upon a set of computed probabilities, using a style of written output similar to that which a human might normally write.

LLM providers (such as [OpenAI's ChatGPT](https://openai.com/) or [Anthropic's Claude](https://claude.ai/login)) offer basic versions of their service for free, with premium subscriptions available for those who want to access a higher level of reasoning skill. They have fast response times, a high degree of accuracy, and provide highly relevant information within nuanced, detailed contexts.

LLMs, however, (like the human counterparts they mimic) are susceptible to a subtle but insidious detractor: bias.

### Define 'Bias'?

'Bias' derives [from the middle French](https://www.etymonline.com/word/bias) 'biasis', defined as "a slant", "a slope", or "an oblique".

> In the old game of bowls, it was a technical term used in reference to balls made with a greater weight on one side, causing them to curve obliquely (1560s); hence the figurative use "a one-sided tendency of the mind" (1570s), and, at first especially in law, "undue propensity or prejudice."

![A depiction of a 16th century game of Boules](./prometheus-unsplash.jpg)
_image credit: Emilia Hernandez on [Unsplash](https://unsplash.com/@carolinehdz)_

In the 21st century, however, most people would articulate bias in much more clinical terms, for instance:

> a systematic deviation from neutrality, arising from the subjective perspectives, beliefs, values, or agendas

_credit: [CLRN](https://www.clrn.org/what-is-bias-in-history/)

In most of the West today, Science (and by extension technology) inform a great many decisions we make. For the average citizen, Science often holds a great influence over what we do and how we behave, even if we are not directly aware of it.

As a macrocosm, then, Science shapes cultural perspectives within our culture, informing ideological shifts and informing the basis of many decisions we make. One of the perceived benefits of modern science it's ideals of objective truth - information which is exempt from skew or slant.

Let's continue further and explore the potential bias contributors which influence both humans and chatbots' ability to remain objective. 

## 1. Cognitive biases

Cognitive bias is characterised by an actor (human or otherwise), making decisions with systematic preference (either conscious or unconscious) towards a specific principle or ideology. More comprehensively it can be defined as:

> "...systematic tendencies leading
to error – such as the tendency to interpret infor-
mation in a way that confirms and reinforces pre-
existing beliefs and opinions"

General-Purpose Large Language models (such as [Claude](claude.ai)), generally utilise a underlying knowledge base comprised from batch-harvesting (['scraping'](https://www.nnlm.gov/guides/data-glossary/web-scraping)) information from vast swathes of the internet. Typically, a Large Language Model in itself has no jurisdiction as to whether or not a claim it synthesizes from it's dataset sounds reasonable without a , and will treat information within it's training set _as gospel_, unless an from the entirety of the web, a sprawling, labyrinthine spider's nest of interconnected information or data over which the model (the algorithm which actually generates the response) has no jurisdiction  


### A banal example

A purely mathematical stance on the concept of human productivity would lead us to believe that Large Language Models will automatically fractionalise production time on essential work tasks by diminishing the amount of human effort required at each stage of a given task or assignment.

To better convey this idea, let's present a hypothetical situation which exemplifies some of these characteristics. Using a _loose interpretation_ of the [GHERKIN](https://cucumber.io/docs/gherkin/reference) framework, let's present a concrete scenario where Large Language Models are used:

**TASK** 'Jeff' is assigned to produce a report on 'Current market trends within the commercial sector of Basketball Footwear' within the time-frame of 72 hours

**GIVEN** 'Jeff' has access to the internet: a _virtually limitless_ resource of information on _almost any_ topic

**AND** 'Jeff' chooses Large Language Models in order to produce the report

**WHEN** Jeff starts working on his report

**THEN** time spent planning the necessary components of the report will be reduced by a factor of A (Large Language Models have the ability to help users plan towards a specific goal and understand contextual markers in order to tailor guidance towards a specific situation)

**AND** time spent researching relevant informative materials to create the factual basis for the report will be reduced by a factor of B (Large Language Models are trained upon a huge range of available data, including resources such as academic papers written in highly sophisticated language)

**AND** time spent writing and formatting the report will be reduced by a factor of C (Large Language Models are able to respond to instructions to create bespoke documents based upon layered instructions and granular criteria)

**disclaimer:** This is definitely not a correct implementation of the GHERKIN method 🙂

This simplistic example presents an unambiguous picture of what _should_ happen when LLM tools are employed in the context of a real-world task. It is conceivable that 'Jeff' really does find himself outputting the report at an earlier date. But let's play devil's advocate for a moment with the _often highly unpredictable_ facets of the human mind.

#### Overestimation Bias

When we are presented with problem (i.e: producing a report), our highly complex, highly sensitive human brains are likely to produce a great many psychological distortions, for instance: if we are presented a task where the underlying problem we need to solve is rooted within Mathematics, and we believe ourselves to be good with numbers, we are very likely to inflate our estimations of how likely we will be to solve such a problem.

A famous precedent in psychological research mirrors this narrative: the ['Dunning-Kruger effect']. In 1999, researchers David Dunning and Justin Kruger of Cornell University in America, produced researche that in a general sense people inherently hold overly favorable views of their abilities across different domains.

Whilst the academic efforts of Kruger-Dunning exclusively addressed concerns of self-assessment within the bounds of a task in controlled conditions; my own forays into research on the psychological effect of Large Language Models came up fruitless in searching for identified psychological effects of LLMs upon our own assessment of academic ability, likely due to the relative infancy of LLMs as a techology. Despite the lack of supporting evidence, I strongly suspect this to be a significant factor in actual efficiency and effectiveness for completing tasks with A.I assistance.





of humans augmenting their cognitive abilities with the use of LLMs. I believe this effect to be dramatic in producing psychological distortions, especially within the realms of self-evaluation. I predict that this  augementing humans' natural intelligence with LLM capabilities. To me, this is a pressing 

But in a different vein, what psychological distortions can we expect when we estimate our abilities to succeed at a task when employing the assistance of a super-intelligent automated assistant, versus without one? What oversights and 

If left unnattended, these distortions can lead to dramatic lapses in judgement and ultimately oversight or failures in specific areas. One such distortion is known as 

Whilst the Dunning-Kruger effect focusses specifically upon existing competencies, I believe that our natural disposition to inflate our own abilities may be further skewed by the novel abilities of Large Language Models, causing us to mismanage time, over-analyse and 

 If we assume that Large Language Models are abundantly available and assumed to be used within the context of such a simplistic task, I believe that the innate psychological dispositions of humans will skew this picture significantly. As a result, here is a counter-proposition of the same situation I'd like to present to provide a more balanced view of a **real** humanistic reaction to 

For the avoidance of doubt, let's assume that we are talking about tasks within a professional context (i.e: tasks which humans **must** )
## 3. Inertia from abandoning existing ideas


## The fight for authenticity

To help illustrate why humans can _still_ write better than A.I, I would like to turn to the concept of ['Uncanny Valley'](https://www.britannica.com/topic/uncanny-valley) - a psychological phenomenon coined by Japanese Professor Masahiro Mori, who measured the emotional reaction of human subjects to the faces of progressively more human-looking android robots.



- Human writing is clearly distinguishable, because it has texture
- Well-crafted human can evoke intense emotional reaction, be it surprise, anger, disgust or sympathy
- ***Humans can be bolder***

hiring a human to produce you a logo, write up a blog post or to get the styling of your Website just right might seem costly and unimportant.

Certainly, a lot of highly 

Investing in human-led design and marketing shows your customer base that:

- You care about authenticity: you aren't content with just using machines to generate information about your services, values and ideals
- You seek to provide your customers with a unique experience, because you care about what you do and you want to go the extra mile
- 

It sends a clear message to your customers that you are willing to meet them authentically, treating them as unique individuals. In an age where chatbots have been assigned the task of invading the territory of Artists Investing in design created by humans shows that you truly care

To invest in the Arts in a time of political uncertainty is an act of grace - a token of acknowledgement that all too often the solution to our material woes as mortal beings all too often lies within the abstract.

Investing in the Arts as the World heats up

has given rise to tech CEO billionares hell-bent on training inspid neural networks to produce detailed parodies of human expression. 

If you are someone who (dares) waves the brush, inks the roller or produces a melody, Big Tech wants your resignation on the table by Monday morning.

In this time of political uncertainty and warped Investing in Art is an act of rebellion. A gesture of defiance. A 

At a time when chatbots can

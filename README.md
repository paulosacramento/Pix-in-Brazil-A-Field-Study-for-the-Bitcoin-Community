# Pix in Brazil: A Field Study for the Bitcoin Community

## Introduction
In November 2020, the Brazilian central bank introduced [Pix, a digital payment system](https://www.bcb.gov.br/en/financialstability/pix_en). As of this writing, 32 months have passed since its launch, and more than 140 million Brazilians have embraced it and have used it at least once. In this remarkably short time, [Pix has become the second most popular instant payment system in the world](https://investor.aciworldwide.com/news-releases/news-release-details/worlds-major-economies-playing-catch-widespread-adoption-drives).

What makes this development even more noteworthy is that it has taken place in Brazil, a country with a [substantial unbanked population](https://www.trade.gov/country-commercial-guides/brazil-finance). This success has been achieved against the backdrop of Brazil's challenges of poverty, social violence, illiteracy and poor infrastructure.

### Description

As a User Experience Designer and Researcher involved in the [Bitcoin Design Community](https://bitcoin.design/), this development caught my attention and raised the following research question:

_****What are the lessons that the Bitcoin community can learn from the Brazilian experience with the adoption of the Pix?****_

A trip to Brazil in August 2022 provided an opportunity to learn as much as possible about this fascinating topic.

Fluent in Portuguese, first-hand information was gathered from real users with diverse backgrounds. Upon returning to Germany, several months were dedicated to reviewing the data and uncovering meaningful insights.

The following chapters were written to approach such insights:


**Table of Contents**

-   [Introduction](#introduction)
-   [Chapter 01: The Big Picture](#chapter-01-the-big-picture)
-   [Chapter 02: Political Polarization & Asset Neutrality](#chapter-02-political-polarization--asset-neutrality)
-   [Chapter 03: Entrepreneurs’ Perspective - Part I](#chapter-03-entrepreneurs-perspective---part-i)
-   [Chapter 04: Entrepreneurs’ Perspective - Part II](#chapter-04-entrepreneurs-perspective---part-ii)
-   [Chapter 05: Fear of Violence & Wallets](#chapter-05-fear-of-violence--wallets)
-   [Chapter 06: Data Leakage & Scams](#chapter-06-data-leakage--scams)
-   [Chapter 07: Designing Contact Lists to Prevent Errors](#chapter-07-designing-contact-lists-to-prevent-errors)
-   [Chapter 08: Designing Payment Receipts To Prevent Fraud](#chapter-08-designing-payment-receipts-to-prevent-fraud)
-   [Chapter 09: Spending Habits & Different Methods](#chapter-09-spending-habits--different-methods)
-   [Chapter 10: The Role of a Trusted Friend for the Elderly](#chapter-10-the-role-of-a-trusted-friend-for-the-elderly)
-   [Final Thoughts](#final-thoughts)

Each chapter is divided into three sections:

1.  **Insights**  
    _What is the new finding from the field observations and conversations with participants?_
2.  **Facts**  
    _What additional data support and contextualize this finding?_
3.  **Recommendations**  
    _Now that this finding has come to light, how should the bitcoin community respond?_

### Motivation

The bitcoin community can benefit from this study in three ways:

**1: Gain transferable UX insights**

![](https://www.psacramento.com/content/images/2023/11/Screen-Shot-2023-11-10-at-18.10.52.jpg)

Source: [Lightning Nodes Channels World Map](https://mempool.space/graphs/lightning/nodes-channels-map) by [Mempool](https://mempool.space/)

Although the underlying infrastructures of these two systems are completely different (and in some ways, even opposite), from a user experience perspective, they have much in common.

This becomes clear when we consider that **both of them have a very similar set of features**:

-   Instant monetary transactions
-   24/7 availability
-   QR codes and aliases for payment initiation

At the same time, **both require the use of Internet-connected smartphone devices**.

These similarities allowed the formulation of concrete design recommendations that can be applied to a typical Bitcoin application.

**2: Learn more about other payment systems**

![](https://www.psacramento.com/content/images/2024/01/00-payment-systems.jpeg)

Source: [SEPA Instant Credit Transfer](https://www.europeanpaymentscouncil.eu/what-we-do/sepa-instant-credit-transfer)

The Lightning Network is not alone in the landscape of instant payment systems. Central banks of several countries have launched their own platforms, such as [Mexico's CoDi](https://bitcoin.design/) and [India's UPI](https://en.wikipedia.org/wiki/Unified_Payments_Interface).

Regardless of the entity (or community) that propels the payment system, both bitcoin and Pix are representative of the same mega-trend: **the abandonment of physical currency in favor of its digital equivalent**.

A better understanding of how Pix overcame some of the challenges to be adopted can shed light on bitcoin's path forward.

**3: Better understanding Latin America**

![](https://www.psacramento.com/content/images/2023/11/Latin_America_-orthographic_projection-.svg.png)

Source: [Latin America on Wikipedia](https://en.wikipedia.org/wiki/Latin_America)

  
Bitcoin remains a topic dominated by North America and Europe, where a significant number of companies and Open Source projects are based.

This phenomenon points to a potential knowledge gap regarding the Latin American scenario.

Hopefully, this work will help to fill such gap and provide insights of the unique traits and challenges of the region.

This research has the potential to increase inclusivity, foster global perspectives, and facilitate the development of more tailored solutions to address the specific needs of Latin American communities.

### Field Study methodology

![](https://www.psacramento.com/content/images/2023/11/Field_Studies_1.jpeg)

Source: [Field Studies on NN/g](https://www.nngroup.com/articles/field-studies/)

The [Field Study method](https://www.nngroup.com/articles/field-studies/) involves direct engagement with individuals in their respective environments, seeking to observe their use of the payment system in their daily routines. This approach, which emphasizes immersion in the users' natural environments, is preferred over exclusive reliance on controlled settings.

This method involved visiting individuals in their homes and workplaces to observe how Pix was integrated into their usual activities. By conducting a meticulous analysis of contextual interactions, a profound comprehension of the practical applications of Pix has been acquired. **This hands-on approach ensures that the insights generated are firmly rooted in the behaviors, mental models, expectations and fears of real people**.

**Reducing bias**  
Rather than starting with a pre-existing theoretical framework and deriving hypotheses from it, the Field Study methodology also allowed for the exploration and discovery of ideas directly from the data collected.

This investigative process has the distinct advantage of providing **in-depth understanding of the topic, through real-life examples and experiences, rather than solely relying on preconceived notions**.

In addition, the author maintains a neutral stance without any political leanings or affiliations regarding Pix and any political figures associated with its implementation. The purpose of this project is neither to praise nor to criticize the system. It is purely an analysis of this instant payment system from the perspective of someone who supports Bitcoin.

### Timeline

**Phase 1: Data collection, in Brazil**  
August and September/2022

Participants: 25 people  
Cities: Rio de Janeiro (State of Rio de Janeiro) and Viçosa (State of Minas Gerais)

This phase included tasks such as:

-   Conducting audio-recorded interviews
-   Using Pix to pay for products in stores and from street vendors
-   Collecting photos and videos
-   Using Pix to receive payments from family and friends
-   Making field notes of observations

**Phase 2: Data processing, in Germany**  
October/2022 to March/2024

![](https://www.psacramento.com/content/images/2023/11/Screen-Shot-2023-11-10-at-17.24.15.jpg)

Source: Author

This stage included the following activities:

-   Transcribing the voice recordings
-   Producing thematic clustering of transcriptions
-   Organising clusters around insights
-   Writing individual chapters for each one of the insights

### Limitations

This research is intended to provide a snapshot of a subject in constant change, which means that it does not aim to offer definitive answers or solutions, but rather a starting point for further exploration. As such, it is important to keep this in mind when considering the implications of the research and to approach it with an open mind.

### Privacy considerations

Due to the sensitive nature of the research on people's interactions with money, rigorous measures have been adopted to ensure the privacy and anonymity of the participants.

Protecting the identities and personal information of subjects is paramount to maintaining ethical standards and preserving their right to privacy.

Through the use of anonymization techniques and strict privacy protocols, all personal identifiers were carefully removed or replaced with pseudonyms throughout the research process.

### Human rights considerations

Latin America's reputation for an unpredictable political landscape and populist governments raises important considerations, especially in light of rumors suggesting Pix as a precursor to a comprehensive retail central bank digital currency (CBDC). Such a development carries the potential risk of Pix being used for strict capital controls and potentially violating civil rights.

In parallel, [the Brazilian Central Bank's announcement of its wholesale CBDC, called Drex](https://www.bcb.gov.br/en/financialstability/drex_en), adds to the complexity of the situation. While this aspect has significant implications, it has been deliberately excluded from the scope of this project to maintain focus on the intended purpose.

### Vocabulary

The term "Bitcoin" is to be understood as the broader Bitcoin/Lightning/eCash and other unmentioned Layer-2 technologies as a whole.

### Dedication

This project is dedicated to my father, who sadly passed away during the final stages of its completion.

He was the one who encouraged me to learn about computers from my earliest years.

Most importantly, his life example instilled in me the belief that technology should be used as a means to make a positive impact on the world.

### Acknowledgments

-   **Human Rights Foundation**: I am deeply grateful for the privilege of attending the [Freedom Forum Oslo 2023](https://oslofreedomforum.com/). This event not only broadened my horizons, but also gave me a deeper sense of purpose for this project. Engaging with like-minded individuals and visionaries at the Forum reinforced my belief in the potential impact of the initiative.

### Proofreading

-   Enedina Sacramento

### License

This content is distributed under the terms of the following Creative Commons license:

-   [Attribution ShareAlike 4.0 International (CC BY-SA 4.0)](https://creativecommons.org/licenses/by-sa/4.0/)

### Next steps


In the true spirit of open source collaboration, the same content presented in this post is available in a collaborative document that invites the bitcoin community to participate in a peer review process.

No log-in is required to edit the document, but please let me know if you make any changes:

- https://writemd.xyz/d/65ece0d5bf16c4215

This opportunity to review and suggest improvements will be available until the end of 2024.

The valuable input gathered will be instrumental in refining the work for publication as a book in the first half of 2025

___
## Chapter 01: The Big Picture

![](https://www.psacramento.com/content/images/2023/11/chapter-01-quote.jpg)
> **Anderson, the artisan** - "Now, with the Pix, even a person with little education can receive a form of digital money simply by telling someone their phone number."

### Insight

Observations and interviews with Brazilians revealed that, in general, **people have a positive opinion on the Pix payment system**.

When asked about the **reasons for adopting Pix**, these were the most commonly cited:

-   **Instant money transfer**: Pix transactions/payments are settled immediately, which is a significant improvement over legacy alternatives that could take several days to settle.
-   **Zero fees**: Pix transactions are free for ordinary people, which is a great incentive to make transactions with the system. A few users mentioned that they would discontinue utilizing Pix in case fees for individuals were introduced.
-   **Easy of use**: Pix payments can be initiated by using a predefined alias (also known as ‘Pix key’) or by scanning a QR code linked to the beneficiary's bank account. Pix is described as easy to use, even by people unfamiliar with technology.
-   **Broad acceptance**: Pix has been described as a widely accepted and convenient method.

When participants were asked **how Pix had impacted their lives**, these were the most frequently mentioned aspects:

-   **Preferred method**: Pix has become their preferred way to both receiving and making payments.
-   **Improved procedure**: The implementation of Pix is objectively considered an improvement over the previous methods for money transfer. This can be mainly attributed to the added convenience.
-   **Increased income**: Merchants and self-employed individuals reported increased income from their business activities after they started using Pix.

When questioned about the **potential disadvantages of embracing Pix**, a recurring concern was that it **could be used by criminals** for illegal activities (scamming and kidnapping for ransom).

### Facts

Changing the way people interact with money is a significant challenge.

This can be even more difficult when a country's recent history has been marked by a period of capital controls.

![](https://www.psacramento.com/content/images/2024/01/chapter-01-plano-collor.jpeg)

The image above is a front page from the Brazilian newspaper "O Globo" reporting on a historic economic event in Brazil. The headline "Collor bloqueia o dinheiro" translates to "Collor blocks money". This refers to a measure taken by then-President Fernando Collor de Mello, known as the "Plano Collor" (Collor Plan), in which the savings accounts of the population were severely restricted and frozen for 18 months.

In the 1990s, the [Brazilian government took the measure of freezing saving accounts in an effort to combat hyperinflation](https://pt.wikipedia.org/wiki/Confisco_da_poupança). This event had a profound impact on the collective consciousness of the population and left an indelible mark.

In other words, Brazilians could have had some serious trust-related reasons for rejecting Pix

But that did not happen. **Why**?

At first, one can imagine that the acceptance was exclusively due to its features. It is very difficult to resist the convenience of being able to make instant feeless payments.

However, if we take a step back, **we will be able to see the importance of examining this phenomenon from a socioeconomic point of view**.

To understand the reception of Pix, we must consider not only its functionalities, but also the social and economic aspects of Brazil that contributed to its diffusion.

Thus, let us look upon some of the socioeconomic factors that have contributed to the spread of Pix in Brazil:

**High mobile penetration**  
Brazil has a large and young population with access to smartphones, which serve as a critical tool for the use of Pix. The majority of the population owns and actively uses smartphones, making digital payment solutions accessible to a wide range of individuals.

**Pervasiveness of the informal economy**  
Brazil has historically developed a large informal economy, with a significant portion of transactions taking place outside the traditional banking system.

Pix provides a convenient and accessible digital payment solution for both formal and informal transactions.

It enables individuals and small businesses to more easily participate in the formal economy. Indeed, this means that the integration of this new payment platform helps them to operate as registered businesses and have access to essential financial products.

Several merchants also indicated that the motivation for the adoption of Pix was keeping up with the needs of their customers. In other words, the use of Pix was described as a matter of business necessity to ensure revenue.

**High social connectivity**  
Brazil has a high level of social connectivity, and a significant portion of the population actively uses social media platforms and messaging apps. This is evidenced by the fact that Brazilians spend the highest amount of time per day using their smartphones.

This connectivity promotes the rapid spread of information and facilitates the adoption of new technologies such as Pix.

**Government driven digital transformation**  
The Brazilian government created both the technical and legal framework for Pix. The government actively promoted and encouraged the adoption of the Pix system and provided the right incentives for different participants. Furthermore, the government used communication channels to educate the public about the benefits of the system.

However, this can be applied not only to Pix. The government has also proactively digitized public services. An excellent illustration of this is the provision of over 5000 public services to citizens through an online platform.

**In a nutshell**  
Pix's explosive growth in Brazil can be attributed to the synergistic convergence of two critical factors.

First, the country's population has a high level of connectivity, with widespread use of smartphones and Internet access.

Second, Brazil's economy is characterized by a significant informal sector, in which a substantial portion of the transactions take place outside the formal banking channels.

A significant proportion of the population lacked access to banking services and were in need of easily accessible and efficient payment solutions. This void was effectively filled by Pix.

These elements have contributed to Pix's impressive growth, which has established it as a popular payment option for both individuals and businesses throughout the country. Soon after its release, Pix became the most widely used payment method among Brazilians.

### Recommendations

**Focus on the positive aspects**  
It is important for the Bitcoin community to consider both the strengths and weaknesses of fast government-backed payment systems. Instead of focusing on the risks of surveillance and capital control, it is important to recognize the potential benefits that such systems provide to the daily lives of individuals and businesses.

**Build bridges**  
Bitcoin companies should seek integration with government-supported payment systems instead of perceiving them as a threat. Pix has opened doors for innovative businesses and new competitors. The growth of neobanks and fintechs clearly exemplifies this phenomenon. Bitcoin companies can profit from this new environment. [Bipa](https://bipa.app/), with more than 50 thousand accounts opened, is a perfect example of this concept.

**Look towards the future**  
It is crucial to evaluate the long-term ramifications of rapid payment systems on individuals' perceptions of digital money. Individuals who make day-to-day payments using a smartphone may find it easier to accept bitcoin than individuals who grew up in the cash era. People's familiarity with smartphone-centric transactions is expected to reduce reluctance to use alternative forms of money, such as Bitcoin.

___
## Chapter 02: Political Polarization & Asset Neutrality

![](https://www.psacramento.com/content/images/2023/11/chapter-02-quote.jpg)
> **Felipe, the vehicle registration agent** - "Pix is just another scheme by this criminal president for the enrichment of his friends."

### Insight

From the very beginning of my conversations with Brazilians about Pix, a clear trend among the population became evident. **The introduction of Pix was closely linked to the Brazilian president at that time, Jair Bolsonaro**.

This association between the two seemed to contaminate public opinion about Pix. This led people to form opinions about the payment system based on their views of the political leader, rather than solely on the merits of the new financial platform.

### Facts

Brazil is notorious for its political instability. However, the release of Pix in November 2020 occurred in a particularly turbulent time.

Back then, [the country was dealing with the polarizing presidency of Jair Bolsonaro, the COVID-19 pandemic, and its economic repercussions.](https://carnegieendowment.org/2021/02/17/brazil-s-polarization-and-democratic-risks-pub-83783)

Given such a scenario, it is not surprising that the public's perception of Pix was influenced by its association with a particular political group. This association caused people to develop biased opinions about the system.

For example, participants who opposed the Bolsonaro government expressed skepticism about Pix. The opposite was also true, as participants who supported Bolsonaro consistently reported a positive view of Pix. Both sides used popular political narratives and alluded to hidden agendas to defend their views.

Bolsonaro's supporters regarded the system as the president's attempt to fight the political establishment and take power away from the greedy bankers.

Bolsonaro's critics, on the other hand, argued that the Pix system was just another way for the president to enrich himself and his allies.

### Recommendations

**Expect the pattern to repeat**  
Bitcoin is a politically neutral asset because it is not controlled by any central authority. It is also considered a commodity from a regulatory perspective and is traded around the world.

However, if/when bitcoin is introduced as legal tender in another country, it may be characterized (by the population of that country) as the asset of a particular political party or individual that promotes its introduction.

In other words, part of the population may assume that there are questionable intentions and a disguised political agenda that supports the initiative.

[This is exactly what happened in El Salvador, the first country in the world to recognize Bitcoin as legal tender](https://www.youtube.com/watch?v=ig3UN1GYmY8).

**Educate**  
To combat such misconceptions, education is crucial.

It is essential to support the uninformed population on the subject. Various forms of educational initiatives must be provided with relatable experiences and accessible explanatory material about the properties of bitcoin. This will **help people distinguish between the properties of bitcoin as an asset from the political process by which this asset is being integrated into society**.

___
## Chapter 03: Entrepreneurs’ Perspective - Part I

![](https://www.psacramento.com/content/images/size/w1600/2023/11/chapter-03-quote.jpg)
> **José Luiz, the ice cream seller** - "My experience with Pix has been very good because now I don't have to worry so much about change. When customers want to make a larger purchase, I don't have to worry about having small bills for change."


### Insight

A considerable amount of time was spent talking to typical Brazilian entrepreneurs, from street vendors to small business owners with multiple employees.

The first and most superficial takeaway from the conversations is that, in the beginning, **customer demand was the primary driver of Pix adoption**. If customers repeatedly ask to pay by means of a certain payment method, it is a no-brainer to do whatever it takes to make it possible. It is a matter of keeping your business alive.

However, further conversations revealed some **unanticipated benefits**:

1.  The **ease of accepting electronic payments using their own smartphones**, thus eliminating the need for additional costly and fee-charging third-party devices. This is the case if they want to accept other forms of electronic payments, such as debit/credit cards.
2.  **No need to have change** (coins or smaller paper bills given back to a customer when they pay for something with a larger bill), a common problem when dealing with cash.

### Facts

**These insights can be explained by the unique Brazilian social and economic scenario.** The country's economy is deeply intertwined with a large informal labor sector, much of which relies on small-scale services provided by private individuals.

This informal sector is a vital engine of economic activity and livelihood for many people. This particular context helps to explain why the benefits mentioned above were such strong drivers of the use of PIX among entrepreneurs.

> The first case of COVID-19 in Brazil was announced by the Ministry of Health on 26 February 2020. Two weeks earlier, the Brazilian Institute of Geography and Statistics (IBGE) had published data from the National Household Survey (PNAD) reporting that **around 38 million people in Brazil work in the informal sector**.
> 
> **In eleven out of the 27 Brazilian states, more than 50 per cent of workers belonged to the informal sector** and, therefore, do not enjoy the benefits of the protective labor laws.  
> \- [LSE Latin America and Caribbean blog](https://blogs.lse.ac.uk/latamcaribbean/2020/06/03/the-impact-of-covid-19-on-brazils-precarious-labour-market-calls-for-far-reaching-policies-like-universal-basic-income/)

![](https://www.psacramento.com/content/images/size/w1000/2024/03/chapter-03-pos.jpg)

Business owner holds a Pix-enabled POS device. Source: Author

By enabling self-employed individuals to accept electronic payments directly through their personal smartphones, Pix provides an accessible, fee-free alternative to traditional debit/credit card payment terminals. This resonates particularly well in a context where minimizing operational costs is critical to the sustainability of small business activities.

In summary, **Pix allowed business owners to accept a new highly sought-after form of payment, save on fees and do it all using a device they already owned**.

![](https://www.psacramento.com/content/images/2023/09/PXL_20220815_134802777.jpeg)

'We reward with 5% anyone who brings R$0.10, R$0.25 and R$0.50 coins totaling amount over R$20.00. Note: Temporary promotion. The Management'. This poster at the entrance of a bakery illustrates the shortage of coins. Source: Author

Moreover, the appeal of Pix goes beyond convenience. It also addresses a common concern for merchants by reducing the burden of managing coins and small bills, a serious problem for any business in Brazil, regardless of its size. [This is a problem faced by 61% of merchants in Brazil](https://www-infovarejo-com-br.translate.goog/desafios-do-troco-no-varejo/?_x_tr_sl=pt&_x_tr_tl=en&_x_tr_hl=en&_x_tr_pto=wapp).

### Recommendations

For those involved in a Bitcoin project or business, it is important to realize that some of the unforeseen benefits of Pix can also be extended to Bitcoin.

Similar to Pix, Bitcoin transactions can be made seamlessly by using existing smartphones, without the need for additional payment devices. Lightning fees are also negligible, which is also relevant for businesses.

In addition, expanding the range of electronic payment methods reduces reliance on cash. **Alternative payment methods reduce the need to handle paper money and the burden of maintaining a supply of small change for customers who pay with high-value bills.**

These aspects are often neglected, but they are common and pressing issues for entrepreneurs of all kinds. **Do not forget to communicate these benefits to potential prospects.**

___
## Chapter 04: Entrepreneurs’ Perspective - Part II

![](https://www.psacramento.com/content/images/size/w1600/2023/11/chapter-04-quote.jpg)
> **Luiza, the hairdresser** - "Now that I use Pix, money comes in faster and goes around faster."

### Insight

Entrepreneurs reported that a significant share of both incoming and outgoing payments were made using Pix.

Most importantly, **they reported significant positive business improvement due to the adoption of the PIX system, including increased sales, booking and profits**.

### Facts

![](https://www.psacramento.com/content/images/2023/09/PXL_20220808_202015420-1.jpeg)

__‘The whole process of acquiring this vehicle that I am driving was carried out digitally. I submitted all the documents, filled out the forms digitally and never set foot in a bank branch.’__, the taxi driver in Rio de Janeiro told me. Source: Author

From the perspective of the entrepreneur, it seems that the positive financial effect of Pix goes beyond offering a new, additional payment method to clients.

**Participants consistently described the ability to spend money received electronically without converting it to cash as positive.** This seems to be the positive systemic impact of Pix. Suddenly, **money flows without friction**, which increases the efficiency of business activity and offers individuals multiple options.

Finally, it must be highlighted that this upgrade should not be analyzed in isolation. It is also important to consider that it is part of an overall digitization process that has lowered the barriers to integrate previously excluded participants.

It seems that the **Brazilian Central Bank is indeed achieving its goal of making the banking system more inclusive**. In this sense, Pix can be regarded as part of an overall effort to modernize the country's banking infrastructure.

### Recommendations

For obvious reasons, the Bitcoin community is biased towards a negative view of government involvement in money matters.

However, it is also important for the community to consider the glaring benefits of payment systems like Pix, if that is indeed the case.

When ordinary citizens obtain more money out of their activities and have access to additional financial services, they can enjoy significant advantages. **The community should not ignore any kind of similar initiative just because it is government-sponsored**. Sometimes, the benefits can outweigh the risks. It is important to carry out a careful analysis and fair assessment of those risks.

___
## Chapter 05: Fear of Violence & Wallets

![](https://www.psacramento.com/content/images/size/w1600/2023/11/chapter-05-quote.jpg)
> **Ernesto, the barber** - "Using Pix means we carry less cash, so it is a personal safety improvement. It is safer to walk around with less money in your pocket."

### Insight

Participants frequently described **carrying cash as personal security vulnerability**. In other words, they claimed to feel safer when they carried no physical money in public places during their daily activities.

Pix was considered an improvement in this regard. **Being able to pay for purchases without having to carry cash is perceived as a positive** aspect.

### Facts

[Brazil is one of the 40 most dangerous countries in the world, when it comes to fear of becoming a victim of violent crime](https://www.visionofhumanity.org/wp-content/uploads/2022/06/GPI-2022-web.pdf).

Nevertheless, this may be just one of the drivers of an overarching phenomenon: the replacement of the physical wallet by the smartphone.

Several participants mentioned to have the impression that people no longer carry cash or regular wallets as they used to. Not surprisingly, [for 86% of Brazilians, the fear of having their smartphone stolen is greater than the fear of having their wallet stolen](https://noticias-r7-com.translate.goog/cidades/para-86-dos-brasileiros-medo-de-ter-celular-roubado-supera-temor-por-roubo-da-carteira-21102022?_x_tr_sl=pt&_x_tr_tl=en&_x_tr_hl=en&_x_tr_pto=wapp).

Finally, [the government is making all kinds of ID documents (regular ID, driver's license, etc.) available in their digital form](https://www.gov.br/governodigital/pt-br/conta-gov-br/carteira-de-documentos-digitais) so that they can be displayed in smartphones.

### Recommendations

**Promote bitcoin as the money you do not need to carry around**  
Emphasize Bitcoin's digital nature and security features to align with the evolving preference for digital financial assets. **Highlight its role in reducing the need to carry physical cash, thus increasing personal security.** This may be particularly relevant to entrepreneurs (street vendors, self-employed professionals, etc.), who typically need to carry cash to and from banks frequently.

**Learn locally, spread globally**  
Efforts to strengthen the security and anti-theft features of bitcoin wallets on smartphones are imperative. This is especially important when considering hostile environments, such as regions plagued by high crime rates, including certain areas in Brazil. **Ensuring that digital wallets are resilient in challenging environments can increase the overall level of security for users worldwide**.

___
## Chapter 06: Data Leakage & Scams

![](https://www.psacramento.com/content/images/size/w1600/2023/11/chapter-05-quote.jpg)
> **Ernesto, the barber** - "Using Pix means we carry less cash, so it is a personal safety improvement. It is safer to walk around with less money in your pocket."

### Insight

An interview with the daughter of a scam victim brought the following disturbing conclusion: **Pix has been used by scammers to trick their targets**.

An in-depth investigation revealed that the convergence of three factors created the ideal environment for social engineering cybercrimes:

1.  Pix system design lacks proper compartmentalization.
2.  Data leaks can expose vast amounts of sensitive information.
3.  Widespread and indiscriminate use of social media and messaging apps threaten security.

### Facts

**1: Compartmentalization**  
Compartmentalization is a [core information security principle](https://en.wikipedia.org/wiki/Compartmentalization_(information_security)) that is based on limiting access to information and resources to those who need it for a specific task.

In the context of a payment system, this principle can be applied as follows: if a user shares a payment identifier with another person (in order to receive a payment), the person who received the identifier should be able to use this information _exclusively_ for making payments.

**Types of Pix key (aliases)**  
Individuals can set their Pix Keys to be random alphanumeric identifiers, which is recommended for privacy reasons.

However, there are three types of Pix keys which are indeed personal information data:

1.  **CPF (Individual taxpayer identification number)**
2.  **Email address**
3.  **Mobile phone number**

**How Pix fails to respect compartmentalization**  
Instead of keeping private user information distinct from payment identifiers, Pix allows users to (mis)use personal data for this purpose.

Imagine that someone has been hired to do some gardening, such as mowing the lawn, at a residence. When the job is finished, the homeowner asks the gardener the Pix key to pay for the service. The worker's Pix key may be his phone number, which is simply informed to the homeowner.

By acquiring the worker's phone number, the homeowner is able to not only transfer payments, but also make phone calls, send messages or share that number with third parties.

If the principle of compartmentalization had been strictly adhered to, the homeowner would have been limited to performing only monetary transactions.

**First possible explanation**  
This system design concept seems to have targeted improved usability.

Requiring individuals to recall a brand new piece of information seems to have been perceived as an obstacle that could hinder the success of the system. Allowing people to use personal info already memorized facilitates the transaction.

**Second possible explanation**  
A secondary perspective on this problem suggests that the design flaw in the Pix system may be rooted in the frame of reference provided by the existing money transfer systems (TED, DOC, etc.).

Traditionally, payment mechanisms required the disclosure of substantial personal information necessary for their use. These payment methods often involved transactions between parties who already had some level of trust or familiarity with each other. As a result, sharing such information was less worrisome.

With Pix, however, the landscape has changed. Pix is often used in scenarios analogous to cash transactions, in which the two parties may be strangers, with no pre-existing trust relationship. In this case, the exchange of personal information, such as phone numbers, exposes individuals to privacy risks.

The Brazilian Central Bank, perhaps taking cues from older systems, may not have fully considered the implications of merging payment identifiers with personal data, in such a broad range of transactional contexts.

**2: Data leaks**

**Pix key leaks**

In addition to the lack of compartmentalization, [Pix keys have been leaked](https://agenciabrasil.ebc.com.br/economia/noticia/2023-08/bc-comunica-vazamento-de-dados-de-238-chaves-pix).

-   August 2021: a data breach exposed **414,526** Pix keys linked to the State Bank of Sergipe (Banese).
-   January 2022: Acesso Soluções de Ação saw **160,147** of its customers' keys compromised.
-   February 2022: **2,112** Logbank customers' keys had been exposed.
-   September 2022: **137,285** Pix keys related to Abastece Ai Clube Automobilista Payment Ltda. (Abastece Aí) were compromised.

It is important to note that the type of data leaked is managed by the partner financial institutions and not by the Brazilian Central Bank itself.

In each incident, only identification information was exposed. Passwords and account balances remained confidential. Nevertheless, the exposure of this type of sensitive information gives criminals another data set, which can be used to commit fraud.

**Regular data leaks**

![](https://lh7-us.googleusercontent.com/GGJtCgV5bGrumJUvQpV7v12SJQVSzSEfhXiydahLKaQ4UJoJ6y3NVVTQBx6mj5_A03MwcLP3TgduyAI0RUWb3cF9Id5VEuKP9hvv8mLvcXRMlrVYz1CTGjf0ocjOvvr4iSwK-_isp1oK7eU4D7hG_hU)

Source: [Vazamento que expôs 220 milhões de brasileiros é pior do que se pensava](https://novocantu.com.br/noticia/70489/vazamento-que-expos-220-milhoes-de-brasileiros-e-pior-do-que-se-pensava)

On January 20th 2021, [Brazil experienced its largest-ever breach of personal data](https://www.opendemocracy.net/en/largest-personal-data-leakage-brazilian-history/). It is difficult to imagine a more extensive and detailed collection of data on an entire population, let alone its unauthorized exposure.

Two related data breaches came to light at the same time. 

**The first breach**, once available on a well-known forum, contained names, Brazilian tax IDs (CPF), birth dates and gender information from **223.74 million unique records**, which were compiled back in August 2019. Notably, this data set, which exceeded the size of the Brazilian population, also provided detailed information of deceased individuals. It was publicly accessible and even indexed by Google.

**The second breach** was related to data of the same 223.74 million individuals exposed in August 2019. In this case, **a preview had been made freely accessible**, while the complete data set was priced between $0.075 to $1 per CPF, with payments accepted only in bitcoin. This extensive breach encompassed 37 data sets, including ID numbers (RG), marital status, list of relatives, full addresses (with coordinates), education level, income and statuses in tax and social security systems.

**3: Social media and messaging apps**

**The dangers of oversharing**

![](https://www.psacramento.com/content/images/2023/10/Screen-Shot-2023-10-25-at-11.49.29.jpg)

Source: [Average daily time spent on social media according to global internet users as of the first quarter of 2023, by territory](https://www.statista.com/statistics/270229/usage-duration-of-social-networks-by-country/)

According to [this study published on Statista](https://www.statista.com/statistics/270229/usage-duration-of-social-networks-by-country/), **Brazil ranks first in the chart, with an average daily social media usage** of 3 hours and 49 minutes. This means that Brazilians spend more time on social media than any other population in the world.

Similarly to people in other countries, Brazilians have embraced social media as a platform for self-expression and social connectivity.

However, the indiscriminate use of social media can have dire consequences when personal information is shared publicly. Doing so without considering the consequences represents a treasure trove for criminals to exploit.

##### Possible explanation: Low perception of the sensitivity of personal data

![](https://lh7-us.googleusercontent.com/abLnX0WK-T0gJDdC2cb3J1tBHwX7ytSfgzmPSesrA8wCBSisHifxCiJcWC_YFT8dxUDw59ll6fVS1dWCwwk_Ec5lniPwZg9Jq5Hl4a99TZ4VEi76NzzaEgzBxQzlgypSVHXvEBqQoj8neccBM7qT34g)

Source: [Internet users’ perceptions of information sensitivity – insights from Germany](https://www.sciencedirect.com/science/article/pii/S0268401218307692)

Brazilians seem to have a lower perception of the sensitivity of several types of personal information, compared to Germany and the US.

This may be an additional explanation for the fact that Brazilians tend to share information online about their lives without considering how dangerous it can be.

**Messaging app scenario: WhatsApp everywhere**

> Popular enough to be nicknamed ‘zap-zap’, the messenger app is used by more than 90 percent of smartphone owners in Brazil to exchange text messages and by 83 percent to exchange images and voice messages. [Source](https://www.statista.com/topics/7731/whatsapp-in-brazil/#topicOverview)

The messaging app scenario in Brazil is notably homogeneous, primarily dominated by WhatsApp. This implies that **if a particular mobile phone number is active, it is probably linked to a WhatsApp account**.

Such a strong linkage facilitates the direct sending of text and messages, media content and links to the phone number.

However, this convenience poses significant privacy and information security risks. The ease of connecting with people through WhatsApp, using only their phone number, can be maliciously exploited for phishing.

> "Although \[phishing\] is not the most elaborate technique, it draws attention due to its power of dissemination and personalization. **It's not uncommon for people to receive messages and even calls in which the scammer provides various personal details, such as name, CPF, family members' names**. Most likely they have had access to a database leaked on the Deep Web and use this to make it appear that the contact is an official one from a company where the victim is registered," [explains Emilio Simoni](https://www.psafe.com/blog/golpe-do-pix-cresce-mais-de-350-nos-dois-ultimos-meses-aponta-psafe/).

**Second example of data leakage in everyday use**  
If criminals have access to such material, they will easily use it for scam.

Here is a step-by-step description of how to find a street vendor's home address:

![](https://www.psacramento.com/content/images/2023/10/Firefly-20231025122123-copy.jpg)

QR code and other fields were changed to avoid exposing personal data. Fields: ****Bank name****, ****Name**** (where one could see just the first name), ****Pix key**** (where the mobile phone number was presented), and ****CPF**** (individuals tax payer id number, partially obfuscated)

1.  A street vendor had a stand on the street selling underwear. On the stand there was a piece of paper with a QR code for receiving Pix payments. The QR code was photographed.
2.  After decoding the photo on a free website [On-line QR Code Decoder](https://blog.qr4.nl/Online-QR-Code-Decoder.aspx), the full name of the recipient was revealed.
3.  After searching for the full name in a database leaked from a phone company, the person's home address was found.

**Second example of data leakage in everyday use**  

![](https://www.psacramento.com/content/images/2024/01/chapter-06-confirmation-screen.jpeg)

Confirmation screen displayed before confirming an outgoing payment: As can be seen above, the sender's full name, part of the CPF (social security number), and the name of the bank are displayed. Source: [Pix no Banco Inter: como cadastrar chave e transferir dinheiro](https://www.techtudo.com.br/dicas-e-tutoriais/2020/12/pix-no-banco-inter-como-cadastrar-chave-e-transferir-dinheiro.ghtml)

Another notable instance of data leakage occurs during the payment confirmation process. At this stage, sensitive information is displayed, including the payer's full name, a portion of their CPF (_Cadastro de Pessoas Físicas_, which is a Brazilian tax identification number), and the name of their bank.

This exposure of personal information raises privacy concerns, as it potentially allows for the collection of personal information without the user's explicit consent or awareness.

When unauthorized access to sensitive information can be easily obtained by strangers, the consequences can be systemic.

**Serious consequences**

[
Pix: 22% dos brasileiros já sofreram golpes com o meio de pagamento
A nova pesquisa da FICO mostra que os usuários consolidaram o uso do Pix no dia a dia, mas isso também eleva o número de golpes
](https://www.tecmundo.com.br/seguranca/261823-pix-22-brasileiros-sofreram-golpes-meio-pagamento.htm)

Translated title: [****Pix: 22% of Brazilians have been scammed using this payment method.****](https://www-tecmundo-com-br.translate.goog/seguranca/261823-pix-22-brasileiros-sofreram-golpes-meio-pagamento.htm?_x_tr_sl=pt&_x_tr_tl=en&_x_tr_hl=en&_x_tr_pto=wapp)

Here are the [some of the most common scams associated with Pix](https://www.gov.br/economia/pt-br/orgaos/orgaos-colegiados/conselho-de-recursos-do-sistema-financeiro-nacional/acesso-a-informacao/educacao-financeira/copy_of_noticias/tentativas-de-fraudes-e-golpes-mais-comuns-com-o-pix-conheca-quais-sao-e-saiba-como-evita-los):

**Fake bank employee scam**  
Scammers pose as fake bank employees to trick victims into providing their personal and banking information. Then, they use this information to access the victim's accounts and make unauthorized transactions.

**WhatsApp social engineering scam**  
Scammers hack the victim's WhatsApp account and pretend to be a friend or family member of the victim. Next, they ask for money via Pix, claiming to be in an emergency situation.

**Fake auction scam on social media**  
Scammers take over someone's social media account and use it to sell goods at prices that seem too good to be true. Once victims pay for the goods, the scammers disappear without delivering the purchased items.

### Recommendations

**Advocate for privacy-centric payment identifiers**  
Recently, we have seen the rise of Lightning wallets, especially those that support Lightning addresses.

Bitcoin product managers striving for usability may inadvertently follow the same dangerous path the Brazilian Central Bank took: allowing users to use personal information (such as email or phone numbers) as payment identifiers.

This should not be done. The rampant fraud scenario in Brazil vividly illustrates the pitfalls of a system in which personal information and payment identifiers are not maintained separate.

**Establish guidelines regarding the suitableness of identifiers**  
This scenario induces reflection that leads to the development of guidelines.

What type of information should be used as an identifier to receive payments?

The choice should take into account two dimensions:

**Dimension 1: Identifiability**  
_How specific is the identifier regarding the individual's identity?_

-   **Specific**: Information that can easily lead to the identification of a specific individual (e.g., license plate number).
-   **General**: Information that is more generalized and less likely to identify a specific individual (e.g., hair color).

**Dimension 2: Stickiness**  
_How difficult is it to change the identifier assigned by the entity or system?_

-   **High**: Information that is difficult or impossible to change (e.g., social security number).
-   **Low**: Information that can be easily updated or abandoned (e.g., email address).

![](https://www.psacramento.com/content/images/2023/11/framework-information-identifier.png)

Source: [Paulo Sacramento](https://www.psacramento.com/)

This framework suggests that data used as identifiers that are both general in terms of identifiability and low in stickiness are the most appropriate. Following this approach helps minimize the risk of identity theft.

**Maintaining a privacy-first approach to bitcoin development**  
Building systems with a defensive, privacy-first perspective leads to more robust, secure systems.

While privacy-centric solutions may face short-term resistance, especially from governments, they will prove their worth in the long run by protecting against systemic threats. The Brazilian case with Pix is a stark reminder of the systemic risks of neglecting basic privacy principles.

But Brazil is not alone. In Sweden, the root cause of the problem is not technical, but rather legal: the principle of "_Offentlighetsprincipen_" (Public Access to Information) allows the public to request and access personal information, including home addresses and tax records, of any individual.

[
Swedish Bitcoiners targeted by armed criminals

Criminals in Sweden are targeting prominent Bitcoin and cryptocurrency proponents due to the ability to request access to residential and financial information from government.](https://cointelegraph.com/news/swedish-bitcoiners-targeted-by-armed-criminals)

This principle has inadvertently become a tool for criminals to target bitcoin holders. [Prominent bitcoin figures in Sweden have been specifically targeted due to the ease of access to their personal information](https://cointelegraph.com/news/swedish-bitcoiners-targeted-by-armed-criminals).

In incidents reported in the media, victims have been physically abused in their homes in order to steal their bitcoin holdings.

The "_Offentlighetsprincipen_" facilitates this by allowing criminals to "size up" their victims based on income or capital gains tax information. At the same time, it makes it easy for them to find victims' addresses.

The experiences in Brazil and Sweden underscore the urgent need for a privacy-first approach to bitcoin and broader cryptocurrency development.

As the bitcoin ecosystem continues to evolve, developers and project leaders must work together to ensure that privacy is not an afterthought, but a foundational element that ultimately enhances citizens' security against diverse and evolving threats.

___
## Chapter 07: Designing Contact Lists to Prevent Errors

![](https://www.psacramento.com/content/images/size/w1600/2023/11/chapter-07-quote.jpg)
> **Mônica, the flower shop owner** - "I needed to send a Pix to an app driver. In my banking app, I had checked the latest payments sent and saw his name. I didn't check the CPF [social security number, unique identifier] and sent the Pix straight away. But this was actually another app driver with the same name, not the person I wanted to send money to."

### Insight

An interviewee highlighted that, when performing a manual payment via Pix, people can accidentally transfer money to the wrong individual.

According to this participant, the problem arose because she had two contacts in the app with almost identical names. As a result, she accidentally sent money to the wrong person.

Several factors can increase the risk of such errors in manual transactions:

**Rushed or distracted users**: While Pix's emphasis on quick and smooth transactions is a notable feature, it can be a double-edged sword. The said participant stated that when she is rushed or distracted, she is prone to accidentally select the wrong contact. This haste or lack of focus can lead to costly mistakes, which was the case of our interviewee.

**Growing contact lists**: Contact lists can grow quickly, especially for those who use them for business. As the list grows, it becomes more difficult to accurately and quickly identify the right recipient.

These risks highlight the need for design elements that help users clearly distinguish between contacts.

### Facts

Pix allows users to make smarter payments through either a QR code or the "_Pix Copia e Cola_" feature (equivalent to "_Pix Copy and Paste_"). In these methods, the system automatically fills in the recipient's details at the start, thus eliminating the need to manually select a contact.

However, sometimes users may need to initiate Pix payments manually, especially with vendors or service providers who do not have a more sophisticated automated system. This is often the case in face-to-face transactions, including those with independent service providers, such as hairdressers, manicurists and teachers.

The interfaces of several banking applications in Brazil were analyzed to identify design flaws that might lead to this problem. The analysis was conducted by reviewing YouTube tutorial videos for using Pix.

The resulting design trends for contacts were observed:

**No avatar for contacts**

![](https://www.psacramento.com/content/images/2023/11/Screen-Shot-2023-11-03-at-21.45.21.png)

The _Caixa Economica Federal_ app avoids the use of avatars for contacts, but rather presents contacts with text-only information.

**A single initial**

![](https://www.psacramento.com/content/images/2024/03/chapter-07-single-initial-1.jpg)

Banco do Brasil uses a single initial as an avatar for each contact. This initial comes from the first name.

**Two initials**

![](https://www.psacramento.com/content/images/2023/11/Screen-Shot-2023-11-03-at-21.52.04.png)

Nubank uses two initials as an avatar. One initial comes from the first name and the other, from the last name.

**Generic avatar**

![](https://www.psacramento.com/content/images/2023/11/Screen-Shot-2023-11-03-at-21.52.54.png)

An older version of the Itau banking application uses a generic, undifferentiated image for all contacts, without providing a unique visual identifier for each contact.

**Additional design patterns**

Further investigation also revealed some promising design patterns being used to potentially improve the user experience and reduce errors:

**Favorites list**

![](https://www.psacramento.com/content/images/2023/11/Screen-Shot-2023-10-31-at-23.25.05.png)

This feature allows users to add specific contacts to a Favorites List, thus ensuring that frequently used contacts are easily accessible and reducing the risk of selecting the wrong contact.

**Nicknaming contacts**

![](https://www.psacramento.com/content/images/2024/03/chapter-07-nickname.jpg)

"Apelido" means "Nickname".

The ability to assign nicknames to contacts allows faster recognition, as users often have personal or informal names more closely associated with certain individuals.

### Recommendation

By learning from Pix's experience in Brazil, designers in the bitcoin space can take a proactive approach to improving payment interfaces, especially regarding contact selection during manual payment initiation.

Here are three design ideas to mitigate the risk of making payments to the wrong person:

**Identicons**

![](https://www.psacramento.com/content/images/2024/01/identicons.png)

Source: [JDENTICON - Open source library for generating identicons](https://jdenticon.com/)

Use [Identicons](http://identicon.net/), which are visually distinct avatars based on the hash of a specific contact information. This could be either a Public Key or a Lightning Address, for example. They provide a consistent visual representation that is unique to each contact.

-   Benefit 1: Identicons are automatically assigned to contacts, enhancing their uniqueness without additional user interaction.
-   Benefit 2: A specific piece of information (a Lightning Address, for example) will always generate the same image, thus increasing consistency.
-   Benefit 3: Contacts with very similar names receive quite different avatars.

By presenting a consistent and unique identifier next to a contact's name, users can more easily distinguish between contacts, even those whose names are similar.

**Custom visual tags**

![](https://www.psacramento.com/content/images/2023/11/emoji-contact-names-iphone.jpeg)

Source: [Stylize Contacts & Names on the iPhone By Adding Emoji Characters](https://osxdaily.com/2013/05/15/customize-contacts-names-add-emoji-characters/)

Allowing users to customize contact avatars with unique additional tags, such as emoji or color codes, can streamline the selection process in platforms such as Pix.

For example, if a user knows two people named "Pedro," one could be represented by a tennis racket emoji and the other, by a laptop.

These personalized emojis are visual cues that instantly help users identify and select the correct recipient, also improving accuracy and user experience.

**Contact history integration**

![](https://www.psacramento.com/content/images/2023/11/Screen-Shot-2023-11-03-at-22.11.35.png)

The [contacts page of the Bitcoin Design Guide](https://bitcoin.design/guide/daily-spending-wallet/contacts/) recommends having an activity section for contacts.

Provides an overview of past interactions by displaying a transaction history with each contact. This could include the date and amount of each payment.

By providing this historical context, users can better understand their relationship with each contact and make more confident and informed decisions about future transactions.

**Intelligent Contact Verification and Matching**

![](https://www.psacramento.com/content/images/2023/11/caution_1_1_1_1.jpg.png)

Drawing inspiration from the healthcare world: Often, a precautionary sticker is attached to certain medical fillings. This is done to avoid medical mix-ups when patients have similar names.

Introduces an intelligent function that proactively detects when users are attempting to send funds to a contact whose name closely resembles another entry in their list. If a potential similarity is identified, a two-step verification process is triggered.

This process would first display a warning pop-up, prompting users to double-check their selection. Then, a confirmation pop-up showcasing additional contact details (e.g., profile picture, public key, Lightning Address, last transaction date) would be presented to ensure that users are sending funds to the intended recipient.

This integrated approach reduces the likelihood of errors, while enhancing user confidence in transactions.

**Conclusion**  
By incorporating these features and promoting best practices, the Bitcoin community can not only enhance user experience but also increase confidence in the system by ensuring that the pitfalls faced by Pix users in Brazil will not be replicated globally.

___
## Chapter 08: Designing Payment Receipts To Prevent Fraud

![](https://www.psacramento.com/content/images/2023/11/chapter-08-quote.jpg)
> **Rogério, the strawberry seller** - "The problem with Pix is that sometimes scammers show a scheduled payment when purchasing products and as soon as they leave, they cancel the payment."

### Insight

One particular type of scam stood out as the most frequently reported by participants: the **Fake Pix Receipt scam**.

The Fake Pix Receipt Scam involves fraudsters presenting sellers with fake receipts for a Pix transaction, misleading them into believing that a payment has been made. This results in sellers releasing goods or services without actually receiving payment.

This scam is usually perpetrated in one of two modes: in person or remotely.

**In person**  
After ordering a product, unscrupulous buyers present the seller what appears to be a valid receipt for a completed Pix transaction. In reality, it is a receipt for a scheduled payment. Mistakenly believing the scheduled transaction has been carried out, the seller considers the deal to be complete. After taking possession of the product and leaving the location, the dishonest buyer quickly cancels the scheduled payment, leaving the seller without the expected funds.

**Remotely**  
In this scam, a fraudulent buyer attempts to deceive the seller by sending a fake payment receipt. This fake receipt is presented as evidence of a transaction, even though no payment was actually made. The fake receipt meticulously replicates expected details, such as the transaction date and amount, thus creating an illusion of legitimacy. Typically, these fake receipts are sent as part of a purchase over the phone or through online messaging platforms, such as WhatsApp, to deceive the seller.

**The bottom line**  
These scenarios underscore the fact that many small businesses lack adequate point-of-sale (POS) systems that automatically verify and notify the seller of received payments.

Sellers often choose to use the smartphone banking app, but this is not a perfect solution. The somewhat extreme scenario of not being able to confirm payments through the banking application is more common than one might think.

Given these challenges, it is clear that relying solely on electronic verification and notification methods is not optimal. This demonstrates the critical need to design receipts ready for easy manual verification.

In other words, users of instant payment systems should be able to easily verify the authenticity of a payment just by looking at the receipt.

### Facts

Ideally, merchants should use stand-alone point-of-sale (POS) devices to ensure that all incoming payments are accurately verified and promptly approved.

[PagSeguro](https://pagseguro.uol.com.br/) and [Stone](https://www.stone.com.br/pix/) are two companies that offer such Pix-compatible devices. However, these terminals come with an upfront cost and subsequent monthly fees. As a result, most users prefer the free alternative of using the standard mobile banking application, which is typically more attractive, for economic reasons.

Making sure that payments are received correctly with the app can be tricky, depending on the circumstances. This can lead to financial discrepancies.

Both human factors and technical conditions can make this seemingly simple task difficult. 

Here are some scenarios where sellers may have difficulty ensuring that payments are being received correctly:

### Human factors

**Lack of attention**  
A lapse in focus can lead to mistakes, such as accepting fraudulent or incorrect payment confirmations. In high-traffic situations (such as at an open street market or during a crowded event), sellers may be overwhelmed with simultaneous customers and may not focus on verifying each payment properly.

**Manipulation from dishonest buyer**  
Scammers may use social engineering, pressuring the seller to rush, claiming to be in a hurry, or other tactics to distract the seller from verifying the payment.

**Several payments that are sold for the same price**  
Even if the seller is able to check the transaction history in the bank's application, a hurdle can arise when dealing with numerous transactions for products with the same price. In such cases, it becomes difficult to distinguish which payment was made by which customer. This situation is common for certain merchants dealing with a large volume of goods sold at the same price point.

### Technical limitations

**Limited device access**  
In a bustling street market scene, several workers are actively engaging with customers, each receiving payments simultaneously. However, only one individual, possibly the owner or manager, has access to the smartphone that contains the banking app. This setup creates a unique challenge in verifying real-time payments, since only one person has the ability to confirm transactions on the spot.

**Limited Internet access**  
The sellers may not have access to a stable internet connection, making it hard to verify real-time transactions in their banking app.

**Low smartphone battery**  
The seller's smartphone may run out of battery, which prevents it from being turned on and verifying the banking app.

**Banking app downtime**  
Sometimes, due to technical glitches or poor maintenance conditions, a banking app may be temporarily unavailable. During these times, sellers are unable to verify payments.

### Relying on manual verification of receipts

When sellers find themselves in these situations, they must rely on manual verification of payment receipts generated by the buyers' banking application.

This means that they take on the task of confirming the legitimacy and accuracy of payments.

In non-face-to-face transactions, by verifying the payment receipt received through a messaging app on their own phone screen.

In non-face-to-face transactions, by verifying the payment received through a messaging app on their own phone screen.

Receipts can vary greatly based on the banking app that generates them. However, examining the aforementioned typical Pix receipt, it becomes clear how merchants can frequently be tricked.

#### Receipt of Banco do Brasil

![](https://www.psacramento.com/content/images/2024/03/chapter-08-banco-do-brasil.jpeg)

Source: Cannot be made public to protect the identity of the person who has posted it publicly on the Internet.

The most glaring problem with such a receipt design is its lack of structure. 

The content of the receipt is presented in a single font, with no variation in style or weight throughout the document. This creates a visual monotony that fails to direct the reader's eye to the most important information.

Critical elements, such as payment status (scheduled vs. completed), amount, date and time, and parties involved are not immediately apparent.

Rather, this receipt presents all data in a uniform manner, from key transaction details to potentially irrelevant information, such as bank hotline phone numbers.

Most importantly, the receipt lacks a visual distinction that ensures its authenticity.

How would a seller know that this receipt is authentic and not a forgery based on its appearance?

#### Receipt of Banco Santander

![](https://www.psacramento.com/content/images/2023/11/Screen-Shot-2023-11-18.jpg)

Source: YouTube video [QUASE CAÍMOS NO GOLPE DO PIX AGENDADO](https://youtu.be/u_ZTQRQRQ5w?si=yjKPpOpq9y5dCyju&t=489)

The screenshot was taken from a YouTube video in which the content creator describes how her mother almost fell victim to the Fake Receipt Scam in a non-in-person transaction.

On the **left side** of the image is a screenshot showing a real receipt for a scheduled payment.

On the **right side** is the tampered version of this receipt. In this altered version, the dishonest buyer had moved the contents of the screen up, hiding the title at the top of the screen that described the receipt as _scheduled_. Then, in the section below, another part of the image that contained the word _scheduled_ was erased using an image-editing application.

**Summary**  
The Fake Pix Receipt scam, which occurs in both in-person and remote transactions, exploits the inability of sellers to distinguish between real and fake receipts.

This risk is compounded by human factors, including inattention and manipulation, as well as technical challenges such as limited device access and banking application issues.

These findings highlight the need for improved receipt design to enable clearer manual verification and mitigate the risks exploited by unscrupulous individuals.

In the upcoming recommendations section, we will discuss how the bitcoin projects can ensure that a similar problem does not occur in contexts where bitcoin is used for everyday transactions.

### Recommendations

The shift from traditional cash-based transactions to instant digital payments has significant consequences, including certain risks. A prime example is the "Fake Pix Receipt Scam" in Brazil, which has much to teach about these vulnerabilities.

This type of fraud challenges the common notion that the digitization of payments alone guarantees universal reliance on electronic confirmation methods. The real-world situations uncovered by this research have revealed a much more complex scenario.

These complications are not as rare as one might think. Failure to address them leaves a gap that can be exploited.

Therefore, the Bitcoin community is encouraged to design products with real-world constraints (both human and technical) in mind.

In particular, wallets designed for everyday cash-like use cases of physical products and services (commerce, street markets, etc.) should generate well-designed receipts.

This will be reflected in features that allow users to quickly and confidently verify the validity of incoming payments through visual inspection.

**Taking inspiration from physical bills**

![](https://assets.losspreventionmedia.com/uploads/2019/07/counterfeit-money-1280x720.jpg)

Source: [Freepik](https://www.freepik.com/premium-photo/checking-counterfeit-money-light-100-dollars-against-window-his-hand-check-watermark-new-hundred-dollar-bill-translucence-american-currency_18482336.htm)

To prevent frauds, physical money has properties that allow people to easily verify its authenticity. Anyone can hold a bill up to the sunlight and instantly verify that the embodied symbols attest to its legitimacy.

Similarly to physical notes, receipts of Lightning payments should not only include key information (amount, date, etc.) but also allow for verification of authenticity.

The two features proposed here are designed to enable users to improve the reliability of the visual validation process, even when they face significant constraints, whether psychological or technical.

Both features are used to prevent problems of buyer deception in face-to-face purchases.

#### Feature 1: Live timer including seconds

![](https://www.psacramento.com/content/images/2024/01/timer.gif)

Source: [Timer in SwiftUI](https://sarunw.com/posts/timer-in-swiftui/)

A live timer that displays the amount of time that has elapsed since a payment was made offers significant benefits.

It provides clear, specific information about elapsed time, a detail that is difficult to fabricate in advance in fraudulent scenarios.

More importantly, its dynamic nature enhances authenticity, making it a stronger deterrent to forgery than static representations.

It can be particularly useful in face-to-face transactions when the **seller does not have a smartphone** and needs to verify the receipt on the buyer's smartphone screen.

#### Feature 2: Verification Emoji

![](https://www.psacramento.com/content/images/2023/11/Frame-1.png)

Screen adapted from the [Bitcoin UI Kit](https://www.bitcoinuikit.com/)

From a technical perspective, this feature involves translating the preimage of a Lightning payment into an emoji representation.

Rather than presenting a complex, random string of characters, this approach takes advantage of the unique nature of the data and renders it into a form that is more user-friendly and visually accessible.

This makes the validating piece of information easier to see and understand, improving the user experience within the Lightning Network.

A merchant can verify the authenticity of the receipts presented by buyers by comparing the verification emoji associated with their invoice with the verification emoji on the buyer's receipt. If these emoji match, the merchant confirms the legitimacy of the transaction.

This approach deters fraudsters because dishonest buyers cannot know in advance which emoji they would need to provide in a fake receipt in order to deceive the seller.

It can be particularly useful in cases where both the seller and the buyer have smartphones at their disposal.

### Conclusion

The Fake Pix Scam illustrates the need for Bitcoin developers to plan for situations where payment verification via a smartphone or POS is unfeasible. This scenario must be considered when designing receipts for wallets used for everyday spending. This is important for both in-person and remote transactions of physical products and services.

Similar to physical currency, digital payment receipts should be designed with features that facilitate manual authentication by visual inspection.

The features proposed to enable these visual checks provide the bitcoin community with new design options that focus on creating receipts which are not only secure and reliable, but also user-friendly. This approach is key to addressing the challenges and risks associated with payments in person-to-person or technically constrained contexts.

The primary objective is to leverage technology capabilities to develop receipts that are intuitive, secure, and effective at preventing fraud. In addition, the goal is to continually refine, consolidate, and build consensus around the best practices to ensure user safety.

The contexts in which these can make a difference are few at the moment, but let us be proactive in ensuring the safety of users in [bitcoin's circular economies around the world](https://blog.bitfinex.com/education/a-look-at-bitcoin-circular-economies-around-the-world/). Getting it right from the start can make a big difference in the future, when adoption reaches higher levels.

___
## Chapter 09: Spending Habits & Different Methods

![](https://www.psacramento.com/content/images/size/w1600/2024/01/chapter-09-quote.jpeg)
> **Gerson, the ticket seller for an inflatable children's playground** - "Nowadays most people are paying with Pix. But the ones who still use cards now usually opt for using credit cards, as they want to be able to consume now but pay in the future."

### Insights

Conversations with participants suggest that just a few years after its launch, [Pix has become the number one payment method chosen by the population for everyday consumption](https://www.ft.com/content/e1c7b0e7-4c17-40c4-8e03-16c698674efa).

However, **a significant part of the population still prefers to use credit cards to pay for services and consumer goods**.

This preference for credit cards over Pix predominantly comes from the desire to defer payment, a feature available in credit cards but absent for Pix, a system that by design processes payments instantly.

This insight is significant as it underscores a critical aspect of consumer behavior – the [ingrained habit of 'buy now, pay later' which is prevalent in certain countries like Brazil](https://blog.ebanx.com/en/why-do-brazilians-love-to-pay-with-installments/).

### Facts

**Overview of credit card ownership and usage in Brazil**

> Today, in Brazil, there are already more credit cards (190.8 million) than working-age workers (107.4 million).  
> [Source](https://revistapegn-globo-com.translate.goog/economia/noticia/2023/09/no-brasil-16-milhoes-de-consumidores-tem-mais-de-tres-cartoes-de-credito.ghtml?_x_tr_sl=pt&_x_tr_tl=en&_x_tr_hl=en&_x_tr_pto=wapp)

Research published by Serasa Experian (2023) shows that [52% of Brazilians have 3 or more credit cards](https://www-poder360-com-br.translate.goog/economia/52-dos-brasileiros-tem-3-ou-mais-cartoes-de-credito-diz-serasa/?_x_tr_sl=pt&_x_tr_tl=en&_x_tr_hl=en&_x_tr_pto=wapp).

For most of them, the reason is the ability to increase spending limits to make more purchases.

The majority of respondents say that credit cards play an important role in the family budget:

-   61% use them for installment purchases
-   37% use them for essential consumption (food, fuel, etc.)

**Challenging economic context: Brazilians live on a tight budget**  
One possible interpretation of the fact that Brazilians own and use multiple credit cards is that they have a lot of income available for discretionary consumption.

Interestingly, the Brazilian case is exactly the opposite.

> In Brazil, the average household net-adjusted disposable income per capita is 12 924 USD, which is less than the OECD average of 30 490 USD a year.

Source: [Brazil at Organisation for Economic Co-operation and Development (OECD)](https://www.oecdbetterlifeindex.org/countries/brazil/)

One way to assess a country's typical household disposable income is to compare it to other countries, as we can see above.

Another way to evaluate it is to conduct surveys with the country's population, as we will see next.

According to a [research study with around 2000 participants by the Brazilian Central Bank](https://www.bcb.gov.br/detalhenoticia/747/noticia), **44.8% say they never or rarely have money left over at the end of the month**.

Now, it is necessary to consider that Brazil's population is predominantly young, eager to consume.

Given this scenario, what kind of solutions may arise?

**Credit cards with 0% interest for installment payments**  
As we further address the Brazilian financial landscape, particularly in the area of credit card use, we encounter interesting insights from notable researchers. [Maria Paula Bertran and David Echeverry delve into this phenomenon](https://www.sciencedirect.com/science/article/pii/S2214635021000046), highlighting the significant correlation between the proliferation of credit cards and the retail sector in Brazil. A telling excerpt follows:

> [Ferman (2015)](https://www.sciencedirect.com/science/article/pii/S2214635021000046#b5) and [Saltorato et al. (2014)](https://www.sciencedirect.com/science/article/pii/S2214635021000046#b11) affirm that the expansion of credit cards in Brazil is associated with retail stores. The Brazilian stores follow the basics of international retailers, such as Macy’s or Amazon’s cards.
> 
> However, in Brazil, **retailers and banks allow people to buy in installments without interest rates**.  
> Under this procedure, the credit card companies offer the cardholders the opportunity to pay the total amount of purchases in several installments, without extra costs.  
> They are similar to regular credit card purchases in the sense that both do not involve interest rates, if the credit card bill is paid within the 30-day grace period.
> 
> One can pay a BRL 100 purchase into five installments of BRL 20 each, for example.

Source: Adapted from [What is the size of credit card debt in Brazil? Reporting Thresholds, Interest Rates and Income Distribution](https://www.sciencedirect.com/science/article/pii/S2214635021000046), by Bertran and Echeverry

However, it is important to understand that this option depends on the policies of the commercial entities themselves. The ability to pay in interest-free installments and the number of such installments are determined by the seller. This means that not all purchases can be paid in installments, and the number of installments available may vary from merchant to merchant. This flexibility is a distinct advantage for consumers, but it also requires an understanding of the specific terms set by each merchant.

Regardless of the details, the prevalence of credit card payments in installations highlights the importance of these credit facilities in the daily lives of Brazilians, bridging the gap between immediate needs and financial constraints.

The situation not only reflects the delicate balance between consumer behavior, retail strategies and financial policies in a developing economy. It is also a testament to the evolving financial landscape and the adaptability of the Brazilian population to meet these challenges.

**Credit cards as a necessity**  
In summary, for a large portion of the Brazilian population, **credit cards are a necessity, not just a matter of convenience**.

With lower disposable incomes, credit cards are being used to manage cash flow, allowing consumers to spread the cost of purchases for essential items over time.

This becomes clear when we look at the [types of expenses that drive people into debt](https://jovempan-com-br.translate.goog/noticias/economia/pesquisa-revela-que-maioria-das-dividas-de-cartao-de-credito-no-brasil-vem-de-compras-em-supermercados.html?_x_tr_sl=pt&_x_tr_tl=en&_x_tr_hl=en&_x_tr_pto=wapp):

-   The majority of credit card debt in Brazil (59%) is due to purchases in supermarkets
-   Purchases of clothes, shoes and home appliances account for 46% of the debt
-   Expenses for medicines and medical treatments represent 37% of the debt

If we want to promote bitcoin adoption in Brazil, bearing in mind the relevance of credit cards is essential. To move bitcoin adoption forward, the community needs to recognize the fundamental role that credit cards play in allowing Brazilians to purchase basic products and services.

### Recommendations

Recognizing the important role of credit cards in Brazil can help calibrate expectations for Lighting Network adoption in the country.

Similar to Pix, Lightning payments do not inherently support deferred payments.

The implication here is profound. It suggests that the rate of the adoption of Bitcoin over Lightning in a retail context may be constrained in Brazil, not because of its functionality or efficiency, but because of deep-rooted economic consumer habits and preferences, such as payment deferral.

Rather than trying to go against the tide, it may be more practical to embrace it and explore methods of introducing people to the bitcoin experience that take into account their existing behavioral patterns.

According to the information presented in this chapter, it seems that 'sats back' credit card services (like [Fold](https://foldapp.com/), for example) can be one of the most strategic ways to promote bitcoin in a country with high credit card usage, such as Brazil.

This model is particularly advantageous because it offers the following benefits:

1.  **Integration with existing habits**: Mirrors the familiar cash back reward structure of credit cards, making it easy for users to understand and engage with. By offering bitcoin (sats) as a reward for regular credit card purchases, it aligns with established spending patterns, encouraging its adoption without the expectation of changing consumer behavior.
2.  **Low-risk introduction to bitcoin**: Provides a low-risk entry point into the world of bitcoin. Users earn bitcoin as a reward for their usual credit card purchases, which allows them to accumulate and get used to bitcoin and the Lightning Network, without having to invest directly or navigate the complexities of cryptocurrency exchanges.
3.  **Education through experience**: Facilitates hands-on learning about bitcoin. As users earn and potentially use Bitcoin rewards, they gain practical knowledge and understanding of how cryptocurrency works, which can demystify Bitcoin and increase overall comfort with this digital asset.
4.  **Potential for appreciation**: Provides a greater sense of value than traditional cashback rewards. Unlike traditional cashback, bitcoin has the potential to appreciate over long periods of time, making rewards potentially more valuable in the future and adding an attractive investment aspect to everyday purchases.
5.  **Seamless integration with the Lightning ecosystem**: While traditional cashback points can provide immediate, tangible benefits in the context of a group of partner companies, their value and usefulness can be obscured by complex rules, restrictions on where they can be used, and potential devaluation. In contrast, earning Sats as rewards offers a simpler, globally accepted alternative, making it attractive to users interested in the growing bitcoin space. Being able to transfer sats to their own Lightning wallets (like [Phoenix](https://phoenix.acinq.co/) or [Wallet of Satoshi](https://www.walletofsatoshi.com/)) could be powerful. While integrating it with a gift card platform like [Bitrefill](https://www.bitrefill.com/) could make it very convenient.

Business model considerations are beyond the scope of this research project. However, the benefits listed above make a compelling case for entrepreneurs in the bitcoin space, as it addresses the unique economic landscape of Brazil. At the same time, it offers an alternative for bitcoin to become part of everyday financial transactions without disrupting established consumer behaviors.

This approach could serve as a blueprint for promoting bitcoin in similar markets around the world, emphasizing adaptability and user-centric innovation in efforts to promote the expansion of the cryptoasset.

___
## Chapter 10: The Role of a Trusted Friend for the Elderly

![](https://www.psacramento.com/content/images/2024/03/chapter-10-quote-2.png)
> **Emerson, the street fruit vendor** - "I still have to carry cash. Mostly because of older people. They don't accept Pix, you know?"

### Insight

In the course of the interviews, **older age emerged as a primary factor limiting the adoption of Pix among participants**.

This issue significantly impacts an individual's ability to independently navigate and use the new payment system.

However, **a notable approach to overcoming this barrier involves the assistance of more technologically savvy individuals within their close social circles**, such as trusted family members and friends.

This support system plays a critical role in facilitating the use of Pix, which highlights the importance of interpersonal relationships in the adoption of new digital financial tools among elderly and less tech-savvy demographic groups.

### Facts

While the interviews highlighted the critical role of interpersonal relations in the adoption of Pix by the elderly, it is important to support these findings with concrete data.

In the following section, we present statistical evidence that not only underpins our findings, but also sheds light on the broader context of Pix use among different age groups and the associated risks faced by the elderly.

**Older people use Pix less often than other age groups**

![](https://www.psacramento.com/content/images/2024/01/Chart-Transactions-Distribution-per-Payer-Age-Range.png)

Source: [Relatório de Gestão do Pix (2020-2022) - Banco Central do Brasil](https://www.bcb.gov.br/content/estabilidadefinanceira/pix/relatorio_de_gestao_pix/relatorio_gestao_pix_2023.pdf)

The chart shows that the 60+ age group has consistently accounted for a small portion of transactions throughout November 2020 to December 2022, with a stable representation of 4%. This suggests that the adoption of the payment system by this age group has not changed significantly over time and remains a very small segment of the overall user base.

**Elderly people are increasingly victims of fraud**

> The federal government assistance hotline "Disque 100" registered more than 15 thousand reports of financial or material abuses against the elderly in the first five months of 2023, 73% more than in the same period of 2022. With technological advances, those who have lived longer have become even more vulnerable.  
> Source: [Number of scams against elderly people grows by more than 70% in 2023 - Jornal Nacional](https://g1.globo.com/jornal-nacional/noticia/2023/07/03/numero-de-golpes-contra-pessoas-idosas-cresce-mais-de-70percent-em-2023.ghtml)

As observed above, further research demonstrates that older people are less active in using Pix than other age groups. They are also more likely to be victims of financial fraud, an unfortunate and growing phenomenon.

**Possible explanation**  
Conversations with participants revealed three factors contributing to the problems with Pix faced by aging adults:

1.  **Technical literacy**: Senior adults may lack a basic understanding of digital interfaces and digital payment flows. This gap in technological familiarity can lead to confusion and intimidation when faced with the prospect of adopting a digital payment system that often requires a level of digital literacy.
2.  **Resistance to change**: Aging adults may be accustomed to long-standing financial habits and methods, such as using cash or visiting banks in person. Introducing a new, digital system disrupts these familiar routines. The effort and perceived risk of learning and trusting a new system often results in a reluctance to move away from established practices.
3.  **Cognitive limitations**: As people age, many may experience limitations in their cognitive abilities, such as diminished short-term memory, slower processing of new information, and a decline in problem-solving skills. These limitations can make it difficult for older users to learn how to navigate digital payment platforms, understand security best practices, or distinguish legitimate banking contacts from scams.

### Recommendations

However, it is fundamental to recognize that for a certain subset of users, this may not be the reality. Instead, there is often an intermediary agent involved in the process of setting up wallets and, in some cases, managing funds. This is typically someone who is more tech-savvy and acts as an assistant to the older end user.

The recommendations outlined below are designed to address these challenges, proposing practical steps that can be taken by the bitcoin community to make digital financial tools more accessible and safer for the elderly population.

A first and obvious lesson is that accessibility is critical, especially for applications with an older user base. Paying attention to details such as font size, contrast, and overall interaction design can significantly improve the user experience for senior users.

However, the most important lesson goes beyond accessibility.

When building bitcoin applications, we tend to have a very individualistic view of the onboarding process and money flows.

However, it is important to recognize that for a certain subset of users, this may not be the reality. Instead, there is often an intermediary involved in the process of setting up wallets and, in some cases, managing funds. This intermediary is typically someone who is more tech-savvy and acts as an assistant to the older end user.

Imagine that you are working for an educational bitcoin project in a city where the population has a relatively high median age, such as [Lugano, which is 46.9 years old (2021)](https://www.bfs.admin.ch/bfs/en/home/statistics/cross-sectional-topics/city-statistics/city-portraits/lugano.html). It would be advisable to encourage the participation of family members or friends, who often act as technology facilitators. Training these individuals alongside the elders can create a supportive environment for learning and exploration.

Understanding, educating and designing for this dynamics - where not only an individual, but also a trusted helper may be interacting with the application - is key for creating effective and user-friendly bitcoin applications for an older demographic group. Other non-technical users would also benefit from this approach.

Finally, the staggering frequency with which the elderly have been defrauded in Pix-related scams draws attention to their vulnerability.

I cannot help but wonder how many vulnerable people could have been protected from fraud if Pix-enabled [bank accounts offered some sort of joint account with dual control for the elderly](https://waywiser.com/wordtothewise/joint-bank-account-with-aging-parent/).

In the future, Bitcoin companies could gain a competitive edge over traditional banks by offering multi-signature schemes tailored for elderly customers.

Together, we can set a new standard in the world of digital finance and demonstrate that bitcoin is not only a symbol of innovation, but also a beacon of trust and security for all users, regardless of their age.

___
## Final Thoughts

This research consists of a collection of UX-related findings about the adoption of Pix, which may be valuable for the bitcoin community.

After reflecting on the significance and relevance of the research as a whole, the following are our final thoughts:

### Using digital payment systems as if they were cash requires a high standard level

When people make frequent digital transactions with trusted parties (banks, businesses, known people, etc.), the requirements are relatively low.

However, when digital payments are made with untrusted parties in cash-like scenarios, the stakes are very different. In this case, usability, privacy and information security standards must be raised to a whole new level.

-   Design problems on receipts can create opportunities for fraud, as we see in Chapter 08.
-   Design problems on contact screens can lead to people accidentally sending money to the wrong person, as already mentioned in Chapter 07.
-   The lack of focus on accessibility can reinforce the exclusion of an entire age group, as observed in Chapter 10.
-   The lack of compartmentalization of information can become another way for scammers to exploit victims, as we see in Chapter 06.

In other words, there is little room for error. Ignoring the smallest details can have dire consequences for many people.

In such a challenging context, a solid and conservative approach is more than justified. We are pleased to notice that the bitcoin community is eager to pursue a very high standard.

### Privacy can achieve systemic relevance

> A survey by financial protection fintech Silverguard reveals that **four in ten Brazilians have already been victims of some attempted fraud with Pix**. **One out of every five individuals being successfully scammed**.  
> Source: [Pix scam: find out what the most common cases are and how to protect yourself](https://www-cnnbrasil-com-br.translate.goog/economia/golpe-com-pix-saiba-quais-sao-os-casos-mais-comuns-e-como-se-proteger/?_x_tr_sl=pt&_x_tr_tl=en&_x_tr_hl=en&_x_tr_pto=wapp)

When we consider the bitcoiners' stance on privacy, the position clearly pays off because it protects citizens in a way that speaks for itself.

This is something that became increasingly clear as we worked on Chapter 06, which addresses the problems that arise from non-compartimentalizing personal information in the context of payments.

It is well known that governments have long fought against privacy in the context of financial transactions.

Nevertheless, we need to consider a scenario in which this changes. We also need to ponder over the possibility that governments around the world may find the systemic risks associated with the lack of privacy in public digital payment networks more concerning than the dangers associated with money laundering and terrorist financing.

This is especially true in an era of state-sponsored hacking operations, frequent data breaches, and powerful AI tools made available to the public.

These three factors can point to how the risk of not securing personal data at the foundational layers can lead to serious vulnerabilities that affect society as a whole.

With privacy layers such as [Lightning](https://en.wikipedia.org/wiki/Lightning_Network) and [Cashu](https://cashu.space/), the bitcoin community is not only paving the way for a secure alternative that can be used in emergencies and edge scenarios, but also setting an example and establishing a positive reference point that may be adopted as a mainstream standard in the future.

### Double-edged sword: tighter controls and more fluid money

When it comes to human rights, we believe it is fundamental to recognize that instant payment systems will both challenge and complement bitcoin in a nuanced dynamic.

Some of the countries most advanced in adopting instant payment systems are relatively unstable democracies.

In this sense, these new systems can pose serious risks to human rights, as they naturally consolidate power in the hands of the government.

Nevertheless, this issue needs to be approached with caution.

On one hand, it allows for government overreach, as observed when [Moraes ordered the blocking of Pix of a person that was being investigated of organising demonstrations against the government](https://veja-abril-com-br.translate.goog/coluna/maquiavel/moraes-manda-bloquear-pix-de-investigado-por-organizar-ato-antidemocratico?_x_tr_sl=pt&_x_tr_tl=en&_x_tr_hl=en&_x_tr_pto=wapp).

On the other hand, it makes it easier to set up the infrastructure for escaping the local currency. [Bipa](https://bipa.app/) is an excellent example, as it allows Brazilians to easily buy bitcoin with Pix. It even allows them to withdraw to their own self-custodial wallets via Lightning.

Rather than demonizing the system for being state-sponsored, it is more reasonable to recognize the dynamic, often complementary, often competing interplay between these modernized fiat rails and bitcoin.

### Generational shift

Finally, consider the experience that the generation born in Brazil after the release of Pix will have with money.

They will grow up in a highly connected world with very little exposure to physical money. At the same time, they will be used to making payments with QR codes on the street with Pix. At home, they will be sending money to their favorite video streamers via YouTube and Twitch.

How will this generational shift affect the adoption of bitcoin in the country?

We believe it may have a very positive impact, since this generation's experience with money will be digital from the beginning of their lives.

Bitcoin is also only 15 years old, and because of its inherent characteristics, it has the potential to become a foundational layer for the emerging digitized monetary landscape. However, it is far from being the only player.

If we wish to understand how bitcoin might be widely adopted in certain contexts, such as Latin America, it is essential to pay attention to recent developments, such as the adoption of Pix.

It feels like such an important phenomenon has been ignored by the community. Expectations and views of bitcoin adoption are better assessed in the context of the vast landscape of emerging and competing systems.

This perspective encourages a holistic approach to understand bitcoin's position in the evolving financial ecosystem.

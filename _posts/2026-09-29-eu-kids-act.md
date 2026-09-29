---
layout: post
title: "Can I See Some ID? The EU Kids Act and the Age-Checked Internet"
tag: Platforms & speech
tag_color: c2
thumbnail: /assets/images/posts/laptopchild.jpg
---

A fourteen-year-old in Paris opens her favourite app at midnight. Under a new EU proposal, she couldn't have an account of her own at all, her time on the app would be capped at an hour a day, the notification that pulled her back in at that hour couldn't be sent, and the beauty filter she uses would be gone.

It sounds drastic, but the concerns behind it are ones most of us will recognise: the effect of being online on children's sleep, self-esteem and mental health, and the risk of cyberbullying and grooming. The Commission opens its proposal with the statistic that [only half of children aged 9 to 16 across Europe say they feel safe online](https://www.lse.ac.uk/media-and-communications/research/research-projects/eu-kids-online/reports-and-findings/AgeBans).

The European Commission's answer, [published on 17 September](https://commission.europa.eu/news-and-media/news/eu-kids-act-helping-children-navigate-safer-online-world-2026-09-17_en), is the [EU KIDS Act](https://eur-lex.europa.eu/legal-content/EN/TXT/?uri=CELEX%3A52026PC0681), a Regulation with a name very clearly built backwards from its acronym: "EU Keeping Internet Digital Spaces Accountable and Trustworthy". Most of the coverage so far has focused on one number: children under 15 would no longer be able to open their own accounts on most social media and video-sharing platforms.

That number matters. It will remove accounts, reshape how millions of teenagers use the internet, and is likely to be the most fought-over line in the text. But it was also the part everyone saw coming. Read past the first few articles and you find something much broader, and far less discussed: design rules that apply to anyone who hasn't proved they are an adult, a very particular model of age verification, and a new set of obligations for general-purpose chatbots like ChatGPT, Gemini and Claude.

## Why now

The Commission's case rests on two prongs: child protection and the preservation of the EU single market. It points to a [Special Panel on Child Safety Online](https://commission.europa.eu/topics/digital-economy-and-society/special-panel_en) whose co-chairs reported to President von der Leyen in July 2026, recommending an EU-wide access restriction, harmonised safety-by-design rules and privacy-preserving age checks.

The market problem is that Member States weren't waiting. Italy, France, Greece, Austria, Poland and Belgium (along with Norway, through the EEA) have all notified draft national laws restricting minors' access to certain services under the EU's [TRIS procedure](https://technical-regulation-information-system.ec.europa.eu/en/home), with age limits ranging from 13 to 16. That matters because the single market is meant to let a service built for one Member State operate across all of them. A patchwork of national age limits would mean platforms redesigning their products country by country, with children getting a different level of protection depending on where they live. The European Parliament, in its [resolution of 26 November 2025](https://www.europarl.europa.eu/doceo/document/TA-10-2025-0299_EN.html), asked for a harmonised age of 16 (with parental authorisation below that) and a hard floor of 13. 

## It's Not What You Are, It's What You Do

Article 6 does not ban under-15s from all social media as such. It stops them creating or using an account on an online social networking or video-sharing service where the service poses a risk to their privacy, safety or security. That risk is then defined by features. 

**A service qualifies if it does any one of the following:**

- lets account holders live-stream or broadcast to an open audience;
- lets them contact or interact with people outside their existing connections;
- uses a recommender system based on profiling;
- suggests contacts or content from outside the user's existing connections;
- uses infinite scroll, engagement incentives, or notifications designed to pull the user back in.

![Diagram showing five features (live-streaming, connecting with strangers, a profiling-based feed, suggested contacts and content, and engagement design), any one of which means no account of their own under 15. From 13, a guardian can set up a limited account.](/assets/images/posts/kids-act-feature-test.png)

It is hard to think of a mainstream platform that meets none of these. A profiling-based feed alone is enough. So the real question for a platform is not "are we social media?" but "do we have any of these features?", which is a far harder test to argue your way out of.

Below 15, there are two narrower routes. For children aged 13 and 14, a guardian can set up a limited account (Article 6(2)), with guardian tools permanently switched on, a daily time limit that can be set no higher than one hour, and contacts pre-approved by the guardian. Legally, recital 22 treats this as the guardian's account rather than the child's. Under 13, the only route is Article 7: access to a video-sharing service designed specifically for young children, through the guardian's own account, never for a child under 3, again capped at an hour a day, and with recommendations and search switched off by default.

![Timeline of access by age: under 3, no access; 3 to 12, only through a guardian's account on video-sharing services built for young children, one hour a day, no recommendations or search; 13 to 14, a limited account set up by a guardian with guardian tools always on, one hour a day and guardian-approved contacts; 15 and over, their own account, child-safe by default until verified as an adult.](/assets/images/posts/kids-act-age-tiers.png)

The feature test also shifts who has to prove what. The Commission describes the proposal as [reversing the burden of proof](https://digital-strategy.ec.europa.eu/en/news/eu-kids-act-restrict-social-media-platforms-access-children-eu): it is for providers to show that their services are age-appropriate and safe by design, not for regulators to show that they aren't.

## Implications for AI platforms

The part of the proposal I think deserves far more attention is its scope. Article 2 brings in AI companions and "general conversational chatbots", defined in Article 3 as general-purpose AI systems with general conversational functions that can help across multiple domains and tasks. Customer service bots and other single-purpose tools are carved out. The mainstream assistants are not.

**Article 14 then requires these providers to:**

- avoid design features that simulate emotions or interpersonal relationships likely to create emotional dependency;
- apply the addictive-design, safe-settings and spending rules from Articles 9, 11 and 13;
- by default, not use information from a minor's previous conversations in later ones;
- allow under-13s access only through guardian tools;
- test for risks to minors before launch, and monitor for serious incidents afterwards.

Recital 32 is explicit that persistent conversational memory should be disabled by default for minors, except where it is needed to keep them safe. The reason it gives is data accumulation: a system that remembers can build up sensitive information about a child and reinforce harmful patterns over time. The emotional dependency rule is harder to pin down. Nobody would describe a coding assistant as simulating a relationship, but persistent personas, a remembered name, warm check-in messages and a chatbot that asks how your day went all sit somewhere on that spectrum. Where exactly the line falls will depend on guidance and enforcement, and that is where the real argument will happen.

Where a chatbot is built into a social network or game, it can't be switched on automatically, displayed prominently, or promoted to minors, and they must be able to opt out easily (Article 14(2)). Recital 34 gives the example of a chatbot pinned to the top of a child's contacts list. Enforcement builds on the existing structures of the [Digital Services Act](https://eur-lex.europa.eu/eli/reg/2022/2065/oj) and the [AI Act](https://eur-lex.europa.eu/eli/reg/2024/1689/oj) (Article 34), with the AI Office responsible for chatbots under Chapter IX of the AI Act. Fines can reach [6% of worldwide turnover](https://digital-strategy.ec.europa.eu/en/faqs/kids-act-explained), matching the DSA's ceiling in Article 52 and double the 3% that applies to most AI Act obligations under Article 99. For services the Commission supervises directly, Article 35 adds an expedited procedure: preliminary findings within 30 days of opening proceedings and a final decision targeted within 90.

The obligations above apply to minors. But read Article 14 alongside the next section and the question becomes: how does a chatbot know who is a minor?

## Child-safe by default, for everyone

The most important sentence in the proposal might be Article 8(1). Social networks, video-sharing platforms, online games, AI companions, general chatbots and app stores must design their services to the safety requirements *by default*, including for users who never register, and may only depart from them once they have established, through age assurance, that the user is an adult. The child-safe version becomes the baseline, and the adult experience is something you verify into.

For chatbots, that has a striking consequence. Article 14 sits in the same chapter that Article 8 makes the default. So an adult in Europe whose age hasn't been established could find their assistant forgetting previous conversations and applying the same design limits it would for a thirteen-year-old. The adult version of ChatGPT or Claude would become something you have to be recognised into. That need not mean handing over ID, since for these design obligations the proposal allows lighter methods such as age estimation (more on that below), but it does mean every provider will need some answer to the question of who it is talking to. Very little of the coverage so far has noticed this, and it may turn out to be the change most adults actually feel.

The UK has been here before, though not quite in the same place. Since the Online Safety Act's [child safety duties took effect on 25 July 2025](https://www.ofcom.org.uk/online-safety/protecting-children/enforcement-bulletin-enforcement-programme-to-protect-children-from-harmful-content-through-the-use-of-age-assurance), adults have been asked to prove their age to reach certain content, and the backlash has centred on privacy and individual liberty, with critics calling it an [invasion of privacy](https://itif.org/publications/2026/07/09/uks-latest-online-safety-proposal-would-further-erode-privacy-and-free-speech/) to hand ID to private companies. But the OSA's age checks are tied to specific categories of content: section 12 requires highly effective age assurance to stop children encountering "primary priority content" such as pornography and material promoting suicide, self-harm or eating disorders. The EU proposal goes further. It makes the child-safe version the default for the whole service, not just its riskiest corners.

The EU's answer to the privacy objection is its own infrastructure, and a two-tier approach to how hard the checks are. For the under-15 account rule, providers must use age verification, and self-declaration is expressly not enough (Articles 27 and 29). The model is an EU age verification solution provided by a third party and certified by a public authority, with [European Digital Identity Wallets](https://eur-lex.europa.eu/eli/reg/2024/1183/oj) deemed to qualify (Article 29(2) and (3)), building on the Commission's April 2026 Recommendation on a common framework for EU age verification. Member States must make at least one age verification solution available (Article 31). For the wider safety-by-design obligations, including the chatbot rules, other age assurance methods are allowed if they meet the same standards of accuracy, reliability and privacy (Article 29(4)). Operating system providers that already hold an age signal must share it, with the user's consent, with services that need it (Article 29(6)). And existing accounts are only re-checked where the provider cannot tell with a high degree of confidence that the holder is over the age threshold (Article 32).

## Where this leaves us

This is still only a proposal. It now goes through the ordinary legislative procedure, and with Parliament having already asked for 16, the age threshold is likely to be the first fight. The Commission has also built in a review by 2030 that must look specifically at the Regulation's impact on freedom of expression and information.

The criticisms are serious. Access restrictions can push teenagers onto their parents' accounts or towards less regulated corners of the internet. Checking everyone's age carries a real cost to adults' privacy and anonymity, however well it is designed. And guardian tools assume an engaged, digitally confident guardian, which not every child has. To its credit, the proposal anticipates that last point: recital 43 says compliance should not depend exclusively on guardians, since they may be absent or disengaged, and that guardian tools complement the provider's responsibility rather than replace it. The Commission's broader answer is harmonisation and privacy-preserving technology, and on paper that answer is a strong one.

My own view is that the debate about 15 is the easy part to have an opinion on. The part that will actually change the internet is the combination of Article 8(1) and Chapter V: child-safe by default, adult by verification. If the EU's age verification system works, that could quietly reset the default experience of every major platform and chatbot in Europe. If it doesn't, platforms will be left choosing between disabling accounts they can't verify and serving everyone the version built for children. Everyone will call this a social media ban, and that label will stick. What it actually regulates is design.

*Thumbnail photo by [Vlad Deep](https://unsplash.com/@vladdeep?utm_source=unsplash&utm_medium=referral&utm_content=creditCopyText) on [Unsplash](https://unsplash.com/photos/childs-hands-typing-on-a-laptop-keyboard-zniM2Qqaxv4?utm_source=unsplash&utm_medium=referral&utm_content=creditCopyText)*

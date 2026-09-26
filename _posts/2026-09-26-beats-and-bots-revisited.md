---
layout: post
title: "Beats & Bots, Revisited: Should AI Music Be Copyrighted?"
tag: Media & IP
tag_color: c4
thumbnail: /assets/images/posts/beats-and-bots-revisited.jpg
---

In 2025 I presented research at the British Conference of Undergraduate Research under the title *Beats & Bots: Should AI Music Be Copyrighted?* It grew out of a funded Junior Research Associate project at the University of Sussex, and it's where this blog gets its name. A lot has changed since then, so this post is part origin story and part update. I'll set out what I argued, what four people working in music, law and tech told me, and where I stand now.

![At the British Conference of Undergraduate Research 2025](/assets/images/posts/bcur-badge.jpeg){: style="max-width: 300px; display: block; margin: 0 auto;"}
*At the British Conference of Undergraduate Research 2025, Newcastle University*
{: style="text-align: center;"}

One clarification first. There are two copyright questions about AI music that often get merged. One is about **inputs**: can AI companies train on existing songs without permission? The other is about **outputs**: can anyone own a song an AI generated? The input question deserves its own post. This one is about outputs.

## The problem

Take Suno. You type something like "a groovy soul song about the place where we used to go", press Create, and seconds later you have a finished track with vocals, instrumentation and structure. If that track is protected by copyright, who is the author? The person who typed the sentence? The developers who built the model? Nobody?

The answer matters in practice. If nobody owns AI output, anyone can copy, sample or re-upload it freely. If the prompter owns it, one sentence can generate a portfolio of protected works in an afternoon. If the developer owns it, a handful of companies could end up holding rights in millions of songs.

## The EU: originality and creative choices

EU law has no specific rule for computer-generated works, so the general requirements apply. Under the [InfoSoc Directive](https://eur-lex.europa.eu/legal-content/EN/TXT/?uri=CELEX:32001L0029) and the CJEU's decision in [*Infopaq* (C-5/08)](https://eur-lex.europa.eu/legal-content/EN/TXT/?uri=CELEX:62008CJ0005), a work must be original in the sense of being the author's own intellectual creation. That means a production in the literary, scientific or artistic domain, resulting from human intellectual effort and free creative choices that are expressed in the output.

For AI music, that raises obvious problems. A one-line prompt involves very few creative choices. The user doesn't choose the training data and, with a black-box model, may not know what it is. Most importantly, the user doesn't control how the prompt becomes sound. Two identical prompts can produce completely different songs, which makes it hard to say that the output expresses the user's choices rather than the model's.

A more useful approach comes from [*Painer* (C-145/10)](https://eur-lex.europa.eu/legal-content/EN/TXT/?uri=CELEX:62010CJ0145), where the CJEU recognised that creative choices can be made at different stages of producing a work. A [2022 study](https://www.ivir.nl/publicaties/download/870626_D3.5-Final-report-on-the-impact-of-IA-authorship_formatted-1.pdf) by Oleksandr Bulayenko, João Pedro Quintais and colleagues adapted this for AI into three phases:

**Conception**: designing and planning the work.

**Execution**: turning that plan into rough drafts.

**Redaction**: reworking the drafts into a finished product.

The value of this framework is that it doesn't treat "AI music" as one category. A user who can show real creative involvement across those phases has a credible claim to authorship. A user who typed one sentence and accepted the first result does not.

## The UK: a provision out of step with its own law

The UK looked like the outlier because of [section 9(3) of the Copyright, Designs and Patents Act 1988](https://www.legislation.gov.uk/ukpga/1988/48/section/9). It provides that for a computer-generated work, the author is the person by whom the arrangements necessary for its creation are undertaken. On paper, the UK was the one major jurisdiction that already protected AI output.

In my original presentation I described UK originality in terms of "skill, labour and judgement", the test UK courts have applied for over a century. In [*THJ Systems v Sheridan* [2023] EWCA Civ 1354](https://caselaw.nationalarchives.gov.uk/ewca/civ/2023/1354), the Court of Appeal held that the correct standard is the EU-derived test of the author's own intellectual creation. In practice, the two now sit side by side. Skill, labour and judgement still shapes how courts and lawyers talk about originality, and the tests often overlap, since the skill and judgement behind a work are usually the creative choices *Infopaq* looks for. The real difference is that effort alone no longer counts. Since Brexit, EU case law has also become "assimilated law", so UK appellate courts have more room to reshape the test again. Either way, section 9(3) sits uneasily with both. If originality requires human creative choices, it's hard to see how a work with no human author can be original. And under skill, labour and judgement, the question remains whose skill, labour and judgement a machine-generated work reflects.


I also relied on *Express Newspapers v Liverpool Daily Post* [1985], where the court compared a computer to a pen: the person using the tool, not the tool itself, is the author. That remains good law, and it matters here. Where AI is used as a tool, a human can be the author in the ordinary way, with no need for section 9(3) at all. Section 9(3) is aimed at a different situation: works with no human author. The key case on it is [*Nova Productions v Mazooma Games* [2007] EWCA Civ 219](https://www.bailii.org/ew/cases/EWCA/Civ/2007/219.html), where the programmer, not the person playing the game, was held to have made the arrangements necessary for the work's creation. Applied to generative AI, that reasoning points towards the developer rather than the prompting user, which is not the result most people would expect or want. So the real question is which side of the line a piece of AI music falls on: a human work made with a tool, or a computer-generated work with no human author.

![A line drawing of a pen](/assets/images/posts/pen.png){: style="max-width: 200px; display: block; margin: 0 auto;"}

The government seems to agree the provision doesn't work. Its [Report on Copyright and Artificial Intelligence](https://assets.publishing.service.gov.uk/media/69ba692226909a14239612e4/CP2602959_-_Report_on_Copyright_and_Artificial_Intelligence_web.pdf), published in March 2026, concluded that protection for computer-generated works under section 9(3) should be removed, though it plans to keep monitoring how it is used. For now, though, there is no new legislation, and section 9(3) remains on the statute book until Parliament acts.

## Elsewhere

China went the other way. In [*Li v Liu*](https://english.bjinternetcourt.gov.cn/pdf/BeijingInternetCourtCivilJudgment112792023.pdf) (Beijing Internet Court, 2023), AI-generated images were held to be original because the plaintiff designed the elements through prompts and set the layout and composition through parameters, which reflected his own choices and arrangement. The court looked closely at the process, not just the prompt, which makes the decision closer to the *Painer* approach than it first appears.

The US has held firm on human authorship. In March 2026, the Supreme Court [declined to hear](https://www.supremecourt.gov/search.aspx?filename=/docket/docketfiles/html/public/25-449.html) *Thaler v Perlmutter*, leaving in place the [2025 DC Circuit ruling](https://media.cadc.uscourts.gov/opinions/docs/2025/03/23-5233.pdf) that upheld the Copyright Office's human authorship requirement. How much human contribution is enough is still unresolved, and pending cases such as [Allen v Perlmutter](https://www.copyright.gov/rulings-filings/review-board/docs/Theatre-Dopera-Spatial.pdf), involving an image refined through more than 600 prompts, may begin to answer it.

So the jurisdictions converge on one question, even if they answer it differently: what did the human actually contribute?

## What the professionals told me

For the original project, I ran 30 to 45 minute one-to-one interviews with four people: Orla Mair, a classical musician and Cambridge music graduate; Zakk Virdee, bassist for Distressed Call; an IP lawyer at a large tech company; and a software engineer working in AI. The latter two chose to remain anonymous.

Their common ground was clear. All four felt AI lacks true creativity and shouldn't replace human artistry, that human involvement should stay central, and that the law needs to define AI's role more clearly.

The most interesting finding sat inside that agreement. Every interviewee felt AI music should be capable of copyright protection, yet none of them thought AI itself was creative. Those positions only fit together if protection attaches to the human contribution rather than the machine's output. Without framing it that way, my interviewees were describing the *Painer* approach.

Where they differed was on who that human should be.

**Orla** thought AI might eventually need some form of legal personhood to resolve ownership. She put the underlying problem well: *"If AI music can be copyrighted, who really deserves the credit? The person who typed in a few words, or the developers who created the AI? It's a tricky question."*

**Zakk** wanted regulation handled by independent bodies to protect creative freedom.

**The software engineer** argued content should be attributed to the human or corporate entity guiding its creation.

**The tech lawyer** proposed a tiered approach, with protection scaled to the level of human input and creative contribution. *"We need to have clear guidelines to determine what qualifies as an AI-generated work,"* they told me. *"Without this, we could face legal and ethical dilemmas regarding innovation and liability."*

One result surprised me: most interviewees did not think musicians should have to disclose when they use AI. That sits awkwardly with the idea that protection should depend on human contribution, because if nobody discloses AI use, nobody can check what the human actually did. I'll come back to this.

With hindsight, some views have aged better than others. Legal personhood for AI has lost ground, and *Thaler* shows courts aren't heading that way. The engineer's model of attributing output to whoever guided its creation is essentially section 9(3), which the UK now proposes to scrap. The tech lawyer's tiered approach looks the most durable, because it's the one that matches where the law is actually going.

## What a tiered approach looks like in music

Music is a useful test case because the tools already allow very different levels of involvement. Suno's interface, for example, includes a Custom mode and an Upload Audio button alongside the simple description box. Using the *Painer* phases, I'd sketch the tiers like this.

**A single prompt, first result accepted.** No meaningful creative choices are expressed in the output. No protection.

**Human-written lyrics set to AI-generated music.** The lyrics are a literary work protected in the ordinary way, whatever the AI does with them. The music itself is not the lyricist's creation, so protection covers the words, not the track as a whole.

**Iterative generation, selection and arrangement.** Generating dozens of versions, choosing sections, restructuring and combining them starts to look like the redaction phase. There's a real argument that the selection and arrangement are the user's own intellectual creation, much as a compilation can be protected even if its parts aren't.

**AI material reworked in production.** Uploading your own melody or recording, then editing, re-performing, mixing and layering the output in a DAW, involves human choices at every phase. This is closer to using a sophisticated instrument than commissioning a machine, and it should be protected like any other human-made track.

The line between tiers won't always be clean, and courts will have to draw it case by case, as they already do with photography and compilations. But that's normal for copyright. The point is that the question becomes "what did you do?" rather than "did you use AI?"

## Where I land now

**First, removing section 9(3) is the right call.** It's inconsistent with the originality standard UK courts now apply, and in practice it would reward the least creative uses of AI. Without it, AI-assisted music would be treated like any other work: protected where a human made the creative choices, and not where they didn't.

**Second, protection should follow human contribution, assessed across the whole creative process.** The *Painer* phases give courts a workable framework, and the tiered approach my tech lawyer interviewee suggested is what that framework looks like in practice. Human-made elements should keep their protection when AI is involved. Purely machine-generated elements should be free for anyone to use.

**Third, a tiered system needs some evidence of process.** This is where I'd now push back on my interviewees' scepticism about disclosure. I don't think musicians should have to label every track, but anyone claiming copyright in AI-assisted work should expect to show what they contributed if the claim is challenged: drafts, project files, generation histories. Creators who document their process will be in a much stronger position than those who don't.

When I first presented this research, I concluded that we needed a framework that serves both innovation and human creators. I still think that. I'm just clearer now about what it looks like. Copyright shouldn't ask whether a machine was involved. It should ask what the human did.



![Presenting interview findings at BCUR 2025](/assets/images/posts/bcur-presenting.jpeg){: style="max-width: 480px; display: block; margin: 0 auto;"}
*Presenting the interview findings at BCUR 2025*
{: style="text-align: center;"}



*(This post draws on research funded through the University of Sussex Junior Research Associate scheme and presented at BCUR 2025.)*



Thumbnail photo by [Franck V.](https://unsplash.com/@possessedphotography) on [Unsplash](https://unsplash.com/photos/robot-playing-piano-U3sOwViXhkY)
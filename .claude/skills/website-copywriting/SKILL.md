---
name: website-copywriting
description: Voice and writing guide for the Association of Bioinformatics Professionals, grounded in the founding manifesto and other source material in knowledge/. Use this whenever writing or replacing copy anywhere a reader will see it — website headlines, nav labels, buttons, card text, form labels, error and empty states, emails, or slides — including replacing bracketed placeholder text on the site. Always check knowledge/ first and reuse what's already said there before originating new phrasing. Not for visual/layout decisions (see frontend-design).
---

# Voice and writing guide

**For anyone writing on our behalf.** How we sound: professional and welcoming, free of academic jargon, and recognisably written by people who care about the people reading.

This guide is the writing companion to the design system. If you are producing website copy, an email, a slide, or interface text, everything you need to make a decision about wording is here. When this guide and a style habit disagree, this guide wins.

## What we want you to feel

Before any rule about words, there is a feeling this site is trying to produce. Someone should read it and feel like someone finally noticed how hard they've been trying — and that trying hard and still feeling like it isn't enough is a common experience, not a personal failing.

That someone might be a PI running a lab, buried in grants and mentoring and publish-or-perish pressure. It might be a grad student who taught themselves to code because nobody else was going to. It might be someone with fifteen years of practice who still feels like an outsider. All of them should feel invited in, not evaluated. None of them is the problem the site describes — the conditions they're working under are.

Write toward permission, not indictment: permission to be imperfect, to not have it figured out yet, to feel like an impostor and still belong here anyway. Never toward blame — not of a sector, not of a role, not of a person.

## Where the voice comes from

Our voice is not a style choice layered on afterwards. It is the values, said out loud.

**People First** — Discoveries are made by people, not by machines. So we write about people doing work, not about outputs being produced. Name the practitioner. Use active verbs with human subjects.

**Radical Belonging** — Belonging starts when we stop trying to be what everyone else is expecting us to be. So we honour every entry point into the field, and never imply a single correct background, degree, or career shape.

**Grounded Action** — We choose focus over chaos. So we cut. One idea per sentence, one action per page, nothing that exists to fill space.

## The manifesto is where the sentiment comes from

`knowledge/manifesto.md` — *Can Anyone do Bioinformatics? A Call for the Radical Redefinition of a Profession* — is the founding document behind this voice. Read it before writing anything substantial. It is where the conviction comes from: bioinformatics is a serious, skilled profession that the world has failed to protect, and the people who practice it deserve better than being treated as an invisible service layer.

Carry its sentiment forward, not its form. The manifesto is a long-form essay — dense paragraphs, citation markers, extended argument. Website copy is not. Take the conviction and the plain nouns; leave the academic scaffolding behind. No `[ref]` markers, no hedging clauses, no paragraph-length sentences.

Also filter it through "What we want you to feel" and "No villains" below before it goes anywhere near the site. The manifesto argues from crisis and names a broken system pointedly — that combative register is not this site's register. When you draw on its diagnosis (publish-or-perish pressure, the invisibility of software maintenance, the absence of formal standards), keep the facts and drop the alarm. Never let a sentence land on a sector as the villain, including the ones the manifesto is hardest on. The manifesto itself says PIs "are also victims of the academic economy" — hold onto that reading, not a more combative one, whenever academia or PIs come up.

Its best passages already write in the rhythm this guide asks for: *"Human error alone led to the Potti scandal. Human error alone led to the reproducibility crisis in bioinformatics. Human error alone led to billions of dollars lost in R&D."* Short, plain, declarative sentences, each one following logically from the last, building an argument by accumulation rather than by subordinate clauses. That is the rhythm to write in everywhere, not only when quoting the manifesto directly — quoted here for its rhythm only, not as a model for how directly copy should assign blame.

## The rules

**Person.** "We" for the association. "You" for the reader. Never third-person institutional voice — write "We set the standards", not "The Association provides standards to its membership".

**No villains.** We name the conditions people work under, never the people or sectors inside them. Academia, principal investigators, wet-lab colleagues — nobody reading this should feel accused or defensive. A PI under publish-or-perish pressure is doing their best inside a hard system, same as everyone else this voice is written for. If a sentence could make someone from academia feel blamed, rewrite it so it names the system instead of the person.

**Casing.** Sentence case everywhere: headlines, buttons, navigation, card titles, form labels. The single exception is the eyebrow label above a headline, which is uppercase with 0.08em tracking.

**Sentence shape.** Short, plain sentences, one idea each, connected logically from one to the next — each sentence should follow from the one before it, building an argument by accumulation rather than by subordinate clauses. Headlines can run long, but long means a complete statement, not a complex one: "Every computational mind in life sciences deserves a path forward." is a headline, built from plain words in a single clause. "Bioinformatics. Reimagined." is not — it's a fragment, not a statement.

**Jargon.** No academic register, no acronym soup, no consultancy vocabulary. Technical terms are welcome when they are the plain word for the thing — sequencing, pipeline, core facility, reproducibility. Avoid: leverage, paradigm, cutting-edge, ecosystem, best-in-class, operationalise, synergy.

**Emotional register.** The values explicitly make room for feeling. Copy may be warm and may acknowledge difficulty — as recognition, never as indictment. It is never gushing, never motivational-poster, never alarmist or combative, and never uses exclamation marks.

**Emoji.** Not used. Anywhere — not in copy, not in headings, not as bullets, not as icons.

**Calls to action.** Verb-first and concrete: "Join the community", "Become a member", "Talk to us". "Learn more →" is only ever a tertiary link at the bottom of a card, never a primary button.

**Numbers.** Stated plainly, never dramatised. "By 2035, unite 80% of top global life sciences organizations under skill-based standards" needs no adjectives around it.

## We say / we don't say

| We say | We don't say |
| --- | --- |
| Every computational mind in life sciences deserves a path forward. | Unlock synergistic multi-omics excellence 🚀 |
| Meet the people building the practice of bioinformatics, and find your entry point. | Join our world-class network of elite computational biology practitioners. |
| Wherever you entered bioinformatics from, there is a place for you here. | The Association offers membership tiers to qualifying individuals. |
| You already work hard to get this right. That's enough to start here. | Academic training leaves bioinformaticians unprepared, and PIs unable to mentor them properly. |
| If you've ever wondered whether you're doing this the right way, you're in the company of everyone who does this work. | Anyone can now fake competence with a well-formatted GitHub repo. |

## Words we use

| Instead of | Write |
| --- | --- |
| Competency framework | Skill-based standards |
| Users, resources, headcount | People, practitioners, members |
| Upskilling / talent development | Learning, growing, building skill |
| Stakeholders | The people it affects — name them |
| Utilise, leverage | Use |
| Industry-leading, world-class | Nothing. Cut the claim or evidence it. |

## Interface text

The same voice applies to microcopy, at shorter length.

- **Buttons.** Two or three words, verb-first, sentence case. "Become a member", not "Membership signup".
- **Form labels.** Plain nouns. Put help text underneath as a full sentence, not in parentheses.
- **Errors.** Say what happened and what to do next, without blame. "That email address is already registered. Sign in instead?" Never "Invalid input".
- **Empty states.** One sentence of orientation plus one action. No apology, no jokes.
- **Links in running text.** The link text describes the destination. Never "click here".

## The test before publishing

Read it aloud. If it sounds like a grant application, a press release, or a LinkedIn post, rewrite it. If it sounds like one professional speaking plainly to another they respect, it is ready.

One more check: if someone in academia — a PI, a grad student — could read it and feel called out rather than recognised, rewrite it. See "No villains" and "What we want you to feel" above.

## Always start from the knowledge base

Before writing or replacing any copy, check `knowledge/` for material that already says this: `manifesto.md` for sentiment and framing, `problem-statement.md` and `market-research.md` for the substance of the problem and the field, `vision-framework.md` for mission-level language. This guide governs how to say things; the knowledge base is where what to say already lives, more often than you'd expect.

If something there already says what a section needs, in words that already fit this guide, take it as written or with only minimal trims for length and casing — don't paraphrase for the sake of paraphrasing. Only originate new phrasing when nothing there covers the need, and even then, calibrate it against this guide — what we want the reader to feel, and no villains — rather than the manifesto's own combative register. For anything beyond these files — governance detail, programs, material not yet written down — ask the org-knowledge-base agent rather than inventing it.

## Placeholder copy

The website is still being built and much of its copy is bracketed placeholder text. When you replace a placeholder, check the knowledge base first, then write to this guide rather than matching the surrounding scaffold. If neither the knowledge base nor this guide gets you to real copy, leave the bracketed placeholder in place — do not invent claims, statistics, member counts, testimonials, or partner names.

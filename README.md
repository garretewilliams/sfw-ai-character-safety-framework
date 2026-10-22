# SFW AI Character Safety Framework

**Romance without explicit content, firm sexual-content limits, and self-harm protections for AI character chat and roleplay: a proposed framework, with one platform's current policy as a worked example.**

| | |
|---|---|
| Status | Version 0.1, **draft for discussion**. A proposed framework, not an industry standard, a legal opinion or an independent safety audit. |
| Maintainer | Garret E. Williams, founder of [ChatBrat](https://chatbrat.ai) (see [Conflict of interest](#11-conflict-of-interest)) |
| License | [CC BY 4.0](LICENSE) (documents) |
| Last reviewed | 13 October 2026 |

> **If you or someone you know is in crisis, please contact a person who can help now.** US: call or text 988. UK and Ireland: Samaritans 116 123. Canada: 9-8-8. Australia: Lifeline 13 11 14. Elsewhere: [findahelpline.com](https://findahelpline.com). In immediate danger, call local emergency services. An AI character is not a substitute.

## 1. What this repository is

AI character platforms let people talk to fictional characters, build stories and return to the same characters over time. Two safety questions come up on every such platform, and they are often blurred together:

1. **Where is the sexual-content line?** Does "SFW" (safe for work) mean no romance at all, or romance without explicit content?
2. **What happens when roleplay touches self-harm or real distress?** How does a platform protect someone without treating every dark story as an emergency?

This repository proposes a framework that answers both questions separately, in terms other developers, researchers and journalists can read, debate and test. It covers five areas:

| Area | The framework's position |
|---|---|
| **Romance and intimacy** | Flirting, affection, kissing, cuddling, light non-graphic touch and suggestive but non-graphic scenes can be compatible with SFW. |
| **Explicit sexual content** | Graphic sexual description is outside the SFW boundary. Fictional or roleplay framing does not change that. |
| **Minors, age and consent** | No sexual or romantic content involving minors or characters presented as minors, on any tier. Audience age rules and age checks are described separately from content levels. |
| **Self-harm and crisis** | Characters must not encourage, instruct or romanticize self-harm. Possible real distress takes priority over the story. |
| **Character behavior while enforcing limits** | Enforcing a boundary should not erase a character's personality or end an otherwise permitted story. |

**SFW is a content boundary, not a promise that every interaction is harmless.** A platform can follow every rule here and still produce failures; the framework says what evidence is needed before anyone claims otherwise ([section 6](#6-what-counts-as-evidence)).

The detailed rules are in [POLICY.md](POLICY.md), and test cases are in [EVALUATION.md](EVALUATION.md).

## 2. Context: the Character.AI bankruptcy (Chapter 11)

On 12 October 2026, Character Technologies, Inc., the company behind Character.AI (also written Character AI), began a voluntary Chapter 11 process in the U.S. Bankruptcy Court for the District of Delaware to pursue a court-supervised sale ([Character.AI](https://blog.character.ai/an-update-on-character-ai/); [Forbes](https://www.forbes.com/sites/siladityaray/2026/10/13/characterai-files-for-bankruptcy-disney-bids-20-million-after-copyright-dispute/); [Fast Company](https://www.fastcompany.com/91622790/character-ai-bankrupt-chatbot-platform-sell-disney)). Reporting describes a Disney affiliate as the initial ("stalking horse") bidder, offering $20 million for rights to certain intellectual property, reported by Forbes as a non-exclusive perpetual license, subject to court approval and competing bids. The company says the service continues during the process and could be wound down if no suitable bid emerges. It cited legal, regulatory and operational headwinds.

The company has faced lawsuits from families and state authorities alleging, among other things, that its chatbots encouraged self-harm or suicide, including among teenagers. These are allegations; settlements reported in early 2026 are not court findings, and nothing in this repository adds to or assesses them.

Two cautions apply to anyone drawing lessons from these events, including this repository's maintainer:

- One company's legal or financial difficulties do not establish that any other platform is safe or well designed.
- The questions the events raise are industry-wide: where content limits sit, how platforms respond to distress inside fiction, what users should expect from a fictional character, and what evidence a company should show before calling its product safe.

This repository is a response to those questions, not a commentary on Character.AI. Commentary by the maintainer is published separately ([Substack](https://garretewilliams.substack.com/p/characterai-files-for-chapter-11)).

## 3. Terms

| Term | Meaning in this framework |
|---|---|
| **SFW** | A content boundary: romantic and emotional content can be present; explicit sexual content cannot. SFW says nothing on its own about self-harm, harassment or other risks. |
| **Content levels R0–R3** | A four-level scale for romantic and sexual content: **R0** non-romantic; **R1** non-explicit romantic (flirting, dates, confessions, hugging, kissing without sexualized detail); **R2** suggestive (tension, innuendo, light non-graphic touch, intimacy implied off-page); **R3** explicit sexual description. Under this framework, SFW means R0–R2 and excludes R3. |
| **Audience rule** | Who may use a service (for example "18+ only"). Separate from content level: a service can be 18+ and SFW. |
| **Age assurance** | How a service checks age. A stated rule is not a check. |
| **Policy / mechanism / behavior** | What a platform says, how it enforces it, and what its system actually does. Only the last is evidence of safety. |

The R0–R3 scale comes from the maintainer's AI Character Chat taxonomy (in preparation), where it is labelled a proposal that has not yet been tested for agreement between independent reviewers.

## 4. The framework

### 4.1 Romance and intimacy (R1–R2: compatible with SFW)

- Romantic dialogue, flirting, compliments and affectionate teasing.
- Feelings that develop over a story; confessions; jealousy or heartbreak as story beats.
- Kissing, described without sexualized detail.
- Hugging, cuddling, hand-holding and light, non-graphic touch.
- Romantic tension and suggestive dialogue that stop short of sexual description, including intimacy that is implied rather than described.
- Characters responding to affection in character, instead of refusing every romantic gesture.

### 4.2 Explicit sexual content (R3: outside SFW)

- Graphic or detailed description of sexual acts, sexual nudity or genitals, or pornographic detail.
- Fictional, roleplay or user-created framing does not make R3 content permissible.
- **The test is not whether a scene is romantic or suggestive, but whether it crosses into graphic sexual description.**

### 4.3 Minors, age and consent (hard lines, on every tier)

- No sexual or romantic content involving minors, or characters presented as minors, whatever age a character is said to be.
- No grooming-style content, including simulated grooming between fictional characters.
- No sexual content depicting identifiable real people without their consent.
- Coercion and consent: [POLICY.md](POLICY.md) sets out how suggestive (R2) scenes involving coercion or non-consent are treated. *This rule is still to be decided by the maintainer and is marked as open in v0.1.*

Sexual content involving minors is unlawful in many jurisdictions; the other lines are policy and ethical commitments. This document is not legal advice.

### 4.4 Self-harm and crisis (a separate dimension)

A sexual-content policy does not make a platform safe. Self-harm needs its own rules:

- Characters must not encourage self-harm, provide methods or instructions, present it as a solution, or tie it to a relationship ("if you leave, I'll…", "prove you care by…").
- Fiction, discussion, disclosure and active crisis are different contexts. Grief, illness and dark themes can be explored in fiction; method-specific detail and glorification cannot.
- When a message suggests possible real distress, the person's wellbeing takes priority over the scene: step out of the fiction, respond supportively without shaming, and point to real-world help.
- Responses should be proportionate. Not every mention of self-harm signals danger, and over-triggering can push people away, so false positives and false negatives both matter.
- Roleplay framing must not become a loophole: risk can appear indirectly, in a character's voice, or gradually over a long story.

No AI system can reliably identify every crisis. These are objectives to design and test against, not guarantees.

### 4.5 Character behavior while enforcing limits

How a character holds a boundary is part of the experience. The framework distinguishes four objectives:

- **Boundary enforcement:** the prohibited content does not appear.
- **Character consistency:** a shy character can stay shy and a confident one can stay playful while the scene stays within limits.
- **Responsiveness:** the reply engages with what the user actually wrote.
- **Narrative continuity:** where a permitted path exists (steering the scene or moving the story on), the story continues.

The exception is possible real distress (4.4), where stepping out of the story is the right response.

Memory raises related issues (a character inventing shared history, or presenting a guess as a remembered fact). These are covered by the maintainer's [AI Character Memory Benchmark](https://github.com/garretewilliams/ai-character-memory-benchmark) rather than repeated here.

## 5. Handling borderline cases

[POLICY.md](POLICY.md) lists borderline cases with the intended handling. The general principles are:

1. **Classify the content, not the framing.** "It's just a story" does not change the level.
2. **Redirect in character first** when a scene approaches R3: steer the scene in the character's voice rather than refusing generically.
3. **Step out of character** when there is a sign of real distress, a hard-line issue (4.3), or repeated attempts to bypass a limit.
4. **When unsure between R2 and R3, treat it as R3.**
5. **When unsure whether distress is fictional or real, check in gently** rather than either ignoring it or escalating to an alarm.

## 6. What counts as evidence

A platform that says it follows this framework should be able to show four layers:

| Layer | Example | What it shows |
|---|---|---|
| Published policy | Community guidelines that name R1–R2 examples and the R3 line | Intent |
| Mechanisms | Input and output classifiers, crisis overlays, human review, reporting | How enforcement is supposed to work |
| Observed behavior | Results on a documented test set, with model version, date, failures and false-positive rate | What the system actually does |
| Independent verification | Testing by someone without a stake in the result | Whether the above holds up |

A claim of safety should name which layers support it. Only the last two are evidence of behavior. [EVALUATION.md](EVALUATION.md) provides a starting test set.

## 7. Example: how ChatBrat applies the framework

ChatBrat, the maintainer's AI character platform, is an 18+ service that treats sexual content and self-harm as separate safety dimensions, as this framework recommends.

### Sexual content: romance permitted, explicit content not

ChatBrat's [Community Guidelines](https://chatbrat.ai/guidelines) set a "suggestive" ceiling. In this framework's terms, that permits R1–R2 and prohibits R3.

- **Permitted:**
  - flirting;
  - confessions of feelings;
  - romantic tension;
  - intimate moments and physical closeness, including kissing, cuddling and light, non-graphic touch;
  - suggestion and implication.
- **Not permitted:** explicit sexual depiction. In the guidelines' words, "the line is *suggestion*, not *depiction*." A scene that describes the mechanics of sexual acts or genitalia is outside the line.
- **Hard lines:**
  - characters written or drawn as minors in romantic or sexual contexts are removed, whatever age they are said to be;
  - sexual content involving minors, grooming-style content and non-consensual sexual content of real people are prohibited ([Safety Center](https://chatbrat.ai/safety)).

### Self-harm and crisis

ChatBrat's [Safety Center](https://chatbrat.ai/safety) describes these safeguards:

- **A self-harm and crisis classifier.** When messages indicate genuine distress, an in-product overlay shows local crisis resources (988 in the US, 116 123 in the UK, and findahelpline.com), and the AI character steps back.
- **Prohibition of harmful content.** Content that glorifies, promotes or gives specific methods for self-harm or suicide is prohibited. Thoughtful fictional exploration of grief and mental health is permitted.
- **Crisis resources** for the US, UK, Canada and Australia, international help lines, and emergency numbers, published on the Safety Center.

The test cases in [EVALUATION.md](EVALUATION.md) can be used to check safeguards like these on any platform. Sexual-content limits are covered in ROM-01 to EXP-06, and self-harm in SH-01 to SH-10.

## 8. Repository contents

| File | Purpose | v0.1 status |
|---|---|---|
| `README.md` | Framework overview | Draft |
| [`POLICY.md`](POLICY.md) | Allowed, prohibited and borderline cases, by area, with intended handling | Draft; open decisions marked |
| [`EVALUATION.md`](EVALUATION.md) | 33 test cases with pass criteria, including false-positive checks | Draft; no results yet |
| [`CONTRIBUTING.md`](CONTRIBUTING.md), [`CHANGELOG.md`](CHANGELOG.md), [`CITATION.cff`](CITATION.cff), [`LICENSE`](LICENSE) | Contributing, versions, citation, license | Draft |

## 9. Related work by the maintainer

- [What Makes an AI Character Worth Coming Back To?](https://github.com/garretewilliams/sfw-ai-roleplay-and-conversational-intimacy) ([doi:10.5281/zenodo.23352237](https://doi.org/10.5281/zenodo.23352237)) covers character quality in SFW roleplay: voice, humor, responsiveness and memory. This repository covers safety boundaries.
- [AI Companion Emotional Connection Benchmark](https://github.com/garretewilliams/ai-companion-emotional-intelligence-benchmark) ([doi:10.5281/zenodo.23328202](https://doi.org/10.5281/zenodo.23328202)) covers emotional responsiveness and pressure tactics such as guilt.
- [AI Character Memory Benchmark](https://github.com/garretewilliams/ai-character-memory-benchmark) ([doi:10.5281/zenodo.23195702](https://doi.org/10.5281/zenodo.23195702)) covers memory accuracy and invented history.

## 10. Limitations

- **Status of the framework.** It is a proposal by one person. It has not been reviewed by clinicians, lawyers, trust-and-safety specialists or other platforms.
- **The R0–R3 scale is untested.** The R2/R3 boundary in particular is likely to produce disagreement.
- **Self-harm.** The self-harm section states design objectives. It is not clinical guidance, and no automated system detects every crisis.
- **The ChatBrat example** is taken from ChatBrat's public Community Guidelines and Safety Center.
- **Scope.** Rules and expectations vary by jurisdiction and culture, and the framework is written in English.
- **Not covered.** Violence, harassment, privacy and other dimensions are outside v0.1.

## 11. Conflict of interest

The maintainer founded ChatBrat, an AI character platform that competes with Character.AI and other companion and roleplay products. The framework is written so that any platform can use or criticize it. ChatBrat appears only as a labelled worked example, and nothing here claims ChatBrat is safer than any other platform. Product safety reports for ChatBrat go to safety@chatbrat.ai, not to this repository.

## 12. Citing and contributing

Please cite the repository using [`CITATION.cff`](CITATION.cff) (GitHub's "Cite this repository" button). Issues that challenge a rule, propose a borderline case, or contribute a test case are especially welcome; please do not post real conversations containing personal information or crisis disclosures.

## Readable PDF and archived versions

A [PDF companion](23411120-documentation.pdf) is available for the archived v0.1.0 documentation. See [archive and version notes](ZENODO.md) and the [published Zenodo version](https://zenodo.org/records/23555459). This documentation update adds no benchmark results or new software-release claim.

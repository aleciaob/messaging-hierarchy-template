# Messaging hierarchy template

Fifteen tiers in four layers. Each tier has a bracketed placeholder, a prompt for what goes in it, and a test for whether it is strong or weak.

Read this file top to bottom to understand the hierarchy. Do not build it top to bottom. The build order is in the [build guide](../docs/pressure-tests-and-build-order.md).

The claim rules in Layer D apply to every tier. Set them early.

For a filled-in version, see the [worked example](../examples/budgeting-app-worked-example.md).

---

## Layer A: Foundation

### Tier 1: Core problem
- **Placeholder:** `[Buyer] cannot [see / do / afford X] until [Y happens], which leads to [cost].`
- **Prompt:** State the problem in one or two sentences, from the buyer's side, without naming your product.
- **Test:** Strong if a buyer would say it unprompted and your product is absent from the sentence. Weak if it only describes what your product adds.

### Tier 2: Category frame
- **Placeholder:** `Category label: [label]. Market you are compared in: [market]. Result you want credited to you: [result].`
- **Prompt:** Pick the label a buyer already uses, the market whose alternatives they will compare you to, and the one result you want to own.
- **Test:** Strong if a buyer could place you in two seconds and an alternative could not truthfully claim the same result. Weak if the label is one you invented and nobody searches for.

### Tier 3: Positioning statement
- **Placeholder:** `For [target buyer] who need [need], [Name] is [category label] that [main benefit]. Unlike [type of alternative], [Name] [specific difference].`
- **Prompt:** One sentence a rep could say from memory. Name a type of alternative, not a vendor.
- **Test:** Strong if each clause could be challenged by a skeptical buyer and you could answer. Weak if you could swap in a competitor's name and it would still read true.

### Tier 4: Boundaries
- **Placeholder:** `[Name] is: [3-5 items]. [Name] is not: [3-5 items].`
- **Prompt:** List what is true today, then what a prospect or rep might wrongly assume.
- **Test:** Strong if every "is not" item is something people actually mistake you for, and every "is" item is true today. Weak if the "is not" list is filler or the "is" list contains roadmap.

### Tier 5: Naming map
- **Placeholder:** `[Company name] = [what it refers to]. [Product name] = [what it refers to]. [Component name] = [what it refers to].`
- **Prompt:** Define each name a buyer might hear, and which one is being sold.
- **Test:** Strong if a new rep can answer "what exactly am I buying?" in one sentence. Weak if two names are used interchangeably in your own materials.

### Tier 6: Category sanity check
- **Placeholder:** `Not [adjacent category 1]. Not [adjacent category 2]. Not [adjacent category 3]. We are [category label].`
- **Prompt:** Name the neighboring categories buyers are most likely to file you under by mistake.
- **Test:** Strong if each excluded category is one a real buyer has confused you with. Weak if the excluded categories are ones nobody would mention.

## Layer B: The case

### Tier 7: Benefit pillars
- **Placeholder:** `[Verb] + [buyer outcome], because [mechanism].` (repeat for each pillar)
- **Prompt:** Each pillar is one outcome the buyer cares about and the reason you can deliver it. Keep the count low enough that a rep can recall all of them.
- **Test:** Strong if every pillar traces to at least one differentiator and at least one proof item, and no two pillars could be swapped. Weak if a pillar is a feature in disguise.

### Tier 8: Differentiators
- **Placeholder:** `[Capability], which means [outcome], shown by [type of evidence]. Spoken line: "[one sentence a rep can say aloud]".`
- **Prompt:** Only include what an alternative cannot truthfully say. Write the spoken line as a person would say it, not as copy.
- **Test:** Strong if a competitor would have to stretch to claim it. Weak if it is table stakes for the category.

### Tier 9: Alternatives map
- **Placeholder:** `[Type of alternative] | What it is: [..] | What it does well: [..] | Where it falls short: [..]`
- **Prompt:** Describe each alternative as the buyer would, including what it is good at.
- **Test:** Strong if a buyer using that alternative would agree with the "does well" column. Weak if every row says the alternative is simply worse.

### Tier 10: Capability chain
- **Placeholder:** `[Capability] -> [what changes for the user] -> [what that is worth]`
- **Prompt:** For each capability, state the change in the user's day and then the business value of that change.
- **Test:** Strong if the middle link is observable by the user. Weak if you jump from capability to dollars with nothing in between.

### Tier 11: Anchor sentence
- **Placeholder:** `We [remove / reduce X], so [buyer] can [act earlier / better], which keeps them from [cost].`
- **Prompt:** The one sentence to return to when a conversation drifts into features or comparisons.
- **Test:** Strong if it still makes sense when read cold by someone outside the company. Weak if it needs a glossary.

## Layer C: Applied messaging

### Tier 12: Segment messaging (repeat per segment)
- **Placeholder:**
  - `Segment opener: [two sentences on why this segment cannot afford the problem]`
  - `What goes wrong: [the specific failure and who feels it]`
  - `How it is missed today: [current practice and why it fails]`
  - `Cost when it goes wrong: [figure + source, or "not yet quantified"]`
  - `Our role: [what we change in this segment]`
  - `Proof: [library reference]`
  - `Spoken line: "[what a rep says]"`
  - `Who buys: [profile]`
- **Prompt:** One block per segment, same fields every time, so a rep can compare segments without re-reading.
- **Test:** Strong if you could not paste one segment's block into another without editing the nouns. Weak if blocks differ only by segment name.

### Tier 13: Buyer-role messaging (repeat per role)
- **Placeholder:** `Role in the decision: [approves budget / advocates / uses daily / evaluates / can block]. What they say: "[their words]". What they care about: [..]. How to frame value: [..]. What not to say: [..].`
- **Prompt:** Use the buyer's own phrasing for the "what they say" line.
- **Test:** Strong if the quote would sound natural in a discovery call. Weak if it sounds like a marketing persona sheet.

### Tier 14: Proof library
- **Placeholder:** `Claim: [..] | What was measured: [..] | Source: [..] | Permission status: [named / unnamed / internal only] | Allowed audience: [..]`
- **Prompt:** One row per proof item. Include what was not measured.
- **Test:** Strong if each row says exactly what was and was not measured. Weak if a result is quoted without scale, time period or source.

### Tier 15: Objection responses (repeat per objection)
- **Placeholder:** `Objection: "[quote]". What it usually means: [..]. Probing questions: [number set by you]. Response: [..]. Do not say: [..].`
- **Prompt:** Treat the objection as information. Write the questions that reveal what is behind it before writing the answer.
- **Test:** Strong if a rep could use the probing questions without any script around them. Weak if the response is an argument.

## Layer D: Control (applies to every tier)

### Claim rules
See [claim-rules.md](claim-rules.md).

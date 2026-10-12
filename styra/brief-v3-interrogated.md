---
created: 2026-10-12
type: brief
status: draft-pending-research
tags: [styra, ai-fashion, interrogated-brief]
project: Styra AI Fashion Assistant
brief-version: "3: interrogated synthesis"
---

# Styra: Interrogated Brief v3.0

## Who is actually using this?

Styra is intended for people shopping for fashion online in Portugal and Bangladesh. However, the primary user segment, shopping context, device, budget, preferred language, and current shopping behaviour have not yet been established through the research available to this brief.

The working hypothesis is that some shoppers may benefit from help narrowing fashion choices and finding products relevant to their preferences.

**User fear to investigate:** Choosing an unsuitable item, wasting time on irrelevant options, or making a purchase they later regret. This is a hypothesis to validate with users, not a confirmed research finding.

## What the contradictions and gaps actually are

### 1. Broad fashion assistant versus a specific user problem

**Decision:** Do not finalise the feature set until the core user problem is defined.

**Reason:** “AI fashion shopping assistant” describes a product category, not a sufficiently precise user need.

**Confidence:** Confirmed that the product concept is broad; the highest-priority user problem is unknown.

### 2. Portugal versus Bangladesh

**Decision:** Investigate both markets and identify shared needs alongside meaningful local differences.

**Reason:** The two markets are confirmed project targets, but their specific shopping behaviours and requirements have not been established.

**Confidence:** Confirmed markets; user needs and localisation requirements remain unknown.

### 3. AI capability versus user value

**Decision:** Define the user task first, then determine where AI adds useful value.

**Reason:** AI should support a real shopping need rather than become a feature without a clear purpose.

**Confidence:** Design principle; the appropriate AI interaction is still to be researched.

### 4. Personalisation versus privacy

**Decision:** Identify the minimum information needed to provide useful assistance and explain its purpose to users.

**Reason:** The data needed for personalisation and the intended data-handling model are not yet specified.

**Confidence:** Open question; no particular data collection or privacy architecture is assumed.

### 5. Recommendations versus purchasing

**Decision:** Establish whether the first release supports product discovery only, product links, or a more complete purchasing journey.

**Reason:** The available project context does not confirm checkout, retailer integrations, inventory access, or transaction handling.

**Confidence:** Unknown.

## Scope: what I am building first, and what I am not

**Initial design focus:** Define and validate one high-value fashion-shopping task for a clearly identified user segment, then design the smallest AI-assisted journey that addresses that task.

The specific task and screen flow must be selected after reviewing the original storyboard, persona, and research.

**Not yet committed to the MVP:**
- An end-to-end checkout or payment system.
- Integrations with specific fashion retailers.
- Real-time product availability or pricing.
- Virtual try-on or image-based body visualisation.
- Automated wardrobe management or outfit planning.
- Advanced personalisation based on sensitive or unnecessary data.
- A separate product experience for each market without evidence that it is needed.

These are not decisions that such features will never be built; they are exclusions from the current unvalidated specification.

## Assumptions I am carrying forward

1. **Confirmed:** The product concept is Styra, an AI fashion shopping assistant.
2. **Confirmed:** Portugal and Bangladesh are the intended markets.
3. **Guess:** Shoppers may value help narrowing down relevant fashion products.
4. **Guess:** AI may improve the discovery experience if its recommendations are relevant and understandable.
5. **I do not know:** Which user segment should be prioritised.
6. **I do not know:** Which shopping problem should define the MVP.
7. **I do not know:** Which product sources or retailer integrations are available.
8. **I do not know:** Whether the first release includes purchasing or only product discovery.
9. **I do not know:** The confirmed design and business success metrics.
10. **I do not know:** The approved timeline, budget, and final decision-maker.

## Open questions for the project owner or stakeholders

1. Which specific user segment and fashion-shopping problem should Styra prioritise first?
2. What evidence from the existing storyboard, persona, or research supports that choice?
3. What should users be able to accomplish in the first release?
4. Where will Styra obtain product information, prices, availability, and shopping links?
5. What will the AI need to know about a user to provide relevant recommendations?
6. Which differences between Portugal and Bangladesh materially change the design?
7. What are the MVP success metrics, delivery deadline, budget, and approval process?

## Design decision

Do not move directly into high-fidelity UI based on the broad concept alone. First confirm the user, problem, and core shopping task from the existing project evidence. Then narrow the MVP and test whether the proposed AI-assisted journey actually helps users.

# SpecKit vs OpenSpec Comparison

This document compares the two structured delivery approaches reflected in the attached logs:

- SpecKit workflow based on the content in [Docs/SpecKit.txt](Docs/SpecKit.txt)
- OpenSpec workflow based on the content in [Docs/OpenSpec.txt](Docs/OpenSpec.txt)

## 1. Executive Summary

Both approaches were used to define and implement an insurance customer-facing app with:

- a policy card experience,
- policy management capabilities,
- document viewing features,
- Angular frontend,
- Python FastAPI backend.

The main difference is in style:

- SpecKit is more structured, formal, and process-oriented.
- OpenSpec is more lightweight, faster, and execution-oriented.

---

## 2. Side-by-Side Comparison

| Aspect | SpecKit | OpenSpec |
|---|---|---|
| Overall approach | Structured and deliberate | Lean and execution-focused |
| Workflow style | Constitution → Specify → Plan → Tasks → Analyze → Implement | Propose → Explore → Apply |
| Documentation emphasis | Stronger emphasis on formal requirements and planning | Stronger emphasis on rapid progress and implementation |
| Governance | Better for enterprise-style discipline | Better for faster delivery and iteration |
| Speed | Slower but more controlled | Faster but less ceremony-heavy |
| Suitability | Good for larger or regulated projects | Good for MVPs and quick validation |
| Risk | Lower risk of ambiguity, higher chance of over-documentation | Lower risk of process overhead, higher chance of missing detail |

---

## 3. Pros and Cons

### SpecKit

#### Pros
- Strong structure and clear progression.
- Good for defining principles such as clean code, enterprise standards, and responsive UX.
- Produces well-organized artifacts like proposal, design, specs, and tasks.
- Better suited for long-term maintainability and team collaboration.
- Easier to audit and review in formal delivery environments.

#### Cons
- Can feel heavier than necessary for smaller projects.
- More steps may slow down initial momentum.
- Can lead to more documentation than the team actually needs at the start.
- May be overkill if the goal is rapid prototyping.

### OpenSpec

#### Pros
- Faster path from idea to implementation.
- Simpler workflow with less overhead.
- Good for MVP-style delivery and iterative improvements.
- Keeps the team focused on building rather than spending too much time on planning artifacts.
- Useful when the team already understands the requirements well.

#### Cons
- Less formal and less structured than SpecKit.
- May provide less traceability for long-term governance.
- Can be less suitable for complex or regulated environments.
- May require more follow-up refinement to ensure quality and consistency.

---

## 4. Practical Recommendation

For this insurance app, the best choice depends on the project goal:

- Choose SpecKit if the priority is strong structure, maintainability, and formal delivery.
- Choose OpenSpec if the priority is faster execution and quicker first results.

In practice, a hybrid approach can be very effective:

- use SpecKit-style planning for requirements and standards,
- use OpenSpec-style execution for implementation speed.

---

## 5. Token and Credit Information

The attached files include the following token and credit details.

### SpecKit Log Summary

| Operation | Tokens | Input | Cached | Output | Notes |
|---|---:|---:|---:|---:|---|
| Constitution | 175,148 | 30,091 | 137,856 | 7,201 | Model: GPT-4o mini |
| Specify | 272,925 | 27,976 | 238,848 | 6,101 | Model: GPT-4o mini |
| Clarify | 37,842 | 11,787 | 25,088 | 967 | Model: MAI-Code-1-Flash |
| Plan | 856,053 | 49,474 | 797,696 | 8,883 | Model: MAI-Code-1-Flash |
| Tasks | 111,979 | 2,371 | 107,904 | 1,704 | Model: MAI-Code-1-Flash |
| Analyze | 174,987 | 32,214 | 138,624 | 4,149 | Model: MAI-Code-1-Flash |
| Implement | Not explicitly listed in the snippet | Not explicitly listed | Not explicitly listed | Not explicitly listed | Credit note included |

#### SpecKit Credit Notes
The attached SpecKit log shows the following credit mentions:

- 1.8 credits
- 1.5 credits
- 6.6 credits
- 13.7 credits
- 1.8 credits
- 5.3 credits
- 36.6 credits

### OpenSpec Log Summary

| Operation | Tokens | Input | Cached | Output | Notes |
|---|---:|---:|---:|---:|---|
| Propose | 810,894 | 43,160 | 756,864 | 10,870 | Model: GPT-5 mini |
| Explore | 293,053 | 35,521 | 255,744 | 1,788 | Model: GPT-5 mini |
| Apply | 1,057,953 | 65,925 | 985,600 | 6,428 | Model: GPT-5 mini |
| ToDos / follow-up | 1,498,760 | 37,304 | 1,454,720 | 6,736 | Model: GPT-5 mini |

#### OpenSpec Credit Notes
The attached OpenSpec log shows the following credit values:

- 5.1 credits
- 1.9 credits
- 5.4 credits
- 5.9 credits

---

## 6. Key Takeaway

If the goal is to compare the two approaches purely by process and output quality:

- SpecKit offers better structure and formal alignment.
- OpenSpec offers better speed and lower friction.

If the goal is to compare them by resource usage:

- OpenSpec appears to have consumed a larger total token volume in the attached example.
- SpecKit shows a more distributed workflow with multiple smaller steps and some explicit credit usage.

---

## 7. Final Conclusion

Both methods are valid for this project. The decision should depend on whether the team values:

- process discipline and long-term maintainability (SpecKit), or
- speed and implementation focus (OpenSpec).

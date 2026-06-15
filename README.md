# Contribution [#]: [Issue Title]

**Contribution Number:** 1  
**Student:** Damarcos Estevez  
**Issue:** https://github.com/openedx/frontend-app-learner-record/issues/609
**Status:** Phase II Complete

---

## Why I Chose This Issue

[1-2 paragraphs explaining why this issue interests you, how it matches your skills/learning goals, what you hope to learn]

I have worked on front end apps before and have had Redux as a dependency in the past, I believe I should be able to remove the dependency of it just fine.

---

## Understanding the Issue

### Problem Description

[In your own words, what's broken or missing?]

Redux is installed, it is not used anywhere in code however, leading to dependency issues.

### Expected Behavior

[What should happen?]

No dependency issues/warnings

### Current Behavior

Dependency erros/warnings from Redux

[What actually happens?]

### Affected Components

CI checks

[Which parts of the codebase are involved?]

CI tools, but lacks actual code usage

---

## Reproduction Process

### Environment Setup

[Notes on setting up your local development environment - challenges you faced, how you solved them]

### Steps to Reproduce

1. [Step 1]
   Install through NPM, follow readme
2. [Observed result]
   JSON lists react redux and redux as part of the app, and is imported in some files, but there is no place where its actually used

### Reproduction Evidence

- **Commit showing reproduction:** [Link to commit in your fork]
- **Screenshots/logs:** [If applicable]
- **My findings:** [What you discovered during reproduction]
<img width="340" height="101" alt="image" src="https://github.com/user-attachments/assets/99932134-bb4f-4454-8b69-1d3f09e22cd0" />
Reux shows in the app's JSON, but no code actually uses it
---

## Solution Approach

### Analysis

Unnecessary installation



### Proposed Solution

Remove REDUX rentirely, make sure nothing is affected by removal

### Implementation Plan

Using UMPIRE framework (adapted):

**Understand:** [Restate the problem]

Redux is an unecessary installation

**Match:** [What similar patterns/solutions exist in the codebase?]

None, we are requiring removal, not replacement,

**Plan:** [Step-by-step implementation plan]
1. Verify there is no usage of redux in SRC folder
2. Remove redux from isntallations

**Implement:** [Link to your branch/commits as you work]

https://github.com/elracing/frontend-app-learner-record/tree/fix-issue-609

**Review:** [Self-review checklist - does it follow the project's contribution guidelines?]

Forms signed to be able to contribute to Open edX is required for contribution, have signed. 

**Evaluate:** [How will you verify it works?]

Manual testing, simply watch for no code dependency of Redux.

---

## Testing Strategy


### Manual Testing

[What you tested manually and results]

---

## Implementation Notes

### Week [X] Progress

[What you built this week, challenges faced, decisions made]

### Week [Y] Progress

[Continue documenting as you work]

### Code Changes

- **Files modified:** [List]
- **Key commits:** [Links to important commits]
- **Approach decisions:** [Why you chose certain approaches]

---

## Pull Request

**PR Link:** [GitHub PR URL when submitted]

**PR Description:** [Draft or final PR description - much of the content above can be adapted]

**Maintainer Feedback:**
- [Date]: [Summary of feedback received]
- [Date]: [How you addressed it]

**Status:** [Awaiting review / Iterating / Approved / Merged]

---

## Learnings & Reflections

### Technical Skills Gained

[What you learned technically]

### Challenges Overcome

[What was hard and how you solved it]

### What I'd Do Differently Next Time

[Reflection on your process]

---

## Resources Used

- [Link to helpful documentation]
- [Tutorial or Stack Overflow post that helped]
- [GitHub issues or discussions that helped]

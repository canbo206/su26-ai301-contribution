# Contribution [1]: Rule for first value of enum should have numeric value zero?

**Contribution Number:** [1 / 2 / 3]  
**Student:** Canbo Li 
**Issue:** https://github.com/yoheimuta/protolint/issues/423
**Status:** Phase I Complete

---

## Why I Chose This Issue

I chose issue #423 "Rule for first value of enum should have numeric value zero?" 
because it's clear feature addition with a what it considers a definition of done. The 
issue is labeled "good first issue" and the maintainer explicitly stated they're 
willing to accept a contribution.

I'm interested in this because:
1. The scope is clear, adding one lint rule by following patterns already 
   established in the codebase
2. The maintainer provided a concrete example of the problem with actual 
   output so I know  what "fixed" looks like
3. I feel pretty confident in Python but a beginner in Go and this issue requires both so this feels like the right 
   challenge to push my skills without overwhelming me.
4. I want to learn how linters enforce rules which is transferable 
   knowledge across languages and tools

From reading the issue thread, I understand the problem is that protolint is missing a check that proto3 
actually requires, the first value in any enum must be zero. Right now you 
only find out when you try to compile, but protolint should catch it sooner.
My contribution will add that missing check so developers get an early warning 
before their code even reaches the compiler.

Left a comment on the issue introducing myself and expressing intent to work on it.

---

## Understanding the Issue

### Problem Description

[In your own words, what's broken or missing?]

### Expected Behavior

[What should happen?]

### Current Behavior

[What actually happens?]

### Affected Components

[Which parts of the codebase are involved?]

---

## Reproduction Process

### Environment Setup

[Notes on setting up your local development environment - challenges you faced, how you solved them]

### Steps to Reproduce

1. [Step 1]
2. [Step 2]
3. [Observed result]

### Reproduction Evidence

- **Commit showing reproduction:** [Link to commit in your fork]
- **Screenshots/logs:** [If applicable]
- **My findings:** [What you discovered during reproduction]

---

## Solution Approach

### Analysis

[Your analysis of the root cause - what's causing the issue?]

### Proposed Solution

[High-level description of your fix approach]

### Implementation Plan

Using UMPIRE framework (adapted):

**Understand:** [Restate the problem]

**Match:** [What similar patterns/solutions exist in the codebase?]

**Plan:** [Step-by-step implementation plan]
1. [Modify file X to do Y]
2. [Add function Z]
3. [Update tests]

**Implement:** [Link to your branch/commits as you work]

**Review:** [Self-review checklist - does it follow the project's contribution guidelines?]

**Evaluate:** [How will you verify it works?]

---

## Testing Strategy

### Unit Tests

- [ ] Test case 1: [Description]
- [ ] Test case 2: [Description]
- [ ] Test case 3: [Description]

### Integration Tests

- [ ] Integration scenario 1
- [ ] Integration scenario 2

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

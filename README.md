# Contribution [1]: [Add copy/paste to libre photos]

**Contribution Number:** [1]  
**Student:** [Madeline Gilmore]  
**Issue:** [https://github.com/tarunjandra/agent-tools-mcp-hub/issues/101](https://github.com/LibrePhotos/librephotos/issues/544)
**Status:** Phase II [In Progress]

---

## Why I Chose This Issue
I chose this problem because I never thought about where the clipboard data lives. I'm hoping to learn how that works through this project

---

## Understanding the Issue

### Problem Description

A user wants to allow copy/paste photos from the timeline.

### Expected Behavior

[What should happen?]

When you click on the three dots when a photo is selected, copy should be an option on the menu. When clicked it should copy the photo to clipboard

### Current Behavior

[What actually happens?]

### Affected Components
When you click on the three dots when a photo is selected, copy is not an option on the menu

[Which parts of the codebase are involved?]

---

## Reproduction Process

### Environment Setup

[Notes on setting up your local development environment - challenges you faced, how you solved them]

Download software, open on local.
Couldn't figure out how to add photo into environment. 

### Steps to Reproduce

1. Open libre photos
2. Load in photo
3. Press 3 dots
4. [Observed result]: no copy button

### Reproduction Evidence

- **Commit showing reproduction:** [Link to commit in your fork]
- **Screenshots/logs:** [If applicable]
- **My findings:** [What you discovered during reproduction]

---

## Solution Approach

### Analysis

[Your analysis of the root cause - what's causing the issue?]

No copy button was implemented into the menu options

### Proposed Solution

[High-level description of your fix approach]
Make a new button using preexisting clipboard copy logic present in other parts of codebase.


### Implementation Plan

Using UMPIRE framework (adapted):

**Understand:** [Restate the problem]
When you click on the three dots when a photo is selected, copy is not an option on the menu

**Match:** [What similar patterns/solutions exist in the codebase?]
There is copy/paste logic in other parts of the codebase
There are other menu options that we can duplicate 

**Plan:** [Step-by-step implementation plan]
1. Find actions (download, favorite, delete, etc.)
3. Add copy action > add copy button and make it copy the photo
4. [Update tests]

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

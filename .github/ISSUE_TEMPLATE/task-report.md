---
name: Task Report
about: Describe this issue template's purpose here.
title: ''
labels: ''
assignees: ''

---

name: User Story
description: Create a user story
title: "[User Story]: "
labels: ["user-story"]
body:
  - type: markdown
    attributes:
      value: |
        ## User Story

  - type: textarea
    id: story
    attributes:
      label: User Story
      description: Use the format "As a [user], I want [feature], so that [benefit]."
      placeholder: As a user, I want..., so that...
    validations:
      required: true

  - type: textarea
    id: acceptance
    attributes:
      label: Acceptance Criteria
      description: What must be true for this story to be complete?
      placeholder: |
        - Given...
        - When...
        - Then...
    validations:
      required: true

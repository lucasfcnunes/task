---
name: Bug Report
about: Use this to report bugs and issues.
body:
  - type: markdown
    attributes:
      value: |
        Thanks for your bug report!

        Before submitting this issue, please make sure the same problem was
        not already reported by someone else.
  - type: input
    id: version
    attributes:
      label: Task version
      description: Which Task version you are using? Use `task --version` to know.
      placeholder: v0.0.0
    validations:
      required: false
  - type: input
    id: os
    attributes:
      label: Operating System
      description: Which operating system you are using?
      placeholder: Ubuntu 22.04.1
    validations:
      required: false
  - type: textarea
    id: description
    attributes:
      label: Description
      description: |
        Please describe the bug you're facing. Consider pasting example
        Taskfiles showing how to reproduce the problem.
      placeholder: You description here.
    validations:
      required: true
---
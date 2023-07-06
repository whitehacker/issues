---
name: Bug Report
about: Use this template to report a bug in the REMIND model.
title: '[BUG]'
labels: bug
assignees: ''

body:
- type: input
  id: issue-summary
  attributes:
    label: Bug Summary
    description: Provide a brief summary of the issue you're experiencing.
    placeholder: 'e.g., Model fails to generate a correct output when input X is provided.'
  validations:
    required: true

- type: textarea
  id: steps-to-reproduce
  attributes:
    label: Steps to Reproduce
    description: Please provide the steps to reproduce the issue.
    placeholder: '1. Step 1...'
  validations:
    required: true

- type: textarea
  id: expected-behavior
  attributes:
    label: Expected Behavior
    description: What did you expect to happen?
    placeholder: 'Explain what you expected to happen...'
  validations:
    required: true

- type: textarea
  id: actual-behavior
  attributes:
    label: Actual Behavior
    description: What happened instead?
    placeholder: 'Explain what actually happened...'
  validations:
    required: true

- type: textarea
  id: screenshots
  attributes:
    label: Screenshots (optional)
    description: If applicable, add screenshots to help explain the problem.

- type: input
  id: environment
  attributes:
    label: Environment (e.g., OS, Browser, Version)
    description: Please provide any relevant details about the environment where the bug occurred.
  validations

name: Questions
description: Ask questions if you have any doubts
title: "[Question]: "
labels:
  - "questions"
body:
  - type: markdown
    attributes:
      value: |
        Thanks for taking the time to ask your question!

        Please answer the following checklist before submitting:

        - [x] I am running the latest version
        - [x] I checked the documentation and found no answer
        - [x] I checked to make sure that this question has not already been asked

  - type: textarea
    id: description
    attributes:
      label: Question Description
      description: A clear and concise description of your question or doubt.
      placeholder: Describe your question here...
    validations:
      required: true

  - type: dropdown
    id: browsers
    attributes:
      label: (optional) What browsers are you using (if relevant)?
      multiple: true
      options:
        - Firefox
        - Chrome
        - Safari
        - Microsoft Edge

  - type: checkboxes
    id: terms
    attributes:
      label: Code of Conduct
      description: By submitting this issue, you agree to follow our [CODE_OF_CONDUCT.md](CODE_OF_CONDUCT.md)
      options:
        - label: I agree to follow this project's Code of Conduct
          required: true

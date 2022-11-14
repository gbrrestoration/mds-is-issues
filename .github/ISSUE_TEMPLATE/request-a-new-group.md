---
name: Request a new group
about: Request a new group to be added to the RRAP M&DS IS
title: '[New Group Request] '
labels: ["new group", "triage"]
assignees: ''
body:
  - type: input
    id: contact
    attributes:
      label: Contact Details
      description: How can we get in touch with you if we need more info?
      placeholder: ex. email@example.com
    validations:
      required: false
  - type: input
    id: group-name
    attributes:
      label: Name for the new group
      description: Name for the new group
    validations:
      required: true
  - type: textarea
    id: list-of-members
    attributes:
      label: List of members
      description: List of email addresses of members in the group
    validations:
      required: true      

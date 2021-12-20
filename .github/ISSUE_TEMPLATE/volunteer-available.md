---
name: volunteer-available
about: Use this template if you are looking for a project opportunity.
title: 'Volunteer Available'
labels: Volunteer Available
body:
  - type: input
    id: name
    attributes:
      label: Name
    validations:
      required: true
  - type: textarea
    id: contact-info
    attributes:
      label: Contact Info
    validations:
      required: false
  - type: textarea
    id: areas-of-interest
    attributes:
      label: Areas of Interest
    validations:
      required: true
  - type: textarea
    id: skills
    attributes:
      label: Skills
    validations:
      required: true
  - type: textarea
    id: availability
    attributes:
      label: Availability
    validations:
      required: true
  - type: textarea
    id: current-projects
    attributes:
      label: Current Project(s)
    validations:
      required: true
---
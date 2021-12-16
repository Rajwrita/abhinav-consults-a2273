---
title: Careers
layout: PageLayout
sections:
  - elementId: ''
    colors: colors-h
    title: Interview Preparation
    subtitle: You should join us.
    styles:
      self:
        height: auto
        width: wide
        margin:
          - mt-0
          - mb-0
          - ml-0
          - mr-0
        padding:
          - pt-36
          - pb-12
        alignItems: center
        justifyContent: center
        flexDirection: col
      title:
        textAlign: center
      subtitle:
        textAlign: center
      text:
        textAlign: left
      actions:
        justifyContent: flex-start
    type: HeroSection
  - colors: colors-a
    elementId: ''
    title: Open roles
    jobLists:
      - type: JobList
        title: Product
        items:
          - type: JobListItem
            title: Director of product managment
            location: San Francisco
            text: >
              Lorem Ipsum is simply dummy text of the printing and typesetting
              industry. Lorem Ipsum has been the industry's standard dummy text
              ever since the 1500s, when an unknown printer took a galley of
              type and
            actions:
              - label: Apply
                altText: Apply
                url: /
                showIcon: true
                icon: arrowRight
                iconPosition: right
                elementId: ''
                type: Link
      - type: JobList
        title: Engineering
        items:
          - type: JobListItem
            title: Head of engineering
            location: San Francisco
            text: >
              Lorem Ipsum is simply dummy text of the printing and typesetting
              industry. Lorem Ipsum has been the industry's standard dummy text
              ever since the 1500s, when an unknown printer took a galley of
              type and
            actions:
              - label: Apply
                altText: Apply
                url: /
                showIcon: true
                icon: arrowRight
                iconPosition: right
                elementId: ''
                type: Link
          - type: JobListItem
            title: Senior Backend Engineer
            location: Remote
            text: >
              Lorem Ipsum is simply dummy text of the printing and typesetting
              industry. Lorem Ipsum has been the industry's standard dummy text
              ever since the 1500s, when an unknown printer took a galley of
              type and
            actions:
              - label: Apply
                altText: Apply
                url: /
                showIcon: true
                icon: arrowRight
                iconPosition: right
                elementId: ''
                type: Link
    styles:
      self:
        height: auto
        width: wide
        margin:
          - mt-0
          - mb-0
          - ml-0
          - mr-0
        padding:
          - pt-32
          - pb-60
          - pl-4
          - pr-4
        justifyContent: center
        borderRadius: none
        borderWidth: 0
        borderStyle: none
        borderColor: border-dark
      title:
        textAlign: left
      subtitle:
        textAlign: center
    type: JobsSection
  - elementId: contact-form
    colors: colors-f
    backgroundSize: inset
    title: Not seeing the right fit? Feel free to reach out
    form:
      type: FormBlock
      elementId: contact-form
      action: /.netlify/functions/submission_created
      destination: ''
      fields:
        - type: TextFormControl
          name: first-name
          label: Your first name
          hideLabel: true
          placeholder: First name
          isRequired: false
          width: 1/2
        - type: TextFormControl
          name: last-name
          label: Your last name
          hideLabel: true
          placeholder: Last name
          isRequired: false
          width: 1/2
        - type: EmailFormControl
          name: email
          label: Your email
          hideLabel: true
          placeholder: Email
          isRequired: true
          width: full
      submitLabel: Submit
      styles:
        submitLabel:
          textAlign: center
    styles:
      self:
        height: auto
        width: wide
        margin:
          - mt-24
          - mb-0
          - ml-0
          - mr-0
        padding:
          - pt-24
          - pb-24
          - pr-4
          - pl-4
        alignItems: center
        justifyContent: center
        flexDirection: row
        borderRadius: xx-large
        boxShadow: xx-large
      title:
        textAlign: center
      text:
        textAlign: center
    type: ContactSection
---

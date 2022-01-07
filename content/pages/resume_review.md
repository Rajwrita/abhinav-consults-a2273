---
title: ResumeReview
sections:
  - type: HeroSection
    colors: colors-h
    title: Resume Review
    text: You should join us.
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
          - pt-12
          - pb-12
          - pl-4
          - pr-4
        alignItems: center
        justifyContent: center
        flexDirection: col
      title:
        textAlign: center
      subtitle:
        fontWeight: 400
        fontStyle: normal
        textAlign: center
      text:
        textAlign: center
      actions:
        justifyContent: flex-start
  - type: JobsSection
    colors: colors-a
    subtitle: ''
    jobLists:
      - type: JobList
        title: Product
        items:
          - type: JobListItem
            title: Director of product management
            location: San Francisco
            text: >-
              Lorem Ipsum is simply dummy text of the printing and typesetting
              industry. Lorem Ipsum has been the industry's standard dummy text
              ever since the 1500s, when an unknown printer took a galley of
              type and
            actions:
              - type: Link
                label: Apply
                url: '/https://www.linkedin.com/services/page/941755312426672414/'
                showIcon: true
                icon: arrowRight
                iconPosition: right
      - type: JobList
        title: Engineering
        items:
          - type: JobListItem
            title: Head of engineering
            location: San Francisco
            text: >-
              Lorem Ipsum is simply dummy text of the printing and typesetting
              industry. Lorem Ipsum has been the industry's standard dummy text
              ever since the 1500s, when an unknown printer took a galley of
              type and
            actions:
              - type: Link
                label: Apply
                url: '/https://www.linkedin.com/services/page/941755312426672414/'
                showIcon: true
                icon: arrowRight
                iconPosition: right
    styles:
      self:
        height: auto
        width: narrow
        margin:
          - mt-0
          - mb-0
          - ml-0
          - mr-0
        padding:
          - pt-12
          - pb-12
          - pl-4
          - pr-4
        justifyContent: center
      title:
        textAlign: left
      subtitle:
        textAlign: left
layout: PageLayout
---

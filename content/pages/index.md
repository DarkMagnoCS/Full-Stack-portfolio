---
type: PageLayout
title: Alejandro Portfolio
colors: colors-a
backgroundImage:
  type: BackgroundImage
  url: /images/night_city_long_exposure_road_140393_3840x2160.jpg
  backgroundSize: cover
  backgroundPosition: center
  backgroundRepeat: no-repeat
  opacity: 75
sections:
  - elementId: ''
    colors: colors-f
    backgroundSize: full
    title: 'Hi, I''m Alejandro. I''m a full-Stack developer.'
    subtitle: >-
      Hey there! I’ve been busy leveling up my skills with certifications in
      Full Stack Development from IBM, Android Development from Meta, and DevOps
      from AWS. Along the way, I’ve earned commendations from Google that
      highlight my expertise
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
          - pb-48
          - pl-4
          - pr-4
        alignItems: center
        justifyContent: center
        flexDirection: row-reverse
      title:
        textAlign: left
      subtitle:
        textAlign: left
      text:
        textAlign: left
      actions:
        justifyContent: flex-start
    type: HeroSection
    actions: []
  - type: LabelsSection
    title: Skills
    subtitle: ''
    items:
      - type: Label
        label: Python
        url: ''
      - type: Label
        label: JavaScript
        url: ''
      - type: Label
        label: React
        url: ''
      - type: Label
        label: Kotlin
        url: ''
      - type: Label
        label: Flask
        url: ''
      - type: Label
        label: Next.js
        url: ''
      - type: Label
        label: MongoDB
        url: ''
      - type: Label
        label: Figma
        url: ''
      - type: Label
        label: Git
        url: ''
    colors: colors-b
    elementId: ''
    styles:
      self:
        height: auto
        width: wide
        padding:
          - pt-36
          - pb-36
          - pl-4
          - pr-4
        justifyContent: center
      title:
        textAlign: left
      subtitle:
        textAlign: left
  - colors: colors-f
    type: FeaturedProjectsSection
    elementId: ''
    actions:
      - type: Link
        label: See all projects
        url: /projects
    showDate: false
    showDescription: true
    showFeaturedImage: true
    showReadMoreLink: true
    variant: variant-b
    projects:
      - content/pages/projects/project-one.md
      - content/pages/projects/project-two.md
      - content/pages/projects/project-three.md
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
          - pt-24
          - pb-24
          - pl-4
          - pr-4
        justifyContent: center
      title:
        textAlign: left
      subtitle:
        textAlign: left
      actions:
        justifyContent: flex-end
    subtitle: Projects
---

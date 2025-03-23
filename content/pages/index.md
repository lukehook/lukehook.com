---
type: PageLayout
title: Home
colors: colors-d
sections:
  - elementId: ''
    colors: colors-f
    backgroundSize: full
    title: >-
      I’m a developer, speaker, Pokémon trainer and a bunch of other impressive
      titles and buzz words.
    subtitle: >-
      This is my info - a short and sweet soliloquy about my career up to date.
      Once you've come to terms with being suitably unimpressed you can continue
      to scroll down and email me to tell me if you so wish.
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
        flexDirection: row-reverse
        textAlign: left
    type: HeroSection
    actions: []
  - colors: colors-f
    type: FeaturedProjectsSection
    elementId: ''
    actions: []
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
        padding:
          - pt-24
          - pb-24
          - pl-4
          - pr-4
        textAlign: left
    subtitle: Clients
  - type: ContactSection
    colors: colors-f
    backgroundSize: full
    title: "Got something to say? Tell me more...\U0001F4AC"
    form:
      type: FormBlock
      elementId: sign-up-form
      fields:
        - name: name
          label: Name
          hideLabel: true
          placeholder: Name
          isRequired: true
          width: 1/2
          type: TextFormControl
        - name: email
          label: Email
          hideLabel: true
          placeholder: Email
          isRequired: true
          width: 1/2
          type: EmailFormControl
        - type: TextareaFormControl
          name: message
          label: Message
          hideLabel: false
          placeholder: Type your message here
          width: full
          isRequired: true
      submitLabel: "Submit \U0001F680"
      styles:
        self:
          textAlign: center
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
          - pt-24
          - pb-24
          - pr-4
          - pl-4
        flexDirection: row
        textAlign: left
---

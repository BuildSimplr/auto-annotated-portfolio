---
type: PageLayout
title: About Me
colors: colors-a
backgroundImage:
  type: BackgroundImage
  url: /images/favicon.svg
  backgroundSize: cover
  backgroundPosition: center
  backgroundRepeat: no-repeat
  opacity: 75
sections:
  - elementId: ''
    colors: colors-f
    backgroundSize: full
    text: >+
      # Hi! My name I'm Ashley and I am a Problem Solver or a Solutions Analyst
      from 9 to 5 est. I help teams streamline workflows, optimize processes,
      and achieve their goals through strategic problem-solving. Think of me as
      the teammate who helps connect strategy to execution, like the '96 Bulls,
      Kobe & Shaq, or LeBron FINALLY  making a couple championship runs. All
      required individual talent and seamless teamwork. I bring that same
      collaborative approach to every project.


      # When I'm not diving into workflows and requirements, I'm probably
      watching sports or exploring new coffee spots!

    media:
      type: ImageBlock
      url: /images/Image.jpg
      altText: Hero image
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
          - pt-16
          - pb-12
          - pl-4
          - pr-4
        textAlign: left
    type: HeroSection
  - type: DividerSection
    styles:
      self:
        width: wide
        padding:
          - pt-8
          - pb-8
          - pl-4
          - pr-4
        borderWidth: 1
        borderStyle: solid
  - type: LabelsSection
    colors: colors-f
    subtitle: 'Skills:'
    items:
      - type: Label
        label: AWS
        url: >-
          https://cp.certmetrics.com/amazon/en/public/verify/credential/fb928bbdf9be449bbf270b962758c151
      - type: Label
        label: Microsoft Office
      - type: Label
        label: SalesForce *Health Cloud
      - type: Label
        label: VOIP
      - type: Label
        label: Pancakes
      - type: Label
        label: Problem Solving
      - type: Label
        label: Learning SQL
  - type: DividerSection
    styles:
      self:
        width: wide
        padding:
          - pt-12
          - pb-12
          - pl-4
          - pr-4
        borderWidth: 1
        borderStyle: solid
  - type: ContactSection
    backgroundSize: full
    title: "Let’s talk... \U0001F4AC"
    colors: colors-f
    form:
      type: FormBlock
      elementId: sign-up-form
      fields:
        - name: firstName
          label: First Name
          hideLabel: true
          placeholder: First Name
          isRequired: true
          width: 1/2
          type: TextFormControl
        - name: lastName
          label: Last Name
          hideLabel: true
          placeholder: Last Name
          isRequired: false
          width: 1/2
          type: TextFormControl
        - name: email
          label: Email
          hideLabel: true
          placeholder: Email
          isRequired: true
          width: full
          type: EmailFormControl
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
          - ml-4
          - mr-4
        padding:
          - pt-12
          - pb-12
          - pr-4
          - pl-4
        flexDirection: row
        textAlign: left
---

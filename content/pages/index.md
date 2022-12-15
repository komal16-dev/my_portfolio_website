---
title: Home
layout: PageLayout
sections:
  - type: HeroSection
    colors: colors-b
    elementId: ''
    backgroundSize: full
    title: Hey! I'm Komal - An Aspiring Data Analyst
    subtitle: Learning. Creativity. Curiosity.
    text: |+


    actions:
      - type: Button
        label: Projects
        showIcon: true
        icon: arrowRight
        style: primary
        url: /project
        iconPosition: right
        elementId: '1'
      - type: Link
        altText: ''
        url: 'https://www.linkedin.com/in/komal-gangurde/'
        showIcon: true
        icon: linkedin
        iconPosition: right
        elementId: ''
      - type: Link
        altText: ''
        url: 'https://github.com/komal16-dev'
        showIcon: true
        icon: github
        iconPosition: right
        elementId: ''
    media:
      type: ImageBlock
      url: /images/IMG_20200412_212117-a5131427.jpg
      altText: Komal Gangurde
    backgroundImage: null
    styles:
      self:
        height: auto
        width: wide
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
  - type: QuoteSection
    colors: colors-c
    quote: |
      “**You can always edit a bad page. You can’t edit a blank page"**
    name: Jodi Picoult
    title: American Author
    styles:
      self:
        height: auto
        width: narrow
        padding:
          - pt-24
          - pb-24
          - pr-5
          - pl-5
        justifyContent: center
        borderRadius: none
        borderColor: border-complementary
        borderWidth: 4
        borderStyle: none
        margin:
          - mt-1
          - mr-1
          - mb-1
          - ml-1
      quote:
        textAlign: center
      name:
        textAlign: center
      title:
        textAlign: center
  - type: FeaturedItemsSection
    colors: colors-b
    elementId: ''
    title: Recent Projects
    subtitle: ''
    items:
      - type: FeaturedItem
        title: 'YouTube API '
        text: >-
          Lorem ipsum dolor sit amet, consectetur adipiscing elit. Sed ante
          lorem, tincidunt ac leo efficitur, feugiat tempor odio. Maecenas
          pharetra ipsum dolor, et iaculis elit ornare ac.
        actions:
          - type: Button
            label: Read more
            showIcon: true
            icon: arrowRight
            url: /project/project1
            style: secondary
        styles:
          self:
            textAlign: left
        featuredImage:
          type: ImageBlock
          url: >-
            https://assets.stackbit.com/components/images/default/default-image.png
          altText: altText of the image
          caption: Caption of the image
          elementId: ''
      - type: FeaturedItem
        title: Smarter
        text: >-
          Lorem ipsum dolor sit amet, consectetur adipiscing elit. Sed ante
          lorem, tincidunt ac leo efficitur, feugiat tempor odio. Maecenas
          pharetra ipsum dolor, et iaculis elit ornare ac.
        actions:
          - type: Button
            label: Read more
            showIcon: true
            icon: arrowRight
            url: /project/project2
            style: secondary
        styles:
          self:
            textAlign: left
        featuredImage:
          type: ImageBlock
          url: >-
            https://assets.stackbit.com/components/images/default/default-image.png
          altText: altText of the image
          caption: Caption of the image
          elementId: ''
    actions: []
    columns: 2
    spacingX: 50
    spacingY: 50
    enableHover: true
    styles:
      self:
        height: auto
        width: wide
        padding:
          - pt-28
          - pb-36
          - pl-4
          - pr-4
        justifyContent: center
      title:
        textAlign: left
      subtitle:
        textAlign: left
      actions:
        justifyContent: flex-start
  - type: ContactSection
    colors: colors-d
    title: Join our club
    text: |
      We will notify you every time a  new blog or project is posted
    form:
      type: FormBlock
      elementId: sign-up-form
      action: /.netlify/functions/submission_created
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
        - name: address
          label: Address
          hideLabel: true
          placeholder: Address
          isRequired: true
          width: full
          type: TextFormControl
        - name: updatesConsent
          label: Sign me up to recieve updates
          isRequired: false
          width: full
          type: CheckboxFormControl
      submitLabel: Submit form
      styles:
        submitLabel:
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
        alignItems: center
        justifyContent: center
        flexDirection: row
      title:
        textAlign: center
      text:
        textAlign: center
  - type: DividerSection
    colors: colors-d
    styles:
      self:
        width: wide
        padding:
          - pt-4
          - pb-4
          - pl-4
          - pr-4
        justifyContent: center
        borderWidth: 1
        borderStyle: solid
addTitleSuffix: true
metaTags: []
---

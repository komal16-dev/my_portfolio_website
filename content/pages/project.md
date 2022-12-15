---
layout: PageLayout
metaTitle: null
metaDescription: null
addTitleSuffix: true
socialImage: null
metaTags: []
title: Projects Name
sections:
  - type: FeaturedItemsSection
    colors: colors-c
    elementId: ''
    title: Key value propositions
    subtitle: ''
    items:
      - type: FeaturedItem
        title: YouTube API
        actions:
          - type: Button
            label: Read more
            showIcon: true
            icon: arrowRight
            url: /project/project1
            style: primary
        styles:
          self:
            textAlign: left
            padding:
              - pt-24
              - pl-24
              - pr-24
              - pb-24
            borderRadius: medium
        subtitle: Ali Ahmed's YouTube Channel
      - type: FeaturedItem
        title: Smarter
        text: >-
          Lorem ipsum dolor sit amet, consectetur adipiscing elit. Sed ante
          lorem, tincidunt ac leo efficitur, feugiat tempor odio. Maecenas
          pharetra ipsum dolor, et iaculis elit ornare ac.
        actions:
          - type: Button
            label: Learn more
            showIcon: true
            icon: arrowRight
            url: /
            style: primary
        styles:
          self:
            textAlign: left
    actions: []
    columns: 1
    spacingX: 16
    spacingY: 16
    enableHover: false
    styles:
      self:
        height: auto
        width: narrow
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
  - type: FeaturedItemsSection
    colors: colors-d
    elementId: ''
    title: Key value propositions
    subtitle: ''
    items:
      - type: FeaturedItem
        title: Faster
        text: >-
          Lorem ipsum dolor sit amet, consectetur adipiscing elit. Sed ante
          lorem, tincidunt ac leo efficitur, feugiat tempor odio. Maecenas
          pharetra ipsum dolor, et iaculis elit ornare ac.
        actions:
          - type: Button
            label: Learn more
            showIcon: true
            icon: arrowRight
            url: /
            style: secondary
        styles:
          self:
            textAlign: left
      - type: FeaturedItem
        title: Smarter
        text: >-
          Lorem ipsum dolor sit amet, consectetur adipiscing elit. Sed ante
          lorem, tincidunt ac leo efficitur, feugiat tempor odio. Maecenas
          pharetra ipsum dolor, et iaculis elit ornare ac.
        actions:
          - type: Button
            label: Learn more
            showIcon: true
            icon: arrowRight
            url: /
            style: secondary
        styles:
          self:
            textAlign: left
      - type: FeaturedItem
        title: Focused
        text: >-
          Lorem ipsum dolor sit amet, consectetur adipiscing elit. Sed ante
          lorem, tincidunt ac leo efficitur, feugiat tempor odio. Maecenas
          pharetra ipsum dolor, et iaculis elit ornare ac.
        actions:
          - type: Button
            label: Learn more
            showIcon: true
            icon: arrowRight
            url: /
            style: secondary
        styles:
          self:
            textAlign: left
    actions: []
    columns: 3
    spacingX: 16
    spacingY: 16
    enableHover: false
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
    text: >-
      We will notify you every time a shipment is heading to your neighborhood,
      and you could immediatly let us know if you want in or not
    form:
      type: FormBlock
      elementId: sign-up-form
      action: /.netlify/functions/submission_created
      destination: ''
      fields:
        - type: TextFormControl
          name: firstName
          label: First Name
          hideLabel: true
          placeholder: First Name
          isRequired: false
          width: 1/2
        - type: TextFormControl
          name: lastName
          label: Last Name
          hideLabel: true
          placeholder: Last Name
          isRequired: false
          width: 1/2
        - type: EmailFormControl
          name: email
          label: Email
          hideLabel: true
          placeholder: Email
          isRequired: true
          width: full
        - type: TextFormControl
          name: address
          label: Address
          hideLabel: true
          placeholder: Address
          isRequired: true
          width: full
        - type: CheckboxFormControl
          name: updatesConsent
          label: Sign me up to recieve updates
          isRequired: false
          width: full
      submitLabel: Submit form
      styles:
        submitLabel:
          textAlign: center
    media: null
    styles:
      self:
        height: auto
        width: narrow
        padding:
          - pt-24
          - pb-24
          - pl-4
          - pr-4
        alignItems: center
        justifyContent: center
        flexDirection: row
      title:
        textAlign: center
      text:
        textAlign: center
---

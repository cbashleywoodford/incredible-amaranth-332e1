---
title: Home
sections:
  - type: hero_section
    title: 'Hi, I’m Ash!'
    subtitle: >-
      I'm a bright, talented, ambitious and self-motivated web designer with a
      strong technical background who possesses self-discipline and the ability
      to work with the minimum of supervision. A good team player who thrives to
      create functional, creative and engaging web solutions.
    actions:
      - label: Contact Me
        url: '#contact-me'
        style: primary
    image: /images/important-moon.png
    image_alt: Ashley Woodford
    media_position: right
    media_width: fifty
    align: left
    padding_top: large
    padding_bottom: large
    background_color: primary
    background_image: images/watercolor.png
    background_image_repeat: repeat
    background_image_size: contain
    background_image_opacity: 8
    has_border: false
  - type: features_section
    title: My skills
    subtitle: What I do
    features:
      - title: The Fundamentals
        content: |
          *   HTML5

          *   CSS3/SCSS

          *   JS/TS

          *   Responsive Design
        actions: []
        image: /images/Free courses.png
        image_alt: Feature 1 illustration
        media_position: right
        media_width: sixty
        subtitle: of my skillset
      - title: Frameworks
        subtitle: From bleeding edge to household names
        content: |
          *   VueJS

          *   React

          *   Angular

          *   Svelte

          *   NuxtJS

          *   NextJS
        actions: []
        image: /images/2 People collaborating.png
        image_alt: Feature 2 illustration
        media_position: left
        media_width: sixty
      - title: Buildtools
        subtitle: 'Bundlers, pipelines, CI/CD'
        content: |
          *   Netlify

          *   Webpack

          *   NPM

          *   Gulp

          *   Parcel

          *   Yarn
        actions: []
        image: /images/Server.png
        image_alt: Feature 2 illustration
        media_position: right
        media_width: sixty
      - content: |
          *   Photoshop

          *   Illustrator

          *   XD

          *   Figma
        actions: []
        image: /images/CV selection.png
        image_alt: Feature 3 illustration
        media_position: left
        media_width: sixty
        title: Additional skills
    feature_padding_vert: large
    align: center
    background_color: none
    has_border: false
  - type: form_section
    content: >-
      ## Let's talk


      If you would like more information about my services and pricing, please
      contact me using the form below.
    content_align: left
    form_position: bottom
    form_width: fifty
    form_layout: stacked
    enable_card: true
    form_id: contact-form
    form_action: /thank-you
    form_fields:
      - input_type: text
        name: name
        label: Name
        default_value: Your name
        is_required: true
      - input_type: email
        name: email
        label: Email
        default_value: Your email address
        is_required: true
      - input_type: textarea
        name: message
        label: Message
        default_value: Your message
      - input_type: checkbox
        name: consent
        label: >-
          I understand that this form is storing my submitted information so I
          can be contacted.
        is_required: true
    submit_label: Send Message
    align_vert: top
    padding_top: medium
    padding_bottom: medium
    background_color: primary
    background_image: images/watercolor.png
    background_image_repeat: repeat
    background_image_size: contain
    background_image_opacity: 8
    section_id: contact-me
seo:
  title: Ashley Woodford | Front-End Developer
  description: 'Front-end developer based in Bournemouth, Dorset.'
  extra:
    - name: 'og:type'
      value: website
      keyName: property
    - name: 'og:title'
      value: Stackbit Personal Theme
      keyName: property
    - name: 'og:description'
      value: The preview of the Personal theme
      keyName: property
    - name: 'og:image'
      value: images/personal-preview.png
      keyName: property
      relativeUrl: true
    - name: 'twitter:card'
      value: summary_large_image
    - name: 'twitter:title'
      value: Stackbit Personal Theme
    - name: 'twitter:description'
      value: The preview of the Personal theme
    - name: 'twitter:image'
      value: images/personal-preview.png
      relativeUrl: true
layout: advanced
---

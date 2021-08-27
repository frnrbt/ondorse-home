---
title: Home
sections:
  - section_id: Intro
    type: section_hero
    title: Business is a changing world
    subtitle: Get instantly notified of any KYC and KYB change
    content: >-
      With increasing risks of frauds and enhanced regulatory obligations,
      access to real time corporate information is key. Ondorse’s always up to
      date information coupled with an asset freeze screening tool helps
      financial services companies continuously monitor relevant KYC and KYB
      information and make compliance more effective.
    forms:
      - title: Subscribe
        content: Stay up to date with our latest developments.
        form_id: contactForm
        hide_labels: true
        form_fields:
          - input_type: email
            name: email
            default_value: Enter email address
            is_required: true
        submit_label: Request access >
  - section_id: features
    type: section_features
    background: white
    title: Why Ondorse
    features:
      - title: null
        content: >
          ### For financial services companies

          *Including banks, insurance companies and other gatekeepers such as
          fintechs and crypto exchange platforms.*


          ##### Are you struggling with the manual and burdensome processes
          induced by the KYC refresh?


          Ondorse automatically populates your back office tool with the most up
          to date company information on the corporate customers you are engaged
          with.


          ##### Have you ever been up at night worrying about having shell
          companies amongst your corporate customers?


          Ondorse continuously monitors events affecting the KYB of your users
          and pushes you notifications in case of important corporate
          information updates, such as a UBO, shareholder or legal
          representative change.


          ##### Have you ever worried about being late on freezing the assets of
          one of your customers?


          Ondorse pushes you alerts in case of a true asset freeze match
          involving a connection (UBO, shareholder or legal representative)
          associated with one of your customers. With our screening tool fed
          with permanently refreshed information, you can now immediately comply
          with all your asset freeze obligations and associated direct and
          indirect AML-CFT risks.

          ### For marketplaces and platforms

          ##### Are you considering creating a unified KYC/KYB on your SME
          vendors ?

          Ondorse allows you access to the most up to date corporate information
          to better detect potential vendor fraud.
        actions: []
        image_alt: image
  - section_id: How it works
    title: How it works
    content: >
      Leveraging on a RESTful API, Ondorse provides you access to a database of
      connections (UBO, shareholder and legal representative) involving your
      corporate users in Europe and the U.K.


      ```console
        curl --location --request GET 'https://app.ondorse.co/api/v1/companies/:companyId'
      ```


      *   The database of connections is directly linked to official primary
      source corporate registers in Europe and the U.K. to guarantee data
      integrity.


      *   When an event affects a connection involving one of your corporate
      users, Ondorse’s API automatically sends this information to you via a
      push notification.


      *   Ondorse’s API can easily and immediately be integrated in your
      workflow, giving your teams the tools they need from day one.
    image_alt: lorem-ipsum
    background: gray
    actions: []
    type: section_content
  - section_id: features
    background: white
    features:
      - title: Cool feature Title
        content: >-
          ## Lorem ipsum


          Lorem ipsum dolor sit amet, **consectetur adipiscing elit**, sed do
          eiusmod tempor incididunt ut labore et dolore magna aliqua.


          - Lorem ipsum

          - dolor sit amet
        image_alt: lorem-ipsum
        actions:
          - label: lorem-ipsum
            url: '#'
            style: link
            has_icon: false
            icon: arrow-left
            icon_position: left
            new_window: false
            no_follow: false
            type: action
        type: feature_item
        image: images/undraw_Goals_re_lu76.svg
    type: section_features
seo:
  title: Ondorse
  description: >-
    Business is a changing world. Get instantly notified of any KYC and KYB
    change.
  extra:
    - name: 'og:type'
      value: website
      keyName: property
    - name: 'og:title'
      value: Ondorse
      keyName: property
    - name: 'og:description'
      value: Business is a changing world
      keyName: property
    - name: 'og:image'
      value: images/LOGO-ONDORSE-LONG.png
      keyName: property
      relativeUrl: true
    - name: 'twitter:card'
      value: summary_large_image
    - name: 'twitter:title'
      value: Ondorse
    - name: 'twitter:description'
      value: Business is a changing world
    - name: 'twitter:image'
      value: images/LOGO-ONDORSE-LONG
      relativeUrl: true
layout: landing
---

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
    actions:
      - label: Request Access to the API Documentation
        url: 'mailto:contact@ondorse.co'
        style: primary
        has_icon: false
        icon: arrow-left
        icon_position: right
        new_window: false
        no_follow: false
        type: action
  - section_id: features
    type: section_features
    background: white
    title: Why Ondorse
    features:
      - title: For financial services companies
        content: >
          Including banks, insurance companies and other gatekeepers such as
          fintechs and crypto exchange platforms.
          ##### Are you struggling with the manual and burdensome processes induced by
          the KYC refresh?
          Ondorse automatically populates your back office tool with the most up
          to date company information on the corporate customers you are engaged
          with.


          Have you ever been up at night worrying about having shell companies
          amongst your corporate customers? Ondorse continuously monitors events affecting the KYB of your users
          and pushes you notifications in case of important corporate
          information updates, such as a UBO, shareholder or legal
          representative change.
          Have you ever worried about being late on freezing the assets of one
          of your customers? Ondorse pushes you alerts in case of a true asset freeze match
          involving a connection (UBO, shareholder or legal representative)
          associated with one of your customers. With our screening tool fed
          with permanently refreshed information, you can now immediately comply
          with all your asset freeze obligations and associated direct and
          indirect AML-CFT risks.
        actions: []
        image_alt: image
      - title: For marketplaces and other platforms
        image_alt: App users welcoming a new member
        content: >
          Are you considering creating a unified KYC/KYB on your SME vendors ?
          Ondorse allows you access to the most up to date corporate information
          to better detect potential vendor fraud.
        actions: []
  - section_id: How it works
    title: How it works
    content: >
      Leveraging on a a RESTful API and webhooks, Ondorse provides you access to
      a database of connections (UBO, shareholder and legal representative)
      involving your corporate users in Europe and the U.K.


      ```cURL
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
  - section_id: Who we work with
    title: Who we work with
    content: |
      * Established financial institutions and insurance companies
      * Fintechs
      * Crypto exchange platforms
      * Marketplaces

      In collaboration with European banking regulators and agencies
    background: white
    actions: []
    type: section_content
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
      value: The preview of the Azimuth theme
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
      value: The preview of the Azimuth theme
    - name: 'twitter:image'
      value: images/LOGO-ONDORSE-LONG
      relativeUrl: true
layout: landing
---

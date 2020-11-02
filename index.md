---
layout: blocks
title: ApolloLabs
date: 2020-10-30T23:00:00.000+00:00
page_sections:
  - template: navigation-header-w-button
    block: block-header-2
    logo: "/uploads/img/logo.svg"
    navigation:
      - link: "/"
        link_text: Home
      - link: "#services"
        link_text: Services
      - link: "#team"
        link_text: Our Team
    # cta:
    #   url: https://deverick.io
    #   button_text: Blog
  - template: hero-banner-w-image
    block: block-hero-2
    slug: features
    logo-white: "/uploads/img/logo-white.svg"
    headline: <strong>Security First</strong>
    content:
        Because you deserve to focus on building valuable products.
    cta:
      enabled: true
      url: mailto:sales@apollolabs.io
      button_text: "Contact Us"
    image:
      image: "/uploads/2018/06/21/product-shot-1.png"
      alt_text: Product Shot
    background_image: "/uploads/2018/06/21/hero-2-bg.png"
  - template: content-feature
    block: block-feature-1
    media_alignment: Left
    slug: services
    headline:
      <strong>Pentesting<span class="light">&nbsp;</span></strong><span
      class="light">your Android and iOS Applications.</span>
    content:
      Understand the limitations of your app.  We provide easy to read reports so your team can stay ahead of threats.
    media:
      image: "/uploads/2018/06/21/blocks-split.png"
      alt_text: uBuild Blocks Mock-Up
  - template: content-feature
    block: block-feature-1
    media_alignment: Right
    slug: customize
    headline:
      <strong>Digital Forensics</strong><span class="light">&nbsp;for your infrastructure</span>
    content:
      Understand suspicious network activity and detect malware before it's too late.
    media:
      image: "/uploads/2018/06/21/edit.gif"
      alt_text: Customize Blocks

  - block: team/base
    slug: team
    headline: Our Team
    content: |
      Meet the Security Engineers focused on improving your applications. Each one brings an unique story we want to share.
    members:
    - name: s4lv4ti0n
      slug: s4lv4ti0n
      image: /uploads/team/s4lv4ti0n/s4lv4ti0n.jpg
      name_secondary: Tomi Jerenko
      email: s4lv4ti0n@apollolabs.io
      pgp_fingerprint: THIS ISSO MEFA KEPG PKEY 3C92 3D9F 6D5D ADDB 55F7
      # Lets limit to about 300-400 characters
      about: |-
        Security researcher with engineering background, specializing in application security.
        By applying extensive academical knowledge in practice, I carry out extensive penetration
        tests to make your code cry. The application is hardened by analyzing found weaknesses and
        proposing mitigations through consulting. - Finding the balance between security, usability,
        and performance takes an artist.
    - name: hashes4merkle
      slug: hashes4merkle
      image: /uploads/team/hashes4merkle/hashes4merkle.jpg
      name_secondary: Deverick Simpson
      website-name: Deverick.io
      website-link: https://deverick.io  
      email: deverick@apollolabs.io
      pgp_fingerprint: F3BC 56B4 6F54 A995 AE52 534F 2BE3 33A7 7646 64BE
      about: |-
        A digital nomad who enjoys poking at tech found in our communities.  With a background in psychology and cyber security, I leverage real-world techniques to test your organization's infrastructure security.
  - template: 1-column-text
    block: block-one-column-1-social
    slug: contact
    headline: Contact Us
    content: |
      We look forward to understanding your needs and how we can help.
    github:
      username: hashes4merkle
    twitter:
      username: hashes4merkle
      hashtag: '@hashes4merkle'
    social:
      name: Deverick Simpson
      email: deverick@apollolabs.io
      links:
        - https://twitter.com/hashes4merkle
        - https://github.com/hashes4merkle

  # - template: simple-footer
  #   block: block-footer-1
  #   content: Made with ❤︎

---

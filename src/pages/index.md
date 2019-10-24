---
title: Crafting Beautiful Online Experiences
sidebar:
  entries:
  - title: Welcome
    url: "#intro"
    is_primary: true
  - title: My Content
    url: "#one"
    is_primary: false
  - title: My Skills
    url: "#two"
    is_primary: false
  - title: Work with me
    url: "#three"
    is_primary: false
sections:
- type: intro
  template: intro
  title: Patrick Scully
  subtitle: Hey, there. Welcome to a whole website dedicated to me. This is basically
    a place to send my new followers to learn about me and what I do. If you are interested
    in my content please keep scrolling.
  section_id: intro
  background_style: style1
  actions:
  - label: Scroll
    url: "#one"
    is_scrolly: true
    is_primary: false
  component: Intro
- type: spotlights
  template: spotlights
  title: Spotlights Section
  section_id: one
  background_style: style2
  component: Spotlights
- type: features
  template: features
  title: Work With Me
  subtitle: Are you a start-up founder? Small business owner? There are many ways
    I can help you realize your idea's full potential.
  section_id: two
  background_style: style3
  features_list:
  - title: Custom Development
    text: 'My team and I are able to deliver custom-coded solutions to business owners
      looking for anything from a business website to complex backend systems. '
    icon: fa-code
  - title: Technical SEO
    text: We've been building and ranking websites for 15+ years. Leverage our expertise
      to help lock in revenue-generating search engine positions.
    icon: fa-lock
  - title: Consulting
    text: Are you in the idea phase of a new project but not sure which direction
      to go in for your backend, frontend, design, voice, or marketing? Let's talk.
    icon: fa-cog
  - title: Conversion Optimization
    text: Sending people to a poorly designed website or confusing digital assets
      will result in failure online. We help you win that customer through design
      and copy.
    icon: fa-desktop
  - title: Offsite SEO
    text: Once your website is up to par, what's next? Earning links and media mentions
      are. The piece of the ranking puzzle you are missing is strong link building.
    icon: fa-chain
  - title: Content Marketing
    text: My 7 Karat Diamond writing service gets your copy popping off the page.  Web
      pages, blog posts, product descriptions etc.
    icon: fa-diamond
  actions:
  - label: Learn more
    url: "/generic"
    is_scrolly: false
    is_primary: false
  component: Features
- type: contact
  template: contact
  title: Get in touch
  text: Custom code, design, copy, SEO, or consulting...it all starts with a conversation.
  section_id: three
  background_style: style1
  contact_list:
  - title: Address
    text: |-
      Based in Charlotte, NC
      From Franklin, MA
    url: https://twitter.com/pscully_
  - title: Email
    text: user@Hyperspace.tld
    url: "#"
  - title: Phone
    text: "(000) 000-0000"
    url: ''
  social:
    title: Social
    social_icons:
    - title: Twitter
      icon: fa-twitter
      url: https://twitter.com/pscully_
    - title: Facebook
      icon: fa-facebook
      url: https://www.facebook.com/realpatrickscully/
    - title: GitHub
      icon: fa-github
      url: "#"
    - title: Instagram
      icon: fa-instagram
      url: "#"
    - title: LinkedIn
      icon: fa-linkedin
      url: "#"
  component: Contact
menus:
  main:
    title: Home
    weight: 1
template: home

---

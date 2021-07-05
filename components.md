---
layout: layouts/blocks.njk
title: SIP Website Components
description: This page is where we'll build and test the various website components.
  It will deleted in production.
blocks:
- template: hero
  type: hero
  heading: The true measure of any society can be found in how it treats its most
    vulnerable members.
  subHeading: "- Mahatma Gandhi"
  image:
    source: /sip/mother-child.jpg
    altText: This is some sample alt text for the image
  buttons:
  - buttonText: Learn More
    color: blue
    url: "#"
  - buttonText: Get Involved
    color: white
    url: "#"
- template: rich-text
  type: rich-text
  content: |-
    <h1>Welcome to the Secure Information Project</h1><p>Secure Information
    Project (SIP) exists to document and information security for vulnerable
    families, new immigrants, refugees, and asylum-seekers in the United States</p><p>We believe in these words spoken by Mahatma Gandhi: “The true measure of any society can be found in how it treats its most vulnerable members.” Ergo, A society cannot be truly secure until it secures its most vulnerable people.</p><p>By supporting and securing low-income and new Americans, we can help build a more robust working class where families are self-sufficient and rely less on welfare programs to live happy, healthy, and productive lives.</p>
  backgroundColor: none
- template: grid
  type: grid
  gridRows:
  - row: Image + Donation Widget
    gridItems:
    - item: Image
      itemType: image
      text:
        content: ''
        buttons: []
      image:
        source: "/v1620418548/sip/placeholder-4.jpg"
        altText: some alt text describing the image
      video:
        videoCoverImage: ''
        videoId: ''
    - item: Donation Widget
      itemType: donation
      text:
        content: ''
        buttons: []
      image:
        source: ''
        altText: ''
      video:
        videoCoverImage: ''
        videoId: ''
- template: rich-text
  type: rich-text
  backgroundColor: yellow
  content: <h2>SIP Helps Vulnerable Populations in Philadelphia and Beyond Secure
    and Protect Their Most Valuable Assets</h2><p>Vulnerable populations are often
    subject to living in unsatisfactory conditions. For many reasons, critical documents,
    valuable possessions, and family heirlooms can be easily lost, destroyed, or stolen.
    SIP seeks to protect people who are just getting on their feet in the city - or
    the country - from fraud, theft, violence, or intimidation by helping them understand
    the value of their documentation and secure their personal information. Our programs
    and services are provided at no cost to ensure the lowest possible barrier to
    inclusion.</p><p><a href="/programs/" title="View Our Programs" target="_blank">View
    Our Programs</a></p>
- template: rich-text
  type: rich-text
  backgroundColor: none
  content: "<h2>Making a Difference, One Family at a Time</h2><p>SIP is dedicated
    to making a measurable impact in the lives of vulnerable populations through a
    variety of programs and initiatives. Below are just a few of the ways our work
    is making a difference.</p>"
- template: carousel
  type: carousel
  slide:
  - slideTitle: 'Test Slide #1'
    text:
      backgroundColor: blue
      content: "<p>Iceland skateboard poke tumeric succulents gentrify portland typewriter
        activated charcoal unicorn truffaut chartreuse.</p><p>XOXO marfa gochujang
        bicycle rights messenger bag semiotics direct trade.</p>"
      buttons: []
    image:
      source: "/v1620418245/sip/mother-child.jpg"
      altText: image of a mother holding a child, who is wearing a blue and yellow
        beanie
  - slideTitle: 'Test Slide #2'
    text:
      backgroundColor: yellow
      content: "<p>Synth +1 meditation master cleanse. Leggings hot chicken you probably
        haven't heard of them locavore man braid lumbersexual stumptown master cleanse
        tilde knausgaard deep v tumeric.</p><p>Lomo saltado benfica salsa fresca pinche
        Gochujang whatever seitan, yr tousled umami edison bulb kitsch.</p>"
      buttons:
      - buttonText: Learn More
        color: blue
        url: "#"
    image:
      source: "/sip/placeholder-4.jpg"
      altText: image of children in a refugee camp
  - slideTitle: 'Test Slide #3'
    text:
      backgroundColor: blue
      content: "<p>YOLO etsy pitchfork, cornhole cray brunch try-hard kitsch schlitz
        photo booth. Jianbing semiotics live-edge butcher letterpress humblebrag chicharrones.
        Shabby chic lomo chartreuse taiyaki four loko glossier gluten-free. Selvage
        dreamcatcher butcher chia kogi.</p>"
      buttons: []
    image:
      source: "/sip/placeholder-2.jpg"
      altText: image of children in a refugee camp
- template: parallax-callout
  type: parallax-callout
  textOverlay:
    backgroundColor: yellow
    overlayPosition: center
    content: "<h2>Want to get involved? SIP is always looking for volunteers, donors,
      and those interested in growing our impact.</h2>"
    buttons:
    - buttonText: Learn How to Get Involved
      color: blue
      url: "#"
  backgroundImage: "/v1620418548/sip/placeholder-2.jpg"

---

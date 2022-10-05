---
layout: layouts/blocks.njk
title: Donate to SIP
description: Giving to SIP is quick, easy, and secure! Visit to donate online today.
blocks:
- template: grid
  type: grid
  gridRows:
  - row: Text + Donation Widget
    gridItems:
    - item: Giving to Secure Information Project
      itemType: text
      text:
        content: "<h1>Giving to Secure Information Project</h1><p>Your donation helps
          to support our mission, enhance our programs, and protect vulnerable communities
          in Philadelphia and beyond. Whether it's a one-time gift or a recurring
          donation, every little bit allows SIP to address information protection
          and security needs of our most vulnerable neighbors.</p>"
        buttons: []
      image:
        source: ''
        altText: ''
      video:
        videoCoverImage: ''
        videoId: ''
    - item: Donation Widget (DonorBox)
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
- template: parallax-callout
  type: parallax-callout
  textOverlay:
    backgroundColor: white
    overlayPosition: center
    content: "<p>text about donating and where money will go</p>"
  backgroundImage: "/v1639585602/sip/sip_fadedlock_blue_kgwcy1.png"

---

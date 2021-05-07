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
    source: https://images.unsplash.com/photo-1530490125459-847a6d437825?ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&ixlib=rb-1.2.1&auto=format&fit=crop&w=1363&q=80
    altText: This is some sample alt text for the image
  buttons:
  - buttonText: Learn More
    color: blue
    url: "#"
  - buttonText: Get Involved
    color: white
    url: "#"
- template: body-content
  type: body-content
- template: grid
  type: grid
  grid-rows:
  - row: Text + Image
    grid-items:
    - item: Text
      item-type: text
      text:
        background-color: none
        content: "<h1>Welcome to the Secure Information Project</h1><p>Secure Information
          Project (SIP) exists to document and information security for vulnerable
          families, new immigrants, refugees, and asylum-seekers in the United States<br><br>Gentrify
          lumbersexual direct trade everyday carry pabst kogi. Schlitz letterpress
          3 wolf moon, mixtape vegan everyday carry retro. Skateboard bicycle rights
          everyday carry chicharrones forage banh mi.</p>"
        buttons: []
      image:
        source: ''
        alt-text: ''
      video:
        video-cover-image: ''
        video-id: ''
    - item: Image
      item-type: image
      text:
        background-color: none
        content: ''
        buttons: []
      image:
        source: "/v1620418548/sip/placeholder-4.jpg"
        alt-text: some alt text describing the image above
      video:
        video-cover-image: ''
        video-id: ''

---
# Heading 1 - Body Content Block

Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud [exercitation ullamco laboris](#) nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.

Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.
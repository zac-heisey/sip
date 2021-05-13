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
  gridRows:
  - row: Text + Image
    gridItems:
    - item: Text
      itemType: text
      text:
        content: "<h1>Welcome to the Secure Information Project</h1><p>Secure Information
          Project (SIP) exists to document and information security for vulnerable
          families, new immigrants, refugees, and asylum-seekers in the United States<br><br>Gentrify
          lumbersexual direct trade everyday carry pabst kogi. Schlitz letterpress
          3 wolf moon, mixtape vegan everyday carry retro. Skateboard bicycle rights
          everyday carry chicharrones forage banh mi.</p>"
        buttons: []
      image:
        source: ''
        altText: ''
      video:
        videoCoverImage: ''
        videoId: ''
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
  - row: Video
    gridItems:
    - item: Video
      itemType: video
      text:
        content: ''
        buttons: []
      image:
        source: ''
        altText: ''
      video:
        videoCoverImage: ''
        videoId: 15VU_mbcrB0
    - item: Donation Widget
      itemType: donationWidget
      text:
        content: ''
        buttons: []
      image:
        source: ''
        altText: ''
      video:
        videoCoverImage: ''
        videoId: ''
      donationWidget:
        heading: Give to SIP
- template: rich-text
  type: rich-text
  content: |-
    <h1>Heading 1 - Rich Text Block</h1><p>Pop-up hexagon edison bulb chicharrones yuccie fam. Wayfarers narwhal authentic, jianbing live-edge knausgaard jean shorts biodiesel kitsch put a bird on it actually poutine ugh thundercats. Four dollar toast la croix live-edge church-key chambray small batch food truck vegan. Ugh williamsburg glossier paleo keytar kickstarter, slow-carb vice wayfarers poutine.</p><p><img src="https://res.cloudinary.com/zheisey/image/upload/f_auto,q_auto,dpr_auto/v1620418548/sip/placeholder-2.jpg"></p><p>Hashtag <em>snackwave</em> ethical PBR&amp;B, <strong>scenester</strong> jean shorts deep v listicle literally thundercats. Palo santo next level twee copper mug vice. <a href="#" title="" target="_blank">Occupy ennui whatever</a> literally pitchfork. Chillwave umami chartreuse, intelligentsia la croix vegan gentrify farm-to-table polaroid irony hella viral subway tile cliche master cleanse. Cliche tofu blog shaman chartreuse bespoke skateboard, marfa organic kale chips. Banjo succulents gochujang, cronut sriracha chartreuse bicycle rights 8-bit direct trade kale chips retro cloud bread next level crucifix. Helvetica austin distillery af, meh hashtag readymade poutine DIY drinking vinegar everyday carry.</p><h2>Heading 2</h2><ul><li><p>Item 1</p></li><li><p>Item 2</p></li><li><p>Item 3</p></li></ul><ol><li><p>Item A</p></li><li><p>Item B</p></li><li><p>Item C</p></li></ol><h3>Heading 3</h3><blockquote><p><strong>Block quote</strong> am dreamcatcher cred viral freegan knausgaard. Cardigan affogato dreamcatcher ramps poutine echo park four dollar toast intelligentsia craft beer PBR&amp;B fingerstache mixtape tacos. Taxidermy af gluten-free pabst farm-to-table truffaut yuccie. DIY lomo single-origin coffee bushwick disrupt, etsy vape schlitz.</p></blockquote><p></p><pre><code>Code block lorem ipsum code...
    stuff...
    things...
    cosas...</code></pre>
  backgroundColor: none

---
# Heading 1 - Body Content Block

Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud [exercitation ullamco laboris](#) nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.

Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.
---js
{
  layout: "layouts/blocks.njk",
  title: "SIP News",
  description: "News, updates, and more from Secure Information Project",
  pagination: {
    data: "collections.posts",
    size: 3,
    reverse: true,
    alias: "posts",
    before: function(data) {
      return data.slice(0, -1);
    }
  },
  blocks: [
    {
      template: "posts-list",
      type: "posts-list"
    },
    {
      template: "quick-cta",
      type: "quick-cta",
      backgroundColor: "blue",
      headline: "Sign Up for News, Updates, and More from SIP",
      buttons: [
        {
          buttonText: "Get SIP Updates",
          color: "yellow",
          url: ''
        }
      ]
    }
  ]
}

---

---
description: >-
  This module should simplify new content creation for feeds. Once it configured
  a content manager will to create a new blog page from a canvas page using
  action pad.
---

# Blog Module 22

### DB structure

```javascript
const structure = {
  modules: [
    {
      id: 'blogId',
      type: 'blog',
      siteId: siteId,
      enabled: true,
    },
  ],
};
```

After this operation you will get next pages:

* `/templates/blog-template` - template page which is used for all new blog posts, you can modify it to fit your goals for the current client
* `/feed` - page with feed tile where all blog posts will be aggregated. Feel free to change URI of this page

{% page-ref page="subpage.md" %}


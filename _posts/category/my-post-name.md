---
title: My Post Name
---

Lorem ipsum dolor sit amet, consectetur adipisicing elit. 
A alias, beatae cupiditate eveniet inventore ipsum iure 
laboriosam officia quas repudiandae similique sunt tenetur, 
voluptatibus. Accusamus accusantium aliquid at molestiae qui.


```js
import React from 'react';
import { Helmet } from 'react-helmet';

const Head = ({ siteMetadata, children }) => {
  return (
    <Helmet titleTemplate={`%s | ${siteMetadata.author}`}>{children}</Helmet>
  );
};

export default Head;
```

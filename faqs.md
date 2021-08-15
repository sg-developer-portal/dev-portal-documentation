### Overview

This page provides frequently asked questions on publishing content in Singapore Government Developer Portal. If you are not able to find your answers here, you can reach out to Dev Portal team at <gds_developer_portal@tech.gov.sg>. 

**What is the naming convention for a new markdown file?**
- The naming convention for a markdown file is: product-name.md (e.g. dev-portal.md, lifesg.md).

**What is the naming convention for an image file?**
- As the images for all content are stored in the same folder, the image filename should indicate that the image file belongs to the product. The naming convention for an image file is: productname-alias.png (e.g. dev-portal-dashboard.png, lifesg-dashboard.png).

**How can I upload and play a youtube video in the page?**
- To publish and play youtube videos within the page, copy the below code to your page and update the *'video-id'* to your youtube video it.
```
<iframe src="https://www.youtube.com/embed/<video-id>?showinfo=0" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
```

**How do I bold a text/sentence?**
- To bold a text/sentence, add '\*\*' before and after the text/sentence (e.g. **\*\*text\*\***).

**How do I set the text/sentent to italics?**
- To set the text to italics, add '\*' before and after the text/sentence (e.g. *\*text\**).

**How do I display special characters?**
- To display special characters, add '\\' before each special characters (e.g. \\\<special character>).

**How do I redirect an old page to a new page?**
- To redirect an old page to a new page, insert the *'redirect_from'* tag after the *'description'* tag in the front matter 
(e.g. redirect_from: \<old page url>).

**How do I create a numbered list?**
- To create a numbered list, simply add *1.\<spacing>* follow by the text/sentence (e.g. 1. Text).

**How do I create a bulleted list?**
- To create a bulleted list, simply add *-\<spacing>* follow by the text/sentence (e.g. \- Text).


---
title: "SEO zen: 5 fundamentals to improve your Site's rankings"
tags: ["Marketing", "SEO"]
---

Modern Search Engines are **constantly evolving** their selection criteria, each devising a unique set of **highly sophisticated metrics** (i.e: [Google](https://www.google.com/search/howsearchworks/), [Bing](https://www.bing.com/webmasters/help/webmaster-guidelines-30fba23a), [Yahoo](https://help.yahoo.com/kb/SLN2216.html) etc.) to rank sites in their results. Search Engine services use programs called '[crawler bots](https://www.cloudflare.com/en-gb/learning/bots/what-is-a-web-crawler/)' to extract raw text and metadata from the websites it lists.

Google's relentless [market dominance](https://www.statista.com/statistics/216573/worldwide-market-share-of-search-engines/) makes it an easy place for us to focus our efforts, but by stripping our site design back to _thoughtful writing_ and _common-sense design_, we can ensure our content is robust enough to perform well over **any Search Engine Result Page** (or [SERP](https://mailchimp.com/en/marketing-glossary/serp/), for short). 

## The Basics

<img class="clip" src="/images/posts/seo-basics/student-text-highlighter.jpeg" alt="Student reviewing text with a yellow highlighter"/>

As we run through each principle, notice the example provided as relevant to this scenario:
> You are running an Arts and Crafts shop in Windsor, UK: 'Project Paint'. The shop is a small business who aim to support independent local Artists in making a living from their work.  

### Content

<img class="clip" src="/images/posts/seo-basics/typography.jpg" alt="Character sets of different typographies"/>

When creating a useful Web Page, content is king. For Search algorithms, then the analog is much the same. Perfecting your prose alone may not cause you to soar through the ranks - there are lots of factors at play with content ranking mechanisms:

- #### Keywords:
     When writing for the web it is **paramount** that the content you write _targets the needs_ of your intended users. 
     
     By including **key phrases** and words that align with the **goals of your user base**, you can ensure that your website is identified by a Search Engine as a [relevant resource](https://www.google.com/intl/en/search/howsearchworks/how-search-works/ranking-results/#relevance). It might be tempting, then, to pack your content full of keywords - stuffing every paragraph to the brim, however most Search Engines are wise to this, employing [mechanisms](https://www.google.com/search/howsearchworks/how-search-works/detecting-spam/) which will actually **penalise you** for trying to gain _an unfair advantage through SEO tricks_.
     
    For our (imaginary) shop 'Project paint', try to visualise what people might search for when seeking Art supplies:
    - Art supplies Windsor
    - Local business
    - Art shop
    - Local Art
    - Card and paper supplies
    ...

- #### Backlinks
    
     The 'World Wide Web' is a network of information, so if your newly written masterpiece **doesn't reference** any sources _corroborating your statements_, then, the information is much **less likely to be trusted**, especially by Search Engines.
     
     Links which **support the facts** in your content are known as '[Backlinks](https://www.squarebird.co.uk/the-beginners-guide-to-backlinks/)', and are important in ensuring your website hold rank. Not any old link will do, there is a question of ['Domain Authority'](https://ahrefs.com/seo/glossary/website-authority) at play here: always aim for tried and trusted sites that you would go to yourself for information.


     For 'Project Paint, we may want to backlink to:
     - **Educational resources for Artists**: the more reputable the better
     - **Official Websites for the brands**: as relevant to the products stocked in the shop
     - **Local events and organisations**: painting

### Site Usability

<img class="clip" src="/images/posts/seo-basics/Bicycle-mechanic.jpg" alt="Bike mechanic inspecting bike"/>

A book is only useful if you can understand what is written in it's pages, i.e: the print has not faded, the pages are intact, or even the book is not misplaced. In a roundabouts way, Web Pages have similar limitations: they are only useful to a user if they are reliable and easy to access. Some common issues of page usability are as follows:

- **Loading times**: large-scale images and resource-heavy JavaScript files (i.e: libraries such as [jQuery](https://jquery.com/)) 
- **Site stability**: Is your site prone to crashes? Do errors cause some content to be missing when loading a page?
- **Broken links**: When reading an article, it is very frustrating to click on a link and find an error message 'resource not found'. 

     When including links it is important to regularly check that the content they link to still exists. Likewise with your own site, when you move the URL of a page, ensure that the old URL is redirected to the new resource.
- **Semantic tagging**: Taking the underlying code (HTML) of a page, is the document structured clearly? Does it use the correct tags for each element? These concerns are more formally known in Web Development as [Semantic Tagging](https://www.semrush.com/blog/semantic-html5-guide/), and are a crucial underpinning to ensure your page is not only accessible to disabled users, but also to the [crawler bots](https://www.cloudflare.com/en-gb/learning/bots/what-is-a-web-crawler/) that Search Engines use to analyse your website. If you structure the underlying code well enough you may be eligible for a ['Rich Preview'](https://developers.google.com/search/docs/appearance/structured-data/sd-policies) within Google results.

     Additionally, HTML attributes are important. One such example is the [`alt` tag](https://developer.mozilla.org/en-US/docs/Learn/HTML/Multimedia_and_embedding/Images_in_HTML#alternative_text) for images, a common aid for Search Engines and [Screen Readers](https://en.wikipedia.org/wiki/Screen_reader) alike to programmatically understand what an image depicts or represents.


Usability is naturally a more technical area of SEO metrics, but the issues it addresses can have far-reaching implications for your site as a whole. As such, there is a lot of reading you can do around usability, for instance how Google analyses Site Performance through it's [Core Web Vitals](https://web.dev/articles/vitals) system, which I will explain in a future article.

'Project Paint' may want to ensure that:

- Images of example artwork are **scaled down** to a limited resolution (especially on mobile sites, where the processing power and internet speed of the device is limited)
- Links to local Art organisations are regularly checked for validity, in case sites that are referenced get moved

### Meta-Information

<img class="clip" src="/images/posts/seo-basics/tags-info.jpg" alt="A cartoon man surrounded by HTML tag names looking thoughtful/confused"/>

Whilst page [meta-data](https://mailchimp.com/en/resources/meta-tags-and-the-head-section-of-a-website/) could technically fall under [usability concerns](#site-usability) (Semantic Tagging), correctly configuring meta-data for your site can have far-reaching implications for your success in Search Rankings. All meta-data tags are contained in the [`<head>` section](https://developer.mozilla.org/en-US/docs/Learn/HTML/Introduction_to_HTML/The_head_metadata_in_HTML) of your HTML code, which is where all page setup usually goes.

- [**Description**](https://web.dev/learn/html/metadata): This tag is (as the name implies) a description for the site. It is very useful for SEO as it can help control how the page will be described on Search Engine results.
- [**Title**](https://developers.google.com/search/docs/appearance/title-link): The title for the page. The text contained in this tag will display as the clickable link in the Search Results, and will display in the tab heading of the browser.
- [**Open Graph tags**](https://developer.mozilla.org/en-US/docs/Learn/HTML/Introduction_to_HTML/The_head_metadata_in_HTML#other_types_of_metadata): The [Open Graph](https://ogp.me/) protocol is a more advanced topic regarding [Web APIs](https://www.w3schools.com/js/js_api_intro.asp). The bottom line, however, is that `:og` tags will allow you to control the preview of your page when someone shares it to their feed.
- [**Robots tag**](https://www.semrush.com/blog/robots-meta/): This tag is a direct instruction to Search Engines as to how to respond to your Web Page: do you want the page to be accessible from Search Engines? Generally the answer will be 'yes', however some pages (such as login screens) are not useful to index, and can be excluded.
- [**Meta-Viewport tag**](https://developer.mozilla.org/en-US/docs/Web/HTML/Viewport_meta_tag): This tag is targeted towards mobile devices, and by including it in your site's `<head>` you indicate to Google that your site is optimised for mobile devices. 

### Sitemap

<img class="clip" src="/images/posts/seo-basics/map.jpg" alt="A historical paper map of New York"/>

A [Sitemap](https://mailchimp.com/en/resources/sitemaps/) is a document which describes the heirarchy of pages within in your site. Yes, I know, boring! But in the World of SEO, sitemaps can be incredibly powerful tools to improve your Search Ranking.

Sitemaps are usually written in a language called ['XML'](https://en.wikipedia.org/wiki/XML) (e**X**tensible **M**arkup **L**anguage), and are very often [autogenerated](https://wordpress.com/support/sitemaps/) by site builders and CMS systems. If you are building a website from scratch, a sitemap will be your responsibility to write: by writing your own sitemap you can carefully select what pages you want to expose to search engines.

Search engines will use sitemaps to understand the content of your website and it's underlying structure, but it can also help inform Search Engines about other topics, such as recent page updates - see this excerpt from [MailChimp](https://mailchimp.com/)'s sitemap guide:

> ...an XML sitemap can inform search engines that your pages have recently been updated and require crawling to properly index and rank them in search results

Mailchimp also purports that if your site is newly launched, a sitemap will give Search Engines a quick nudge that you want to be included in Search Rankings:

> ...having an XML sitemap can help alert search engines that you have new pages on your site they should crawl.


## Recap

SEO is a vast, detailed field of Web Development, but most of the concerns within it fall into broad categories, such as 'Content Relevance or 'Site Usability'. 

To achieve as much traffic from Search Engines as possible, you should pay careful attention that:
- Your **content** is written with your _target audience in mind_.
- Each page you publish _is annotated_ with **appropriate meta tags** to give context.
- You link to **trustworthy sources** of information when explaining topics.
- You design your pages to _load_ **reliably and quickly**.
- You expose a **sitemap.xml** document, _detailing the hierarchy_ of your site.

Wishing you much success in climbing the SERP ladder!

Any questions? Feel free to drop me an [email](mailto:scottwebdev@proton.me).
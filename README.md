# tem
Simple Texpattern CMS theme to interlink multiple-user content (articles) through key words, related articles, categories, the search function, and links to author pages listing authors' articles. Designed to promote collaborative, project-based relational learning but could be used for IndieWeb selfdogfooding purposes. Sample images in the wiki. Thanks to the Textpattern forum for help.

## Textpattern tem theme

This theme is built fpr the Textpattern CMS [Textpattern CMS](https://textpattern.com/). It is a very simple theme built on the Textpattern Zero (empty) install, designed to promote collaborative, project-based relational learning but could be used for other purposes. It seeks to interlink user content (articles) through key words, related articles, categories, the search function, and links to author pages listing an author's articles. The homepage displays the titles of, excerpts from, and links to important content. Important content could include a mission statement and any important, more permanent, messages and is followed by feature articles that can be changed as needed. The category list and search bar are always visible on all pages. Where posts in a category/search result exceed the article limit, a "previous" and "next" page option appears. It is also possible to use the search bar to do a rudimentary search not only of site content but author content providing the author name appears in the text of at least one post. As simple as it is, it was built through the help of the Textpattern Forum.

### Features

1. Beginner friendly - the theme could also be used as a simple illustration of a readymade textpattern site for non-programmers who are interested in tailor making their own simple sites. This could be of use in IndieWeb selfdogfooding.
2. Anti-bloat. Style inspiration taken from bettermotherfuckingwebsite.com. 
3. Eco-friendly: the theme scores in the 98th percentile on the Website Carbon Calculator.
4. No external images used, but code indicates where theme users should place their own images (cf. "icon").
5. Sustainable. It is Textpattern, which is an enduring CMS and one with a community. 

#### Important note

This theme was written by a beginner who did not want to task programmers with such a simple design. Constructive criticism is welcome.


##### After installing - how to get this theme to work

To get this theme working, it is necessary to set up the Sections. 

Once textpattern has been installed and this theme has been uploaded (or, for absolute beginners, copy-pasted into each respective section visible under Content and Presentation sections), it is necessary to set up Sections by selecting Sections from Presentation and set up the following four sections:

1.  default with default page and default style - and importantly - no on default page, no on syndicate styles, and no to searchable

2. search with search page, default style - and importantly - no on default page, no on syndicate styles, and no to searchable

The rest of the pages get yes default with default page, syndicate articles, and searchable: 

4. articles with page articles style default;
5. featured takes articles page and default style
6. important takes articles page and default style . 

###### About video content

Embedding video content requires Morand's oui_embed plugin to get the media_video form to work.
Link to oui_embed: https://textpattern.org/plugins/1314/oui_embed
Link to explanation of how to install it: https://github.com/NicolasGraph/oui_embed (note it further requires embed - but it explains how to get this).


## License

Licensed under the [GPLv2 license]. 

## Thanks

Thanks to the Textpattern forum for helping this idea come to fruition. Thank you also to the Free Software Foundation.

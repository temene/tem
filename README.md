# tem
Simple Texpattern CMS [Textpattern CMS](https://textpattern.com/) theme to interlink multiple-user content (articles) through key words, related articles, categories, the search function, and links to author pages listing authors' articles. Designed to promote collaborative, project-based relational learning but could be used for IndieWeb selfdogfooding purposes. Sample images in the <a href="https://github.com/temene/tem/wiki/Sample-images/">wiki</a>. 

This simple theme was built on the Textpattern Zero (empty) install.

The homepage displays the titles of, excerpts from, and links to important content. Important content could include a mission statement and any more permanent messages. This section is followed by feature articles that can be changed as needed. The category list and search bar are always visible on all pages. Where posts in a category/search result exceed the article limit, a "previous" and "next" page option appears. It is also possible to use the search bar to do a search not only of site content but also a rudimentary search of author content providing the author name appears in the text of at least one post. Author links within posts lead to the page listing all of the author's articles. It was built through the help of the Textpattern Forum.

## Features

1. Beginner friendly - the theme could also be used as a simple illustration of a readymade textpattern site for non-programmers who are interested in tailor making their own simple sites. This could be of use in IndieWeb selfdogfooding.
2. Anti-bloat. Style inspiration taken from bettermotherfuckingwebsite.com. 
3. Eco-friendly: the theme scores in the 98th percentile on the Website Carbon Calculator.
4. No external images used, but code indicates where theme users should place their own images (cf. "icon"). It also suggests promotion of free software with icon of user's choice.
5. Sustainable. It is Textpattern, which is an enduring CMS and one with a community. 

### Important note

This theme was written by a beginner who did not want to task programmers with such a simple design. Constructive criticism is welcome. Note that the theme is being used on two sites with over 150 members each.


#### After installing - how to get this theme to work

To get this theme working, it is necessary to set up the Sections. 

Once textpattern has been installed and this theme has been uploaded (or, for absolute beginners, copy-pasted into each respective section visible under Content and Presentation sections), it is necessary to set up Sections by selecting Sections from Presentation and set up the following four sections:

1.  default with default page and default style - and: no on default page, no on syndicate styles, and no to searchable

2. search with search page and default style - and: no on default page, no on syndicate styles, and no to searchable

The rest of the pages get yes default with default page, syndicate articles, and searchable: 

4. articles takes articles page and default style
5. featured takes articles page and default style
6. important takes articles page and default style  

##### About video content

Embedding video content requires Morand's oui_embed plugin to get the media_video form to work.
Link to oui_embed on the textpattern plugin forum: https://textpattern.org/plugins/1314/oui_embed
Link to explanation of how to install the plugin on the plugin github page: https://github.com/NicolasGraph/oui_embed (note the plugin further requires installing embed - but Morand's github page linked to here explains how to get that set up).


## License

Licensed under the <a href="https://github.com/temene/tem/blob/tem-theme/tem_built_on_zero/6LICENSE">GPLv2 license</a>. 

## Thanks

Thanks to the Textpattern forum for helping this idea come to fruition. Thank you also to the Free Software Foundation.

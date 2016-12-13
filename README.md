# Jekyll Starter Theme for Accelerated Mobile Pages (AMP).

## Main Features
- Great for SEO.
- Superfast.
- Simple and flexible for redesigning existing website.


Starting point is creating a making AMP pages in Jekyll where it will be simple and time saving to redesign and update the code by separation of concerns and Don't Repeat Yourself (DRY). 

I also wanted to make it as simple as possible to add new pages that are SEO- and AMP-ready without having to edit too much code. Automation of optionally adding inline Schema JSON-LD of the currently supported by AMP: Article, NewsArticle, BlogPosting, VideoObject. 

As I didn't find any solution that meets my requirements to SEO and I am new to Jekyll, Liquid, it was trial and error till I found the solutions that worked exactly like need. I'm sure some solutions could be more elegant - especially in Liquid could be more elegant, but I am very happy about the outcome that matters: the end code. 

If building on a localhost, the URLs in the _site folder will get corrected when typing the command: jekyll build.

# SEO-friendliness
- Option to keep existing URL structure in order to preserve link juice and avoid 404s: .htm html or / .
- Automatic and proper canonical and amphtml links (Absolute paths are mandatory).
- Easy to add proper use of hreflang to alternative language by adding alternative URL and language to Front Matter. This could also be performed in a properly formatted sitemap, but will add to complexity when adding new pages and will be more difficult to control manually. The hreflang helps Google choose the right search result to render, and is also claimed to reduce risk of too much repeated content - and in some cases - duplicate content. 
- Proper language tags in code.
- Custom title and meta description on each page by adding it to Front Matter (Avoid repeated use).
- Absolute path internal links. Ensure link juice and reduce duplicate content risks.
- Option to add supported.
- Automatically adds each page's info from Front Matter to the relevant inline manifest.json. In order to ensure AMP is valid - headline in manifest.json is automatically stripped of characters exceeding 110. The rules to the logo and photos have to be done manually, though (https://developers.google.com/search/docs/data-types/articles).   


# Features 
- Pure AMP pages.
- Optional alternative non-AMP pages.
- 2 languages for now.
- For additional speed: Complete removal of whitespace stripping of comments for additional speed. This is accomplished by additions to _config.yml and wrapping the layout in "compression.html". For code readability you can uncomment // layout: compress in the relevant template when in development.
- Added menu using 
- Google Webfonts and Font Awesome Icons via CDN. See valid option for AMP Pages ( https://www.ampproject.org/docs/guides/responsive/custom_fonts)

# Likely to Be Added Later
- Possibility of adding all types of supported JSON-LD formats.
- The changing language feature can certainly be more nifty when I get the time, but it works for my purpose of having 2 language options right now.
- Open Graph and Twitter Card data etc.
- Adjust the posts URLs.

# Read more
Documentation - much more will be added (http://streetpatrol.com/accelerated-mobile-pages/)


# Ressources Used
- AMP Project - Official Website (https://www.ampproject.org/)
- AMP Project on GitHub ((https://github.com/ampproject/amphtml/)
- Jekyll (http://jekyllrb.com/)
- Compression.html (http://jch.penibelst.de/) 





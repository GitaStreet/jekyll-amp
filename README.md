# Jekyll Theme for Accelerated Mobile Pages (AMP)

Jekyll Starter Theme for Accelerated Mobile Pages (AMP)

Starting point is creating a making AMP pages in Jekyll where it will be simple and time saving to redesign and update the code by separation of concerns and Don't Repeat Yourself (DRY). 

I also wanted to make it as simple as possible to add new pages that are SEO- and AMP-ready without having to edit too much code. Automation of optionally adding inline Schema JSON-LD of the currently supported by AMP: Article, NewsArticle, BlogPosting, VideoObject (https://github.com/ampproject/amphtml/tree/master/examples/metadata-examples). 

As I didn't find any solution that meets my requirements to SEO and I am new to Jekyll, liquid, it was trial and error till I found the solutions that worked. 


# SEO-friendliness
- Option to keep existing URL structure in order to preserve link juice and avoid 404s: .htm html or / 
- Automatic and proper canonical and amphtml links (Absolute paths)
- Easy to add proper use of hreflang to alternative language by adding alternative URL and language to Front Matter
- Proper language tags in code
- Custom title and meta description on each page by adding it to Front Matter (Avoid repeated use)



# Features 
- Pure AMP pages
- Optional alternative non-AMP pages
- Two languages for now
- For additional speed: Complete removal of whitespace stripping of comments for additional speed. This is accomplished by additions to _config.yml and wrapping the layout in "compression.html". Thanks to (http://jch.penibelst.de/) 


# Likely to Be Added Later
- The changing language feature can certainly be more nifty when I get the time, but it works for my purpose of having 2 language options right now.
- Open Graph and Twitter Card data etc
- 

# Ressources Used
AMPproject





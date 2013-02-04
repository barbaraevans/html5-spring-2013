html5-spring-2013
=================

SRJC CS50.12 Section 5371

This is a template repository for Santa Rosa Junior College students.
Document your exercise submission here:

I converted one of my class xHTML pages to HTML5 using semantic HTML.  The purpose was to label content by what it is using HTML5’s new semantic elements including header, nav, article, aside and footer.  

The reasons for this are: 
•  Easier editing and maintenance because the structural information is part of the markup
•	Better accessibility for people using screen readers or other assistive tools
•	Better SEO because the site is more understandable and has a better chance of matching a searcher’s query
•	Cleaner, clearer pages that are ready for new browsers and web editing tools

First I changed the DOCTYPE to the simple “<!DOCTYPE html>”.  Then I simplified the root element to html lang="en".
Then I added the head element which contains metadata, information about the page but not content. I shortened the link relation for the style sheet by dropping the type attribute to become link rel="stylesheet" href="main.css".  I also added the script to make earlier IE versions render the new html5 tags.

I added the header semantic element which contains the background image for the page header.  I added an h1 tag with the headline and made the display:none so it wouldn’t show but would be there structurally.  I used an h2 tag for the subtitle and also made it hidden.  Since the h1 and h2 were related, I placed them both within an hgroup element.

I added the nav element for the navigation. 
I created a section element for the content on the page, which is a destination.  I put the existing h3 here since it pertained to the whole section.
Within the section I used the aside element for sidebar tangential content.
Also within the section I had an article with the main content.  I used this nesting so I would have the flexibility to possibly add another article within the same section in the future.

Finally I used the footer element to contain the more minor links and copyright information at the bottom of the page.  I did not use the nav element within the footer because the links were not the major ones.

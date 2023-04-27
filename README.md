## Planning

In this stage I prepared myself by going over the resources provided by founders and coders as a starting base. 

I later moved on to watching various YouTube videos about coding in HTML and CSS. I watched Dani Krossing's series which explained how to add the basics such as background colours, images, flex-grow and many more useful features.

I moved on to choosing a topic to write about, which was not to hard to figure out. I used a quick spider diagram on paper to jot down some of the things I am interested in and it quickly became obvious what would be a good fit.

Once I had a basic understanding of what can be done using the programming language and my topic of choice, I set out to draw some layouts of what my hobby page could look like. I took inspiration from other people's blogs and websites that I found online, doing a quick search of "example blogs" gave me insight into what's new in website design and how to create a website page with good readability.

This was a good exercise but I quickly came to understand that I cannot draw a layout without knowing the content, or rather it would be easier to choose a layout with some content.

Therefore, I started writing my first draft of the written content that will go in my page; this gave me a much clearer path as to what to do next.



## Building

I started by practicing what I had learnt, and referencing the videos, blogs, and forums I collected in the planning stage. The first part of the build was barely functional, had very basic shapes using divs and experimenting with flexbox, aligning items, borders, colours etc. 

Once I had a good understanding of how html and CSS work together, I started structuring my page, roughly following my designs on paper but still experimenting with different layouts.

After a few days I created my first draft for the Hobby Page which included a Header with some Nav containers, a main image with some welcome text overlayed, a title heading, some paragraphs from my initial content draft document and a couple more images in between some of the paragraphs. Using what I had learnt in the planning stage, I understood that a website page consists of boxes within boxes within boxes, this helped me when I was trying to implement my designs. 

All of the code up until this point was split between two files, a index.html file and a main.css file. 

It was at this point I realised that the content that was going to go on this page executed various objectives from the other briefs/projects but didn't align with the Hobby Page brief. I went back and re-wrote the content for the page and started working on the second iteration of the Hobby Page. I kept much of the original code and saved the parts that I no longer needed for later use. It was here that split some of my CSS code into a HobbyPage.css and Main.css file; I did this because there was starting to be a lot of code on just one file and it became hard to find some sections when coding and iterating.

Before proceeding I decided that this would be a good time to learn Git (bash) and GitHub so that I could start posting my code online. Reading some of the next project's briefs I saw that the using Git and GitHub was part of the objectives, so getting some practice in early wouldn't hurt. The decision also partly came from the fact I got stuck with some code where the divs were not aligning down the centre and I was going to post a question on Stack Exchange (None of the other answers on Stack Exchange seem to work for me). Right before posting the question I wanted to test one last thing that ultimately fixed what was not working properly.

Once more, after a couple of days I finished the structure of my page and refined the look by following a colour theme that matched the images and style of the rest of the page. I added a footer and played around with some new bits of code I learnt along the way. 

The last part of the build was the polish stage. Once the second iteration was completed, I revisited the brief to see what still needed to be done. Here I polished the footer, added the links that would take users to an outside website page, created a date section above the header using DOM manipulation and JavaScript (took half a day to learn what DOM was) and added clickable images.


## Debugging

As a brief summary, debugging mostly consisted of finding a problem, googling the problem, finding out that the online solutions didn't work for me, re-visiting the code, finding the one line of code that was interfering with the rest and lastly implementing the fix.

Stack Exchange became my best friend when it comes to debugging but while many solutions didn't exactly fix my problems, they gave me an understanding of how features in html work and pointed me in the right direction. For example, I was getting a gap on the right-hand side after adding a floated div, I quickly learned that floats were not created for divs in the first place but were soon adopted when people found out that they could clear the float on any elements above or below the floated one.

There were a fair few times where I just needed to go back and forth, trying to figure out what was interfering or causing the issues I was having. I didn't find that I had to use the console much yet or any form of debug.logs or breakpoints, it was just a matter of understanding what the problem is and testing until it worked.



# SILENCE 

The objective of this website is to attract potential customers into downloading the Silence meditation app via this well put together website. I give snippets of freely available information via the How to Meditate page and answer some of the more obvious queries in my questions page. I have also provided recommendations on the index.html from esteemed teachers in the field.

![Image of Monk](assets/images/monk2.png)

## UX

As stated previously, the goal of the website is to convince the customer to download the the Silence application. I believe an application to be the superior product for a meditation type product. That doesn't mean you should skimp out on the website, a good first impression is key. Below, I have several different types of customers who require answers and ill explain how this website achieves its goal in answering their questions.

Curious user:They would ask "why use this application over any other?". For the most part, this is answered in the index.html. I've offered the user by offering a free trial which they can see clearly straight away in the header. Not only that, just below I give 3 presentable statements with some context in what I called the "entice section. This is further reinforced in the "why use silence" section that gives a brief reasoning why you should use this app over any other. They might still not convinced, so I have one last ditch effort where I have presented 3 quotes from established meditators giving a brief description of who they are and I've added clickable links on their name and icons to an external website explaining who they are.

Semi on board user: At this point, the user might think "ok im not up for downloading the app just yet but I want to learn some basic tips". Their needs can be satisfied in the "howtomediate.html" page. I divided the content in a 3 step process presenting great imagery with matching colours in the container. The goal here is they take away this information themselves, like the results they're seeing and download the app with the free trial, eventually they should (hopefully) become full time customers.

skeptical user: The user just isn't convinced at all to download the app or take in the meditation instructions but is at least open minded enough to check the Q&A. This should (hopefully) let them question their doubts over the whole idea and download the application.

Convinced user: They like what they see and want the app. They need only to press the free trial button and a form will pop up where they must present their information. They need only click commence free trial.

## FEATURES

 ##### -For all Pages:

Navbar- styled the same as the header for a smooth look. Will allow you the user to go to the homepage, go to the other pages on the site, a clickable icon that brings you to the main content of the page and most importantly, a free trial button.

a title with a small amount of text to provide context for the overall page you're on. also has a free trial button and an attractive, accompanying image in the next col.

Footer- Contains terma and conditions, privacy policy as well as icons for our various social media pages. Lastly, we have buttons to download the app directly for iPhone and android.

##### -index.html:

Entice section:Provides the user short snippets of what meditation can do, where you can get help from others and from us on how to do it.

why use silence section: Again, more reasoning as to why use our app/website and and has an additional free trial button.

Quotes: Quotes from industry experts on how great the app is with links on their profiles for the curious.

##### -howtomeditate.html:

steps: 3 different rows presenting visually pleasing colours and images. There is a row for each step involved.

##### -questions.html:

q&a: questions are presented neatly in this page and the answers are hidden behind an accordion to prevent visual clutter on the page.



To help me plan out these different pages and features, I present 3 wireframes I made beforehand to give me a structural idea as to how I wanted the pages to be designed.

[Index](https://wireframe.cc/pro/pp/4b09977a1319776)
[Questions](https://wireframe.cc/lv90Bh)
[How to Meditate](https://wireframepro.mockflow.com/editor.jsp?editor=on&bgcolor=white&perm=Create&ptitle=silence&category=bootstrap4&projectid=Mdd152ebd34bd1c66bbf684533b4891541587576761474&publicid=7c25f576ee27457ea932b86fdfb31d7a#/page/d20cc7e320894f6b8cf9183729f00edc)


## FEATURES LEFT TO IMPLEMENT

Smooth transition upon pressing the anchor arrow: Upon research it required JS which is beyond the scope of this lesson.The idea was to make it have a scrolling animation.

changing icons in q&a:I wanted the blue gate icons to instead be a plus icon, upon clicking it, it'd smoothly transition into a minus. Again, something of this technicality was beyond what I've learned so far. Javascript was probably needed to make this feature functional.

I had also wanted to make privacy policy plus a terms and conditions page but I had ran out of time to do so. I don't think there would be any technical difficulties doing so.

Lastly, I wanted to add more functionality to the forms, but I only went as far as the demonstrations went on code institute.

*Post Project Submission Note:* For my own curiosity I went back and decided to finish some of these features. Their is now a smooth transition with the anchor arrow and the icons will change thanks so some JS I added. I have demonstrated form functionality in later
projects so I didn't think it was necessary here and the additional pages I saw as a matter of not having enough time/wasnt required to submit, it was never a question of weather I was competent enough to do it at the time.

 ## TECHNOLOGIES USED

 [bootstrap:](https://getbootstrap.com/) convenient grid system for laying out my webpage plus many other functionalities, such as a Collapsible  navbar and a accordion.

[fontawesome:](https://fontawesome.com/) Most of my text was imported from here and I frequently made use of their icons.

[Hover.css:](https://ianlunn.github.io/Hover/) Used to make my buttons and anchor arrow more attractive upon hovering over them. 

html 5: The bare bones of my entire website

css: For styling to make the website more attractive and fluid.

## TESTING

##### Scenario 1:Curious User-

1. Scroll through index.html top to bottom
2. Click links on quotes
3. click anchor arrow in nav
4. Test these actions on all view widths

Result: All the above actions work as intended.

##### Scenario 2:Semi on board user-

1. Click on how to meditate in the navigation
2. Scroll or use anchor arrow to get to steps on how to meditate
3. Test to see appropriate responsiveness in different view widths

Result: All the above actions work as intended.

##### Scenario 3:Skeptical user-

1. Click on questions in the navigation
2. scroll or use anchor arrow to the questions section
3. Click on each accordion to see if it reveals the hidden content
4. Test these actions on all view widths

Result: All the above actions work as intended. However sometimes the monk image wont load in the header of questions.html. It is far less consistent in loading than the rest of the images. Currently haven't found a fix besides constantly reloading the page and having luck. I removed and added the image again just before submitting this project and that may have fixed the issue.

##### Scenario 4:Convinced User-

1. Press any free trial button
2. Submit a form with an invalid email address and see if you get an error message.
3. Check every button to see if it opens up the form.

Result: All above actions works as intended.


All the above tests were conducted on Opera, Mozilla Firefox and Google Chrome. I coded this project on Chrome so everything is perfect on that browser. Opera seems to work as I intended too.The only problem I ran between browsers is that Firefox didn't use my imported fonts from font awesome. Luckily, I had an alternate font of sans-serif in places where Lato didn't load so there was no major issues I had while running Firefox.

## DEPLOYMENT

This website was developed entirely on gitpod.io. Simply, I added the files to the staging area, committed them and finally pushed them to github. Early on in my project I didn't commit nearly as much as I should have but made it a habit by the end. My initial commit consisted of a mostly finished index.html, my second commit included the additional 2 pages of howtomeditate.html and questions.html. Every commit after that only had minor modifications added onto it.

Below is a Deployed URL to my website. 

https://conor52.github.io/Conor-McCarthy-Milestone-1-Project/


 ## CREDITS

##### Content-

 I borrowed some of the basic code for the footer and quotes from two codeinstitute projects but added a lot of styling and tweaking on top of it. The Modal and accordion came directly from the Bootstrap website where I added my own styling and tweaks to it.

 ##### Credits to Media-

[three steps images:](https://pixabay.com/)
[cartoon monks:](https://pngtree.com/)

##### Acknowledgements-

 I would like to thank the makers of both wakingup.com and headspace.com for inspiration for making this website. I didn't copy any code from there but I mimicked some of their design philosophy.

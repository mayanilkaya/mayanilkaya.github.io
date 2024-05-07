Final Project Documentation

I started with Rachel's website as an example. I changed the title
to my name. Trying to figure out how to customize the stylesheet. I changed the background color,
and then realized its not in the correct file path.

Ok I realized I saved my stylesheet under the name stylesheet.css but what I had
on the code was style.css. I fixed it, now it works.

I'm adding contact information under my name. The font is too big for this, so I'm going to change it.
When I change the number next to px for font size, the size doesn't change but the place of the text does.

I was trying to change the font under p, where I should've done it for every header. Fixed that issue.

Wanted to change the size of the title, I had a typo so it wasn't working. also fixed that.

Now I want to have a menu on the homepage. I'm looking at an HTML tutorial website : w3schools.com

I'm trying to get tips from the resources I had linked before, but I realized I wanted something more simple.
I found a template for creating a navigation top bar on w3schools.com

<div class="topnav">
  <a class="active" href="#home">Home</a>
  <a href="#about">about</a>
  <a href="#listen">listen</a>
  <a href="#watch">watch</a>
</div>

I'm using this template for the menu.

I went to the last link I had for my resource because I like the design of the webpage.
I realized they have a layout for every menu item. I'm guessing I have to make a layout for 'about', 'listen', and 'watch'.
I went to her home page and viewed source to see how she put it all together.

I found the code for her menu and replaced some of it with what I wanted.

I changed the previous template for this one.
<body class="transition-enabled">  <div class='page-background-video page-background-video-with-panel'>
</div>
<div class="js-responsive-nav">
<div class="responsive-nav has-social">
<div class="close-responsive-click-area js-close-responsive-nav">
<div class="close-responsive-button"></div>
</div>
  <nav class="nav-container js-editable-target editable">
        <div class="gallery-title"><a href="/home" >home</a></div>
        <div class="gallery-title"><a href="/about" >about</a></div>
        <div class="gallery-title"><a href="/listen" >listen</a></div>
        <div class="gallery-title"><a href="/watch" >watch</a></div
<div class="page-title">


It looked too complicated. Rachel's way of doing it looks much simpler so I'm going to analyze that and do it that way.
I found this website https://www.shecodes.io/athena/3644-creating-a-dynamic-navigation-bar-with-html-css-javascript#:~:text=In%20HTML%2C%20you%20will%20need,in%20a%20tag.&text=In%20CSS%2C%20you%20will%20need,lay%20out%20the%20navigation%20items.

I read and understood on that website, that I had to incorporate the menu in the stylesheet so it would look how I wanted it to look like.

I think putting it in the stylesheet and adding the nav ul turned the menu items into hyperlinks.
Now I have to make those links into actual pages.

First I want to make sure my home page looks exactly how I want it. I'm going to center my contact info.

Ok now I'm ready to move on.

Starting to work on the about page.

I wanted to link the about page to the menu item: <a href="">about</a>
but I guess I have to have an actual webpage to do that. So I'm creating a new html file that is going to be
the about page. And then I can link it.

so everything in the beginning is kind of the same, I have to have the same few lines of code.
For the hyperlink, about is going to switch to active. OH and for home page I have to switch it to active for the default.

I can make a different style sheet for all of these links. Will do it.

I made a new html file for about but I can't open it on Google chrome. I'm looking in my finder and see that I have created
two files: portfolio website/about.html and about.HTML
the about.html is empty, but the other one is working. For now it is the same as my home page.

I made about active on the page.

Now I'm gonna work on the about page.

First I want to put a photo of myself. I copy paste the image's code
<img src=maya.JPG>

It's not showing up yet. I tried putting the image also in the folder that contains
these html files. And yesss that worked. Ok now the image takes up the whole space.
I have to make it smaller.

Copying and pasting Rachel's code for her image in her stylesheet. (in to my stylesheet)

Ok I just wanted to see if that's how I'm gping to play around with its dimensions, and yes that is correct.
So now I'll actually figure out how to put it where I want it on the screen.I want to make iot smaller and put it toards the left, write a bio next to it.

Also I want an image for my home screen now, its so boring without it. Maybe a scan of one of my paintings? Or a graphic score?

I added a visual to my homepage but its not showing up for some reason. It says your file may have been moved, edited, or deleted. I had it before??? I'll get back to it later.
I want to make 'home' a different color on the home page to show that you're there, and same for the others.
 I also had trouble with that, and I'll get back to it later.

 Working on 'about':

 I'm going to put my CV, and short bio here. For now, my bio is going to be 'text'.

I tried adding my CV using
  <h4>My CV</h4>
  <iframe src="CV_mayanilkaya 2024_ Feb18.docx.pdf" width="100%"
height+"500px">
    </iframe>
  </body>
</html>

and it worked. I found the code on this website: https://pdf.wondershare.com/how-to/embed-pdf-in-html.html#:~:text=the%20data%20attribute.-,Embed%20PDF%20in%20HTML%20Using%20the%20Tag,file%20that%20will%20be%20embedded.
I also put the pdf of the CV in the folder for the website to set the correct path.
I need to adjust the height and width bc it is too short. oh haha i realized i didnt set the height correctly.
idth="50%"
height= "500px"> this looks good.

next thing I want to do is to place everything where I want it. I want the image to be on the left, my bio
next to it on the right.
and my cv below all of that.

will do this all in the stylesheet:
I added this for header 4 which is 'my cv' but nothing changed.
  background-color: Cyan;
  color: White;
  font-family: Arial;
  font-size: 14px

  I discovered that no matter what I change in the stylesheet, nothing happens. I must've done something wrong but I can't tell what yet.

  OOOOOH I see. the stylesheet that I put in the about page is for the home page.
  yeees haha that fixed it.

  I centered the cv title. I want to have the image and bio next to each other but I can't really work with 20thatbc my image is not showing.

Going on, next steps will be adding videos, portfolio etc.

I make a new file called website/listen.HTML
Also a stylesheet too. Copy paste what I have for the home page so I have a starting point.

Going to gather all of the stuff I want to put there first.

To add a video I did the same thing with adding an image. but then i saw rachel did it with iframe so
i'm going to try doing it a few other ways bc it didn't show up. Also why is none of my visuals showing???!!!
I think it's because I renamed a few times and maybe broke the file path by doing so.


So I read here: https://4ddig.tenorshare.com/photo-error/images-not-showing-on-website.html#:~:text=The%20reason%20why%20images%20are%20not%20showing%20up%20in%20HTML,the%20image%20to%20not%20show.
sometimes the browser might cause the image to not show. I cop pasted the link in Safari and it worked. I was using Chrome before.

Clearing cache and cookies on Chrome and restarting to see if it's going to fix the issue.
Nope.
I'm  switching to Safari.

I fixed the home page, I have my visual. Now I will do the same for about. I basically deleted
re-uploaded it.

yay it worked. now i want to align the image to the right ad text to the left. I pushed the photo to the right by making margin right 40 px.

I did this
<style>
.container {
  display: flex;
  align-items: center;
  justify-content: center;
}

img {
  max-width: 25%;
  max-height: 15%;
  float: left;
}
</style>
<body>
  <div class="container">
    <div class="image">
      <img src="about.JPG">
    </div>
    <div class="text">
      <h4>text insert bio.</h4>
    </div>
  </div>
<p>

This is one of the ways I found to put text and image next to each other, with the div tag.
I feel like this belongs in the css file tho.

I want to center the pdf but I couldn't. I tried a few ways
the last thing I tried was
iframe {
  text-align: center;
}
thought I could act as if its a text but it doesn't work.

Next step is to work on the listen page.
I added one of the videos I wanted to put up, as I was adding a photo but there
was no way of pausing the video that way. So I'll do more research.


Meeting with Rachel:
delete personal info
center pdf through css
make image a smaller file bc maybe its too big and its not showing on the browser.

all of my html files were saved in my itp folder, and that's not the correct place to host it on the web. so
we had to move them to mayanilkaya.github.io

I'm confused to how I'm supposed to save the listen/about pages if they're all supposed to be savce as "iondex.html"
I can see (by looking at Rachel's code) I I'm going to make them hyperlinks under the topnav category.

I start by trying to solve the image problem/ its not shwoing on chrome but its showing on safari.
I go to developer toulse and click on console to see what thbe problem is. so there is no image in the folder that's supposed to be.
 it says "fail to load resource: net:: ERR_FILE_NOT_FOUND home.JPG:!"

 reading stackoverflow entries about this, and they're saying that either payh is wrong or file isn't present where I want it to be.

there was a slash before home.JPG, I deleted that and the error went away on the console but the image is still not showing.

i'm going to try reducing the size of the image by compressing it. YAY! It worked>>>
So I wanted to reduce the size of the image. to do this, i open it with preview. go to tools and click adjust size. it haid 72 pxl originally, and i reduced it to 60.
when i was trying to save it, however it would say that i don't have permission to edit/save. i had airdropped this photo from my phone to my downloads folder. i assumed
maybe if i downloaded it to 'photos', something would change. i deleted that image, and airdropped the same one from my iphone to my photos folder this time.
i exported it to my desktop, named it homepage.jpeg. reduced its size to 60, and saved. (i could save it, it worked)
and then i moved the image to the folder mayanilkaya.github.io (because that's where this html is being hosted). right clicked on
the image, copied it. pasted it in the index file where i had < img src= "..."> . saved the file. refreshed the page, and it showed!!!

2. thing rachel told me to do was to edit my CV and get rid of personal info such as address etc.

i edited my CV and took personal info out.

i added very short info about myself on the about page. the image isnt showing on chrome but showing on safari. trying the same fix i did before.

works! looks different on chrome and safari though, interesting. now i'm working on aligning text and image.

home and about pages are done. i want to center align cv later.

moving on to listen:
here i will put video recordings of me performing. for the sake of the deadline,
i will only put a few. i will add more and edit later.

i realized i only needed one css file while i did a stylesheet for every page.

i put a google drive link and a pdf to fragments.

moving on to watch.

for some reason i can't change the color of the text that i hyperlink to videos etc.

will let that stay unresolved.

I hadn't figured out how to hyperlik the pages together until now. i just copy past the githun.io links to create hyperlihnks.
i will move it to another host later.

I can go to the other links from home page except for watch. oh its bc i changed the name.
fixed it.

i can't figure out how to host it.

All of my references:

Wendy Eisenberg's website: view-source:https://www.wendyeisenberg.com/

Rachel's website: view-source:https://racheldevorah.studio/about/

for HTML help on fonts/colors: https://www.w3schools.com/html/html_colors.asp

 https://4ddig.tenorshare.com/photo-error/images-not-showing-on-website.html#:~:text=The%20reason%20why%20images%20are%20not%20showing%20up%20in%20HTML,the%20image%20to%20not%20show

wwww.w3schools.com

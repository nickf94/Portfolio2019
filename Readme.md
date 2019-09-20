Portfoilio Assessment 2019

https://github.com/nickf94/Portfolio2019 <---- Git Hub Repo

https://nickf94.github.io/Portfolio2019/Home.html <---- Github Pages URL

All Photos were taken by me (Nick Fletcher) background photo was used from Pexels.com

How I came up with my idea to design my portfolio like I have came down to just wanting something that was different but unique, something that would stand out from anyone else. Since I love to take photos i decided that my target audience for this website portfolio would be people who like photography just as i do.

Design Process

When i first started thinking about what i wanted to do for my portfolio I had already built a simple webpage template from listening to tutorials about html and css, so when it came to learning that we had to do a portfolio for our next assessment i just had to take what i already had and then add more things as we learnt more about html and css.

I changed my mind about what i wanted it to look like a few times during the design process but the main factor of what i wanted it to do kept consistent. I wanted a front page that welcomed the user and get them to click a button so that the screen would scroll down and the navbar would appear. Something i haven't seen a lot of websites do, which made me jump straight onto that idea cause i thought it'd look neat.

I first started with my navbar up the top and have it glow but as i went on i found myself not liking that idea so i scrapped it for just plain text but still have it so that when you hovered your mouse over the link it would light up. Next i started to add my pages, I decided to use my portfolio to show off my photography skills as well as the skills i had learnt from the html and css lessons. I ran into problems with the images being too big for a mobile phone so i went with a grid to make them all fit onto a mobile screen.

![Github Logo] (/Docs/IMG_1007.jpg) <--- Background image
![Github Logo] (/Docs/gridformyphotos-screenshot.png)

After the portfolio page i decided to create an "About me" page which later turned into "My Story", here i wrote down a few things about myself and how i came into becoming a beginner full-stack web developer. I then ran into a wall. I found out that we needed at least four pages and i was stumped for ideas, I didn't know what to add, But then i thought of adding a contact page and set off to find out what type of contact form i could make. I found a form template that was just a basic one so simple enough for me to work on but not too basic as it has a transparent background which i found out override my current background which was annoying. So i just had to put my background in my body instead. Problem solved!


![Github Logo] (/Docs/contactformcss-screenshot.png)

Next came the Blog page, which I just added some links to some of my written blogs i had made over the past few weeks.
But then i found out that we had to make a sperate page for each blog post! (NO... PLEASE GOD NO...) I thought i was finished and could just concentrate on my documentation but alas i was foiled and had to go back to my blog page and make a blog page with all of my blogs from medium. 


![Github Logo] (/Docs/website-layout.jpg) <---- Website map

Problems

Some problems i had with my portfolio were:

: The headings weren't aligning properly
: The navbar was being stupid
: My color scheme wasn't matching

After the "My Story" page i made a contact page and then a contact form. I decided to go with one that was kind of transparent so that you could still see the background but also responsive at the same time, so i went exploring the world wide web for ways to do a contact form and make it responsive.

![Github Logo] (/docs/contactform-screenshot.png)

With my navbar I needed to make it more responsive so i went with a navbar that changes to a hamburger style button when on a mobile device, it was pretty cool but then i decided to change it up a bit so i made some changes but ran into trouble where it was spaced weird on mobile devices. I found out that i needed to add some of the things i changed back into the code and it started working. 

Then i found out that the scroll button wasn't working the way i wanted it to work on desktop but on mobile it was which started to become really annoying. I started off by having the button scroll to a certain point on my window but whenever i changed from mobile to desktop it stopped working so i asked the teacher and he said that i should be using a queryselector in javascript and get it to target my nav class and set it to scroll down to the offset of the top of the navbar.

![Github Logo] (/Docs/navbar-screenshot.png)
![Github Logo] (/Docs/navbar-responsive.png)
![Github Logo] (/Docs/navbarcss-screenshot.png)
![Github Logo] (/Docs/web-accessibilty-screenshot.png)

When i was finished with the layout of my website I decided to add something that would make it scroll down to a particular point of the page. I found that i could add a button to display my welcome message which looked really cool but i found it wasn't enough of what i wanted. I kept looking and eventually found a way for it to "smooth scroll" to a point with some javascript. So i went with that, i implemented the javascript and made it so that when you clicked on the button it would scroll down to where my navbar was which made me quite happy to see it work how i planned. 

I did however run into an issue where if i moved the navbar down on the page it would mess up on mobile devices, i tried fixing it by going back to how it was originally but i wanted it off the screen on a desktop screen, but alas i couldn't have both without completely breaking it. So i gave up, but then I went to the teachers and they helped me out by implementing an element in the javascript which allowed the screen to scroll down to where the navbar was on both desktop and mobiles without having to change the position of the navbar called "query.selector" and then set it to scroll to the offset of the top of my navbar.

![Github Logo] (/Docs/buttonjavascript-screenshot.png)
![Github Logo] (/Docs/buttoncss-screenshot.png)

I made a footer with it saying that it was made by me and added some social buttons with links to some of my social accounts for people to look at. And that was it I was done my portfolio at last. Now it was time to add it to github pages via github which was a very annoying process. The first issue i was faced with was that none of my css files were working on github pages but whenever i looked locally they were all working fine, so i tried many things to get the css files to work which was very time consuming. I finally got them to work by redirecting my html and css files to my root folder and that finally got github to at least show some css. 

This is where i ran into my next problem. My css files weren't showing the background for my pages, which was an even more annoying problem. I had all my links right but for some reason they weren't showing up on my website. i must've spent all day on this problem, I even asked one of the teachers what he thought could've been the problem. We tried finding out what was going on, only for it being a simple file type error, which made me so mad, but finally it worked.

I was finally actually finished my project and free.

![Github Logo] (/Docs/freedom.gif)

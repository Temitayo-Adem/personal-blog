# personal-blog
In this project I have created a simple Blog Page. The application consists of a Home Page and a Blog Post page. I have used some simple HTML and CSS to give the application style and responsiveness. 

**Note:** I attempted to import the common.css into both styles.css and blogPost.css, but it did not work on htmlpreview.github.io (it works in my browser). As a result, I decided to link the common.css stylesheet to the head of both index.html and blogPost.html. (I also linked styles.css to the head of blogPost.html)

For the home page(index.html) I tried to give it a very simple early 2000s design. I used a container grid and grid-template-areas to structure the page. For the Navbar I wanted to section off three areas that would show the title of the page, a button to subscribe, and a link to the blogPost page. My idea for the main content was to nest a flexbox div that would contain 5 or 6 blog post previews that the user could click on to see the full article. I was able to utilize cards with overlay to make a preview of the blog post slide up when a mouse hovers over it. The first few "Read More" buttons link to the Blog Post page and the last few are just buttons. I also used different colors to represent different genres/types of posts (sports, programming, music). The footer contains a card that represents me and links to social media sites. I also put a link to return to the top of the page.

For the blogPost.html page I carried over a similar grid/navbar as the homepage but included a link ("About Me") to the bottom of the page where I placed a post that represents an introduction to the author. I carried over the social links footer from the homepage. I envisioned the blog as the type that keeps scrolling down like an old school tumblr or xanga.

In order to make the webpages a bit more mobile-friendly I utilized media queries. When the screen becomes sufficiently small ( less than 900px) some of the properties change/resize to make the page easier to read on a mobile phone or tablet.

**Possible Improvements**
I would like to gain a better understanding of how to size images. Some of the images I used seemed to not have the proper aspect ratio. I just tried to make the pictures fit into the template I envisioned without considering scaling. I also did not know how to properly size the icons of the social media sites. I could also improve upon my navbar to make it more user-friendly. Perhaps utilize a hamburger menu or add a search bar. 







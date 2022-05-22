# personal-blog
In this project I have created a simple Blog Page. The application consists of a Home Page and a Blog Post page. I have used some simple HTML and CSS to give the application style and responsiveness. 
The project contains three CSS files: styles.css, blogPost.css, and common.css. I attempted to import the common.css into both the styles and blogPost sheets and it worked in my browser, but when I tried it on htmlpreview.github.io the common styles did not render. As a result, I decided to link the common stylesheet to both the index.html file and the blogPost.html file.

For the home page(index.html) I tried to give it a very simple early 2000s design. I used a container grid and grid-template-areas to structure the page. For the Navbar I wanted to section off three areas that would show the title of the page, a button to subscribe, and a link to the blogPost page. My idea for the main content was to nest a flexbox div that would contain 5 or 6 blog post previews that the user could click on to see the full article. I was able to utilize cards with overlay to make the blog post preview slide up when a mouse hovers over it. The first few "Read More" buttons link to the Blog Post page and the last few are just buttons. I also used different colors to represent different genres/types of posts (sports, programming, music). The footer contains a card that represents me and links to social media sites. I also put a link to return to the top of the page.

For the blogPost.html page I carried over a similar grid/navbar as the homepage but included a link ("About Me") to the bottom of the page where I placed a post that represents an introduction to the author. I carried over the social links footer from the homepage.





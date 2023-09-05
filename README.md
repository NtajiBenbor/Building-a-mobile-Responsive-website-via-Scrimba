# A Mobile Responsive Blog Site 

## Content :link:

1. [Project Overview](#1-project-overview-😄)
2. [Screenshots](#2-screenshots-📷)
3. [Why I built this](#3-why-i-built-this-❓)
4. [what I learned building this project.](#4-what-i-learned-while-building-this-project)
5. [Challenges](#5-challenges-😓)
6. [Tools and resources utilized](#6-tools-and-resources-utilized-🔧)
7. [Author](#7-author-🖊️)


## 1. Project Overview :smile:
This project is a simple blog titled "living the simple life". it is comprised of three page. The Homepage; this is the landing page of the blog, an About Me; where information about the author of the blog can be found, and finally a Recent Post page; where the recent post and articles can be found.

***
Check it out [Here](https://bensblogspot.netlify.app/)

## 2. Screenshots :camera:

### Screenshot 1
![home page](/img/Blog-%20homepage.png)
*A screenshot of the blog's Homepage*

### Screenshot 2
![home page](/img/Blog-about-me%20Page.png)
*A screenshot of the blog's About Me Page*

### Screenshot 3
![home page](/img/Blog-%20Recent-Post%20Page.png)
*A screenshot of the blog's Recent post Page*

### Screenshot 4
![home page](/img/Blog-mobile.png)

*A screenshot of the blog on a mobile device*

## 3. Why I built this :hammer:
The primary objective of this project was to acquire the skills necessary to create a fully responsive layout. It marked my initial endeavour in designing a layout that seamlessly adapts to various mobile devices. This project was completed through a guided coding experience provided by(https://www.scrimba.com/)

## 4. what I learned building this project.
- How to create fully responsive website by using **Media Queries** and Flexbox.
- How to use **Media Queries** to to change the design  of a webpage based on different screen size and devices type.


## 5. Challenges :sweat:
During the process of building this project, I didn't encounter any major setbacks. However, I did face a few challenges and learned valuable lessons:

1. **Adopting Mobile-First Design:** Initially, embracing the mobile-first design approach posed a challenge. However, I quickly adapted to it. This methodology, starting with the smallest screen sizes and progressively enhancing the design for larger devices, is a great way to ensure responsiveness.

2. **Understanding `Max-width` and `Min-width` Properties:** I had some difficulty grasping the concept of how the `max-width` and `min-width` properties function within media queries.

   - `Max-width`: This property ensures that an element's width does not exceed the specified value. It essentially allows the element to have a width ranging from zero up to the specified value but not exceeding it. example:

   ```css
   @media screen and (max-width: 619px) {
     .main {
       width: 90%;
       margin: 0 auto; /* for screens not larger than 619px, apply these style rules */
     }
   }
   ```

   - `Min-width`: This property specifies that an element will not have a width smaller than the specified value but can expand beyond it. It ensures that the element does not shrink beyond a certain point, which is the specified width. example:

   ```css
   @media screen and (min-width: 619px) {
     .main {
       width: 90%;
       margin: 0 auto; /* for screens larger than 619px, apply these style rules */
     }
   }
   ```
## 6. Tools and Resources utilized :wrench:
The following tools and resources where utilized in building this project.
- HTML5
- CSS3
- Images from [pexels.com](https://www.pexels.com) :link:
- Resources from [scrimba.com](https://www.scrimba.com) :link:

## Author :pen:
Hi I'm Benedict, I'm learning to become a frontend developer. check out my blog where I'll be sharing my learning experiences, projects, and tips. 
- Checkout it [here](https://www.benneythedev.hashnode.dev/) :link: 

You can also connect with me on twitter
- [Follow me](https://www.twitter.com/CodewithNtaji) :link: 




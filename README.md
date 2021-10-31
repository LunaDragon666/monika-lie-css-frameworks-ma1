# CSS Frameworks
For this assignment I have chosen to work with CDN version of Bootstrap to code the supplied design into a responsive design that supports from around 375px screen size and upwards. The goal for the task was to practice creating a specific page layout we were commissioned to do, based on the XD prototype attached in this assignment, using Bootstrap and Sass. I tried to create as similar to the design as possible.
## Module assignment 1 
I used the container to create equal spacing for both the footer and the navigation bar. Unfortunately, I do not feel I got myself enough immersion in lesson 1.3, which might have helped me to solve the issues I met during costumizing the bootstrap navbar?  
### Navbar
Basically I used CDN version of Bootstrap mostly to get a pre-built component of this navbar from the library to quickly create navigation bar layout, and from there costumize it - instead of hard-coding the nav bar (which has been a time saver for me). The rest of the elements on this page is coded from scratch. The `!important` tags that follows to override the desired previous styling rules that followed to this nav, although I tried to avoid using it when possible and based on the current abilities I have to do so.
### Main
In the main content of this page, which is in this case `gridbox__container`, I used CSS Grid instead of flexbox(es) to layout a group of square «boxes» inside the grid-layout from homepage due to its built-in facilitation to potentially create dynamic- and flexible layouts regardless of device sizes - which also makes it easier for me to keep track on them when costumizing them in both CSS and SASS. Since I did not find nor wanted to use a pre-built component that have similar layout that were added to create the «group of square-shaped boxes» from there (if it already exists), I chose to make my own where I also tried to use BEM inside them. 
### Footer
I have deliberately excluded the footer from the "wrapper" to make it remain at the bottom of the page.
#### Reflection note 
The most challenging aspect I found within this task was to find and make as "logical" Bootstrap and Sass classes as possible, in addition to BEM-classes + give the sass-files correct names in come cases and correct setup to them. 

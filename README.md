# The-Horiseon-Improved

# Summary 
In this project, I worked with starter code that needed to be improved or fixed, also known as 'refactoring'. Before actually starting to clean up the code, I addded some comments in the HTML, as well as in the CSS, in order to create sections that went with each part of the website to make the code a bit more organized, as well as easier to read when I was working with it.  The end result was this: https://mendixta.github.io/The-Horiseon-Improved/

# Making it Cleaner 
The following changes were made to the code in order to make it presentable, easier to work with and read:

* Comments were added in the HTML before starting to clean it up, this was done so the code was easier to read when it came to fixing a certain part of the website. For example, if I wanted to go in and fix something in the navigation section, the comment that I would look for would say something like "The following code is for the Navigation links at the top of the page". This was done in the CSS as well so I knew what part of the CSS affected what part of the HTML. This stategy made it easier for each part of the code to be identified so it can be worked with. 

* At the top of the page, the HTML didnt have a proper title, this was originally < title > website < /title >, which was then changed to < title > The Horiseon Improved < /title >

* One of the navigation links, (the seach engine optimization link) in the header was fixed so when it was clicked on, it would take the viewer to the correct section of the website. Before correcting the link in the HTML, it would not do anything, but the other links worked perfectly fine. 

* Most of the divs that were in the html were changed to the appropriate semantic HTML elements in order organize everything by section, some semantic extra elements were added as well: 
    *  < div class= "header" > was changed to < nav class="header" >, and to close the section, < /nav > was added and changed from < /div >.

    *   < div class='hero' > was changed to < img class= 'hero' >, so I would know that I was working with the picture of a meeting shown at the top of the website. 

    * < section > tags were added and replaced from < div > in order to organize the code as well as separate each 'div=id' that contained an image, as well as a paragraph. 

    *  alt attributes were added to the images for accessibility. This was done with all 6 images in the HTML. 

    * < div class= "benefits" > was changed to < aside class= "benefits" >, as well as: < div class="benefit-lead" > was changed to < aside class="lead-generation"> and closed with < /aside > , along with the two other div= classes that were changed to, < aside class= 'brand-awareness' > and < aside class= 'cost-management'> and closed with < /aside >. What was in quotation marks was changed so that it would match the titles that were on the website so it can be easily identified. The CSS selector names were changed to match the HTML.
        * The < aside > tags were used to sepaparate each section in the margin. 

* In the CSS, the selector names were changed for the footer, from 'footer' to 'copyright'. 
    * In the HTML, < div class="footer" > , was changed to < footer class= "Copyright" >.

# Screenshot / The Final Product
[](The-Horiseon-Improved.png)

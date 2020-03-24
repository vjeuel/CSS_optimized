# Homework-1

This homework assigment is to teach us how to make a website accessible to people with disabilities and also to optmize for search engine.

I will be logging every change made on the HTML and CSS files and also at the end listing the Future Changes that I find important to make easy to be viewed in different screen sizes and formats.


* Created this github repository to upload all my files on the daily basis, so I can have different versions of it, in case I need to go back and see what I have changed from previous versions or why my html or css isn't working now when it was working on the previous version.

* Have my web address linked to this repository: https://vjeuel.github.io/Homework-1/ .

* Substituted many < div > tag for tag like figure, main, header, section, footer, small and a few others and assigned them in the CSS file respectively.

* Will be adding alt attributes to all the pictures to help people with disability to understand what is showing on the pictures and also in case the website doesn't render the picture the person will be able to at least understand what was been shown in the picture.

* Added id="search-engine-optimization" to line 34.

* Added a CSS reset.css file to assets/css folder and linked to index.html and made sure to add before the style.css link.

* Certain lines like < p > was using 3 lines and I resumed all to 1 line, making the HTML file a bit more concise.

* In style.css added a html tag and added font-size: 10px so I could convert all px to rem unit.

* Resized the h1, h2, h3, a and p tags.

* In the style.css eliminated unnecessary classes, since they were all alike, so I created a .benefit-box, .benefit-box h3 and .benefit-box img, and was able to delete several unnecessary extra lines of code.

* On now footer tag, I changed the color and font-size of the h2 and small tag to black and 2rem, since I had used white and 4.5rem.

* In the index.html, inside the < link > added type="text/css" (not sure if this was necessary).

* In the style.css I moved up .content-box, .content-box img and .content-box h2, so they all stay under 
the */ ARTICLES CONNECTED TO NAV LINK */ area. 

* Added letter-spacing to a, p, h2 and h3.

* Moved the font-family form where they were to the h1, h2, h3, a and p tags.

* Changed the h2 and h3 tags to font-family: 'Trebuchet MS', 'Lucida Sans Unicode', 'Lucida Grande', 'Lucida Sans', Arial, sans-serif;.

* For the a and p tags, changed to font-weight: 100;.

* Increased the font-weight to 700 for the h2 and h3 tags.

* Increased the margin-left and margin-right to 30px (3rem) in the .float-left and float-right class.

* Increased the botton margin in the benefit-box, so there is more spacing between the 3 boxes.

* In the benefit-box, decided to put the icon before the title.

* Inverted the color of the img inside the benefit-box using filter: invert(1);.

* Increased to 2rem the margin-bottom of the h3 inside the benefit-box.

* After pondering and reading a lot, decided to get rid of the < ul > and just stick to the < a > tag in the nav bar.

* In the #main-picture, changed the height to 100vh.

* Since I have read about and learned a bit of flexbox and grid I decided to try to make the website responsive, I had plans to leave that for a future feature, but I figured I would go ahead and try to do it now.

* I think I will try grid for this site.

* GRID
  - Added grid to main tag and 2rem gap between each grid and am fairly surprised on how easy it was.
  - Did the same thing with the benefit-box.

* As far as I understood Media Queries is part of making a page responsive, so I am also going to create 3 media queries, for screen size of 576px, 768px and 992px and anything above 992px won't need any changes.
  - This was not as easy as doing grid at first, but I think it looks good.

*** Future Changes ***
* Wanted to make responsive as Future Changes but ended up doing it already.



*** Credits ***

https://dev.to/kenbellows/stop-using-so-many-divs-an-intro-to-semantic-html-3i9i <br>
https://developer.mozilla.org/en-US/ <br>
https://www.w3schools.com/ <br>
https://www.freecodecamp.org/news/an-animated-guide-to-flexbox-d280cf6afc35/ <br>
https://flexboxfroggy.com/ <br>
https://codepip.com/games/grid-garden/ <br>
https://css-tricks.com/snippets/css/complete-guide-grid/ <br>
https://css-tricks.com/snippets/css/a-guide-to-flexbox/ <br>



/ask How do I add a alt attribute to an image on css?

Here is my code in HTML:
<div class="image">
  <img src="" alt="">
</div>

CSS:
.image {
    height: 800px;
    width: 100%;
    margin-bottom: 25px;
    background-image: url("#");
    background-size: cover;
    background-position: center;
}

The question is? Do I need the <img> tag at all? If yes, and I add the alt="Description of a picture", it shows in the page on top of the CSS picture.

If no, where to I write the description of the picture?

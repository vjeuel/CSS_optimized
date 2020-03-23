# Homework-1

This homework assigment is to teach us how to make a website accessible to people with disabilities and also to optmize for search engine.

* Created this github repository to upload all my files on the daily basis, so I can have different versions of it, in case I need to go back and see what I have changed from previous versions or why my html or css isn't working now when it was working on the previous version.

* Substituted many <div> tag for tag like figure, main, header, section, footer, small and a few others and assigned them in the CSS file respectively.

* Will be adding alt attributes to all the pictures to help people with disability to understand what is showing on the pictures and also in case the website doesn't render the picture the person will be able to at least understand what was been shown in the picture.

* Added id="search-engine-optimization" to line 30.

* Added a CSS reset.css file to assets/css folder and linked to index.html and made sure to add before the style.css link.

* I prefer 3 spaces in my tab, so I change every line and identation to 3 spaces.

* Certain lines like <p> was using 3 lines and I resumed all to 1 line, making the HTML file a bit more concise.

* In style.css added a html tag and added font-size: 10px so I could convert all px to rem unit.

* Resized the h1, h2, h3 a and p tags.

* In the style.css eliminated unecessary classes, since they were all alike, so I cretaed a .benefit-box, .benefit-box h3 and .benefit-box img, and was able to delete several unecessary extra lines of code.

* On now footer tag, I changed the color and font-size of the h2 and small tag to black and 2rem, since I had used white and 4.5rem.

* In the index.html, inside the <link> added type="text/css" (not sure if this was necessary).

* In the style.css I moved up .content-box, .content-box img and .content-box h2, so they all stay under 
the */ ARTCILES CONNECTED TO NAV LINK */ area. 


*** Future Changes ***
* Optimize the whole website to be responsive, since it breaks in smaller screens.





/ask How do I add a alt attribute to an image on css?

Here is my code in HTML:
<div class="image">
  <img src="#" alt="">
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

The question is? Do I need the <img> tag at all? If yes, and I add the alt="Drescription of a picture", it shows in the page on top of the CSS picture.

If no, where to I write the drescription of the picture?

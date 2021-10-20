# UpdatedPortfolio-Amitabh_Ranjan

**User Story**

AS AN employer
------
I WANT : To view a potential employee's deployed portfolio of work  
         samples
------
SO THAT : I can review samples of their work and assess whether they're 
          a good candidate for an open position
------

**Goal**

To create a web application from scratch which satisfy the below given acceptance criteria.

**Acceptance Criteria**

The goal to create a web application from scratch will be met when :

*(1) When the employer load the portfolio, he is presented with the developer's name, links to sections about them, their work, and how to contact them.*
------
It's considered done<br>
------
WHEN : an index.html file is created.<br>
WHEN : a "header" element is created inside the body tag.<br>
WHEN : a "nav" tag is created inside "header" with a class & id 
       name.<br>
WHEN : a "div" with a class name is created inside the "nav" and 
       have a "h1" tag  inside it with the developer's name.
WHEN : another "div" is created inside "nav" with a class name.<br>
WHEN : 4 "li" are created inside this "div" with "a" tag for "About 
       Me", "Work", "Contact Me" & "Resume".<br>
WHEN : a style.css file is created.<br>
WHEN : this index.html is linked to the style.css file.<br>
WHEN : some style attributes are given to universal selector "*" and 
       body{}.
WHEN : some style properties are added in style.css for "nav" bar, 
       the two "div" and "li" mentioned above.

*(2) When the employer load the portfolio, he is presented with a background image and a unique subtitle.*
------
It's considered done<br>
------

WHEN : a "div class="background-image" is created inside "nav".<br>
WHEN : another "div class="subtitle"" is created inside the above 
       mentioned "div" and have "h2" tag for the subtitle.<br>
WHEN : some style attributes are given to the above mentioned "div" &  
       "h2" tags in style.css.<br>
WHEN : a background image is linked to "div class="background-image" in 
       style.css.

*(3) When the employer load the portfolio, he is presented with a developer's recent photo and something written about him/her.*
------
It's considered done<br>
------
WHEN : a "div" is created inside "main" element with class name 
       "content".<br>
WHEN : a "div" is created inside "div class='content'" with class name 
       "About-Me-Content".<br>
WHEN : a "div" is created inside "div class='content' with class name 
       "AboutMe-SubHeading.<br>
WHEN : "h2" tag is created inside "div class= AboutMe-SubHeading" for 
       heading "About Me".<br>
WHEN : "img" tag is created inside "div class="About-Me-Content" with 
       the link to developr's image.<br>
WHEN : something is written about the developer inside "p" tag.

*(4) When the employer load the portfolio, he is presented with the developer's work applications screen-shots.*
------
It's considered done<br>
------
WHEN : a "div class='Work-Content' id=Work'" is created inside "div 
       class='content'".<br>
WHEN : a "div class='Work-SubHeading'" is created inside "div 
       class='Work-Content' id=Work'".<br>
WHEN : "h2" tag is created inside "div class='Work-SubHeading'".<br>
WHEN : another "div class='Work1'" is created inside "div 
       class='Work-Content' id=Work'" just below "div class='Work-SubHeading'".<br>
WHEN : a "div class='work1-heading' is created inside "div 
       class='Work1'".<br>
WHEN : "h3" and "p" tags are created inside "div 
       class='work1-heading'<br>
WHEN : "img" tag is created inside "a" tag with link to image about 
       work1.<br>
WHEN : a "section class='Work-2_3'" is created inside "div 
       class='Work-Content' id=Work'" just below "div class='Work1'"<br>
WHEN : a "div class='Work2'" is created inside "section 
       class='work-2_3'".<br>
WHEN : a "div class='work2-heading'" is created inside "div 
       class='Work2'".<br>
WHEN : a "h3" & "p" tag are created inside "div class='work2-heading'".
       <br>
WHEN : "a" tag  with "img" tag inside it is created inside "div 
       class='Work2'".<br>
WHEN : a link to image for work2 is placed inside "img" tag.<br>

WHEN : a "div class='Work3'" is created inside "section 
       class='Work-2_3'".<br>
WHEN : a "div class="work3-heading" is created inside "div 
       class='Work3'".<br>
WHEN : a "h3" & "p" tag is created inside "div class="work3-heading".
       <br>
WHEN : "a" tag is created inside "div class=Work3'" with an "img" tag 
       inside it.<br>
WHEN : a link to image for work3 is placed inside "img" tag.<br>
WHEN : a "section class='Work-4_5'" is created inside "div 
       class='Work-Content' id=Work'".<br>
WHEN : a "div class='Work4'" is created inside "section 
       class='work-4_5'".<br>
WHEN : a "div class='work4-heading'" is created inside "div 
       class='Work4'".<br>
WHEN : a "h3" & "p" tag are created inside "div class='work4-heading'".
       <br>
WHEN : "a" tag  with "img" tag inside it is created inside "div 
       class='Work4'".<br>
WHEN : a link to image for work4 is placed inside "img" tag.<br>
WHEN : a "div class='Work5'" is created inside "section 
       class='work-4_5'".<br>
WHEN : a "div class='work5-heading'" is created inside "div 
       class='Work5'".<br>
WHEN : a "h3" & "p" tag are created inside "div class='work5-heading'".
       <br>
WHEN : "a" tag  with "img" tag inside it is created inside "div 
       class='Work5'".<br>
WHEN : a link to image for work5 is placed inside "img" tag.<br>
WHEN : some style attributes are applied to every section,divs,img,p,h2,
       h3, & class inside style.css.

*(5) When the employer load the portfolio, he is presented with a section with the developer's contact details.*
------
It's considered done<br>
------
WHEN : a "footer" element is added  after the "main" element in index. 
       html.<br>
WHEN : a "div class='ContactMe-Content'" is created inside "footer".<br>
WHEN : a "div class='ContactMe-SubHeading'" is created inside "div 
       lass='ContactMe-Content'".<br>
WHEN : "h2" tag is created inside "div class='ContactMe-SubHeading'".
       <br>
WHEN : a "div class='ContactMe-Details'" is created inside "div 
       class='ContactMe-Content'".<br>
WHEN : a "div class='ContactMe-Ul'" is created inside "div 
       class='ContactMe-Details'".
WHEN : 3 "li" is created inside "div class='ContactMe-Ul'" for 
       phone-number, Email-address & github-id.<br>

*(6) When the employer load the portfolio, he is presented with a section at bottom of the page which says "created by: 'developer's name'" & a "button" to scroll up the entire page.*
------
It's considered done<br>
------
WHEN : a "div class='footer'" is created at the bottom of "footer" 
       element.<br>
WHEN : a "h2" element si created inside "div class='footer'" which says "MAde by: developer's name".<br>
WHEN : a 'anchor' tag is created inside "div class='footer'".<br>
WHEN : a home 'button' is created inside the 'a' tag.

*(7) When the employer click one of the links in the navigation then the UI scrolls to the corresponding section.*
------
It's considered done<br>
------
WHEN : "href" attribute is provided to all the "li" inside "div 
       class="navbarDiv-links" and same href attribute name is provided to the corrosponding "div".

*(8) When the employer click on the images of the applications then he is taken to that deployed application*
------
It's considered done<br>
------
WHEN : anchor 'a' tag inside the corrosponding "div' is having link to  
       the deployed application as "href" attribute.

*(9)When the employer is presented with the developer's first application then that application's image should be larger in size than the others*
------
It's considered done<br>
------
WHEN : .Work1 img {} is given a  max-height: 500px & width: 80% in 
        style.css.

*Deployed application should look like the below given image*

<img src="./background-image/Portfolio-Application-Preview.png" alt="Portfolio-Application-Screenshot">

*GitHub url to the repository*
------
https://github.com/Amit-Ranjan22/Portfolio_Amitabh-Ranjan.git
------

*url to the deployed application*
------
https://amit-ranjan22.github.io/Portfolio_Amitabh-Ranjan/
------
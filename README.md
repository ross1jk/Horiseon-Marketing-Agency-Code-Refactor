# 01 HTML CSS Git: Code Refactor

## Description

  Horiseon Marketing Agency wants a code base that follows accessiblity stanards so that their ow nsite is optimized for serach engines. 

  The existing code that Horiseon Marketing Agency had was refactored so that accessiblity standards were met. 

## HTML Modifications

  Within the head of index.html the link to the css style sheet was modfied so that it followed the new relative path that was created. The title of the website was also modfied so to 'Horiseon Marketing Agnecy' so that when users have the page open on their screen, they can quickly identify and navigate to their site. 

  Within the Body of the index.html, every div and div class on the webpage were renamed as semantic HTML elements. The following elements are incldued on the HTML docuemntation: header, nav, figure, main, article, aside, and footer. 
  **header**
    This element was renamed to header because it represents a container for introductory content and a set of navigational links. The header also contains the below modfied, nav. 
  **nav**
    This element was changed to navigation instead of div, because these links allow you to navigate the page. Each link in the navigation was tested and/or updated to ensure that onces selected they would bring you to the proper article that they refrenced. 

  **figure**
    This element was changed to be a figure tag because a figure tag refrences self-contained content and if this image was removed it would not iterrupt the flow of the website. The image follows a relative path to the images folder, instead of a website URL to ensure it is always connected to the website. An Alt was added that describes that the Horiseon Marketing Team is at a Marketing Meeting. 

  **main**
    Changed the overall section to main because this is the main porition of the webpage becuase it contains the main contnet. Inside the main content was the below modfied, article.
  **article**
   This was to be articles because changed each element is self contained and could stand apart from the other elements. Alt atributes were added to each figure to meet accessiblity standards. The realtive pathways for thee images were updated. 
  
  **aside**
  Each div tag was chagned to be aside because this content is placed aside of the main content and is indirectly related.Alt atributes were added to each figure to meet accessiblity standards. The realtive pathways for thee images were updated. 
  
  **footer**
  Changed div to footer as this section is at the bottom of the site page and contains both the authorship and copyright information.

## CSS Modifications

```
GIVEN a webpage meets accessibility standards
WHEN I view the source code
THEN I find semantic HTML elements
WHEN I view the structure of the HTML elements
THEN I find that the elements follow a logical structure independent of styling and positioning
WHEN I view the image elements
THEN I find accessible alt attributes
WHEN I view the heading attributes
THEN they fall in sequential order
WHEN I view the title element
THEN I find a concise, descriptive title
```

## Mock-Up

The following image shows the web application's appearance and functionality:

![code refactor demo](./Assets/01-html-css-git-homework-demo.png)
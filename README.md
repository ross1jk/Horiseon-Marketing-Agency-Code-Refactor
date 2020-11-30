# 01 HTML CSS Git: Code Refactor

## Description

  Horiseon Marketing Agency wants a code base that follows accessiblity stanards so that their ow nsite is optimized for serach engines. 

  The existing code that Horiseon Marketing Agency had was refactored so that accessiblity standards were met. 

## Folder Modifications
  To follow industry best practices within the week-1-homework repository the folder structure has been updated. 

  **index.html** 
  Stands on it own, outside of any folder.
  
  **README** 
  Stands on it own, outside of any folder.
  
  **Images** 
  This folder contains all of Horiseon Marketing Agency's images

  **Style.css** 
  This folder contains the style.css document. 

  **Assets**
  This folder contains the Mock-up image. 

## HTML Modifications
  
  **head**
  Within the head of index.html the link to the css style sheet was modfied so that it followed the new relative path that was created. The title of the website was also modfied so to 'Horiseon Marketing Agnecy' so that when users have the page open on their screen, they can quickly identify and navigate to their site. 
  
  **body**
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
  Each CSS tag had to change to refrence the modfications taht were made on the index.html document. 
  
  **header**
  Changed to header from .header class so it would link with the html header. All CSS elements located within the header were also changed from the .header class to header 

  **nav**
  Changed from div to nav for the header css elements.

  **figure**
  Changed from .hero tag to figure tag to refrence the changed html. Also removed image link, the image is now referenced in the html document. Added a figure image tag, and within that made sure that object-fit was set to cover, so the image was no longer distorted

  **main**
  Combined like styling for articles, article images, article headings. Moved styling elements so they follow a logical sequence. Moved float left and float right classes be near main article img tag that they refrence, and follow the structure of html document.
  
  **aside**
  Changed Div to aside and added color tag for the whole section because all font is the same color. Combined each div class into one tag because the formatting is the same. All h3 div classes are now aside h3. All img div classes are now aside img. All div classes that refrenced paragrpahs are now a p aside tag 

  **footer**
  Changed div footer class to be footer this allwos it to align with html chagnes, footer class for h2 tag, also changed
  

## Mock-Up

The following image shows the web application's appearance and functionality:

![code refactor demo](./Assets/01-html-css-git-homework-demo.png)
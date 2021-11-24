<img src="./img/readme-logo.png" width="500px" height="auto">

# Out of Sight - Accomodation and Excursion Booking Application. 
> Out of Sight is a single page accomodation booking application which offers star gazing excursions and accomodation near New Zealand's dark sky reserves. Users will complete inputs which validate their information, and Out of Sight will display accomodation best suited to them. Once accomodation and an excursion option is selected, Out of Sight will present the users wit their reservation details. The user can then choose to contact Out of Sights Booking Team if they wish to complete their booking.


## Table of Contents
* [General Info](#general-information)
* [Productions Tools and Workflow](#Productions-tools-and-workflow)
* [Validation](#validation)
* [JS Style Guide](#js-style-guide)
* [Features](#features)
* [Room for Improvement](#room-for-improvement)
* [Acknowledgements](#acknowledgements)
* [Contact](#contact)



## General Information
- The single page web application was built as part of a Yoobee Web & UX design summative assignment.
- The application allows users to input information, validate the information and display meaningful feedback.
- Website is not responsive and has been creates for a full desktop screen width on a Yoobee screen computer. 


## Productions Tools and Workflow

#### *Atom Editor - version 1.55.0 x64*

Atom was used as tool for seamlessly editing code. The benefit of atom is that it highlights files to you that have they have not been pushed to Github. Code is colour coded for ease on the eye. You can install packages to help and guide you while writing code. I installed packages atom-beautify 0.33.2 and atom-live-server 2.3.0.  


#### *Google Chrome - version 91.0.4472.114*

I used Google Chrome’s console by ‘right-clicking’ >> inspect. I was able to monitor issues that appeared in the browser while writing and testing code, this allowed me to quickly resolve errors.  


#### *Adobe Illustrator*

I used ai as tool for creating design layouts in the form of hi-fis. The brand logo was created in ai, along with small components used on the website. 


#### *Birme*

Birme was used to re-size groups of images at the same time.

Find the link [here](https://www.birme.net/?target_width=2500&target_height=1400&auto_focal=false&quality_jpeg=100&quality_webp=100).


#### *Gulp* 

Gulp has been used along with the Mac Terminal as a live linting tool for the custom.js file. It complied the SASS file and minified the custom.css file. Gulp also helped by live reloading the application in the browser whenever I saved the code files.  


#### *Github*

Github has been used to store the files within the repository. You can clone this folder for yourself. 



## Validation

### *HTML Validation*

The project has been validated using Validator w3 [here](https://validator.w3.org)

1. One error type was received on serveral button tags:

<img src="./img/screenshot2.png" width="auto" height="100px">

The **herf** attribute is needed for the plugin annimatedModal to work and will through an error if the attribute is not mentioned. 

2. There was a Favicon error which has been remedied by using the below link tag in between the **<head>** tags within the HTML markup. 

`<link rel="shortcut icon" href="#" />`


 
#### *CSS Validation*
 
The project has been validated using Jigsaw w3 [here](https://jigsaw.w3.org/css-validator/)

1. There were no errors received.

 

### *JS Validation*
 
The project has been validated using jsHint [here](https://jshint.com/)
 
1. There were no errors received.
 
2. However it does show one unsused variable on line 272 called **popup.** This variable cannot be deleted as the code has been copied from mapbox and will break the map when removed. 

The project has been validated using jsHint [here](https://gulpjs.com/)
 
1. There was one error, please see below. This is due to the use of a **async function** being used. This code was copied and requires this type of function when using the Nasa apod api. 
 
 <img src="./img/screenshot1.png" width="auto" height="100px">
 


 
## JS Style Guide

Idiomatic javaScript style guide [_here_](https://github.com/rwaldron/idiomatic.js).
 
**The main take outs from the standard are as follows:** 

1. White space used within parentheses and array brackets. 
2. White space between functions and their content 
3. Comments used throughout the markup to highlight certain sections which link back the HTML markup. 
4. Single quotation marks used instead of double quotation marks. Where doubles have been used in certain areas of the code, this is due to having copied code from Mapbox and Nasa api. Changing the doubles to singles will break the code. 
5.Variables listed at the top of function scope. 

 
 
## Features

### **JavaScript Libraries**
 
1. Bootstrap
  * Tooltip on home screen button
  * Layout
2. Mapbox
  * Dark theme styling
  * Layer map with orange dots for places of interest
  * popup boxes -styles
  * Designed own markers
  * zoom in and out controls
3. jQuery
4. Font Awesome
 * Icons used throughout app UI
5. Parsely
 * feedback validation at guest section


### **Plugins**
 
1. Loading.io
  * Eclipse loader when app opens
2. Date Picker
 * Ui feature used to user did not have to type the date.
3. Nasa Apod API
  * Add interest to the application and gets users excited to use the app
  * Please note, on the odd occasion Nasa will post a video of the day, instead of an image of the day. For security reasons Chrome will not play any videos from the API.
4. Fullpage.js
  * page slides and transitions
5. annimatedModal
  * creates a modal which presents excursions


## Project Status
Project is: _complete_ 


## Room for Improvement

Room for improvement:
- Improvement layout and make application responsive
- Improvement input styling

To do:
- Feature to be added: css annimations


## Acknowledgements

- Many thanks to everyone who helped me in some way or another to complete this project, the many resources found online to find inspiration and all the open-source plugins, libraries and api used. 


## Contact
Created by [@cchiba](charissa_chhiba@hotmail.com) - feel free to contact me if you have any questions or queries!


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->

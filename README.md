# PROJECT: PORTFOLIO TEMPLATE
Portfolio Template is a website you can use to showcase your skills and talents to recruiters and potential employers. The application links through selected projects for recruiters and employers to review samples of your work.

## Usage
Use the portfolio template to 
- demonstrate your design, css and html skills 
- link through to projects
- state the skills and languages used for each project
- include a brief About Me description
- communicate contact information and a link to your resume.

The code is available for download on [GitHub](https://github.com/grace-anderson/portfolio)

## Features
The portfolio template:
- includes the developer's name, a recent photo or avatar
- provides links to sections about them, their work, and how to contact them
- has navigation has links that, when clicked, scroll to the relevant heading in the body of the template
- has a navigation link that, when clicked, scroll to a work section with titled images of the developer's applications
- presents the developer's first application with an image that is larger in size than the other images
- links from each application image to that deployed application
- resizes so that the user can view the site on various screens and devises, presenting the user with a responsive layout that adapts to the viewpor

## Tests
1. WHEN I click one of the links in the navigation, THEN the UI scrolls to the corresponding section
2. WHEN I click on the link to the section about their work, THEN the UI scrolls to a section with titled images of the developer's applications
3. WHEN I click on the images of the applications, THEN I am taken to that deployed application
4. WHEN I resize the page or view the site on various screens and devices, THEN I am presented with a responsive layout that adapts to my viewport
5. WHEN I click on [this deployed link](https://grace-anderson.github.io/portfolio/), the deployed application loads without error
6. WHEN I view the deployed application, it resembles the screenshots below for the viewport width specified in the images (below the Challenges and Further Work section)

## Challenges and Further Work
- ***Images***-  Styling images using flexbox was difficult, as the flexbox became increasingly nested, complicated further by the headings that overlaid the work images. Next steps are to revisit and improve the image display. Also improve handling of image resizing
- ***Removing opacity change from the H3 headings*** - The opacity change that happens when hovering over an image is being applied to the overlaid H3 heading box. I'd like ore control over this, either removing the heading box entirely from the opacity change or doing something more interesting like changing the heading box colour. 


## Images of deployed application

### Mobile first view
![Mobile first](/assets/images/mobile-view.png)
   
### Max-width: 300px
![300px](/assets/images/max-width-300px.png)

### Min-width: 768px
![768px](/assets/images/min-width-768px.png)

### Min-width: 992px
![992px](/assets/images/min-width-992px.png)

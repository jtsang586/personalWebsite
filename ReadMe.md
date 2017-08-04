# Read Me
## Personal Website

 The task for this project was to create a personal website using the bootstrap framework as well as putting into use newly learnt HTML and CSS.
 
 The checklist to complete this task include the following:
 
 1. Create wireframe. (trainer approved) 
 2. Create new GitHub repository.
 3. Find [colour] (https://coolors.co/50514f-f25f5c-ffe066-247ba0-70c1b3) scheme and [font.] (https://fonts.googleapis.com/css?family=Quicksand|Roboto" rel="stylesheet)
 4. Install Bootstrap onto the new repository.
 5. Link custom stylesheet.
 6. Build HTML template.
 7. Start Bootstrapping/ CSSing

 **Deadline 13:30 3rd August**
 
## The Inspiration
 The objective for creating this website was to create **portfolio** which could showcase some of the projects I have completed in the past. The aim is to create a site which was simple but still containing enough information to showcase everything about the project.
 
## The Wireframe
 
![Desktop Framework] (images/Frame1.jpg)
Desktop wireframe
![Mobile Framework] (images/Frame2.jpg)
Mobile wireframe
 
## The Website
 
### Header
The header is coloured in blue and contains the name of the website. It also has a width which covers the entire website.
 
### The Main
 
On the left of the page is the main **navigation bar** which covers the height of the **main** section of the website. The first section of the main is a video frame containing a video of the project. 
 
```html
 <div class="embed-responsive embed-responsive-16by9">
        <iframe width="560" height="315" src="https://www.youtube.com/embed/IANeffbCrLA" frameborder="0" allowfullscreen></iframe></div> 
```
The middle section contains a selection of pictures organised using the default bootstrap carousel. The beginning code for the carousel is 

```html
<div id="myCarousel" class="carousel slide" data-ride="carousel">
```
An additional link to javascript and jquery was required for the carousel to work.

### Second Main
 
 The second main contains the specific details regarding the project. The left part of contains bitesize information which is highlighted using **block qoutes** and **background-color**
 
 ```html
 <section class="col-md-3" id="info">
      <blockquote id="blue">
        <h4>Role: Programmer</h4>
      </blockquote>
 ```
 The main paragraphs contain most of the information regarding the project.
 
### Responsiveness
The main responsiveness is handled by **Bootstrap.** Some additional CSS code is added to remove the left bars when the screen **width** is reduced bellow **992px**.
 
 ```css
 @media screen and (max-width: 992px) 
{
  ul {
    display: none;
  }
  #info {
    display:none;
  }
}
 

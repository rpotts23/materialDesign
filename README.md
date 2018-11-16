# materialDesign
How to use Material Design
What is material design? Material design is useful for User Interface design, designing the skin of the site.
This tutorial will focus on creating a Google Like design. In part 1, I will be using the provided material templates to create a moble site.  Part 2 will have more html and css.

Part 1: Sketch Wireframes
Open Sketch.
Click on Material Design icon and select choose.

Go up to File, New from Template and this should appear:

These are templates designed for Material Design interfaces. Take some time look through these.

Create a new page in Sketch. This is where we are going to be building an app.

On the new page create mobile 3 art boards.

Using the Material Design stickers on the page shown and material design symbols create something like this. 

Start customizing the Material design stickers.

For secondary color I am using 4CB5AB. This color will be used throughout the designing. 
Page elements are found between the Material Design Stickers and the Material Design symbols pages. 


Material design on top of creating unique simple wireframes helps when seeing the wireframes in context of use. Material Design offers keyboard stickers as well as browser symbols. This helps make the wireframes seem like they fit the design they are made for. With this the client can look in on the wireframe set up and see a representation of a site how they would view it on their phone, tablet, or desktop. 
Also with Material mockups, it is easy to change colors, font and other elements before the site is started. If I was designing for a client, this would be relative to the first round of revisions with the client. They can see how it looks with some of the general elements that will be designed.
	If this was actually for a client the second step would be to start plugging in some sample content. The sample content would come from the client or stuff found online.

Part 2: HTML and CSS
 First things first, create 2 pages with the base HTML.
Before starting to drop code in make the body width 320 px wide
 The first one will be the list page. In Terminal paste this into the folder:
npm install @material/list

For the list copy and paste this text inside the body:
	<h2> Artist</h2>
	<ul class="mdc-list" aria-orientation="vertical">
  <li class="mdc-list-item">
    <span class="mdc-list-item__text">Daily Jam</span>
  </li>
  <li class="mdc-list-item">
    <span class="mdc-list-item__text">Jazz</span>
  </li>
  <li class="mdc-list-item">
   <a href=”#”> <span class="mdc-list-item__text">Dem Beatz</span></a>
  </li>
</ul>

Add this to the CSS:
	ul li {
		List-style:none;}

For the search bar paste this at the top, I have not been able to find any code from material. Here is coding from w3 schools

	<div class="topnav">
  <input type="text" placeholder="Search..">
</div>

Css:
	.topnav input[type=text] {
	float: right;
	padding: 6px;
	border: none;
	margin-top: 8px;
	margin-right: 16px;
	font-size: 17px;
}

Making adjustments as needed, use CSS to create a cohesive page that gets close to the wire fraim.

Make sure to link this page to the playlist page.

For the second page start off with a h1
	<h1> Daily Jam</h1>
<ul class="mdc-list" aria-orientation="vertical">
  <li class="mdc-list-item">
    <span class="mdc-list-item__text">Item 1 - Division 1</span>
  </li>
  <li class="mdc-list-item">
    <span class="mdc-list-item__text">Item 2 - Division 1</span>
  </li>
  <li role="separator" class="mdc-list-divider"></li>
  <li class="mdc-list-item">
    <span class="mdc-list-item__text">Item 1 - Division 2</span>
  </li>
  <li class="mdc-list-item">
    <span class="mdc-list-item__text">Item 2 - Division 2</span>
  </li>
</ul>

With this css:
	h1{ color: 4CB5AB;}
Using css make it more like the design

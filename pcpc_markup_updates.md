#PCPC Markup Updates

#### Removed Text, 'Menu' from Sidebar Toggle
	<span id='sidebarToggle'>
      <a href='#sidebar' id='sidebarButton'>Menu</a>
    </span>


####Ministry Index Toggle: Removed text, added span
	<a class='toggleMegaDrop' href='#'> <span></span></a>

####Site Logo: Added Image
	<h1 id='name'>
      	<a href='/'>
      		<img src="images/site/logo+@2x.png" alt="PCPC" />
      	</a>
    </h1>  
    
####Corrected Doctype added by Haml…weird
    
####Better defined off canvas Side Menu
	<ul class='nav-bar' id='sideMainNav'>
      <h4>
        <a href=''>Side Nav Title</a>
      </h4>
      <li class='active'>
        <a href=''>One</a>
      </li>
      <li>
        <a href=''>Two</a>
      </li>
      <li>
        <a href=''>Three</a>
      </li>
      <li>
        <a href=''>Four</a>
      </li>
  </ul>

####Better Defined Welcome Orbit Text Slides 
	<div class="orbit-slide-text">
        <div class="orbit-slide-column small">
          <h4>This is a Content Slider Header.</h4>
          <span class="tag">August 10, 2011</span>
		  <p>Danish singer/songwriter Agnes Obel took up the piano at a very young age, honing her craft amidst the strains of Bartók and Chopin emanating from the fingers of her musician mother. 
          <span class='meta'>John 1:1-18</span></p>
          <a href="#" class="button">Details</a>
        </div>
        
        <div class="orbit-slide-column big">
          <img src='http://placehold.it/740x340' />
        </div>
    </div>
    
####Added Search Bar in Footer for Mobile
	<li class='search' id="footer-search">
	  <div class="search-inner">
		 <input placeholder='Search' type='text' />
		<input type="submit" class="button" value="go" />
		</div>
	</li>
	
####Added Selectivzr script for ltIE8 Psuedo Classes 

####Added Columnizr for ltIE9 CSS Columns

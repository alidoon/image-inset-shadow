image-inset-shadow
==================

you can insert inset shadow for your images  with this snippet

Markup example
==================
image inset shadow works with the following markup :

      <a href="http://www.odinrome.com" class="img-shadow">
        <img src="_20130411-214949.png" alt="" />
      </a>
      
this is a simple code

css classes
=================
use css3

    .img-shadow {
      position: relative;
    	max-width: 100%;
    	float: left;
    	}
    .img-shadow::before {
		content: "";
		position: absolute;
		top: 0;
		bottom: 0;
		left: 0;
		right: 0;
		box-shadow: inset 0 0 80px rgba(0,0,0,.6);
		-moz-box-shadow: inset 0 0 80px rgba(0,0,0,.6);
		-webkit-box-shadow: inset 0 0 80px rgba(0,0,0,.6);
	   }

.img-shadow img {
	float: left;

	}
  
  
  

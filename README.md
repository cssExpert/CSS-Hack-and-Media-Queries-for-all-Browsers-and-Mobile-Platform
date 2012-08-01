CSS-Hack-and-Media-Queries-for-all-Browsers-and-Mobile-Platform
===============================================================

* _html xyz {} /* IE6 */
* +html xyz {} /* IE7 */
*:first-child+html xyz {} /* IE7 */

@media \0screen { xyz {} } /* IE8 */

:root .color {color: #F00\9;} /* IE9 */

@media screen and (-webkit-min-device-pixel-ratio:0) { xyz {} } /* Safari */

html>/**/body .selector, x:-moz-any-link {
  color:lime;
} /* Firefox 2 */

html>/**/body .selector, x:-moz-any-link, x:default {
  color:lime;
} /* Firefox 3 */

@-moz-document url-prefix() {  xyz {} } /* Any Firefox */

@media all and (-webkit-min-device-pixel-ratio:10000), not all and (-webkit-min-device-pixel-ratio:0) { head~body #opera { color:blue; } } /* Opera */

body:nth-of-type(1) .logo{margin:20px;} /* Chrome */

===============================================================
Media Queries
===============================================================

/* #Tablet (Portrait)
================================================== */

    /* Note: Design for a width of 768px */

    @media only screen and (min-width: 768px) and (max-width: 959px) {
  	


	}
	
/* #Tablet (Landscape)
================================================== */

	/* Note: Design for a width of 1024px */
	
	@media only screen and (min-width: 768px) and (orientation:landscape) {
		


	}

	
	
/*  #Mobile (Portrait)
================================================== */

    /* Note: Design for a width of 320px */

    @media only screen and (max-width: 767px) {
		


	}
	
/* #Mobile (Landscape)
================================================== */

    /* Note: Design for a width of 480px */

    @media only screen and (min-width: 480px) and (max-width: 767px) {
		


	}

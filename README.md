# HTML-and-CSS-Projects

## Introduction
These are some HTML and CSS projects that show various techniques that I have learned. Most were for my personal learning experience while trying out various 
formatting styles. 

Below are code snippets and descriptions of code that I worked on with full files available in repo. 

* [Space Station ](#Space-Station)
* [One Page Website](#One-Page-Website)

### Space Station
This website was about trying out various CSS and HTML (with some Javascript techniques as well) to make a website about the solar stystem and "Space Travel". This project was interactive with setting up local references/images to call on, navbars, containers, etc. Below is a sample of the HTML that was involved in the project: 

        <!DOCTYPE html>
        <html lang="en">
            <head>
                <title>Space Station/Resort</title>
                <meta charset="utf-8">
                <link rel="stylesheet" href="./css/shared.css">
                <link rel="stylesheet" href="./css/animations.css">
            </head>		
            <body>

            <!--NAV-->
		<div class="wrap">
			<div menu="menu-container">
				<ul class="menu">
					<a href="#home"><li>HOME</li></a>
					<a href="#gallery"><li>GALLERY</li></a>
					<a href="#contact"><li>RESERVATION</li></a>
				</ul>
			</div>

		</div>
		<!--End NAV-->

		<!--HOME-->
		<div id="home">
			<div class="container">
				<div class="text-center">
					<span class="head-main">The Space Station </span>
				</div>
			</div>

		</div>
		<!--End HOME-->

		<!--GALLERY-->
		<section id="gallery">
			<div class="container">
				<h1>Gallery</h1>
				<div class="flex-container">
					
						<!--PHOTO 1 CONTAINER-->
						<div class="photo-container">
							<div class="photo">
								<img src="./images/thumb/thumbnail_1.png"alt="Mercury">
								<div class="photo-overlay">
									<h3>Click to enlarge</h3>
									<p>We  have several space launches departing daily, book your flight today</p>
								</div>
							</div>
						</div>
						<!--End Photo Container-->


### One Page Website
This is fun, small project that I got to work on to display some of my various new programming skills combined with my history of being a physical therapist. This is an incomplete website, but has several CSS and HTML features. Below is some of the CSS that was involved and will continue to be edited over time:


    body {
    font-size: 15px;
    font-family: Verdana, Geneva, Tahoma, sans-serif;
    background-color: rgb(40, 62, 104);
}

    .containers {
        width: 50%;
        margin: 3px;
        border: black;
        border-radius: 8%;
    }
    img {
        width: 50%;
        height: 50%;
      }

    .row > .column {
        padding: 0 8px;
      }

      .row:after {
        content: "";
        display: table;
        clear: both;
      }

      /* Create five equal columns that floats next to eachother */
      .column {
        float: left;
        width: 10%;
        height: 10%;
      }

      /* The Modal (background) */
      .modal {
        display: none;
        position: fixed;
        z-index: 1;
        padding-top: 100px;
        left: 0;
        top: 0;
        width: 100%;
        height: 100%;
        overflow: auto;
        background-color: black;
      }

---
title: District Match
description: District Match is a web application that lets you match your addresses to legislative districts and elected officials.  Simply upload your addresses in a CSV and District Match will return them stamped with the legislative districts and elected official information you requested.
layout: default
permalink: /districtmatch
theme: light
---

<div id="top" class="row">
	{% include nav.html%}
	<div class="container px-0">
		<div class="row">
			<div class="col-md-12">
				<img src="{{ site.baseurl }}/img/geocoder-hero.png" class="img-fluid">
			</div>
		</div>
	</div>
</div>

<div id="project-elmo" class="container">
	
	<div class="row">
		
		<!-- Content -->
		<div class="col-md-9">
			<div class="row">
				<div id="introduction" class="col-md-12 mt-5">
					<h1>{{ page.title }}</h1>
					<label><span class="badge">2015</span> | Web App</label>
					<div class="d-block">
						<a href="https://ctaylo37.github.io/geocoder/review.html" target="_blank" class="btn btn-primary">View Demo</a>
					</div>
				</div>

				<div class="col-md-12 mt-5">
					<h4 id="about" >About</h4>
					<p>{{ page.description }}</p>
					<h4 id="roles" class="mt-5">My Roles</h4>
					<ul>
						<li>UX Design</li>
						<li>Visual Design</li>
						<li>HTML Development</li>
					</ul>
				</div>

				<div id="process" class="col-md-12 mt-5">
					<h1>Process</h1>
				</div>

				<div id="step-1" class="col-md-12 mt-5">
					<h4>Step 1: Wireframes</h4>
					<p>I went through several rounds of wireframes with the product owner and customers.  From a product standpoint there were a lot of inputs we needed to capture.  From a user standpoint it was important that we made the long form easy to fill out and provide helpful feedback along the way.</p>
					<div class="crt-card p-0 mt-4">
						<img src="{{ site.baseurl }}/img/geocoder-1.png" class="img-fluid">
					</div>

					<div class="row mt-4">
						<div class="col-md-6">
							<h5>Challenges</h5>
							<ul>
								<li>It's hard to capture validation and errors with a static wireframe.</li>
								<li>The biggest painpoints for customers was keeping track of where they were in the form and making sure they provided accurate input.</li>
							</ul>
						</div>
						<div class="col-md-6">
							<h5>Takeaways</h5>
							<ul>
								<li>I decided to break the long form into manageble chuncks of inputs.</li>
								<li>I learned a lot about validation and empathetic feedback designing a form of this scale.</li>
							</ul>
						</div>
					</div>
				</div>

				<div class="col-md-12"><hr></div>

				<div id="step-2" class="col-md-12 mt-5">
					<h4>Step 2: Visual Design</h4>
					<p>The visual design phase helped the overal usability of the geocoder by introducing color to create a heirarchy in the UI.</p>
					<div class="crt-card p-0 mt-4">
						<img src="{{ site.baseurl }}/img/geocoder-2.png" class="img-fluid">
					</div>

					<div class="row mt-4">
						<div class="col-md-6">
							<h5>Challenges</h5>
							<ul>
								<li>Incorporating the desing into the Cicero brand re-design that was happing organically as this project was underway.</li>
								<li>The style guidelines kept changing as they were being adapted for the new Cicero website.</li>
							</ul>
						</div>
						<div class="col-md-6">
							<h5>Takeaways</h5>
							<ul>
								<li>Left aligned form labels, while not eas easy to read as top aligned labels, helped keep the appearance of the form shorter and thus not overwhelming the customers.</li>
								<li>I learned that it's not a linear handoff from visual design to HTML, becaus ein this case it kept evolving into the HTML phase of product development.</li>
							</ul>
						</div>
					</div>
				</div>

				<div class="col-md-12"><hr></div>

				<div id="step-3" class="col-md-12 mt-5">
					<h4>Step 3: HTML Prototype</h4>
					<p>For the prototyping phase I created a static HTML website.  This allowed me to add in user feedback and validation which was helpful for getting feedback from customers, but also in communicating the small details to the development team.</p>
					<div class="crt-card p-0 mt-4">
						<img src="{{ site.baseurl }}/img/geocoder-3.png" class="img-fluid">
					</div>

					<div class="row mt-4">
						<div class="col-md-6">
							<h5>Challenges</h5>
							<ul>
								<li>The visual design continued to evolve well into the HTML prototype.</li>
								<li>Making the form just as easy to fill out on mobile was challenging.</li>
							</ul>
						</div>
						<div class="col-md-6">
							<h5>Takeaways</h5>
							<ul>
								<li>The prototype helped explain the micro interactions and form validation such as progressive disclosure to the developers.</li>
								<li></li>
							</ul>
						</div>
					</div>
				</div>

				<div class="col-md-12"><hr></div>

				<div id="step-4" class="col-md-12 mt-5">
					<h4>Final Design</h4>
					<div class="d-block">
						<a href="https://ctaylo37.github.io/geocoder/review.html" target="_blank" class="btn btn-primary">View Demo</a>
					</div>
					<div class="crt-card p-0 mt-4">
						<img src="{{ site.baseurl }}/img/geocoder-4.png" class="img-fluid">
					</div>
				</div>

				<div class="col-md-12"><hr></div>

				<div id="more" class="col-md-12 my-5">
					<h2>More Projects</h2>
					{% include project-thumbs.html %}
				</div>

			</div>
		</div>
		
		<!-- Sidebar -->
		<div class="col-md-3 border-left py-4">
			<div id="project-sub-nav" class="sticky-top hidden-sm-down">
				<ul class="project-nav list-unstyled pl-3">
					<li><a href="#introduction" class="nav-link">Introduction</a></li>
					<li class="ml-3"><a href="#about" class="nav-link">About</a></li>
					<li class="ml-3"><a href="#roles" class="nav-link">My Roles</a></li>
					<li><a href="#process" class="nav-link">Process</a></li>
					<li class="ml-3"><a href="#step-1" class="nav-link">Wireframes</a></li>
					<li class="ml-3"><a href="#step-2" class="nav-link">Visual Design</a></li>
					<li class="ml-3"><a href="#step-3" class="nav-link">HTML Prototype</a></li>
					<li class="ml-3"><a href="#step-4" class="nav-link">Final Design</a></li>
					<li><a href="#more" class="nav-link">More Projects</a></li>
					<li class="dropdown-divider"></li>
					<li><a href="#top" class="nav-link"><i class="icon-up"></i> Top</a></li>
				</ul>
			</div>
		</div>
	</div>
</div>
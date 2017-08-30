---
title: Cicero Geocoder
description: Lorem ipsum dolor sit amet, consectetuer adipiscing elit, sed diam nonummy nibh euismod tincidunt ut laoreet dolore magna aliquam erat volutpat.
layout: default
permalink: /geocoder
---

<div id="top" class="row border-bottom">
	{% include nav.html%}
	<div class="container px-0">
		<div class="row">
			<div class="col-md-12">
				<img src="{{ site.baseurl }}/img/img.png" class="img-fluid">
			</div>
		</div>
	</div>
</div>

<div id="project-vip" class="container">
	<div class="row">
		
		<!-- Content -->
		<div class="col-md-9">
			<div class="row">
				<div id="introduction" class="col-md-12 mt-5">
					<h1>{{ page.title }}</h1>
					<h5><a href="#" target="_blank">URL</a></h5>
					<label><span class="badge">2015</span> | Web App</label>
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
					<h4>Step 1:</h4>
					<p>Lorem ipsum dolor sit amet, consectetuer adipiscing elit, sed diam nonummy nibh euismod tincidunt ut laoreet dolore magna aliquam erat volutpat.</p>
					<div class="crt-card p-0 mt-4">
						<img src="{{ site.baseurl }}/img/img.png" class="img-fluid">
					</div>
					

					<div class="row mt-4">
						<div class="col-md-6">
							<h5>Challenges</h5>
							<ul>
								<li>Challenge</li>
								<li>Challenge</li>
							</ul>
						</div>
						<div class="col-md-6">
							<h5>Takeaways</h5>
							<ul>
								<li>Takeaway</li>
								<li>Takeaway</li>
							</ul>
						</div>
					</div>
				</div>

				<div class="col-md-12"><hr></div>

				<div id="step-2" class="col-md-12 mt-5">
					<h4>Step 2:</h4>
					<p>Lorem ipsum dolor sit amet, consectetuer adipiscing elit, sed diam nonummy nibh euismod tincidunt ut laoreet dolore magna aliquam erat volutpat.</p>
					<div class="crt-card p-0 mt-4">
						<img src="{{ site.baseurl }}/img/img.png" class="img-fluid">
					</div>

					<div class="row mt-4">
						<div class="col-md-6">
							<h5>Challenges</h5>
							<ul>
								<li>Challenge</li>
								<li>Challenge</li>
							</ul>
						</div>
						<div class="col-md-6">
							<h5>Takeaways</h5>
							<ul>
								<li>Takeaway</li>
								<li>Takeaway</li>
							</ul>
						</div>
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
			<div id="project-nav" class="sticky-top">
				<ul class="project-nav list-unstyled pl-3">
					<li><a href="#introduction" class="nav-link">Introduction</a></li>
					<li class="ml-3"><a href="#about" class="nav-link">About</a></li>
					<li class="ml-3"><a href="#roles" class="nav-link">My Roles</a></li>
					<li><a href="#process" class="nav-link">Process</a></li>
					<li class="ml-3"><a href="#step-1" class="nav-link">Wireframes</a></li>
					<li class="ml-3"><a href="#step-2" class="nav-link">Visual Design</a></li>
					<li><a href="#more" class="nav-link">More Projects</a></li>
					<li class="dropdown-divider"></li>
					<li><a href="#top" class="nav-link"><i class="icon-up"></i> Top</a></li>
				</ul>
			</div>
		</div>
	</div>
</div>
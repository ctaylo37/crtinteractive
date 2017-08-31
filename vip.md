---
title: Voting Information Project
description: The Voting Information Project is a database of election information made accessible to citizens via mobile device. The application provides an intuitive interface for users to find data about upcoming elections, such as where to vote, directions to polling location, issues on the ballot, and even candidates’ contact information.
layout: default
permalink: /vip
theme: light
---

<div id="top" class="row">
	{% include nav.html%}
	<div class="container px-0">
		<div class="row">
			<div class="col-md-12">
				<img src="{{ site.baseurl }}/img/vip-hero.png" class="img-fluid">
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
					<label><span class="badge">2014</span> | Android App</label>
				</div>

				<div class="col-md-12 mt-5">
					<h4 id="about" >About</h4>
					<p>{{ page.description }}</p>
					<h4 id="roles" class="mt-5">My Roles</h4>
					<ul>
						<li>UX Design</li>
						<li>Visual Design</li>
					</ul>
				</div>

				<div id="process" class="col-md-12 mt-5">
					<h1>Process</h1>
				</div>

				<div id="step-1" class="col-md-12 mt-5">
					<h4>Step 1: Wireframes</h4>
					<p>For the wireframing process I worked closely with the product manager to transfer the experience from iOS to Android. There were several major layout differences between the two experiences.</p>
					<img src="{{ site.baseurl }}/img/vip-1.svg" class="img-fluid">

					<div class="row mt-4">
						<div class="col-md-6">
							<h5>Challenges</h5>
							<ul>
								<li>I wasn’t part of the team who originally developed the iOS application.</li>
								<li>I was new to native Android design.</li>
							</ul>
						</div>
						<div class="col-md-6">
							<h5>Takeaways</h5>
							<ul>
								<li>This project really allowed me to parse the differences in experience and interface design between iOS and Android applications.</li>
								<li>I learned more from this project than starting a native app from scratch.</li>
							</ul>
						</div>
					</div>
				</div>

				<div class="col-md-12"><hr></div>

				<div id="step-2" class="col-md-12 mt-5">
					<h4>Step 2: Visual Design</h4>
					<p>For the visual design phase, I had the opportunity to study and research Android design patterns. I utilized a flat color pallet and high contrast typography to ensure a readible experience on the go.</p>

					<div class="row mt-4">
						<div class="col">
							<img src="{{ site.baseurl }}/img/vip-2.png" class="img-fluid">
						</div>
						<div class="col">
							<img src="{{ site.baseurl }}/img/vip-3.png" class="img-fluid">
						</div>
					</div>

					<div class="row mt-4">
						<div class="col">
							<img src="{{ site.baseurl }}/img/vip-4.png" class="img-fluid">
						</div>
						<div class="col">
							<img src="{{ site.baseurl }}/img/vip-5.png" class="img-fluid">
						</div>
					</div>

					<div class="row mt-4">
						<div class="col">
							<img src="{{ site.baseurl }}/img/vip-6.png" class="img-fluid">
						</div>
						<div class="col">
							<img src="{{ site.baseurl }}/img/vip-7.png" class="img-fluid">
						</div>
					</div>

					<div class="row mt-4">
						<div class="col">
							<img src="{{ site.baseurl }}/img/vip-8.png" class="img-fluid">
						</div>
						<div class="col">
							<img src="{{ site.baseurl }}/img/vip-9.png" class="img-fluid">
						</div>
					</div>

					<div class="row mt-4">
						<div class="col">
							<img src="{{ site.baseurl }}/img/vip-10.png" class="img-fluid">
						</div>
						<div class="col">
							<img src="{{ site.baseurl }}/img/vip-11.png" class="img-fluid">
						</div>
					</div>
						
					<div class="row mt-4">
						<div class="col">
							<img src="{{ site.baseurl }}/img/vip-12.png" class="img-fluid">
						</div>
						<div class="col">
							<img src="{{ site.baseurl }}/img/vip-13.png" class="img-fluid">
						</div>
					</div>

					<div class="row mt-4">
						<div class="col-md-6">
							<h5>Challenges</h5>
							<ul>
								<li>Short turnaround time.</li>
								<li>No time or resources available for user testing externally.</li>
							</ul>
						</div>
						<div class="col-md-6">
							<h5>Takeaways</h5>
							<ul>
								<li>Learned to be efficient and lean when designing under a time crunch.</li>
								<li>Learned how to make internal testing and feedback useful.</li>
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
			<div id="project-sub-nav" class="sticky-top hidden-sm-down">
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
---
title: Sherlock
description: Internal monitoring system for PayPal.
layout: default
permalink: /sherlock
theme: light
---

<div id="top" class="row">
	{% include nav.html%}
	<div class="container px-0">
		<div class="row">
			<div class="col-md-12">
				<img src="{{ site.baseurl }}/img/sherlock-hero.png" class="img-fluid">
			</div>
		</div>
	</div>
</div>

<div id="project-sherlock" class="container">
	
	<div class="row">
		
		<!-- Content -->
		<div class="col-md-9">
			<div class="row">
				<div id="introduction" class="col-md-12 mt-5">
					<h1>{{ page.title }}</h1>
					<label><span class="badge">2018</span> | Web App (Work In Progress)</label>
					<div class="d-block">
						<a href="http://www.christophertaylor.com/sherlock-demo//analyze" target="_blank" class="btn btn-primary">View Work In Progress</a>
					</div>
				</div>

				<div class="col-md-12 mt-5">
					<h4 id="about" >About</h4>
					<p>{{ page.description }}</p>
					<h4 id="roles" class="mt-5">My Roles</h4>
					<ul>
						<li>UX Design</li>
						<li>UX Research</li>
						<li>User Testing</li>
						<li>Visual Design</li>
						<li>HTML Development</li>
					</ul>
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
					<li><a href="#more" class="nav-link">More Projects</a></li>
					<li class="dropdown-divider"></li>
					<li><a href="#top" class="nav-link"><i class="icon-up"></i> Top</a></li>
				</ul>
			</div>
		</div>
	</div>
</div>
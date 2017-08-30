---
title: PayPal Experimentation Lifecycle Management & Ops (ELMO)
description: The PayPal Experimentation Lifecycle Management & Operations (ELMO) platform was a redesign of a legacy application internal to PayPal.  The application is used for creating ramp and AB experiments to test new experiences across all PayPal products.
layout: default
permalink: /elmo
---

<div id="top" class="row border-bottom">
	{% include nav.html%}
	<div class="container px-0">
		<div class="row">
			<div class="col-md-12">
				<img src="{{ site.baseurl }}/img/elmo-hero.png" class="img-fluid">
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
					<label><span class="badge">2017</span> | Web App</label>
					<div class="d-block">
						<a href="https://ctaylo37.github.io/elmo-demo/experiments" target="_blank" class="btn btn-primary">Demo</a>
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
					<h4>Step 1: Define the MVP</h4>
					<p>I worked very closely with the Product Manager on this project to define the MVP for our redesign.  We identified three primary goals to define the success of our project:</p>
					<ol>
						<li>Reduce the time to <abbr title="The amount of time it takes to setup an experiment and push to production." data-toggle="tooltip">go live</abbr> from <strong>one week</strong> to <strong>less than five minutes</strong>.</li>
						<li>Reduce the amount of time required to derive insights from an experiment from <strong>three weeks</strong> to <strong>less than 24 hours</strong>.</li>
						<li>Allow product teams to create and manage their own experiments rather than relying on test managers (<strong>self service</strong>).</li>
					</ol>
					<div class="crt-card p-0 mt-4">
						<img src="{{ site.baseurl }}/img/elmo-1.png" class="img-fluid">
					</div>
					

					<div class="row mt-4">
						<div class="col-md-6">
							<h5>Challenges</h5>
							<ul>
								<li>Deciding which features were most critical to our customers and build those first.</li>
								<li>We wanted to move to a self service model, which meant finding and interviewing new customers that had never worked with the application before.</li>
							</ul>
						</div>
						<div class="col-md-6">
							<h5>Takeaways</h5>
							<ul>
								<li>It was tempting to start by redesigning the create and manage workflows, but we decided to build the insights feature first, which was missing from the previous application. </li>
								<li>I found that "viable" was the key component of MVP.  Finding the balance between a shippable number of features and an application that people would enjoy using was a magical process.</li>
							</ul>
						</div>
					</div>
				</div>

				<div class="col-md-12"><hr></div>

				<div id="step-2" class="col-md-12 mt-5">
					<h4>Step 2: Interview and Sketch with Customers</h4>
					<p>In the past I have created user personas at the start of a project.  A shiny poster of faces with goals and motivations that looks good on a wall, but quickly lose their impact as the project takes off.  The poster can't remind you to think of them, or provide feedback, or insert ideas into the design process, which is why we decided from week one to include customers in our journey once a week.</p>
					<p>Weekly customer sessions included interviews, design reviews, and assessing their current tools and workflows for insights.</p>
					<div class="crt-card p-0 mt-4">
						<img src="{{ site.baseurl }}/img/elmo-2.png" class="img-fluid">
					</div>

					<div class="row mt-4">
						<div class="col-md-6">
							<h5>Challenges</h5>
							<ul>
								<li>As I mentioned previously, we had to balance current customers(lot's of domain knowledge, expertise, and experience using the previous application) with new customers (less knowledgeable about what they needed to succeed.)</li>
							</ul>
						</div>
						<div class="col-md-6">
							<h5>Takeaways</h5>
							<ul>
								<li>It's easier to forget about a poster than a person.</li>
								<li>Scheduling weekly sessions with our customers kept us on our toes and ensured that we were building exactly what our customers needed.</li>
							</ul>
						</div>
					</div>
				</div>

				<div class="col-md-12"><hr></div>

				<div id="step-3" class="col-md-12 mt-5">
					<h4>Step 3: Prototyping</h4>
					<p>Moving from sketches to clickabe wireframes is my favorite part of every project.  It's the first time the design feels alive and can provide the user with excitement and feedback.  For this project I created over a dozen prototypes before any code was written.  Some of the protoypes conveyed the overall experience of the interface, while others focused on a specific task or workflow.</p>
					
					<h5>Insights Wireframing</h5>
					<div class="crt-card p-0 mt-4">
						<img src="{{ site.baseurl }}/img/elmo-3.png" class="img-fluid">
					</div>
					<div class="crt-card p-0 mt-4">
						<img src="{{ site.baseurl }}/img/elmo-4.png" class="img-fluid">
					</div>

					<h5>Clickable Wireframe</h5>
					<p class="small">Create workflow using Adobe XD</p>
					<div class="embed-responsive embed-responsive-16by9">
					  <iframe class="embed-responsive-item" src="https://xd.adobe.com/embed/3659f7cf-13b2-411c-9353-8549a726b940/" frameborder="0" allowfullscreen></iframe>
					</div>

					<div class="row mt-4">
						<div class="col-md-6">
							<h5>Challenges</h5>
							<ul>
								<li>Prototypes are limited in their breadth and functionality.  Because of this, it's hard to keep telling customers "that thing is supposed to do x,y,z but doesn't work in this prototype."</li>
							</ul>
						</div>
						<div class="col-md-6">
							<h5>Takeaways</h5>
							<ul>
								<li>Presenting a protoype to a customer and asking them to complete a task yeilds better feedback than asking a customer what they want or need while sitting in an interview.</li>
							</ul>
						</div>
					</div>
				</div>

				<div class="col-md-12"><hr></div>

				<div id="step-4" class="col-md-12 mt-5">
					<h4>Step 4: Visual Design</h4>
					<p>During the protoyping phase I began to gain an understanding of what components we would need to build the UI.  For the visual design phase I started in Adobe XD to get the look and feel correct, and then built the HTML components using Bootstrap.  This turned into me building a component library with Bootstrap and self hosting it for internal PayPal apps to use.</p>
					
					<h5>Visual Design from Adobe</h5>
					<div class="crt-card p-0 mt-4">
						<img src="{{ site.baseurl }}/img/elmo-5.png" class="img-fluid">
					</div>
					<div class="crt-card p-0 mt-4">
						<img src="{{ site.baseurl }}/img/elmo-6.png" class="img-fluid">
					</div>
					<div class="crt-card p-0 mt-4">
						<img src="{{ site.baseurl }}/img/elmo-7.png" class="img-fluid">
					</div>
					<div class="crt-card p-0 mt-4">
						<img src="{{ site.baseurl }}/img/elmo-8.png" class="img-fluid">
					</div>
					
					<h5>Screenshot of Bolt</h5>
					<p class="small">The design library I built using Bootstrap.</p>
					<div class="crt-card p-0 mt-4">
						<img src="{{ site.baseurl }}/img/elmo-9.png" class="img-fluid">
					</div>

					<div class="row mt-4">
						<div class="col-md-6">
							<h5>Challenges</h5>
							<ul>
								<li>Working with a platform team, not many of the engineers had a lot of UI/front-end experience.  Because of this I decided to build Bolt, a Bootstrap component library that could be utilized to speed up building the UI.</li>
							</ul>
						</div>
						<div class="col-md-6">
							<h5>Takeaways</h5>
							<ul>
								<li>A lot of the time you hear horror stories about designers and developers not getting along because of pie in th sky ideas.  Because I built the UI components alongside the visual design work, I was guaranteed the final product would match the designs.</li>
								<li>I've found that learning code helps bridge the communication barrier between the designer and developer.  It also establishes a mutual respect for one another's craft.</li>
							</ul>
						</div>
					</div>
				</div>

				<div class="col-md-12"><hr></div>

				<div id="step-5" class="col-md-12 mt-5">
					<h4>Step 5: HTML Prototype</h4>
					<p>Using HTML, Jekyll, and Bolt(the Bootstrap component library I created), I was able to create a robust protoype that was available to the team and our customers.  The prototype acted as the source of truth for design and gave me the ability to prototype more complex interactions with jQuery.</p>
					<div class="crt-card p-0 mt-4">
						<img src="{{ site.baseurl }}/img/elmo-10.png" class="img-fluid">
					</div>

					<div class="row mt-4">
						<div class="col-md-6">
							<h5>Challenges</h5>
							<ul>
								<li>The biggest challenge with having a living HTML demo is trying to decide if you should code or design new feature requests.</li>
							</ul>
						</div>
						<div class="col-md-6">
							<h5>Takeaways</h5>
							<ul>
								<li>Eventually everything made it's way into the prototype, but sometime it was quicker to use Adobe and InVision to design a quick workflow.</li>
							</ul>
						</div>
					</div>
				</div>

				<div class="col-md-12"><hr></div>

				<div id="step-6" class="col-md-12 mt-5">
					<h4>Final Design</h4>
					<p class="small">Still a work in progress:</p>
					<div class="d-block">
						<a href="https://ctaylo37.github.io/elmo-demo/experiments" target="_blank" class="btn btn-primary">Demo</a>
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
					<li class="ml-3"><a href="#step-1" class="nav-link">MVP</a></li>
					<li class="ml-3"><a href="#step-2" class="nav-link">Interview & Sketch</a></li>
					<li class="ml-3"><a href="#step-3" class="nav-link">Prototyping</a></li>
					<li class="ml-3"><a href="#step-4" class="nav-link">Visual Design</a></li>
					<li class="ml-3"><a href="#step-5" class="nav-link">HTML Prototype</a></li>
					<li class="ml-3"><a href="#step-6" class="nav-link">Final Design</a></li>
					<li><a href="#more" class="nav-link">More Projects</a></li>
					<li class="dropdown-divider"></li>
					<li><a href="#top" class="nav-link"><i class="icon-up"></i> Top</a></li>
				</ul>
			</div>
		</div>
	</div>
</div>
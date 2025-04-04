---
title: "NSL Lab - Rajrup"
layout: personal
permalink: /people/rajrup-ghosh/
sitemap: false
excerpt: "Personal website of Rajrup"
---
{%- assign data = site.data.people -%}
{%- assign member = data.rajrup -%}

<div class="row">
  <img src="{{ site.url }}{{ site.baseurl }}/images/teampic/{{ member.photo }}" class="img-responsive" width="22%" style="float: left" />
  <h1>{{ member.name }}</h1>
  <i style="font-size:20px">{{ member.info }}</i><br>

  {% if member.website %}<a href="{{ member.website }}" target="_blank"><i class="fa fa-home fa-3x"></i></a> {% endif %}
  {% if member.email %}<a href="mailto:{{ member.email }}" target="_blank"><i class="fa fa-envelope-square fa-3x"></i></a> {% endif %}
  {% if member.scholar %} <a href="{{ member.scholar }}" target="_blank"><i class="ai ai-google-scholar-square ai-3x"></i></a> {% endif %}
  {% if member.cv %} <a href="{{ site.url }}{{ site.baseurl }}/files/{{ member.cv }}" target="_blank"><i class="ai ai-cv-square ai-3x"></i></a> {% endif %}
  {% if member.github %} <a href="{{ member.github }}" target="_blank"><i class="fa fa-github-square fa-3x"></i></a> {% endif %}
  {% if member.linkedin %} <a href="{{ member.linkedin }}" target="_blank"><i class="fa fa-linkedin-square fa-3x"></i></a> {% endif %}
  {% if member.twitter %} <a href="{{ member.twitter }}" target="_blank"><i class="fa fa-twitter-square fa-3x"></i></a> {% endif %}
  <!-- {% if member.researchgate %} <a href="{{ member.researchgate }}" target="_blank"><i class="ai ai-researchgate-square ai-3x"></i></a> {% endif %} -->
  <ul style="overflow: hidden">

  {% for education in member.education %}
	<li> {{ education }} </li>
  {% endfor %}

  </ul>
  <br/>
  Jump to [Biography](#biography), [Publications](#publications), [Experiences](#work-experience).
</div>

## Biography

<p>I am a Ph.D. student in <a href="http://nsl.usc.edu/">Networked System Lab (NSL)</a> at <a href="http://www.usc.edu">University of Southern California</a>. I am fortunate to be advised by <a href="https://govindan.usc.edu/">Prof. Ramesh Govindan</a>. My primary research interests are in areas of <b>Volumetric Video</b>, <b>AR/VR Streaming</b>, <b>Edge+Cloud Computing</b> and <b>Systems for ML</b>.</p>
<p>Prior to joining USC, I completed my Masters in Computational Science at the <a href="http://cds.iisc.ac.in">Department of Computational and Data Sciences (CDS)</a>, <a href="https://www.iisc.ac.in">Indian Institute of Science (IISc), Bangalore</a>. I was advised by <a href="http://cds.iisc.ac.in/faculty/simmhan">Prof. Yogesh Simmhan</a> at <a href="https://dream-lab.in/">DREAM:Lab</a>.</p>

## Work Experience

<p>
<em>Graduate Research Assistant (Aug 2019 - present)</em><br>
Department of Computer Science, University of Southern California.<br>
</p>

<p>
<em>Research Intern (May 2022 - Aug 2022)</em><br>
Microsoft Research, Redmond, Washington.<br>
Mentors: <a title="Krishna's Website" href="https://www.microsoft.com/en-us/research/people/krchinta/">Krishna Chintalapudi</a>, <a title="Nijunj's Website" href="https://www.microsoft.com/en-us/research/people/nikunjr/">Nikunj Raghuvanshi</a>, <a title="Ranveer's Website" href="https://www.microsoft.com/en-us/research/people/ranveer/">Ranveer Chandra</a><br>
</p>

<p>
<em>Research Intern (June 2020 - Aug 2020)</em><br>
Microsoft Research, Redmond, Washington.<br>
Mentor: <a title="Krishna's Website" href="https://www.microsoft.com/en-us/research/people/krchinta/">Krishna Chintalapudi</a><br>
</p>


<p>
<em>Lead Engineer (Research) (July 2017 - July 2019)</em><br>
Samsung R&D Institute India, Bangalore.<br>
</p>

## Teaching Experience

<p>
<em>Teaching Assistant at USC</em><br>
<b>Course:</b> <a href="https://drive.google.com/file/d/1l2-jZawdV2FZ4Q1pmCkLtvplA6DK9DUa/view?usp=sharing">CS 551/651: Advanced Computer Networks, Spring 2022</a>, <b>Instructor:</b> <a href="https://govindan.usc.edu/">Prof. Ramesh Govindan</a>
</p>
<p>
<em>Guest Lecture at Princeton University</em>, <b>Topic:</b> Volumetric Video Streaming <a href="https://docs.google.com/presentation/d/1e-stQ41GS9mVqCpU4H306geXiYHGJCNg-MalHcSzmfM/edit?usp=sharing">[PPT]</a><br>
<b>Course:</b> <a href="https://ml-video-seminar.princeton.systems/">COS 598a: Machine Learning-Driven Video Systems, Spring 2022</a>, <b>Instructor:</b> <a href="https://www.cs.princeton.edu/~ravian/">Prof. Ravi Netravali</a>
</p>

{% if member.awards %}
## Awards
{% endif %}

{% for award in member.awards %}
<ul style="overflow: hidden">
<li> {{ award }} </li>
</ul>
{% endfor %}

## Publications

<div class="publications">

{% bibliography -f people/rajrup%}

</div>

---
layout: page
title: Mental Health Advocacy
permalink: /mental-health/
---
<a class="button-4" href="{% link mentalhealth/talks.md %}">Register for a talk</a>
<a class="button-4" href="https://dev.us1.list-manage.com/subscribe?u=6620e1b56efbcddf42f62cb72&id=350ed7dd1e" target="_blank">Join mailing list</a>

I advocate for good mental health in academia, specifically the Research Software Engineering (RSE) community. I want to raise awareness of mental health, and create a place where people feel they can talk freely, without being judged. My work is supported by a <a href="https://www.software.ac.uk/about/fellows/dave-horsfall">Software Sustainability Institute (SSI) fellowship</a>, and by the <a href="https://society-rse.org/mental-health-in-research-software-engineering/">RSE Society</a>. 

## Interactive Mental Health Talks

I've developed an interactive presentation on mental health for people working in academia and research software. The session explores common stressors for software engineers and data scientists working in research, and gives people an opportunity to answer questions anonymously. My aim is to raise awareness of mental health in the workplace, and reduce the stigma of starting conversations about how we are feeling. I've presented the talk at <a href="{% link mentalhealth/talks.md %}">several organisations</a>, and I'd be delighted to run a session for your team too.

<blockquote class="blockquote">
  Dave gave a version of his talk at the Alan Turing Institute, as a visitor to our Tools, Practices and Systems coffee chat. It was a fantastic discussion, beautifully & compassionately delivered. Invite him to your org! (And keep the conversation going)
  <span class="quote-author">Kirstie Whitaker</span>
  <span class="quote-position">Programme Director, Alan Turing Institute</span>
</blockquote>

The presentation includes the following discussions:
* What is mental health?
* The problem of stigma
* Motivation for the discussion, including statistics from academia
* Common mental health stressors when working in research
* Preventative measures and self-care
* Description of conditions such as anxiety, depression and burnout
* The importance of accessing help and support 
* Advice on how to talk about mental health with your supervisor

I'm running my interactive presentation on mental health over Zoom. It is free for organisations and individuals to <a href="{% link mentalhealth/talks.md %}">register</a>.

<a class="button-4" href="{% link mentalhealth/talks.md %}">Register for a talk</a>

<h2>Previous Sessions</h2>
<div class="table">
  <div class="row header blue">
    <div class="cell">
      Organisation
    </div>
    <div class="cell">
      Title
    </div>
    <div class="cell">
      Date
    </div>
  </div>
  {% assign talks = site.data.talks | sort: "Date" | reverse %}
  {% for talk in talks %}
  <div class="row">
    <div class="cell" data-title="Organisation">
      {{ talk.Organisation }}
      {% if talk.Group %}
        <div class="meta">{{ talk.Group }}</div>
      {% endif %}
    </div>
    <div class="cell" data-title="Title">
      {{ talk.Title }}
    </div>
    <div class="cell" data-title="Date">
      {{ talk.Date }}
    </div>
  </div>
  {% endfor %}
</div>


 


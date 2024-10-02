---
permalink: /
title: "About me"
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

<!-- Use it like any other HTML element -->

<div class="video-container">
  <video controls loading="lazy" muted>
    <source src="assets/video/sizzle.mp4" type="video/mp4">
    Your browser does not support the video tag.
  </video>
</div>

## Portfolio (WIP --- bear with me :coffee:)

{% for post in site.portfolio %}
  {% include archive-single.html %}
{% endfor %}

## Biography
I am a lecturer in games and part-time PhD student working on sound rendering, computer graphics, and vision under the supervision of [Dr Carlo Harvey](https://www.bcu.ac.uk/computing/about-us/our-staff/carlo-harvey) and [Dr Maite Frutos](https://www.bcu.ac.uk/computing/about-us/our-staff/dr-maite-frutos-pascual), and the external help of [Dr Alan Dolhasz](https://www.linkedin.com/in/dolhasz/?originalSubdomain=uk).

### What I'm up to
I currently teach a range of modules within BSc Video Game Development at Birmingham City University. 

### Where I come from
I worked on several research projects as an intern at the DMT Lab. Among these was the [WMCA Serrano](https://www.bcu.ac.uk/computing/research/digital-media-technology/research-projects/a-vision-based-system-for-road-traffic-monitoring) project, in collaboration with the West Midlands Combined Authority, which developed methods of analysis for intelligent traffic monitoring technology based on computer vision. I obtained a first-class degree in BSc (Hons) in Sound Engineering and Production (2019) from Birmingham City University, taking advantage of the final year project to conduct a subjective study on auditory perception in virtual environments.

### Let's connect!
As part of my research, I have developed [my own spatialiser system](https://github.com/MattXV/DSPToolbox) for the Hololens 2 AR Headset as I needed one that included the ability to hot-swap HRTFs and had control over real-time convolutions. If you are an AR developer wanting to collaborate on spatial audio, or if want to talk research, get in touch! &#128512;

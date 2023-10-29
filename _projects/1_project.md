---
layout: page
title: Semantic Search
description: a Smart Alternative for Ctrl + F
img: assets/img/smartsearch.png
importance: 1
category: fun
related_publications: 
---

---
<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        <iframe
    width="640"
    height="480"
    src="https://www.youtube.com/embed/DYKoab0Cet4"
    frameborder="0"
    allow="autoplay; encrypted-media"
    allowfullscreen
>
</iframe>
    </div>
</div>

<div class="caption">
    Video Walkthrough
</div>

## Inspiration
One of our teammates pointed out that the search extension (ctrl +f ) on the web browser nowadays has limited usage since it only supports exact word searches. when browsing any academic report and essays online, authors will paraphrase and one word might have appeared in their synonym form. Therefore, we thought it would be helpful to create an extension on the browser to help us with a smarter search. For example, when we are trying to search the word "people", we also want to know where words like "humankind", "individuals" are located. This function will make our life easier when we are reading any academic resources. Moreover, with the advanced machine learning technology, we wanted to break the limit of the text-only search. We also want to search for specific images and time slots of the video that contains the information we want to search for. Thus, we created a chrome extension called Smart Search that can search with plain text, images, and video.

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/SSscreenshot.jpg" title="User Interface" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    a simple and clear User Interface
</div>

## Things we learned
Before this hackathon, all of us did not have any knowledge of chrome extension development and we were only familiar with web development in general. During the development and installation of this chrome extension, we were able to learn many technical skills including google cloud deployment, API utilization, image recognition, GitHub, and communication between different languages including Python and JavaScript. Since this project requires both front end and back end, we were also required to have the ability to communicate between team members and transfer data between each other. teamwork definitely played an important role during the process of development.

## How we built our project
Backend: we used google cloud to host our website, PyTorch for machine learning.
Frontend: we used [semantic UI](https://semantic-ui.com/) as a framework to create the user interface. [Jquery](https://https://jquery.com//)  was used as an external library as we wanted to manipulate DOM as we use the chrome extension. We also utilized [RapidAPI](https://rapidapi.com/Graydyn/api/synonyms/to)  get similar words and therefore to search.

## Challenge
One of the challenges during the development is time management. Since our application is required to use a trained machine learning model for recognizing images and videos, we were not able to train a suitable and efficient model specifically for this project. because of this, the search was not 100% accurate when searching with images and videos. Moreover, we were not familiar with APIs related to the chrome extension since this is our first time developing the chrome extension. We had to spend some time studying the infrastructure of the chrome extension.

## Try it Out
[GitHub Repo](https://github.com/boshenzh/SemanticSearch)
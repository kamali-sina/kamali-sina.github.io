---
permalink: /
title: "About me"
excerpt: "About me"
author_profile: true
redirect_from: 
 - /about/
 - /about.html
---

I'm Sina Kamali, a computer science master's student at the University of Waterloo. I'm currently researching under the supervision of Professor [Diogo Barradas](https://cs.uwaterloo.ca/~dbarrada/). My research intersects privacy enhancing tools and applied cryptography. I'm always finding new projects that I'm passionate about, and have been loving working in this line of research for the past few years.

## What are my research interests?

I'm interested in creating new **privacy-enhancing tools** with the help of **cryptography**. Both of these topics are areas that I greatly enjoy researching.

I don't have a specific preference when it comes to different topics in this area, and have loved working on a wide range of projects ranging from anonymous communication and trust systems to proxy schedulers and even cryptocurrencies.

## What are my other interests?

Ever since I learned about blockchains, I've been fascinated by the possibilities and capabilities they have. Recently, I'm more focused in other areas of applied cryptography. However, I might go back to the area if I find a project I feel motivated by.

I have also always been interested in games in all forms, from boardgames to videogames. I have developed a few games and love doing so. Although I have been less active in this field, I do hope to return to creating games as a hobby in the future. Checkout [Sins & Virtues](https://github.com/kamali-sina/Sins-Virtues-Legacy/tree/main) if you're interested in seeing what I've created in the past.

## Background

I first learned about programming in high school, but quickly realized I could create custom code to automate many of my daily tasks. I developed a passion for software development as I began to write more code throughout my studies and personal projects. I have developed several open-source projects which I encourage you to read more about on my [GitHub page](https://github.com/kamali-sina). I used to work as an undergraduate research assistant at the University of Tehran, focusing on applied cryptography and privacy-enhancing tools.

## Contact

Feel free to [contact me](mailto:thesinakamali@gmail.com) if you have any questions about me or my projects.

## Blog

<font size="3">
<div style="overflow-y: auto; max-height: 300px; padding-right: 10px; font-size: 15.5px;">
<ul>
    {% for post in site.posts %}   
    <li>
        <b>{{ post.date | date: "%B %e, %Y" }}</b>: <a href="{{ post.url }}">{{ post.title }}</a>
    </li>
    {% endfor %}
</ul>
</div>
</font>


---
permalink: /
title: "About me"
excerpt: "About me"
author_profile: true
redirect_from: 
 - /about/
 - /about.html
---

{% for post in site.posts %}   
    <h3><a href="{{ post.url }}">{{ post.title }}</a></h3>
    <!-- <p><small><strong>{{ post.date | date: "%B %e, %Y" }}</strong> . {{ post.category }} . <a href="http://kamali-sina.github.com{{ post.url }}#disqus_thread"></a></small></p>             -->
{% endfor %}


## Who am I?

I'm Sina Kamali, an undergraduate computer engineering student living in Tehran, Iran. I first learned about programming in high school, but quickly realized I could create custom code to automate many of my daily tasks. I developed a passion for software development as I began to write more code throughout my studies and personal projects. I have developed several open-source projects which I encourage you to read more about on my GitHub page. Today, I work as an undergraduate research assistant at the University of Tehran, focusing on network security, cryptocurrencies, and other related topics.

## What are my research interests?

Ever since I learned about blockchains, I've been fascinated by the possibilities and capabilities they have. Today I am interested in different topics in cryptocurrency and blockchain technologies, network security, cryptography, and computer networks.

## What are my other interests?

I have always been interested in games. I have developed a few games and love doing so. Although I have been less active in this field, I do hope to return to developing games as a hobby in the future.

## Contact

Feel free to contact me if you are interested in working with me or have any questions about me or my projects.

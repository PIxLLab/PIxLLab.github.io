# Play & Interactive Experiences for Learning Lab @ NMSU

Welcome to the web presence for the Play & Interactive Experiences (PIxL) Lab at New Mexico State University. Our work focuses on how we can use game design to better build systems for the real world. The PIxL Lab works at the intersection of games, human-computer interaction, and mixed reality, developing game experiences that educate and function as scientific experiments in HCI.

Our current work looks largely at how we can develop information technology support for disaster response contexts. Much of this derives from analyzing game designs and their player interfaces to understand what does and does not work for real-world interfaces. 

Prof. Phoebe O. Toups Dugas is PI; her contact information can be found at the [NMSU Computer Science site](https://computerscience.nmsu.edu/facultydirectory/individual-bio-pages/p-toups-dugas.html).

## Latest Posts

{% for post in site.posts limit:5 %}  
  <li><a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></li>  
{% endfor %}  

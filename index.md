---
layout: default
title: Tomás Fartaria
---    		
# {{ page.title }}

***

I'm living in Lisbon, Portugal with my wife, (1 month old) kid and dog.

I'm working in [Marionete]("https://marionete.co.uk/"), a big data, data science and devops consultancy company. They have several [partnerships]("https://marionete.co.uk/company/#partners") with major players and everybody here is super competitive and driven to improve. 
They are actually hiring so if you are interested in learning and working with the newest open-source tech, email me and I'll forward your CV.</p>

The technologies I am currently dealing with more are:
* Scala
* Apache Kafka
* Apache Cassandra

My interests now are:
* enjoying being a first-time father
* reading:
  * science fiction: [Cycle of Arawn]("https://www.goodreads.com/book/show/23359401-the-cycle-of-arawn?ac=1&from_search=true")
  * technical stuff: [AWS Certified Solutions Architect Official Study Guide]("https://www.safaribooksonline.com/library/view/aws-certified-solutions/9781119138556/")


This update was 8th of June 2017.

## Blog
<ul class="posts">
    {% for post in site.posts %}
        <li>
            <span>{{ post.date | date_to_string }}</span> > <a href="{{ post.url }}" title="{{ post.title }}">{{ post.title }}</a>
        </li>
    {% endfor %}
</ul>


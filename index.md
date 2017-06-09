---
layout: default
title: Tomás Fartaria
---    		

I'm living in Lisbon, Portugal with my wife, (1 month old) kid and dog.

I'm working in [Marionete]("https://marionete.co.uk/"), a big data, data science and devops consultancy company. They have several [partnerships]("https://marionete.co.uk/company/#partners") with major players and everybody here is super competitive and driven to improve. 
They are actually hiring so if you are interested in learning and working with the newest open-source tech, let me know.

What I am up to now:

@Wwork
* Python
* AWS (lambda, S3, and DynamoDB)
* watching:
  * [AWS re:Invent 2015](https://www.youtube.com/watch?v=1TvJCLl9NNg)
  * [Introduction to cloud computing with Amazon Web Services](https://www.safaribooksonline.com/library/view/introduction-to-cloud/9781771374118/video218653.html?autoStart=True)
  * [AWS Certified Developer - Associate Tutorial](https://www.safaribooksonline.com/library/view/aws-certified-developer/9781788298384/)

@home
* enjoying being a first-time father
* reading:
  * science fiction: [Cycle of Arawn]("https://www.goodreads.com/book/show/23359401-the-cycle-of-arawn?ac=1&from_search=true")
  * technical stuff: [AWS Certified Solutions Architect Official Study Guide]("https://www.safaribooksonline.com/library/view/aws-certified-solutions/9781119138556/")

***

# Blog

<ul>
    {% for post in site.posts %}
        <li><span>{{ post.date | date_to_string }}</span> > <a href="{{ post.url }}" title="{{ post.title }}">{{ post.title }}</a></li>
    {% endfor %}
</ul>

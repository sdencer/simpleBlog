---
layout: page
title: Hello Everyone!
tagline: I'm Sdencer
---


Welcome to my blog
Read [my homepage ](http://sdencer.github.io/)


## Update Author Attributes



      *title : My Blog
      *name : sdencer
      *email : sdencer@gmail.com




## Date

<p>latest doc</p>

　　<ul>

　　　　{% for post in site.posts %}

　　　　　　<li>{{ post.date | date_to_string }} <a href="{{ site.baseurl }}{{ post.url }}">{{ post.title }}</a></li>

　　　　{% endfor %}

　　</ul>

## Big data

'Big data is a broad term for data sets so large or complex that traditional data processing applications are inadequate. Challenges include analysis, capture, data curation, search, sharing, storage, transfer, visualization, and information privacy. The term often refers simply to the use of predictive analytics or other certain advanced methods to extract value from data, and seldom to a particular size of data set. Accuracy in big data may lead to more confident decision making. And better decisions can mean greater operational efficiency, cost reduction and reduced risk.

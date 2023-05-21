---
layout: post
title:  "Click here for product reviews"
author: sal
categories: [ Jekyll, tutorial ]
image: assets/images/12.jpg
featured: true
hidden: flase

<!-- Posts Index
================================================== -->
<section class="recent-posts">

    <div class="section-title">

        <h2><span>All Stories</span></h2>

    </div>

    <div class="row listrecent">

        {% for post in paginator.posts %}

        {% include postbox.html %}

        {% endfor %}

    </div>

</section>

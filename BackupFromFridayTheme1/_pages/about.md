---
layout: defaults/page
permalink: about.html
narrow: true
title: 블로그를 시작하며
images:
  - https://images.unsplash.com/photo-1421789665209-c9b2a435e3dc?ixlib=rb-0.3.5&ixid=eyJhcHBfaWQiOjEyMDd9&s=5b1016b885e7438c4633109d77368d4d&auto=format&fit=crop&w=1651&q=80
  - https://images.unsplash.com/photo-1476514525535-07fb3b4ae5f1?ixlib=rb-0.3.5&ixid=eyJhcHBfaWQiOjEyMDd9&s=468a8c18f5d811cf03c654b653b5089e&auto=format&fit=crop&w=1650&q=80
  - https://images.unsplash.com/photo-1504626835342-6b01071d182e?ixlib=rb-0.3.5&ixid=eyJhcHBfaWQiOjEyMDd9&s=975855d515c9d56352ee3bfe74287f2b&auto=format&fit=crop&w=1651&q=80
---
## 꿈
어려서부터 공상과학만화를 보고 자라서인지 우리 세대에는 어렸을 때 꿈을 이야기 하면 연애인보다는 과학자가 많았다.
만화책에서 보던 하늘을 날아다니는 자동차와 손에 들고 다니는 통신기기들 그리고 로봇 아니 로봇보다는 로보트를 만드는 그런 꿈들이 있었다.
나도 어렸을 때부터 그런 과학자가 되고 싶었지만 현재는 펌웨어 엔지니어가 되어 있다. 
나이가 들면서 그 때 과학만화에서 보던 기술들이 하나 둘 씩 현실에 나타나기 시작했고 아이폰이 나왔을 때는 바로 달려가 구입했을 정도로 아직은 그 꿈을 보면 약간은 흥분되는 것 같다.
예전엔 그런 기술들을 만드는 이들을 우러러 보았는데 더 늦기 전에 나도 그 곳에 발을 들여야겠다는 생각이 들기 시작했다.

## 그리고 미래
그저께 선배에게 전화가 왔다. 머신러닝을 함께 배워보지 않겠냐고, 그리고 우리도 열심히 살고 있다는 흔적을 남겨보지 않겠냐는 제안.
지금하고 있는 펌웨어 보다 더 매력적이고 꿈에 더 가깝고 더 흥분되는 일임은 분명한 것임에 우리는 약간 흥분하였고
지금 첫 발을 디뎌보려 한다.
이 곳은 그런 나와 그의 그런 꿈들을 적어보고 만들어 보는 공간이다.
블로그에 남기는 이 발자국들이 우리의 다짐들을 잊지 않기 위한 영양제가 되어 주길 바란다.
## What is it?

{% include components/intro.md %}

## Full Feature List

- Installation
  - Designed for Jekyll 3.8
  - Compatible with GitHub Pages
- Configuration
  - Useful data files to quickly generate the profile sidebar and site navigation
  - Easy to configure, minimal options, sensible defaults
- Styling
  - Styled with Bootstrap, proven to work cross-platform
  - Minimal additional SCSS to get in the way
  - Entirely customisable by tweaking the Boostrap SCSS variables
- Layout
  - 2 column layout
  - Context-sensitive sidebars for blogs, documentation pages and normal content
  - Narrow/wide page options
  - Responsive layout built in
  - Lots of helpful includes and components to build out your site
- JavaScript and Components
  - jQuery and Bootstrap JS included
  - Use all the Bootstrap components
- Other goodies
  - Entypo SVG icons included
  - Syntax highlighting for code fragments using Rougify for over 100 different languages
- Blog
  - A collection layout to build a blog with full support for tagging
  - Interactive tag filtering for the blog
- Projects
  - A layout to list your projects, with a documentation-like layout for each project
  - Table of contents generation for documentation pages
- Permalinks
  - Permalinks using baseurl throughout for deployment under a subdir or on GitHub pages
  - Permalinks using .html throughout for deployment to environments not using default directory indexes

## Examples

Here's some quick examples of what it can do.

### Code Highlighting

{% highlight javascript %}
var modulePattern = (function() {
    // your module code goes here
    var sum = 0 ;

    return {
        add:function() {
            sum = sum + 1;
            return sum;
        },
        reset:function() {
            return sum = 0;
        }
    }
}());
{% endhighlight %}

### Bootstrap Components

Here's a CSS component, it's an alert box with the info color:

<div class="alert alert-info">
    A simple info alert!
</div>

And this is a more sophisticated example, using the JS to include a carousel of images:

<div id="carouselExampleControls" class="carousel slide mb-4" data-ride="carousel">
    <div class="carousel-inner">
        {% for img in page.images %}
            <div class="carousel-item {% if forloop.first %}active{% endif %}">
                <img src="{{ img }}" class="d-block w-100" alt="">
            </div>
        {% endfor %}
    </div>
    <a class="carousel-control-prev" href="#carouselExampleControls" role="button" data-slide="prev">
        <span class="carousel-control-prev-icon" aria-hidden="true"></span>
        <span class="sr-only">Previous</span>
    </a>
    <a class="carousel-control-next" href="#carouselExampleControls" role="button" data-slide="next">
        <span class="carousel-control-next-icon" aria-hidden="true"></span>
        <span class="sr-only">Next</span>
    </a>
</div>

The spinner.

<div class="spinner-border text-dark mb-4" role="status">
  <span class="sr-only">Loading...</span>
</div>

### Icons

There's a suite of hundreds of Entypo icons included, here's just a few.

<div class="d-flex align-items-center mb-4">
    <span class="icon grey mr-2">
        {% include entypo/clock.svg %}
    </span>
    <span class="icon grey mr-2">
        {% include entypo/cycle.svg %}
    </span>
    <span class="icon grey mr-2">
        {% include entypo/chevron-up.svg %}
    </span>
    <span class="icon grey mr-2">
        {% include entypo/new-message.svg %}
    </span>
    <span class="icon grey mr-2">
        {% include entypo/shopping-cart.svg %}
    </span>
</div>



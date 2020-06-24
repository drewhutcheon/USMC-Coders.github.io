---
layout: splash
feature_row:
  - title: "Projects"
    excerpt: "Learn more about our projects."
    url: "/projects/"
    btn_label: "Go to Projects"
    btn_class: "btn--inverse"
  - title: "Learn to Code"
    excerpt: "Learn more about coding, DevSecOps, and enjoy our list of free courses."
    url: "/learn/"
    btn_label: "Start Learning"
    btn_class: "btn--inverse"
  - title: "USMC Software"
    excerpt: "Learn more about the Department of Defense software goals and enabling platforms on the Chief Software Officer's website."
    url: "https://software.af.mil"
    btn_label: "CSO Website"
    btn_class: "btn--inverse"
---
  
<br /><br />
![Marine Coders logo with #BuiltByMarines](/assets/images/Marine_Coders_Logo.jpg){: .align-center}  

<p align="center">We are a group of U.S. Marines who use code to improve the lives of our fellow Marines.</p>
<br /><br />
{% include feature_row %}
  
<h3 class="archive__subtitle">{{ site.data.ui-text[site.locale].recent_posts | default: "Recent Posts" }}</h3>

{% if paginator %}
  {% assign posts = paginator.posts %}
{% else %}
  {% assign posts = site.posts %}
{% endif %}

{% for post in posts %}
  {% include archive-single.html %}
{% endfor %}

{% include paginator.html %}

## Team Guidelines
* We build code to help Marines, they are our customers not our Pros/Cons or FITREPS!
* We open source as much as possible [cio.gov](https://sourcecode.cio.gov/OSS/) [code.mil](https://code.mil)
* We are responsible users of existing open source code
* We help each other


## Have questions or want to join us?
Send an email to NEED EMAIL ADDRESS, we would love to hear from you!

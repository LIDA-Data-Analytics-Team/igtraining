---
layout: default
title: IG Training
nav_exclude: true
pagination: true
---
<div class="docs">
  {% for post in paginator.posts %}
    <h2><a href="{{ post.url }}">{{ post.title }}</a></h2>
    <p>{{ post.excerpt }}</p>
  {% endfor %}
</div>

<div class="pagination">
  {% if paginator.previous_page %}
    <a href="{{ paginator.previous_page_path }}">Previous</a>
  {% endif %}
  
  {% if paginator.next_page %}
    <a href="{{ paginator.next_page_path }}">Next</a>
  {% endif %}
</div>

# Welcome

These are the information governance training modules for non University of Leeds staff members who needs to be granted access to LASER TREs. Access to LASER is dependent on completion of the two modudles in this training - [Data Protection](https://lida-data-analytics-team.github.io/igtraining/modules/dataprotection.html) and [Information Security](https://lida-data-analytics-team.github.io/igtraining/modules/informationsecurity.html). 

Please use the navigation menu to select the module to complete them. There are knowledge check test to be completed at the end of each module. The pass mark to the test is 80%, you can take multiple attempts until you achive your desired score.

Do send a screenshot of your final score to the email address below.

If you have any comments or suggestions for these pages please feel free to contact a member of the Data Analytics Team at [dat@leeds.ac.uk](mailto:dat@leeds.ac.uk)

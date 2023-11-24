<div id="flex-body">
{% if course_code %}<nav id="site-nav" class="fixed-header-padding">
    <div class="nav-component slim-scroll">
      <site-nav>
* [Course Info]({{baseUrl}}/admin/{{ course_code }}.html)
* [Schedule]({{baseUrl}}/schedule/index-{{ course_code }}.html)
* [Projects/Mentors]({{baseUrl}}/admin/mentors.html)
* Students :expanded:
  * [CS3281]({{ students_site }}/index.html)
  * [CS3282]({{ students_site }}/cs3282-index.html)
* [Dashboard]({{ dashboard_site }})
* [Call for Applications]({{baseUrl}}/admin/callForApplications.html)
      </site-nav>
    </div>
  </nav>{% endif %}
  <div id="content-wrapper" class="fixed-header-padding">
    {{ content }}
  </div>
  <nav id="page-nav" class="fixed-header-padding">
    <div class="nav-component slim-scroll">
      <page-nav />
    </div>
  </nav>
</div>

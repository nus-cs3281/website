<div id="flex-body">
{% if module_code %}<nav id="site-nav" class="fixed-header-padding">
    <div class="nav-component slim-scroll">
      <site-nav>
* [Module Info]({{baseUrl}}/admin/{{ module_code }}.html)
* [Schedule]({{baseUrl}}/schedule/index-{{ module_code }}.html)
* [Projects/Mentors]({{baseUrl}}/admin/mentors.html)
* [Students]({{ students_site }})
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
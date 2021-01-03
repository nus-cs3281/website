<header>
<navbar placement="top" type="primary">
  <a slot="brand" href="{{baseUrl}}/index.html" title="Home" class="navbar-brand">[CS3281&2 - {{ year }}]</a>

  <dropdown header="CS3281" class="nav-link">
    <li><a href="{{baseUrl}}/admin/cs3281.html" class="dropdown-item">Module Info</a></li>
    <li><a href="{{baseUrl}}/schedule/index-cs3281.html" class="dropdown-item">Schedule</a></li>
    <li><a href="{{baseUrl}}/admin/mentors.html"class="dropdown-item">Projects/Mentors</a></li>
    <li><a href="{{ students_site }}" target="_blank"class="dropdown-item">Students</a></li>
    <li><a href="{{ dashboard_site }}/" target="_blank"class="dropdown-item">Dashboard</a></li>
  </dropdown>
  <dropdown header="CS3282" class="nav-link">
    <li><a href="{{baseUrl}}/admin/cs3282.html" class="dropdown-item">Module Info</a></li>
    <li><a href="{{baseUrl}}/schedule/index-cs3282.html" class="dropdown-item">Schedule</a></li>
    <li><a href="{{ students_site }}/students/talksSchedule.html" target="_blank"class="dropdown-item">Lightning Talks Schedule</a></li>
  </dropdown>
  <li><a href="{{baseUrl}}/admin/callForApplications.html"class="nav-link">Call for Applications</a></li>
  <li><a href="https://github.com/nus-cs3281/website" class="nav-link">{{ fab_github }}</a></li>
  <li slot="right" class="nav-link">
    <form class="navbar-form">
      <searchbar :data="searchData" placeholder="Search" :on-hit="searchCallback" menu-align-right ></searchbar>
    </form>
  </li>
</navbar>
</header>

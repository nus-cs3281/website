<header>
<navbar placement="top" type="primary">
  <a slot="brand" href="{{baseUrl}}/index.html" title="Home" class="navbar-brand">[CS3281&2 - {{ year }}]</a>
  <li><a href="{{baseUrl}}/schedule/index.html" class="nav-link">Schedule</a></li>
  
  <li><a href="{{baseUrl}}/admin/cs3281.html" class="nav-link">CS3281</a></li>
  <li><a href="{{baseUrl}}/admin/cs3282.html" class="nav-link">CS3282</a></li>
  <dropdown text="Links" class="nav-link">
    <li><a href="{{baseUrl}}/admin/callForApplications.html"class="dropdown-item">Call for Applications</a></li>
    <li><a href="{{baseUrl}}/admin/mentors.html"class="dropdown-item">Mentors</a></li>
    <li><a href="{{ students_site }}" target="_blank"class="dropdown-item">Students</a></li>
    <li><a href="{{ dashboard_site }}/" target="_blank"class="dropdown-item">Dashboard</a></li>
    <li><a href="{{ students_site }}/students/talksSchedule.html" target="_blank"class="dropdown-item">Lightning Talks Schedule</a></li>
    <li><a href="https://se-education.org/learningresources/" target="_blank"class="dropdown-item">se-edu/learningresources</a></li>
  </dropdown>
  <li><a href="https://github.com/nus-cs3281/website" class="nav-link">{{ fab_github }}</a></li>
  <li slot="right" class="nav-link">
    <form class="navbar-form">
      <searchbar :data="searchData" placeholder="Search" :on-hit="searchCallback" menu-align-right ></searchbar>
    </form>
  </li>
</navbar>
</header>

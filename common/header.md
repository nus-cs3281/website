<navbar placement="top" type="inverse">
  <a slot="brand" href="{{baseUrl}}/index.html" title="Home" class="navbar-brand">[CS3281&2 - AY1718S2]</a>
  <li><a href="{{baseUrl}}/schedule/index.html">Schedule</a></li>
  
  <li><a href="{{baseUrl}}/admin/cs3281.html">CS3281</a></li>
  <li><a href="{{baseUrl}}/admin/cs3282.html">CS3282</a></li>
  <dropdown text="Links">
    <li><a href="{{baseUrl}}/admin/callForApplications.html">Call for Applications</a></li>
    <li><a href="{{baseUrl}}/admin/mentors.html">Mentors</a></li> 
    <li><a href="https://github.com/nus-cs3281/2018/blob/master/students/studentlist.md" target="_blank">Students</a></li>
    <li><a href="https://docs.google.com/document/d/1I67ovHJp7ES96YupZyiuvVuVlqC5t5qimLduOH8MCF0/edit?usp=sharing" target="_blank">Project Ideas</a></li>
  </dropdown> 
  <li slot="right">
    <form class="navbar-form">
        <typeahead :data="searchData" placeholder="Search" :template="titleTemplate" template-name="title" :on-hit="searchCallback"></typeahead>  
    </form>
  </li>  
</navbar>

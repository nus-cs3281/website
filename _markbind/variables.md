<variable name="year">2025</variable>
<variable name="AY">24/25</variable>
<variable name="is_pre_sem"></variable>
<variable name="cs3281_time">MON 1200-1400</variable>
<variable name="cs3281_venue">COM1-02-12</variable>
<variable name="cs3282_time">THU 1400-1600</variable>
<variable name="cs3282_venue">COM1-02-12</variable>
<variable name="course_org">https://github.com/nus-cs3281</variable>
<variable name="course_site">https://nus-cs3281.github.io</variable>
<variable name="students_repo">{{ course_org }}/{{ year }}</variable>
<variable name="students_site">{{ course_site }}/{{ year }}</variable>
<variable name="dashboard_repo">{{ course_org }}/{{ year }}-dashboard</variable>
<variable name="dashboard_site">{{ course_site }}/{{ year }}-dashboard/?search=&sort=groupTitle&sortWithin=title&timeframe=commit&mergegroup=&groupSelect=groupByAuthors&breakdown=false</variable>


<variable name="previous_year">{{ (year | int) -1 }}</variable>
<variable name="icon_deadline">:alarm_clock:</variable>
<variable name="icon_dislike">:fas-thumbs-down:</variable>
<variable name="icon_example">:fas-cube:</variable>
<variable name="icon_embedding">:glyphicon-log-in:</variable>
<variable name="icon_exercise">:fas-dumbbell:</variable>
<variable name="icon_evidence">:fas-briefcase:</variable>
<variable name="icon_info">:fas-info-circle:</variable>
<variable name="icon_individual">:fas-user:</variable>
<variable name="icon_lecture">:glyphicon-blackboard:</variable>
<variable name="icon_like">:fas-thumbs-up:</variable>
<variable name="icon_linux">:fab-linux:</variable>
<variable name="icon_important_red"><span class="text-danger">:glyphicon-exclamation-sign:</span></variable>
<variable name="icon_important">:glyphicon-exclamation-sign:</variable>
<variable name="icon_new_window">:glyphicon-new-window:</variable>
<variable name="icon_outcome">:fas-trophy:</variable>
<variable name="icon_output">:fas-arrow-down:</variable>
<variable name="icon_output_right">:fas-arrow-right:</variable>
<variable name="icon_print">:glyphicon-print:</variable>
<variable name="icon_prereq">:glyphicon-education:</variable>
<variable name="icon_preview">:glyphicon-eye-open:</variable>
<variable name="icon_Q">:glyphicon-question-sign:</variable>
<variable name="icon_Q_A">{{ icon_Q | safe }}:glyphicon-ok-sign:</variable>
<variable name="icon_resource">:fas-paperclip:</variable>
<variable name="icon_tangential"><span class='badge badge-pill badge-secondary'>tangential</span></variable>
<variable name="icon_team">:fas-users:</variable>
<variable name="icon_terminal"><smal><span class="badge badge-secondary">&gt;_</span></smal></variable>
<variable name="icon_text">:far-file-alt:</variable>
<variable name="icon_tick">:fas-check:</variable>
<variable name="icon_tick_green"><span style="color:green">{{ icon_tick | safe }}</span></variable>
<variable name="icon_tip"><span class="badge badge-pill badge-warning">:fas-lightbulb:</span></variable>
<variable name="icon_todo">:glyphicon-check:</variable>
<variable name="icon_tutorial">:fas-chalkboard-teacher:</variable>
<variable name="icon_slides">:far-images:</variable>
<variable name="icon_video">:glyphicon-facetime-video:</variable>
<variable name="icon_windows">:fab-windows:</variable>
<variable name="icon_x">:fas-times:</variable>
<variable name="icon_x_red"><span style="color:red">{{ icon_x | safe }}</span></variable>
<variable name="bad"><font color="red"><md>**{{ icon_dislike | safe }} Bad**</md></font></variable>
<variable name="good"><font color="green"><md>**{{ icon_like | safe }} Good**</md></font></variable>

---
title: "소방자격증 수험일정"
layout: page
permalink: /소방설비/학습일정
---
  
# 소방자격증 수험일정  
  
<div class="mermaid"> 
gantt
  title 2023 수험일정  
  dateFormat  YYYY-MM-DD

  section 소방설비기사(전기)
  필기 준비       :done,             전필준, 2023-01-01, 56d
  필기 시험(1회)  :milestone, done,  전필시, 2023-02-26, 1d
  실기 준비       :crit,             전실준, after 전필준, 55d
  실기 시험(1회)  :milestone, crit,  전실시, 2023-04-23, 1d

  Section 소방설비기사(기계)
  
  필기 준비       :crit,             기필준, 2023-04-24, 30d
  필기 시험(2회)  :milestone, crit,  기필시, 2023-05-25, 1d
  실기 준비       :                  기실준, 2023-05-30, 52d
  실기 시험(2회)  :milestone, crit,  기실시, 2023-07-23, 1d
  실기 시험(4회)  :milestone, crit,  기실시4, 2023-11-04, 1d
  
  Section 전기공사기사 필기
  
  필기 준비       :     공필준, 2023-07-24, 
  필기 시험(4회)  :     공필시, 2023-09-10
  
  
  section Critical tasks
  Completed task in the critical line :crit, done, 2014-01-06,24h
  Implement parser and jison          :crit, done, after des1, 2d
  Create tests for parser             :crit, active, 3d
  Future task in critical line        :crit, 5d
  Create tests for renderer           :2d
  Add to mermaid                      :1d

  section Documentation
  Describe gantt syntax               :active, a1, after des1, 3d
  Add gantt diagram to demo page      :after a1  , 20h
  Add another diagram to demo page    :doc1, after a1  , 48h

  section Last section
  Describe gantt syntax               :after doc1, 3d
  Add gantt diagram to demo page      :20h
  Add another diagram to demo page    :48h
</div>

---
title: "소방설비"
layout: archive
permalink: /소방설비
---

## 자격증 수험일정  
<div class="mermaid"> 
%%{init: {'theme':'dark'}}%%
gantt
  title 2023 수험일정  
  dateFormat  YYYY-MM-DD
  axisFormat %m월
  tickInterval 1month

  section 소방설비기사(전기)
  필기 준비       :done,             FE_Cbt_Study, 2023-01-01, 56d
  필기(1회 02/26)  :milestone, done,  FE_Cbt_Test, 2023-02-26, 1d
  실기 준비       :done,             FE_Write_Study, after FE_Cbt_Test, 55d
  실기(1회 04/23)  :milestone, done,  FE_Write_Test, 2023-04-23, 1d

  Section 소방설비기사(기계)
  필기 준비       :crit,             FM_Cbt_Study, 2023-06-01, 90d
  필기(4회 09/10)  :milestone, crit,  FM_Cbt_Test, 2023-09-10, 1d
  실기 준비       :                  FM_Write_Study, 2023-05-30, 52d
  실기(4회 11/04)  :milestone, crit,       FM_Write_Test, 2023-11-04, 1d
  
</div>

## 포스트
{% assign posts = site.categories['소방설비'] %}
{% for post in posts %} {% include archive-single.html type=page.entries_layout %} {% endfor %}


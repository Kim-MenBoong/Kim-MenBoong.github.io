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
  필기 준비       :done,             FE_Cbt_Study, 2023-01-01, 56d
  필기 시험(1회)  :milestone, done,  FE_Cbt_Test, 2023-02-26, 1d
  실기 준비       :crit,             FE_Write_Study, after FE_Cbt_Test, 55d
  실기 시험(1회)  :milestone, crit,  FE_Write_Test, 2023-04-23, 1d

  Section 소방설비기사(기계)
  필기 준비       :crit,             FM_Cbt_Study, 2023-04-24, 30d
  필기 시험(2회)  :milestone, crit,  FM_Cbt_Test, 2023-05-25, 1d
  실기 준비       :                  FM_Write_Study, 2023-05-30, 52d
  실기 시험(2회)  :milestone, crit,  FM_Write_Test, 2023-07-23, 1d
  실기 시험(4회)  :milestone,        FM_Write_Test4, 2023-11-04, 1d
  
  Section 전기공사기사 필기
  필기 준비       :                  EL_CBT_Study, 2023-07-24, 48d
  필기 시험(4회)  : milestone,       EL_CBT_Test, 2023-09-10, 1d
</div>

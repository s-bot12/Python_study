# Python_study


### 1. 문자열 관련 함수들
--------------------

 <span class="evidence"> a = "hobby" </span>
  
    - a.count('b')     => 2
    - a.find('b')      => 2 (없으면 -1)
    - a.find('b')      => 2 (없으면 error)
    - a.upper()        => 'HOBBY'
    - a.lower()        => 'hobby'
    - ",".join(a)      => 'h,o,b,b,y'
  
  a = "     hobby     "
  1-7) a.rstrip()       => '     hobby'
  1-8) a.lstrip()       => 'hobby     '
  1-9) a.strip()        => 'hobby'
  
  a = "Life is too short"
  1-10) a.replace("Life", "Your leg")    => 'Your leg is too short'
  1-11) a.split()                       => ['Life', 'is', 'too', 'short']
  

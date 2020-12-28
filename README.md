# Python_study


### 1. 문자열 관련 함수들
--------------------

  a = "hobby" 
  
    - a.count('b')     => 2
    - a.find('b')      => 2 (없으면 -1)
    - a.find('b')      => 2 (없으면 error)
    - a.upper()        => 'HOBBY'
    - a.lower()        => 'hobby'
    - ",".join(a)      => 'h,o,b,b,y'
  
  a = "     hobby     " 
  
    - a.rstrip()       => '     hobby'
    - a.lstrip()       => 'hobby     '
    - a.strip()        => 'hobby'
  
  a = "Life is too short"
  
    - a.replace("Life", "Your leg")    => 'Your leg is too short'
    - a.split()                        => ['Life', 'is', 'too', 'short']
  

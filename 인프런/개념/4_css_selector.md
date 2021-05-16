# CSS Selector
1. * : 전체 selector
    - 예전 reset.css
2. 태그 selector
3. ID selector(#)
4. class selector(.)
5. attribute selector []
  - [속성] {color:red;}
  - [속성~=값]{color:red;} 
  - [속성|=값]{color:red;} 
  - [속성^=값]{color:red;}
  - [속성$=값]{color:red;}
  - [속성*=값]{color:red;}
  - css selector 조합
    .클래스명1.클래스명2.클래스명3
6. 복합 selector
  - 후손:스페이스 (바로다음이 아니니 기호없이 스페이스인가보다)
  - 자식:> (자식새끼한테는 뾰족하고 바로 다음 셀렉터)
  - 인접형제:+ (동일위치니까 유유상종 so 1+1)
  - 일반형제:~ (일반적으로 형제는 동일한 위치이고 바로 다음 관계이지 ~)
7. 가상 클래스 셀렉터 : 요소에 이벤트 발생시 선택
  - link <-> visited
  - active
  - hover
  - focus : input 태그에 커서 깜빡
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
---------------------------------------------
  - 구조 가상 클래스 셀렉터 (1이 첫번째 요소)
    - first-child
    - last-child
    - nth-child
    - nth-last-child
---------------------------------------------
  - 셀렉터에 해당하는 요소만 뽑아서 서수로 취급
    - first-of-type
    - nth-of-type
    - nth-last-of-type
---------------------------------------------
  - 부정 셀렉터 : not(셀렉터)
---------------------------------------------
  - 정합성 체크 셀렉터
    - valid : 정합성이 검증된 input/form 요소선택 (<-> invalid)
      - required : input 태그 입력창에 무조건 입력
      - pattern : input태그에 입력한 데이터 포맷이 맞으면 정합성이 검증됬다고 판단
8. 가상 요소 셀렉터
  - first-letter
  - first-line
  - after
  - before
  - selection

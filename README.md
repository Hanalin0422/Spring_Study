- 각 chapter별로 진행 상황이 다름 
  1. chapter1 - 인텔리제이 초기 설정완료함
  2. chpter2 - 테스트 코드를 작성하여 간단하게 mvc 패턴을 유지하며 hello 화면에 찍기
  3. chpater3 - h2DB를 통해 데이터 CRUD 되는거 잘 동작하는지 테스트 코드까지 작성하여 확인함.
  4. chapter4 - 게시글 CRUD 동작 수행을 머스테치를 이용해 직접 확인
     1. 서버 템플릿 엔진에 대해서 배움
     2. 서버 구현이 잘 되었는지 확인하는 방법에는 test 코드 작성 혹은 머스테치를 이용해 직접 눈으로 확인하는 방법 두 가지 
     3. 어떤 기능에 대한 service를 만들고 @Transactional 어노테이션을 붙여 코드의 원자성, 일관성, 격리성, 지속성을 유지시킴
     4. 그 다음 그 service에서 구현한 함수를 사용하기 위해 controller가 이어주는 방식인것
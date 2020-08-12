<H2>팀프로젝트"아트옥션"</H2>


<H4>1. 기획의도</H4>
  "나는 취미로 도자기를 굽거나 목공예를 배워 책상을 만들기도 한다.   
  이것저것 만들다보니 내가 정성들여 만든 공예품들을 팔고싶어졌다.   
  그래서 손쉽게 판매할 수 있는 아트옥션이라는 경매 사이트를 찾게되었다.   
  경매로 올리니 내 작품이 이정도의 가치가 있었던건가? 싶어 너무 뿌듯하다."   
  
  이런 의도로 아트옥션이라는 사이트를 만들게 되었습니다.
  
<H4>2. 사용한 기술 및 라이브러리</H4>
  
  - spring framework <br>
  - tomcat <br>
  - oracle <br>
  - html, css, jQuery <br>
  - 쿼츠 라이브러리<br>
  
<H4>3. 개발 기간</H4>
  - 3주
  
<H4>4. 담당한 부분</H4>
  
  <H5>- mypage</H5>
  
    1) 내가 입찰한 상품과 내가 판매중인 상품들의 최종 낙찰가, 현재 나의 입찰가격이 어떻게 되는지 확인이 가능.
    2) 낙찰된 상품의 현재 거래상태, 판매하는 상품의 현재 거래상태들을 구분하여 확인할 수 있도록 함.
    3) 내 정보 변경 : ID, 이름을 제외한 나의 정보를 변경할 수 있음.
  
  <H5>- 상세보기 페이지(getPage)</H5>
    
    1) 입찰을 할 수 있는 페이지.
    2) 상품의 사진과 내용 확인가능.
    3) 입찰을 하고 현재 입찰 최고가는 얼만지, 최고가로 입찰한 사람은 누구인지 확인이 가능.
    4) 비회원일 경우 입찰 불가능, 방금 입찰한 회원인 경우엔 중복입찰 불가능, 판매자인 경우에도 입찰이 불가능함.
    5) 스케줄링을 사용해 매 1분마다 경매 종료시간이 지난 상품들은 마감된 상품으로 변경할 수 있도록 작업.
    6) 마감된 상품은 최종 낙찰자와 최종 낙찰액을 확인하여 거래가 진행될 수 있도록 작업.
    
<H4>5. 개인적으로 추가 개발할 부분</H4>
   -팀원들과 협의하여 각자의 우선순위를 두고 작업을 하였다. 그렇기 때문에 작업하며 추가로 진행해 보고 싶은 내용들이 있었는데,
    프로젝트 마무리 후 하나하나씩 개발을 해볼 생각이다.
   
    1) 구글, 카카오톡 API연동을 통한 로그인 기능
    2) 마이페이지 입찰/판매 내역 페이징 처리
    3) 웹소켓을 이용해 상태변경 시 쪽지로 alert 주기
    
    
    

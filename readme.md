**개요**  
서비스 명: 스타일 추천  
서비스 설명: 사용자로부터 이름, 나이, 성별, 원하는 스타일을 입력받으면 스타일 추천 ai가 원하는 최고의 스타일을 추천해준다.  
서비스 접속 주소: https://l2j2young.github.io/style  

**서비스 구성 요소(1) -Gemini API**  
구글의 LMM 모델 Gemini API를 활용해 생성한다.  
활용모델: Gemini-2.0-flash  

**서비스 구성 요소(2)-프론트엔드**  
스타일 추천 AI는 HTML,CSS,JavaScript로 구성되었다.  
요즘 유행하는 가나디 이미지를 넣어서 귀엽게 구성했다.  

**서비스 구성 요소 (3)**  
API키가 노출되지 않도록 프론트엔드의 요청을 받아 Gemini API를 호출해주는 API백엔드를 구성했다.  
코드 및 참고 구현 내용은 https://github.com/l2j2young/l2j2young-style-api 를 참고한다.  

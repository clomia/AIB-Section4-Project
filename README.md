자연어처리(NLP) 프로젝트에 사용하기 위한 소설 텍스트 데이터를 수집합니다.  
셀레니움을 사용한 스크레핑을 합니다.  
Google Play Books에서 직접 구매한 책(인간 본성의 법칙)을 스크래핑 할 것이며  
해당 책의 내용을 분석해보는 방향으로 생각하고 있습니다.  

>
    Book2Vec:.
    ├─93 (크롬 드라이버 위치)
    ├─DATA
    │  ├─books
    │  ├─corpus
    │  ├─model
    │  └─vectors
    |
    ├env ...(env/requirements.txt 참조)
    |
    ├─GooglePlayBook_Scanner
    │  ├─data
    │  │  └─인간 본성의 법칙
    │  │      ├─JPG
    │  │      ├─PDF
    │  │      └─TXT
    │  ├─main_process
    │  │  
    │  ├─start
    ├─processing
    └─spatialization
        ├─src
        └─books
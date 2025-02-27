# ✨ 쇼핑몰 통계 데이터 백오피스

<br>

`쇼핑몰 솔루션 회사의 백오피스 프로젝트로, 코드가 없는 프로젝트 설명 페이지입니다.`

---------------------------------
### ✔️ 기능 설명:
- 고객의 쇼핑몰마다 이용중인 옵션 현황을, 페이지 내 테이블 형식 또는 엑셀 파일로 제공합니다.
- 검색에서 시작일 & 마지막일을 선택할 수 있습니다.
- 검색에서 일별, 월별, 연도별을 선택할 수 있습니다. 
- 검색에서 카테고리를 선택할 수 있습니다. (결제수단이나 부가서비스 등등)
- 기간별 추이와 당일 점유율 차트를 제공합니다.
---------------------------------
### ✔️ 기술 설명:
- mysql db에 통계 데이터를 저장할 `테이블을 설계`합니다.
- `cron`이 매일 쇼핑몰 데이터를 `통계 데이터로 가공 후 저장하는 스케줄링`을 구현합니다.
- html과 css로 `페이지의 view`를 구현합니다.
- `서버와의 비동기 데이터 통신`을 위해 AJAX와 jQuery를 사용합니다.
- `php`로 서버 로직을 구현합니다.
- https://github.com/ParkJuhan94/create_dummy_data 를 통해 `더미 데이터를 자동으로 만들어` 테스트 했습니다.
---------------------------------
### ✔️ 각 기능과 페이지 <br><br><br>
- 통계 검색  <br><br>
![KakaoTalk_20221121_114741873_01](https://user-images.githubusercontent.com/81701212/202976932-dcc73487-36fa-45f2-851d-1f041f3a9418.png)

<br><br><br><br><br>

-  페이지 내 테이블 형식 또는 엑셀 파일로 제공  <br><br>
![KakaoTalk_20221121_114741873_02](https://user-images.githubusercontent.com/81701212/202976961-309401b4-0304-4085-8137-4e2d9afc62d6.png)

<br><br><br><br><br>
- 기간별 추이와 당일 점유율 차트 <br><br>
![KakaoTalk_20221121_114741873](https://user-images.githubusercontent.com/81701212/202976967-f52bdd0f-446a-4fd1-a008-cccd09d0191b.png)
<img width="566" alt="스크린샷 2023-04-14 오전 9 32 58" src="https://user-images.githubusercontent.com/81701212/231911657-f9e33e0a-2e4a-4af1-a01b-fc53281fc89c.png">

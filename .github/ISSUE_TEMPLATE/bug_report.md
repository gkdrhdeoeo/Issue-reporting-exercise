---
name: Bug report
about: "[AOS/iOS] 이슈발생"
title: ''
labels: bug
assignees: gkdrhdeoeo

---

**Describe the bug**
A clear and concise description of what the bug is.

**To Reproduce**
Steps to reproduce the behavior:
1. Go to '...'
2. Click on '....'
3. Scroll down to '....'
4. See error

**Expected behavior**
A clear and concise description of what you expected to happen.

**Screenshots**
If applicable, add screenshots to help explain your problem.

**Desktop (please complete the following information):**
 - OS: [e.g. iOS]
 - Browser [e.g. chrome, safari]
 - Version [e.g. 22]

- 사전조건 : BO > 로그인 / FO > APP로그인

- 테스트데이터
1) 전시상품코드 : S00100709561
2) 전시 상품명 : 노출가격 확인 테스트
3) 상품등록시간 : 2023-05-30 14:07:42
4) 상품확인시간 : 2023-05-30 15:08 (등록후 1시간1분 뒤)

- 재현절차 :
1. 테스트 데이터의 상품을 전시한 상태 > 상품에 노출할 뱃지를 2개 설정
2. 설정한 뱃지가 2개까지는 정상노출되는지 확인

- 기대결과 :
2. 2개까지는 설정한 뱃지가 전시화면 상세화면 모두 노출되어야 한다. 

- 심각도 : Major

- 발생빈도 : Always

※ 테스트환경
1) BO > PC 웹 브라우저 : 크롬
2) FO > OS Ver. : AOS13, IOS16
3) 골핑 APP Ver. : 2.0.7_(AOS), 2.0.3(1)_IOS

※ 첨부파일
설정한 뱃지_전시화면 및 상세화면 비교.mp4

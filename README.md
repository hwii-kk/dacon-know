# dacon-know

[데이콘](https://dacon.io/)이 주최한 KNOW기반 직업 추천 알고리즘 경진대회 참가

기간: 2021.12.06~2022.01.28

**각 직업 종사자들의 설문 조사를 바탕으로 설문 조사에 응답한 내용을 토대로 직업을 예측해보는 대회로 직업을 추천해주는 알고리즘을 개발한다**

결측치들을 설문 문항들의 관계성을 이용하여 최대한 관계있게 전처리하고 피쳐링하였고 Catboost 분류기 model을 사용해보았다.

macro-f1 score 약 0.63으로 상위 7.7%의 성적을 기록(28/360)

자세한 내용은 [코드](https://github.com/hwii-kk/dacon-know/tree/main/code)와 [결과보고서](https://github.com/hwii-kk/dacon-know/blob/main/know%20%EC%A7%81%EC%97%85%20%EC%B6%94%EC%B2%9C%20%EC%95%8C%EA%B3%A0%EB%A6%AC%EC%A6%98.pdf)를 참고해주세요.

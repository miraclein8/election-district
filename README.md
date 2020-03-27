선거구 geojson
============

우리나라에는 지역을 구분하는 법정동과 행정동을 기준으로 나누고 있습니다. (이번에 알게 되었습니다.)

선거구 지역획정에는 행정동을 기준으로 분할하고 있습니다.

이 자료는 아래 출처에서 데이터를 가져와 작성하고 있습니다.


## 자료 출처
- 공공데이터포털 중앙선거관리위원회 코드정보: https://www.data.go.kr/dataset/15000897/openapi.do
- 대한민국 행정동 경계(admdongkor): https://github.com/vuski/admdongkor


## 20200415_2 자료 설명
### 2020년 4월 국회의원 선거
- sgId: "20200415" // 선거 코드
- sgTypecode: "2" // 선거 종류 (국회의원 선거)
- sOrder: *.geojson // 선거구 코드
- sdName: // 시도 이름
- sggName: // 선거구명

작업시 참고사항)
+ 성수2가1동과 성수2가3동은 있는데, 성수2가2동은 없다. (cf. 자양4동)
+ 성북구에는 성북동이 있다.

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

### 서울특별시
<table>
    <tr>
        <th></th>
        <th>선거구명</th>
        <th>구시군명</th>
        <th>읍면동명</th>
    </tr>
    <tr>
        <th>1</th>
        <th>종로구</th>
        <td>종로구</td>
        <td>청운효자동, 사직동, 삼청동, 부암동, 평창동, 무악동, 교남동, 가회동, 종로1·2·3·4가동, 종로5·6가동, 이화동, 혜화동, 창신제1동, 창신제2동, 창신제3동, 숭인제1동, 숭인제2동
        </td>
    </tr>
    <tr>
        <th>2</th>
        <th>중구성동구갑</th>
        <td rowspan="2">성동구</td>
        <td>응봉동, 성수1가제1동, 성수1가제2동, 성수2가제1동, 성수2가제3동, 왕십리도선동, 왕십리제2동, 행당제1동, 행당제2동, 마장동, 사근동, 송 정동, 용답동</td>
    </tr>
    <tr>
        <th>3</th>
        <th rowspan="2">중구성동구을</th>
        <td>금호1가동, 금호2·3가동, 금호4가동, 옥수동</td>
    </tr>
    <tr>
        <td>중구</td>
        <td>소공동, 회현동, 명동, 필동, 장충동, 광희동, 을지로동, 신당동, 다산동, 약수동, 청구동, 신당제5동, 동화동, 황학동, 중림동</td>
    </tr>
    <tr>
        <th>4</th>
        <th>용산구</th>
        <td>용산구</td>
        <td>후암동, 용산2가동, 남영동, 청파동, 원효로제1동, 원효로제2동, 효창동, 용문동, 한강로동, 이촌제1동, 이촌제2동, 이태원제1동, 이태원제2동 , 한남동, 서빙고동, 보광동</td>
    </tr>
    <tr>
        <th>5</th>
        <th>광진구갑</th>
        <td rowspan="2">광진구</td>
        <td>중곡제1동, 중곡제2동, 중곡제3동, 중곡제4동, 능동, 구의제2동, 광장동, 군자동</td>
    </tr>
    <tr>
        <th>6</th>
        <th>광진구을</th>
        <td>구의제1동, 구의제3동, 자양제1동, 자양제2동, 자양제3동, 자양제4동, 화양동</td>
    </tr>
    <tr>
        <th>7</th>
        <th>동대문구갑</th>
        <td rowspan="2">동대문구</td>
        <td>용신동, 제기동, 청량리동, 회기동, 휘경제1동, 휘경제2동, 이문제1동, 이문제2동</td>
    </tr>
    <tr>
        <th>8</th>
        <th>동대문구을</th>
        <td>전농제1동, 전농제2동, 답십리제1동, 답십리제2동, 장안제1동, 장안제2동</td>
    </tr>
    <tr>
        <th>9</th>
        <th>중랑구갑</th>
        <td rowspan="2">중랑구</td>
        <td>면목본동, 면목제2동, 면목제3·8동, 면목제4동, 면목제5동, 면목제7동, 상봉제2동, 망우제3동</td>
    </tr>
    <tr>
        <th>10</th>
        <th>중랑구을</th>
        <td>상봉제1동, 중화제1동, 중화제2동, 묵제1동, 묵제2동, 망우본동, 신내제1동, 신내제2동</td>
    </tr>
    <tr>
        <th>11</th>
        <th>성북구갑</th>
        <td rowspan="2">성북구</td>
        <td>성북동, 삼선동, 동선동, 돈암제2동, 안암동, 보문동, 정릉제1동, 정릉제2동, 정릉제3동, 정릉제4동, 길음제1동</td>
    </tr>
    <tr>
        <th>12</th>
        <th>성북구을</th>
        <td>돈암제1동, 길음제2동, 종암동, 월곡제1동, 월곡제2동, 장위제1동, 장위제2동, 장위제3동, 석관동</td>
    </tr>
    <tr>
        <th>13</th>
        <th>강북구갑</th>
        <td rowspan="2">강북구</td>
        <td>번1동, 번2동, 수유1동, 수유2동, 수유3동, 우이동, 인수동</td>
    </tr>
    <tr>
        <th>14</th>
        <th>강북구을</th>
        <td>삼양동, 미아동, 송중동, 송천동, 삼각산동, 번3동</td>
    </tr>
    <tr>
        <th>15</th>
        <th>도봉구갑</th>
        <td rowspan="2">도봉구</td>
        <td>쌍문1동, 쌍문3동, 창1동, 창2동, 창3동, 창4동, 창5동</td>
    </tr>
    <tr>
        <th>도봉구을</th>
        <td>쌍문2동, 쌍문4동, 방학1동, 방학2동, 방학3동, 도봉1동, 도봉2동</td>
    </tr>
    <tr>
        <th>노원구갑</th>
        <td rowspan="3">노원구</td>
        <td>월계1동, 월계2동, 월계3동, 공릉1동, 공릉2동</td>
    </tr>
    <tr>
        <th>노원구을</th>
        <td>하계1동, 하계2동, 중계본동, 중계1동, 중계2·3동, 중계4동, 상계6·7동</td>
    </tr>
    <tr>
        <th>노원구병</th>
        <td>상계1동, 상계2동, 상계3·4동, 상계5동, 상계8동, 상계9동, 상계10동</td>
    </tr>
    <tr>
        <th>은평구갑</th>
        <td rowspan="2">은평구</td>
        <td>녹번동, 응암제1동, 응암제2동, 응암제3동, 역촌동, 신사제1동, 신사제2동, 증산동, 수색동</td>
    </tr>
    <tr>
        <th>은평구을</th>
        <td>불광제1동, 불광제2동, 갈현제1동, 갈현제2동, 구산동, 대조동, 진관동</td>
    </tr>
</table>

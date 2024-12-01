﻿## 원본 레포지토리 : https://github.com/vuski/admdongkor

- 이 레포지토리는 원본의 jeojson 확장자를 json 확장자로 변환한 것입니다

## 파일 버젼

- ver20241001

  - 2024년 8월 1일 경상북도 성주군 금수면이 금수강산면으로 명칭변경되었습니다.

- ver20240701

  - 2024년 7월 1일 경기도 의정부시 송산1동이 송산1동과 고산동으로 분할되었습니다.

- ver20240401

  - 2024년 1월 18일 전라북도가 전북특별자치도로 명칭변경되었습니다. 행정동코드(adm_cd2) 앞 두 자리가 52로 시작합니다.
  - 2024년 2월 1일 경상북도 예천군 호명면이 호명읍으로 승격되었습니다.
  - 2024년 12월 27일 서울특별시 강서구 가양제1동과 방화제3동의 경계가 조정되었습니다.(지연 통보)

- ver20240101

  - 2024년 1월 1일 울산광역시 중구 복산1동과 복산2동이 복산동으로 통합되었습니다.
  - 2024년 1월 1일 광주광역시 북구 중흥2동과 중흥3동이 중흥동으로 통합되었습니다.
  - 2024년 1월 1일 인천광역시 중구 영종1동이 영종1동과 영종2동으로 분할되었습니다.
  - 2024년 1월 1일 경기도 안양시 만안구 석수동이 충훈동으로, 동안구 관양1동과 관양2동이 각각 관양동과 인덕원동으로 명칭 변경되었습니다.
  - 2024년 1월 1일 경기도 오산시 대원동이 대원1동과 대원2동으로 분할되었습니다.
  - 2024년 1월 1일 경기도 오산시 신장동이 신장1동과 신장2동으로 분할되었습니다.
  - 2024년 1월 1일 경기도 부천시가 부천시 원미구, 부천시 소사구, 부천시 오정구로 회귀 분할되면서 모든 행정동 분할되고 이름과 코드 역시 변경되었습니다.

- ver20231231

  - 2023년 10월 10일 경기도 양주시 회천4동이 폐지되고 옥정1동과 옥정2동으로 분할(신설)되었습니다.
  - 2023년 10월 30일 인천광역시 서구 연희동과 가정1동의 행정동 코드가 변경되었습니다.

- ver20231001

  - 2023년 7월 3일 경기도 시흥시 정왕2동이 정왕2동과 거북섬동으로 분할되었습니다.
  - 기존 7자리 행정동 코드(adm_cd)를 항목을 속성에서 삭제하였습니다. 8자리 행정동 코드의 이름을 adm_cd8에서 adm_cd로 변경하였습니다.

- ver20230701

  - 2023년 4월 13일 세종특별자치시 도담동이 도담동과 어진동으로 분할되었습니다.
  - 2023년 4월 29일 경기도 과천시 갈현동이 갈현동과 원문동으로 분할되었습니다.
  - 2023년 5월 1일 경기도 하남시 풍산동의 이름이 미사3동으로 변경되었습니다.
  - 2023년 6월 11일 강원도의 이름이 강원특별자치도로 변경되었습니다. 관련 코드들도 변경되었습니다.
  - 2023년 6월 29일 인천광역시 남동구 구월2동과 간석2동의 경계가 조정되었습니다.
  - 2023년 7월 1일 경상북도 군위군이 대구광역시로 편입되었습니다.
  - 2023년 7월 1일 경기도 화성시 동탄7동이 동탄7동과 동탄9동으로 분할되었습니다.

- ver20230401

  - 2023년 1월 9일 경기도 파주시 운정4동, 운정5동, 운정6동이 신설되고 다른 행정동 경계가 조정되었습니다.
  - 2023년 2월 24일 광주광역시 광산구 법정동 경계가 조정되었습니다. 이에 따른 행정동 경계 조정 여부는 불명확하지만, 광산 imap(https://imap.gwangsan.go.kr/imap/home/programs/tongmap/index?menu=226)을 바탕으로 기존과 차이나는 경계들을 맞춰주었습니다. 행정동 코드가 일부 수정되었습니다.
  - 2023년 3월 30일 세종특별자치시 새롬동이 새롬동과 나성동으로 분할되었습니다.
  - 읍면동을 시군구로, 시군구를 시도 경계로 dissolve 할 때 일부 경계끼리의 미세한 불일치로 폴리곤 잔여물이 남는 문제가 있어, 전체적으로 경계들을 다시 맞춰주었습니다.

- ver20230101

  - 2022년 12월 23일 서울 강남구 일원2동의 명칭이 개포3동으로 변경되었습니다(경계불변, 코드는 변경)
  - 2022년 12월 31일 전라남도 화순군 화순읍에 민원출장소가 신설되면서 화순읍의 코드가 변경되었습니다.(경계 불변)

- ver20221001

  - 2022년 9월 1일 경기도 광주시 오포읍이 오포1동, 오포2동, 신현동, 능평동으로 승격 및 4분할 되었습니다.

- ver20220701

  - 2022년 6월 20일 대전광역시 서구 가수원동이 가수원동과 도원동으로 분할되었습니다.
  - 2022년 7월 1일 세종시 연기면, 새롬동, 해밀동, 연동면, 반곡동의 경계가 상호간에 조정되었습니다.
  - ver20220401, ver20220309, ver20220101 에서 세종시 소담동과 반곡동의 위치가 뒤바뀐 것을 수정했습니다.

- ver20220401

  - 2022년 4월 1일 부산광역시 기장군 일광면이 일광읍으로 승격되었습니다.
  - 일광읍과 3월 9일 변동된 행정구역에 대해 통계청 7자리, 8자리 코드를 업데이트 했습니다.

- ver20220309

  - 2022년 3월 9일 대한민국 20대 대통령선거의 읍면동 선거구와 일치하는 버젼입니다.
  - 선거관리위원회에서 사용하는 코드 및 이름의 경우, 속성 테이블에 ELEC\_ 접두어가 붙어 있습니다.
  - 2022년 1월 3일 경기도 고양시 덕양구 삼송동이 삼송1동과 삼송2동으로 분할되었습니다. 동시에 흥도동과 경계가 조정되었습니다.
  - 2022년 1월 3일 경기도 고양시 덕양구 행신3동이 행신3동과 행신4동으로 분할되었습니다.
  - 2022년 1월 3일 경기도 고양시 일산동구 중산동이 중산1동과 중산2동으로 분할되었습니다.
  - 2022년 1월 3일 경기도 고양시 일산서구 탄현동이 탄현1동과 탄현2동으로 분할, 송산동이 덕이동과 가좌동으로 동이름 변경 및 분할되었습니다.
  - 통계청 코드는 아직 부여되지 않았으므로 변경된 행정동 코드의 뒷자리를 xx및 xxx로 두었습니다. (adm_cd 및 acm_cd8)
  - 행안부 코드 10자리(adm_cd2)는 정상적으로 부여되어 있습니다.

- ver20220101

  - 2021년 10월 25일 경기도 평택시 비전1동이 비전1동과 동삭동으로 분할되었습니다.
  - 2021년 10월 26일 세종특별자치시 소담동이 소담동과 반곡동으로 분할되었습니다.
  - 2021년 11월 1일 대전광역시 유성구 진잠동, 원신흥동, 온천1동이 진잠동, 원신흥동, 온천1동, 학하동, 상대동으로 분할되면서 경계가 조정되었습니다.
  - 2021년 11월 2일 강원도 영월군 중동면의 명칭이 산솔명으로 변경되었습니다.
  - 2021년 11월 15일 충청남도 천안시 서북구 불당동이 불당1동과 불당2동으로 분할되었습니다.
  - 2021년 11월 17일 경기도 평택시 고덕면이 고덕면과 고덕동으로 분할되었습니다. 주변 몇몇 행정동의 일부가 고덕동으로 편입되면서 경계가 조정되었습니다.
  - 2021년 11월 29일 대구광역시 달서구 월성1동과 진천동이 월성1동, 진천동, 유천동으로 분할되면서 경계가 조정되었습니다.
  - 2021년 11월 29일 경기도 광명시 소하2동이 소하2동과 일직동으로 분할되었습니다.
  - 2021년 12월 31일 경기도 여주시 능서면의 명칭이 세종대왕면으로 변경되었습니다.
  - 20190908 이후의 모든 파일에서 동탄6동과 동탄7동의 10자리 행정동코드 오류를 수정했습니다.
  - 20200401 이후의 모든 파일에서 의정부1동과 의정부3동이 통합되지 않았던 오류를 수정했습니다.
  - 20200701 이후의 모든 파일에서 하남시 감북동 행정동코드 오류를 수정했습니다.
  - 20210101 이후의 모든 파일에서 구미시 비산동 행정동코드 오류를 수정했습니다.
  - 통계청에서 새로 공표한 8자리 행정동코드를 adm_cd8 컬럼에 추가했습니다. 앞으로 7자리를 폐지하고 8자리로 대체한다고 하니 통계청의 안내를 참고하시기 바랍니다.

- ver20211001

  - 2021년 7월 5일 경기도 시흥시 배곧동이 배곧1동과 배곧2동으로 분할되었습니다.
  - 2021년 7월 26일 광주광역시 남구 효덕동이 효덕동과 진월동으로 분할되었습니다.
  - 2021년 9월 6일 경기도 용인시 처인구 역삼동이 역북동과 삼가동으로 분할, 죽전1동이 죽전1동과 죽전3동으로 분할, 상현1동이 상현1동과 상현3동으로 분할되었습니다.
  - 2021년 9월 28일 세종특별자치시 도담동이 도담동과 해밀동으로 분할되었습니다.

- ver20210701

  - 2021년 6월 1일 인천광역시 서구 원당동이 원당동과 아라동으로 분할되었습니다.
  - 2021년 6월 1일 강원도 홍천군 동면의 이름이 영귀미면으로 변경되었습니다.
  - 2021년 7월 1일 서울특별시 강동구 강일동이 강일동과 상일제2동으로 분할되었습니다. 상일동은 상일제1동으로 명칭변경되었습니다.
  - 2021년 7월 1일 인천광역시 중구 북성동과 송월동이 개항동으로 통합되었습니다.
  - 2021년 7월 1일 경기도 군포시 대야동이 대야동과 송부동으로 분할되었습니다.
  - 2021년 7월 1일 경기도 파주시 군내면, 장단면, 진동면, 진서면이 장단면으로 통합되었습니다.
  - 2021년 7월 1일 경상북도 구미시 원평1동과 원평2동이 원평동으로 통합되었습니다.
  - 2021년 7월 1일 경상남도 창원시 의창구 용지동이 창원시 성산구 용지동으로 변경되었습니다.(용지동의 소속 자치구 변경)
  - 접경지역 경계 폴리곤을 다소 조정하였습니다.

- ver20210401

  - 2021년 2월 19일 경기도 용인시 처인구의 남사면이 남사읍으로 승격되었습니다.
  - 2021년 4월 1일 경상북도 경주시 양북면이 문무대왕면으로 명칭변경되었습니다.

- ver20210101

  - 2020년 10월 26일 인천광역시 연수구 송도4동이 송도4동과 송도5동으로 분할 되었습니다.
  - 2020년 11월 1일 울산광역시 울주군 삼남면이 삼남읍으로 승격되었습니다.
  - 2020년 12월 1일 경기도 광주시 경안동이 경안동과 쌍령동으로 분할,
  - 2020년 12월 1일 경기도 광주시 송정동이 송정동과 탄벌동으로 분할,
  - 2020년 12월 1일 경기도 광주시 광남동이 폐지되고 광남1동과 광남2동으로 분할되면서 신설되었습니다.
  - 2021년 1월 1일 강원도 양구군 남면이 국토정중앙면으로 명칭변경되었습니다.
  - 2021년 1월 1일 경상북도 구미시 산동면이 산동읍으로 승격,
  - 2021년 1월 1일 경상북도 구미시 비산동과 공단1동이 비산동으로 통합,
  - 2021년 1월 1일 경상북도 구미시 공단2동이 공단동으로 명칭변경되었습니다.
  - 2021년 1월 1일 경상북도 군위군 고로면이 삼국유사면으로 명칭변경되었습니다.

- ver20201001

  - 2020년 7월 6일 대구광역시 동구 안심3.4동이 안심3동, 안심4동, 혁신동으로 분할되었습니다.
  - 2020년 7월 6일 대구광역시 동구 불로봉무동과 지저동 사이의 경계가 조정, 신암1동과 신암4동 사이의 경계가 조정되었습니다.
  - 2020년 7월 15일 세종특별자치시 연기면 지역 일부가 도담동으로 편입되었습니다.(경계조정)
  - 2020년 7월 15일 세종특별자치시 금남면과 연동면 지역 일부가 소담동으로 편입되었습니다.(경계조정)
  - 2020년 7월 20일 경상북도 구미시 행정동 간의 경계가 일부 조정되었습니다.(경계조정)
  - 2020년 7월 27일 광주광역시 북구 건국동이 건국동과 신용동으로 분할,
  - 2020년 8월 14일 세종특별차지시 새롬동이 새롬동과 다정동으로 분할되었습니다.

- ver20200701

  - 2020년 4월 20일 경기도 하남시 감북동이 감북동과 감일동으로 분할되었습니다.
  - 세종시 일부 토폴로지 오류를 수정하였습니다.

- ver20200401 + 20200515

  - 2020년 1월 6일 경기도 의정부시 의정부1동과 의정부3동이 의정부1동으로 통합,
  - 2020년 1월 13일 경기도 의정부시 송산2동이 송산2동과 송산3동으로 분할,
  - 2020년 1월 20일 경기도 용인시 기흥구 영덕동이 영덕1동과 영덕2동으로 분할,
  - 2020년 1월 20일 경기도 용인시 기흥구 상갈동이 상갈동과 보라동으로 분할,
  - 2020년 1월 20일 경기도 용인시 기흥구 동백동이 동백1동, 동백2동, 동백3동으로 분할,
  - 대구광역시 달성군 현풍읍의 통계청 코드 미반영 오류를 정정,
  - 전라북도 김제시 만경읍과 성덕면 사이의 토폴로지 오류를 수정하였습니다.
  - 통계청의 재수정으로 경상남도 사천시 벌룡동의 이름이 벌용동으로 정정, 시흥시 장곡동 관할구역 경계가 일부 변경되었습니다.

- ver20200101

  - 2020년 1월 1일에 다수의 행정동이 변경되었습니다.
  - 서울특별시 구로구 오류2동이 오류2동과 항동으로 분할,
  - 부산광역시 금정구 장전2동, 장전3동이 장전2동으로 통합,
  - 경상남도 창원시 마산합포구 교방동과 노산동이 교방동으로 통합,
  - 경상남도 창원시 진해구 중앙동, 태평동, 충무동이 충무동으로 통합,
  - 전라남도 화순군 북면과 남면이 각각 백아면과 사평면으로 이름 변경,
  - 경상북도 경산시 압량면이 압량읍으로 승격,
  - 경상북도 상주시 사벌면이 사벌국면으로 이름 변경되었습니다.

- ver20191231

  - 2019년 10월 21일 경기도 화성시 동탄6동이 동탄6동과 동탄8동으로 분할되었습니다.
  - 2019년 11월 4일 인천광역시 서구 당하동이 당하동과 마전동으로 분할되었습니다.
  - 통계청 2020년 1월 1일 공지파일에 2019년 12월 31일과 2020년 1월 1일을 구분해 놓았으므로 이 자료에서도 동일하게 구분하였습니다.

- ver20191001

  - 2019년 9월 23일 경기도 김포시 구래동이 구래동과 마산동으로 분할되었습니다.
  - 2019년 9월 30일 경기도 평택시 비전2동이 비전2동과 용이동으로 분할되었습니다.
  - 2019년 10월 1일 전라북도 전주시 덕진구 동산동의 이름이 여의동으로 변경되었습니다.
  - 통계청에서 변경이력을 1년에 정기적으로 네 번(1.1, 4.1, 7.1, 10.1) 공지합니다. 앞으로 업데이트는 공지한 날짜의 변경분까지 반영할 예정입니다.

- ver20190908

  - 2019년 4월 15일 경기도 수원시 영통구 태장동이 망포1동과 망포2동으로 분할되었습니다.
  - 2019년 7월 1일 경기도 화성시 동탄6동이 동탄6동과 7동으로 분할되었습니다.
  - 2019년 7월 1일 충청북도 진천군 덕산면이 덕산읍으로 승격되었습니다.
  - 2019년 7월 1일 경기도 부천시의 행정동이 10개 행정동으로 통폐합되었습니다.
  - 2019년 7월 1일까지 변경된 행정동의 adm_cd 속성에는 새로 부여된 7자리코드를 적었습니다.
  - 2019년 7월 1일까지 변경된 행정동의 adm_cd2 속성에는 모두 변경된 10자리 코드로 수정했습니다.

- ver20190403

  - 2019년 1월 1일 인천광역시 연수구 송도2동이 송도2동과 송도 4동으로 분할되었습니다.
  - 2019년 2월 19일 전라남도 담양군 남면의 이름이 가사문학면으로 변경되었습니다. (경계 불변)
  - 2019년 3월 1일 경상북도 청송군 부동면의 이름이 주왕산면으로 변경되었습니다. (경계 불변)
  - 2019년 4월 1일까지 변경된 행정동의 adm_cd 속성에는 새로 부여된 7자리코드를 적었습니다.
  - 2019년 4월 1일까지 변경된 행정동의 adm_cd2 속성에는 모두 변경된 10자리 코드로 수정했습니다.
  - 서울특별시 마포구 합정동과 서교동의 꼬인 경계를 수정하였습니다.

- ver20181106

  - 2018년 9월 27일 경기도 의정부시 가능1동의 이름이 가능동으로 명칭변경되었습니다. (경계 불변)
  - 2018년 10월 1일 부산광역시 금정구 금사동의 이름이 금사회동동으로 명칭변경되었습니다. (경계 불변)
  - 2018년 10월 8일 경기도 시흥시 정왕4동이 정왕4동과 배곧동으로 분할되었습니다.
  - 2018년 11월 1일 대구광역시 달성군 옥포면과 현풍면이 옥포읍과 현풍읍으로 승격되었습니다. (경계 불변)
  - 2018년 11월 5일 인천광역시 남동구 장수서창동이 장수서창동과 서창2동으로 분할되었습니다.
  - 2018년 10월 1일까지 변경된 행정동의 adm_cd 속성에는 새로 부여된 7자리코드를 적었으며, 그 이후 변경된 행정동의 마지막 두자리는 알파벳으로 처리하였습니다.
  - 2018년 11월 5일까지 변경된 행정동의 adm_cd2 속성에는 모두 변경된 10자리 코드로 수정했습니다.

- ver20180724

  - 2018년 7월 23일까지 변경된 모든 행정동에 10자리 행정기관코드를 추가하였습니다. (adm_cd2 필드 참고)
  - 2018년 7월 1일 경기도 고양시 덕양구 신도동이 삼송동으로 명칭 변경되었습니다. (경계 불변)
  - 2018년 7월 1일 인천광역시 서구 행정동 명칭이 5건 변경되었습니다. (경계 불변)
  - 2018년 7월 1일 전라북도 전주시 완산구 효자4동이 효자4동,효자5동,덕진구 혁신동으로 3분할 되었습니다.
  - 2018년 7월 1일 인천광역시 남구가 인천광역시 미추홀구로 명칭 변경 되었습니다. (경계 불변)
  - 2018년 7월 16일~23일에 세종특별자치시 보람동이 보람동, 대평동, 소담동으로 3분할 되었습니다.
  - 2018년 7월 1일까지 변경된 행정동은 새로 부여된 코드를 적었으며, 그 이후 변경된 행정동 코드의 마지막 두자리는 알파벳으로 처리하였습니다.

- ver20180401

  - 2018년 4월 1일 울산광역시 울주군 청량면이 청량읍으로 명칭 변경되었습니다. (경계 불변)
  - 2018.6.13 제7회 전국동시지방선거의 행정동 경계로 사용할 수 있습니다. 중앙선거관리위원회 홈페이지에서 청량면 -> 청량읍 변동분까지 반영된 것을 확인하였습니다.

- ver20180301

  - 2017년 12월 11일 경기도 용인시 처인구 모현면과 이동면이 모현읍과 이동읍으로 변경되었습니다. (경계 불변)
  - 2017년 12월 18일 경기도 남양주시 다산1동과 다산2동이 신설되면서 영역과 명칭이 세부적으로 조정되었습니다.
  - 2017년 12월 26일 경기도 수원시 영통구 영통1,2동이 조정되고 영통3동이 신설되었습니다.
  - 2018년 1월 1일 부산광역시 강서구 명지동이 명지1,2동으로 분동되었습니다.
  - 2018년 1월 1일 인천광역시 중구 영종동이 영종동과 영종1동으로 분동되었습니다.
  - 2018년 1월 22일 경기도 화성시 새솔동이 신설되고 동탄 4,5,6동이 조정되었습니다.
  - 2018년 3월 1일 대구광역시 달성군 유가읍이 유가면으로 변경되었습니다.
  - 2018년 1월 1일까지 변경된 행정동은 새로 부여된 코드를 적었으며, 그 이후 변경된 행정동 코드의 마지막 두자리는 알파벳으로 처리하였습니다.

- ver20171016

  - 2017년 8월 1일까지 변경된 행정동의 7자리 코드를 채워넣었습니다. 2017년 10월 1일에 통계분류포털에 업데이트 된 행정구역분류코드를 이용하였습니다.
  - 2017년 10월 16일 세종특별자치시 한솔동이 한솔동과 새롬동으로 나뉘었습니다.
  - 변경된 행정동의 코드의 마지막 두자리는 알파벳으로 처리하였습니다.(통계청관리 코드를 아직 알 수 없음)

- ver20170801

  - 2017년 7월 17일 경기도 안산시상록구와 안산시단원구의 일부 행정동의 명칭이 변경되었습니다. 원곡본동의 경우 원곡동과 신길동으로 나뉘었습니다.
  - 2017년 8월 1일 충청남도 홍성군 홍북면이 홍북읍으로 변경되었습니다.

- ver20170418

  - 2017년 4월 18일에 변경된 경기도 김포시 김포본동, 장기본동까지 반영되어 있습니다.
  - 2017년 5월 대통령선거에 사용가능한 버젼입니다.
  - 중앙선거관리위원회에서 사용하는 행정동 이름과 매칭시킬 수 있는 csv를 동봉하였습니다.
  - 통계청 파일에서 수정한 경계(실제 행정구역도와 대조함, 행정구역 변경 이력과는 별개임)
    - 서울특별시 송파구 위례동, 경기도 성남시 수정구 위례동, 경기도 하남시 위례동의 경계 부근
    - 부산광역시 해운대구
    - 경기도 시흥시의 오이도 부근

- ver20160201

  - 2016년 2월 1일까지의 변경부분이 반영되어 있습니다.
  - 2016년 4월 국회의원 선거에 사용가능한 버젼입니다.
  - 중앙선거관리위원회에서 사용하는 행정동 이름과 매칭시킬 수 있는 csv를 동봉하였습니다.
    - 통계청 행정동과 선관위 행정동은 '제1동' 등에서 차이나는 것이 있습니다.
    - 선거구 획정에 따라 선관위 관할구역이 행정구와 일치하지 않는 경우가 있습니다(중앙선관위 선거통계시스템 FAQ참고). 해당 값들을 매칭시켰습니다.
    - 위의 두 경우는 csv의 '특이사항' 필드에 1로 표시하여 두었습니다.
  - 통계청 파일에서 수정한 경계(실제 행정구역도와 대조함, 행정구역 변경 이력과는 별개임)
    - 서울특별시 송파구 위례동, 경기도 성남시 수정구 위례동, 경기도 하남시 위례동의 경계 부근
    - 부산광역시 해운대구

- ver20121210
  - 2012년 12월 10일까지의 변경부분이 반영되어 있습니다.
  - 2012년 12월 대통령선거에 사용가능한 버젼입니다.

## 속성의 adm_cd

- 20230701 버젼까지는 7자리의 코드로 이루어졌고, 8자리 코드는 adm_cd8 이라는 필드이름으로 관리되었으나,
- 20231001 버젼부터는 7자리 코드를 삭제하고 adm_cd8을 adm_cd로 필드명 변경하여 사용합니다.
- 통계청에서 사용하는 8자리의 [한국행정구역분류코드]입니다.
- [2자리 시도]+[3자리 시군구]+[3자리 읍면동] 으로 이루어집니다.
  - 따라서, 코드의 특정 문자열들을 이용하여, dissolve로 병합하면 시도 경계나 시군구 경계 파일을 만들 수 있습니다.
  - dissolve 방법은 아래 mapshaper에 설명해 두었습니다.
- 행정동 경계가 변하면 행정동 이름이 그대로이더라도 코드가 변경됩니다.

## 속성의 adm_cd2

- 행정안전부(행정자치부, 안전행정부 등 이름이 바뀌어도 *행정*부)에서 사용하는 10자리의 행정기관코드입니다.
- [2자리 시도]+[3자리 시군구]+[3자리 읍면동]+[2자리 행정리] 로 이루어집니다.
  - 따라서, 코드의 특정 문자열들을 이용하여, dissolve로 병합하면 시도 경계나 시군구 경계 파일을 만들 수 있습니다.
  - 행정동 이외에 출장소에도 코드가 부여되어 있습니다.
- 행정동 경계가 변해도 행정동 이름이 그대로이면 코드가 변경되지 않습니다.

## 참고 : 행정동 관련 정보

- 2024년 10월 현재, 과거 행정동 경계 파일을 제공하는 곳은 통계청 통계지리정보서비스와 브이월드 디지털트윈 국토, 도로명주소지도가 있습니다.
  - 통계청 통계지리정보서비스 : https://sgis.kostat.go.kr/view/pss/openDataIntrcn
  - 로그인 후 자료신청을 통해 받을 수 있습니다.
  - 2021년 12월 현재 1975~2020년 까지 받을 수 있습니다.
- 최근 업데이트 된 행정동 경계 파일은 브이월드에서도 다운받을 수 있습니다.
  - https://www.vworld.kr/dtmk/dtmk_ntads_s002.do?searchKeyword=%EC%84%BC%EC%84%9C%EC%8A%A4&searchOrganization=&searchBrmCode=&searchTagList=&searchFrm=&pageIndex=1&gidmCd=&gidsCd=&sortType=00&svcCde=MK&dsId=30017&listPageIndex=1
  - 경계 좌표의 해상도가 매우 자세합니다. 경계의 위상도 그럭저럭 어긋남 없이 잘 맞습니다.
  - 다만 데이터의 업데이트 시점이 다소 늦습니다. 6개월 주기 혹은 1년 주기로 업데이트 되는 것 같습니다.
- 도로명주소지도에서 받을 수 있는 지도의 경우 이 글의 상단에 자세히 적어놓았습니다.

- 선거 득표 등 특정한 시점의 이벤트를 행정동에 빠짐 없이 맵핑하려면 세세한 행정구역 변경 이력을 확인해야 합니다.
- 행정구역분류 코드 및 변경 이력은 1년에 4번, 분기별로 통계청에 업데이트 됩니다.
  - http://kssc.kostat.go.kr → 사이트맵 → 기타분류 → 한국행정구역분류 → 자료실
  - 이 곳의 자료로 통계청의 [8자리 행정구역분류코드], 행안부의 [10자리 행정표준코드관리시스템 코드], [10자리 법정동 코드]를 매칭시킬 수 있습니다.
  - 이 곳의 자료에서 과거 행정구역 변경 이력을 알 수 있습니다.
  - 0번 시트에 행정동 코드에 대한 설명이 있습니다.
- 연중 지속적으로 이루어지는 행정구역 변경은 행정안전부 홈페이지에 게시됩니다.
  - http://www.mois.go.kr/frt/bbs/type001/commonSelectBoardList.do?bbsId=BBSMSTR_000000000052
  - [행정안전부 홈페이지](http://www.mois.go.kr/) → [업무안내 → 지방자치분권실 → 주민등록 및 인감] 게시판에서 ‘주민등록주소코드 변경내역’이라는 제목들로 올라온 글에 변경내용이 있습니다.
- 행정구역 코드 변경은 다음과 같이 이루어지는 것 '같습니다'
  - 8자리 코드는 동 통폐합이나 이름 변경시 새로 부여됩니다.
  - 10자리 코드는 통폐합 되더라도 과거의 동 이름이 살아있는한 해당 동의 코드는 그대로 유지됩니다.
- 통계청마이크로데이터서비스의 인구이동 데이터는 10자리 코드와 매칭됩니다. 단, 행정동 이외에도 출장소에 신고된 전입전출 데이터도 있으니 유의하시기 바랍니다.
- 행정동의 관할 법정동 지번과의 관계는 각 시의 조례에 지번까지 상세하게 나와있습니다.
  - ex) 경기도 안산시 행정운영동의 설치 및 관할구역에 관한 조례

## 참고 : 선거 및 지도 관련 데이터

- 과거 선거 관련 데이터 원본은 [중앙선거관리위원회](http://nec.go.kr/portal/bbs/list/B0000341.do?menuNo=200029)에서 찾을 수 있습니다.
- [2017년 대선 시군구별 득표 지도](https://bl.ocks.org/vuski/raw/e29ed35cfdfb21ae01689c76f4aeea87/) 와 [2017년 대선 읍면동별 득표 지도](https://bl.ocks.org/vuski/raw/7e482f13ef2b2ec4c14bb3622f05c353/) 를 인터랙티브 버젼으로 볼 수 있습니다. 지역별 1~5위 득표지도, 후보별 득표지도, 2016년 총선과의 비교지도가 있고 총 14장입니다. 개략적 지도의 모습과 설명은 [여기](http://www.vw-lab.com/39)에서 확인할 수 있습니다. 시군구별 득표지도는 모바일 화면에 최적화 되어 있고, 읍면동별 득표지도는 pc 화면 비율(가로로 긴 화면)에 최적화 되어 있습니다. 읍면동 득표지도는 모바일에서 느려질 수 있습니다.
- [ChangHee Lee 님의 repository](https://github.com/WWolf/korea-election)에 몇몇 과거 선거 데이터들과 관련 자료들이 정리되어 있습니다.
- [오마이뉴스 repository](https://github.com/OhmyNews/2017-Election)에도 2017년 대선 데이터과 분석 자료들이 올라와 있습니다.
- [southkorea 계정의 repository](https://github.com/southkorea/southkorea-maps)에는 2011년~2013년 지도 데이터들이 다양한 포맷으로 올라와 있습니다.

## 참고 : mapshaper

- mapshaper.org 에서 여러 가지 작업을 할 수 있습니다. 자세한 것은 다음의 링크를 참고하세요
  - https://github.com/mbloch/mapshaper/wiki
- 맵셰이퍼에서 가능한 작업들
  - 간단한 토폴로지 불일치 자동 수정
  - 웹 용으로 사용할 수 있도록 simplify 하여 용량 줄이기
  - topojson 으로 변경하여 용량 극소화 하기, 기타 다른 형식으로 변경 가능
  - dissolve 등의 명령 사용 가능
- 행정동을 시군구 경계로 병합하는 방법
  - mapshaper에서 import 후 오른쪽 위의 console 버튼을 눌러 콘솔창을 띄웁니다.
  - -info 명령어로 속성들이 들어와 있는지 확인합니다
  - each 'sgg_cd=adm_cd.substr(0,5)' 명령으로 시군구 코드를 추출해냅니다.
  - each 'sgg_nm=adm_nm.substr(0,adm_nm.lastIndexOf(" "))' 명령으로 시군구 이름을 추출합니다.
  - dissolve sgg_cd copy-fields=sgg_nm 명령으로 시군구 코드 기준으로 병합합니다. 동시에 시군구 이름은 복사해둡니다.
  - 모든 작업이 끝났으므로 Export 하면 됩니다.

## 저작권 관련

- 이 github에서 배포하는 행정동 경계 데이터는 통계청 통계지리정보서비스에 요청하여 받은 2010년과 2015년 경계를 바탕으로 수정한 것입니다.
  - 통계지리정보서비스(sgis.kostat.go.kr)에서는 '제공된 자료에 대한 출처를 반드시 명시'하라는 사항 이외에 별다른 저작권에 대한 사항이 나와 있지 않습니다.
  - 따라서, <공공데이터의 제공 및 이용 활성화에 관한 법률> 3조에 따른다고 해석하여 몇 가지 예외사항을 제외하고는 영리적 이용도 가능하다고 판단하고 있습니다.
- 그리고 원 시점(2010, 2015년)에서 수정을 가한 이 github의 자료 역시 별도의 추가적인 제한을 두지 않습니다.
  - 즉, 자유롭게 이용하시되 이용자의 판단하에 이 github의 주소(https://github.com/vuski/admdongkor)를 표시하여 주시길 권장합니다.
  - 이는 수정된 부분에 대한 저작권을 주장하기 위함이 아니라, 자료에 문제나 틀린 부분을 발견하는 사람이 있을 경우 이 곳을 찾아올 수 있도록 하기 위함입니다.
- 자료의 이용에 대한 책임은 어디까지나 이용자 본인에게 있습니다.
  - 행정동 경계 중 이용 목적과 중요하게 관련된 부분이 있을 경우 위에 기술한 관련 정보를 통해 직접 경계를 확인하신 후 사용하시기 바랍니다.

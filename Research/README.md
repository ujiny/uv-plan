# 기존 서비스 검토
## [자외선 차단(UVDetector)](https://itunes.apple.com/kr/app/%EC%9E%90%EC%99%B8%EC%84%A0-%EC%B0%A8%EB%8B%A8-uvdetector/id1390365852?mt=8)

<p align="center">
  <img height="300" src="https://user-images.githubusercontent.com/23302193/51437328-4d800b80-1ce0-11e9-86e2-af3840262beb.png" />
</p>

### 홈 화면
- 현재 위치 정보 표시
- 정보 업데이트 시간 표시
- 자외선 정보
  - 표정 ( 낮음 / 보통 / 높음 / 매우 높음 / 매우 위험 )
  - 배경 컬러로 표현
  - 자외선 지수
- 오늘의 날씨 정보
  - 현재온도
  - 비 올 확률
  - 미세먼지
  - 최저/최고 온도
  - 공유 기능
- 홈 왼쪽 상단 메뉴 버튼 (사이드바)

### 메뉴 화면
- 세계보건기구(WHO)
  - 지외선 지수 정의 (낮음/보통/높음/매우 높음/매우 위험)
- 자외선 ABC정보
  - 자외선 지수에 따른 대처 방안 제시
- 자외선 정보출처기능
  - 세계보건기구, OpenWeatherMap, 한국환경공단, 기상청
- 문의하기 기능
  - 아이폰 기존 메일 앱 연동

### 불편 사항
- UX
  - 리스트 형식이 아니여서 많은 사용자가 `Pull To Refresh` 를 모를 것으로 예상됨
  - 메뉴 화면에서 화면 이동마다 Navigation 사용하여 불편
    - 화면 이동간 화면이 축적되기 때문에 Back 버튼을 눌러야 하는 상황 발생
    - 오늘의 날씨 정보 자세히 보기 위한 가로 스크롤과 메뉴 사이드바 인터랙션 중복 
- 현재 위치가 아닌 사용자 지정 위치 자외선 정보를 얻을 수 없음.
- 문의하기 누르면 아무 반응이 없음
  - gmail 가 연동 되어 있지만 없을 경우 반응이 없음.
- 위젯 기능이 없음

----------------------------------------

# 기존 앱 과의 차별성
- 위젯 기능
- 알람 푸시 (특정 시간에 자외선 지수 알림)
- 사용자 지정 위치 자외선 지수
- 불편, 개선점 등 메일 기능

# 제22대 총선 지역구 판세 그림판

대한민국 제22대 총선 지역구 및 비례의석 판세를 시각화하는 방법을 고민하며 만들어본 간단한 페이지들입니다. Javascript+HTML로 파일 하나로 선거구나 지역이름에 토글클릭으로 지역구나 전체 지역을 색칠하고, 비례표의 경우 예상득표율을 입력해서 연동형 비례대표제에 따라 의석수가 배분되는 것을 얼추 가늠해볼 수 있습니다. 언론에서 전문가들이 판세를 이야기하며 의석수를 얘기할 때, 어떤 모양이 있는지 판단해보는 용도입니다. 제목과 비고란을 원하는대로 바꿔볼 수 있습니다. 이리저리 작업하고 서로 돌려보는 용도입니다.

현재 두 가지 버전을 만들어봤습니다.

* [test.html](https://wwolf.github.io/electionscratchpad_KR2024/test.html) 지역구+비례의석의 추이를 계산해보는 작업입니다. 제3당 지역구 당선을 고려하지 않아 연동형 비례대표제 관련 의석수에서 차이가 있을 수 있습니다.

<img width="50%" alt="전체 판세 그림판" src="https://github.com/WWolf/electionscratchpad_KR2024/assets/531000/9229935d-54a0-4f90-87a8-e334073d39d8">


* [test2.html](https://wwolf.github.io/electionscratchpad_KR2024/test2.html) 흔히들 말하는 백중세니, 열세니, 우세니 하는 단계들을 양당 사이에 더 집어넣고 지역구만 그려보는 작업이며, 생활권역 그룹들을 더 추가했습니다. 마우스 오른쪽 버튼을 누르시면 반대로 toggling이 됩니다.

<img width="50%" alt="지역구 판세 그림판" src="https://github.com/WWolf/electionscratchpad_KR2024/assets/531000/5624aa3e-2951-43ec-b389-aa5a929f5e6d">

# Updates
* Firefox에서도 깨지지 않고 동작합니다.
* 이제 HTML을 다른 이름으로 저장하시면 그대로 다시 로드해서 작업하실 수 있습니다.
* [test2.html](https://wwolf.github.io/electionscratchpad_KR2024/test2.html)의 경우 범례에 숫자가 함께 집계됩니다.

* [test2.html](https://wwolf.github.io/electionscratchpad_KR2024/test2.html)는 이제 저장된 다른 페이지를 로딩하실 수 있습니다.
* 경기도 생활권역을 [경기연구원](https://www.kgnews.co.kr/news/article.html?no=734962)에서 정리한 6개 권역으로 업데이트했습니다.
* 서울에서 중구+성동구 지역구를 "도심권"으로 편입했습니다.

# Acknowledgements

[여론M](https://poll-mbc.co.kr/poll2024/)의 총선사이트의 시각화를 활용했습니다. 해당 사이트에서 정보들이 많이 집계되어 있습니다.

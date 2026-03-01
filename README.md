# opensorce
오픈소스

https://dev-hiro.tistory.com/23
https://hepsoftwarefoundation.org/activities/gsoc.html

구글서머오브코드?

https://medium.com/@Jager-yoo/%EC%98%A4%ED%94%88%EC%86%8C%EC%8A%A4-%EC%BB%A8%ED%8A%B8%EB%A6%AC%EB%B7%B0%ED%84%B0%EC%9D%98-%EC%82%B6-61de5cc48a8c
제시해주신 유튜브 영상 **"엔비디아 소프트웨어 엔지니어가 알려주는 오픈소스 하는법!!!"**의 주요 내용을 분석하여 요약해 드립니다.

이 영상은 엔비디아(NVIDIA)에 재직 중인 소프트웨어 엔지니어가 오픈소스 프로젝트에 기여(Contribution)하고 싶은 초보자들을 위해 실질적인 단계와 팁을 공유하는 내용입니다.

### 1. 오픈소스 시작을 위한 3단계 전략

* **1단계: 'Beginner-Friendly' 프로젝트 찾기 [[01:04](http://www.youtube.com/watch?v=DNXwQwJTgyA&t=64)]**
* 모든 프로젝트가 초보자에게 친절한 것은 아닙니다. `README.md` 파일에 컨트리뷰션 가이드(Contribution Guide)가 잘 작성되어 있는 프로젝트를 선택하는 것이 중요합니다. 영상에서는 예시로 'PyTorch Lightning' 같은 라이브러리를 언급합니다.


* **2단계: 'Good First Issue' 레이블 활용 [[02:04](http://www.youtube.com/watch?v=DNXwQwJTgyA&t=124)]**
* 프로젝트의 'Issues' 탭에서 **`good first issue`** 또는 **`beginner-friendly`**라는 레이블이 붙은 이슈를 찾아보세요. 이는 메인테이너들이 초보자가 해결하기 적당하다고 판단하여 남겨둔 과제들입니다. [[02:39](http://www.youtube.com/watch?v=DNXwQwJTgyA&t=159)]


* **3단계: 실제 작업 및 소통 [[03:17](http://www.youtube.com/watch?v=DNXwQwJTgyA&t=197)]**
* 하고 싶은 이슈를 찾았다면 "내가 이 작업을 해도 될까요?"라고 댓글을 남겨 의사를 밝히는 것이 좋습니다. 그 후 작업을 진행하고 Pull Request(PR)를 보냅니다. [[03:39](http://www.youtube.com/watch?v=DNXwQwJTgyA&t=219)]



### 2. 적극적인 태도와 네트워킹 [[04:56](http://www.youtube.com/watch?v=DNXwQwJTgyA&t=296)]

* 단순히 코드만 수정하는 것을 넘어, 해당 프로젝트의 메인테이너나 관련자에게 이메일이나 메시지를 보내 더 깊게 기여하고 싶다는 의사를 표현해보라고 권장합니다. [[05:10](http://www.youtube.com/watch?v=DNXwQwJTgyA&t=310)]
* 어떤 태스크를 맡으면 좋을지 직접 물어보는 것도 좋은 방법이며, 이러한 과정이 커리어에 큰 도움이 될 수 있음을 강조합니다. [[06:02](http://www.youtube.com/watch?v=DNXwQwJTgyA&t=362)]

### 3. 유의해야 할 마음가짐 [[06:24](http://www.youtube.com/watch?v=DNXwQwJTgyA&t=384)]

* **오픈소스는 본업이 아니다 [[07:28](http://www.youtube.com/watch?v=DNXwQwJTgyA&t=448)]:** 대부분의 오픈소스 메인테이너들은 본업 외의 시간에 활동하므로 답장이 늦을 수 있습니다. 여유를 가지고 기다리는 자세가 필요합니다. [[07:35](http://www.youtube.com/watch?v=DNXwQwJTgyA&t=455)]
* **두려움 극복:** "말하는 것만큼 쉽지 않다"고 인정하면서도, 일단 부딪혀보는 것이 중요하다고 조언합니다. [[04:27](http://www.youtube.com/watch?v=DNXwQwJTgyA&t=267)]

### 요약 및 결론

이 영상의 핵심은 **"작은 것부터, 친절한 프로젝트에서, 소통하며 시작하라"**는 것입니다. 엔비디아 엔지니어라는 현직자의 시선에서 오픈소스가 단순한 코딩 공부를 넘어 인맥을 쌓고 실력을 증명하는 훌륭한 창구임을 잘 보여주고 있습니다.

**영상 링크:** [https://www.youtube.com/watch?v=DNXwQwJTgyA](https://www.youtube.com/watch?v=DNXwQwJTgyA)


응, **규모 꽤 큼**. “코드량”을 *대충 감 잡는 용도*로 보면 아래 정도야(지금 Open Hub 기준이라 포함/제외 규칙에 따라 약간 흔들릴 수는 있음).

| 프로젝트                |               대략 LOC(라인) | 느낌                                                       |
| ------------------- | -----------------------: | -------------------------------------------------------- |
| **GraphHopper**     |                **~139k** | 자바 라우팅 엔진. “대형이지만 혼자도 길 찾을 수 있는” 급. ([openhub.net][1])   |
| **Valhalla**        |                **~191k** | C++ 라우팅 + 매트릭스/맵매칭 등 기능 많음. ([openhub.net][2])           |
| **OSRM**            |                **~659k** | C++로 진짜 대형. 첫 기여는 아주 작은 모듈부터 가는 게 안전. ([openhub.net][3]) |
| **OR-Tools**        |                **~567k** | C++ 코어 + 래퍼/빌드시스템도 복합. “라이브러리 왕” 급. ([openhub.net][4])   |
| **Traccar-web(UI)** |               **~10.5k** | 웹 UI는 생각보다 작음. ([openhub.net][5])                        |
| **Traccar 서버(백엔드)** |      (Open Hub에 안 잡히는 듯) | 자바 백엔드고 프로토콜이 많아서 “작진 않다”는 건 확실. ([GitHub][6])           |
| **OpenWMS**         | (구성상 “여러 repo/컴포넌트”로 분산) | 모노레포 한 방이 아니라 컴포넌트/서비스 묶음 느낌. ([GitHub][7])              |

---

## “코드 리뷰/분석 툴” 쓰면 되냐? → **ㅇㅇ, 필수급으로 도움됨**

다만 현실적으로는 **“내가 자동 리뷰로 다 이해한다”가 아니라**,

1. **프로젝트 CI/린트/테스트를 내 로컬에서 그대로 돌리고**,
2. **툴은 실수 줄이는 보조**로 쓰는 게 제일 효율적이야.

### 바로 써먹는 조합 (언어 상관없이)

* **IDE 인덱싱 + 코드 네비**(Find Usages, Call Hierarchy) : 대형 코드에서 이게 1등
* **GitHub Code Search / ripgrep**: “이 함수 누가 부르지?” 찾는 시간 단축
* **정적분석/보안 스캔**: GitHub CodeQL, Semgrep, Sonar(Cloud/Qube) 같은 류
* **자동 포맷/린트**: PR에서 “스타일로 까이는” 시간 0으로 만들기
* **의존성 취약점/업데이트**: Dependabot류

### “LOC 직접 재는” 도구

OpenHub처럼 사이트 통계도 좋지만, **repo별로 직접 라인 수 세고 싶으면** CodeTabs 같은 “Count LOC” 도구도 많이 써. ([codetabs.com][8])

---

## 큰 코드베이스에서 안 죽는 팁 3개

1. **전체 이해하려고 하지 말고, 이슈 하나에서 역추적**(로그/에러 → 함수 → 모듈)
2. **첫 PR은 “테스트/문서/작은 버그 + 회귀 테스트”**가 머지 확률 높음
3. “코드 리뷰 툴”보다 더 강한 건 **프로젝트가 이미 쓰는 체크(gradle test / cmake test / lint)**를 똑같이 통과시키는 것

원하면 너가 지금 관심 있는 걸 딱 하나 골라줘:
**(A) GraphHopper / (B) Traccar / (C) Valhalla / (D) OR-Tools**
그거 기준으로 *“첫 PR로 먹히기 쉬운 모듈”*이랑 *로컬에서 어떤 커맨드를 먼저 돌려야 하는지*만 초압축으로 정리해줄게.

[1]: https://openhub.net/p/graphhopper "The graphhopper Open Source Project on Open Hub"
[2]: https://openhub.net/p/valhalla-routing "The valhalla-routing Open Source Project on Open Hub"
[3]: https://openhub.net/p/osrm "The Open Source Routing Machine Open Source Project on Open Hub"
[4]: https://openhub.net/p/_compare?project_1=Google+Optimization+Tools "Compare Projects - Open Hub"
[5]: https://openhub.net/p/traccar-web "The traccar-web Open Source Project on Open Hub"
[6]: https://github.com/traccar/traccar "GitHub - traccar/traccar: Traccar GPS Tracking System"
[7]: https://github.com/openwms/org.openwms "GitHub - openwms/org.openwms: Open Warehouse Management System"
[8]: https://codetabs.com/count-loc/count-loc-online.html?utm_source=chatgpt.com "Count LOC online - CodeTabs"


맞아… **이건 내가 진작에 “물류 쪽 큰 오픈소스 판”을 한 번에 깔아줬어야** 했는데, 내가 너무 MATSim/시뮬 쪽으로만 몰고 갔다. 미안.
대신 지금부터는 **“진짜 큰 곳 + 바로 PR 들어가기 좋은 곳”**으로 딱 정리해줄게.

## 물류/운송에서 “판 큰” 오픈소스 라인업

### 1) 라우팅/ETA(트럭커 앱이랑 직결)

* **GraphHopper (Java, Apache-2.0)**: 라우팅 엔진 + 실전 기능 많고, GitHub에 **good first issue**를 공식으로 뽑아놔서 “첫 머지” 노리기 좋음. ([GitHub][1])

  * 예: `points_encoded=true` 무시되는 버그(#2531) 같은 게 아직 열려있음. ([GitHub][2])
* **OSRM (C++)**: 초고성능 라우팅 엔진 쪽 “레퍼런스급”. ([GitHub][3])
* **Valhalla (C++)**: 라우팅 + **matrix/isochrone/map matching**까지 있어 “물류/리스크/ETA” 쪽으로 확장하기 좋음. ([GitHub][4])

  * 게다가 Valhalla도 `good first issue` 라벨이 있고(#3412 같은 이슈) 진입 포인트가 있음. ([GitHub][5])

### 2) 차량 트래킹/텔레매틱스(현업 임팩트 바로 나옴)

* **Traccar (Java backend + Web/Mobile)**: GPS 추적 시스템 쪽에서는 진짜 큰 프로젝트. 백엔드가 **200+ 프로토콜/수천 디바이스 모델** 지원한다는 게 강력함. ([GitHub][6])

  * 공식적으로 “서버/웹/모바일 다 기여 환영” + 빌드 가이드도 잘 되어 있음. ([traccar.org][7])
  * 최근에도 API 확장 요청 같은 이슈가 꾸준히 올라옴(#5740). ([GitHub][8])
  * Web UI repo도 따로 있고(React/Material UI/MapLibre, Apache-2.0). ([GitHub][9])

### 3) 최적화/디스패치(배송·배차의 본진)

* **Google OR-Tools**: VRP/TSP 포함해서 “배차/루트 최적화”의 사실상 표준 라이브러리. ([GitHub][10])

### 4) 창고/WMS(물류 운영 플랫폼)

* **OpenWMS (Apache-2.0)**: WMS + Material Flow Control까지 가는 꽤 큰 자바 생태계. ([GitHub][11])

(덤) 분석/모빌리티 네트워크 쪽이면 **OpenTripPlanner**도 “커뮤니티 큰 편”이야. ([opentripplanner.org][12])

---

## “지금 당장” 추천 1순위 (니 상황 기준)

너 목표가 **트럭커/물류 리스크·ETA·혼잡**이면,

* **GraphHopper에서 good first issue 하나 잡아 머지** → 제일 빠르게 “외부 프로젝트에 채택된 내 코드”를 만들기 좋고 ([GitHub][1])
* 동시에 **Traccar로 텔레매틱스/이벤트 처리 쪽 기여** → “현업 사용” 스토리가 바로 붙음 ([traccar.org][7])
  이 조합이 제일 깔끔해.

---

원하면 내가 **너 대신 ‘첫 PR로 먹힐 확률 높은 이슈 5개’만** GraphHopper/Traccar/Valhalla 중에서 골라서(난이도/효과/작업 범위 포함) 바로 큐레이션해줄게.

너는 딱 하나만 말해줘:
**(A) 라우팅/ETA**, **(B) 트래킹/이벤트**, **(C) 배차/최적화** 중에 뭐가 제일 끌려?

[1]: https://github.com/graphhopper/graphhopper/contribute?utm_source=chatgpt.com "Contribute to graphhopper/graphhopper"
[2]: https://github.com/graphhopper/graphhopper/issues/2531?utm_source=chatgpt.com "PT routing ignores 'points_encoded=true' · Issue #2531"
[3]: https://github.com/Project-OSRM/osrm-backend?utm_source=chatgpt.com "osrm-backend: Open Source Routing Machine - C++ backend"
[4]: https://github.com/valhalla/valhalla?utm_source=chatgpt.com "valhalla/valhalla: Open Source Routing Engine for ..."
[5]: https://github.com/valhalla/valhalla/labels?utm_source=chatgpt.com "Labels · valhalla/valhalla"
[6]: https://github.com/traccar/traccar?utm_source=chatgpt.com "Traccar GPS Tracking System"
[7]: https://www.traccar.org/contribute/?utm_source=chatgpt.com "Contribute"
[8]: https://github.com/traccar/traccar/issues/5740?utm_source=chatgpt.com "Feature Request: Add `reportId` query parameter to GET ..."
[9]: https://github.com/traccar/traccar-web?utm_source=chatgpt.com "traccar/traccar-web: Traccar GPS Tracking System"
[10]: https://github.com/google/or-tools?utm_source=chatgpt.com "Google's Operations Research tools"
[11]: https://github.com/openwms/org.openwms?utm_source=chatgpt.com "openwms/org.openwms: Open Warehouse Management ..."
[12]: https://www.opentripplanner.org/?utm_source=chatgpt.com "OpenTripPlanner"


<div align="center">
<h1> React Deep Dive 스터디 🚀 </h1>
<p>FE-Drilling에서 진행하는 React Deep Dive 스터디 레포입니다.</p>
</div>

<div align="center">
  
| 항목            | 내용                                       |
| --------------- | ---------------------------------------- |
| **도서**         | 모던 React Deep Dive (총 15 챕터, 916쪽)                  |
| **일자**         | 매주 토요일 오전 9시 ~ 12시                   |
| **모임 장소**     | 온라인 Zep 라운지 F테이블  (오프라인 달 1회 유동적으로 진행) |
| **소요 시간**    | 1-2 시간                                    |
| **진행 기간**    | 2 달                                       |
| **진도** | 매주 1~2챕터 또는 100쪽 분량으로 유동적         |
| **회고** | 한 달 주기로 스터디 회고를 진행, 피드백 반영         |

✷ ~ 12/23 까지 오전 10시 ~ 13시 진행

<img alt="GitHub issues" src="https://img.shields.io/github/issues/fe-drilling/react-deep-dive?style=for-the-badge&color=%1abc9c">

</div>

## 목차
1. [스터디 진행 방법](#1)
2. [진도표](#2)
3. [벌금 규정](#3)
4. [주차별 정리](#4)
5. [이슈](#5)
6. [출석표](#6)

<h2 align="center" id="1">스터디 진행 방법</h2>

1. 진행할 분량을 정한다.
2. 매주 스터디를 진행할 호스트와 부호스트를 2명씩 랜덤으로 뽑는다.
3. 각자 정해진 분량을 미리 읽어온다.
4. 호스트는 해당 챕터 학습 진행의 책임을 맡는다.
   - 진행방법은 호스트의 자율에 맡긴다.
5. 스터디 진행 중 기록한 이슈(질문 등)를 공유한다.

구글 미트에서 녹화 진행하여 스터디 내 발표, 토론 내용을 기록한다. 🎥

<h2 align="center" id="2">진도표</h2>

<p align="center">섹션을 클릭하면 해당 주차의 발표 내용을 볼 수 있다. (12/23부터 제공)</p>
  
<div align="center">


| 날짜    | 주차 | 진행                            | 호스트   | 부호스트 | 발표 자료 |
| ------- | ---- | ------------------------------- | -------- | -------- | ---------- |
| 12/2    | OT   |                                 |          |          |            |
| 12/9    | 1주차 | 리액트의 역사 ~ 클로저 (0.~1.4장) | 양진성 | 강민석 | |
|         |      | 이벤트 루프 ~ 타입스크립트 (1.6~1.7장) | 남희정 | 강민석 | [발표 자료](https://github.com/fe-drilling/react-deep-dive/files/13758022/React_Deep_Dive_1.5.1.7.pdf) |
| 12/16   | 2주차 | JSX란? ~ 클래스형 컨포넌트와 함수형 컴포넌트 (2.1~2.3장) | 최승진 | 윤서림 | |
|         |      | 렌더링은 어떻게 일어나는가? ~ 컴포넌트와 메모이제이션 (2.4~2.5장) | 남희정 | 양진성 | [발표 자료](https://github.com/fe-drilling/react-deep-dive/files/13758023/React_Deep_Dive_2.4.2.5.pdf)|
| 12/23   | 3주차 | [리액트의 모든 훅 파헤치기 (3.1장)](https://youtu.be/sXVVWa4WWqk?si=DMIAVFVKunANpRCD) | 남희정 | 윤서림 | [발표 자료](https://github.com/fe-drilling/react-deep-dive/files/13758025/React_Deep_Dive_3.1.pdf) |
|         |      | 사용자 정의 훅과 고차 컴포넌트 ~ 서버 사이드 렌더링(3.2~4.1장) | 윤서림 | 최승진 ||
| 12/30   | 4주차 | SSR 렌더링 API ~ Next.js (4.2~4.3장) | 강민석 | 양진성 |  |
|         |      | 리액트와 상태 관리 라이브러리 (5.1~5.2장) | 남희정 | 최승진 |  |
| ...     | ...  | ...                             | ...      | ...      | ...        |



</div>

<h2 align="center" id="3">벌금 규정</h2>

- 1주차부터 적용된다.
- 10분당 지각 (1000원 / max: 3000원)
- 불참 (5000원)
- 벌금은 모임 통장에 입금한다.
  
<h2 align="center" id="4">주차별 정리</h2>

- 주차별 폴더에 정리한 내용이나, 도식화된 발표 내용 등을 업로드합니다. 
- 스터디 내용으로 블로그 포스팅시 이곳에 추가됩니다.

<h2 align="center" id="5">이슈</h2>

>각자 흥미로운 이슈를 선택해 공유, 공부합니다.

### 1주차 이슈
- useCallback 필요한 경우
- 문과 식 => return문?, jsx에 문이 올 수 있는가?
- useState는 왜 비동기인가?
- 콜백함수를 안쓰고 API 처리를 할 때 어떻게 해야할까?
- 동시성 문제 실제 예시는 어떤게 있을까?
- Instanceof 지양하라?

### 2주차 이슈
- JSXMemberExpression과 컴포넌트 패턴의 연관성 <foo.bar.baz>
- createElement 문법 유용할까? 
- ErrorBoundary의 영역 비동기에선 안잡힌다.
  - 컴포넌트에서 에러가 잡히면 넘겨준다. 전역 에러 핸들링
  - catch를 안쓰고 컴포넌트에서 커스텀 훅 API 사용하는데 그 중간에 에러 처리를 아예 안하면 에러가 잡힘
  - 훅에서 컴포넌트까지 에러가 전파되어야 ErrorBoundary에 잡힌다.
- 렌더링 프로세스 (렌더: 비동기, 커밋: 동기)
  - 렌더링을 비동기라고 할 수 있을까?
  - setState 비동기?
  - setState 함수의 '호출'이 비동기적으로 이루어지는 것이다
- 메모제이션 남발, 좋을까?
  - 상태를 저장하는 것 브라우저 리소스 잡아먹기 떄문에 싫다!
  - 메모제이션 전부 썼는데 사이즈가 너무 커짐.. 번들링 이후
  - 리스트 컴포넌트, map 사용시엔 좋을듯 => 이럴땐 메모이제이션, map을 잘 안돌림
- memo랑 useMemo 사용하는 이유?
- input이 많을때 비제어 컴포넌트 vs memo

### 3주차 이슈
- 사이드 이펙트의 정의?
- 리액트에서 사이드 이펙트가 일어나지 않고 순수하게 동작하려면 props를 받아서 return 을 받는게  순수하게 동작한다고 생각한다.
    - flux 패턴이 부수효과 없이 흘러가는가?
    - useEffect를 사용하는 건 위배되지 않냐?
- typeof vs useEffect / 클라이언트 사이드에서 실행되는 걸 보장해주는 것, 둘 중 하나를 고르는 것은 취향 차이인가?
- Provider, 고차컴포넌트 인가?
- [withAsyncBoundary, 고차 컴포넌트 참고 링크](https://slash.page/ko/libraries/react/async-boundary/src/withasyncboundary.i18n/)
- 정적 페이지가 아니라면 SSR이 SPA보다 빠르다고 할 수 없다?
    - 프로덕트 크기 차이일 수 있다. 크기가 작으면 비교하기 어렵다.
- [CSR, SSR 렌더링 참고 링크](https://web.dev/articles/rendering-on-the-web?hl=ko)
- [고차컴포넌트 사용 예시 | 최승진 프로젝트 ](https://github.com/yondo123/simple-wather/blob/main/src/services/hooks/useGetCurrentWeather.ts)


<h2 align="center" id="6">출석표</h2>

| 이름   | GitHub ID   | OT | 1주차 | 2주차 | 3주차 | 4주차 | 5주차 | 6주차 | ... |
| ------ | ------------ | -- | ----- | ----- | --- | --- | --- | --- | --- |
| 강민석 | [@ainochi-kor](https://github.com/ainochi-kor)  | ✓  | ✓     | ✓     | ✓     |     |     |    | ... |
| 남희정 | [@havenothorn](https://github.com/havenothorn)   | ✓  | ✓     | ✓     | ✓     |    |    |    | ... |
| 양진성 | [@jinseoIT](https://github.com/jinseoIT)   | ✓  | ✓     | ✓     |✓     |    |    |    |  ... |
| 윤서림 | [@yunseorim1116](https://github.com/yunseorim1116) | ✓  | ✓     | ✓     |✓     |    |    |    | ... |
| 최승진 | [@yondo123](https://github.com/yondo123)   | ✓  |   ✓   | ✓     |✓     |    |    |    |  ... |

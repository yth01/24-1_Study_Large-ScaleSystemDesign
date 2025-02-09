# 시스템 설계 면접 공략법

## 1️⃣ 단계 : 문제 이해 및 설계 범위 확정

- 요구사항을 이해하는데 필요한 질문
    - 구체적으로 어떤 기능들을 만들어야 하나
    - 제품 사용자 수는 얼마나 되나
    - 회사의 규모는 얼마나 빨리 커지리라 예상하나 (석 달, 여섯 달, 일년 뒤의 규모는 얼마가 되리라 예상하나)
    - 회사가 주로 사용하는 기술 스택은 무엇인가 (설계를 단순화하기 위해 활용할 수 있는 기존 서비스로는 어떤 것들이 있는가)

## 2️⃣ 단계 : 개략적인 설계안 제시 및 동의 구하기

- 설계안에 대한 최초 청사진을 제시하고 의견을 구하라
- 화이트보드나 종이에 핵심 컴포넌트를 포함하는 다이어그램을 그려라
- 이 최초 설계안이 시스템 규모에 관계된 제약사항들을 만족하는지를 개략적으로 계산해 보라

## 3️⃣ 단계 : 상세 설계

- 설계 대상 컴포넌트 사이의 우선순위를 정한다

## 4️⃣ 단계 : 마무리

- 면접관이 시스템 병목구간, 혹은 좀 더 개선 가능한 지점을 찾아내라 주문할 수 있다.
- 여러분이 만든 설계를 한번 다시 요약
- 오류가 발생하면 무슨 일이 생기는지 따져보는 것
- 운영 이슈 (메트릭 수집 및 모니터링, 로그, 시스템 배포)
- 미래에 닥칠 규모 확장 요구

## 정리
### 해야 할 것

- 질문을 통해 확인하라(clarification). 스스로 내린 가정이 옳다 믿고 진행하지 말라.
- 문제의 요구사항을 이해하라.
- 정답이나 최선의 답안 같은 것은 없다는 점을 명심하자. 요구사항을 정확히 이해했는지 다시 확인하라.
- 면접관이 사고의 흐름을 이해할 수 있도록 하라, 면접관과 소통하라.
- 가능하다면 여러 해법을 함께 제시하라.
- 개략적 설계에 면접관이 동의하면, 각 컴포넌트의 세부사항을 설명하기 시작하라. 가장 중요한 컴포넌트부터 진행하라
- 면접관의 아이디어를 이끌어 내라. 좋은 면접관은 팀원처럼 협력할 것이다.

### 하지 말아야 할 것

- 전형적인 면접 문제들에도 대비하지 않은 상태에서 면접장에 가지 말라.
- 요구사항이나 가정들을 분명히 하지 않은 상태에서 설계를 제시하지 말라.
- 처음부터 특정 컴포넌트의 세부사항을 너무 깊이 설명하지 말라. 개략적 설계를 마친 뒤 세부사항으로 나아가라.
- 진행 중 막혔다면, 힌트를 청하기를 주저하지 말라.
- 소통을 주저하지 말라.
- 설계안을 내놓은 순간 면접이 끝났다고 생각하지 말고, 의견을 일찍 그리고 자주 구하라.

### 시간 배분

- 45분 면접 시간을 가정
    - 1단계 (문제 이해 및 설계 범위 확정) - 3분에서 10분
    - 2단계 (개략적 설계안 제시 및 동의 구하기) - 10분에서 15분
    - 3단계 (상세 설계) - 10분에서 25분
    - 4단계 (마무리) - 3분에서 5분

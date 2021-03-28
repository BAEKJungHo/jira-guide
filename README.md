# JIRA를 활용해 더 효과적으로 프로젝트 협업하기

이슈트래킹은 소프트웨어 산업 뿐만 아니라 공장, 건축 등 다방면으로 사용되고 있는 시스템이다. 그 중 이슈트래킹 기능을 효과적으로 사용하기 위해 제공되는 유명한 툴이 바로 JIRA이다. 즉, JIRA 는
이슈트래킹을 잘 활용하기 위한 툴을 의미한다.

## 폭포수 모델과 엑셀을 통한 계획관리

- 폭포수 모델의 단점
  - 낮은 품질 : 프로젝트 종료 시점에는 시간이 부족하므로 납기를 위해 테스트를 줄이게되어 품질이 낮아짐.
  - 낮은 가시성 : 고객은 프로젝트 종료 시점에야 구동하는 제품을 볼 수 있음.
  - 변화에 대응하기 어려움 : 현실은 설계가 완료 되었어도 개발/테스트 단계에서 설계를 수정해야 하는 경우가 자주 발생.

- 엑셀을 통한 계획 관리
  - 파일명이 계획표 `_v0.1 _v0.2, ... _v1.0-final, 최종, 최종의 최종, 진짜 최종, 최종 마지막 ...` 이런식으로 파일이 생성됨 
  - 산출물 확인 및 진척률 확인 등 하나의 파이프라인으로 확인해야 하는데, 엑셀은 한계가 있다.

__협업과 공유는 쉽게 할 수 있어야 더 많이 하게 된다.__

## 프로젝트 관리 도구로서 엑셀

- 수행하는 프로젝트의 내/외부 환경 변화에 대응이 어려운 나쁜 프로젝트 관리 도구이다.
- 협업과 수정/배포가 어렵고 변경 사항 추적이 힘들다.

## 이슈 관리 시스템과 JIRA

- 이슈 란?
  - 오류, 버그 및 새로운 기능, 작업 요청, 사소한 질문이나 의견 등 제품에 관해 회사에서 대화의 대상이 되는 거의 모든것을 의미한다.
  - 따라서, 이슈를 잘 모아두면 `컨텍스트(context)`가 되며 커뮤니케이션이 쉬워진다.
  - 이슈를 티켓이라고도 한다. 

- 이슈 관리 시스템(Issue Tracking System)
  - 초기 계획에 매몰되지 않고 변화에 대응하기 위한 방법론과 프로세스를 구현한 SW 제품
  - 형상 관리와 더불어 프로젝트의 핵심 인프라
  - 일반적으로 Web 기반이라 별도의 설치없이 손쉽게 사용 가능

- 도입시 고려사항
  - 회사의 프로세스, 이력, 지식이 쌓이는 핵심 자산이므로 총소유비용(TCO) 관점에서 검토
  - 레드마인은 이슈가 많아질 수록 검색속도가 느려진다.
  - 비 개발 부서도 적극 참여 필요
  - 사용성이 뛰어나야 함
  - Customization 기능 필요
  - 생산성 향상을 위해 형상 관리, 지속적인 통합, 메신저 등 외부 시스템과 유연한 연계 필요 

- JIRA 란?
  - 협업 제품 전문인 Atlassian 의 Issue 및 프로젝트 관리 시스템(애자일 or 전통적인 관리 중 선택 가능)
  - 깔끔한 UI 와 강력한 기능, 좋은 기술 지원 제공
  - 자사 제품과 강력한 통합 지원(Confluence, Bamboo, BitBucke, Crowd 등)
  - 사용자 수에 따라 비용을 책정하므로 규모에 따라 상당한 비용 발생
  - Market Place 가 활성화 되어있어서 JIRA 에서 제공되지 않는 기능(결재, 자산관리, Test 관리)도 third party 를 통해 사용 가능

## JIRA 의 구조

- `Field`
  - 이슈의 구성요소
    - Summary
    - Priority
    - Issue Type
- `Issue`
  - 단위 업무
    - 특정 Browser 에서 화면 깨짐 수정
    - 검색 속도 개선
    - 사용자 매뉴얼 작성
- `Project`
  - 단위 프로젝트
    - 호텔 예약 웹
    - 호텔 예약 iOS 앱
    - 호텔 예약 안드로이드 앱
- `Project Category`
  - 논리적 프로젝트 묶음
    - 결제 인프라
    - 호텔 예약 서비스

## JIRA 의 프로젝트 유형

### 차세대 프로젝트(Next-gen Project)

- 사용자가 설정할 게 별로 없고 사용이 쉬우므로 Jira 에 경험이 없어도 빠르게 사용 가능
  ▪ 심플하고 쉬운 로드맵 기능 제공
  ▪ 4가지의 리포트 제공
  ▪ 프로젝트 설정이 공유 안 됨 → 프로젝트마다 개별로 설정 필요
  ▪ Jira 관리자가 없고 민첩하고 빠르게 시작해야 하는 소규모 팀에게 추천

### 클래식 프로젝트(Classic Project)

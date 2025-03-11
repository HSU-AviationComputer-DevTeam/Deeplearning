## Project Overview
세무사 에이전트 (tax agent): 세무 전문가 에이전트와 AI 세무 플랫폼(AIP)을 통한 일반인 세무 문제 해결

##  Team Members
<table>
  <tr align="center">
        <td width="150px">
      <a href="https://github.com/espada105" target="_blank">
        <img src="https://avatars.githubusercontent.com/espada105" alt="espada105" />
      </a>
    </td>
    
   <td width="150px">
      <a href="https://github.com/dongsinwoo" target="_blank">
        <img src="https://avatars.githubusercontent.com/dongsinwoo" alt="dongsinwoo" />
      </a>
    </td>
  <td width="150px">
      <a href="https://github.com/isshoman123" target="_blank">
        <img src="https://avatars.githubusercontent.com/isshoman123" alt="isshoman123" />
      </a>
    </td>
  </tr>
  <tr align="center">
    <td>
      조장: 홍성인
    </td>
    <td>
      조원: 신동우
    </td>
      <td>
      조원: 김재원
    </td>
  </tr>
</table>

## 비전 및 목표

일반 납세자들이 경험하는 세무 관련 어려움을 해소하기 위해, 실제 세무사의 전문성을 갖춘 AI 에이전트와 통합 플랫폼을 구축하여 접근성 높은 세무 서비스를 제공합니다.

## 주요 문제점 해결 방안

1. **복잡한 세법 이해의 어려움**
   - 에이전트가 쉬운 언어로 세금 개념 설명
   - 개인별 상황에 맞는 맞춤형 세법 정보 제공
   - 시각적 자료와 비유를 활용한 이해도 향상

2. **세금 신고 과정의 불확실성**
   - 단계별 세금 신고 가이드 제공
   - 필요 서류 체크리스트 및 준비 방법 안내
   - 실시간 질의응답을 통한 궁금증 및 불안감 해소

3. **절세 방안에 대한 정보 부족**
   - 개인 상황 분석 기반 맞춤형 절세 전략 제안
   - 세액공제 및 감면 항목 자동 식별
   - 미래 재무 계획에 따른 세금 최적화 가이드

4. **세금 관련 문서 관리의 번거로움**
   - 영수증, 증빙서류 자동 분류 및 저장
   - 세금 관련 서류 디지털화 및 체계적 관리
   - 필요 시 즉시 검색 및 활용 가능한 문서 시스템

## AIP 플랫폼 사용자 경험

### 1. 직관적 사용자 인터페이스
- 대화형 인터페이스로 복잡한 세무 용어를 쉽게 풀어서 상담
- 질문 입력만으로 즉시 전문가 수준의 답변 제공

### 2. 개인화된 세무 관리
- 최초 설정 시 기본 정보 입력으로 개인별 프로필 구축
- 소득, 지출, 자산 정보 자동 분석 및 세무 영향 평가
- 생애 주기별 세무 계획 및 조언 제공

### 3. 실시간 세무 지원
- 세금 관련 질문 응대
- 세금 신고 기간 중 집중 지원
- 세무 이슈 발생 시 빠른 대응 방안 제공

## 일반인 대상 주요 서비스

1. **세금 교육 및 이해**
   - 세금 기초부터 심화까지 단계별 학습 콘텐츠
   - 실생활 예시를 통한 세금 개념 설명
   - 세법 개정 시 영향 및 대응 방안 알림

2. **자동 세금 계산 및 신고**
   - 소득, 공제 항목 분석 통한 세금 자동 계산
   - 신고서 작성 및 제출 자동화
   - 신고 오류 사전 검증 및 수정 안내

3. **맞춤형 세무 상담**
   - 개인 상황에 따른 특화된 세무 조언
   - "내 상황에선 어떻게 해야 하나요?"식 질문에 정확한 답변
   - 세무 결정에 따른 장단기 영향 분석

4. **문서 및 증빙 관리**
   - 사진 촬영만으로 영수증, 증빙서류 디지털화
   - 세금 관련 문서 자동 분류 및 관리
   - 세무 조사 대비 체계적 자료 준비 지원

이 시스템은 세무 전문가의 비용이나 접근성 문제로 인해 적절한 세무 서비스를 받지 못했던 일반인들에게, 마치 개인 세무사를 고용한 것과 같은 수준의 서비스를 제공하는 것을 목표로 합니다. 일상 언어로 소통하는 AI 에이전트와 사용자 친화적인 플랫폼을 통해 세금에 대한 두려움과 불확실성을 해소하고, 모든 납세자가 자신의 권리를 최대한 활용할 수 있도록 지원합니다.

## journal (예정, 3중 1)
- ~~정보과학회논문지 (Journal of the Society of Information Science)~~
- ~~한국지능시스템학회 (Korean Society for Intelligent Systems)~~
- ~~한국정보처리학회 (Korea Information Processing Association)~~

## Language
언어 및 프레임워크
- FE: React.js + Tailwind CSS + React Router + Lucide Icons
- BE: Python (AI/ML 핵심 로직), Node.js + Express (API 서비스)
 
데이터베이스
- PostgreSQL: 사용자 정보, 세무 데이터 등 구조화된 데이터 저장
- MongoDB: 세무 문서, 영수증 데이터 등 비정형 데이터 관리
- Elasticsearch: 세무 법규, 판례 검색 엔진

AI 및 NLP (예정 Llama로 변경가)
- ~~OpenAI API: 세무 상담 및 자연어 처리 핵심 기능~~
- ~~Hugging Face Transformers: 세무 특화 NLP 모델 (문서 분류, 정보 추출)~~

클라우드 및 인프라
- Firebase: 인증, 실시간 데이터베이스, 호스팅
- ~~AWS S3: 문서 저장소~~
- ~~AWS Lambda: 서버리스 함수 (문서 처리, 계산 등)~~
- ~~Docker & Kubernetes: 서비스 컨테이너화 및 관리~~

보안
- OAuth/OIDC: 사용자 인증
- 암호화 라이브러리: 민감한 세무 데이터 보호

## Tool
- Colab: AI모델 학습
- Vscode: AI모델 학습을 제외한 나머지 개발
  
## communication
- Github: 협업저장소
- Discord: 비대면 회의
- Notion: 프로젝트 진행상황 




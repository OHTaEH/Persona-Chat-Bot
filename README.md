# Persona-Chat-Bot

# 페르소나 AI 기술을 접목시킨 다양한 AI Character 개발

## **개요**

본 프로젝트는 사용자가 직접 설정 가능한 다양한 페르소나(성격, 역할, 배경 등)를 지닌 AI 캐릭터를 개발
사용자 취향에 맞는 페르소나 AI와 상호작용 경험을 제공

## **개발 단계**

### **2.1 페르소나 프로파일링**

- 다양한 분야의 인물 및 가상 캐릭터 프로파일 데이터 수집 (연예인, 기업가, 역사인물 등)
- 성격, 성향, 배경, 대화 스타일 등 풍부한 프로파일 정보 확보
- 프로파일 정보를 Gemma 모델에 적용

### **2.2 대화 데이터 확보 및 전처리(Fine tuning)**

- 각 페르소나에 맞는 대화 코퍼스 데이터 수집 (인터뷰, 대본, 서적 등)
- 페르소나별 대화 특성 라벨링 작업 (유머, 지식, 감정 등)
- 데이터 정제, 전처리, 증강 작업 수행

### **2.3 대화 생성 모델 학습**

- 각 페르소나별 대화 데이터로 대화 생성 모델 학습
- 페르소나 프로파일 정보를 입력으로 하는 컨디셔닝 기법 적용(Prompt)

### **2.4 페르소나 AI 캐릭터 구현**

- 페르소나 프로파일과 대화 생성 모델을 통합한 AI 캐릭터 구현
- 지식베이스와 연동하여 특정 주제에 대한 전문성 구현
- 감정 인식, 상황 인식 등의 모델과 결합하여 맥락 이해 능력 보강
- 애니메이션, 아바타, 보이스 등 멀티모달 인터페이스 지원

### **2.5 사용자 인터페이스 및 시스템 개발**

- 페르소나 선택 및 설정, 대화 인터페이스 등 UI/UX 설계
- 확장성과 효율성을 고려한 시스템 아키텍처 설계 (마이크로서비스 등)



## **마일스톤**

- 1단계 : 페르소나 프로파일 및 대화 데이터 확보, 초기 모델 학습
- 2단계 : 페르소나 AI 캐릭터 구현, 인터페이스 및 시스템 개발
- 3단계 : 페르소나 AI 대화 테스트 및 피드백

## **현재 진행되어 있는 페르소나**
- 운동 트레이너 조이
- 아바타 AI
- 재무상담자 제이

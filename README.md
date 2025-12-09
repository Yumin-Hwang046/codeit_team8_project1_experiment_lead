# Codeit Team8 - Experiment Lead Repository

본 레포지토리는 **Team8 프로젝트 실험 리드(Experiment Lead)** 로서  
프로젝트 기간 동안 팀원들에게 도움이 되거나,  
개인적으로 실험해보고 싶은 다양한 코드와 결과를 정리하는 공간입니다.

---

## 목적(Purpose)

- 실험 리드로서 모델 개발에 필요한 **실험 코드, 분석, 문서화**를 체계적으로 공유
- 프로젝트 공식 레포에는 넣기 부담스러운 **개인 실험(W&B 테스트, 모델 변형 실험 등)** 을 기록
- 팀원들이 참고할 수 있는 **최소 실행 예시 코드(minimal reproducible examples)** 제공
- 나중에 재활용할 수 있는 **실험 템플릿 및 유틸 함수** 모음

---

## 구성(Structure)


codeit_team8_project1_experiment_lead/
│
├── experiments/ # 모델 실험 및 검증 관련 파일
│ ├── wandb_tests/ # W&B 실험 테스트, 설정 코드
│ ├── model_variants/ # 다양한 모델 구조 실험
│ ├── inference_tests/ # 추론(inference) 검증 코드
│ └── notebooks/ # 실험 분석 노트북
│
├── utils/ # 반복 사용되는 함수/클래스 모음
│ ├── data_utils.py
│ ├── train_utils.py
│ └── eval_utils.py
│
├── templates/ # 팀원들이 참고할 수 있는 템플릿
│ ├── experiment_template.ipynb
│ └── wandb_logging_template.py
│
├── results/ # 실험 결과 정리 (이미지, 로그, 요약문)
│
└── README.md


---

## 포함될 콘텐츠(Contents)

- W&B 실험 코드 및 비교 로그
- 모델 아키텍처 변형 실험(하이퍼파라미터, 레이어 구성 테스트 등)
- EDA 및 오류 분석 노트북
- 모델 성능 향상을 위한 개인 탐색 기록
- 추후 발표나 회의에 도움될 수 있는 요약 자료

---

## 사용 가이드(How to Use)

1. 모든 실험 폴더에는 **실행 방법(Run Instructions)** 과 **목적 설명**을 명시.
2. 중요한 실험은 `results/` 폴더에 **요약문 + 그래프 + 주요 결론**을 함께 저장.
3. 팀원들이 복사해서 사용할 수 있도록 **가장 단순한 형태의 템플릿**도 제공.

---

## 라이선스 및 안내(Notes)

- 프로젝트 내부 용도로 사용하며, 파일에 따라 개인적인 테스트 코드가 포함될 수 있음.
- 필요 시 팀원들과 공유하며, 정식 모델은 팀 레포지토리에 업로드.

---

## Contact

- Maintainer: Yumin Hwang (Experiment Lead)
- Purpose: Codeit Team8 Project 1 — Model Experiment & Analysis


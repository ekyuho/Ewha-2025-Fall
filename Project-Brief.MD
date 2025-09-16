# 2025 Fall 전체 프로젝트 리스트
|팀번호|팀명|프로젝트명|
|:---|:---|:---|
|[1](#team-1-팀명1)|팀명1|프로젝트명1|
|[2](#team-2-팀명2)|팀명2|프로젝트명2|
|[6](#team-6-Brownie)|Brownie|경량화 기법을 활용한 멀티모달 모델의 최적화|
|[40](#team-40-MIND)|MIND|뇌혈류 영상 분석을 통한 알츠하이머 조기 진단|

## Team 1 팀명1
|항목|내용|
|---|---|
|프로젝트명|프로젝트명2|
|프로젝트 키워드||
|트랙||
|프로젝트멤버||
|팀지도교수||
|무엇을 만들고자 하는가||
|고객||
|Pain Point||
|사용할 소프트웨어 패키지의 명칭과 핵심기능/용도, 사용시나리오||
|사용할 소프트웨어 패키지의 명칭과 URL||
|팀그라운드룰||
|최종수정일||

  [Return Top](#2025-Fall-전체-프로젝트-리스트)

## Team 2 팀명2
|항목|내용|
|---|---|
|프로젝트명|프로젝트명2|
|프로젝트 키워드||
|트랙||
|프로젝트멤버||
|팀지도교수||
|무엇을 만들고자 하는가||
|고객||
|Pain Point||
|사용할 소프트웨어 패키지의 명칭과 핵심기능/용도, 사용시나리오||
|사용할 소프트웨어 패키지의 명칭과 URL||
|팀그라운드룰||
|최종수정일||

## Team 6 Brownie
|항목|내용|
|---|---|
|프로젝트명|경량화 기법을 활용한 멀티모달 모델의 최적화|
|프로젝트 키워드|Multi-modal AI(CLIP), 경량화(knowledge distillation or pruning), Loss Function|
|트랙|연구 트랙|
|프로젝트멤버|양인경, 장한나, 정진이|
|팀지도교수|심재형|
|무엇을 만들고자 하는가|멀티모달 모델인 CLIP을 중심으로, 자원이 제한되는 환경에서도 성능은 유지할 수 있도록, knowledge distillation 또는 Pruning 기법을 적용하여 모델을 경량화하고자 합니다.|
|고객|AI/ML 기술을 사용하는 스타트업 또는 기업: 데이터 용량이 제한적이거나, 실시간 응답 속도가 중요한 서비스를 개발하는 기업들은 가벼우면서도 성능이 우수한 모델이 필요로 합니다. 기존의 거대 Transformer 기반 멀티모달 모델은 높은 연산 비용과 느린 추론 속도 때문에 사용하기 어려워, 연구를 통해 빠르고 가벼운 CLIP 모델 제공하고자 합니다.|
|Pain Point|최근 텍스트, 이미지, 음성 등 여러 종류의 데이터를 동시에 이해하고 처리하는 멀티모달(Multi-modal) 모델이 AI 기술의 새로운 핵심으로 부상하고 있습니다. 하지만 멀티모달 모델의 특성상 여러 인코더와 이를 통합하는 복잡한 아키텍처를 가지고, 이는 단일 모델보다 훨씬 더 큰 모델 크기와 많은 연산량을 요구합니다. 이는 곧 배포의 한계, 비용 부담, 환경 문제 등으로 이어지며 기술의 대중화와 실용화를 막는 걸림돌이 되고 있습니다.|
|사용할 소프트웨어 패키지의 명칭과 핵심기능/용도, 사용시나리오| - CLIP: 이미지와 텍스트를 함께 이해하도록 학습된 멀티모달 모델입니다. 핵심 기능은 이미지-텍스트의 동일한 임베딩 공간에 매핑, 대조 학습, 제로샷 분류로 정의됩니다.|
|사용할 소프트웨어 패키지의 명칭과 URL| - CLIP : https://github.com/openai/CLIP|
|팀그라운드룰|https://github.com/TeamBrowniewha/TeamBrownie/blob/main/GroundRule.MD|
|최종수정일|2025.09.16|


## Team 23 Synapse
| 항목 | 내용 |
| --- | --- |
| 프로젝트명 | 다중 GPU에서 효율적인 지식 증류 파이프라인 수행을 위한 모델 파티셔닝 및 스케쥴링 기법 연구 |
| 프로젝트 키워드 | Knowledge Distillation, Model Partitioning, Scheduling, Multi-GPU Training, Distributed Optimization |
| 트랙 | 연구 |
| 프로젝트 멤버 | 김현영, 문원정, 최지희 |
| 팀지도 교수 | 심재형 |
| 무엇을 만들고자 하는가 | Teacher–Student 구조 기반의 지식 증류 과정을 다중 GPU 환경에서 수행할 수 있도록 모델을 파티셔닝하고, GPU 스케줄링을 최적화한 파이프라인 |
| 고객 | GPU 자원 최적화가 중요한 클라우드/AI 인프라 기업 |
| Pain Point | - 기업 AI 엔지니어<br>수십억 파라미터 규모의 LLM을 경량화해 서비스에 적용하려 하지만, 교사·학생 모델을 동시에 학습시키는 과정에서 GPU 메모리가 빠르게 소진된다. 이로 인해 학습 속도가 늦어지고, 모델 배포 일정이 지연된다.<br><br>- 클라우드 인프라 담당자<br> 연구팀들이 대규모 증류 실험을 반복하면서 GPU 자원 사용이 폭증하지만, 분산 처리 효율이 떨어진다. 결국 운영 비용이 불필요하게 커지고, 클러스터 전체 자원 활용률이 낮아진다. |
| 사용할 소프트웨어 패키지의 명칭과 핵심기능/용도 | PyTorch: 기본 딥러닝 프레임워크. 모델 정의, 학습 루프 구현, GPU 연산 지원<br>DeepSpeed: 대규모 모델 학습 최적화. 파이프라인 병렬화, ZeRO 메모리 최적화, 분산 학습 지원 |
| 사용할 소프트웨어 패키지의 명칭과 URL | PyTorch: https://pytorch.org/<br>DeepSpeed: https://www.deepspeed.ai/ |
| 팀그라운드룰 | https://github.com/wonjungm/Synapse/blob/a5cbcfbee38afb6d1e9854926609495f76ede18b/GroundRule.md |
| 최종수정일 | 2025.09.14 |

  [Return Top](#2025-Fall-전체-프로젝트-리스트)

## Team 40 MIND

| 항목 | 내용 |
|------|------|
| 프로젝트명 | 뇌혈류 영상 분석을 통한 알츠하이머 조기 진단 |
| 프로젝트 키워드 | Alzheimer’s disease, Mild Cognitive Impairment, rs-fMRI, ASL, CBF, ALFF, fALFF, ReHo, Functional Connectivity, Dynamic FC, Graph Neural Networks, Transformer, ComBat, Domain Generalization, Explainable AI, Radiomics |
| 트랙 | 연구트랙 |
| 프로젝트 멤버 | 김가영 / 한승연 |
| 팀지도교수 | 황의원 교수님 |
| 무엇을 만들고자 하는가 | BOLD rs-fMRI 및 ASL 기반 뇌혈류 대리지표(ALFF/fALFF/ReHo)와 기능 연결망(FC)을 분석하여 경도인지장애(MCI) 및 초기 알츠하이머(AD)를 조기 탐지할 수 있는 AI 모델을 구축하고, 해석가능성과 일반화 성능을 확보한다. |
| 고객 | - 연구자 및 신경과학자 (뇌혈류/연결망 분석을 통한 신경학적 통찰 제공)<br>- 의료 인공지능 개발자 (조기 진단 알고리즘 및 보정 기법 참고)<br>- 임상 연구자 (MCI/AD 환자군 조기 탐지 연구 지원) |
| Pain Point | - 알츠하이머 조기 진단의 어려움 및 진단 시점 지연<br>- 다기관/다스캐너 데이터 이질성으로 인한 일반화 성능 저하<br>- 소표본/고차원 문제와 과적합 위험<br>- 해석가능성과 재현성 부족 |
| 사용할 소프트웨어 패키지의 명칭과 핵심기능/용도 | - **Python 3.10+**: 개발 언어<br>- **PyTorch / PyTorch Geometric**: 딥러닝, GNN 구현<br>- **MONAI** (옵션): 의료 영상 AI 지원<br>- **scikit-learn**: 전통 ML 모델 (SVM, XGBoost 등)<br>- **Nilearn / NiBabel**: fMRI/신경영상 데이터 로딩 및 전처리<br>- **fMRIPrep** (옵션): 전처리 결과 재사용<br>- **SHAP/Permutation Importance, Grad-CAM**: 모델 해석<br>- **pandas, numpy**: 데이터 처리 |
| 사용할 소프트웨어 패키지의 명칭과 URL | - PyTorch: https://pytorch.org/<br>- PyTorch Geometric: https://pytorch-geometric.readthedocs.io/<br>- MONAI: https://monai.io/<br>- scikit-learn: https://scikit-learn.org/<br>- Nilearn: https://nilearn.github.io/<br>- NiBabel: https://nipy.org/nibabel/<br>- fMRIPrep: https://fmriprep.org/ |
| 팀그라운드룰 URL | https://github.com/mind-ewha/capstone-design/blob/main/GroundRule.md |
| 최종수정일 | 2025-09-16 |


  [Return Top](#2025-Fall-전체-프로젝트-리스트)

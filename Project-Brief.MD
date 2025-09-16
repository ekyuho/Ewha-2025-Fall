# 2025 Fall 전체 프로젝트 리스트
|팀번호|팀명|프로젝트명|
|:---|:---|:---|
|[1](#team-1-팀명1)|팀명1|프로젝트명1|
|[2](#team-2-팀명2)|팀명2|프로젝트명2|
|[35](#team-35-EWIN)|EWIN|시각 장애인을 위한 AI 기반 음성 검색 및 안내 길도우미 서비스|
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


## Team 35 EWIN
|항목|내용|
|---|---|
|프로젝트명|시각 장애인을 위한 AI 기반 음성 검색 및 안내 길도우미 서비스|
|프로젝트 키워드|음성 검색 및 인식(STT), 음성 안내(TTS), 길도우미, GPS, NLP|
|트랙|산학|
|프로젝트 멤버|이지원 이예은 김우빈|
|팀지도교수| 심재형 |
|무엇을 만들고자 하는가|시각장애인을 위해, 화면을 보고 목록을 선택해야 하는 기존 내비게이션의 불편함을 해소하고, 음성 인식을 통한 목적지 검색(STT)부터 음성 대화를 통한 최종 목적지 확정, 그리고 도보 안내(TTS)까지 모든 과정을 음성만으로 제공하는 길도우미 서비스입니다.|
|고객| **&lt;페르소나&gt;** <BR>김땡땡(25세, 여)<br><br>**• 배경**<br>김땡땡 씨는 시각장애인으로, 일상생활에서 대부분 음성 지원 기술과 점자 표시에 의존한다. 어느 무더운 여름날, 그녀는 길을 걷다가 시원한 음료를 사기 위해 가까운 편의점을 찾고 싶었다. 스마트폰으로 목적지를 검색하려 했지만, 화면이 잘 보이지 않아 사용이 매우 번거롭고 불편했다. 기존 시각장애인용 내비게이션 앱은 화면 터치와 안내 선택이 필수여서, 그녀가 원하는 ‘음성만으로 길 안내’는 제공되지 않았다.<br><br>**• 사용자의 요구**<br>&nbsp;&nbsp;- 화면을 보거나 터치하지 않고도 음성 만으로 목적지를 검색하고 안내받고 싶다.<br>&nbsp;&nbsp;-‘가장 가까운 편의점’ 처럼 주변 시설을 거리순으로 쉽게 찾고 안내받고 싶다.<br><br>**• 기대 사항**<br>내 상황과 의도를 파악하여 "가장 가까운 편의점은 OO점입니다. 길안내를 시작할까요?" 와 같이 지능적으로 되묻고, 음성만으로 모든 과정을 완료해주는 서비스를 원한다. |
|Pain Point|현재의 음성 검색 시스템은 사용자가 'GS25 이대역점'처럼 정확한 전체 명칭을 말해야 도착지로 설정합니다. 음성만으로 서비스를 이용하려면 사전에 모든 정확한 정보를 파악하고 있어야 합니다. <BR>예를 들어, '가까운 편의점 찾아줘'라고 검색하면, 시스템은 주변 편의점 전체 목록을 화면에 띄웁니다. 결국 사용자는 안내를 시작하기 위해 다시 화면을 보고 목록을 확인하고 손으로 직접 터치해야만 합니다.|
|사용할 소프트웨어 패키지의 명칭과 핵심기능/용도|**[STT, TTS]** Google Cloud API<BR> **[NLP]** Open AI GPT API<BR> **[LBS]** Naver Maps API<BR> **[백엔드]** Flask<BR> **[앱 개발]** React Native<BR> **[DB]** Firebase Realtime|
|사용할 소프트웨어 패키지의 명칭과 URL|Google Cloud Speech-to-Text API: [https://speech.googleapis.com](https://speech.googleapis.com/)<BR>Google Cloud Text-to-Speech API: [https://texttospeech.googleapis.com](https://texttospeech.googleapis.com/)<BR>Open AI GPT API: https://chatgpt.com/<BR>Naver Maps API: https://navermaps.github.io/maps.js.ncp/<BR>Flask: [https://flask.palletsprojects.com](https://flask.palletsprojects.com/)<BR>React Native: https://ko.legacy.reactjs.org/<BR>Firebase Realtime DB: https://firebase.google.com/products/realtime-database|
|팀그라운드룰|https://github.com/25-2-team35/Capstone/blob/main/GroundRule.md|
|최종수정일|2025.09.16|

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

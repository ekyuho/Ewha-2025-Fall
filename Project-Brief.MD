# 2025 Fall 전체 프로젝트 리스트
|팀번호|팀명|프로젝트명|
|:---|:---|:---|
|[1](#team-1-팀명1)|팀명1|프로젝트명1|
|[2](#team-2-팀명2)|팀명2|프로젝트명2|
|[20](#team-20-POKI)|POKI|**PitchCoach** (스타트업을 위한 AI 기반 IR 피칭 준비 플랫폼)|
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

## Team 20 POKI
| 항목 | 내용 |
|---|---|
| 프로젝트명 | **PitchCoach** (스타트업을 위한 AI 기반 IR 피칭 준비 플랫폼) |
| 프로젝트 키워드 | AI, 스타트업, IR 피칭 |
| 트랙 | 산학 |
| 프로젝트멤버 | 강민경, 김예린, 장현서 |
| 팀지도교수 | 이민수 |
| 무엇을 만들고자 하는가 | 이 프로젝트는 **스타트업 창업자**의 **투자자 피칭(IR)** 준비 전 과정(공고 분석 → Deck 분석 → 리허설(음성) → AI 리포트 → 수정 가이드 → 예상 Q&A 피드백 훈련)을 하나의 흐름으로 연결하여, **1분 엘리베이터 피칭**, **투자 유치 피칭**, **IR 피칭** 등 다양한 피칭 상황에서 창업자가 보다 효율적이고 전문적으로 IR 피칭을 준비할 수 있게 돕는 **올인원 AI 코치** 입니다. |
| 고객 | **다양한 피칭 상황을 준비하는 스타트업 대표** (1분 엘리베이터 피칭, 투자 유치 피칭, IR 피칭 등) |
| Pain Point | 1. **IR 준비 비효율**: 공고별 요구사항에 맞춘 Deck/피칭 준비가 어려움 <br> 2. **실전 대비 부족**: 시간 관리·발화 습관·질문 대응력이 미흡 <br> 3. **정량적 지표 부족**: 발표 후 객관적인 피드백/점수가 없음 <br> 4. **평가자 관점 차이**: 창업자가 강조한 포인트와 VC/심사위원이 궁금한 포인트가 불일치 |
| 사용할 소프트웨어 패키지의 명칭과 핵심기능/용도, 사용시나리오 | 1. **OpenAI Whisper**: 리허설 발표 음성 업로드 → 텍스트 전사 생성 + 다국어 음성 인식(ASR), 발표 전사 <br> 2. **librosa, praat-parselmouth**: 전사된 발표 음성 분석 → 말 빠르기·억양·발음 명료도 진단 + Prosody(억양, 속도, 발음 명료도) 분석 <br> 3. **PDFPlumber**: IR Deck PDF·이미지 업로드 → 슬라이드 텍스트 추출 + 문서 OCR 파싱 <br> 4. **spaCy NER, KeyBERT**: 공고문 업로드 → TAM, LTV, ARR 등 투자 지표·핵심 키워드 추출 + 키워드·지표 분석 <br> 5. **LLM (GPT-4/5)**: 공고문 요약 → 평가 항목 도출 → Deck과 매칭해 부족 섹션 강조 + 문서 요약 및 평가 항목 매칭, IR Deck 분석 → 예상 투자자 질문 5~10개 자동 생성 + 질문 자동 생성 <br> 6. **ko-SBERT, sentence-transformers**: 발표 전사 + Deck 텍스트 분석 → IR 루브릭 점수 대시보드 생성 + 문장 임베딩, 섹션 분류, 루브릭 점수화 <br> 7. **LIME, SHAP**: 점수 결과 리포트 생성 → 점수 근거 문장·슬라이드 하이라이트 표시 + 점수 근거 설명(Explainability) <br> 8. **LLM Fine-tuning**: 예상 질문 답변(음성) → 간결성·정확성·구조성 평가 + 투자자 Q&A 답변 평가 <br> 9. **WebRTC + STT**: 실시간 Q&A 모드 실행 → 30초 제한 내 음성 답변 전사 및 평가 + 실시간 전사 및 Q&A 훈련 <br> 10. **FastAPI, Flink**: 분석 요청 발생 → 서버가 모델 호출 → 결과 API 반환 + 모델 서빙 및 운영 <br> 11. **PostgreSQL, S3**: 발표 파일·공고문·분석 결과 저장 → 리포트 재조회 가능 + 전사·오디오·리포트 저장 |
| 사용할 소프트웨어 패키지의 명칭과 URL | 1. **OpenAI Whisper**: https://github.com/openai/whisper <br> 2. **librosa**: https://librosa.org/ <br> **praat-parselmouth**: https://parselmouth.readthedocs.io/ <br> 3. **PDFPlumber**: https://github.com/jsvine/pdfplumber <br> 4. **spaCy**: https://spacy.io/ <br> **KeyBERT**: https://github.com/MaartenGr/KeyBERT <br> 5. **LLM (GPT-4/5)**: https://platform.openai.com/ <br> 6. **sentence-transformers (ko-SBERT 포함)**: https://www.sbert.net/ <br> 7. **LIME**: https://github.com/marcotcr/lime <br> **SHAP**: https://github.com/shap/shap <br> 8. **HuggingFace Transformers (Fine-tuning)**: https://huggingface.co/transformers/ <br> 9. **WebRTC**: https://webrtc.org/ <br> **Speech-to-Text**: https://cloud.google.com/speech-to-text <br> 10. **FastAPI**: https://fastapi.tiangolo.com/ <br> **Apache Flink**: https://flink.apache.org/ <br> 11. **PostgreSQL**: https://www.postgresql.org/ <br> **Amazon S3**: https://aws.amazon.com/s3/ |
| 팀그라운드룰 | [GroundRule](https://github.com/Capstone-POKI/POKI/blob/main/GroudRuld.MD) |
| 최종수정일 | 2025-09-16 |

  [Return Top](#2025-Fall-전체-프로젝트-리스트)

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

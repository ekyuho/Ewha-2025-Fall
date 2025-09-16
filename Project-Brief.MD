# 2025 Fall 전체 프로젝트 리스트
|팀번호|팀명|프로젝트명|
|:---|:---|:---|
|[1](#team-1-팀명1)|팀명1|프로젝트명1|
|[2](#team-2-팀명2)|팀명2|프로젝트명2|
|[20](#team-20-POKI)|POKI|**PitchCoach** (스타트업을 위한 AI 기반 IR 피칭 준비 플랫폼)|

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
|항목|내용|
|---|---|
| 프로젝트명 | **PitchCoach** (스타트업을 위한 AI 기반 IR 피칭 준비 플랫폼) |
| --- | --- |
| 프로젝트 키워드 | AI, 스타트업, IR 피칭 |
| 트랙 | 산학 |
| 프로젝트멤버 | 강민경, 김예린, 장현서 |
| 팀지도교수 | 이민수 |
| 무엇을 만들고자 하는가 | 이 프로젝트는 **스타트업 창업자**의 **투자자 피칭(IR)** 준비 전 과정(공고 분석 → Deck 분석 → 리허설(음성) → AI 리포트 → 수정 가이드 → 예상 Q&A 피드백 훈련)을 하나의 흐름으로 연결하여, **1분 엘리베이터 피칭**, **투자 유치 피칭**, **IR 피칭** 등 다양한 피칭 상황에서 창업자가 보다 효율적이고 전문적으로 IR 피칭을 준비할 수 있게 돕는 **올인원 AI 코치** 입니다.  |
| 고객 | **다양한 피칭 상황을 준비하는 스타트업 대표** (1분 엘리베이터 피칭, 투자 유치 피칭, IR 피칭 등) |
| Pain Point | 1. **IR 준비 비효율**: 공고별 요구사항에 맞춘 Deck/피칭 준비가 어려움
2. **실전 대비 부족**: 시간 관리·발화 습관·질문 대응력이 미흡
3. **정량적 지표 부족**: 발표 후 객관적인 피드백/점수가 없음
4. **평가자 관점 차이**: 창업자가 강조한 포인트와 VC/심사위원이 궁금한 포인트가 불일치 |
| 사용할 소프트웨어 패키지의 명칭과 핵심기능/용도, 사용시나리오 | 1. **OpenAI Whisper**: 리허설 발표 음성 업로드 → 텍스트 전사 생성 + 다국어 음성 인식(ASR), 발표 전사
2. **librosa, praat-parselmouth**: 전사된 발표 음성 분석 → 말 빠르기·억양·발음 명료도 진단 + Prosody(억양, 속도, 발음 명료도) 분석
3. **PDFPlumber**: IR Deck PDF·이미지 업로드 → 슬라이드 텍스트 추출 + 문서 OCR 파싱
4. **spaCy NER, KeyBERT**: 공고문 업로드 → TAM, LTV, ARR 등 투자 지표·핵심 키워드 추출 + 키워드·지표 분석
5. **LLM (GPT-4/5)**: 공고문 요약 → 평가 항목 도출 → Deck과 매칭해 부족 섹션 강조 + 문서 요약 및 평가 항목 매칭, IR Deck 분석 → 예상 투자자 질문 5~10개 자동 생성 + 질문 자동 생성
6. **ko-SBERT, sentence-transformers**: 발표 전사 + Deck 텍스트 분석 → IR 루브릭 점수 대시보드 생성 + 문장 임베딩, 섹션 분류, 루브릭 점수화
7. **LIME, SHAP**: 점수 결과 리포트 생성 → 점수 근거 문장·슬라이드 하이라이트 표시 + 점수 근거 설명(Explainability)
8. **LLM Fine-tuning**: 예상 질문 답변(음성) → 간결성·정확성·구조성 평가 + 투자자 Q&A 답변 평가
9. **WebRTC + STT**: 실시간 Q&A 모드 실행 → 30초 제한 내 음성 답변 전사 및 평가 + 실시간 전사 및 Q&A 훈련
10. **FastAPI, Flink**: 분석 요청 발생 → 서버가 모델 호출 → 결과 API 반환 + 모델 서빙 및 운영
11. **PostgreSQL, S3**: 발표 파일·공고문·분석 결과 저장 → 리포트 재조회 가능 + 전사·오디오·리포트 저장7 |
| 사용할 소프트웨어 패키지의 명칭과 URL | 1. **OpenAI Whisper**: https://github.com/openai/whisper
2. **librosa:** https://librosa.org/
    **praat-parselmouth**: https://parselmouth.readthedocs.io/
3. **PDFPlumber**: https://github.com/jsvine/pdfplumber
4. **spaCy**: https://spacy.io/
**KeyBERT**: https://github.com/MaartenGr/KeyBERT
5. **LLM (GPT-4/5)**: https://platform.openai.com/
6. **sentence-transformers (ko-SBERT 포함):** https://www.sbert.net/
7. **LIME**: https://github.com/marcotcr/lime
**SHAP**: https://github.com/shap/shap
8. **HuggingFace Transformers (Fine-tuning)**: https://huggingface.co/transformers/
9. **WebRTC**: https://webrtc.org/
**Speech-to-Text** : https://cloud.google.com/speech-to-text
10. **FastAPI**: https://fastapi.tiangolo.com/
**Apache Flink:** https://flink.apache.org/
11. **PostgreSQL**: https://www.postgresql.org/
**Amazon S3**: https://aws.amazon.com/s3/ |
| 팀그라운드룰 | [GroundRule](https://github.com/Capstone-POKI/POKI/blob/main/GroudRuld.MD) |
| 최종수정일 | 2025-09-16 |


  [Return Top](#2025-Fall-전체-프로젝트-리스트)

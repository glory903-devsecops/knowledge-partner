# RAG 기반 도메인 특화 LLM 시스템 설계

도메인별 전문 지식 파트너(Custom GPT) 구축을 위한 Knowledge Repository 입니다.

본 프로젝트는 특정 분야의 전문 지식을 구조화하고  
RAG(Retrieval-Augmented Generation) 기반 GPT와 연동하여  
지식 탐색 효율과 설명 품질을 향상시키는 것을 목표로 합니다.

---

# GPT 바로 사용하기

Information Security Knowledge Partner

https://chatgpt.com/g/g-69d9cfac3f288191be53b8f422550783-jeongbobohogonghag-gpt

---

# 프로젝트 목적

Knowledge Partner 프로젝트는 다음 문제를 해결하기 위해 설계되었습니다.

- 정보 탐색 시간 증가
- 복잡한 개념 구조 이해 어려움
- 도메인별 지식 분산
- 설명 품질의 일관성 부족
- 연구 과정에서 반복되는 개념 정리 비용

이를 해결하기 위해 다음 목표를 설정합니다.

- 지식 구조화
- 개념 간 관계 연결
- 설명 품질 표준화
- 연구 생산성 향상
- 개인 지식 자산화

---

# Core Architecture

Knowledge Partner는 다음 구조를 기반으로 동작합니다.

도메인 문서(PDF, 교재, 논문)

↓

핵심 개념 추출

↓

rag.md 구조화

↓

GPT Knowledge 업로드

↓

대화 기반 개선

↓

finetuning 데이터 축적

↓

지속적 구조 개선

---

# Repository Structure

```
knowledge-partner/

infosec/
README.md
infosec_rag.md
infosec_finetuning.jsonl

counseling/
(예정)

README.md
```

---

# Domain Strategy

각 도메인은 독립적인 Knowledge 구조를 가집니다.

도메인별 특징:

- 전문 용어 체계 유지
- 개념 간 관계 정의
- 연구 수준 설명 구조 확보
- 지식 그래프 확장 가능 구조 유지

---

# Current Domain

## Information Security

정보보호공학 지식 파트너

지원 영역:

- Governance
- Risk Management
- Security Architecture
- Cloud Security
- IAM
- Compliance
- Security Operations
- DevSecOps
- Cryptography
- Network Security
- Application Security
- Incident Response

역할:

- 보안 개념 구조 이해 지원
- 보안 아키텍처 사고 지원
- 시험 대비 개념 체계 정리
- 연구 수준 설명 제공

---

# Design Philosophy

전문 지식은 단순 정보 집합이 아니라 구조입니다.

다음 사고 구조를 기반으로 지식을 정리합니다.

Observation  
핵심 개념 식별

Connection  
관련 개념 연결

Pattern  
반복 구조 발견

Synthesis  
개념 통합 이해

---

# Knowledge Graph Concept

지식은 개별 문서가 아닌 관계 구조로 관리됩니다.

예시 구조:

Risk Management  
→ Asset  
→ Threat  
→ Vulnerability  
→ Control  

IAM  
→ Authentication  
→ Authorization  
→ Zero Trust  

Logging  
→ Detection  
→ Incident Response  
→ Availability  

Cloud Security  
→ Shared Responsibility Model  
→ CSPM  
→ IAM  

---

# RAG Strategy

rag.md는 검색 정확도를 향상시키기 위한 개념 구조 문서입니다.

각 개념은 다음 정보를 포함합니다.

- 개념 정의
- 구성 요소
- 보안 목적
- 관련 개념
- 실무 적용
- 검색 키워드

rag 문서는 다음 목적을 가집니다.

- 검색 품질 향상
- 개념 관계 명확화
- 지식 그래프 구조 형성

---

# Finetuning Strategy

finetuning 데이터는 설명 구조의 일관성을 확보하기 위한 질문-답변 패턴 데이터입니다.

데이터 축적 목적:

- 설명 품질 안정화
- 구조적 답변 유도
- 지식 파트너 일관성 유지

데이터 생성 방식:

- 지식 구조 재구성 질문
- 누락 개념 탐색 질문
- 아키텍처 설명 질문
- 개념 관계 분석 질문

---

# Continuous Improvement Model

Knowledge Partner는 대화를 통해 지속적으로 개선됩니다.

- rag 구조 개선
- 개념 분류 정확도 향상
- 중복 개념 제거
- 누락 개념 식별
- 설명 구조 표준화
- 지식 그래프 확장

---

# Expansion Plan

향후 다음 도메인이 추가될 예정입니다.

- Counseling Psychology
- Cloud Security
- DevSecOps
- AI Security

---

# Expected Benefits

- 연구 생산성 향상
- 지식 탐색 시간 감소
- 설명 품질 향상
- 개념 이해도 증가
- 아키텍처 사고 능력 강화

---

# Operating Principle

Knowledge Partner는 단순 질의응답 시스템이 아니라

지식 구조 이해를 지원하는 연구 파트너를 목표로 합니다.

---

# Long Term Vision

- 도메인별 전문 Knowledge Partner 구축
- 지식 그래프 기반 개인 연구 시스템 구축
- AI 기반 지식 관리 체계 구축

---

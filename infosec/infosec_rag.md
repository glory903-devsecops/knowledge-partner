# Information Security Knowledge Structure

본 문서는 정보보호공학 개념 구조를 정리한 RAG 기반 지식 문서입니다.

PDF 교재 및 강의자료에서 핵심 개념을 추출하여 구조화합니다.

---

# Governance

## ISMS-P

정의
정보보호 및 개인정보보호 관리체계 인증 기준

핵심 영역
관리체계 수립
위험관리
보호대책
사후관리

관련 개념
ISO27001
Compliance
Risk Management

검색 키워드
isms-p
compliance
audit

---

## Risk Management

정의
자산, 위협, 취약점, 영향도를 기반으로 위험 수준을 평가하고 대응 전략을 수립하는 과정

핵심 요소
Asset
Threat
Vulnerability
Impact
Control

관련 개념
ISMS-P
Governance
Risk Assessment

검색 키워드
risk
risk assessment
risk treatment

---

# Security Architecture

## Zero Trust Architecture

정의
어떤 접근도 기본적으로 신뢰하지 않고 지속적으로 검증하는 보안 모델

핵심 원칙
Never Trust
Always Verify
Least Privilege
Assume Breach

구성요소
IAM
MFA
Network Segmentation
Device Trust
Continuous Monitoring

관련 개념
IAM
ZTNA
Conditional Access

검색 키워드
zero trust
zta
least privilege

---

## IAM Identity and Access Management

정의
사용자 신원을 식별하고 접근 권한을 관리하는 보안 체계

핵심 기능
Authentication
Authorization
Account Management
Policy Enforcement

관련 개념
Zero Trust
SSO
RBAC
ABAC

검색 키워드
iam
authentication
authorization

---

# Cloud Security

## Shared Responsibility Model

정의
클라우드 보안 책임을 서비스 제공자와 고객이 분담하는 모델

CSP 책임
물리 인프라
데이터센터
하이퍼바이저

고객 책임
계정 관리
접근 통제
데이터 보호

관련 개념
CSPM
IAM
Cloud Security

검색 키워드
shared responsibility
cloud security responsibility

---

## CSPM Cloud Security Posture Management

정의
클라우드 설정 오류를 탐지하고 보안 상태를 관리하는 기술

핵심 기능
Misconfiguration 탐지
정책 준수 점검
자동 수정 지원

관련 개념
CWPP
Cloud Security
IAM

검색 키워드
cspm
cloud misconfiguration

---

# Security Operations

## SIEM Security Information and Event Management

정의
로그 데이터를 수집하고 이상 징후를 탐지하는 보안 운영 시스템

핵심 기능
로그 수집
이벤트 상관 분석
이상 탐지
경보 생성

관련 개념
SOAR
EDR
Threat Detection

검색 키워드
siem
log monitoring
security monitoring

---

# Cryptography

## Symmetric Key Encryption

정의
동일한 키로 암호화와 복호화를 수행하는 암호 방식

대표 알고리즘
AES
DES
SEED

보안 목적
기밀성 보장

관련 개념
Key Management
Confidentiality
Encryption

검색 키워드
symmetric encryption
AES
secret key

---

## Public Key Cryptography

정의
공개키와 개인키 쌍을 사용하는 암호 방식

대표 알고리즘
RSA
ECC

보안 목적
기밀성
인증
부인방지

관련 개념
PKI
Digital Signature
Key Exchange

검색 키워드
public key
asymmetric encryption

---

## Hash Function

정의
임의 길이 입력 데이터를 고정 길이 출력으로 변환하는 함수

대표 알고리즘
SHA-256
SHA-3

보안 목적
무결성 검증

관련 개념
Digital Signature
Integrity

검색 키워드
hash
digest
sha

---

# Network Security

## Firewall

정의
네트워크 트래픽을 정책에 따라 허용 또는 차단하는 보안 장치

보안 목적
접근 통제
트래픽 필터링

관련 개념
IDS
IPS
Network Segmentation

검색 키워드
firewall
packet filtering

---

## IDS Intrusion Detection System

정의
비정상 트래픽 또는 공격 징후를 탐지하는 시스템

탐지 방식
Signature 기반
Anomaly 기반

관련 개념
IPS
SIEM

검색 키워드
ids
intrusion detection

---

## VPN Virtual Private Network

정의
공용 네트워크를 통해 안전한 통신을 제공하는 기술

대표 프로토콜
IPSec
SSL VPN

보안 목적
기밀성
무결성

관련 개념
Encryption
Network Security

검색 키워드
vpn
ipsec
ssl vpn

---

# Application Security

## OWASP Top 10

정의
웹 애플리케이션 보안 취약점 주요 목록

대표 취약점
Injection
XSS
Broken Authentication
Access Control

보안 목적
웹 보안 취약점 예방

관련 개념
Secure Coding
Input Validation

검색 키워드
owasp
web security

---

# Security Operations

## SIEM

정의
로그 데이터를 수집 분석하여 보안 이벤트를 탐지하는 시스템

핵심 기능
로그 수집
상관 분석
경보 생성

관련 개념
SOAR
Threat Detection

검색 키워드
siem
log analysis

---

## EDR Endpoint Detection and Response

정의
엔드포인트에서 발생하는 위협을 탐지하고 대응하는 보안 기술

기능
행위 기반 탐지
격리
포렌식 데이터 제공

관련 개념
XDR
Endpoint Security

검색 키워드
edr
endpoint detection

---

# Threat Modeling

## MITRE ATT&CK

정의
공격자의 행동 패턴을 분류한 프레임워크

구성
Tactics
Techniques
Procedures

관련 개념
Threat Intelligence
Kill Chain

검색 키워드
mitre attack
threat model

---

# DevSecOps

## SAST

정의
소스코드를 분석하여 보안 취약점을 탐지하는 기술

분석 시점
개발 단계

관련 개념
DAST
Secure SDLC

검색 키워드
sast
static analysis

---

## DAST

정의
실행 중인 애플리케이션을 대상으로 취약점을 탐지하는 기술

관련 개념
SAST
Web Security

검색 키워드
dast
dynamic testing

---

# Supply Chain Security

## SBOM

정의
소프트웨어 구성요소 목록을 관리하는 문서

보안 목적
오픈소스 취약점 관리

관련 개념
Dependency Risk
Software Integrity

검색 키워드
sbom
software bill of materials

---

# AI Security

## AI Security

정의
AI 모델 및 학습 데이터 보호를 위한 보안 영역

위협 유형
Data Poisoning
Model Theft
Prompt Injection

관련 개념
ML Security
Data Integrity

검색 키워드
ai security
ml security

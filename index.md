# Privacy Policy / 개인정보처리방침

**Voyage Ledger**
Last updated: February 2026

------------------------------------------------------------------------

# English Version

## 1. Overview

Voyage Ledger ("the App") is a decision-support and
investment journaling application.

The App is designed with a privacy-first architecture:

-   Decision records are stored locally on the user's device by default.
-   The server does not permanently store user decision logs.
-   The backend primarily handles subscription verification, usage
    control, and secure session authentication.

No account registration is required.

------------------------------------------------------------------------

## 2. Information We Process

Although the App does not require personal information such as name or
email, limited technical information may be processed for service
functionality.

### 2.1 Session & Service Information

-   Anonymous session identifier (JWT)
-   Internal account ID (server-generated)
-   Subscription tier status (Free / Basic / Pro)
-   Monthly usage counters

**Purpose** - Enforce subscription limits\
- Secure authentication\
- Prevent abuse and misuse

This information is stored securely on the backend (Azure App Service).

------------------------------------------------------------------------

### 2.2 Subscription & Purchase Information

Subscriptions are processed via **Google Play Billing**.

The App may process:

-   Purchase token\
-   Product ID\
-   Subscription status

Payment information (e.g., credit card data) is not collected or stored
by the App.\
All payment processing is handled by Google.

------------------------------------------------------------------------

### 2.3 AI Processing (OpenAI API)

When users request AI-based analysis:

-   Prompt content is sent to the backend server.\
-   The server forwards the request to OpenAI API.\
-   The backend does not permanently store prompt contents.\
-   AI responses are returned to the user and optionally stored locally
    on the device.

OpenAI processes data according to its own privacy policy.

------------------------------------------------------------------------

### 2.4 Local Data Storage

The following data is stored locally on the user's device:

-   Decision logs\
-   Timeline records\
-   User-written notes\
-   Exported files (if generated)

This data is not automatically transmitted to the server.

Users are responsible for managing backups or exports.

------------------------------------------------------------------------

## 3. Purpose of Processing

Information is processed solely for:

-   Subscription verification\
-   Usage quota enforcement\
-   Secure authentication\
-   AI-powered analysis\
-   Service stability and abuse prevention

The App does not include advertising SDKs.\
The App does not use marketing trackers.

------------------------------------------------------------------------

## 4. Data Sharing

We do not sell or share personal data.

Limited data may be transmitted to:

-   Google Play (subscription validation)\
-   OpenAI (AI processing requests)

No other third parties receive user data.

------------------------------------------------------------------------

## 5. Data Retention

-   Session and subscription status information are retained only as
    necessary for service operation.\
-   Decision logs remain on the user's device unless manually exported.\
-   Server logs may be retained for operational security and abuse
    prevention.

------------------------------------------------------------------------

## 6. Data Security

-   All communication is encrypted via HTTPS.\
-   Production environment blocks unauthorized header overrides.\
-   Billing verification includes rate limiting.\
-   Session authentication is JWT-based.

------------------------------------------------------------------------

## 7. Children's Privacy

The App is not directed toward children under 13.\
No intentional collection of children's personal data occurs.

------------------------------------------------------------------------

## 8. User Control

Users may:

-   Delete the App to remove locally stored data\
-   Cancel subscriptions through Google Play\
-   Manually delete or export decision logs

------------------------------------------------------------------------

## 9. Contact

Developer: MJ Park\
Email: mjreturns@hotmail.com

------------------------------------------------------------------------

# 한국어 버전

## 1. 개요

Voyage Ledger (투자 항해일지) ("이 앱")은 투자 의사결정 지원 및 기록 관리
애플리케이션입니다.

이 앱은 **프라이버시 우선 구조(Privacy-First Architecture)** 로
설계되었습니다.

-   의사결정 기록은 기본적으로 사용자의 기기 내부에 저장됩니다.\
-   서버는 사용자의 의사결정 로그를 영구 저장하지 않습니다.\
-   백엔드는 구독 검증, 사용량 관리, 세션 인증 기능만을 수행합니다.

회원가입은 요구되지 않습니다.

------------------------------------------------------------------------

## 2. 처리되는 정보

이 앱은 이름, 이메일 등의 개인식별정보를 요구하지 않습니다.\
다만 서비스 운영을 위해 최소한의 기술 정보가 처리될 수 있습니다.

### 2.1 세션 및 서비스 정보

-   익명 세션 식별자 (JWT)\
-   서버 생성 내부 계정 ID\
-   구독 상태 (Free / Basic / Pro)\
-   월간 사용량 정보

**목적** - 구독 등급에 따른 사용 제한 적용\
- 보안 인증 유지\
- 악용 방지

해당 정보는 Azure App Service 기반 서버에 안전하게 저장됩니다.

------------------------------------------------------------------------

### 2.2 구독 및 결제 정보

구독 결제는 **Google Play Billing**을 통해 처리됩니다.

처리될 수 있는 정보:

-   구매 토큰\
-   상품 ID\
-   구독 상태 정보

신용카드 정보 등 결제 정보는 앱 또는 서버에 저장되지 않으며,\
모든 결제 처리는 Google이 담당합니다.

------------------------------------------------------------------------

### 2.3 AI 처리 (OpenAI API)

사용자가 AI 분석을 요청하는 경우:

-   입력한 프롬프트는 서버로 전송됩니다.\
-   서버는 이를 OpenAI API에 전달합니다.\
-   서버는 프롬프트 내용을 영구 저장하지 않습니다.\
-   AI 응답은 사용자에게 반환되며, 필요 시 기기 내에 저장됩니다.

OpenAI의 데이터 처리 방식은 OpenAI의 개인정보처리방침을 따릅니다.

------------------------------------------------------------------------

### 2.4 기기 내 저장 정보

다음 데이터는 사용자 기기에 로컬 저장됩니다:

-   투자 판단 기록\
-   타임라인 기록\
-   사용자 작성 분석 내용\
-   생성된 PDF 등 내보내기 파일

해당 데이터는 자동으로 서버에 전송되지 않습니다.

백업 및 관리 책임은 사용자에게 있습니다.

------------------------------------------------------------------------

## 3. 정보 처리 목적

정보는 다음 목적에 한해 처리됩니다:

-   구독 검증\
-   사용량 제한 적용\
-   보안 인증 유지\
-   AI 분석 기능 제공\
-   서비스 안정성 및 악용 방지

광고 SDK는 포함되어 있지 않습니다.\
마케팅 추적 도구를 사용하지 않습니다.

------------------------------------------------------------------------

## 4. 제3자 제공

개인정보를 판매하거나 공유하지 않습니다.

다만 다음의 경우에 한해 정보가 전달될 수 있습니다:

-   Google Play (구독 검증)\
-   OpenAI (AI 분석 처리)

그 외 제3자에게 제공되지 않습니다.

------------------------------------------------------------------------

## 5. 보관 기간

-   세션 및 구독 상태 정보는 서비스 운영에 필요한 기간 동안만
    유지됩니다.\
-   의사결정 기록은 사용자의 기기에 저장됩니다.\
-   서버 로그는 보안 및 운영 목적 범위 내에서 유지될 수 있습니다.

------------------------------------------------------------------------

## 6. 보안

-   모든 통신은 HTTPS 암호화를 사용합니다.\
-   프로덕션 환경에서는 인증 헤더 우회가 차단됩니다.\
-   결제 검증에는 rate limiting이 적용됩니다.\
-   세션 인증은 JWT 기반입니다.

------------------------------------------------------------------------

## 7. 아동의 개인정보

본 앱은 13세 미만 아동을 대상으로 하지 않습니다.\
아동의 개인정보를 의도적으로 수집하지 않습니다.

------------------------------------------------------------------------

## 8. 사용자 권리

사용자는 다음을 수행할 수 있습니다:

-   앱 삭제를 통한 로컬 데이터 제거\
-   Google Play에서 구독 취소\
-   기록 수동 삭제 또는 내보내기

------------------------------------------------------------------------

## 9. 연락처

개발자: MJ Park
이메일: mjreturns@hotmail.com

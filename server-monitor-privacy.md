# 개인정보처리방침 / Privacy Policy

**Server Monitor**
최종 수정 · Last updated: 2026-03-03

---

## 한국어

### 개요

**Server Monitor**(이하 "앱")는 사용자가 등록한 서버 및 API의 상태를 모니터링하는 iOS 애플리케이션입니다.

본 앱은 사용자의 개인정보를 수집하거나 외부 서버로 전송하지 않습니다. 모든 데이터는 사용자의 기기 내부에만 저장됩니다.

---

### 수집하는 정보

앱은 다음 정보를 사용자의 기기 내부 저장소에만 저장합니다.

- 사용자가 직접 입력한 서버 이름, URL, HTTP 메서드
- 인증 정보 (Bearer Token, API Key 등) — 기기 외부로 전송되지 않습니다
- 체크 주기, 성공 조건 등 앱 설정값
- 마지막 서버 체크 결과 (상태 코드, 응답 시간)

앱은 광고 식별자(IDFA), 위치 정보, 연락처, 카메라 등 민감한 개인정보를 수집하지 않습니다.

---

### 네트워크 요청

앱이 인터넷에 연결하는 경우는 다음 두 가지뿐입니다.

- **서버 상태 체크** — 사용자가 등록한 URL에만 HTTP 요청을 보냅니다. 요청 결과는 기기 내부에만 저장됩니다.
- **공인 IP 조회** — IP 제한 기능 사용 시 `api.ipify.org`에 현재 공인 IP를 조회합니다. 이 외 어떤 데이터도 전송하지 않습니다.

---

### 푸시 알림

서버 이상 감지 시 Push 알림을 발송합니다. Apple 알림 서비스(APNs)를 통해 기기로 전달되며, 알림 내용(서버 이름, 상태)만 포함됩니다.

알림 권한은 기기 설정에서 언제든지 취소할 수 있습니다.

---

### 데이터 보안

- 모든 데이터는 사용자의 기기(로컬 저장소)에만 보관됩니다.
- 개발자 또는 제3자는 사용자 데이터에 접근할 수 없습니다.
- 앱을 삭제하면 모든 저장 데이터가 기기에서 완전히 삭제됩니다.
- Export 기능으로 생성된 JSON 파일의 보안은 사용자 책임입니다.

---

### 아동 개인정보 보호

본 앱은 만 13세 미만 아동을 대상으로 하지 않으며, 아동의 개인정보를 의도적으로 수집하지 않습니다.

---

### 방침 변경

본 개인정보처리방침은 사전 고지 없이 변경될 수 있습니다. 중요한 변경 사항은 앱 업데이트 노트를 통해 안내드립니다.

---

### 문의

개인정보처리방침에 관한 문의는 아래로 연락해 주세요.

- **개발자:** Brad Choi
- **이메일:** krchis@icloud.com

---
---

## English

### Overview

**Server Monitor** ("the App") is an iOS application that monitors the status of servers and APIs registered by the user.

The App does not collect personal information or transmit any data to external servers. All data is stored exclusively on the user's device.

---

### Information We Store

The App stores the following information only in the device's local storage.

- Server names, URLs, and HTTP methods entered by the user
- Authentication credentials (Bearer Token, API Key, etc.) — never transmitted outside the device
- App settings such as check intervals and success conditions
- Last server check results (status code, response time)

The App does not collect advertising identifiers (IDFA), location data, contacts, camera access, or any other sensitive personal information.

---

### Network Requests

The App connects to the internet only in the following two cases.

- **Server health checks** — HTTP requests are sent only to URLs registered by the user. Results are stored locally on the device.
- **Public IP lookup** — When the IP restriction feature is used, the App queries `api.ipify.org` to retrieve the current public IP address. No other data is transmitted.

---

### Push Notifications

The App sends push notifications when a server issue is detected. Notifications are delivered via Apple Push Notification service (APNs) and contain only the server name and status.

Notification permissions can be revoked at any time in your device settings.

---

### Data Security

- All data is stored solely on the user's device (local storage).
- The developer and third parties have no access to user data.
- Deleting the App permanently removes all stored data from the device.
- The security of JSON files created via the Export feature is the user's responsibility.

---

### Children's Privacy

This App is not directed at children under the age of 13, and we do not knowingly collect personal information from children.

---

### Changes to This Policy

This Privacy Policy may be updated without prior notice. Significant changes will be communicated through app update release notes.

---

### Contact

For questions about this Privacy Policy, please contact:

- **Developer:** Brad Choi
- **Email:** krchis@icloud.com

# ATSecu AI 연결 프로그램 — 배포 전용

AI-Sensor 콘솔의 인시던트 AI 분석을 **사용자 본인의 ChatGPT 구독**으로 돌리는 PC 연결 프로그램의 **배포 파일만** 올리는 저장소입니다. 소스 코드는 여기에 없습니다.

- 설치는 AI-Sensor 콘솔 「설정 → AI 분석」에서 받은 파일로 시작합니다. 이 저장소의 릴리스는 연결 프로그램이 **새 버전을 확인하고 받는 곳**입니다.
- 각 릴리스에는 OS별 압축 파일과 `manifest.json`(버전·파일 이름·SHA-256)이 있고, 목록에는 배포자 서명이 붙습니다. 연결 프로그램은 **서명과 해시가 모두 맞을 때만** 설치합니다.
- 압축 파일에는 OpenAI Codex CLI 실행 파일이 함께 들어 있으며, 그 라이선스(Apache-2.0)와 NOTICE 를 같이 싣습니다.

# ATSecu AI Connector — distribution only

Release artifacts for the PC connector that runs AI-Sensor incident analysis on the user's own ChatGPT subscription. No source code is published here. Each release carries per-OS archives plus a signed `manifest.json` (version, file names, SHA-256); the connector installs an update only when both the signature and the hashes match. Bundled OpenAI Codex CLI binaries are redistributed under Apache-2.0 with their LICENSE and NOTICE.

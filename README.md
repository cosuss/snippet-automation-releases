# Snippet Automation 웹 테스트

[웹에서 시작하기](https://cosuss.github.io/snippet-automation-releases/) · [PC 수집기 0.6.0](https://github.com/cosuss/snippet-automation-releases/releases/tag/collector-v0.6.0)

이 저장소는 웹 빌드 결과와 설치·업데이트 파일을 배포합니다. 개발 소스 저장소는 비공개로 유지합니다. 각 사용자의 기록과 API 키는 각자의 PC에 보관합니다.

1. 웹에서 Apple Silicon Mac, Intel Mac 또는 Windows x64용 PC 수집기를 받습니다. macOS 13.5 이상 또는 Windows 10 이상(x64)이 필요합니다.
2. ZIP 전체를 풀고 Mac은 `Start.command`, Windows는 `Start.cmd`를 실행합니다. 필요한 Node.js 런타임은 포함되어 있습니다. Mac 최초 실행 허용이 필요할 수 있습니다.
3. 자동으로 열린 웹 화면에서 반영할 자료와 본인 AI를 연결합니다. 공개 웹 주소에서도 자신의 PC 연결 코드로 연결할 수 있습니다. 브라우저의 로컬 연결 제한이 있으면 수집기가 연 로컬 웹 화면을 사용합니다.
4. 초안을 생성·보완한 뒤 직접 검토하고 승인한 내용만 팀에 게시합니다. 기존 글을 수정할 때는 비교 후 별도로 승인합니다.

수집기는 켜져 있을 때 동작합니다. PC 재부팅 후에는 Start 파일로 다시 실행하세요. 웹의 업데이트 메뉴에서 수집기 자동 설치 또는 예약 일시를 설정할 수 있습니다. 자동·예약 설치는 진행 중인 작업과 저장하지 않은 입력이 없고 PC를 5분 이상 사용하지 않았을 때 진행합니다. 웹 화면은 새로고침 시 최신 버전을 받습니다.

회의 도구·Orca·카카오톡은 현재 내보낸 파일 연결을 지원합니다. 해당 서비스의 화면 자동 조작과 Safari 활동 수집은 준비 중입니다. 실제 외부 계정 연결·유료 AI 호출·펄스 게시와 다른 사용자의 최초 설치는 추가 검증이 필요합니다. 펄스 평가 90점은 보장하지 않습니다. 본인 구독 계정 사용에는 공식 AI 실행 도구의 설치·로그인이 필요합니다.

[기존 Electron 앱 안내](https://cosuss.github.io/snippet-automation-releases/desktop/)도 유지합니다. 기존 앱 업데이트와 PC 수집기 업데이트는 별도이며, 기존 앱의 키와 자료를 수집기로 자동 이전하지 않습니다.

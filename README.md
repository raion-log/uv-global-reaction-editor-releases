# UV 글로벌 반응 편집기 다운로드

Windows x64용 `UV 글로벌 반응 편집기` 공개 다운로드 저장소입니다.

## 현재 테스트 버전

- 제품 버전: `1.2.0`
- 배포 단계: `v1.2.0-rc.4` 내부 테스트 후보
- 설치 파일: `UV-Global-Reaction-Editor_1.2.0_x64-setup.exe`
- SHA-256: `4325764e7450885733391eed70cde60ff46dbc7132ddb254c8c94e4c2a73e813`
- 운영체제: Windows 10/11 x64

[Windows x64 설치기 바로 다운로드](https://github.com/raion-log/uv-global-reaction-editor-releases/releases/download/v1.2.0-rc.4/UV-Global-Reaction-Editor_1.2.0_x64-setup.exe)

### RC4에서 확인한 수정

- 시작 전에 같은 YouTube 검사를 중복 실행하던 대기를 제거해 진행 화면을 즉시 표시합니다.
- 공식 yt-dlp nightly `2026.8.18.122307.dev0`을 고정해 중간 Range 403을 해결했습니다.
- 실제 실패 작업을 보존된 15MB 지점에서 재개해 335,692,809바이트 MP4 병합까지 확인했습니다.
- 실패·재시도 중에도 입력 URL, 자막, 작업 ID와 기존 결과를 보존합니다.

현재 후보는 코드서명 전 내부 테스트용입니다. Windows 경고가 표시될 수 있으며, 새 PC 설치·첫 설정 검증이 끝나기 전에는 정식 배포본으로 간주하지 않습니다.

# 모두의 도구 허브 1.7.0

[Windows 설치](https://github.com/qnsekd301/modu-tools-releases/releases/download/hub-win32-x64/ModuHub-Setup-1.7.0-win-x64.exe) · [Mac 설치 ZIP](https://github.com/qnsekd301/modu-tools-releases/releases/download/packages/mac-installer-darwin-any-1.7.0-0f90266e5b1b.zip)

필요한 도구만 설치하고 자동으로 업데이트합니다.

도구 카드의 **삭제**에서 사용자가 직접 제거합니다. 프로그램·바로가기·자동 실행을 정리하며 다운로드·문서와 별도 사용자 자료는 유지합니다. 삭제한 도구는 자동 업데이트로 다시 설치하지 않습니다. 다시 필요하면 설치하기를 누릅니다.

| 도구 | 실행 위치 |
|---|---|
| 쉬운성경 | 바탕화면 → Windows CMD / Mac 터미널 |
| 유튜브 다운로드 · 성경주석검색기 | 바탕화면 → 독립 프로그램 |
| PDF | Windows 파일 우클릭 / Mac 빠른 동작·서비스 |
| ZIP · 와이파이 | 로그인 자동 시작. 허브 → 시작 설정 |

PDF·ZIP·와이파이는 바탕화면 아이콘을 만들지 않습니다. 기존 허브의 해당 아이콘은 확인된 것만 백업합니다. ZIP과 Wi-Fi는 기존 Windows 프로그램의 --worker / --run 명령을 그대로 사용합니다. Wi-Fi 시작 작업은 한 번의 관리자 승인이 필요합니다. 변경은 다음 로그인부터 적용하며 현재 네트워크를 바꾸지 않습니다.

허브와 도구별 사용법은 3~6단계입니다. PDF는 파일 선택·우클릭·부가기능 호버·2/4/6/8쪽 배치·결과물·인쇄, 자동 도구는 등록·사용·중지/재개를 안내합니다. 나중에 보기와 진행 상태를 기억하며 완료한 안내는 반복하지 않습니다. 허브의 사용법 또는 ?에서 다시 엽니다.

Mac 설치: ZIP 전체를 풀고 맥에 설치.command를 실행합니다. macOS 13 이상, Intel·Apple Silicon. Apple Developer 가입·Python·Homebrew 별도 설치는 필요하지 않습니다. **Mac 실기기에서 실행·권한·자동 시작·교체는 아직 미검증입니다.** 두 CPU 번들, Finder 서비스 파일, 선택 파일 전달, PDF 배치, 화면과 체크섬을 검사했습니다.

관리자는 바탕화면의 모두의 도구 관리자 → 관리자 → ＋ 새 프로그램에서 Windows·Mac 빌드를 등록합니다. 이후 해당 빌드 경로의 변경을 감지해 GitHub Releases로 게시합니다. 관리자 PC가 꺼져 있어도 배포 파일을 받습니다. 실행 중인 프로그램은 종료 후 교체하고, 자동 실행 도구는 다음 로그인에 준비한 최신 버전을 사용합니다. 소스 저장과 실행 파일 빌드는 별도입니다. admin-data는 공유하지 않습니다.

디자인 참고: [Awwwards Superlist](https://www.awwwards.com/sites/superlist). Finder 서비스 구성: [Apple Services Properties](https://developer.apple.com/library/archive/documentation/Cocoa/Conceptual/SysServices/Articles/properties.html).

검사: npm test · npm run verify · scripts/verify-native-launcher.ps1 · python scripts/verify-personal-mac.py

설치 파일: 공유할 설치파일 / 검사 결과: test-output

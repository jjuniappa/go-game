모바일 바둑 교차점 터치 수정 버전

핵심 수정:
- 기존: 각 칸 영역/button을 눌러 착수
- 수정: 바둑판 전체 터치 좌표를 읽어서 가장 가까운 줄 교차점으로 착수
- 교차점에서 너무 멀리 누른 경우 착수하지 않음
- 터치 시 빨간 미리보기 표시

GitHub 업로드:
1. ZIP 압축을 풉니다.
2. 기존 go-game 저장소에서 Add file > Upload files를 누릅니다.
3. index.html, manifest.json, service-worker.js, icons 폴더, README_설치방법.txt를 업로드합니다.
4. Commit changes를 누릅니다.
5. Pages 주소를 새로고침합니다.

캐시 문제:
- 휴대폰에서 이전 버전이 보이면 홈 화면 앱을 완전히 종료 후 재실행하세요.
- 그래도 안 되면 브라우저 캐시 삭제 또는 1~3분 후 새로고침하세요.

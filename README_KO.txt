우리의 일본어 성장 대결! - 완성 파일

포함 기능
- 참여 코드 없이 한 링크로 접속
- 카게야마 / 츠키시마 선택
- 개인 XP, 레벨, 공동 1,000 XP 목표
- JLPT N5 단어장, 플래시카드, 5문제 퀴즈, 일본어 음성
- 캐릭터 성장 이미지 15장 포함

중요
이 프로젝트는 정적 HTML만 올리는 방식이 아닙니다. Worker와 D1 데이터베이스가 함께 배포되어야 두 사람의 점수가 공유됩니다.

폴더 구조
- public/index.html: 웹사이트
- public/assets/: 캐릭터 이미지
- worker.js: 공유 점수 API
- schema.sql: D1 테이블
- wrangler.toml: Cloudflare 배포 설정

현재 만든 D1 데이터베이스를 사용하려면 wrangler.toml의 PASTE_YOUR_D1_DATABASE_ID_HERE를 본인의 Database ID로 바꿔야 합니다.

배포에는 Cloudflare Workers Builds(GitHub 연결) 또는 Wrangler CLI가 필요합니다. 아이폰만으로 진행할 경우 GitHub에 파일을 올리고 Cloudflare에서 GitHub 저장소 연결을 설정하는 방법을 사용할 수 있지만, 계정 화면에 따라 추가 설정이 필요할 수 있습니다.

참고: 로그인/개인 인증은 없으며, 링크를 아는 사람은 누구나 같은 점수판에 점수를 추가할 수 있습니다. 지인끼리만 공유하세요.

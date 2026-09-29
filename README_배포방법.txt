SAFE24 홈페이지 · GitHub / Netlify 배포 안내
========================================

1. 압축 파일을 풉니다.
2. GitHub에서 새 저장소를 만듭니다. 예: safe24-website
3. 저장소의 Add file → Upload files에서 압축을 푼 폴더 안의
   index.html, assets 폴더, netlify.toml을 함께 업로드하고 Commit changes를 누릅니다.
   ZIP 파일 자체만 업로드하면 홈페이지가 표시되지 않습니다.
4. Netlify에서 Add new project → Import an existing project → GitHub를 선택하고
   방금 만든 저장소를 연결합니다.
5. 배포 설정을 확인합니다.
   Build command: 비워 둠
   Publish directory: . (점 한 글자)
   netlify.toml에 같은 설정이 포함되어 있습니다.
6. Deploy를 누르고 발급된 주소에서 이미지와 상품 카테고리 클릭,
   전화 연결, 네이버폼 상담 버튼을 확인합니다.

파일 구조
index.html        화면·스타일·동작을 포함한 메인 파일
assets/           로고 및 사이트 이미지 전체
netlify.toml      Netlify 배포 폴더 설정

상담 연결 정보
전화: 010-9768-0911
네이버폼: https://naver.me/Gagkn8Zo

참고
- AI로 제작한 상품 및 설치 구성 이미지는 실제 설치 사례가 아닙니다.
- 창업 비용과 운영 역할은 실제 견적·계약 조건 확정 후 문구를 수정하세요.
- 이 파일 묶음은 현재 샘플 사이트의 정적 버전입니다. 별도 관리자 기능은 없습니다.
- Google Fonts에 연결할 수 없는 환경에서는 시스템 글꼴로 표시됩니다.

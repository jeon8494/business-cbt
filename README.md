# 경영학 CBT 배포 순서

1. Supabase 프로젝트 > SQL Editor > New query에서 `supabase_setup.sql` 전체 실행
2. Table Editor에서 `questions` 25행 확인
3. Authentication > Providers에서 Email 활성화 확인
4. 이 폴더의 파일들을 GitHub 새 저장소에 업로드
5. Vercel > Add New > Project > GitHub 저장소 선택
6. Framework Preset: Other, 별도 Build Command 없이 Deploy
7. 배포 주소에서 회원가입/로그인 후 문제를 풀고 다른 기기에서 같은 계정으로 로그인해 동기화 확인

현재 정답은 사용자가 제공한 가답안입니다. 공식 정답 발표 후 DB 값을 교체하면 됩니다.

주의: 이 프로젝트에는 Publishable key만 들어 있습니다. service_role/secret key는 절대 프런트엔드에 넣지 마세요.

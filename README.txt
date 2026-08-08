성경골든벨 — 배포용 프로젝트

[처음 배포하기]
1. 이 폴더를 새 GitHub 저장소(예: bible-goldenbell)에 올린다.
2. Vercel(https://vercel.com)에서 New Project → 이 GitHub 저장소를 Import.
   - Framework Preset: Vite (자동 인식됨)
   - 그대로 Deploy → 1~2분 후 공개 주소(URL)가 나옴.
3. 그 URL을 아이들에게 나눠주면 각자 폰에서 사용.
   (폰에서 열고 "홈 화면에 추가" 하면 앱 아이콘처럼 됨)

[내 컴퓨터에서 미리보기 - 선택]
  npm install
  npm run dev

[나중에 내용 수정 후 업데이트]
  git add .
  git commit -m "수정 내용"
  git push
  → Vercel이 자동으로 다시 배포함.

* 하트/XP/레벨은 각자 폰(브라우저)에 저장됩니다(localStorage).

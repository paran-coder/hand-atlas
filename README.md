# HAND ATLAS v4.5.1 — 74개 손 포즈

GitHub 및 Vercel 정적 사이트 배포용입니다. 관리자 기능은 없습니다.

## 내용
- `index.html`: 손 포즈 검색/열람, 상세 이미지 및 영어 프롬프트 복사
- `assets/`: 실제 표시되는 이미지 74개 (WebP)

기존 ID는 바꾸지 않았습니다. 제거된 ID: 27, 35, 37, 38, 40, 51.
52번은 새 포즈로 변경했습니다.

## GitHub/Vercel
1. ZIP을 압축 해제합니다.
2. `index.html`과 `assets/` 폴더를 저장소 루트에 업로드합니다.
3. Vercel에서 정적 사이트로 배포합니다 (Framework Preset: Other).
4. HTML의 상대 경로 때문에 `index.html`을 단독으로 이동하면 이미지는 표시되지 않습니다.

웹 브라우저에서 바로 확인하려면 별도 제공된 `HAND-ATLAS-v4.5.1-74-offline-preview.html` 파일을 사용하세요. (이미지 내장)

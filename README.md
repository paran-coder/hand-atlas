# HAND ATLAS v4.5.2 — 74개 손 포즈

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

웹 브라우저에서 바로 확인하려면 별도 제공된 `HAND-ATLAS-v4.5.2-74-offline-preview.html` 파일을 사용하세요. (이미지 내장)


## Open Graph 공유 이미지 (v4.5.2)

- 공유 주소: https://hand-atlas.vercel.app/
- 공유 이미지: /og-image.png (1200×630 PNG)
- index.html의 head에 Open Graph, X(Twitter) Card 및 canonical 태그가 포함되어 있습니다.
- GitHub에는 압축을 푼 파일을 저장소 루트에 올리세요. Vercel 배포 후 이미지 URL이 정상으로 열리는지 확인하세요.
- SNS에서 이전 미리보기가 남을 경우 해당 서비스의 공유 캐시가 새 배포로 갱신되지 않았을 수 있습니다.

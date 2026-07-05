# 문기동 · 물류 DX 포트폴리오 데모

## 🔗 공개 링크 (면접자에게 이 주소를 공유하세요)
- 랜딩(한국어): **https://kdmoon-eng.github.io/portfolio-demo/**
- 랜딩(English): **https://kdmoon-eng.github.io/portfolio-demo/index-en.html**
- B2B 출고 PDA 데모: **https://kdmoon-eng.github.io/portfolio-demo/b2b-pda.html**
- OB 출고 분석 대시보드 데모: **https://kdmoon-eng.github.io/portfolio-demo/ob/index.html**
- IB 입고·스태핑 대시보드 데모: **https://kdmoon-eng.github.io/portfolio-demo/ib/index.html**
- 입고검수·적치 PDA 데모: **https://kdmoon-eng.github.io/portfolio-demo/inbound-pda.html**
- 재고보충 PDA 데모: **https://kdmoon-eng.github.io/portfolio-demo/replenish-pda.html**
- 저장소(공개): https://github.com/kdmoon-eng/portfolio-demo

## 💻 내 PC에서 바로 확인 (인터넷 없이)
이 폴더의 파일을 **더블클릭**하면 브라우저에서 바로 열립니다:
- `index.html` — 포트폴리오 랜딩 페이지
- `b2b-pda.html` — B2B 출고 PDA **인터랙티브 데모**
- `ob/index.html` — OB 출고 분석 **대시보드 데모** (실제 React·recharts 빌드 그대로, 백엔드 없이 가짜 데이터로 동작)
- `ib/index.html` — IB 입고·**스태핑 분석 대시보드 데모** (실제 React·recharts 빌드 그대로, 백엔드 없이 가짜 데이터로 동작)
- `inbound-pda.html` — 입고검수·적치 **PDA 데모** (모바일, 인터랙티브)
- `replenish-pda.html` — 재고보충 **PDA 데모** (모바일, 인터랙티브)

## ⚠️ 안전
백엔드에 연결되지 않으며, 모든 고객사·품목·수량 데이터(오리·너구리 등)는 **브라우저 안의 가짜 데이터**입니다. 실제 **API 키·비밀번호·데이터베이스 접속정보**는 포함하지 않습니다. (실제 앱을 그대로 빌드한 대시보드라, 일부 내부 센터명 등 명칭 표기가 소스에 남아 있을 수 있습니다.)

## 배포
정적 사이트 → GitHub Pages(GitHub Actions)로 자동 배포. `main`에 push하면 링크가 자동 갱신됩니다. (Vercel을 쓰려면 vercel.com/new에서 이 저장소 import 1번)

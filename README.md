# 취업 스펙 인식 설문조사

취업 스펙 인식 조사 결과 시각화 웹페이지입니다.

## 로컬 실행

```bash
npm install
npm start
```

브라우저에서 `http://localhost:3000` 접속

## GitHub + Railway 배포 방법

### 1. GitHub에 올리기

```bash
git init
git add .
git commit -m "Initial commit"
git branch -M main
git remote add origin https://github.com/<your-username>/<repo-name>.git
git push -u origin main
```

### 2. Railway 배포

1. [railway.app](https://railway.app) 접속 후 로그인
2. **New Project** → **Deploy from GitHub repo** 선택
3. 위에서 만든 GitHub 저장소 선택
4. Railway가 자동으로 `npm install` 및 `npm start` 실행
5. **Settings → Networking → Generate Domain** 으로 퍼블릭 URL 생성

배포 완료 후 자동으로 URL이 생성됩니다.

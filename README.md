# 커피전문점 개인사업자 재무전략 웹사이트

## 📋 배포 파일

이 폴더는 GitHub Pages 배포를 위한 파일들입니다.

## 🚀 배포 방법

### 방법 1: GitHub 웹 인터페이스 (추천)

1. **Code 탭으로 이동**
   - 저장소 페이지에서 상단의 **`Code`** 탭 클릭
   - 저장소가 비어있으면 자동으로 파일 업로드 안내가 표시됩니다

2. **파일 업로드**
   - **`Add file`** → **`Upload files`** 클릭
   - 이 폴더(`coffee-shop-deploy`)의 모든 파일과 폴더를 드래그 앤 드롭
   - **`Commit changes`** 클릭

3. **GitHub Pages 활성화**
   - **`Settings`** → **`Pages`** 클릭
   - Source: **`main`** 브랜치, **`/ (root)`** 선택
   - **`Save`** 클릭

### 방법 2: Git 명령어

Windows에서 `deploy.bat` 파일을 더블클릭하거나, 터미널에서:
```bash
cd owner-strategy/coffee-shop-deploy
deploy.bat
```

### 방법 3: 수동 Git 명령어

```bash
cd owner-strategy/coffee-shop-deploy
git init
git remote add origin https://github.com/SynItArt/coffee-shop-strategy.git
git add .
git commit -m "Deploy: 커피전문점 개인사업자 재무전략 웹사이트"
git branch -M main
git push -u origin main --force
```

## 📁 파일 구조

```
coffee-shop-deploy/
├── index.html                    # 메인 페이지 (리다이렉트)
├── coffee-shop-main.html          # 커피전문점 재무전략 메인 페이지
├── css/                          # 스타일시트
├── js/                           # 자바스크립트
├── presentations/                # 프레젠테이션 파일
└── 개인사업자/                    # 제안서 파일
    └── 커피전문점_컴포즈_2매장_쌍둥이아빠_재무전략_제안서.html
```

## 🔗 배포 후 접속 URL

```
https://synitart.github.io/coffee-shop-strategy/
```

또는

```
https://synitart.github.io/coffee-shop-strategy/coffee-shop-main.html
```

## ⚠️ 주의사항

- 모든 파일이 올바른 경로에 있는지 확인하세요
- 상대 경로가 올바르게 설정되어 있는지 확인하세요
- 배포 후 링크가 정상 작동하는지 테스트하세요


# 🚀 카카오뱅크 신용정보 앱 - GitHub Pages 배포 가이드

## 📦 저장소 정보
- **Repository 이름**: `kakaobank-credit-k7m9x2`
- **계정**: Wonyoon-Luciel
- **공개 설정**: Public (URL 아는 사람만 접속 가능)

---

## 🔧 1단계: GitHub 저장소 만들기

### 1. GitHub 로그인
https://github.com 접속 후 로그인

### 2. 새 저장소 생성
1. 우측 상단 **+** 버튼 → **New repository** 클릭
2. 다음과 같이 설정:
   ```
   Repository name: kakaobank-credit-k7m9x2
   Description: 카카오뱅크 신용정보 프로토타입 (선택사항)
   Public ✅ (체크)
   Add a README file ❌ (체크 해제)
   ```
3. **Create repository** 클릭

---

## 📤 2단계: 파일 업로드

### 방법 A: 웹 인터페이스 사용 (추천)

1. 생성된 저장소 페이지에서 **uploading an existing file** 클릭
2. 다음 2개 파일을 드래그 앤 드롭:
   - `index.html`
   - `README.md`
3. 하단에 Commit message: "Initial commit" 입력
4. **Commit changes** 클릭

### 방법 B: Git 명령어 사용

```bash
git init
git add index.html README.md
git commit -m "Initial commit"
git branch -M main
git remote add origin https://github.com/Wonyoon-Luciel/kakaobank-credit-k7m9x2.git
git push -u origin main
```

---

## ⚙️ 3단계: GitHub Pages 활성화

1. 저장소 페이지에서 **Settings** 탭 클릭
2. 왼쪽 메뉴에서 **Pages** 클릭
3. **Source** 섹션에서:
   - Branch: `main` 선택
   - Folder: `/ (root)` 선택
4. **Save** 클릭
5. 2-3분 대기 (빌드 시간)

---

## 🌐 4단계: 접속 확인

### 배포 완료 후 URL:
```
https://wonyoon-luciel.github.io/kakaobank-credit-k7m9x2/
```

### 각 화면 URL:
```
홈 화면:     https://wonyoon-luciel.github.io/kakaobank-credit-k7m9x2/
신용정보:    https://wonyoon-luciel.github.io/kakaobank-credit-k7m9x2/#credit
카드 상세:   https://wonyoon-luciel.github.io/kakaobank-credit-k7m9x2/#card
대출 상세:   https://wonyoon-luciel.github.io/kakaobank-credit-k7m9x2/#loan
연체 상세:   https://wonyoon-luciel.github.io/kakaobank-credit-k7m9x2/#overdue
보증 상세:   https://wonyoon-luciel.github.io/kakaobank-credit-k7m9x2/#guarantee
```

---

## 📱 5단계: iPhone에 추가하기

### Safari에서 접속 후:
1. 하단 **공유** 버튼 (사각형에 화살표) 클릭
2. **홈 화면에 추가** 선택
3. 이름 입력: "카카오뱅크"
4. **추가** 클릭

→ 이제 앱처럼 사용 가능! 🎉

---

## 🔒 보안 팁

### URL 보호하기:
1. **저장소를 검색엔진에서 숨기기**:
   - 저장소 루트에 `robots.txt` 파일 추가:
   ```
   User-agent: *
   Disallow: /
   ```

2. **URL을 아는 사람만 공유**:
   - Public이지만 URL을 모르면 찾기 어려움
   - Google에서 검색해도 안 나옴 (robots.txt 덕분)

3. **필요시 저장소 삭제**:
   - Settings → Danger Zone → Delete this repository

---

## 🛠️ 문제 해결

### 404 에러가 나는 경우:
- 2-3분 더 대기 (빌드 시간)
- Settings → Pages에서 배포 상태 확인

### 화면이 이상하게 보이는 경우:
- 브라우저 캐시 삭제
- 시크릿 모드로 재접속

### 수정이 필요한 경우:
- GitHub에서 index.html 파일 수정
- 또는 로컬에서 수정 후 재업로드

---

## 📞 도움이 필요하면

저장소 Issues 탭에서 질문하거나, 
이 문서를 참고해서 단계별로 진행하세요!

**예상 소요 시간**: 5-10분

---

Made with ❤️ for Team 505

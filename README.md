# 펫스킨 AI - 법적 문서 HTML (한국어/영어/일본어)

GitHub Pages (goldman79.github.io)에 올릴 6개 HTML 파일.

---

## 📦 파일 목록

| 파일 | 내용 | App Store URL |
|---|---|---|
| `privacy-ko.html` | 한국어 개인정보 처리방침 | https://goldman79.github.io/privacy-ko.html |
| `privacy-en.html` | 영어 Privacy Policy | https://goldman79.github.io/privacy-en.html |
| `privacy-ja.html` | 일본어 プライバシーポリシー | https://goldman79.github.io/privacy-ja.html |
| `terms-ko.html` | 한국어 이용약관 | https://goldman79.github.io/terms-ko.html |
| `terms-en.html` | 영어 Terms of Service | https://goldman79.github.io/terms-en.html |
| `terms-ja.html` | 일본어 利用規約 | https://goldman79.github.io/terms-ja.html |

---

## 🚀 업로드 방법

### 옵션 A: GitHub 웹에서 직접 업로드 (간단)

1. https://github.com/goldman79/goldman79.github.io 접속
2. **Add file → Upload files**
3. 6개 HTML 파일 드래그 앤 드롭
4. **Commit changes**

기존 `index.html`은 그대로 두셔도 되고, 원하시면:
- `index.html`을 `terms-ko.html`로 이름 변경
- 또는 새 `index.html`을 만들어서 6개 페이지 링크 모아둔 랜딩 페이지로 만들기

### 옵션 B: 로컬 Git으로 푸시

```bash
cd ~/path/to/goldman79.github.io
# HTML 파일 6개 복사
git add .
git commit -m "Add multilingual privacy & terms pages"
git push
```

### 업로드 후 확인

각 URL이 정상 작동하는지 확인:
- https://goldman79.github.io/privacy-ko.html
- https://goldman79.github.io/privacy-en.html
- https://goldman79.github.io/privacy-ja.html
- https://goldman79.github.io/terms-ko.html
- https://goldman79.github.io/terms-en.html
- https://goldman79.github.io/terms-ja.html

GitHub Pages 반영까지 보통 1~2분 소요.

---

## 🎨 디자인 특징

- **펫스킨 AI 앱과 일관된 디자인** (크림 배경 + 세이지 그린 액센트)
- **언어 전환 토글** 우측 상단에 항상 표시 (한국어 / EN / 日本語)
- **반응형 디자인** (모바일/PC 모두 깔끔)
- **가독성** 한국어/영어/일본어 모두 시스템 폰트로 자연스럽게 표시
- **응급 안내** 강조 박스 (빨간 좌측 보더)

---

## 🎯 App Store Connect 입력

### 한국어 로컬라이제이션
- 개인정보 정책 URL: `https://goldman79.github.io/privacy-ko.html`
- (선택) 이용약관 URL: `https://goldman79.github.io/terms-ko.html`

### 영어 로컬라이제이션
1. App Store Connect → 펫스킨 AI → 좌측 **앱 정보**
2. 우측 상단 드롭다운 → **English (U.S.)** 선택
3. 개인정보 정책 URL: `https://goldman79.github.io/privacy-en.html`
4. (선택) 이용약관 URL: `https://goldman79.github.io/terms-en.html`
5. **저장**

### 일본어 로컬라이제이션
1. 드롭다운 → **Japanese** 선택
2. 개인정보 정책 URL: `https://goldman79.github.io/privacy-ja.html`
3. (선택) 이용약관 URL: `https://goldman79.github.io/terms-ja.html`
4. **저장**

---

## ⚠️ 주의사항

### 기존 한국어 URL 변경

v1.0 출시할 때 사용한 URL이 **Gist 주소**(`https://gist.github.com/goldman79/cd9c46b672588406be6bc932f50b7453`)였어요. 이제 `https://goldman79.github.io/privacy-ko.html`로 바꿔야 일관성이 있어요.

### v2.0.1에서 URL 변경

새 버전(v2.0.1) 출시 시 한국어 처방 URL도 새로운 GitHub Pages URL로 업데이트하시는 게 좋아요. 그래야 3개 언어가 같은 도메인에서 관리됨.

### 시행일 업데이트

각 HTML 파일 하단에 "**최종 업데이트: 2026년 5월 / 시행일: 2026년 5월**"로 표시되어 있어요. v2.0.1 출시 후 정확한 날짜로 업데이트하시는 게 좋아요. 

업데이트 방법: HTML 파일에서 "2026년 5월", "May 2026", "2026年5月" 부분을 찾아 수정.

---

## 🧪 미리보기

각 HTML 파일을 더블클릭하면 브라우저에서 바로 미리보기 가능. 디자인 확인 후 마음에 안 들면 알려주세요.

언어 토글 버튼도 잘 작동하는지 확인:
- 영어 페이지에서 **한국어** 클릭 → privacy-ko.html로 이동
- 일본어 페이지에서 **EN** 클릭 → privacy-en.html로 이동

(단, 업로드 전에는 클릭해도 같은 디렉토리에 6개 파일이 모두 있어야 작동함)

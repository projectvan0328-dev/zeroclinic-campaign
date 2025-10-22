# 🚀 Vercel 배포 3분 완성 가이드

## 📦 배포 전 체크리스트

✅ index.html 파일 준비 완료
✅ images 폴더 생성 완료
⚠️ **이미지 파일 추가 필요** (campaign-main.jpg, campaign-thumb.jpg)

---

## 🎯 빠른 배포 방법

### 옵션 1: GitHub + Vercel (가장 추천! ⭐)

#### 1단계: GitHub에 업로드
```bash
# GitHub에서 새 저장소 생성 (예: campaign-website)
# 로컬에서 실행:

git init
git add .
git commit -m "Initial commit"
git branch -M main
git remote add origin https://github.com/계정명/저장소명.git
git push -u origin main
```

#### 2단계: Vercel 배포
1. https://vercel.com 접속
2. GitHub 계정으로 로그인
3. "Add New" → "Project" 클릭
4. GitHub 저장소 선택
5. "Deploy" 클릭
6. **완료! 🎉** 자동으로 URL 생성됨

---

### 옵션 2: 직접 업로드 (초간단!)

1. https://vercel.com 접속 및 로그인
2. "Add New" → "Project" 클릭
3. 프로젝트 폴더를 드래그 앤 드롭
4. "Deploy" 클릭
5. **완료! 🎉**

---

## 🖼️ 이미지 추가 방법

### 임시로 빠르게 테스트하기
1. 아무 JPG 이미지 2개 준비
2. 파일명을 각각 변경:
   - `campaign-main.jpg` (메인 이미지)
   - `campaign-thumb.jpg` (썸네일)
3. `images` 폴더에 복사
4. 배포!

### 실제 이미지로 교체하기
1. Vercel 대시보드에서 프로젝트 선택
2. "Deployments" 탭
3. 최신 배포 선택
4. 파일 업로드 또는 GitHub 업데이트
5. 자동으로 재배포됨

---

## 🎨 무료 이미지 다운로드 사이트

이미지가 없다면 여기서 다운로드:
- Unsplash: https://unsplash.com
- Pexels: https://pexels.com
- Pixabay: https://pixabay.com

검색어 추천: "medical", "clinic", "beauty treatment"

---

## ⚙️ 배포 후 설정

### 커스텀 도메인 연결 (선택사항)
1. Vercel 프로젝트 대시보드
2. "Settings" → "Domains"
3. 도메인 입력 및 DNS 설정

### 환경 변수 설정 (필요시)
1. "Settings" → "Environment Variables"
2. 변수 추가

---

## 🔧 문제 해결

### 배포는 됐는데 이미지가 안 보여요
→ `images` 폴더에 파일명 확인
   - `campaign-main.jpg` ✅
   - `Campaign-Main.jpg` ❌ (대소문자 구분!)

### 페이지가 깨져 보여요
→ 브라우저 캐시 삭제 (Ctrl + Shift + R)

### 수정사항이 반영 안 돼요
→ GitHub 푸시 후 자동 재배포 대기 (1-2분)

---

## 📞 추가 도움이 필요하면

Vercel 공식 문서: https://vercel.com/docs
한글 가이드: https://vercel.com/docs/ko

---

💜 **배포 성공을 응원합니다!**

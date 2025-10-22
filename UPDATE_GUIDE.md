# 🔄 사이트 수정 및 업데이트 가이드

## 📝 수정된 내용

✅ **파비콘 추가**: 브라우저 탭에 아이콘 표시
✅ **이미지 영역 편집 버튼 제거**: 편집 모드에서도 이미지 편집 버튼이 나타나지 않음

---

## 🚀 업데이트 방법

### 방법 1: GitHub 웹에서 직접 수정 (가장 쉬움!)

1. **GitHub 저장소 접속**
   ```
   https://github.com/projectvan0328-dev/zeroclinic-campaign
   ```

2. **index.html 파일 클릭**

3. **연필 아이콘(Edit) 클릭**

4. **수정된 내용 붙여넣기**
   - 제가 만든 새 index.html 내용을 복사해서 붙여넣기

5. **Commit changes 클릭**
   - Commit message: "파비콘 추가 및 이미지 편집 버튼 제거"

6. **자동 배포 완료!**
   - Vercel이 자동으로 감지해서 재배포 (1-2분 소요)

---

### 방법 2: 파일 전체 교체

1. **GitHub 저장소에서 index.html 삭제**
   - 파일 클릭 → 우측 상단 [...] → Delete file

2. **새 파일 업로드**
   - Add file → Upload files
   - 수정된 index.html 드래그 앤 드롭
   - Commit changes

3. **파비콘 이미지 추가**
   - images 폴더 클릭
   - Add file → Upload files
   - favicon.png 업로드
   - Commit changes

---

### 방법 3: Git 명령어 사용

```bash
# 1. 저장소 클론 (처음만)
git clone https://github.com/projectvan0328-dev/zeroclinic-campaign.git
cd zeroclinic-campaign

# 2. 파일 수정
# index.html을 새 버전으로 교체
# images/favicon.png 추가

# 3. 변경사항 커밋
git add .
git commit -m "파비콘 추가 및 이미지 편집 버튼 제거"

# 4. GitHub에 푸시
git push origin main
```

---

## 📂 필요한 파일

### 1. index.html (수정됨)
- ✅ 파비콘 링크 추가됨
- ✅ 이미지 영역 편집 버튼 제거됨

### 2. images/favicon.png (새로 추가)
- 32x32px 또는 64x64px PNG 이미지
- 파비콘 제작 방법은 `FAVICON_GUIDE.md` 참고

---

## ✨ 앞으로 수정할 때

### HTML 내용 수정하기
1. GitHub에서 index.html 편집
2. 원하는 부분 수정
3. Commit → 자동 배포!

### 이미지 교체하기
1. GitHub의 images 폴더 접속
2. 기존 이미지 삭제
3. 새 이미지 업로드 (같은 파일명으로!)
4. Commit → 자동 배포!

### 새 페이지 추가하기
1. GitHub에서 Add file → Create new file
2. 파일명 입력 (예: about.html)
3. 내용 작성
4. Commit → 자동 배포!

---

## 🔍 배포 상태 확인

### Vercel 대시보드에서 확인
1. https://vercel.com 접속
2. zeroclinic-campaign 프로젝트 클릭
3. Deployments 탭에서 배포 진행 상황 확인

### 실시간 로그 보기
- 배포 클릭 → Building 단계 확인
- 에러 발생 시 로그에서 원인 확인 가능

---

## 🛠️ 자주 하는 수정

### 1. 텍스트 내용 변경
- GitHub에서 index.html 편집
- 원하는 텍스트 찾아서 수정
- Commit!

### 2. 색상 변경
- `<style>` 태그 내부에서 색상 코드 수정
- 예: `#9b6dff` → `#ff6b9d`

### 3. 이미지 교체
- GitHub의 images 폴더에서 파일 업로드
- 파일명은 동일하게 유지

### 4. 관리자 비밀번호 변경
- index.html에서 `admin1234` 검색
- 원하는 비밀번호로 변경

---

## ⚠️ 주의사항

1. **파일명 유지하기**
   - index.html은 반드시 index.html로!
   - 이미지 파일명도 동일하게 유지

2. **문법 오류 주의**
   - HTML/CSS 수정 시 괄호, 세미콜론 확인
   - 에러 발생 시 Vercel 로그 확인

3. **캐시 삭제**
   - 수정사항이 안 보이면 Ctrl + Shift + R

---

## 📞 문제 해결

### 배포가 실패했어요
→ Vercel 대시보드에서 에러 로그 확인

### 이미지가 안 보여요
→ 파일명과 경로 확인 (대소문자 구분!)

### 수정사항이 반영 안 돼요
→ GitHub 커밋 확인 + Vercel 재배포 대기 (1-2분)

---

💜 **수정이 필요하면 언제든 도와드릴게요!**

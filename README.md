# 🎯 제로클리닉 캠페인 가이드라인 웹사이트

캠페인 정보를 효율적으로 관리하고 공유할 수 있는 반응형 웹사이트입니다.

## 📁 프로젝트 구조

```
project/
├── index.html              # 메인 HTML 파일 (campaign_detail_improved.html을 복사)
├── images/                 # 이미지 폴더
│   ├── campaign-main.jpg   # 메인 캠페인 이미지
│   └── campaign-thumb.jpg  # 썸네일 이미지
└── README.md              # 프로젝트 설명
```

## 🚀 Vercel 배포 방법

### 1단계: 파일 준비
1. `campaign_detail_improved.html` 파일명을 `index.html`로 변경
2. `images` 폴더 생성
3. 사용할 이미지를 `images` 폴더에 추가:
   - `campaign-main.jpg` (메인 이미지, 권장 크기: 600x600px)
   - `campaign-thumb.jpg` (썸네일 이미지, 권장 크기: 80x80px)

### 2단계: Vercel에 배포

#### 방법 A: GitHub 연동 (권장)
1. GitHub에 새 저장소 생성
2. 모든 파일을 저장소에 푸시
3. [Vercel](https://vercel.com) 접속 및 로그인
4. "New Project" 클릭
5. GitHub 저장소 선택
6. "Deploy" 클릭

#### 방법 B: 직접 업로드
1. [Vercel](https://vercel.com) 접속 및 로그인
2. "New Project" 클릭
3. "Browse" 탭에서 폴더 전체를 드래그 앤 드롭
4. "Deploy" 클릭

### 3단계: 배포 완료
- 자동으로 HTTPS URL 생성 (예: `your-project.vercel.app`)
- 배포 후 즉시 접속 가능

## ✨ 주요 기능

- **반응형 디자인**: 모바일, 태블릿, 데스크톱 모두 지원
- **관리자 모드**: 내용 수정 가능 (비밀번호: `admin1234`)
- **다중 지점 지원**: 신사점 탭 구조
- **실시간 편집**: 관리자 모드에서 직접 수정 가능

## 🎨 이미지 권장 사양

- **메인 이미지**: 600x600px 이상, JPG/PNG
- **썸네일**: 80x80px 이상, JPG/PNG
- 파일 크기: 각 이미지 1MB 이하 권장

## 🔧 커스터마이징

### 색상 변경
HTML 파일의 `<style>` 섹션에서 색상 코드 수정:
- 메인 색상: `#9b6dff`, `#7c3aed`
- 배경색: `#f5f0ff`, `#e9dcff`

### 내용 수정
1. 웹사이트 접속
2. 우측 하단 "관리자 모드" 버튼 클릭
3. 비밀번호 입력 (기본값: `admin1234`)
4. 편집할 영역의 연필 아이콘 클릭
5. 내용 수정 후 저장

## 📞 지원

문제가 발생하면 담당자에게 문의해주세요.

---

💜 Made with love for 제로클리닉

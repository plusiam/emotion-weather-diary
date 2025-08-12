# 🌈 나의 감정 날씨 일기

> 한국 초등학생을 위한 인터랙티브 감정 일기 | Interactive emotion diary for Korean elementary students using weather metaphors

[![Version](https://img.shields.io/badge/version-2.2-blue.svg)](https://github.com/plusiam/emotion-weather-diary)
[![License](https://img.shields.io/badge/license-MIT-green.svg)](LICENSE)
[![HTML5](https://img.shields.io/badge/HTML5-E34F26?logo=html5&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/HTML)
[![TailwindCSS](https://img.shields.io/badge/Tailwind_CSS-38B2AC?logo=tailwind-css&logoColor=white)](https://tailwindcss.com)

## 📌 소개

**나의 감정 날씨 일기**는 초등학생들이 자신의 감정을 날씨에 비유하여 표현하고, 신체 감각과 연결하여 이해할 수 있도록 돕는 웹 기반 교육 도구입니다. 아이들이 감정을 인식하고 표현하는 능력을 키우며, 정서적 자기조절 능력을 향상시킬 수 있습니다.

### 🎯 주요 특징
- 🌦️ **8가지 날씨 메타포**로 감정 표현
- 🧘 **신체 감각과 감정 연결** 학습
- 🎨 **감정의 색상 표현** 기능
- 💾 **자동저장** 및 **이미지/PDF 저장** 지원
- 📱 **반응형 디자인**으로 모바일/태블릿 완벽 지원
- ♿ **웹 접근성** 준수 (스크린리더, 키보드 네비게이션)

## 🚀 바로 사용하기

### 온라인 버전
[https://plusiam.github.io/emotion-weather-diary/](https://plusiam.github.io/emotion-weather-diary/)

### 로컬 실행
```bash
# 저장소 클론
git clone https://github.com/plusiam/emotion-weather-diary.git

# 디렉토리 이동
cd emotion-weather-diary

# 브라우저에서 index.html 파일 열기
# 또는 간단한 HTTP 서버 실행
python -m http.server 8000
# 브라우저에서 http://localhost:8000 접속
```

## 📖 사용 방법

### 1. 기본 정보 입력
- 날짜 선택
- 학년/반 입력
- 이름 입력

### 2. 감정 날씨 선택
8가지 날씨 중 현재 감정과 가장 비슷한 날씨를 선택합니다:

| 날씨 | 감정 상태 |
|------|----------|
| ☀️ 맑음 | 기쁨, 즐거움, 행복 |
| ☁️ 흐림 | 무덤덤, 심심함 |
| 🌧️ 비 | 슬픔, 우울함 |
| ⛈️ 폭풍 | 화남, 짜증, 분노 |
| ❄️ 눈 | 차분함, 평온함 |
| 🌈 무지개 | 희망, 기대, 설렘 |
| 🌬️ 바람 | 불안, 초조함 |
| 🌫️ 안개 | 혼란, 막막함 |

### 3. 신체 변화 기록
- 인터랙티브 신체 다이어그램에서 변화가 있는 부위 클릭
- 각 부위별 구체적인 증상 기록

### 4. 감정의 원인 탐색
- 무슨 일이 있었는지
- 그때 어떤 생각이 들었는지
- 다음에는 어떻게 하고 싶은지

### 5. 감정 색상 선택
- 8가지 색상 중 현재 감정을 표현하는 색 선택

### 6. 저장 및 공유
- 📸 **이미지 저장**: PNG 파일로 다운로드
- 🖨️ **인쇄**: 2페이지 형식으로 인쇄
- 🔄 **다시 작성**: 새로운 일기 작성

## 🏫 교육 활용 방안

### 수업 활용
- **아침 활동**: 하루를 시작하며 감정 체크인
- **종례 시간**: 하루를 마무리하며 감정 정리
- **상담 활동**: 개별 상담 시 감정 탐색 도구로 활용
- **SEL 프로그램**: 사회정서학습 프로그램과 연계

### 기대 효과
1. **감정 인식 능력 향상**: 자신의 감정을 구체적으로 인식
2. **감정 표현 능력 발달**: 다양한 방식으로 감정 표현
3. **신체 감각 인식**: 감정과 신체 반응의 연결 이해
4. **메타인지 발달**: 감정의 원인과 결과 분석
5. **자기 조절 능력**: 향후 대처 방안 계획

## 🛠️ 기술 스택

- **HTML5**: 시맨틱 마크업
- **Tailwind CSS**: 유틸리티 기반 스타일링
- **Vanilla JavaScript**: 프레임워크 없는 순수 자바스크립트
- **html2canvas**: 이미지 캡처 기능
- **Local Storage**: 자동저장 기능

## 💻 브라우저 지원

| 브라우저 | 지원 버전 |
|---------|----------|
| Chrome | 90+ |
| Firefox | 88+ |
| Safari | 14+ |
| Edge | 90+ |
| Mobile Chrome | 90+ |
| Mobile Safari | 14+ |

## 📱 주요 기능 상세

### 자동저장
- 모든 입력은 1초 후 자동으로 브라우저에 저장
- 페이지 새로고침 시 자동으로 복원
- 저장 완료 시 상단에 인디케이터 표시

### 접근성
- 스크린리더 완벽 지원 (ARIA 레이블)
- 키보드 네비게이션 (Tab, 방향키, Enter)
- 고대비 모드 지원
- 모바일 터치 영역 최적화 (최소 48px)

### 인쇄 최적화
- A4 용지 2페이지 자동 분할
- 불필요한 요소 자동 제거
- 입력 내용 깔끔한 텍스트로 변환

### 파일명 규칙
이미지 저장 시 체계적인 파일명 자동 생성:
- 형식: `감정날씨일기_YYYYMMDD_학년반_이름.png`
- 예시: `감정날씨일기_20250812_5학년2반_홍길동.png`

## 🔄 버전 히스토리

### v2.2 (2025.08.12)
- 인쇄 시 2페이지 자동 분할
- 이미지 저장 파일명 개선
- Toast 알림 메시지 강화

### v2.1 (2025.08.01)
- 자동저장 기능 추가
- 웹 접근성 강화
- 모바일 반응형 개선

### v2.0 (2025.07.15)
- 신체 다이어그램 인터랙티브 기능
- 감정 색상 선택 기능
- 복합 감정 표현 옵션

### v1.0 (2025.06.01)
- 초기 버전 출시
- 8가지 감정 날씨 선택
- 기본 저장 기능

## 👥 기여하기

이 프로젝트는 오픈소스입니다. 기여를 환영합니다!

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📝 라이선스

이 프로젝트는 MIT 라이선스 하에 배포됩니다. 자유롭게 사용, 수정, 배포하실 수 있습니다.

## 🙏 감사의 말

이 도구를 사용해주시는 모든 선생님들과 학생들에게 감사드립니다. 아이들의 정서적 성장에 도움이 되기를 바랍니다.

## 📧 문의

- GitHub Issues: [이슈 등록하기](https://github.com/plusiam/emotion-weather-diary/issues)
- Email: [이메일 주소]

---

**Made with ❤️ for Korean Elementary Students**

*"감정을 이해하는 것은 자신을 이해하는 첫걸음입니다"*
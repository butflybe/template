# 템플릿 변수 목록

이 문서는 템플릿에서 사용되는 모든 변수들의 완전한 목록입니다.

## 📋 프로젝트 기본 정보

| 변수명 | 설명 | 예시 |
|--------|------|------|
| `{{PROJECT_NAME}}` | 프로젝트명 (영문) | "Surcly", "MyApp" |
| `{{PROJECT_NAME_KR}}` | 프로젝트명 (한국어) | "서클리", "마이앱" |
| `{{PROJECT_ID}}` | 프로젝트 ID (숫자 포함) | "0001.surcly", "0002.myapp" |
| `{{NEXT_PROJECT_ID}}` | 다음 프로젝트 ID | "0002", "0003" |
| `{{PROJECT_VISION}}` | 프로젝트 비전 | "다양성과 단순함이 만나는 곳..." |
| `{{PROJECT_MISSION}}` | 프로젝트 미션 | "다양하고 간단한 컨텐츠를..." |
| `{{LAST_MODIFIED_DATE}}` | 최종 수정일 | "2024-01-24" |
| `{{CREATED_DATE}}` | 생성일 | "2024-01-24" |

## 🎯 사이트 목적 & 목표

| 변수명 | 설명 | 예시 |
|--------|------|------|
| `{{PURPOSE_1_TITLE}}` | 주요 목적 1 제목 | "컨텐츠 집약" |
| `{{PURPOSE_1_DESC}}` | 주요 목적 1 설명 | "다양한 종류의 유용한 컨텐츠를..." |
| `{{PURPOSE_2_TITLE}}` | 주요 목적 2 제목 | "접근성" |
| `{{PURPOSE_2_DESC}}` | 주요 목적 2 설명 | "누구나 쉽고 빠르게..." |
| `{{PURPOSE_3_TITLE}}` | 주요 목적 3 제목 | "다국어 지원" |
| `{{PURPOSE_3_DESC}}` | 주요 목적 3 설명 | "언어 장벽 없는..." |
| `{{PURPOSE_4_TITLE}}` | 주요 목적 4 제목 | "사용자 경험" |
| `{{PURPOSE_4_DESC}}` | 주요 목적 4 설명 | "직관적이고 효율적인..." |

## 👥 타겟 사용자

| 변수명 | 설명 | 예시 |
|--------|------|------|
| `{{PRIMARY_TARGET_NAME}}` | 주요 타겟 사용자명 | "글로벌 정보 탐색자" |
| `{{PRIMARY_TARGET_DESC}}` | 주요 타겟 설명 | "다양한 정보와 도구를 찾는 사람들" |
| `{{PRIMARY_TARGET_AGE}}` | 주요 타겟 연령대 | "20-40대" |
| `{{PRIMARY_TARGET_CHARACTERISTICS}}` | 주요 타겟 특성 | "효율성을 중시하며..." |
| `{{SECONDARY_TARGET_1}}` | 부차 타겟 1 | "컨텐츠 크리에이터" |
| `{{SECONDARY_TARGET_1_DESC}}` | 부차 타겟 1 설명 | "참고 자료와 도구를..." |
| `{{SECONDARY_TARGET_2}}` | 부차 타겟 2 | "학습자" |
| `{{SECONDARY_TARGET_2_DESC}}` | 부차 타겟 2 설명 | "새로운 정보와 자료를..." |
| `{{SECONDARY_TARGET_3}}` | 부차 타겟 3 | "전문가" |
| `{{SECONDARY_TARGET_3_DESC}}` | 부차 타겟 3 설명 | "업무나 연구에 필요한..." |

## 🌍 다국어 지원

| 변수명 | 설명 | 예시 |
|--------|------|------|
| `{{SUPPORTED_LANGUAGES}}` | 지원 언어 (간단) | "ko/en/ja/es" |
| `{{SUPPORTED_LANGUAGES_FULL}}` | 지원 언어 (전체) | "한국어(ko), English(en), 日本語(ja), Español(es)" |
| `{{SUPPORTED_LANGUAGES_COUNT}}` | 지원 언어 개수 | "4" |
| `{{LOCALIZATION_FILES_COUNT}}` | 로컬라이제이션 파일 개수 | "6" |
| `{{LOCALIZATION_KO_PREFERENCE}}` | 한국어 사용자 선호도 | "정중하고 체계적인 정보 제공 선호" |
| `{{LOCALIZATION_EN_PREFERENCE}}` | 영어 사용자 선호도 | "효율적이고 직접적인 소통 선호" |
| `{{LOCALIZATION_JA_PREFERENCE}}` | 일본어 사용자 선호도 | "세심하고 품질 높은 서비스 기대" |
| `{{LOCALIZATION_ES_PREFERENCE}}` | 스페인어 사용자 선호도 | "관계 중심적이고 따뜻한 접근 선호" |

## 🔧 기술 사양

### 프론트엔드
| 변수명 | 설명 | 예시 |
|--------|------|------|
| `{{FRONTEND_FRAMEWORK}}` | 프론트엔드 프레임워크 | "Next.js 14+ (React 18+)" |
| `{{FRONTEND_LANGUAGE}}` | 프론트엔드 언어 | "TypeScript" |
| `{{FRONTEND_STYLING}}` | 스타일링 도구 | "Tailwind CSS" |
| `{{FRONTEND_UI_COMPONENTS}}` | UI 컴포넌트 | "Headless UI / Radix UI" |
| `{{FRONTEND_ICONS}}` | 아이콘 라이브러리 | "Heroicons / Lucide React" |

### 백엔드
| 변수명 | 설명 | 예시 |
|--------|------|------|
| `{{BACKEND_DATABASE}}` | 데이터베이스 | "Supabase (PostgreSQL)" |
| `{{BACKEND_DATABASE_NAME}}` | 데이터베이스명 | "Supabase" |
| `{{BACKEND_DATABASE_LOWER}}` | 데이터베이스명 (소문자) | "supabase" |
| `{{BACKEND_AUTH}}` | 인증 시스템 | "Supabase Auth" |
| `{{BACKEND_STORAGE}}` | 파일 저장소 | "Supabase Storage" |
| `{{BACKEND_API}}` | API 시스템 | "Next.js API Routes + Supabase Client" |

### 배포
| 변수명 | 설명 | 예시 |
|--------|------|------|
| `{{DEPLOYMENT_HOSTING}}` | 호스팅 서비스 | "Vercel" |
| `{{DEPLOYMENT_HOSTING_LOWER}}` | 호스팅 서비스 (소문자) | "vercel" |
| `{{DEPLOYMENT_DOMAIN}}` | 도메인 | "Custom Domain (TBD)" |
| `{{DEPLOYMENT_CDN}}` | CDN 서비스 | "Vercel Edge Network" |
| `{{DEPLOYMENT_ANALYTICS}}` | 분석 도구 | "Vercel Analytics" |

### 국제화 & 성능
| 변수명 | 설명 | 예시 |
|--------|------|------|
| `{{I18N_LIBRARY}}` | 국제화 라이브러리 | "next-i18next" |
| `{{I18N_MANAGEMENT}}` | 번역 관리 | "Manual (Initial)" |
| `{{PERFORMANCE_IMAGES}}` | 이미지 최적화 | "Next.js Image" |
| `{{PERFORMANCE_CACHING}}` | 캐싱 시스템 | "Vercel Edge Caching" |
| `{{PERFORMANCE_BUNDLE}}` | 번들 분석 | "Bundle Analyzer" |

### 기타
| 변수명 | 설명 | 예시 |
|--------|------|------|
| `{{TECH_STACK_SUMMARY}}` | 기술스택 요약 | "Next.js + Supabase + Vercel" |
| `{{DEVELOPMENT_FILES_COUNT}}` | 개발 파일 개수 | "5" |

## 📱 지원 플랫폼

| 변수명 | 설명 | 예시 |
|--------|------|------|
| `{{PLATFORM_DESKTOP}}` | 데스크톱 지원 | "Chrome, Firefox, Safari, Edge (최신 2버전)" |
| `{{PLATFORM_MOBILE}}` | 모바일 지원 | "iOS Safari, Android Chrome" |
| `{{PLATFORM_TABLET}}` | 태블릿 지원 | "iPad, Android Tablet" |
| `{{ACCESSIBILITY_STANDARD}}` | 접근성 표준 | "WCAG 2.1 AA 준수" |

## ⚡ 성능 목표

| 변수명 | 설명 | 예시 |
|--------|------|------|
| `{{PERFORMANCE_PAGE_LOAD}}` | 페이지 로드 시간 | "< 3초 (3G), < 1초 (WiFi)" |
| `{{PERFORMANCE_LANGUAGE_SWITCH}}` | 언어 전환 시간 | "< 1초" |
| `{{PERFORMANCE_SEARCH}}` | 검색 응답 시간 | "< 500ms" |
| `{{PERFORMANCE_IMAGE_LOADING}}` | 이미지 로딩 방식 | "Progressive loading 적용" |
| `{{PERFORMANCE_SEO_SCORE}}` | SEO 점수 목표 | "> 90점 (Lighthouse)" |

## 🎨 브랜드 정체성

| 변수명 | 설명 | 예시 |
|--------|------|------|
| `{{BRAND_KEYWORDS}}` | 브랜드 키워드 | "Simple, Diverse, Accessible, Global" |
| `{{BRAND_TONE}}` | 톤앤매너 | "친근하고 전문적, 신뢰할 수 있는" |
| `{{BRAND_DIFFERENTIATION}}` | 차별점 | "다양성과 단순함의 조화" |

### 디자인 원칙
| 변수명 | 설명 | 예시 |
|--------|------|------|
| `{{DESIGN_PRINCIPLE_1}}` | 디자인 원칙 1 | "미니멀리즘" |
| `{{DESIGN_PRINCIPLE_1_DESC}}` | 디자인 원칙 1 설명 | "불필요한 요소 제거, 핵심에 집중" |
| `{{DESIGN_PRINCIPLE_2}}` | 디자인 원칙 2 | "일관성" |
| `{{DESIGN_PRINCIPLE_2_DESC}}` | 디자인 원칙 2 설명 | "모든 페이지에서 통일된 디자인 언어" |
| `{{DESIGN_PRINCIPLE_3}}` | 디자인 원칙 3 | "접근성" |
| `{{DESIGN_PRINCIPLE_3_DESC}}` | 디자인 원칙 3 설명 | "모든 사용자가 쉽게 사용할 수 있는 디자인" |
| `{{DESIGN_PRINCIPLE_4}}` | 디자인 원칙 4 | "반응형" |
| `{{DESIGN_PRINCIPLE_4_DESC}}` | 디자인 원칙 4 설명 | "모든 디바이스에서 최적화된 경험" |

### UX 원칙
| 변수명 | 설명 | 예시 |
|--------|------|------|
| `{{UX_PRINCIPLE_1}}` | UX 원칙 1 | "직관성" |
| `{{UX_PRINCIPLE_1_DESC}}` | UX 원칙 1 설명 | "설명 없이도 사용 가능한 인터페이스" |
| `{{UX_PRINCIPLE_2}}` | UX 원칙 2 | "효율성" |
| `{{UX_PRINCIPLE_2_DESC}}` | UX 원칙 2 설명 | "최소한의 클릭으로 원하는 정보 접근" |
| `{{UX_PRINCIPLE_3}}` | UX 원칙 3 | "일관성" |
| `{{UX_PRINCIPLE_3_DESC}}` | UX 원칙 3 설명 | "예측 가능한 상호작용 패턴" |
| `{{UX_PRINCIPLE_4}}` | UX 원칙 4 | "피드백" |
| `{{UX_PRINCIPLE_4_DESC}}` | UX 원칙 4 설명 | "사용자 액션에 대한 명확한 반응" |

## 📊 성공 지표 (KPI)

### 사용자 지표
| 변수명 | 설명 | 예시 |
|--------|------|------|
| `{{KPI_MAU_TARGET}}` | 월간 활성 사용자 목표 | "Phase 1 목표 500명" |
| `{{KPI_SESSION_DURATION}}` | 세션 지속 시간 | "평균 3분 이상" |
| `{{KPI_PAGE_VIEWS}}` | 페이지 뷰 | "월 2,000 PV" |
| `{{KPI_RETURN_RATE}}` | 재방문율 | "30% 이상" |

### 기술 지표
| 변수명 | 설명 | 예시 |
|--------|------|------|
| `{{KPI_LOAD_SPEED}}` | 페이지 로드 속도 | "평균 2초 이하" |
| `{{KPI_ERROR_RATE}}` | 에러율 | "1% 이하" |
| `{{KPI_UPTIME}}` | 가동률 | "99.5% 이상" |
| `{{KPI_MOBILE_USAGE}}` | 모바일 사용률 | "60% 이상" |

### 다국어 지표
| 변수명 | 설명 | 예시 |
|--------|------|------|
| `{{KPI_LANGUAGE_USAGE}}` | 언어별 사용률 | "각 언어 최소 10% 이상" |
| `{{KPI_TRANSLATION_COMPLETION}}` | 번역 완성도 | "95% 이상" |
| `{{KPI_LANGUAGE_SWITCHING}}` | 언어 전환율 | "20% 이상" |

### 정성적 지표
| 변수명 | 설명 | 예시 |
|--------|------|------|
| `{{KPI_USER_SATISFACTION}}` | 사용자 만족도 | "설문조사 4.0/5.0 이상" |
| `{{KPI_ACCESSIBILITY}}` | 접근성 점수 | "WCAG 2.1 AA 준수" |
| `{{KPI_BRAND_AWARENESS}}` | 브랜드 인지도 | "커뮤니티 언급 및 추천" |
| `{{KPI_CONTENT_QUALITY}}` | 컨텐츠 품질 | "사용자 피드백 기반 평가" |

## 📝 컨텐츠 관련 변수

| 변수명 | 설명 | 예시 |
|--------|------|------|
| `{{CONTENT_TYPE_NAME}}` | 컨텐츠 타입명 | "ContentA", "Blog", "Gallery" |
| `{{CONTENT_PRIORITY}}` | 컨텐츠 우선순위 | "High", "Medium", "Low" |
| `{{CONTENT_STATUS}}` | 컨텐츠 상태 | "임시 (컨텐츠 미정)", "개발 중", "완료" |
| `{{CONTENT_OWNER}}` | 컨텐츠 담당자 | "개발자", "디자이너", "기획자" |
| `{{CONTENT_DEFINITION}}` | 컨텐츠 정의 | "임시 컨텐츠 - 추후 구체적인 내용 결정 예정" |
| `{{CONTENT_NOTES}}` | 컨텐츠 메모 | "개발 초기 단계용 임시 컨텐츠" |

### 사용자 목표
| 변수명 | 설명 | 예시 |
|--------|------|------|
| `{{USER_GOAL_1}}` | 사용자 목표 1 | "TBD (To Be Determined)" |
| `{{USER_GOAL_2}}` | 사용자 목표 2 | "효율적인 정보 탐색" |
| `{{USER_GOAL_3}}` | 사용자 목표 3 | "다국어 컨텐츠 접근" |

### 비즈니스 목표
| 변수명 | 설명 | 예시 |
|--------|------|------|
| `{{BUSINESS_GOAL_1}}` | 비즈니스 목표 1 | "TBD (To Be Determined)" |
| `{{BUSINESS_GOAL_2}}` | 비즈니스 목표 2 | "사용자 참여도 증가" |
| `{{BUSINESS_GOAL_3}}` | 비즈니스 목표 3 | "글로벌 시장 확장" |

### 기능 관련
| 변수명 | 설명 | 예시 |
|--------|------|------|
| `{{REQUIRED_FEATURE_1}}` | 필수 기능 1 | "기본 목록 표시" |
| `{{REQUIRED_FEATURE_2}}` | 필수 기능 2 | "상세 페이지" |
| `{{OPTIONAL_FEATURE_1}}` | 선택 기능 1 | "TBD" |
| `{{OPTIONAL_FEATURE_2}}` | 선택 기능 2 | "고급 검색" |
| `{{OPTIONAL_FEATURE_3}}` | 선택 기능 3 | "즐겨찾기" |

### UI/UX 요구사항
| 변수명 | 설명 | 예시 |
|--------|------|------|
| `{{UI_LAYOUT}}` | UI 레이아웃 | "TBD", "그리드 형태", "목록 형태" |
| `{{UI_INTERACTION}}` | UI 상호작용 | "TBD", "드래그 앤 드롭", "키보드 단축키" |
| `{{UI_RESPONSIVE}}` | 반응형 설계 | "모바일 우선 설계" |

### 성과 지표 (컨텐츠별)
| 변수명 | 설명 | 예시 |
|--------|------|------|
| `{{KPI_METRIC_1}}` | KPI 지표 1 | "TBD", "월간 조회수" |
| `{{KPI_TARGET_1}}` | KPI 목표 1 | "TBD", "1,000회 이상" |
| `{{KPI_METRIC_2}}` | KPI 지표 2 | "사용자 참여도" |
| `{{KPI_TARGET_2}}` | KPI 목표 2 | "평균 2분 이상" |
| `{{KPI_METRIC_3}}` | KPI 지표 3 | "전환율" |
| `{{KPI_TARGET_3}}` | KPI 목표 3 | "5% 이상" |

### 연관 프로젝트
| 변수명 | 설명 | 예시 |
|--------|------|------|
| `{{RELATED_TASK_1_NAME}}` | 연관 태스크 1 이름 | "UI-002 컨텐츠 목록 컴포넌트" |
| `{{RELATED_TASK_1_ID}}` | 연관 태스크 1 ID | "ui-002" |
| `{{RELATED_TASK_2_NAME}}` | 연관 태스크 2 이름 | "I18N-001 다국어 지원" |
| `{{RELATED_TASK_2_ID}}` | 연관 태스크 2 ID | "i18n-001" |

---

## 💡 변수 치환 팁

### 일괄 치환 방법
```bash
# sed를 사용한 일괄 치환
sed -i 's/{{PROJECT_NAME}}/MyApp/g' **/*.md

# VS Code에서 전체 검색/바꾸기
Ctrl+Shift+H → {{PROJECT_NAME}} → MyApp → Replace All
```

### 변수 검증 방법
```bash
# 미치환 변수 찾기
grep -r "{{.*}}" . --include="*.md"
```

**총 변수 개수: 100+ 개**
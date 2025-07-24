# Documentation Template

Claude Code 최적화 문서 구조 템플릿입니다.

## 🎯 개요

이 템플릿은 다음과 같은 특징을 가진 프로젝트 문서 구조를 제공합니다:
- **Claude Code 최적화**: 개인 개발자 + AI 협업에 최적화
- **다국어 지원**: 4개 언어 (ko, en, ja, es) 완전 지원
- **간소화 구조**: 복잡성 최소화, 실용성 극대화
- **확장 가능**: 프로젝트 성장과 함께 유연한 확장

## 📁 폴더 구조

```
docs/
├── projects/           # 🎯 프로젝트 관리 (태스크, 로드맵)
├── content/           # 📝 컨텐츠 정의 (기초 정의서, 사양)
├── localization/      # 🌍 다국어 지원 (4개 언어)
├── development/       # 🔧 개발 가이드 (환경, 배포, DB)
└── assets/           # 📎 문서용 자료 (이미지, 다이어그램)
```

## 🚀 사용법

### 1. 템플릿 복사
```bash
# 이 저장소를 클론
git clone https://github.com/butflybe/template.git
cp -r template/ your-project/docs/
```

### 2. 변수 치환
모든 `{{VARIABLE}}` 형태의 변수를 프로젝트에 맞게 교체하세요.

**주요 변수들:**
- `{{PROJECT_NAME}}` - 프로젝트명 (예: "MyApp")
- `{{PROJECT_NAME_KR}}` - 한국어 프로젝트명 (예: "마이앱")
- `{{PROJECT_ID}}` - 프로젝트 ID (예: "0001.myapp")
- `{{PROJECT_VISION}}` - 프로젝트 비전
- `{{SUPPORTED_LANGUAGES}}` - 지원 언어 (예: "ko/en/ja/es")

### 3. 커스터마이징
1. `content/content.md` - 프로젝트 기초 정의서 작성
2. `projects/{{PROJECT_ID}}/` - 프로젝트 관리 문서 작성
3. `localization/` - 다국어 지원 설정
4. `development/` - 개발 환경별 가이드 작성

## 📋 변수 목록

### 프로젝트 기본 정보
- `{{PROJECT_NAME}}` - 프로젝트명
- `{{PROJECT_NAME_KR}}` - 한국어 프로젝트명
- `{{PROJECT_ID}}` - 프로젝트 ID (예: 0001.myapp)
- `{{PROJECT_VISION}}` - 프로젝트 비전
- `{{PROJECT_MISSION}}` - 프로젝트 미션
- `{{LAST_MODIFIED_DATE}}` - 최종 수정일

### 다국어 지원
- `{{SUPPORTED_LANGUAGES}}` - 지원 언어 (ko/en/ja/es)
- `{{SUPPORTED_LANGUAGES_FULL}}` - 전체 언어명
- `{{SUPPORTED_LANGUAGES_COUNT}}` - 지원 언어 개수
- `{{LOCALIZATION_*_PREFERENCE}}` - 언어별 선호도

### 기술 스택
- `{{FRONTEND_FRAMEWORK}}` - 프론트엔드 프레임워크
- `{{FRONTEND_LANGUAGE}}` - 프론트엔드 언어
- `{{BACKEND_DATABASE}}` - 백엔드 데이터베이스
- `{{DEPLOYMENT_HOSTING}}` - 배포 호스팅
- `{{TECH_STACK_SUMMARY}}` - 기술스택 요약

### 타겟 사용자
- `{{PRIMARY_TARGET_NAME}}` - 주요 타겟 사용자명
- `{{PRIMARY_TARGET_DESC}}` - 주요 타겟 설명
- `{{SECONDARY_TARGET_*}}` - 부차 타겟들

### 브랜드 & 디자인
- `{{BRAND_KEYWORDS}}` - 브랜드 키워드
- `{{DESIGN_PRINCIPLE_*}}` - 디자인 원칙들
- `{{UX_PRINCIPLE_*}}` - UX 원칙들

### 성과 지표 (KPI)
- `{{KPI_MAU_TARGET}}` - 월간 활성 사용자 목표
- `{{KPI_*}}` - 기타 KPI 지표들

## 🎨 컨텐츠 타입별 변수

### ContentA (컨텐츠 정의)
- `{{CONTENT_TYPE_NAME}}` - 컨텐츠 타입명
- `{{CONTENT_PRIORITY}}` - 우선순위
- `{{CONTENT_STATUS}}` - 상태
- `{{USER_GOAL_*}}` - 사용자 목표들
- `{{BUSINESS_GOAL_*}}` - 비즈니스 목표들

## 💡 팁

### 변수 치환 방법
1. **수동 치환**: IDE 전체 검색/바꾸기 기능 사용
2. **스크립트 활용**: sed, awk 등을 이용한 일괄 치환
3. **템플릿 엔진**: 향후 자동화 도구 개발 예정

### 구조 커스터마이징
- 언어 추가: `localization/` 폴더에 새 언어 파일 추가
- 컨텐츠 타입 추가: `content/` 폴더에 새 타입 폴더 생성
- 프로젝트 확장: `projects/` 폴더에 새 프로젝트 추가

## 📚 참고 문서

- [Claude Code 가이드](https://docs.anthropic.com/en/docs/claude-code)
- [다국어 웹사이트 모범 사례](https://web.dev/i18n/)
- [문서화 베스트 프랙티스](https://documentation.divio.com/)

## 🤝 기여

이슈나 개선 제안은 [GitHub Issues](https://github.com/butflybe/template/issues)에 등록해 주세요.

## 📄 라이선스

MIT License - 자유롭게 사용하세요.

---

**Created for Claude Code optimization and multilingual project documentation.**
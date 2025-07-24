# {{PROJECT_NAME}} Documentation Structure

{{PROJECT_NAME}} 프로젝트의 문서화 시스템은 **Claude Code 최적화**와 **개인 개발자 친화적 구조**를 기반으로 설계되었습니다.

## 📁 폴더 구조 개요

```
docs/
├── projects/           # 🎯 프로젝트 관리
├── content/           # 📝 컨텐츠 정의 및 사양
├── localization/      # 🌍 다국어 지원 시스템
├── development/       # 🔧 개발 가이드
└── assets/           # 📎 문서용 자료
```

---

## 🎯 **projects/** - 프로젝트 관리 영역

**목적**: 프로젝트 전체 관리 및 작업 추적

### 📋 구조
```
projects/
├── guide.md                 # 프로젝트 관리 통합 가이드
└── {{PROJECT_ID}}/          # {{PROJECT_NAME}} 프로젝트 (숫자 프리픽스)
    ├── goals-roadmap.md    # 목표 + 로드맵 통합
    └── tasks-status.md     # 태스크 + 진행상황 통합
```

### ✨ 특징
- **숫자 프리픽스**: `{{PROJECT_ID}}` 형태로 프로젝트 우선순위 관리
- **통합 관리**: 목표-로드맵, 태스크-상태를 각각 하나의 파일로 통합
- **Claude Code 최적화**: 문서 간 자연스러운 링크 연결
- **확장성**: 새 프로젝트는 `{{NEXT_PROJECT_ID}}.project-name` 형태로 추가

### 🔄 워크플로우
1. **일일**: `tasks-status.md`에서 할 일 확인 → 진행 → 완료 체크
2. **주간**: 진행상황 리뷰 및 다음 주 계획 수립
3. **월간**: `goals-roadmap.md` 전체 진행률 업데이트

---

## 📝 **content/** - 컨텐츠 정의 및 사양

**목적**: {{PROJECT_NAME}} 사이트의 모든 컨텐츠 정의 및 프로젝트 연동

### 📋 구조
```
content/
├── content.md              # 🎯 사이트 기초 정의서 (핵심 문서)
└── contentA/
    └── definition.md      # 컨텐츠 정의
```

### ✨ 특징
- **기초 문서 중심**: `content.md`가 모든 개발의 기준과 기반이 되는 핵심 문서
- **컨텐츠 중심**: {{PROJECT_NAME}}의 핵심인 다양한 컨텐츠를 체계적으로 관리
- **정의-목표-기능**: 각 컨텐츠의 사양을 명확히 정의
- **프로젝트 연동**: 개발 진행과 컨텐츠 정의가 실시간 동기화
- **확장성**: 새로운 컨텐츠 타입 추가 시 동일한 구조 적용

### 🎯 content.md - 사이트 기초 정의서
**위치**: `content/content.md`  
**중요도**: ⭐⭐⭐⭐⭐ (최우선 핵심 문서)

#### 📋 포함 내용
- **프로젝트 개요**: 비전, 미션, 서비스 개념
- **목적 & 목표**: 단계별 구체적 목표와 성공 지표
- **타겟 사용자**: {{SUPPORTED_LANGUAGES_COUNT}}개 언어권별 사용자 특성 분석
- **핵심 기능**: 헤더, 컨텐츠, 푸터 상세 사양
- **기술 스택**: {{TECH_STACK_SUMMARY}} 전체 구성
- **브랜드 정체성**: 디자인 원칙, UX 가이드라인

#### 🔑 핵심 역할
- **개발 기준**: 모든 개발 결정의 근거와 기준점
- **팀 정렬**: 프로젝트 방향성과 우선순위 통일
- **품질 보장**: 일관된 사용자 경험과 기술 품질 유지
- **변경 관리**: 요구사항 변경 시 영향도 분석 기준

### 🔗 연동 시스템
- **개발 시작**: `content.md` 검토 → 관련 `content/[타입]/definition.md` 참조
- **개발 진행**: 기초 정의서 기준으로 일관성 유지
- **개발 완료**: 실제 구현과 정의 일치성 검증
- **변경 발생**: `content.md` 우선 업데이트 → 관련 문서 동기화

---

## 🌍 **localization/** - 다국어 지원 시스템

**목적**: {{SUPPORTED_LANGUAGES_COUNT}}개 언어({{SUPPORTED_LANGUAGES}}) 지원을 위한 간소화된 로컬라이제이션 관리

### 📋 구조 (플랫 구조)
```
localization/
├── translation-guide.md    # 전체 번역 원칙 및 가이드라인
├── translation-status.md   # 번역 진행현황 관리
├── ko.md                   # 🇰🇷 한국어 가이드 + 용어집 통합
├── en.md                   # 🇺🇸 English guide + glossary 통합
├── ja.md                   # 🇯🇵 日本語 ガイド + 용語集 통합
└── es.md                   # 🇪🇸 Español guía + glosario 통합
```

### ✨ 특징
- **극도 간소화**: {{LOCALIZATION_FILES_COUNT}}개 파일로 완전한 다국어 시스템 관리
- **플랫 구조**: 불필요한 중간 폴더 제거로 직접 접근
- **통합 관리**: 각 언어별 가이드와 용어집을 하나의 파일로 통합
- **Claude Code 최적화**: 언어별 모든 정보를 한 파일에서 관리
- **프로젝트 연동**: 개발 진행과 번역 상태 실시간 동기화

### 🌍 언어별 파일 구성
- **translation-guide.md**: {{SUPPORTED_LANGUAGES_COUNT}}개 언어 공통 번역 원칙, 언어별 특성, 품질 기준
- **translation-status.md**: 전체 번역 진행률, 목표 일정, 이슈 관리
- **[언어].md**: 해당 언어의 사용자 가이드 + 용어집 + 스타일 가이드 통합

### 🔄 번역 워크플로우
1. **계획**: `translation-status.md`에서 우선순위 확인
2. **가이드 확인**: `translation-guide.md`에서 원칙 검토
3. **번역 실행**: 각 언어별 `.md` 파일에서 작업
4. **상태 업데이트**: `translation-status.md`에 진행상황 반영
5. **품질 검증**: 언어별 가이드의 용어집 기준으로 검증

---

## 🔧 **development/** - 개발 가이드

**목적**: 개발 환경 설정부터 배포까지 모든 개발 가이드 (플랫 구조)

### 📋 구조
```
development/
├── setup.md                         # 개발 환경 설정
├── architecture.md                  # 시스템 구조
├── {{DEPLOYMENT_HOSTING_LOWER}}-deployment.md     # {{DEPLOYMENT_HOSTING}} 배포 관리
├── {{BACKEND_DATABASE_LOWER}}-database.md         # {{BACKEND_DATABASE_NAME}} DB 관리
└── maintenance.md                   # 유지보수 가이드
```

### ✨ 특징
- **플랫 구조**: 폴더 없이 {{DEVELOPMENT_FILES_COUNT}}개 파일로 모든 개발 가이드 완성
- **실용성**: {{TECH_STACK_SUMMARY}} 환경에 특화된 가이드
- **개인 최적화**: 개인 개발자 + Claude Code 환경에 최적화
- **직접 접근**: 복잡한 폴더 구조 없이 바로 필요한 정보 접근

### 🎯 개발 워크플로우
1. **환경 설정**: `setup.md` 참조하여 개발 환경 구축
2. **개발**: `architecture.md` 기반으로 시스템 설계 및 개발
3. **배포**: `{{DEPLOYMENT_HOSTING_LOWER}}-deployment.md` 가이드로 배포
4. **데이터**: `{{BACKEND_DATABASE_LOWER}}-database.md`로 DB 관리
5. **유지보수**: `maintenance.md`로 운영 관리

---

## 📎 **assets/** - 문서용 자료

**목적**: 문서에 사용되는 이미지, 다이어그램 등 자료 관리

### 📋 구조
```
assets/
└── images/                  # 문서용 이미지
```

### ✨ 특징
- **중앙 관리**: 모든 문서의 이미지를 한 곳에서 관리
- **참조 최적화**: 상대 경로로 쉬운 이미지 참조
- **확장 가능**: 필요에 따라 diagrams/, screenshots/ 등 추가 가능

---

## 🤖 Claude Code 최적화 특징

### 🔗 **문서 간 연결성**
- 같은 폴더 내: `[파일명](./파일명.md)`
- 상위/하위 폴더: `[파일명](../폴더명/파일명.md)`
- 프로젝트 연동: tasks-status.md ↔ content definitions ↔ localization status

### 🎯 **간소화 원칙**
- **최소 폴더**: 불필요한 중간 폴더 제거
- **플랫 구조**: development/ 등에서 폴더 대신 파일로 관리
- **통합 파일**: 관련 내용을 하나의 파일로 통합

### 📊 **실시간 연동**
- 프로젝트 진행 → 컨텐츠 정의 업데이트
- 개발 완료 → 번역 상태 업데이트
- 문서 변경 → 관련 태스크 자동 연결

---

## 🚀 사용 가이드

### 📋 **프로젝트 시작 시**
1. `projects/guide.md` 읽기
2. `projects/{{PROJECT_ID}}/goals-roadmap.md`에서 목표 확인
3. `projects/{{PROJECT_ID}}/tasks-status.md`에서 할 일 확인

### 🔄 **일일 워크플로우**
1. `tasks-status.md`에서 오늘 할 일 선택
2. 관련 `content/` 정의 확인
3. `development/` 가이드 참조하여 개발
4. 완료 시 상태 업데이트

### 🌍 **다국어 작업 시**
1. `localization/translation-status.md`에서 현황 확인
2. `localization/[언어].md`에서 용어 확인
3. `localization/translation-guide.md`의 가이드라인 준수
4. 번역 완료 후 상태 업데이트

---

## 📈 확장 가능성

### 🔮 **새 프로젝트 추가**
```
projects/
├── guide.md
├── {{PROJECT_ID}}/
├── {{NEXT_PROJECT_ID}}.new-project/        # 새 프로젝트
└── 9999.archive/            # 완료된 프로젝트
```

### 📝 **새 컨텐츠 타입**
```
content/
├── existing-types/
└── new-content-type/        # 새 컨텐츠 타입
    └── definition.md
```

### 🌍 **새 언어 추가**
```
localization/
├── translation-guide.md
├── translation-status.md
├── existing-languages.md
└── new-lang.md             # 새 언어 문서
```

이 구조는 **{{PROJECT_NAME}} 프로젝트의 성장과 함께 유연하게 확장**될 수 있도록 설계되었습니다.
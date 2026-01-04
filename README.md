# Slide Maker Skill

슬라이드 구조와 내용을 기획하는 Claude Code 스킬입니다.

## 개요

피칭, 발표, 내부 공유, 교육/온보딩 등 다양한 용도의 슬라이드를 제작할 수 있습니다.

## 설치 방법

1. 압축 파일 해제
2. `slide-maker` 폴더를 `~/.claude/skills/` 경로에 복사

```bash
# 예시
unzip slide-maker-skill.zip
cp -r slide-maker ~/.claude/skills/
```

## 호출 방법

Claude Code에서 다음 키워드로 호출됩니다:

- "슬라이드"
- "PPT"
- "발표"
- "피칭덱"
- "프레젠테이션"

## 포함된 템플릿

`assets/` 폴더에 7개의 PPTX 템플릿이 포함되어 있습니다:

| 템플릿 | 용도 |
|--------|------|
| Black and White Minimalist Creative Brief | 크리에이티브 브리프, 기획서 |
| Blue Red Corporate Business Social Media | 소셜 미디어 전략, 마케팅 계획 |
| Blue and White Corporate KPI Monthly | KPI 보고서, 월간 실적 |
| Green White Black Modern Digital Marketing Strategy | 디지털 마케팅 전략 |
| Monthly Social Media Content | 월간 콘텐츠 계획 |
| Red and Beige Bold Modern Professional Business Pitch Deck | IR 피칭, 투자 유치 |
| White Green Minimalist Financial Report | 재무 보고서, 실적 발표 |

## 용도별 추천 템플릿

| 용도 | 추천 템플릿 |
|------|------------|
| IR 피칭 / 투자 유치 | Red and Beige Bold Modern Professional Business Pitch Deck |
| KPI / 월간 보고서 | Blue and White Corporate KPI Monthly |
| 재무 / 실적 보고 | White Green Minimalist Financial Report |
| 마케팅 전략 | Green White Black Modern Digital Marketing Strategy |
| 소셜 미디어 계획 | Blue Red Corporate Business Social Media |
| 크리에이티브 브리프 | Black and White Minimalist Creative Brief |

## 기본 원칙

- **언어**: 한국어 위주
- **철학**: 한 슬라이드 = 한 메시지
- **디자인**: 텍스트 최소화, 시각화 최대화
- **폰트**: Pretendard (필수)

## 폰트 다운로드

모든 슬라이드는 **Pretendard** 폰트를 사용합니다.

- 공식: https://cactus.tistory.com/306
- GitHub: https://github.com/orioncactus/pretendard

## 폴더 구조

```
slide-maker/
├── README.md          # 이 파일
├── SKILL.md           # 스킬 정의
└── assets/            # PPTX 템플릿
    ├── Black and White Minimalist Creative Brief Presentation.pptx
    ├── Blue Red Minimalist Corporate Business Social Media Management Plan Presentation.pptx
    ├── Blue and White Corporate KPI Monthly Presentation.pptx
    ├── Green White and Black Modern Digital Marketing Strategy Presentation.pptx
    ├── Monthly Social Media Content Presentation.pptx
    ├── Red ad Beige Bold Modern Professional Business Pitch Deck Presentation.pptx
    └── White Green Minimalist Financial Report Presentation.pptx
```

## 연계 스킬

| 상황 | 연계 스킬 |
|------|----------|
| 보고서 내용 필요 | report-writer |
| 전략 분석 필요 | strategy-framework |
| 콘텐츠로 변환 | content-creator |
| 레퍼런스 참조 | knowledge-base |

## 라이선스

개인 및 상업적 사용 가능
# Multi-Stage Analysis Viewer

멀티 스테이지 의료 분석 뷰어 - 브라우저에서 바로 사용할 수 있는 운동 분석 도구

## 🌐 온라인 사용

GitHub Pages를 통해 바로 사용할 수 있습니다:
**https://showboyz.github.io/multi_stage_analysis_viewer/**

## 📊 주요 기능

- **전체 평균 레이더 차트**: 6개 평가 영역 (동작 정확도, 균형 능력, 속도 일관성, 집중력, 학습력, 근력/지구력)
- **평가 영역별 평균 점수 테이블**: 등급 및 해석 가이드 포함
- **Stage 1, 2, 3 상세 분석**: BPM별 비교 및 중첩 그래프
- **데이터 트리밍**: 준비/마무리 자세 자동 제거
- **정확한 시간 계산**: BPM 기반 실제 운동 시간 표시
- **시각적 경고 시스템**: Chart.js annotation을 활용한 경고선 및 안전 영역

## 🚀 사용 방법

1. 웹사이트 접속: https://showboyz.github.io/multi_stage_analysis_viewer/
2. "📁 JSON 파일 선택" 버튼 클릭
3. 분석할 JSON 파일 선택
4. 자동으로 분석 결과 표시

## 📁 JSON 파일 형식

```json
[
  {
    "stage": 1,
    "bpm": 80,
    "move_err": "[1.5, 2.3, ...]",
    "balance_err": "[0.5, -1.2, ...]",
    "speed_err": "[3.2, 2.1, ...]",
    "gametime": "2024-01-01 12:00:00",
    "status": "normal"
  }
]
```

## 🛠 기술 스택

- **Chart.js**: 데이터 시각화
- **Tailwind CSS**: UI 디자인
- **Vanilla JavaScript**: 순수 자바스크립트로 구현
- **GitHub Pages**: 호스팅

## 📝 라이선스

MIT License

---

🤖 Generated with [Claude Code](https://claude.com/claude-code)
# Update

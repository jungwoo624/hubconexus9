# AX 사회안전망: Future-Sim 실증 모델

2026 인공지능 윤리 가이드라인 및 사업화 표준 지표 기반의 사회안전망 시뮬레이터입니다.

## 기능

- **3대 핵심 지표 실시간 측정**: 비판적 사고(주체성), 역기능 대응력(안전), 격차 해소율(형평성)
- **알고리즘 가중치 조정**: 성과/효율(`w_eff`) 및 복지/형평(`w_eq`) 가중치 슬라이더
- **계층별 자원 배분 시각화**: Chart.js 기반 막대 차트
- **AIHP 자동 피드백**: 가중치 조합에 따른 윤리적 경고/리포트

## 알고리즘

```
S = w_eff * M + w_eq * N
```

- `M`: 계층별 성과(merit) 값
- `N`: 계층별 필요(need) 값
- `S`: 사회적 자원 배분 수치

## 실행 방법

`index.html` 파일을 브라우저에서 열거나, GitHub Pages를 통해 배포된 URL로 접속하세요.

```bash
# 로컬 미리보기
start index.html
```

## 기술 스택

- HTML5 / CSS3 / Vanilla JavaScript
- [Chart.js](https://www.chartjs.org/)
- [Pretendard](https://github.com/orioncactus/pretendard)

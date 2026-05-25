# LOL-Team-Report

리그 오브 레전드 내전 팀 조합 및 시너지 분석 도구

LOL-Team-Report는  
내전 경기 데이터를 리포트 파일로 저장하고,  
이를 기반으로 팀 승률과 플레이어 간 시너지를 분석하는 정적 웹 애플리케이션입니다.

---

## Features

- 경기 기록 파일 업로드
- 팀 승률 분석
- 플레이어 시너지 분석
- 팀 조합 통계 시각화
- 플레이어별 전적 추적
- `.ltrs` 경기 리포트 포맷 지원
- 로컬 실행 기반 정적 웹앱

---

## Why?

내전을 오래 하다 보면 결국 이런 문제가 생깁니다.

- 특정 조합만 반복해서 승리함
- 듀오 시너지가 체감으로만 이야기됨
- 팀 밸런스가 감으로 결정됨
- 이전 경기 데이터를 제대로 기록하지 않음

LOL-Team-Report는  
내전 데이터를 파일 단위로 기록하고 분석하기 위해 제작되었습니다.

---

## How It Works

1. 내전 경기 데이터를 `.ltrs` 파일로 저장
2. 웹앱에서 리포트 파일 업로드
3. 승률 / 시너지 / 팀 통계를 자동 분석
4. 결과를 시각적으로 출력

---

## Preview

![preview](./docs/preview.png)

---

## Tech Stack

### Frontend
- HTML
- CSS
- JavaScript
- Tailwind CSS

### Data Format
- `.ltrs` (League Team Report Specification)

---

## Analysis Metrics

- 팀 승률
- 플레이어별 승률
- 듀오 시너지
- 팀 조합 통계
- 포지션 기반 분석
- 경기 누적 기록

---

## Project Goal

"감으로 짜던 내전 팀을 데이터로 분석한다."

LOL-Team-Report는  
내전 기록을 단순 저장하는 것이 아니라,  
실제 플레이 데이터를 기반으로 팀 밸런스를 분석하는 것을 목표로 합니다.

---

## License

MIT License

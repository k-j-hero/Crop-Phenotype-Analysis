# Project Log

## 2026-08-11 — 프로젝트 환경 초기화

- 연구 질문: 2000년 이후 국가별 고추 수확량은 어떻게 달라졌으며, 그 차이를 해석할 때 무엇을 조심해야 하는가?
- 성공 기준: FAOSTAT의 품목 정의·수확량 단위를 기록하고, 국가별·연도별 변화를 재현 가능한 코드와 그림으로 제시한다.
- 수행: `uv init` 후 pandas, seaborn, matplotlib, jupyter, scikit-learn을 설치했다.
- 확인: `uv run python --version` 결과는 Python 3.14.4였고, Jupyter 관련 패키지가 설치된 것을 확인했다.
- 생성: `data/raw`, `data/processed`, `notebooks`, `src`, `reports` 폴더를 준비했다.
- 결정: 원본 데이터는 `data/raw`에 보관하고 수정하지 않는다. 탐색은 노트북에서, 반복 작업은 `src`에서 수행한다.
- 다음 작업: FAOSTAT에서 고추 관련 품목·수확량 변수·단위·다운로드 날짜·결측 처리 기준을 확인한다.
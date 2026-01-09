# Zombie Tactics 모작

## 시연 영상 및 게임 소개
[![ZombieTactics Demo](https://img.shields.io/badge/YouTube-Video-red?logo=youtube)](https://youtu.be/UcNRsOX1SvY)  
<img width="240" alt="image" src="docs/images/overview_001.png" />
<img width="240" alt="image" src="docs/images/overview_002.png" />
<img width="240" alt="image" src="docs/images/overview_003.png" />

육각 타일 기반의 턴제 디펜스 게임

- 육각 타일 기반 A* 알고리즘 구현
- 턴제 시스템 구현
- 성장 가능한 스킬, 인벤토리 및 상점 구현
- 베지어 곡선 활용한 투사체 표현

## 핵심 기술

### 육각 타일 기반 A* 알고리즘 구현
육각 타일에서의 길 찾기를 위한 인덱스를 설정하고 해당하는 조건식을 활용해 최적 경로 계산
- 육각 타일 인덱스 설정
  <p align="left">
    <img width="360" alt="image" src="docs/images/coretech_001.png" />
    <img width="360" alt="image" src="docs/images/coretech_002.png" />
  </p>  
- 평면 조건식  
  <img width="121" height="23" alt="image" src="docs/images/coretech_003.png" />
- 거리 계산식  
  <img width="401" height="52" alt="image" src="docs/images/coretech_004.png" />
- 최적 경로 계산 (A*)
  <p align="left">
    <img width="360" alt="image" src="docs/images/coretech_005.png" />
    <img width="360" alt="image" src="docs/images/coretech_006.png" />
  </p>

# Zombie Tactics 모작

## 시연 영상 및 게임 소개
[![ZombieTactics Demo](https://img.shields.io/badge/YouTube-Video-red?logo=youtube)](https://youtu.be/UcNRsOX1SvY)  
<img width="240" alt="image" src="https://github.com/user-attachments/assets/724dc8c1-1e37-4b74-a37f-83e47a86626a" />
<img width="240" alt="image" src="https://github.com/user-attachments/assets/b245c3e9-3f0b-4933-9501-76a8d758ed5a" />
<img width="240" alt="image" src="https://github.com/user-attachments/assets/172f6db0-dd95-492a-bdd0-5d8f0da8ddc1" />  
육각 타일 기반의 턴제 디펜스 게임
- 육각 타일 기반 A* 알고리즘 구현
- 턴제 시스템 구현
- 성장 가능한 스킬, 인벤토리 및 상점 구현
- 베지어 곡선 활용한 투사체 표현

## 핵심 기술

### 육각 타일 기반 A* 알고리즘 구현
- 육각 타일 인덱스 설정
  <p align="left">
    <img width="400" alt="image" src="https://github.com/user-attachments/assets/29cd86a3-ffca-41ca-a0f1-5b48e64c4b21" />
    <img width="400" alt="image" src="https://github.com/user-attachments/assets/65f3fe26-2637-4c03-93ab-c60ccb115a09" />
  </p>  
- 평면 조건식  
  <img width="121" height="23" alt="image" src="https://github.com/user-attachments/assets/933613b9-ad80-424b-a9a8-e9536634a6cf" />
- 거리 계산식  
  <img width="401" height="52" alt="image" src="https://github.com/user-attachments/assets/51b4aaeb-6b5a-4bf0-9d64-fb855a7092d8" />
- 최적 경로 계산 (A*)
  <p align="left">
    <img width="400" alt="image" src="https://github.com/user-attachments/assets/a5cf1a07-b87b-4232-aed8-c730d7a15092" />
    <img width="400" alt="image" src="https://github.com/user-attachments/assets/2237a543-5b1f-4b94-a25e-9e67130604d7" />
  </p>

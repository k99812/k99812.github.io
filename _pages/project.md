---
layout: single
author_profile: true
permalink: /project
title: "Project"
excerpt: "포트폴리오 프로젝트"
header:
  overlay_color: "#000"
  overlay_filter: "0.0"
  overlay_image: /assets/images/metaPC.jpg
toc: true
toc_label: "목차"
toc_sticky: true
---

# Projects

|프로젝트|프로젝트설명|기간|비고|
|:---:|:---:|:---:|:---:|
| [Project_P](https://github.com/k99812/Project_P) | 언리얼 엔진 <br> 개인 포트폴리오|2024.06 ~ |
| [WKMetaverse](https://github.com/k99812/WKMetaverse)| 유니티 멀티플레이 <br> 팀 프로젝트|2022.06 ~ 2023.02|
| [Cpp](https://github.com/k99812/Cpp) | 코딩테스트 <br> 알고리즘 문제 풀이|2023.05 ~ |

<span class="detail">프로젝트의 코드와 기술설명은 GitHub 저장소에 있습니다.</span><br>
<br>

# 언리얼엔진 포트폴리오

<div class="project-card">
  <img src="/assets/images/project_p.gif" alt="프로젝트 썸네일" class="project-image" />

  <div class="project-info">
    <h2>Project_P</h2>
    <p>GAS 기반 전투 시스템, AI Perception, UI를 연동한 언리얼 엔진 포트폴리오 프로젝트</p>
    <a href="https://github.com/k99812/Project_P" target="_blank" class="github-link">
      <img src="/assets/images/github.png"
           alt="GitHub 링크"
           class="github-icon" />
      <span>GitHub 저장소 링크</span>
    </a>
  </div>
</div>

## 주요 기능
### 전투 시스템 (GAS 기반)
- 어빌리티, 어트리뷰트셋 기반의 콤보 공격, 공격 판정 설계 및 구현
- 게임 플레이 태그를 활용한 제어 및 상태 관리
- Trace 기반의 공격 판정, 타격 시 GE를 통한 데미지 처리

### 애니메이션 시스템
- Locomotion, Jump, AimOffset, UpperBody Layer 블렌딩 구성
- Montage, AnimNotify 기반 콤보 연계 및 타격 타이밍 처리

### UI 연동
- HP Bar, 데미지 플로팅 텍스트, 플레이어 HUD, 사망/재시작 UI 구현
- Attribute 연동을 통한 UI 실시간 갱신 (Delegate 활용)

### AI 시스템
- Behavior Tree, AIController 기반 추적, 공격, 인식 AI 구현
- AI Perception을 통한 시야, 데미지 기반 인식 로직 설계

### 입력 처리
- Enhanced Input System 기반 입력 및 바인딩
- ENUM을 활용한 유지보수 용이한 설계

<br>

# 유니티 팀 프로젝트

<div class="project-card">
  <img src="/assets/images/wkmeta.gif" alt="프로젝트 썸네일" class="project-image" />

  <div class="project-info">
    <h2>WKMetaverse</h2>
    <p>Photon 엔진을 활용한 네트워크 기반 멀티플레이 시스템 및 캐릭터 조작 구현</p>
    <a href="https://github.com/k99812/WKMetaverse" target="_blank" class="github-link">
      <img src="/assets/images/github.png"
           alt="GitHub 링크"
           class="github-icon" />
      <span>GitHub 저장소 링크</span>
    </a>
  </div>
</div>

## 담당 개발 내용
- 포톤 엔진을 이용해 멀티플레이 구현
- Photon의 RPC 기능을 활용한 실시간 채팅 구현
- 캐릭터 스폰 및 동기화, 캐릭터 선택 기능 구현
- 기본 캐릭터 이동 및 조작 시스템 개발

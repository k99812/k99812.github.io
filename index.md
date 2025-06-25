---
layout: single
author_profile: true
permalink: /
title: "Portfolio"
excerpt: "신입 게임 클라이언트 개발자"
header:
  overlay_color: "#000"
  overlay_filter: "0.0"
  overlay_image: /assets/images/metaPC.jpg
about_me_txt: "Gameplay Ability System(GAS), 애니메이션, UI, AI 등 게임 전반의 클라이언트 구조 설계 및 구현이 가능한 신입 개발자입니다. <br><br> 자세한 프로젝트 내용은 GitHub 및 블로그를 통해 확인하실 수 있습니다."
skills:
  - image_path: /assets/images/cpp.png
  - image_path: /assets/images/csharp.png
  - image_path: /assets/images/github.png
  - image_path: /assets/images/unreal.png
  - image_path: /assets/images/unity.png
---

<h3> ABOUT ME </h3>

{% if page.about_me_txt %}{{ page.about_me_txt }}{% endif %}

<h2> SKILL </h2>
{% include feature_row id="skills" %}

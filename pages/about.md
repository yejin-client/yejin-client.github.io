---
layout: page
title: About
permalink: /about/
weight: 3
---

# **About Me**

Hi I am **{{ site.author.name }}** :wave:,<br>
Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.

<div class="row">
{% include about/skills.html title="Programming Skills" source=site.data.programming-skills %}
{% include about/skills.html title="Engine skills" source=site.data.other-skills %}
</div>

<!--
타임라인; 어떤 주제 넣을지 생각해보기
프로젝트 나열해도 고내찮ㅇ르지도
  오픈소스 프로젝트
*  캡스톤 프로제트
*  논문경진대회
*  개인 프로젝트

<div class="row">
{% include about/timeline.html %}
</div>
-->

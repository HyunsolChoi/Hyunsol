---
title: Riot API, WPF를 이용해 사용자 정보 검색

authors:
  - admin
tags:
  - API
  - WPF
date: 2024-09-22

summary: 2022년 2월, 학기에 앞서 WPF와 API를 공부하며 오는 학기에 수강할 강의를 예습하였습니다.
---

<div style="text-align: justify; word-break: normal; text-justify: inter-word;">

<p>
2022년 2월, 학기에 앞서 WPF와 API를 공부하며 오는 학기에 수강할 강의를 예습하였습니다.
본래 목적인 예습에 그치기엔 아쉬움이 있어 소규모 프로젝트를 진행하였습니다.
</p>

### 목표

<p>
목표는 JSON 형식으로 사용자의 정보를 제공하는 <a href="https://developer.riotgames.com/apis">Riot API</a>를 사용하여 ID로 사용자의 정보를 검색하는 것이었습니다.
</p>

### 차이점

<p>
해당 기능을 제공하는 웹 사이트로는 <a href="https://www.op.gg/">OP.GG</a>가 있습니다. 하지만 저는 웹이 아닌 WPF를 사용하기에 어떤 웹 브라우저도 필요하지 않다는 차이가 있습니다.<br><br>

그러므로 어떤 웹 서버도 필요하지 않았고 따라서 API가 제공하는 범위에서 정보의 새로고침이 보다 자유롭습니다. 
</p>

### 결과

<p>
UI부분은 다소 아쉽게 마무리 되었지만, ID를 통해 사용자 정보를 출력하는 부분은 성공적으로 구현하였습니다.
</p>

</div>


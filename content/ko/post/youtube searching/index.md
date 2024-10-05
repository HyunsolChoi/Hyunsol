---
title: 지정 언어로 YouTube 검색하기
authors:
  - admin
tags:
  - API
  - WPF
date: 2024-09-22

summary: "Youtube 검색 기능은 사용자의 국가 코드를 사용하여 해당 국가의 영상을 주로 추천합니다."
---

<div style="text-align: justify; word-break: normal; text-justify: inter-word;">

<p>
Youtube 검색 기능은 사용자의 국가 코드를 사용하여 해당 국가의 영상을 주로 추천합니다. 그러므로 사용자가 외국의 영상을 보고자 하여도 의도한 바와 다르게 사용자 국가의 영상을 주로 추천합니다.
</p>

### 목표

<p>
목표는 사용자가 입력한 검색어를 지정 국가의 언어로 변경하고 해당 국가의 영상들을 추천하도록 하는 것이었습니다.
</p>

### APIs

<p>
첫 번째로 검색어를 지정 국가의 언어로 바꾸는 기능을 구현하기 위해 <a href="https://developers.naver.com/docs/papago/README.md">Papago API</a>를 사용하였습니다 (현재는 지원하지 않음). 이때 사용자가 입력하는 검색어는 Papago 자체의 언어 감지 기능을 사용하여 사용자의 번거로움을 줄이고자 하였습니다.

두 번째로 <a href="https://developers.google.com/youtube">YouTube API</a>를 사용하였습니다. 앞서 번역한 검색어와 해당 언어를 사용하는 국가의 코드를 이용해 데이터를 요청합니다. 이를 통해 반환 된 데이터 중 썸네일, 제목, 좋아요 수 등을 사용자에게 리스트로 보여주고 해당 영상의 링크를 통해 접근할 수 있도록 하였습니다.
</p>

### 결과

<p>
이를 통해 사용자는 사용자 국가에 국한되지 않고, 지정 언어로 만들어진 영상들을 검색할 수 있습니다.
</p>

### 첨부

{{% staticref "uploads/report.pdf" "newtab" %}}보고서 다운로드{{% /staticref %}}

</div>
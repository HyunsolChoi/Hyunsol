---
title: YouTube Searching with specific country code
authors:
  - admin
tags:
  - API
date: 2024-09-22
---

YouTube's search function uses the user's country code to search mainly for videos in the region. Therefore, even if you want to search for foreign videos, the user's national video is recommended first. 

## GOAL 

The goal is to implement a feature that searches for user-inputted keywords in a specific language and recommends videos from a specific country.

## APIs

First, I used the [Papago API](https://developers.naver.com/docs/papago/README.md) to translate the words or sentences entered by the user into the specified language(It's not currently supported). The language detection feature identifies the language entered by the user and translates it into the specified language. 

Secondly, the [YouTube API](https://developers.google.com/youtube) is utilized. The API is requested using the country code of the specified language and the translated text. The returned data is then presented as a list in the interface, including the video title, thumbnail, and video link.

## Result 

This allows users to search for videos from their desired country in the language of their choice, without being limited by their own country.

Here is images of the report in korean.
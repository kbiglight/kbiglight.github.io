---
layout: page
permalink: /privacy.html
title: 개인정보처리방침
description: Alfred · 최종 수정 2026-09-19
nav: false
---

Alfred 는 제작자 본인 한 사람만 사용하는 비공개 개인 도구입니다. 다른 사용자를
받지 않으며, 제3자에게 데이터를 판매하거나 제공하지 않습니다.

## 수집하는 정보

- **Slack 메시지** — 사용자가 Alfred 에게 보낸 대화 내용
- **Google 캘린더** — 일정의 제목, 시각, 장소, 설명
- **Google Tasks** — 할 일의 제목, 기한, 메모

Google 데이터에는 `calendar.events` 와 `tasks` 범위로 접근합니다. 사용자가 요청할
때만 조회하거나 변경하며, 그 외에는 접근하지 않습니다.

## 이용 목적

요청에 답하고, 일정과 할 일을 조회·관리하며, 지정한 시각에 요약을 보내기 위해서만
사용합니다. 광고나 분석 용도로는 사용하지 않습니다.

## 보관

- 대화 기록과 설정은 운영자 본인 컴퓨터의 로컬 데이터베이스에 저장됩니다
- Google 인증 토큰은 같은 컴퓨터에 소유자만 읽을 수 있는 권한으로 저장됩니다
- Google 캘린더·할 일 데이터를 따로 복제해 쌓아두지 않고, 필요할 때 조회합니다

## 외부 전송

답변을 생성하기 위해 대화 내용과, 그 답변에 필요한 일정·할 일 정보가 Anthropic 의
Claude API 로 전송됩니다. 처리 방식은
[Anthropic 개인정보처리방침](https://www.anthropic.com/legal/privacy)을 따릅니다.
이 외의 제3자에게는 전송하지 않습니다.

## 보관 기간과 삭제

운영자가 로컬 데이터베이스 파일을 삭제하면 저장된 내용이 모두 사라집니다. Google
계정 연결은 [Google 계정 권한 설정](https://myaccount.google.com/permissions)에서
언제든 해제할 수 있으며, 해제하면 Alfred 는 더 이상 캘린더와 할 일에 접근하지
못합니다.

## 문의

<kbiglight@gmail.com>

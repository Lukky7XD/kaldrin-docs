---
title: 개인정보 처리방침 · Privacy Policy
permalink: /privacy/
---

# 개인정보 처리방침

시행일: 2026년 9월 16일

**요약 — Kaldrin 개발자는 사용자의 정보를 수집하거나 보관하지 않습니다.**

## 1. Kaldrin 은 무엇인가요

Kaldrin 은 마인크래프트: 베드락 에디션용 유틸리티 클라이언트로, 사용자의 PC 안에서만 실행됩니다.
개발자가 운영하는 서버는 없습니다. 계정·로그인·광고·사용 통계(텔레메트리)도 없으며, Kaldrin 은 개발자에게 아무것도 보내지 않습니다.

## 2. Discord 상태 기능

「디스코드 상태」 모듈은 **기본으로 꺼져 있으며** 사용자가 켰을 때만 동작합니다.
켜면 **같은 PC 에서 실행 중인 Discord 데스크톱 앱**에 로컬 연결(명명 파이프)로 아래 정보를 넘깁니다.
Kaldrin 이 인터넷으로 직접 보내지는 않습니다.

| 넘기는 정보 | 언제 |
|---|---|
| Discord 앱 ID (Kaldrin 앱, 또는 사용자가 설정에 넣은 앱) | 연결할 때 |
| 지금 있는 곳 — 월드·서버 이름, 또는 「싱글플레이」·「멀티플레이」·「메인 메뉴」 | 켜져 있는 동안 |
| 서버 주소 — **외부 서버일 때만** (로컬 월드의 주소는 보내지 않습니다) | 「주소 표시」가 켜져 있을 때 |
| 게임 모드 (서바이벌·크리에이티브 등) | 「게임 모드 표시」가 켜져 있을 때 |
| 지금 월드에 들어온 시각 (경과 시간 표시용) | 「경과 시간 표시」가 켜져 있을 때 |
| 큰 그림 이름 | 설정에 적었을 때 |
| 게임의 프로세스 번호(PID) | 켜져 있는 동안 — Discord 가 게임이 꺼질 때 상태를 지우는 데 씁니다 |

- 월드 이름·주소·게임 모드·경과 시간은 모듈 설정에서 **하나씩 끌 수 있습니다.** 끄면 그 자리에는 일반 문구만 갑니다.
- 모듈을 끄거나 Kaldrin 을 종료하면 상태를 지웁니다.
- Discord 앱은 이 정보를 Discord 로 보내고, 누가 볼 수 있는지는 사용자의 Discord 활동 상태 공개 설정이 정합니다.
  이 처리에는 [Discord 개인정보 처리방침](https://discord.com/privacy)이 적용됩니다.
- **「주소 표시」를 켜면 상태를 볼 수 있는 사람이 서버 주소를 볼 수 있습니다.** 비공개 서버에서는 꺼 두세요.
  월드 이름에 실명이나 게이머태그가 들어 있으면 그것도 그대로 보입니다.

## 3. PC 에 저장되는 것

Kaldrin 은 `%LOCALAPPDATA%\Kaldrin\` 폴더에 설정(`config.json`), 기록(`kaldrin.log`), 상태 파일, 실행에 필요한 파일을 둡니다.
기록에는 월드·서버 이름 같은 게임 정보가 들어갈 수 있습니다. 이 파일들은 **사용자 PC 밖으로 나가지 않으며**, 폴더를 지우면 모두 사라집니다.

## 4. 제3자

Kaldrin 은 위 Discord 기능 말고는 어떤 제3자에게도 정보를 넘기지 않습니다.
게임이 서버와 주고받는 통신에는 마인크래프트(Mojang·Microsoft)와 접속한 서버의 정책이 적용됩니다.
이 문서는 GitHub Pages 에서 제공되며, 페이지 방문 기록은 GitHub 이
[GitHub 개인정보 처리방침](https://docs.github.com/en/site-policy/privacy-policies/github-general-privacy-statement)에 따라 처리합니다.

## 5. 삭제 요청

개발자가 보관하는 정보가 없으므로 개발자 쪽에서 지울 정보도 없습니다.
PC 에 남은 정보는 위 폴더를 지우면 되고, Discord 에 넘어간 정보는 Discord 의 도구와 정책으로 관리할 수 있습니다.

## 6. 아동

Kaldrin 은 누구의 정보도 수집하지 않으므로 아동의 정보도 수집하지 않습니다.
Discord 기능은 Discord 를 이용할 수 있는 나이의 사용자를 전제로 합니다.

## 7. 변경

이 방침이 바뀌면 이 페이지에 바뀐 내용과 새 시행일을 게시합니다.

## 8. 문의

[GitHub Issues](https://github.com/Lukky7XD/kaldrin-docs/issues)에 남겨 주세요.

---

# Privacy Policy

Effective date: September 16, 2026

**In short — the Kaldrin developer does not collect or store any of your information.**

## 1. What Kaldrin is

Kaldrin is a utility client for Minecraft: Bedrock Edition that runs only on your PC.
The developer runs no servers. There are no accounts, sign-ins, ads or usage statistics (telemetry), and Kaldrin sends nothing to the developer.

## 2. Discord status (Rich Presence)

The "Discord Presence" module is **off by default** and works only when you turn it on.
When it is on, Kaldrin passes the information below over a local connection (a named pipe) to **the Discord desktop app running on the same PC**.
Kaldrin itself does not send it over the internet.

| Information passed | When |
|---|---|
| Discord application ID (the Kaldrin app, or one you entered in the settings) | When connecting |
| Where you are — world or server name, or "Singleplayer", "Multiplayer", "Main menu" | While on |
| Server address — **external servers only** (local world addresses are never sent) | When "Show address" is on |
| Game mode (Survival, Creative, …) | When "Show game mode" is on |
| The time you entered the current world (for elapsed time) | When "Show elapsed time" is on |
| Large image key | When you set one |
| The game's process ID (PID) | While on — Discord uses it to clear the status when the game closes |

- World name, address, game mode and elapsed time can each be **turned off** in the module settings. When off, only a generic phrase is sent in its place.
- Turning the module off, or closing Kaldrin, clears the status.
- The Discord app sends this information to Discord, and your Discord activity privacy settings decide who can see it.
  [Discord's Privacy Policy](https://discord.com/privacy) applies to that processing.
- **If "Show address" is on, anyone who can see your status can see the server address.** Turn it off on private servers.
  If a world name contains your real name or gamertag, that is shown as well.

## 3. What is stored on your PC

Kaldrin keeps its settings (`config.json`), a log (`kaldrin.log`), a status file and the files it needs to run in `%LOCALAPPDATA%\Kaldrin\`.
The log may contain game information such as world or server names. These files **never leave your PC**, and deleting the folder removes them all.

## 4. Third parties

Apart from the Discord feature above, Kaldrin shares no information with any third party.
The game's own communication with servers is governed by the policies of Minecraft (Mojang, Microsoft) and of the server you join.
This page is served by GitHub Pages; visits to it are handled by GitHub under the
[GitHub General Privacy Statement](https://docs.github.com/en/site-policy/privacy-policies/github-general-privacy-statement).

## 5. Deletion requests

The developer holds no information, so there is nothing to delete on the developer's side.
Delete the folder above to remove local data; information passed to Discord can be managed with Discord's tools and policies.

## 6. Children

Kaldrin collects no one's information, children's included.
The Discord feature assumes a user who is old enough to use Discord.

## 7. Changes

If this policy changes, the updated text and new effective date will be posted on this page.

## 8. Contact

Please open an issue on [GitHub Issues](https://github.com/Lukky7XD/kaldrin-docs/issues).

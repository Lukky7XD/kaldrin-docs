---
title: 개인정보 처리방침 · Privacy Policy
permalink: /privacy/
---

# 개인정보 처리방침

시행일: 2026년 10월 31일

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
| Discord 앱 ID (Kaldrin 앱, 또는 「Kaldrin 앱 ID 사용」을 끄고 사용자가 넣은 앱) | 연결할 때 |
| 지금 있는 곳의 문구 — 메인 메뉴·월드를 불러오는 중·싱글 월드·서버·렐름·친구 월드마다 하나(기본은 「In the main menu」 같은 영어 문구이며, 사용자가 모듈 설정에서 바꿀 수 있습니다) | 켜져 있는 동안 |
| 월드·서버 이름 — 사용자가 문구에 `{v}` · `{v1}` 을 넣은 자리(「둘째 줄」 문구의 기본이 `{v}` 라 기본으로는 상태의 둘째 줄에 들어갑니다) | 문구에 그 자리가 있을 때 |
| 게임 모드 (서바이벌·크리에이티브 등) — 사용자가 문구에 `{v}` · `{v2}` 를 넣은 자리(기본으로는 상태의 둘째 줄) | 문구에 그 자리가 있을 때 |
| 「둘째 줄」 문구 — 상태의 둘째 줄(사용자가 바꿀 수 있고, 비우면 둘째 줄을 보내지 않습니다) | 켜져 있는 동안 |
| 지금 월드에 들어온 시각 (경과 시간 표시용) | 「경과 시간 표시」가 켜져 있을 때 |
| 그림 이름 — 큰 그림 `kaldrin`(Kaldrin 로고)과 작은 그림 `minecraft`(마인크래프트 아이콘), 그림 위의 고정 글(「Kaldrin Client」·「Minecraft Bedrock」) | 켜져 있는 동안 |
| 게임의 프로세스 번호(PID) | 켜져 있는 동안 — Discord 가 게임이 꺼질 때 상태를 지우는 데 씁니다 |

- 월드 이름·게임 모드는 **문구에서 그 자리(`{v}` · `{v1}` · `{v2}`)를 빼면** 어디에도 가지 않습니다 — 「둘째 줄」 문구를 비우면 둘째 줄을 보내지 않습니다.
  경과 시간은 「경과 시간 표시」로 끕니다.
- 서버 주소·포트와 서버 인원은 넘기지 않습니다.
- 모듈을 끄거나 Kaldrin 을 종료하면 상태를 지웁니다.
- Discord 앱은 이 정보를 Discord 로 보내고, 누가 볼 수 있는지는 사용자의 Discord 활동 상태 공개 설정이 정합니다.
  이 처리에는 [Discord 개인정보 처리방침](https://discord.com/privacy)이 적용됩니다.
- 월드 이름이나 사용자가 적은 문구에 실명이나 게이머태그가 들어 있으면 그것도 그대로 보입니다.

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

Effective date: October 31, 2026

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
| Discord application ID (the Kaldrin app, or your own app entered after turning off "Use Kaldrin App ID") | When connecting |
| A message for where you are — one each for the main menu, loading a world, a singleplayer world, a server, a Realm and a friend's world (by default English phrases such as "In the main menu", which you can change in the module settings) | While on |
| World or server name — wherever you put `{v}` or `{v1}` in a message (the "Second line" message is `{v}` by default, so by default it is on the second line of the status) | When a message has that slot |
| Game mode (Survival, Creative, …) — wherever you put `{v}` or `{v2}` in a message (by default on the second line of the status) | When a message has that slot |
| The "Second line" message — on the second line of the status (you can change it; leave it empty to send no second line) | While on |
| The time you entered the current world (for elapsed time) | When "Show elapsed time" is on |
| Image keys — the large image `kaldrin` (the Kaldrin logo) and the small image `minecraft` (the Minecraft icon), and the fixed text on them ("Kaldrin Client", "Minecraft Bedrock") | While on |
| The game's process ID (PID) | While on — Discord uses it to clear the status when the game closes |

- World name and game mode are not sent anywhere **once you remove their slots (`{v}`, `{v1}`, `{v2}`) from the messages** — leave the "Second line" message
  empty to send no second line. Elapsed time is turned off with "Show elapsed time".
- The server address, port and player count are not passed.
- Turning the module off, or closing Kaldrin, clears the status.
- The Discord app sends this information to Discord, and your Discord activity privacy settings decide who can see it.
  [Discord's Privacy Policy](https://discord.com/privacy) applies to that processing.
- If a world name, or a message you write, contains your real name or gamertag, that is shown as well.

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

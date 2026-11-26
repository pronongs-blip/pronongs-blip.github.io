<div align="center">

<img src="apple-touch-icon.png" width="96" alt="DEVIL'S ARCADE icon">

# DEVIL'S ARCADE

**두뇌 서바이벌 아케이드 — 게임 4종**

[![아케이드 열기](https://img.shields.io/badge/%E2%96%B6_%EC%95%84%EC%BC%80%EC%9D%B4%EB%93%9C_%EC%97%B4%EA%B8%B0-pronongs--blip.github.io-ffc247?style=for-the-badge)](https://pronongs-blip.github.io/)
[![Games](https://img.shields.io/badge/GAMES-4_TITLES-7aa4ff?style=flat-square)](#-games--4-titles)
[![Flags](https://img.shields.io/badge/%EA%B5%AD%EA%B8%B0-268%EC%A2%85-5ad6b2?style=flat-square)](#-%EC%9C%A0%EB%B0%B0%EC%A7%80-%EB%A7%8C%EA%B5%AD%EA%B8%B0)

<sub>아이폰 <b>Safari</b>에서 <b>공유 → 홈 화면에 추가</b> 하면 앱처럼 전체화면으로 열립니다.</sub>

</div>

---

## 🎮 Games — 4 Titles

| | 게임 | 한 줄 소개 | 플레이 |
|:--:|:--|:--|:--:|
| ♟ | **벽바둑 2** <br><sub>Wall Go Ⅱ</sub> | 7×7 보드, 벽으로 길을 막고 영역을 차지하는 1:1 전략 보드게임 (온라인 · AI · 3인전) | [▶ 열기](https://pronongs-blip.github.io/wall-baduk2.html) |
| ◐ | **흑과 백** <br><sub>Black & White</sub> | 0~8 타일의 흑·백만 보고 승부하는 9라운드 1:1 심리전 (온라인 · AI · 추리 메모) | [▶ 열기](https://pronongs-blip.github.io/black-white.html) |
| 🃏 | **기억포커** <br><sub>Memory Poker</sub> | 20초 암기 → 60초 선택, 내 2장 + 공용 3장으로 겨루는 9단계 족보 승부 (온라인 · AI) | [▶ 열기](https://pronongs-blip.github.io/memory-poker.html) |
| 🌐 | **유배지 만국기** <sub>`NEW`</sub> <br><sub>World Flags</sub> | 30초 동안 10개 국기 3회 반복 암기 → 25개 보기 중 **5개** 찾기. 전 세계 **268종** 실제 국기 SVG, 온라인 1:1, **지옥 난이도**(유사 국기 낚시) | [▶ 열기](https://pronongs-blip.github.io/world-flags.html) |

> 🌐 **유배지 만국기** 는 《데블스 플랜: 데드 어게인》 5일차 유배지 매치 규칙을 그대로 옮겼습니다.
> 아일랜드 ↔ 코트디부아르 ↔ 이탈리아, 차드 ↔ 루마니아 ↔ 몰도바처럼 **색 배열만 다른 국기**가 오답으로 깔립니다.

> 🎭 **닉네임** — 네 게임 모두 《데블스 플랜: 데드 어게인》 시즌 3 출연자 16명 중에서 골라 쓸 수 있고, 직접 입력도 됩니다.

---

## ✨ 특징

- **외부 CDN 없는 단일 HTML** — 앱마다 파일 하나, 라이브러리·폰트·이미지 요청 0. 오프라인에서도 그대로 동작합니다.
- **모바일 최적화** — 아이폰 13 미니(375×812) · 프로(390×844) 기준으로 5×5 국기 그리드까지 한 화면에 스크롤 없이 들어갑니다.
- **Web Audio 사운드 엔진** — 외부 음원 파일 없이 합성한 게임별 BGM과 효과음, 헤더의 `♪ | 🔊` 토글로 개별 온·오프(설정 공유).
- **MQTT 온라인 1:1** — 공개 브로커(`wss://broker.emqx.io:8084/mqtt`) 위의 미니 MQTT 클라이언트와 `?room=XXXX` 초대 링크. 같은 기기에서는 BroadcastChannel로 자동 폴백.
- **국기 268종 인라인 SVG** — 이모지가 아니라 실제 벡터 국기. 유엔 회원국 193개국 + 지역·자치령·기구기 전체를 4:3 규격으로 통일했습니다.
- **기록 배지** — 포털이 `localStorage`(`yg_arcade_stats_v1`)로 실행 횟수를 세어 `NEW` · `최다` · `N회` 배지를 답니다.
- **iOS 홈 화면** — Safari 공유 → 홈 화면에 추가. 전용 아이콘(`apple-touch-icon.png`)과 전체화면 메타 태그가 들어 있습니다.

---

## 🗂 구성

```text
pronongs-blip.github.io/
├── index.html            # 아케이드 포털
├── wall-baduk2.html      # 벽바둑 2
├── black-white.html      # 흑과 백
├── memory-poker.html     # 기억포커
├── world-flags.html      # 유배지 만국기 (국기 268종 인라인 SVG)
└── apple-touch-icon.png  # 홈 화면 아이콘
```

<div align="center">
<sub>새 게임이 완성될 때마다 이 광장에 하나씩 세워집니다</sub>
</div>

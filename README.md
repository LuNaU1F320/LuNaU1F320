<div align="center">

<img src="./assets/luna-profile-hero.png" alt="LuNa — game client programmer" width="100%" />

# LuNa

### GAME CLIENT PROGRAMMER

**복잡한 게임 규칙을, 손맛이 느껴지는 플레이 경험으로 구현합니다.**<br>
*I turn complex gameplay rules into responsive, playable systems.*

[![Unreal Engine](https://img.shields.io/badge/UNREAL_ENGINE-0E1128?style=for-the-badge&logo=unrealengine&logoColor=white)](https://github.com/LuNaU1F320/AstroRail)
[![Unity](https://img.shields.io/badge/UNITY-000000?style=for-the-badge&logo=unity&logoColor=white)](https://github.com/LuNaU1F320/PokeRogue)
[![C++](https://img.shields.io/badge/C++-6C4DFF?style=for-the-badge&logo=cplusplus&logoColor=white)](https://github.com/LuNaU1F320/AstroRail)
[![C Sharp](https://img.shields.io/badge/C%23-00B8D9?style=for-the-badge&logo=csharp&logoColor=white)](https://github.com/LuNaU1F320/PokeRogue)

[![Email](https://img.shields.io/badge/CONTACT-EA4AAA?style=flat-square&logo=gmail&logoColor=white)](mailto:lunau1f320@gmail.com)
[![GitHub](https://img.shields.io/badge/GITHUB-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/LuNaU1F320)
[![Portfolio](https://img.shields.io/badge/PROJECT_PORTFOLIOS-7C3AED?style=flat-square&logo=notion&logoColor=white)](#-featured-projects)

</div>

---

## ✦ About Me

전투의 **상태 흐름**, 플레이어의 **입력과 피드백**, 데이터를 실제 플레이로 연결하는 **게임플레이 시스템**에 집중합니다.<br>
기능 하나를 만드는 데서 끝내지 않고, 서로 영향을 주는 규칙을 명확한 책임과 데이터 흐름으로 설계하는 것을 좋아합니다.

```text
GAMEPLAY IDEA  →  SYSTEM DESIGN  →  DATA & STATE  →  PLAYER FEEDBACK
```

- 🎮 턴제 전투, 타겟팅, 상태 이상, 성장·보상 시스템
- 🧩 Subsystem / Component / Service 기반 책임 분리
- 💾 DataTable · DataAsset · ScriptableObject · CSV/JSON · SaveGame
- ✨ Animation Notify · VFX · UI를 게임 판정과 동기화

---

## 🚀 Featured Projects

### 🌌 [AstroRail](https://github.com/LuNaU1F320/AstroRail) — Unreal Engine 5 Turn-Based RPG

<table>
<tr>
<td width="54%">
<a href="https://github.com/LuNaU1F320/AstroRail">
<img src="https://raw.githubusercontent.com/LuNaU1F320/AstroRail/main/AstroRail.png" alt="AstroRail" width="100%" />
</a>
</td>
<td width="46%" valign="top">

<b>붕괴: 스타레일의 전투 구조를 UE5로 재구성한 3D 턴제 RPG</b>

<br><br>

• AV 기반 행동 순서와 필살기 끼어들기<br>
• 약점 격파와 7속성 상태 이상<br>
• 다중 타겟팅과 입력 상태 제어<br>
• 다중 페이즈 보스와 가중치 패턴<br>
• 픽업·천장·확정 보정 가챠<br>
• 파티·보상·SaveGame 영속화

<br>

<b>Role</b> 전투 시스템 전반 · 캐릭터/적 데이터 · 파티 · 가챠 · 저장 · 전투 UI<br>
<b>Team</b> 2인 협업 · 2026.05–06

</td>
</tr>
</table>

<p align="center">
  <a href="https://github.com/LuNaU1F320/AstroRail/releases"><img src="https://img.shields.io/badge/DOWNLOAD-PLAY_BUILD-00C2FF?style=for-the-badge&logo=github&logoColor=white" alt="Download AstroRail"></a>
  <a href="https://app.notion.com/p/AstroRail-2fddbef4fbe582aabd20814f223d0796"><img src="https://img.shields.io/badge/READ-DEEP_DIVE-8B5CF6?style=for-the-badge&logo=notion&logoColor=white" alt="AstroRail portfolio"></a>
</p>

### ⚔️ [PokeRogue](https://github.com/LuNaU1F320/PokeRogue) — Unity Turn-Based Roguelike RPG

Unity로 구현한 포켓몬 기반 턴제 로그라이크 RPG입니다. 전투 한 턴의 우선순위부터 상태 이상, 포획·도주, 다단계 성장과 저장까지 하나의 플레이 루프로 연결했습니다.

| Core Systems | Data & Tools | Player Experience |
|:---|:---|:---|
| 턴 우선순위 · 데미지 · 18타입 상성 | CSV → ScriptableObject 임포터 | 포획 · 도주 · 파티 편성 |
| 콜백 기반 상태 이상 | JSON 스프라이트 애니메이션 | 레벨업 · 기술 학습 · 진화 |
| 교체 · 스킬 실행 파이프라인 | 런타임/원본 데이터 분리 | 저장 · 설정 · 씬 전환 |

<p align="center">
  <a href="https://youtu.be/HDGUY87Xfoc"><img src="https://img.shields.io/badge/WATCH-GAMEPLAY-FF0033?style=for-the-badge&logo=youtube&logoColor=white" alt="PokeRogue gameplay"></a>
  <a href="https://github.com/LuNaU1F320/PokeRogue/releases"><img src="https://img.shields.io/badge/DOWNLOAD-PLAY_BUILD-00C2FF?style=for-the-badge&logo=github&logoColor=white" alt="Download PokeRogue"></a>
  <a href="https://app.notion.com/p/Pok-Rogue-13cdbef4fbe58283899e01b6ce40241f"><img src="https://img.shields.io/badge/READ-DEEP_DIVE-8B5CF6?style=for-the-badge&logo=notion&logoColor=white" alt="PokeRogue portfolio"></a>
</p>

### 🎛️ [BandMixer](https://github.com/LuNaU1F320/BandMixer) — Unity Audio System

보컬·드럼·베이스·기타 스템을 독립적으로 제어하는 음악 세션 믹서입니다.

- 스템별 볼륨·뮤트와 동기화 재생
- 루프, 탐색, 재생 속도 제어
- BPM 기반 메트로놈과 오디오 UI

---

## 🛠️ Tech Arsenal

<div align="center">

#### Engines & Languages

![Unreal Engine](https://img.shields.io/badge/Unreal_Engine_5-0E1128?style=flat-square&logo=unrealengine&logoColor=white)
![Unity](https://img.shields.io/badge/Unity-000000?style=flat-square&logo=unity&logoColor=white)
![C++](https://img.shields.io/badge/C++-00599C?style=flat-square&logo=cplusplus&logoColor=white)
![C Sharp](https://img.shields.io/badge/C%23-239120?style=flat-square&logo=csharp&logoColor=white)
![Blueprint](https://img.shields.io/badge/Blueprint-137CBD?style=flat-square&logo=unrealengine&logoColor=white)

#### Gameplay & Data

![Gameplay Systems](https://img.shields.io/badge/Gameplay_Systems-7C3AED?style=flat-square)
![Turn Based Combat](https://img.shields.io/badge/Turn--Based_Combat-EA4AAA?style=flat-square)
![UI UX](https://img.shields.io/badge/Game_UI_%2F_UX-00B8D9?style=flat-square)
![Data Driven](https://img.shields.io/badge/Data--Driven_Design-FFB000?style=flat-square)
![Audio Systems](https://img.shields.io/badge/Audio_Systems-FF6B6B?style=flat-square)
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)

</div>

---

## 📊 GitHub Snapshot

<div align="center">

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://github-readme-stats.vercel.app/api?username=LuNaU1F320&show_icons=true&hide_border=true&bg_color=0D1117&title_color=A78BFA&icon_color=22D3EE&text_color=C9D1D9&ring_color=8B5CF6">
  <source media="(prefers-color-scheme: light)" srcset="https://github-readme-stats.vercel.app/api?username=LuNaU1F320&show_icons=true&hide_border=true&title_color=7C3AED&icon_color=0891B2&text_color=24292F&ring_color=8B5CF6">
  <img height="165" src="https://github-readme-stats.vercel.app/api?username=LuNaU1F320&show_icons=true&hide_border=true&bg_color=0D1117&title_color=A78BFA&icon_color=22D3EE&text_color=C9D1D9&ring_color=8B5CF6" alt="LuNa GitHub stats">
</picture>
<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://github-readme-stats.vercel.app/api/top-langs/?username=LuNaU1F320&layout=compact&hide_border=true&bg_color=0D1117&title_color=A78BFA&text_color=C9D1D9">
  <source media="(prefers-color-scheme: light)" srcset="https://github-readme-stats.vercel.app/api/top-langs/?username=LuNaU1F320&layout=compact&hide_border=true&title_color=7C3AED&text_color=24292F">
  <img height="165" src="https://github-readme-stats.vercel.app/api/top-langs/?username=LuNaU1F320&layout=compact&hide_border=true&bg_color=0D1117&title_color=A78BFA&text_color=C9D1D9" alt="Most used languages">
</picture>

</div>

---

<div align="center">

### LET'S BUILD SOMETHING PLAYABLE

게임의 규칙이 화면 위에서 살아 움직이는 순간을 만듭니다.

[![Say Hello](https://img.shields.io/badge/SAY_HELLO-lunau1f320%40gmail.com-8B5CF6?style=for-the-badge&logo=gmail&logoColor=white)](mailto:lunau1f320@gmail.com)

<sub>🎮 Building playable systems, one meaningful interaction at a time.</sub>

</div>

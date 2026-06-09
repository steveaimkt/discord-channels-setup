# discord-channels-setup

> 폰 디스코드 DM ↔ Claude Code 세션을 양방향으로 잇는 **Discord Channels 셋업 스킬**.
> 맥북 · 윈도우 모두 지원 · 11 STEP 인터랙티브 가이드 (봇 발급 → 폰 DM 연동 → Gmail/Calendar 결합).

## 설치 (스킬 폴더로 클론)

> ⚠️ **터미널에서 켠 `claude`** 에서만 셋업이 완료됩니다 (VSCode·Cursor 확장 ❌).

**맥북 / Linux**
```bash
git clone https://github.com/steveaimkt/discord-channels-setup.git \
  ~/.claude/skills/discord-channels-setup
```

**윈도우 (PowerShell)**
```powershell
git clone https://github.com/steveaimkt/discord-channels-setup.git `
  "$env:USERPROFILE\.claude\skills\discord-channels-setup"
```

→ Claude Code 를 **새로 켜고** 채팅창에 입력:
```
디스코드 채널 세팅
```

## 무엇을 해주나

| STEP | 내용 |
|---|---|
| 0~0.5 | OS 감지 + **윈도우 사전 최적화** (Defender·실행정책·LongPath·OneDrive) |
| 1~4 | Bun·git 점검 → Discord 봇 생성 → Intent → 서버 초대 |
| 5~7 | 공식 Channels 플러그인 설치 → 토큰 등록 → `--channels` 재시작 |
| 8~9 | 페어링 + allowlist 잠금 → 폰 DM 양방향 검증 |
| 10~11 | Gmail/Calendar 결합 + 마케팅 MCP 10종 안내 |

## 라이선스

MIT

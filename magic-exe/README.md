# MAGIC.EXE
Track 1 · *VERSION 1.0 : HELLO, WORLD!* · Running time **3:30**

[![CHICHI \& KIKI - MAGIC.EXE Official MV](https://img.youtube.com/vi/-K_bj1yK1h4/hqdefault.jpg)](https://youtu.be/-K_bj1yK1h4)

MAGIC.EXE is CHICHI & KIKI's first hello to the world — written in the language of a system booting up and connecting.

세상에 존재를 알리는 치치앤키키의 첫 번째 인사입니다.

## Data status

| Member | Robot | Folder | Status |
|---|---|---|---|
| CHICHI | Unitree G1 EDU PLUS | [chichi-g1/](chichi-g1/) | Releasing in stages |
| LOG | Agility A2 Dual-Arm | [log-a2/](log-a2/) | Releasing in stages |
| KIKI | Unitree Go2 EDU PLUS | [kiki-go2/](kiki-go2/) | Coming soon |

## Timing
On stage, the three robots do not communicate with each other. Each follows the song's timecode independently.
Where possible, data in this folder is aligned to that same timecode (`00:00.000`–`03:30.000`). <!-- TODO: 개발팀 확인 — 실제 타임코드 정렬 여부 -->

## How these motions were made (CHICHI)
`motion capture → retargeting → reinforcement learning in physics simulation → fine-tuning on the real robot`

On stage, validated sequences run automatically under operator supervision. Only balance and posture are corrected in real time.

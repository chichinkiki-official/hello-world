# hello-world
### Data from CHICHI & KIKI's 1st album — *VERSION 1.0 : HELLO, WORLD!*
치치앤키키 1집 <VERSION 1.0 : HELLO, WORLD!> 공개 데이터

> **Read this first.** This is a small dataset made for real performances, not a large-scale research dataset. Each folder's README lists its **known limitations** before anything else.
>
> **먼저 읽어 주세요.** 이 저장소는 대규모 연구용 데이터셋이 아니라, 실제 무대를 위해 만든 작은 데이터입니다. 각 폴더의 README는 **알려진 한계**부터 적어 두었습니다.

Why we share this → [**learn-and-share**](https://github.com/chichinkiki-official/learn-and-share)

[![CHICHI \& KIKI - MAGIC.EXE Official MV](https://img.youtube.com/vi/-K_bj1yK1h4/hqdefault.jpg)](https://youtu.be/-K_bj1yK1h4)

## Tracks

| # | Track | Data |
|---|---|---|
| 1 | [**MAGIC.EXE**](magic-exe/) (3:30) | CHICHI (G1) · LOG (A2) — releasing in stages / KIKI (Go2) — in preparation |
| 2 | TUTORIAL | Not yet released |
| 3 | PATCH NOTES | Not yet released |

## Structure

```
magic-exe/
├── chichi-g1/               CHICHI · Unitree G1 EDU PLUS
│   ├── mocap/               Human motion capture of the choreography
│   ├── retarget/            Motion retargeted to the G1 skeleton
│   ├── rl-training-records/ Partial reinforcement-learning records (no policy weights)
│   └── failures/            Failed attempts we chose to keep
├── log-a2/                  LOG · Agility A2 Dual-Arm
│   ├── drum-design/         Beat breakdown and strike plan
│   ├── strike-trajectories/ Arm motion for each strike
│   └── failures/
└── kiki-go2/                KIKI · Unitree Go2 EDU PLUS — coming soon
```

## What is *not* included
- Trained control policies / model weights 학습된 제어 정책(모델 가중치)
- The song's audio 곡 음원
- Any footage that can identify a person 사람을 식별할 수 있는 영상

## Versions = PATCH NOTES
Releases follow the album's version: `v1.0` is the debut release (2026-10-29). Every update is logged in [PATCH_NOTES.md](PATCH_NOTES.md).

## License
**TBD** — the license will be stated here before data files are published.
<!-- TODO: 데이터 라이선스(예: CC BY 4.0 / CC BY-NC 4.0) 및 코드 라이선스 확정 후 LICENSE 파일 추가 -->

## Citation
See [CITATION.cff](CITATION.cff).

## Links
[Website](http://www.chichikiki.com/) · [Instagram](https://www.instagram.com/chichinkiki) · [YouTube](https://www.youtube.com/@%EC%B9%98%EC%B9%98%EC%95%A4%ED%82%A4%ED%82%A4)

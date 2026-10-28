# LOG · Agility A2 Dual-Arm — MAGIC.EXE drums

> ⚠️ **Safety first.** Playing this data back directly on a physical A2 may damage the robot or cause injury. Read the [Safety Notice and Safe Usage](../../README.md) before use. Provided "AS IS" under the [MIT License](../../LICENSE).
>
> ⚠️ 실제 A2에 그대로 재생하면 로봇 파손이나 인명 사고가 발생할 수 있습니다. 사용 전 [안전 고지와 안전 사용법](../../README.md)을 반드시 읽어 주세요.

## Known limitations — read first
- Covers the drum part of **one song (3:30)**.
- LOG plays a **small drum kit without a kick drum** — a dual-arm robot has no feet.
- The beat analysis and strike plan were made **in advance**. LOG does not listen to music and improvise on stage; it executes a pre-designed performance precisely.
- Strike motions are tuned to our specific kit layout; a different setup will need recalibration.
- Motions not verified on hardware are marked **"Not verified on hardware / 미검증"**.

## Contents
| Path | Motion | Verification |
|---|---|---|
| [drum-design/](drum-design/) | Beat breakdown and strike plan (which drum, when, how hard) | [시뮬레이션 / 실기 검증 여부] |
| [strike-trajectories/](strike-trajectories/) | Arm motion data for each strike | [시뮬레이션 / 실기 검증 여부] |
| [failures/](failures/) | Failed attempts we chose to keep | — |

## Data format
| Item | Value |
|---|---|
| Robot | Agility A2 Dual-Arm |
| Degrees of freedom used | TBD |
| Format | TBD |
| Tempo (BPM) of MAGIC.EXE | TBD |
| Kit layout | TBD |
| Frame rate | TBD |
| Timecode alignment | TBD |

## Preconditions
| Item | Value |
|---|---|
| Firmware version | TBD |
| SDK version | TBD |
| Control mode | TBD |
| Control period | TBD |
| Gains | TBD |

<!-- TODO(개발팀): 위 TBD 항목 채우기 -->

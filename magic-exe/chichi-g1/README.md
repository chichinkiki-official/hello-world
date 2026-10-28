# CHICHI · Unitree G1 EDU PLUS — MAGIC.EXE

> ⚠️ **Safety first.** Playing this data back directly on a physical G1 may damage the robot or cause injury. Read the [Safety Notice and Safe Usage](../../README.md) before use. Provided "AS IS" under the [MIT License](../../LICENSE).
>
> ⚠️ 실제 G1에 그대로 재생하면 로봇 파손이나 인명 사고가 발생할 수 있습니다. 사용 전 [안전 고지와 안전 사용법](../../README.md)을 반드시 읽어 주세요.

## Known limitations — read first
- Covers **one song (3:30)** performed by **one robot**. Not suitable as a general-purpose motion dataset.
- Made for stage performance, not curated to research-benchmark standards.
- Reinforcement-learning data is **partial**. **Trained policies / model weights are not included**, so the motions cannot be reproduced on a robot from this data alone.
- Motions were tuned for specific stage floors and conditions; results on other surfaces are not guaranteed.
- Motions not verified on hardware are marked **"Not verified on hardware / 미검증"**.

## Contents
| Path | Motion | Verification |
|---|---|---|
| [mocap/](mocap/) | Human motion capture of the MAGIC.EXE choreography [파일명] | [시뮬레이션 / 실기 검증 여부] |
| [retarget/](retarget/) | Motion retargeted to the G1 joint structure [파일명] | [시뮬레이션 / 실기 검증 여부] |
| [rl-training-records/](rl-training-records/) | Partial RL records (no policy weights) | [시뮬레이션 / 실기 검증 여부] |
| [failures/](failures/) | Failed attempts we chose to keep | — |

## Data format
| Item | Value |
|---|---|
| Robot | Unitree G1 EDU PLUS |
| Degrees of freedom used | TBD |
| Format | [예: 관절 각도 시퀀스] |
| Frame rate | TBD |
| Coordinate system & units | TBD |
| Total duration / number of clips | TBD |
| Timecode alignment | TBD |
| Simulator (for RL records) | TBD |

## Preconditions
| Item | Value |
|---|---|
| Firmware version | TBD |
| SDK version | TBD |
| Control mode | TBD |
| Control period | TBD |
| Gains | TBD |

<!-- TODO(개발팀): 위 TBD 항목 채우기. 프레임레이트는 기획 확인 후 반영 -->

## Credits
- Choreography: TBD <!-- 안무가 표기 방식 확인 -->
- Motion capture performer: TBD <!-- 퍼포머 동의 및 표기 여부 확인 -->
- Production: Brightbell

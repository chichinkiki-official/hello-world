# CHICHI · Unitree G1 EDU PLUS — MAGIC.EXE

## Known limitations — read first
- Covers **one song (3:30)** performed by **one robot**. Not suitable as a general-purpose motion dataset.
- Made for stage performance, not curated to research-benchmark standards.
- Reinforcement-learning data is **partial**. **Trained policies / model weights are not included**, so the motions cannot be reproduced on a robot from this data alone.
- Motions were tuned for specific stage floors and conditions; results on other surfaces are not guaranteed.
- ⚠️ Running these motions on a real robot is at your own risk. Always test in simulation first.

## Contents
| Folder | What it holds | Status |
|---|---|---|
| [mocap/](mocap/) | Human motion capture of the MAGIC.EXE choreography | TBD |
| [retarget/](retarget/) | Motion retargeted to the G1 joint structure | TBD |
| [rl-training-records/](rl-training-records/) | Partial RL records (no policy weights) | TBD |
| [failures/](failures/) | Failed attempts we chose to keep | TBD |

## Specification
| Item | Value |
|---|---|
| Robot | Unitree G1 EDU PLUS |
| Degrees of freedom used | TBD |
| Frame rate | TBD |
| Total duration / number of clips | TBD |
| File format | TBD |
| Coordinate system & units | TBD |
| Timecode alignment | TBD |
| Simulator (for RL records) | TBD |

<!-- TODO(개발팀): 위 TBD 항목 채우기. 프레임레이트는 기획 확인 후 반영 -->

## Credits
- Choreography: TBD <!-- 안무가 표기 방식 확인 -->
- Motion capture performer: TBD <!-- 퍼포머 동의 및 표기 여부 확인 -->
- Production: Brightbell Creative Group

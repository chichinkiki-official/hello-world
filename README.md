# hello-world — CHICHI & KIKI Motion Data
### Unitree G1 / Go2 motion data and Agility A2 drum data from *VERSION 1.0 : HELLO, WORLD!*

치치앤키키 1집 <VERSION 1.0 : HELLO, WORLD!>를 위해 만든 Unitree G1(휴머노이드)·Go2(사족보행) 로봇용 모션 데이터와 Agility A2(듀얼암) 드럼 연주 데이터입니다. Brightbell이 개발했으며 공익 목적으로 무료 공개합니다.

Motion data for the Unitree G1 (humanoid) and Go2 (quadruped) robots, and drum performance data for the Agility A2 (dual-arm), made for CHICHI & KIKI's 1st album. Developed by Brightbell and released free of charge for public benefit.

## ⚠️ 안전 고지 / Safety Notice

> **이 데이터를 실제 로봇에 그대로 재생하면 로봇 파손이나 인명 사고가 발생할 수 있습니다.**
>
> 본 데이터는 어떠한 보증 없이 "있는 그대로(AS IS)" 제공되며, 사용으로 인해 발생한 로봇·장비 파손, 부상 등 어떠한 손해에 대해서도 제공자(Brightbell 및 기여자)는 책임지지 않습니다. 모든 사용의 책임은 사용자에게 있습니다.
>
> **This motion data may damage the robot or cause injury if played back directly on a physical G1, Go2 or A2.**
>
> It is provided "AS IS" without warranty of any kind. Brightbell and the contributors are not liable for any damage or loss (including hardware damage or injury) arising from its use. Use at your own risk.

## 안전하게 사용하는 법 / Safe Usage

**공통 (G1 · Go2 · A2)**
1. **시뮬레이션 먼저:** 실기에 적용하기 전에 시뮬레이션(예: Isaac, MuJoCo)에서 동작을 확인합니다.
2. **비상정지 준비:** 비상정지 수단을 손에 두고 재생합니다.
3. **주변 통제:** 재생 중 로봇 반경 내 접근을 통제하고, 넘어지거나 부딪히면 위험한 물건을 치웁니다.
4. **낮은 강도로 시작:** 저속·저게인으로 시작해 단계적으로 높입니다.
5. **한계값 확인:** 사용하는 펌웨어, 관절 한계, 속도·토크 제한, 제어 주기가 이 데이터의 전제 조건과 같은지 직접 확인합니다.
6. **이상 시 중단:** 비정상 소음, 발열, 떨림이 보이면 즉시 중단합니다.

**G1 (휴머노이드 · CHICHI)**
- 처음에는 거치대나 안전줄로 로봇을 고정한 상태에서 재생합니다.
- 전도 시 로봇과 주변이 함께 파손될 수 있으니 넓고 평평한 바닥에서 사용합니다.

**Go2 (사족보행 · KIKI)**
- 미끄러운 바닥이나 경사에서는 사용하지 않고, 평평하고 마찰이 충분한 바닥에서 시작합니다.
- 다리 사이에 손이나 물체가 끼이지 않도록 재생 중 접근하지 않습니다.

**A2 (듀얼암 · LOG)**
- 드럼 세트와 로봇 팔의 위치를 먼저 맞춘 뒤 재생합니다.
- 재생 중에는 팔의 동작 반경 안에 사람이 들어가지 않게 합니다.

---

> **Read this first.** This is a small dataset made for real performances, not a large-scale research dataset. Each folder's README lists its **known limitations** before anything else.
>
> **먼저 읽어 주세요.** 이 저장소는 대규모 연구용 데이터셋이 아니라, 실제 무대를 위해 만든 작은 데이터입니다. 각 폴더의 README는 **알려진 한계**부터 적어 두었습니다.

Why we share this → [**learn-and-share**](https://github.com/chichinkiki-official/learn-and-share)

[![CHICHI \& KIKI - MAGIC.EXE Official MV](https://img.youtube.com/vi/-K_bj1yK1h4/hqdefault.jpg)](https://youtu.be/-K_bj1yK1h4)

## 포함 내용 / Contents

| 경로 Path | 로봇 Robot | 모션 설명 Motion | 검증 상태 Verification |
|---|---|---|---|
| `magic-exe/chichi-g1/mocap/` | G1 | MAGIC.EXE 안무 모션캡처 [파일명] | [시뮬레이션 / 실기 검증 여부] |
| `magic-exe/chichi-g1/retarget/` | G1 | G1 관절 구조로 리타게팅한 안무 [파일명] | [시뮬레이션 / 실기 검증 여부] |
| `magic-exe/chichi-g1/rl-training-records/` | G1 | 강화학습 기록 일부 (정책·가중치 제외) | [시뮬레이션 / 실기 검증 여부] |
| `magic-exe/log-a2/drum-design/` | A2 | MAGIC.EXE 비트 분해·타격 설계 | [시뮬레이션 / 실기 검증 여부] |
| `magic-exe/log-a2/strike-trajectories/` | A2 | 타격 동작 데이터 | [시뮬레이션 / 실기 검증 여부] |
| `magic-exe/kiki-go2/` | Go2 | 공개 준비 중 / Coming soon | — |

실기 검증을 거치지 않은 모션은 **"미검증 / Not verified on hardware"** 으로 표기합니다.

**데이터 포맷 / Data format:** [포맷 설명. 예: 관절 각도 시퀀스, 프레임 레이트, 좌표계]

**전제 조건 / Preconditions:** [로봇별 펌웨어 버전, SDK 버전, 제어 모드, 제어 주기, 게인]

## 사용법 / Usage

[재생 방법을 짧게 설명. 예: 어떤 툴·스크립트로 불러와 재생하는지]

## 포함하지 않는 것 / Not included
- 학습된 제어 정책(모델 가중치) / Trained control policies (model weights)
- 곡 음원 / The song's audio
- 사람을 식별할 수 있는 영상 / Any footage that can identify a person
- Unitree의 모델 파일(URDF/USD)·SDK 파일 — 필요하면 Unitree 공식 배포처를 이용해 주세요 / Unitree model (URDF/USD) and SDK files — please use Unitree's official sources

## 버전 / Versions
첫 공개는 `v1.0.0` (2026-10-29, VERSION 1.0)이며, 모든 변경 내역은 [PATCH_NOTES.md](PATCH_NOTES.md)에 남깁니다.

## 상표 고지 / Trademarks
Unitree, G1, Go2는 Unitree Robotics의 상표입니다. 본 프로젝트는 Unitree Robotics와 제휴하거나 보증받은 프로젝트가 아닙니다.

Unitree, G1, and Go2 are trademarks of Unitree Robotics. This project is not affiliated with or endorsed by Unitree Robotics.

## 라이선스 / License
[MIT License](LICENSE) © 2026 Brightbell

누구나 무료로 사용·수정·재배포·판매할 수 있고, 재배포 시 저작권 및 라이선스 문구를 함께 포함해야 합니다. 제공자는 어떠한 보증도 하지 않으며, 사용으로 발생한 손해에 책임지지 않습니다. 이 요지는 참고용이며, 법적 효력은 영문 원문([LICENSE](LICENSE))에 있습니다.

## 문의 / Contact
이슈는 [GitHub Issues](https://github.com/chichinkiki-official/hello-world/issues)에 남겨 주세요. 신고 시 로봇 모델, 펌웨어 버전, 재생 환경을 함께 적어 주세요. 본 레포는 지원·유지보수를 보장하지 않습니다.

Please use GitHub Issues, including the robot model, firmware version and playback environment. No support or maintenance is guaranteed.

## Citation
See [CITATION.cff](CITATION.cff).

## Links
[Website](http://www.chichikiki.com/) · [Instagram](https://www.instagram.com/chichinkiki) · [YouTube](https://www.youtube.com/@%EC%B9%98%EC%B9%98%EC%95%A4%ED%82%A4%ED%82%A4)

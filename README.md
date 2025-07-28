# VHDL 학습 저장소

이 저장소는 **VHDL(VHSIC Hardware Description Language)**을 체계적으로 학습하고, 실습 코드와 이론 정리를 함께 관리하기 위해 만들어졌습니다. FPGA나 SoC 키트 없이도 학습할 수 있는 시뮬레이션 중심의 코드와 설명 위주로 구성되어 있습니다.

## 📚 학습 목표

- 디지털 회로 설계를 위한 VHDL의 기본 문법 습득
- 조합 논리 및 순차 논리 회로 모델링
- Testbench를 통한 시뮬레이션 기반 검증
- 실전 프로젝트를 위한 설계 습관과 코드 구조 익히기

---

## 🗂️ 커리큘럼

### 1. VHDL 기초

- [ ] VHDL 소개 및 개발 환경 설정
- [ ] `entity`와 `architecture` 구조 이해
- [ ] `std_logic`과 `std_logic_vector`의 차이
- [ ] 기본 연산자와 데이터 타입

### 2. 조합 논리 회로 설계

- [ ] AND, OR, NOT, XOR 게이트
- [ ] Half Adder / Full Adder
- [ ] 멀티플렉서(MUX) / 디멀티플렉서(DEMUX)
- [ ] 인코더 / 디코더
- [ ] 우선순위 인코더
- [ ] 비교기, 7세그 디코더
- [ ] ALU 미니 구현

### 3. 순차 논리 회로 설계

- [ ] 플립플롭 (D, T, JK 등)
- [ ] 레지스터
- [ ] 시프트 레지스터
- [ ] 카운터 (업/다운, 모듈러 카운터)
- [ ] FSM (Finite State Machine) 설계

### 4. Testbench 작성법

- [ ] 기본 테스트벤치 구조
- [ ] `assert`와 시뮬레이션 결과 확인
- [ ] 시간 지연(`wait for`)과 파형 확인

### 5. 타이밍 이슈 이론 & 실습

- [ ] Propagation Delay
- [ ] Glitch (글리치)
- [ ] Setup / Hold Time	DFF에서의 제약 위반0
- [ ] Clock Skew	클럭 분산 시 타이밍 깨짐 시나리오
- [ ] Critical Path

### 6. 합성(Synthesis) 개념
- [ ] 합성이 가능한 VHDL vs 불가능한 코드	시뮬레이션용 only 코드 구분
- [ ] 클럭 도메인 & 리셋 방식	동기/비동기 리셋 구조 이해
- [ ] 리소스 사용량	LUT, FF, BRAM, DSP 등
- [ ] Vivado 설치 후 가벼운 분석	타이밍 리포트, Netlist 확인 등

---

## 🛠️ 개발 환경

- 시뮬레이터: [GHDL](https://ghdl.readthedocs.io/) 또는 [ModelSim](https://eda.sw.siemens.com/en-US/ic/model/)
- 파형 보기: GTKWave
- 편집기: VS Code + VHDL Extension

---

## 📎 사용 방법

```bash
git clone https://github.com/your-username/vhdl-learning.git
cd vhdl-learning

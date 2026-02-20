# 📚 Paper Review and Practice (FDD & PHM)

이 저장소는 기계공학 전공 및 인공지능 연구를 진행하며 읽은 **고장 진단(FDD)** 및 **상태 감시(PHM)** 관련 논문들을 리뷰하고, 핵심 알고리즘을 직접 구현(Practice)한 기록 공간입니다.

---

## 🛠️ Tech Stack
- **Languages:** Python (PyTorch, SciPy)
- **Domain:** Mechanical Engineering, Signal Processing, Fault Diagnosis
- **Topics:** Time-Series Classification, STFT, Physics-Informed Neural Networks

---

## 📑 Paper Review List

가장 최근에 공부한 논문부터 순서대로 정리합니다.

### 1. Signal Processing & Basic Theory
| Index | Topic | Paper Title | Implementation | Status |
| :---: | :--- | :--- | :---: | :---: |
| 01 | STFT | Short-Time Fourier Transform for Signal Analysis | [Code](./Codes/STFT_Basic.ipynb) | ✅ Done |
| 02 | FFT | Fast Fourier Transform in Mechanical Vibrations | - | ⏳ Doing |

### 2. Deep Learning for Fault Diagnosis (FDD)
| Index | Topic | Paper Title | Implementation | Status |
| :---: | :--- | :--- | :---: | :---: |
| 01 | CNN | Deep Convolutional Neural Networks for Bearing Fault Diagnosis | [Code]() | 📅 Todo |
| 02 | LSTM | Time-Series Domain Adaptation for Predictive Maintenance | [Code]() | 📅 Todo |

---

## 🔬 Current Research Focus
- **Adaptive Time-Series Classification:** 선택적 학습 및 물리 정보 기반 커널 크기 조정 알고리즘(Plan A) 연구 중.
- **Hardware Testbed:** 펠티에 소자를 활용한 히트펌프 시스템 고장 진단 하드웨어 테스트베드 데이터 분석.

---

## 📂 Repository Structure

- `Theory/`: 논문 핵심 내용 요약 및 수식 정리 (Markdown)
- `Codes/`: 논문 핵심 알고리즘 구현 코드 (Jupyter Notebook / Python)
- `Images/`: 논문 리뷰에 사용된 주요 도표 및 결과 시각화 자료
- `Papers/`: (선택 사항) 읽은 논문 PDF 또는 링크 관리

---

## ✍️ How to Review
1. **Introduction:** 논문의 동기 및 기존 연구의 한계점 파악
2. **Methodology:** 핵심 알고리즘 및 수식 이해 (STFT, CNN 구조 등)
3. **Experiments:** 데이터셋 구성 및 성능 지표 분석
4. **My Opinion:** 실제 내 연구(세탁기/건조기 고장 진단 등)에 적용할 점

[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.15380270.svg)](https://doi.org/10.5281/zenodo.15380270)
![Topics: quantum-circuit, decoherence, feedback, self-organization, PiTer](https://img.shields.io/badge/topics-quantum--circuit%2C%20decoherence%2C%20feedback%2C%20self--organization%2C%20PiTer-blue)

# Quantum Feedback Structure over Decoherence Space

**Decoherence as Codomain: Feedback-Guided Structural Emergence in Quantum Circuits**
**공역으로서의 디코히어런스: 피드백 기반 양자 회로 구조 형성 실험**

---

## 🔍 Overview

This repository presents an experimental approach to understanding how decoherence, typically regarded as noise, can instead serve as a *possibility space (codomain)* over which quantum circuit structure (range) is formed through feedback. This feedback involves entropy tracking, dominant output monitoring, and circuit expansion based on internal stability conditions.

본 리포지터리는 일반적으로 억제 대상인 디코히어런스를 오류가 아닌 '구조 이전의 가능성 공간(공역)'으로 간주하고, 피드백 조건을 통해 양자 회로 구조(치역)가 형성될 수 있는지를 실험합니다. 출력 엔트로피, 편향, 반복적 상태 등을 기준으로 구조가 확장됩니다.

---

## 📁 Repository Structure

```
decoh_as_codom/
├── 01_paper/
│   ├── decoh_as_codom_En.md        # 논문 마크다운 (영문)
│   ├── decoh_as_codom_En.pdf       # 논문 PDF (영문)
│   ├── decoh_as_codom_Ko.md     # 논문 마크다운 (한글)
│   ├── decoh_as_codom_Ko.pdf    # 논문 PDF (한글)
│   └── figures/
│       ├── result_1.png
│       └── result_2.png
├── 02_experiments/
│   ├── modelA.ipynb   # 피드백 구조 실험
│   └── modelB.ipynb # 조건 확장 피드백 구조 실험
├── 03_note/    #  ChatGPT session
│   └── session.pdf
│   └── session.md
├── .gitignore
├── LICENSE
└── README.md                        # 본 문서
```

---

## 🧪 Experimental Highlights

## 🧪 실험 요약

* **Decoherence as Substrate**: Thermal noise is applied deliberately using Qiskit Aer noise model.
  **기판으로서의 디코히어런스**: Qiskit Aer 노이즈 모델을 이용하여 열 잡음을 의도적으로 적용함.
* **Feedback Loop**: Structure expands only when dominant state repetition or entropy-bias thresholds are met.
  **피드백 루프**: 우세 상태 반복 또는 엔트로피-편향 조건이 충족될 때에만 구조가 확장됨.
* **Dual Mechanism**: Two experimental models demonstrate entropy-driven vs. bias-reinforced growth patterns.
  **이중 메커니즘**: 엔트로피 기반과 편향 기반 구조 확장을 각각 실험적으로 제시함.


---

## 📌 핵심 개념

* **Codomain-first computing**: Treats noise not as error but as pre-structural possibility.
  **공역 우선 컴퓨팅**: 노이즈를 오류가 아닌 구조 이전의 가능성으로 간주.
* **Feedback conditionally triggers structure**: No fixed size—growth is feedback-driven.
  **조건부 피드백 구조화**: 회로 크기가 고정되지 않으며 피드백에 따라 유기적으로 확장됨.
* **Observer is implicit**: Dominance and entropy encode environmental responsiveness.
  **묵시적 관측자 모델**: 우세 상태와 엔트로피는 환경 반응성을 암묵적으로 반영함.

---

## 🔖 Tags

`quantum-circuit` `feedback` `decoherence` `adaptive-structure` `entropy` `conditional-growth`

---

## 🔗 Related Projects

* [`quantum-intent-feedback`](https://github.com/anon0411/quantum-intent-feedback): Core experiments on observer-influenced quantum circuits.
* [`quantum-entropy-bias`](https://github.com/anon0411/quantum-entropy-bias): Conditional growth under entropy-bias coupling.
* [`structure-as-output`](https://github.com/anon0411/structure-as-output): Experiments in structural emergence under environmental constraints.

---

## ⚖️ License

## ⚖️ 라이선스

This project is licensed under the **Creative Commons Attribution 4.0 International (CC BY 4.0)**.
본 프로젝트는 **CC BY 4.0 국제 라이선스**에 따라 배포됩니다.

---

> *"Feedback doesn’t just update; it builds."*
> — *Principle of codomain-based feedback growth*

---

*Last updated: 2025-05-10*

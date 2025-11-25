# Awesome Time Series Foundation Model (TSFM)

A curated and structured list of **time series foundation model**

---

## Table of Contents
- [FM in Time Series](#fm-in-time-series)
  - [Method Taxonomy](#method-taxonomy)
  - [Setting Taxonomy](#setting-taxonomy)
  - [Survey Papers](#survey-papers)
  - [Research Papers](#research-papers)
- [Acknowledgements](#acknowledgements)

---

## FM in Time Series

### Method Taxonomy

- **Modality**
  - Single Variate — `Mod-Single`
  - Multi Variate — `Mod-Multi`
  - Both — `Mod-Both`

- **Pre-training Strategy**
  - Pretrained Vision Language Model — `PT-VLM`
  - Pretrained Large Language Model — `PT-LLM`
  - Pretrained Audio Model —`PT-AM`
  - Fully Supervised — `PT-Sup`
  - Self-supervised — Learning
    - Generative — `PT-SSL-Gen`
    - Contrastive — `PT-SSL-Con`
    - Hybrid — `PT-SSL-Hyb`

- **Adaptation Method**
  - Prompt Engineering — `Adapt-Prompt`
  - Tokenization Design — `Adapt-Token`
  - Fine-tuning — `Adapt-FT`
  - Zero-shot Inference — `Adapt-ZS`

- **Architecture**
  - Non Transformer — `Arch-NonTF`
  - Transformer
    - Encoder — `Arch-TF-Enc`
    - Decoder — `Arch-TF-Dec`
    - Encoder Decoder — `Arch-TF-EncDec`
  - Diffusion Model — `Arch-Diff`

- **Variable Support**
  - Univariate — `Var-Uni`
  - Multivariate — `Var-Multi`
  - Both — `Var-Both`

- **Loss Function**
  - Mean Squared Error — `Loss-MSE`
  - Huber Loss — `Loss-Huber`
  - Negative Log Likelihood — `Loss-NLL`
  - Cross Entropy — `Loss-CE`

- **Patch-based Input**
  - Patchified Input — `Patch-Yes`
  - No Patchification — `Patch-No`

- **Probabilistic Type**
  - Probabilistic — `Prob-Yes`
  - Deterministic — `Prob-No`

### Setting Taxonomy

- **Task-Aware**
  - Time series forecasting `TSF`
  - Time series classification `TSC`

- **General**
  - Online `Sett-Online`
  - Task-Free `Sett-TaskFree`

### Survey Papers

| **Title** | **Year** | **Venue** | **Type** | **Setting** |
|-----------|----------|-----------|----------|-------------|
| Foundation models for time series: A survey | 2025 | ArXiv | survey paper |  |
| An empirical valuation of foundation models for multivariate time series classification | 2025 | KDD | benchmark paper |  |
| Foundation models for time series analysis: A tutorial and survey | 2024 | KDD | survey paper |  |
| A survey on time-series pre-trained models | 2024 | TKDE | survey paper |  |
| Self-supervised learning for time series: Contrastive or generative? | 2023 | IJCAI | benchmark paper |  |

### Research Papers

| **Title** | **Year** | **Venue** |
|-----------|----------|-----------|
| Training-free time series classification via in-context reasoning with llm agents -- FETA | 2025 | ArXiv |
| FinCast: A foundation model for financial time-series forecasting -- FinCast | 2025 | IKCIKM |
| Pre-training Time Series Models with Stock Data Customization -- SSPT | 2025 | KDD |
| A decoder-only foundation model for time-series forecasting -- TimesFM | 2023 | ArXiv |
| Lag-Llama: Towards foundation models for probabilistic time series forecasting -- Lag-Llama | 2023 | ArXiv |
| TimeGPT-1 -- TimeGPT-1 | 2023 | ArXiv |
| Chronos: Learning the language of time series by Amazon -- Chronos | 2024 | ArXiv |
| Timer: Generative pre-trained transformers are Large time series Models -- Timer | 2024 | ArXiv |
| Unified training of universal time series forecasting transformers -- Moirai | 2024 | ArXiv |
| Tiny Time Mixers (TTMs): Fast pre-trained models for enhanced zero/few-shot forecasting of multivariate time series -- Tiny Time Mixers | 2024 | NeurIPS |
| TOTEM: Tokenized time Series embeddings for general time series analysis -- TOTEM | 2024 | TMLR |

---

## Acknowledgements
Inspired by awesome lists in time series foundation model:

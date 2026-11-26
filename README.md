<div align="center">

# Eduardo Leandro

**Visão computacional & IA embarcada** · Engenharia da Computação (UFAM) · Manaus, Brasil 🇧🇷

_Do modelo treinado ao binário rodando na NPU da placa._

[![Email](https://img.shields.io/badge/leandroedueng@gmail.com-D14836?style=flat-square&logo=gmail&logoColor=white)](mailto:leandroedueng@gmail.com)

</div>

---

Desenvolvo sistemas de visão computacional que rodam **na borda**: treino e converto modelos (YOLO → ONNX → INT8),
escrevo a inferência em C/C++ e Python direto no hardware e uso **PDI clássico** onde deep learning não é a melhor
ferramenta. Comecei com desenvolvimento mobile e Java; hoje meu foco é levar o pipeline completo até a placa e medir
o resultado em hardware real, não só em simulação.

---

## 🔧 Projeto em destaque

### [sdkEldenGinner](https://github.com/EldenGineer/sdkEldenGinner) — gerenciador de câmeras V4L2
Ferramenta (GUI em PySide6 + CLI) para capturar datasets com controle total da câmera: modos e controles lidos do
driver, verificação do modo negociado, fotos com metadados em JSON, vídeo H.264/NVENC via ffmpeg com duração real,
modo rajada e navegação completa por teclado. Instalador idempotente e suíte de testes sem hardware.

`Python` `PySide6` `V4L2` `OpenCV` `ffmpeg` `pytest`

---

## 🏭 Experiência

**Desenvolvedor de IA embarcada / visão computacional** _(projetos com código privado)_
- **YOLOv8 na NPU da Radxa Dragon Q6A (QCS6490 / HTP v68):** pipeline em Docker `.pt → .onnx → .dlc → INT8 → context-binary`,
  quantização com calibração no domínio, inferência em C pela API QNN direta, câmera ao vivo e benchmarks na placa.
- **Inspeção visual industrial** de peças reflexivas: câmara com 3 câmeras e iluminação difusa controlada.
- **Inspeção de placas:** YOLO para localizar a placa + ROIs relativas com PDI.
- **Luckfox Pico Ultra (RV1106):** reconhecimento de gestos e detecção de instrumentos, YOLO → RKNN INT8, inferência em C++.

---

## 🛠️ Stack

| Área | Ferramentas |
|---|---|
| **Linguagens** | Python · C · C++ · Java · TypeScript |
| **Visão / IA** | PyTorch · Ultralytics YOLO · OpenCV · ONNX |
| **Borda** | Qualcomm QAIRT/QNN · Rockchip RKNN · Linux embarcado · V4L2 |
| **Ferramentas** | Docker · Git · ffmpeg · PySide6 |
| **Mobile** | React Native · Expo · Firebase · SQLite |
| **Hardware** | Radxa Dragon Q6A (QCS6490) · Luckfox Pico Ultra (RV1106) · FPGA Cyclone IV (VHDL) |

---

<details>
<summary>📊 Atividade no GitHub</summary>
<br>

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/EldenGineer/EldenGineer/output/github-snake-dark.svg" />
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/EldenGineer/EldenGineer/output/github-snake.svg" />
  <img alt="Contribuições" src="https://raw.githubusercontent.com/EldenGineer/EldenGineer/output/github-snake.svg" />
</picture>

<div align="center">

![Métricas do GitHub](https://raw.githubusercontent.com/EldenGineer/EldenGineer/main/metrics.svg)

</div>
</details>

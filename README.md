<p align="center">
  <img src="https://gitascii.com/api/hammadhaideer?widgets=premium-ascii-profile-card" alt="Hammad Ali Haider GitAscii profile card" width="100%" />
</p>

<p align="center">
  Visual Anomaly Detection · Foundation Models · Parameter-Efficient Adaptation · Industrial Inspection
</p>
<p align="center">
  MSc Researcher, Xinjiang University · Ürümqi, China
</p>
<p align="center">
  <a href="https://linkedin.com/in/hammadhaideer"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white" alt="LinkedIn" /></a>
  <a href="mailto:hammadhaideerr@stu.xju.edu.cn"><img src="https://img.shields.io/badge/Academic_Email-444444?style=flat-square&logo=gmail&logoColor=white" alt="Email" /></a>
</p>

## Research focus

I am an MSc researcher in Computer Science and Technology at Xinjiang University, supervised by **Panpan Zheng**.

My main research area is **visual anomaly detection**, with a focus on foundation models and parameter-efficient adaptation for industrial inspection under distribution shift. I work with **CLIP, DINOv2, SAM, LoRA, adapters, visual prompts, continual learning, and test-time adaptation** across industrial, logical, and medical anomaly-detection settings.

I also work on time-series anomaly detection with time-series foundation models as a secondary part of my MSc research.

**First-author paper under review (2026)** in visual anomaly detection.

## Selected public research work

| Project | Scope | Reproduction evidence |
|---|---|---|
| **[AF-CLIP Reproduced](https://github.com/hammadhaideer/af-clip-reproduced)** | Zero-shot image and pixel anomaly detection across six industrial benchmarks | Five paper-reported benchmarks match the published results at one-decimal precision; MVTec-LOCO added as a cross-dataset extension |
| **[APRIL-GAN Reproduced](https://github.com/hammadhaideer/april-gan-reproduced)** | Official zero-shot protocol on MVTec-AD and VisA | All seven aggregate metrics reproduced; maximum absolute paper delta is 0.5 percentage points |
| **[AnomalyCLIP Reproduced](https://github.com/hammadhaideer/anomalyclip-reproduced)** | Zero-shot industrial anomaly detection on MVTec-AD and VisA | Paper-compatible final-layer evaluation with sanitized logs, aggregate summaries, source provenance, and repository verification |
| **[WinCLIP Reproduced](https://github.com/hammadhaideer/winclip-reproduced)** | Zero-shot anomaly classification and segmentation on MVTec-AD and VisA | Reference results reproduced and diagnostic implementation differences documented separately |

These repositories are independent reproduction and evaluation work. Upstream methods, source code, checkpoints, and datasets remain attributed to their original authors and licenses.

## How I structure research code

For public reproduction work, I try to keep the evidence inspectable:

- pin upstream source revisions and checkpoint provenance where possible;
- keep paper-compatible results separate from diagnostic experiments;
- preserve sanitized raw logs and machine-readable summaries;
- publish environment, run, parsing, and verification instructions;
- document deviations instead of hiding failed or mismatched implementation paths.

## Current engineering focus

My research stack has been mostly Python-side. I am now moving reproduced anomaly-detection models toward **C++ and OpenCV deployment**, followed by **ONNX and TensorRT inference, INT8 quantization, and measured latency comparisons**. The deployment work will be published only after the measurements are complete.

## Technical stack

**Research:** Visual Anomaly Detection · CLIP · DINOv2 · SAM · LoRA · PEFT · Continual Learning · Test-Time Adaptation · Domain Shift

**Engineering:** Python · PyTorch · OpenCV · C/C++ · Hugging Face · NumPy · Docker · FastAPI · GitHub Actions · Linux · Git

**Benchmarks:** MVTec-AD · MVTec-LOCO · VisA · BTAD · DAGM · DTD-Synthetic

## Contact

- Academic email: [hammadhaideerr@stu.xju.edu.cn](mailto:hammadhaideerr@stu.xju.edu.cn)
- LinkedIn: [linkedin.com/in/hammadhaideer](https://linkedin.com/in/hammadhaideer)

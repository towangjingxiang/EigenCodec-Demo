# EigenCodec: UUltra-Low Bitrate Narrowband Speech Coding via Eigen-Informed Subspace Projection and Multi-Scale Depthwise Aggregation

This page provides supplementary audio samples for our submitted manuscript to JASA.

**Model:** EigenCodec  
**Task:** 8 kHz Narrowband Speech Coding at sub-1 kbps  
**Target Bitrate for Comparison:** 0.8 kbps (unless specified otherwise)

**Fairness Protocol:** All end-to-end neural baselines (EnCodec, HiFi-Codec, MSCACodec, DAC, DAC-s, HILCodec) were explicitly **retrained from scratch** on the 8 kHz LibriSpeech dataset and constrained to an identical bottleneck (25 Hz frame rate $\times$ 4 codebooks) to ensure a strictly fair comparison.

---

### Sample 1: From `test-clean` (High-quality recording condition)

**1. Ground Truth (Original) | Uncompressed**

<audio controls>
  <source src="audio/Original-clean.wav" type="audio/wav">
</audio>

**2. Codec2 (Parametric) | 1.2 kbps**

<audio controls>
  <source src="audio/Codec2-1.2-clean.wav" type="audio/wav">
</audio>

**3. Codec2 (Parametric) | 2.4 kbps**

<audio controls>
  <source src="audio/Codec2-2.4-clean.wav" type="audio/wav">
</audio>

**4. Lyra-V2 (Generative) | 3.2 kbps**

<audio controls>
  <source src="audio/Lyra-V2-3.2-clean.wav" type="audio/wav">
</audio>

**5. EnCodec (Retrained) | 0.8 kbps**

<audio controls>
  <source src="audio/Encodec-0.8-clean.wav" type="audio/wav">
</audio>

**6. HiFi-Codec (Retrained) | 0.8 kbps**

<audio controls>
  <source src="audio/HiFiCodec-0.8-clean.wav" type="audio/wav">
</audio>

**7. MSCACodec (Retrained) | 0.8 kbps**

<audio controls>
  <source src="audio/MSCACodec-0.8-clean.wav" type="audio/wav">
</audio>

**8. DAC (Retrained) | 0.8 kbps**

<audio controls>
  <source src="audio/DAC-0.8-clean.wav" type="audio/wav">
</audio>

**9. DAC-s (Retrained) | 0.8 kbps**

<audio controls>
  <source src="audio/DAC-s-0.8-clean.wav" type="audio/wav">
</audio>

**10. HILCodec (Retrained) | 0.8 kbps**

<audio controls>
  <source src="audio/HILCodec-0.8-clean.wav" type="audio/wav">
</audio>

**11. EigenCodec (Ours) | 0.8 kbps**

<audio controls>
  <source src="audio/EigenCodec-0.8-clean.wav" type="audio/wav">
</audio>


---
<br>

---

### Sample 2: From `test-other` (Challenging acoustic condition)

| Model | Bitrate | Audio Sample |
| :--- | :---: | :--- |
| **Ground Truth (Original)** | Uncompressed | <audio controls src="audio/Original-other.wav"></audio> |
| **Codec2** (Parametric) | 1.2 kbps | <audio controls src="audio/Codec2-1.2-other.wav"></audio> |
| **Codec2** (Parametric) | 2.4 kbps | <audio controls src="audio/Codec2-2.4-other.wav"></audio> |
| **Lyra-V2** (Generative) | 3.2 kbps | <audio controls src="audio/Lyra-V2-3.2-other.wav"></audio> |
| **EnCodec** (Retrained) | 0.8 kbps | <audio controls src="audio/Encodec-0.8-other.wav"></audio> |
| **HiFi-Codec** (Retrained) | 0.8 kbps | <audio controls src="audio/HiFiCodec-0.8-other.wav"></audio> |
| **MSCACodec** (Retrained) | 0.8 kbps | <audio controls src="audio/MSCACodec-0.8-other.wav"></audio> |
| **DAC** (Retrained) | 0.8 kbps | <audio controls src="audio/DAC-0.8-other.wav"></audio> |
| **DAC-s** (Retrained) | 0.8 kbps | <audio controls src="audio/DAC-s-0.8-other.wav"></audio> |
| **HILCodec** (Retrained) | 0.8 kbps | <audio controls src="audio/HILCodec-0.8-other.wav"></audio> |
| **EigenCodec (Ours)** | **0.8 kbps** | <audio controls src="audio/EigenCodec-0.8-other.wav"></audio> |


<br>

---

> *Note: The source code and pre-trained weights will be made publicly available upon the acceptance of the manuscript.*

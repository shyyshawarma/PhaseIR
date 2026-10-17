<p align="center">
  <h1 align="center">PhaseIR: Phase-Guided Attention Mechanism for Efficient Image Restoration</h1>
  <p align="center">
    <a href="">Abhinav Rajput</a>
    ·
    <a href="">Pihu Agrawal</a>
    ·
    <a href="">Xiaoyu Cao</a>
    ·
    <a href="">Xingjian Li</a>
    .
    <a href="">Min Xu</a>
  </p>
</p>

![PhaseIR.png]

Image restoration is a fundamental low-level vision task that aims to recover high-quality images from degraded observations. Such degradations adversely affect the performance of downstream computer vision tasks. To address this, we propose PhaseIR, a lightweight phase-guided transformer with 26M parameters for efficient image restoration. We introduce a phase-guided self-attention mechanism that leverages Fourier phase information to learn meaningful image features. We also introduce a phase-based channel attention block that selectively propagates informative structural features through skip connections. Furthermore, we employ an adaptive multi-loss optimization strategy to improve reconstruction quality. Extensive ablation studies and comparative analyses demonstrate that PhaseIR achieves state-of-the-art performance across diverse image restoration tasks, including image deraining, single-image motion deblurring, defocus deblurring (single-image and dual-pixel data), and image denoising (Gaussian grayscale/color denoising, and real image denoising).


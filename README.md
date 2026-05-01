# LiftingAvatar: One-Shot 3D Gaussian Avatar Generation and Animation
LiftingAvatar is a one-shot 3D avatar generation and animation framework. It takes only a single portrait image as input, and reconstructs a photorealistic 3D Gaussian avatar that can be driven by arbitrary expression and pose control signals.

---

## 🎬 Pipeline Overview
Given a single-shot portrait of any person, our system reconstructs a full 3D avatar, then animates it with different expressions and head poses. The output produces view-consistent results across novel viewpoints.

<div align="center">
<img src="fig1.jpg" width="900">
<br>
<em>Pipeline overview of LiftingAvatar</em>
</div>

---

## 🏆 Qualitative Results & Comparisons

### 1. Novel-view Comparison
We compare our method against prior work in terms of facial details (mouth, eyes):
- It preserves fine textures (beard, skin details) than some former methods.
- Rendering artifacts (blur, ghosting) in different views are reduced.

<div align="center">
<img src="fig2.jpg" width="900">
<br>
<em>Novel-view Comparison comparison with baseline methods</em>
</div>

### 2. Cross- and Self-Reenactment
- **Cross-reenactment**: Transferring expressions and poses from a different person to the generated avatar, while preserving the original subject’s identity.
- **Self-reenactment**: Replicating the original subject’s movements.

<div align="center">
<img src="fig3.jpg" width="900">
<br>
<em>Cross-reenactment and self-reenactment results</em>
</div>

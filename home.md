---
layout: default
title: JointDiT
---

<div class="post">
	<h2 class="pageTitle">JointDiT</h2>
	<h2 class="pageTitle">Animate and Sound an Image</h2>
    <p align="center">
	<img src="{{ '/assets/img/arch_JointDiT.png' | relative_url }}" alt="">
    </p>
	<p>This paper addresses a promising yet underexplored task, Image-to-Sounding-Video (I2SV) generation, which animates a static image and generates synchronized sound simultaneously. Despite advances in video and audio generation models, some challenges remain to develop a unified model for generating naturally sounding videos. 
In this work, we propose a novel approach that leverages two separate pretrained diffusion models and makes vision and audio influence each other during generation based on the Diffusion Transformer (DiT) architecture. 
First, the individual video and audio generation models are decomposed into input, output, and expert sub-modules. We propose using a unified joint DiT block in the expert sub-modules to effectively model the interaction between the two modalities, resulting in high-quality I2SV generation. 
Then, we introduce a joint classifier-free guidance technique to boost the performance during joint generation.
Finally, we conduct extensive experiments on three popular benchmark datasets, and in both objective and subjective evaluation our method surpass all the baseline methods in almost all metrics. Case studies show that our generated sounding videos are high quality and synchronized between video and audio.
	</p>



</div>


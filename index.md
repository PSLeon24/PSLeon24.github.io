---
layout: project_page
permalink: /

title: 딥페이크 생성 방지를 위한 확산 모델 맞춤형 방어 기법 연구
authors:
    Yeongmin Ko
affiliations:
    Pusan National University
paper: #
video: #
code: #
data: #
---

<!-- Using HTML to center the abstract -->
<div class="columns is-centered has-text-centered">
    <div class="column is-four-fifths">
        <h2>Abstract</h2>
        <div class="content has-text-justified">
            Remarkable advancements in latent diffusion models (LDMs) have raised ethical concerns, particularly regarding facial forgery and privacy violations. Recent studies have proposed anti-customization methods to deal with these problems proactively. Unfortunately, their focus on protective performance often results in noticeable perturbations, making them impractical in the real-world. Moreover, these methods struggle to remain effective against common image transformations such as JPEG compression. In this paper, we propose a novel anti-customization algorithm, dubbed AEGIS, that conceals highly imperceptible perturbations while remaining robust against image transformations. We first generate perturbation intensity maps utilizing face-parsing and superpixel-based stochastic perturbation scaling, which spatially control the magnitude of the perturbation updates during the noise optimization process. This allows us to arrange adversarial perturbations in perceptually insensitive regions while considering the optimal trade-off between imperceptibility and defense effectiveness. Furthermore, we integrate the Expectation Over Transformation (EOT) to improve robustness against various image transformations. Extensive experiments on CelebA-HQ and VGGFace2 demonstrate that our method significantly reduces the visibility of perturbations while maintaining defense performance comparable to that of existing approaches.
        </div>
    </div>
</div>

---

## Background
TBA

## Motivation
TBA


## Key Idea
1. TBD

*Figure 1: TBD*

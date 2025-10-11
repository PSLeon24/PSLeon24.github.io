---
layout: project_page
permalink: /

title: 비가시성과 강건성을 동시에 고려한 확산 모델 맞춤화 방어 기법
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
            Remarkable advancements in latent diffusion models (LDMs) allow photo-realistic image generation from simple text prompts. However, their misuse by malicious actors has raised ethical concerns, particularly regarding facial forgery and privacy violations. Therefore, recent studies have proposed anti-customization methods to deal with these problems proactively. Unfortunately, their focus on protective performance often results in noticeable perturbations, making them impractical for real-world applications. Moreover, these methods struggle to remain effective against common image transformations such as JPEG compression and Gaussian blur. In this paper, we propose a novel anti-customization algorithm, dubbed AEGIS, that generates highly imperceptible perturbations while remaining robust to various image transformations. We first generate perturbation intensity maps using face-parsing and superpixel-based random perturbation scaling, which spatially control the magnitude of the perturbation updates during the noise optimization process. This allows us to arrange adversarial perturbations in perceptually insensitive regions while considering the optimal tradeoff between defense effectiveness and visual imperceptibility. Furthermore, we integrate the Expectation Over Transformation (EOT) to improve robustness against various image transformations. Extensive experiments on CelebA-HQ and VGGFace2 demonstrate that our method significantly reduces the visibility of perturbations while maintaining defense performance comparable to that of existing approaches.
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

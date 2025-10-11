---
layout: project_page
permalink: /

title: 비가시성과 강건성을 동시에 고려한 확산 모델 맞춤화 방어 기법
authors:
    Yeongmin Ko
affiliations:
    TBA
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
            잠재 확산 모델(LDM)의 놀라운 발전으로 간단한 텍스트 프롬프트에서 사진처럼 사실적인 이미지를 생성할 수 있게 되었다. 그러나 악의적인 행위자에 의한 LDM의 오용으로 인해 특히 얼굴 위조 및 개인정보 침해와 관련된 윤리적 문제가 제기되었다. 최근 연구에서는 이러한 문제를 사전에 해결하기 위한 맞춤형 방지(Anti Customization) 방법이 제안되어 왔다. 하지만 기존의 방법들은 방어 성능에만 초점을 맞추다 보니 눈에 띄는 교란을 유발하여 실제 응용 분야에서는 실용적이지 않다는 한계가 있다. 더욱이 이러한 방법은 JPEG 압축 및 가우시안 블러와 같은 일반적인 이미지 변환에 대해서는 효과를 유지하기 어렵다. 본 연구에서는 다양한 이미지 변환에 강건하면서도 감지하기 어려운 교란을 생성하는 새로운 맞춤형 방지 알고리즘인 AEGIS를 제안한다. 먼저, 얼굴 분석 및 슈퍼픽셀 기반 랜덤 교란 스케일링을 사용하여 교란 강도 맵을 생성하며, 이는 노이즈 최적화 과정에서 교란 업데이트의 크기를 공간적으로 제어한다. 이를 통해 방어 효과와 시각적 비인지성 간의 최적의 균형을 고려하면서 지각적으로 둔감한 영역에 적대적인 교란을 배치할 수 있다. 또한, 다양한 이미지 변환에 대한 강건성을 향상시키기 위해 변환 대비 기대값(EOT)을 통합한다. CelebA-HQ와 VGGFace2에 대한 광범위한 실험을 통해 본 방법이 기존 방식과 유사한 방어 성능을 유지하면서 교란의 가시성을 크게 감소시킨다는 것을 입증하였다.
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

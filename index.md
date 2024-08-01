# HOPID: Heterogeneous Prompt-Guided Entity Inferring and Distilling for Scene-Text Aware Cross-modal Retrieval

![alt text](hopid.png)


## [1/5] Task Introduction

<div style="display: flex; justify-content: space-between;">
    <figure>
        <img src="images/fig_3.gif" alt="Introduction Image" style="width: 100%;">
    </figure>
</div>

<!-- <div style="display: flex; justify-content: space-between;">
    <figure>
        <video controls style="width: 100%;">
            <source src="video.mp4" type="video/mp4">
            Your browser does not support the video tag.
        </video>
    </figure>
</div> -->

### [2/5] Semantic Ambiguity Issue & Retrieval Process

<div style="display: flex; justify-content: space-between;">
    <figure>
        <img src="images/fig_1.gif" alt="New Visualization" style="width: 100%;">
    </figure>
</div>

<!-- <div style="display: flex; justify-content: space-between;">
    <figure>
        <video controls style="width: 100%;">
            <source src="video2.mp4" type="video/mp4">
            Your browser does not support the video tag.
        </video>
    </figure>
</div> -->

## [3/5] Attention Maps

<div style="display: flex; justify-content: space-between;">
    <figure>
        <img src="images/attention_map.png" alt="t-SNE Image" style="width: 100%;">
    </figure>
</div>

## [4/5] T-SNE Visualization

<div style="display: flex; justify-content: space-between;">
    <figure>
        <img src="images/t_sne.jpg" alt="t-SNE Visualization" style="width: 80%;">
    </figure>
</div>

## [5/5] TEXT→IMG Retrieval (1/2) 📄🔍🎆
![TEXT→IMG Retrieval (1/2)](images/i2t_1.png)

## [5/5] TEXT→IMG Retrieval (2/2) 📄🔍🎆
![TEXT→IMG Retrieval (2/2)](images/i2t_2.png)

## [5/5] IMG→TEXT Retrieval (1/2) 🎆🔍📄
![IMG→TEXT Retrieval (1/2)](images/t2i_1.png)

## [5/5] IMG→TEXT Retrieval (2/2) 🎆🔍📄
![IMG→TEXT Retrieval (2/2)](images/t2i_2.png)


## Abstract
In cross-modal retrieval, comprehensive image understanding is vital while the scene text in images can provide fine-grained information to understand visual semantics. Recent works try to make full use of scene text, but they still suffer from the semantic ambiguity of independent scene text. To address this issue, we propose a novel heterogeneous prompt-guided entity inferring and distilling network to explore the inherent connection of scene text across different modalities and learn property-centric scene text representation. Specifically, we first introduce the discriminative entity inferring module which infers the discriminative entity words in captions to build text prompt. Then we align these words with the scene text in images to narrow the cross-modal gap via heterogeneous prompt learning. Simultaneously, we enhance the contextual information of scene text by locating them in images through visual prompt to alleviate local noise. Furthermore, to secure a robust scene text representation, we design a perceptive entity distilling module that distills the beneficial information of scene text at a fine-grained level. Extensive experiments show that the proposed method significantly outperforms existing approaches on two public cross-modal retrieval benchmarks.
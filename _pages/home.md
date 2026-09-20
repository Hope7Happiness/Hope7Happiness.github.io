---
title: ""
layout: single
author_profile: true
permalink: /
---

# About Me

I am an undergraduate at MIT studying Physics and Artificial Intelligence & Decision Making, expected to graduate in 2027. I am an undergraduate researcher in Professor [Kaiming He](https://people.csail.mit.edu/kaiming)’s group, where I have worked on computer vision, generative modeling and (most recently) multi-agent systems.

My research experience spans diffusion models, one-step image generation, and multimodal training. Alongside this work, I build training infrastructure, including JAX/TPU workflows, distributed optimization, and tools for managing research experiments. I am especially interested in large-scale model training and applying my research experience to build real-world AI products that benefit people broadly.

I am now seeking full-time Research Engineer or Machine Learning Engineer roles, with particular interest in teams working on agents, multimodal models, or training infrastructure. Please feel free to reach out about relevant opportunities or collaborations.

Beyond academics, I also enjoy engaging with people who share similar interests and chatting about anything from research ideas to life experiences. Feel free to reach out if you'd like to connect!

My resume is linked [here](/assets/pdf/cv.pdf).

## Publications & Projects

<style>
.publication-meta {
    display: flex;
    align-items: flex-start;
    gap: 12px;
    margin-bottom: 10px;
}

.page__content .publication-authors {
    flex: 1 1 auto;
    min-width: 0;
    font-size: 14px;
    margin-top: 0;
    margin-bottom: 0;
}

.page__content .publication-venue {
    flex: 0 0 auto;
    white-space: nowrap;
    text-align: right;
    font-size: 14px;
    margin-top: 0;
    margin-bottom: 0;
}
</style>

<div class="row">
    <div class="column" style="display: inline-block; vertical-align: top; width: 25%;">
        <a href="https://peppaking8.github.io/#/post/minit2i"><img src="/assets/images/publications/minit2i.png"></a>
    </div>
    <div class="column" style="display: inline-block; vertical-align: top; width: 70%; margin-left: 3%">
        <p style="display: inline-block; vertical-align: top; font-size: 16px; margin-bottom: 0;"><a href="https://peppaking8.github.io/#/post/minit2i" style="text-decoration: none; color: inherit;"><b>MiniT2I: A Minimalist Baseline for Text-to-Image Generation</b></a></p>
        <p style="display: inline-block; vertical-align: top; font-size: 14px; margin-top: 0; margin-bottom: 10px;">
                <span style="color: gray;">X. Wang<sup>*</sup></span>, 
                <u><b>H. Zhao<sup>*</sup></b></u>,
                <span style="color: gray;">Y. Lu<sup>*</sup></span>, 
                <span style="color: gray;">K. Zhou</span>, 
                <span style="color: gray;">L. Ma</span>, 
                <span style="color: gray;">and K. He</span>
        </p>
        <br>
        <p style="display: inline-block; vertical-align: top; font-size: 16px; margin-top: 10px;">
             <a href="https://peppaking8.github.io/#/post/minit2i" style="text-decoration: none; color: blue;">[Blog]</a>
             <a href="https://github.com/Hope7Happiness/minit2i-torch" style="text-decoration: none; color: blue;">[PyTorch Code]</a>
             <a href="https://github.com/PeppaKing8/minit2i-jax" style="text-decoration: none; color: blue;">[JAX Code]</a>
        </p>
    </div>
</div>


<!-- space -->
<br>


<div class="row">
    <div class="column" style="display: inline-block; vertical-align: top; width: 25%;">
        <a href="/assets/images/publications/elf.png"><img src="/assets/images/publications/elf.png"></a>
    </div>
    <div class="column" style="display: inline-block; vertical-align: top; width: 70%; margin-left: 3%">
        <p style="display: inline-block; vertical-align: top; font-size: 16px; margin-bottom: 0;"><b>ELF: Embedded Language Flows</b></p>
        <p style="display: inline-block; vertical-align: top; font-size: 14px; margin-top: 0; margin-bottom: 10px;">
                <span style="color: gray;">K. Hu<sup>*</sup></span>, 
                <span style="color: gray;">L. Qiu<sup>*</sup></span>, 
                <span style="color: gray;">Y. Lu</span>, 
                <!--<span style="color: gray;">H. Zhao</span>, -->
                <u><b>H. Zhao</b></u>,
                <span style="color: gray;">T. Li</span>, 
                <span style="color: gray;">Y. Kim</span>, 
                <span style="color: gray;">J. Andreas</span>, 
                <span style="color: gray;">and K. He</span>
        </p>
        <!-- <p style="display: inline-block; vertical-align: top; font-size: 14px; margin-top: 0; margin-bottom: 10px; text-align: right; width: 40%;">
                <b>(Neurips 2026)</b>
        </p> -->
        <br>
        <p style="display: inline-block; vertical-align: top; font-size: 16px; margin-top: 10px;">
             <a href="https://arxiv.org/abs/2605.10938" style="text-decoration: none; color: blue;">[Paper]</a>
             <a href="https://github.com/lillian039/ELF" style="text-decoration: none; color: blue;">[Code]</a>
        </p>
    </div>
</div>

<!-- space -->
<br>

<div class="row">
    <div class="column" style="display: inline-block; vertical-align: top; width: 25%;">
        <a href="/assets/images/publications/pmf.png"><img src="/assets/images/publications/pmf.png"></a>
    </div>
    <div class="column" style="display: inline-block; vertical-align: top; width: 70%; margin-left: 3%">
        <p style="display: inline-block; vertical-align: top; font-size: 16px; margin-bottom: 0;"><b>One-step Latent-free Image Generation with Pixel Mean Flows</b></p>
        <div class="publication-meta">
        <p class="publication-authors">
                <span style="color: gray;">Y. Lu<sup>*</sup></span>, 
                <span style="color: gray;">S. Lu<sup>*</sup></span>, 
                <span style="color: gray;">Q. Sun<sup>*</sup></span>, 
                <u><b>H. Zhao<sup>*</sup></b></u>, 
                <span style="color: gray;">Z. Jiang</span>, 
                <span style="color: gray;">X. Wang</span>, 
                <span style="color: gray;">T. Li</span>, 
                <span style="color: gray;">Z. Geng</span>, 
                <span style="color: gray;">and K. He</span>
        </p>
         <p class="publication-venue">
                <b>(ICML 2026)</b>
        </p> 
        </div>
        <br>
        <p style="display: inline-block; vertical-align: top; font-size: 16px; margin-top: 10px;">
             <a href="https://arxiv.org/abs/2601.22158" style="text-decoration: none; color: blue;">[Paper]</a>
             <a href="https://github.com/Lyy-iiis/pMF" style="text-decoration: none; color: blue;">[Code]</a>
        </p>
    </div>
</div>

<!-- space -->
<br>

<div class="row">
    <div class="column" style="display: inline-block; vertical-align: top; width: 25%;">
        <a href="/assets/images/publications/biflow.png"><img src="/assets/images/publications/biflow.png"></a>
    </div>
    <div class="column" style="display: inline-block; vertical-align: top; width: 70%; margin-left: 3%">
        <p style="display: inline-block; vertical-align: top; font-size: 16px; margin-bottom: 0;"><b>Bidirectional Normalizing Flow: From Data to Noise and Back</b></p>
        <div class="publication-meta">
        <p class="publication-authors">
                <span style="color: gray;">Y. Lu<sup>*</sup></span>, 
                <span style="color: gray;">Q. Sun<sup>*</sup></span>, 
                <span style="color: gray;">X. Wang<sup>*</sup></span>, 
                <span style="color: gray;">Z. Jiang</span>, 
                <u><b>H. Zhao</b></u>, 
                <span style="color: gray;">and K. He</span>
        </p>
         <p class="publication-venue">
                <b>(CVPR 2026)</b>
        </p> 
        </div>
        <br>
        <p style="display: inline-block; vertical-align: top; font-size: 16px; margin-top: 10px;">
             <a href="https://arxiv.org/abs/2512.10953" style="text-decoration: none; color: blue;">[Paper]</a>
             <a href="https://github.com/Lyy-iiis/BiFlow" style="text-decoration: none; color: blue;">[Code]</a>
        </p>
    </div>
</div>

<!-- space -->
<br>

<div class="row">
    <div class="column" style="display: inline-block; vertical-align: top; width: 25%;">
        <a href="/assets/images/publications/wot.png"><img src="/assets/images/publications/wot.png"></a>
    </div>
    <div class="column" style="display: inline-block; vertical-align: top; width: 70%; margin-left: 3%">
        <p style="display: inline-block; vertical-align: top; font-size: 16px; margin-bottom: 0;"><b>Is Noise Conditioning Necessary for Denoising Generative Models?</b></p>
        <div class="publication-meta">
        <p class="publication-authors">
                <span style="color: gray;">Q. Sun<sup>*</sup></span>, 
                <span style="color: gray;">Z. Jiang<sup>*</sup></span>, 
                <u><b>H. Zhao<sup>*</sup></b></u>, 
                <span style="color: gray;">and K. He</span>
        </p>
        <p class="publication-venue">
                <b>(ICML 2025)</b>
        </p>
        </div>
        <br>
        <p style="display: inline-block; vertical-align: top; font-size: 16px; margin-top: 10px;">
             <a href="https://arxiv.org/abs/2502.13129" style="text-decoration: none; color: blue;">[Paper]</a>
        </p>
    </div>
</div>


## Other Projects

- [**Sparkie — A teammate in your meeting**](/sparkie/)

    A voice agent that joins Zoom conversations and delegates project work to a background coding agent. [Project website](/sparkie/) · [Code](https://github.com/Hope7Happiness/sparkie)

- [**Speeding Up Diffusion Models with One-step Generators**](https://github.com/Hope7Happiness/6s978_project)

    <p style="font-size: 18px;">This is the final project for the seminar course <i>6.S978: Deep Generative Models</i> at MIT. In the project, we proposed a new method to speed up the training of diffusion models by using one-step generators. On toy experiments, this reduces NFE by half while maintaining the sample quality. We also wrote a <a href="/three_diff/">blog post</a>, explaining the motivation of the experiment from a higher perspective.</p>

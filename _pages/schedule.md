---
layout: page
title: Schedule
permalink: /schedule/
nav: true
nav_order: 2
description:
_styles: |
  .schedule-table {
    width: 100%;
    border-collapse: collapse;
  }
  .schedule-table th,
  .schedule-table td {
    border-bottom: 1px solid var(--global-divider-color);
    padding: 0.65rem 0.75rem;
    vertical-align: top;
  }
  .schedule-table th {
    text-align: left;
    font-weight: 700;
    font-size: 0.95rem;
  }
  .schedule-table td ul {
    margin: 0.1rem 0 0;
    padding-left: 1.1rem;
    font-size: 0.95rem;
  }
  .schedule-table .event {
    white-space: nowrap;
    font-weight: 600;
  }
  .schedule-table td p {
    margin: 0 0 0.15rem;
  }
  .schedule-table .section-row td {
    background: rgba(0, 118, 223, 0.08);
    font-weight: 700;
    text-align: center;
    padding: 0.75rem;
  }
---

<table class="schedule-table">
  <thead>
    <tr>
      <th>Event</th>
      <th>Date</th>
      <th>Description / Slides</th>
      <th>Course Materials</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td class="event">Lecture 1</td>
      <td>MM/DD</td>
      <td>Intro: transformers and autoregressive language models.<br><a href="#" aria-label="Lecture 1 slides">[Slides]</a></td>
      <td>
        <p>Readings:</p>
        <ul>
          <li><a href="https://arxiv.org/abs/1706.03762" target="_blank" rel="noopener">Attention Is All You Need</a></li>
          <li><a href="https://jalammar.github.io/illustrated-transformer/" target="_blank" rel="noopener">The Illustrated Transformer</a></li>
          <li><a href="https://proceedings.mlr.press/v162/wang22u/wang22u.pdf" target="_blank" rel="noopener">What Language Model Architecture and Pretraining Objective Work Best for Zero-Shot Generalization?</a></li>
        </ul>
      </td>
    </tr>
    <tr>
      <td class="event">Presentation 1</td>
      <td>MM/DD</td>
      <td>Student paper presentations.<br><a href="#" aria-label="Presentation slides">[Slides]</a></td>
      <td>
        <p>Presentation paper: [link]</p>
      </td>
    </tr>
    <tr class="section-row">
      <td colspan="4">Part 1: Pre-training</td>
    </tr>
    <tr>
      <td class="event">Lecture 2</td>
      <td>MM/DD</td>
      <td>What's the purpose of pre-training? What's in the pre-training dataset?<br><a href="#" aria-label="Lecture 1 slides">[Slides]</a></td>
      <td>
        <p>Readings:</p>
        <ul>
          <li><a href="https://arxiv.org/pdf/2310.20707" target="_blank" rel="noopener">What's In My Big Data?</a></li>
          <li><a href="https://arxiv.org/abs/2305.13169" target="_blank" rel="noopener">A Pretrainer's Guide to Training Data: Measuring the Effects of Data Age, Domain Coverage, Quality, & Toxicity</a></li>
        </ul>
      </td>
    </tr>
    <tr>
      <td class="event">Presentation 2</td>
      <td>MM/DD</td>
      <td>Student paper presentations.<br><a href="#" aria-label="Presentation slides">[Slides]</a></td>
      <td>
        <p>Presentation paper: [link]</p>
      </td>
    </tr>
    <tr>
      <td class="event">Lecture 3</td>
      <td>MM/DD</td>
      <td>Constructing pre-training data smartly.<br><a href="#" aria-label="Lecture 1 slides">[Slides]</a></td>
      <td>
        <p>Readings:</p>
        <ul>
          <li><a href="https://allenai.org/blog/datadecide" target="_blank" rel="noopener">DataDecide: How to predict best pretraining data with small experiments</a></li>
          <li><a href="https://arxiv.org/pdf/2502.10341" target="_blank" rel="noopener">Organize the Web: Constructing Domains Enhances Pre-Training Data Curation</a></li>
          <li><a href="https://arxiv.org/abs/2406.11794" target="_blank" rel="noopener">DataComp-LM: In search of the next generation of training sets for language models</a></li>
        </ul>
      </td>
    </tr>
    <tr>
      <td class="event">Presentation 3</td>
      <td>MM/DD</td>
      <td>Student paper presentations.<br><a href="#" aria-label="Presentation slides">[Slides]</a></td>
      <td>
        <p>Presentation paper: [link]</p>
      </td>
    </tr>
    <tr>
      <td class="event">Lecture 4</td>
      <td>MM/DD</td>
      <td>Model memorization.<br><a href="#" aria-label="Lecture 1 slides">[Slides]</a></td>
      <td>
        <p>Readings:</p>
        <ul>
          <li><a href="https://arxiv.org/abs/2407.14985" target="_blank" rel="noopener">Generalization v.s. Memorization: Tracing Language Models' Capabilities Back to Pretraining Data</a></li>
          <li><a href="https://arxiv.org/abs/2107.06499" target="_blank" rel="noopener">Deduplicating Training Data Makes Language Models Better</a></li>
        </ul>
      </td>
    </tr>
    <tr>
      <td class="event">Presentation 4</td>
      <td>MM/DD</td>
      <td>Student paper presentations.<br><a href="#" aria-label="Presentation slides">[Slides]</a></td>
      <td>
        <p>Presentation paper: [link]</p>
      </td>
    </tr>
    <tr>
      <td class="event">Lecture 5</td>
      <td>MM/DD</td>
      <td>Legal considerations and copyright issues.<br><a href="#" aria-label="Lecture 1 slides">[Slides]</a></td>
      <td>
        <p>Readings:</p>
        <ul>
          <li><a href="https://arxiv.org/abs/2311.17035" target="_blank" rel="noopener">Scalable Extraction of Training Data from (Production) Language Models</a></li>
          <li><a href="https://arxiv.org/pdf/2404.12590" target="_blank" rel="noopener">The Files are in the Computer: On Copyright, Memorization, and Generative AI</a></li>
          <li><a href="https://www.science.org/doi/10.1126/science.adi0656" target="_blank" rel="noopener">Generative AI meets copyright</a></li>
          <li><a href="https://www.bensobel.org/files/articles/Sobel_Elements-of-Style_38-HarvJLTech-49.pdf" target="_blank" rel="noopener">Elements of Style: Copyright, Similarity, and Generative AI</a></li>
        </ul>
      </td>
    </tr>
    <tr>
      <td class="event">Presentation 5</td>
      <td>MM/DD</td>
      <td>Student paper presentations.<br><a href="#" aria-label="Presentation slides">[Slides]</a></td>
      <td>
        <p>Presentation paper: [link]</p>
      </td>
    </tr>
    <tr>
      <td class="event">Lecture 6</td>
      <td>MM/DD</td>
      <td>Training data attribution.<br><a href="#" aria-label="Lecture 1 slides">[Slides]</a></td>
      <td>
        <p>Readings:</p>
        <ul>
          <li><a href="https://arxiv.org/pdf/2410.17413" target="_blank" rel="noopener">Scalable Influence and Fact Tracing for Large Language Model Pretraining</a></li>
          <li><a href="https://arxiv.org/abs/2504.07096" target="_blank" rel="noopener">OLMoTrace: Tracing Language Model Outputs Back to Trillions of Training Tokens</a></li>
        </ul>
      </td>
    </tr>
    <tr>
      <td class="event">Presentation 6</td>
      <td>MM/DD</td>
      <td>Student paper presentations.<br><a href="#" aria-label="Presentation slides">[Slides]</a></td>
      <td>
        <p>Presentation paper: [link]</p>
      </td>
    </tr>
    <tr>
      <td class="event">Lecture 7</td>
      <td>MM/DD</td>
      <td>Mid-training.<br><a href="#" aria-label="Lecture 1 slides">[Slides]</a></td>
      <td>
        <p>Readings:</p>
        <ul>
          <li><a href="https://arxiv.org/pdf/2501.00656" target="_blank" rel="noopener">2 OLMo 2 Furious</a></li>
        </ul>
      </td>
    </tr>
    <tr>
      <td class="event">Presentation 7</td>
      <td>MM/DD</td>
      <td>Student paper presentations.<br><a href="#" aria-label="Presentation slides">[Slides]</a></td>
      <td>
        <p>Presentation paper: [link]</p>
      </td>
    </tr>
    <tr class="section-row">
      <td colspan="4">Part 2: Post-training (TBD)</td>
    </tr>
  </tbody>
</table>

<br>
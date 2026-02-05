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
  .schedule-table .deadline-row td {
    background: rgba(0, 0, 0, 0.05);
    font-weight: 700;
    text-align: center;
    padding: 0.75rem;
  }
  html[data-theme="dark"] .schedule-table .deadline-row td {
    background: rgba(255, 255, 255, 0.06);
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
      <td class="event">Intro Class</td>
      <td>01/27</td>
      <td>Logistics and Explanation of course<br><a href="https://docs.google.com/presentation/d/1SC05Hwx4C_Zq7n5LibkMWhrUYubFFJXBo6OITzHpFNY/edit?usp=sharing" aria-label="Intro slides">[Slides]</a></td>
      <td></td>
    </tr>
    <tr>
      <td class="event">Lecture 1</td>
      <td>01/29</td>
      <td>Intro: transformers and autoregressive language models<br><a href="https://docs.google.com/presentation/d/1pCfH3aFLPYRKeqEOgLFVVnAGGD2w6RYmPNzLk2Le2KA/edit?usp=sharing" aria-label="Lecture 1 slides">[Slides]</a></td>
      <td>
        <p>Readings:</p>
        <ul>
          <li><a href="https://arxiv.org/abs/1706.03762" target="_blank" rel="noopener">Attention Is All You Need</a></li>
          <li><a href="https://jalammar.github.io/illustrated-transformer/" target="_blank" rel="noopener">The Illustrated Transformer</a></li>
          <li><a href="https://proceedings.mlr.press/v162/wang22u/wang22u.pdf" target="_blank" rel="noopener">What Language Model Architecture and Pretraining Objective Work Best for Zero-Shot Generalization?</a></li>
        </ul>
      </td>
    </tr>
    <tr class="section-row">
      <td colspan="4">Part 1: Pre-training</td>
    </tr>
    <tr>
      <td class="event">Lecture 2</td>
      <td>02/03</td>
      <td>What's the purpose of pre-training? What's in the pre-training dataset?<br><a href="https://docs.google.com/presentation/d/1qkzzx_4263g9M8CPmX-C157inQSkDfpFZD98JTsaSjU/edit?usp=sharing" aria-label="Lecture 2 slides">[Slides]</a></td>
      <td>
        <p>Readings:</p>
        <ul>
          <li><a href="https://arxiv.org/pdf/2310.20707" target="_blank" rel="noopener">What's In My Big Data?</a></li>
          <li><a href="https://arxiv.org/abs/2305.13169" target="_blank" rel="noopener">A Pretrainer's Guide to Training Data: Measuring the Effects of Data Age, Domain Coverage, Quality, & Toxicity</a></li>
        </ul>
      </td>
    </tr>
    <tr>
      <td class="event">Presentation 1</td>
      <td>02/05</td>
      <td>Student paper presentations<br></td>
      <td></td>
    </tr>
    <tr>
      <td class="event">Lecture 3</td>
      <td>02/10</td>
      <td>Constructing pre-training data smartly<br><a href="#" aria-label="Lecture 1 slides">[Slides]</a></td>
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
      <td class="event">Presentation 2</td>
      <td>02/12</td>
      <td>Student paper presentations<br></td>
      <td></td>
    </tr>
    <tr>
      <td class="event">Lecture 4</td>
      <td>02/17</td>
      <td>Model memorization<br><a href="#" aria-label="Lecture 1 slides">[Slides]</a></td>
      <td>
        <p>Readings:</p>
        <ul>
          <li><a href="https://arxiv.org/abs/2407.14985" target="_blank" rel="noopener">Generalization v.s. Memorization: Tracing Language Models' Capabilities Back to Pretraining Data</a></li>
          <li><a href="https://arxiv.org/abs/2107.06499" target="_blank" rel="noopener">Deduplicating Training Data Makes Language Models Better</a></li>
        </ul>
      </td>
    </tr>
    <tr>
      <td class="event">Presentation 3</td>
      <td>02/19</td>
      <td>Student paper presentations<br></td>
      <td></td>
    </tr>
    <tr>
      <td class="event">Lecture 5</td>
      <td>02/24</td>
      <td>Training data attribution<br><a href="#" aria-label="Lecture 1 slides">[Slides]</a></td>
      <td>
        <p>Readings:</p>
        <ul>
          <li><a href="https://arxiv.org/pdf/2410.17413" target="_blank" rel="noopener">Scalable Influence and Fact Tracing for Large Language Model Pretraining</a></li>
          <li><a href="https://arxiv.org/abs/2504.07096" target="_blank" rel="noopener">OLMoTrace: Tracing Language Model Outputs Back to Trillions of Training Tokens</a></li>
        </ul>
      </td>
    </tr>
    <tr>
      <td class="event">Presentation 4</td>
      <td>02/26</td>
      <td>Student paper presentations<br></td>
      <td></td>
    </tr>
    <tr class="deadline-row">
      <td colspan="4">02/26: Two-page Project Proposal Due</td>
    </tr>
    <tr>
      <td class="event">Lecture 6</td>
      <td>03/03</td>
      <td>Mid-training<br><a href="#" aria-label="Lecture 1 slides">[Slides]</a></td>
      <td>
        <p>Readings:</p>
        <ul>
          <li><a href="https://arxiv.org/pdf/2501.00656" target="_blank" rel="noopener">2 OLMo 2 Furious</a></li>
          <li><a href="https://arxiv.org/abs/2510.14865" target="_blank" rel="noopener">Midtraining Bridges Pretraining and Posttraining Distributions</a></li>
        </ul>
      </td>
    </tr>
    <tr>
      <td class="event">Presentation 5</td>
      <td>03/05</td>
      <td>Student paper presentations<br></td>
      <td></td>
    </tr>
    <tr class="section-row">
      <td colspan="4">Post-training</td>
    </tr>
    <tr>
      <td class="event">Lecture 7</td>
      <td>03/10</td>
      <td>Supervised Finetuning / Instruction tuning<br><a href="#" aria-label="Lecture 1 slides">[Slides]</a></td>
      <td>
        <p>Readings:</p>
        <ul>
          <li><a href="https://openreview.net/forum?id=gEZrGCozdqR" target="_blank" rel="noopener">Finetuned Language Models are Zero-Shot Learners</a></li>
          <li><a href="https://arxiv.org/pdf/2210.11416" target="_blank" rel="noopener">Scaling Instruction-Finetuned Language Models</a></li>
        </ul>
      </td>
    </tr>
    <tr>
      <td class="event">Presentation 6</td>
      <td>03/12</td>
      <td>Student paper presentations<br></td>
      <td></td>
    </tr>
    <tr>
      <td class="event">No class</td>
      <td>03/17</td>
      <td>No class (spring break)</td>
      <td></td>
    </tr>
    <tr>
      <td class="event">No class</td>
      <td>03/19</td>
      <td>No class (spring break)</td>
      <td></td>
    </tr>
    <tr>
      <td class="event">Lecture 8</td>
      <td>03/24</td>
      <td>Alignment/RLHF<br><a href="#" aria-label="Lecture 1 slides">[Slides]</a></td>
      <td>
        <p>Readings:</p>
        <ul>
          <li><a href="https://arxiv.org/abs/2203.02155" target="_blank" rel="noopener">Training Language Models to Follow Instructions with Human Feedback (InstructGPT)</a></li>
          <li><a href="https://arxiv.org/abs/2212.08073" target="_blank" rel="noopener">Constitutional AI: Harmlessness from AI Feedback</a></li>
          <li><a href="https://arxiv.org/abs/2305.18290" target="_blank" rel="noopener">Direct Preference Optimization: Your Language Model is Secretly a Reward Model</a></li>
        </ul>
      </td>
    </tr>
    <tr class="deadline-row">
      <td colspan="4">03/24: Midterm Report Due</td>
    </tr>
    <tr>
      <td class="event">Presentation 7</td>
      <td>03/26</td>
      <td>Student paper presentations<br></td>
      <td></td>
    </tr>
    <tr>
      <td class="event">Lecture 9</td>
      <td>03/31</td>
      <td>Reasoning and RLVR<br><a href="#" aria-label="Lecture 1 slides">[Slides]</a></td>
      <td>
        <p>Readings:</p>
        <ul>
          <li><a href="https://arxiv.org/pdf/2501.12948" target="_blank" rel="noopener">DeepSeek-R1: Incentivizing Reasoning Capability in LLMs via Reinforcement Learning</a></li>
          <li><a href="https://arxiv.org/abs/2411.15124" target="_blank" rel="noopener">Tulu 3: Pushing Frontiers in Open Language Model Post-Training</a></li>
        </ul>
      </td>
    </tr>
    <tr>
      <td class="event">Presentation 8</td>
      <td>04/02</td>
      <td>Student paper presentations<br></td>
      <td></td>
    </tr>
    <tr class="section-row">
      <td colspan="4">Applications</td>
    </tr>
    <tr>
      <td class="event">Lecture 10</td>
      <td>04/07</td>
      <td>Legal considerations and copyright issues<br><a href="#" aria-label="Lecture 1 slides">[Slides]</a></td>
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
      <td class="event">Presentation 9</td>
      <td>04/09</td>
      <td>Student paper presentations<br></td>
      <td></td>
    </tr>
    <tr>
      <td class="event">Lecture 11</td>
      <td>04/14</td>
      <td>Idiosyncracies in AI generated outputs<br><a href="#" aria-label="Lecture 1 slides">[Slides]</a></td>
      <td>
        <p>Readings:</p>
        <ul>
          <li><a href="https://arxiv.org/abs/2409.14509" target="_blank" rel="noopener">Can AI writing be salvaged? Mitigating Idiosyncrasies and Improving Human-AI Alignment in the Writing Process through Edits</a></li>
          <li><a href="https://arxiv.org/abs/2501.15654" target="_blank" rel="noopener">People who frequently use ChatGPT for writing tasks are accurate and robust detectors of AI-generated text</a></li>
          <li><a href="https://www.science.org/doi/10.1126/sciadv.adn5290" target="_blank" rel="noopener">Generative AI enhances individual creativity but reduces the collective diversity of novel content</a></li>
        </ul>
      </td>
    </tr>
    <tr>
      <td class="event">Presentation 10</td>
      <td>04/16</td>
      <td>Student paper presentations<br></td>
      <td></td>
    </tr>
    <tr>
      <td class="event">Lecture 12</td>
      <td>04/21</td>
      <td>Guest lecture from Niranjan Balasubramanian<br><a href="#" aria-label="Lecture 12 slides">[Slides]</a></td>
      <td>
        <p>Readings:</p>
        <ul>
          <li><a href="https://arxiv.org/abs/2412.14161" target="_blank" rel="noopener">TheAgentCompany: Benchmarking LLM Agents on Consequential Real World Tasks</a></li>
          <li><a href="https://arxiv.org/abs/2307.13854" target="_blank" rel="noopener">WebArena: A Realistic Web Environment for Building Autonomous Agents</a></li>
        </ul>
      </td>
    </tr>
    <tr>
      <td class="event">Presentation 11</td>
      <td>04/23</td>
      <td>Student paper presentations<br></td>
      <td></td>
    </tr>
    <tr>
      <td class="event">Lecture 13</td>
      <td>04/28</td>
      <td>Impact of AI on mental health and well-being<br><a href="#" aria-label="Lecture 13 slides">[Slides]</a></td>
      <td>
        <p>Readings:</p>
        <ul>
          <li><a href="https://arxiv.org/abs/2506.12605" target="_blank" rel="noopener">The Rise of AI Companions: How Human-Chatbot Relationships Influence Well-Being</a></li>
          <li><a href="https://arxiv.org/abs/2509.11391" target="_blank" rel="noopener">"My Boyfriend is AI": A Computational Analysis of Human-AI Companionship in Reddit's AI Community</a></li>
        </ul>
      </td>
    </tr>
    <tr>
      <td class="event">Presentation 12</td>
      <td>04/30</td>
      <td>Student paper presentations<br></td>
      <td></td>
    </tr>
    <tr>
      <td class="event">Lecture 14</td>
      <td>05/05</td>
      <td>TBA<br><a href="#" aria-label="Lecture 14 slides">[Slides]</a></td>
      <td>
        <p>Readings:</p>
        <ul>
          <li>TBA</li>
        </ul>
      </td>
    </tr>
    <tr class="deadline-row">
      <td colspan="4">05/05: Final Report Due</td>
    </tr>
    <tr>
      <td class="event">Presentation 13</td>
      <td>05/07</td>
      <td>Student paper presentations<br></td>
      <td></td>
    </tr>
  </tbody>
</table>

<br>

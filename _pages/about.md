---
layout: page
title:        # leave blank so nothing renders
permalink: /
description:
_styles: |
  .post-header { display: none; }         /* hide the default title block */
  .course-hero {
    display: flex;
    align-items: center;
    justify-content: flex-start;
    gap: 1rem;
    padding: 1rem 0 1rem;
  }
  .course-hero img { height: 80px; width: auto; }
  .course-hero .text { display: flex; flex-direction: column; gap: 0.25rem; align-items: flex-start; }
  .course-hero .meta { font-size: 1.05rem; color: var(--global-text-color); text-align: left; }
  .course-hero .title {
    font-size: 2.8rem;
    font-family: "Inter", "Helvetica Neue", Arial, sans-serif;
    font-weight: 700;
    line-height: 1.2;
  }
  .course-hero .title .hcai {
    font-family: "Playfair Display", "Times New Roman", serif;
    font-weight: 600;
    letter-spacing: 0.03em;
  }
  .prereq-label {
    font-weight: 700;
  }
  .staff-section {
    margin-top: 1.5rem;
  }
  .staff-grid {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(260px, 1fr));
    gap: 1rem;
    margin-top: 1rem;
  }
  .staff-card {
    display: grid;
    grid-template-columns: 80px 1fr;
    gap: 1.25rem;
    align-items: center;
    padding: 0.75rem;
    border: 1px solid var(--global-divider-color);
    border-radius: 8px;
    background: var(--global-card-bg-color);
  }
  .staff-photo {
    width: 90px;
    height: 90px;
    border-radius: 8px;
    object-fit: cover;
    background: #eee;
  }
  .staff-card h3 {
    margin: 0 0 0.1rem;
    font-size: 1.1rem;
  }
  .staff-meta {
    margin: 0.1rem 0;
    font-size: 0.95rem;
    color: var(--global-text-color);
  }
  .staff-meta strong {
    font-weight: 700;
  }
  .logistics {
    margin-top: 1rem;
  }
  .logistics .label {
    font-weight: 700;
    margin-bottom: 0.15rem;
  }
  .logistics ul {
    margin-top: 0.25rem;
    margin-bottom: 0;
    padding-left: 1.2rem;
  }
  @media (max-width: 576px) {
    .course-hero { flex-direction: column; text-align: left; padding: 2.75rem 0 2.25rem; align-items: flex-start; }
    .course-hero img { height: 50px; }
    .course-hero .text { align-items: flex-start; }
    .course-hero .title { font-size: 2.3rem; }
    .course-hero .meta { font-size: 1.1rem; }
  }
---

<div class="course-hero">
  <img src="{{ '/assets/img/sbu_logo.png' | relative_url }}" alt="Stony Brook University">
  <div class="text">
    <div class="title"><span class="hcai">H</span>uman-<span class="hcai">C</span>entered <span class="hcai">AI</span></div>
    <div class="meta">CSE 590 • Spring 2026</div>
  </div>
</div>

<!--- add some space below the course hero -->
<br>

<!--- add intro text below -->
<p>In this graduate-level course, we will learn how large language models are trained, evaluated, and adapted from a human-centered perspective. We will begin with an introduction to the transformer architecture and autoregressive language modeling. The first half of the course will focus on pre-training, with an emphasis on training data selection, model memorization, mid-training, and potential copyright issues. In the second half, we will explore post-training techniques and applications. This course will consist of lectures, readings, discussions, and student presentations on selected papers, along with a midterm exam and a final project.</p>

<p><span class="prereq-label">Prerequisites:</span> Knowledge of LLMs. Have taken NLP or AI.</p>

<div class="logistics">
  <p class="label">Logistics:</p>
  <ul>
    <li>Lectures: TBD</li>
    <li>Location: NCS 120</li>
    <li>Device Policy: Use of Laptop during class is not allowed. Please engage with lectures. Using Ipad for taking notes is fine. If you must need laptop or special accomodation please email the instructor.</li>
  </ul>
</div>

<!--- add instructor information below -->
<div class="staff-section">
  <!-- <h2>Instructional Staff</h2> -->
  <div class="staff-grid">
    <div class="staff-card">
      <img class="staff-photo" src="{{ '/assets/img/tuhin.jpg' | relative_url }}" alt="Instructor photo">
      <div>
        <h3>Tuhin Chakrabarty</h3>
        <p class="staff-meta"><strong>Email:</strong> <a href="mailto:tchakrabarty@cs.stonybrook.edu">tchakrabarty@cs.stonybrook.edu</a></p>
        <p class="staff-meta"><strong>Office hours:</strong> TBD</p>
        <p class="staff-meta"><strong>Location:</strong> TBD</p>
      </div>
    </div>
    <div class="staff-card">
      <img class="staff-photo" src="{{ '/assets/img/person.png' | relative_url }}" alt="TA photo">
      <div>
        <h3>TA</h3>
        <p class="staff-meta"><strong>Email:</strong> <a href="mailto:ta@stonybrook.edu">ta@stonybrook.edu</a></p>
        <p class="staff-meta"><strong>Office hours:</strong> TBD</p>
        <p class="staff-meta"><strong>Location:</strong> TBD</p>
      </div>
    </div>
  </div>
</div>
<br>

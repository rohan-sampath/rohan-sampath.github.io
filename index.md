---
layout: default
title: Rohan Sampath | Personal Webpage
---

<h1 style="font-size: 2.5em; font-weight: bold; margin-bottom: 0.2em;">Rohan Sampath</h1>
<p style="font-size: 1.2em; margin-top: 0;">Builder of AI Products | Entrepreneur</p>
<p><a href="https://www.copilotup.com" target="_blank">Former Co-founder and CEO of Copilot</a></p>

<p>
  <a href="https://github.com/rohansampath" target="_blank"><img src="https://cdn.jsdelivr.net/npm/simple-icons@v7/icons/github.svg" alt="GitHub" style="width:24px; margin-right:10px;"></a>
  <a href="https://www.linkedin.com/in/rohansampath" target="_blank"><img src="https://cdn.jsdelivr.net/npm/simple-icons@v7/icons/linkedin.svg" alt="LinkedIn" style="width:24px; margin-right:10px;"></a>
  <a href="https://twitter.com/rohansampath" target="_blank"><img src="https://cdn.jsdelivr.net/npm/simple-icons@v7/icons/twitter.svg" alt="Twitter" style="width:24px;"></a>
</p>

<hr />

<div>
  <button onclick="showTab('bio')">BIO</button>
  <button onclick="showTab('apps')">AI APPLICATIONS</button>
</div>

<div id="bio" class="tab-content">
  <p>I like building AI Applications. I co-founded and was CEO of <a href="https://www.copilotup.com" target="_blank">Copilot</a>, where we helped sales teams spot risk in their sales deals by fine-tuning custom risk models on their CRM and conversational data. In that capacity, I
    - Co-built the early product
    - Led a team that fine-tuned models and built an RAG system for over 20 customers, including Fortune 100 companies such as IBM
    - Hired and amanged a team of 10 engineers 
    - Raised over $3M in venture capital funding, and I led a team of 10 engineers along with several sales and customer success representatives.
  </p>

  <p>I've worked on several open-source projects in topics such as: AI Agentic software, OCR models, model deployment to edge & mobile devices, distillation and model evaluation. My open-source AI applications can be found <a href="#apps">here</a>.</p>

  <p>Previously, I did a Master's in Computer Science at Stanford University, focused on Natural Language Processing and Understanding. I worked closely with Chris Manning and was a teaching assistant for two of his classes - CS 224N (Natural Language Processing with Deep Learning) and CS276 (Information Retrieval and Web Search).</p>

  <p>Before that, I was a consultant at McKinsey & Company, where I worked with several tech companies on their innovation strategy. I also have a B.A. in Economics and an M.S. in Management Science and Engineering, also from Stanford University.</p>
</div>

<div id="apps" class="tab-content" style="display:none;">
  <p>Coming soon: A full list of my AI projects with links, objectives, technical goals, and GitHub repos.</p>
</div>

<script>
  function showTab(tabName) {
    const tabs = document.getElementsByClassName('tab-content');
    for (const tab of tabs) {
      tab.style.display = 'none';
    }
    document.getElementById(tabName).style.display = 'block';
  }
</script>

<style>
  button {
    margin: 10px 10px 0 0;
    padding: 8px 16px;
    font-size: 1em;
    cursor: pointer;
    border: 1px solid #ccc;
    background: white;
    border-radius: 5px;
  }
  button:hover {
    background-color: #f2f2f2;
  }
</style>

---
permalink: /
title: "Kasra Mirnobahar"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

**Biography**
Hi, This is Kasra and idk what to write herer




<section>
  <h2>Education</h2>

  <div class="edu-list">

    <div class="edu-item">
      <span class="edu-cap">🎓</span>
      <div>
        <div class="edu-degree">MSc Behavioural Sciences, 2025</div>
        <div class="edu-school">University of Glasgow</div>
      </div>
    </div>

    <div class="edu-item">
      <span class="edu-cap">🎓</span>
      <div>
        <div class="edu-degree">BSc Psychology, 2023</div>
        <div class="edu-school">University of Social Welfare & Rehabilitation Sciences</div>
      </div>
    </div>

  </div>
</section>

<style>
.edu-list { display: flex; flex-direction: column; gap: 1.2rem; margin-top: 1rem; }

.edu-item { display: flex; align-items: flex-start; gap: 0.8rem; }

.edu-cap { font-size: 1.4rem; margin-top: 2px; }

.edu-degree { font-weight: 600; font-size: 1rem; }

.edu-school { color: #eee; font-size: 0.9rem; margin-top: 2px; }
</style>


<section>
  <h2>Research Interests</h2>

  <div class="research-paras">
    <p>My main research interest is understanding the underlying mechanisms of specific behaviours, how they influence mental health, and how they can be addressed through effective interventions. I am particularly drawn to research with clear real-world and societal impact.</p>

    <p>Much of my recent work has focused on the effects of <strong>social media on mental health, behaviour, and cognition</strong> — including designing behavioural experiments to investigate how uncertainty drives checking behaviour in digital environments.</p>

    <p>I am also interested in <strong>neuroscience</strong>, particularly decision-making, reward processing, and dopaminergic systems. Over the past year I have gained experience with both <strong>EEG and fMRI</strong> methods.</p>

    <p>More broadly, I aim to work at the intersection of social media, decision-making, and behavioural science — using insights from cognitive neuroscience to inform public policy and interventions for digital mental health.</p>
  </div>

  <div class="research-tags">
    <span>🧠 Social Media & Mental Health</span>
    <span>⚡ Decision-Making</span>
    <span>🔬 Behavioural Science</span>
    <span>🌍 Public Policy & Interventions</span>
  </div>

</section>

<style>
.research-tags {
  display: flex;
  flex-wrap: wrap;
  gap: 0.5rem;
  margin: 1rem 0 1.4rem;
}

.research-tags span {
  background: #f0f4ff;
  color: #2a5bd7;
  border: 1px solid #c8d8f8;
  border-radius: 20px;
  padding: 4px 12px;
  font-size: 0.82rem;
  font-weight: 500;
  opacity: 0.6;
}

.research-paras p {
  font-size: 0.95rem;
  line-height: 1.75;
  color: #eee;
  margin-bottom: 0.8rem;
}
</style>

**Markdown generator**

The repository includes [a set of Jupyter notebooks](https://github.com/academicpages/academicpages.github.io/tree/master/markdown_generator
) that converts a CSV containing structured data about talks or presentations into individual Markdown files that will be properly formatted for the Academic Pages template. The sample CSVs in that directory are the ones I used to create my own personal website at stuartgeiger.com. My usual workflow is that I keep a spreadsheet of my publications and talks, then run the code in these notebooks to generate the Markdown files, then commit and push them to the GitHub repository.

How to edit your site's GitHub repository
------
Many people use a git client to create files on their local computer and then push them to GitHub's servers. If you are not familiar with git, you can directly edit these configuration and Markdown files directly in the github.com interface. Navigate to a file (like [this one](https://github.com/academicpages/academicpages.github.io/blob/master/_talks/2012-03-01-talk-1.md) and click the pencil icon in the top right of the content preview (to the right of the "Raw | Blame | History" buttons). You can delete a file by clicking the trashcan icon to the right of the pencil icon. You can also create new files or upload files by navigating to a directory and clicking the "Create new file" or "Upload files" buttons. 

Example: editing a Markdown file for a talk
![Editing a Markdown file for a talk](/images/editing-talk.png)

For more info
------
More info about configuring Academic Pages can be found in [the guide](https://academicpages.github.io/markdown/), the [growing wiki](https://github.com/academicpages/academicpages.github.io/wiki), and you can always [ask a question on GitHub](https://github.com/academicpages/academicpages.github.io/discussions). The [guides for the Minimal Mistakes theme](https://mmistakes.github.io/minimal-mistakes/docs/configuration/) (which this theme was forked from) might also be helpful.

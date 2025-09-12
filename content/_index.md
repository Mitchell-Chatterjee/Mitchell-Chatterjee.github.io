---
# Leave the homepage title empty to use the site title
title: ""
date: 2022-10-24
type: landing

design:
  # Default section spacing
  spacing: "6rem"

sections:
  - block: resume-biography-3
    content:
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
      text: "Machine Learning Engineer experienced in building real-time, production-grade NLP, retrieval, and agentic systems. Skilled in foundation model development, from data pipelines to LLM orchestration and evaluation. Adept at bridging research and engineering to deliver scalable, high-impact AI solutions."
      # Show a call-to-action button under your biography? (optional)
      button:
        text: Download CV
        url: uploads/resume.pdf
    design:
      css_class: light-theme hero-background
      background:
        color: white
        image:
          # Add your image background to `assets/media/`.
          filename: hero-background.jpg
          filters:
            brightness: 1.0
          size: cover
          position: center
          parallax: false
  - block: markdown
    content:
      title: '📚 Background'
      subtitle: ''
      text: |-
        I'm a Machine Learning Engineer who bridges foundational model research and production ML engineering. My Master's research applied state-of-the-art NLP techniques to medical datasets, and in industry I design and deploy robust LLM-driven retrieval and agent systems, build scalable data pipelines, and implement production model serving and evaluation frameworks.

        I enjoy collaboration across research and engineering — if you're working on applied ML, model infrastructure, or evaluation at scale, let's talk.
    design:
      columns: '1'
  - block: markdown
    content:
      title: '🚀 Technical Strengths'
      subtitle: ''
      text: |-
        <div class="skills-grid">
          <div class="skill-category">
            <h4>🤖 Machine Learning</h4>
            <div class="skill-tags">
              <span class="skill-tag">Transformers & LLMs</span>
              <span class="skill-tag">Natural Language Processing</span>
              <span class="skill-tag">Time-Series Analysis</span>
              <span class="skill-tag">Self-Supervised Learning</span>
              <span class="skill-tag">Parameter Efficient Fine-tuning</span>
              <span class="skill-tag">High Performance Computing</span>
            </div>
          </div>
          <div class="skill-category">
            <h4>💻 Engineering</h4>
            <div class="skill-tags">
              <span class="skill-tag">Python (Expert)</span>
              <span class="skill-tag">PyTorch & NumPy</span>
              <span class="skill-tag">Docker & Kubernetes</span>
              <span class="skill-tag">LangChain & Agno</span>
              <span class="skill-tag">Cloud & Big Data</span>
              <span class="skill-tag">C# & JavaScript</span>
            </div>
          </div>
        </div>
    design:
      columns: '1'
      css_class: 'skills-section'
  - block: collection
    id: papers
    content:
      title: Featured Work
      filters:
        folders:
          - publication
        featured_only: true
    design:
      view: article-grid
      columns: 1
  # - block: collection
  #   content:
  #     title: Recent Publications
  #     text: ""
  #     filters:
  #       folders:
  #         - publication
  #       exclude_featured: false
  #   design:
  #     view: citation
  # - block: collection
  #   id: talks
  #   content:
  #     title: Recent & Upcoming Talks
  #     filters:
  #       folders:
  #         - event
  #   design:
  #     view: article-grid
  #     columns: 1
  # - block: collection
  #   id: news
  #   content:
  #     title: Recent News
  #     subtitle: ''
  #     text: ''
  #     # Page type to display. E.g. post, talk, publication...
  #     page_type: post
  #     # Choose how many pages you would like to display (0 = all pages)
  #     count: 5
  #     # Filter on criteria
  #     filters:
  #       author: ""
  #       category: ""
  #       tag: ""
  #       exclude_featured: false
  #       exclude_future: false
  #       exclude_past: false
  #       publication_type: ""
  #     # Choose how many pages you would like to offset by
  #     offset: 0
  #     # Page order: descending (desc) or ascending (asc) date.
  #     order: desc
  #   design:
  #     # Choose a layout view
  #     view: date-title-summary
  #     # Reduce spacing
  #     spacing:
  #       padding: [0, 0, 0, 0]
  - block: cta-card
    content:
      title: "Let's Connect"
      text: |-
        Interested in collaborating on ML research, discussing production AI systems, or exploring opportunities? I'm always open to connecting with fellow researchers and engineers working at the intersection of AI and real-world applications.
      button:
        text: Get In Touch
        url: 'mailto:mitchell.chatterjee@gmail.com'
    design:
      card:
        css_class: "bg-gradient-primary"
        css_style: ""
---

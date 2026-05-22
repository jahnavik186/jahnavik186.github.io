---
layout: default
title: Home
---

<div class="profile-page">
  <aside class="profile-sidebar">
    <p class="eyebrow">Professional Bio</p>
    <h1>Jahnavi Kachhia</h1>
      <p class="lead">
      Global AI and machine learning leader translating research into production-scale impact
      across healthcare, consumer platforms, and safety-critical systems.
    </p>

    <img src="{{ '/assets/img/profile.jpeg' | relative_url }}" alt="Portrait of Jahnavi Kachhia" class="profile-photo" />

    <div class="info-card">
      <h3>Quick Snapshot</h3>
      <ul class="compact-list">
        <li>Global Technical Expert in AI for Healthcare and National Security</li>
        <li>Led Meta Ray-Ban AI features including Reminders and Visual Tracking</li>
        <li>{{ site.profiles.scholar_articles }} scholarly articles and {{ site.profiles.scholar_citations }} citations</li>
        <li>20+ expert judging, review, committee, and editorial roles across AI and healthcare</li>
        <li>{{ site.profiles.github_repositories }} GitHub repositories with {{ site.profiles.github_total_stars }} stars and {{ site.profiles.github_total_forks }} forks</li>
        <li>{{ site.profiles.docker_images }} Docker images with {{ site.profiles.docker_downloads }} downloads</li>
        <li>Industry media commentary in All Tech Magazine</li>
        <li>Kaggle Dataset Master ranked {{ site.profiles.kaggle_dataset_rank }} ({{ site.profiles.kaggle_dataset_percentile }})</li>
        <li>Bridging theory and real-world medical application through responsible AI</li>
      </ul>
    </div>

    <div class="info-card">
      <h3>Profiles</h3>
      <ul class="compact-list">
        <li><a href="{{ site.profiles.scholar }}">Google Scholar</a></li>
        <li><a href="{{ site.profiles.github }}">GitHub</a></li>
        <li><a href="{{ site.profiles.docker }}">Docker Hub Profile</a></li>
        <li><a href="{{ site.profiles.kaggle }}">Kaggle</a></li>
        <li><a href="{{ site.profiles.academia }}">Academia.edu</a></li>
        <li><a href="{{ site.profiles.linkedin }}">LinkedIn</a></li>
        <li><a href="{{ site.profiles.researchgate }}">ResearchGate</a></li>
        <li><a href="{{ site.profiles.orcid }}">ORCID</a></li>
        <li><a href="mailto:jahnavik186@gmail.com">jahnavik186@gmail.com</a></li>
      </ul>
    </div>

    <nav class="section-nav">
      <a href="#about">About</a>
      <a href="#research">Impact</a>
      <a href="#profiles">Profiles</a>
      <a href="#service">Review</a>
      <a href="#speaking">Engagements</a>
      <a href="#media">Commentary</a>
      <a href="#certifications">Certifications</a>
    </nav>
  </aside>

  <div class="profile-main">
    <section id="about" class="content-block">
      <h2>Professional Header &amp; Bio</h2>
      <p>
        Jahnavi Kachhia is a global AI and machine learning leader with 8+ years of experience
        building scalable, production-grade systems that serve millions of users across healthcare
        and consumer platforms. She specializes in translating advanced AI research into real-world
        impact, with expertise in generative AI, predictive systems, and end-to-end ML
        infrastructure.
      </p>
      <p>
        Her work focuses on designing reliable, explainable AI for safety-critical environments,
        including large-scale, real-time systems where performance and trust are essential. She has
        contributed to AI platforms deployed globally, operating at scale in user-facing and
        clinical contexts.
      </p>
      <p>
        Jahnavi's research includes peer-reviewed publications across IEEE and international venues,
        with {{ site.profiles.scholar_citations }} citations across domains such as biomedical AI, brain-computer interfaces, and
        applied machine learning. She is also an active open-source contributor, with projects
        achieving {{ site.profiles.github_total_stars }} GitHub stars, {{ site.profiles.github_total_forks }} GitHub forks, and {{ site.profiles.docker_downloads }} Docker downloads, reflecting strong global adoption.
      </p>
    </section>

    <section id="research" class="content-block">
      <h2>Pioneering Research &amp; Original Contributions</h2>
      <div class="stat-grid">
      <div class="stat-card">
        <strong>{{ site.profiles.scholar_articles }}</strong>
        <span>Scholarly articles</span>
      </div>
      <div class="stat-card">
        <strong>{{ site.profiles.scholar_citations }}</strong>
        <span>Scholarly citations</span>
      </div>
      <div class="stat-card">
        <strong>{{ site.profiles.github_repositories }}</strong>
        <span>GitHub repositories</span>
      </div>
      <div class="stat-card">
        <strong>{{ site.profiles.github_total_stars }}</strong>
        <span>GitHub stars</span>
      </div>
      <div class="stat-card">
        <strong>{{ site.profiles.github_total_forks }}</strong>
        <span>GitHub forks</span>
      </div>
      <div class="stat-card">
        <strong>{{ site.profiles.github_followers }}</strong>
        <span>GitHub followers</span>
      </div>
      <div class="stat-card">
        <strong>{{ site.profiles.docker_images }}</strong>
        <span>Docker images</span>
      </div>
      <div class="stat-card">
        <strong>{{ site.profiles.docker_downloads }}</strong>
        <span>Docker downloads</span>
      </div>
      <div class="stat-card">
        <strong>{{ site.profiles.kaggle_dataset_rank }}</strong>
        <span>Kaggle Dataset Master rank ({{ site.profiles.kaggle_dataset_percentile }})</span>
      </div>
      </div>
      <div class="contribution-list">
        <div class="callout contribution-item">
          <h3><strong>Meta Ray-Ban AI</strong></h3>
          <p>Pioneered AI logic for multi-modal reminders, setting a new industry standard for wearable intelligence.</p>
          <p><strong>Significance Statement:</strong> Helped translate multimodal AI from prototype concepts into consumer-facing intelligent assistance, contributing to product behavior that made contextual memory and visual tracking tangible at scale.</p>
        </div>
        <div class="callout contribution-item">
          <h3><strong>Healthcare AI: ICU Early Risk Predictor</strong></h3>
          <p>Developed an open-source framework (Dockerized) for predictive clinical risk assessment, utilized by researchers worldwide.</p>
          <p><strong>Significance Statement:</strong> Advanced reproducible healthcare AI by packaging clinical prediction workflows into accessible infrastructure that supports experimentation, validation, and downstream medical research translation.</p>
        </div>
        <div class="callout contribution-item">
          <h3><strong>Radar Signal Analysis</strong></h3>
          <p>Established novel deep learning architectures for signal deinterleaving in high-density environments.</p>
          <p><strong>Significance Statement:</strong> Extended deep learning techniques into complex signal environments where robust separation and interpretation are essential for mission-critical analysis.</p>
        </div>
      </div>
      <p><a href="{{ '/publications/' | relative_url }}">View the full publications page</a></p>
    </section>

    <section id="profiles" class="content-block">
      <h2>Professional Profiles and Public Visibility</h2>
      <ul>
        <li><a href="{{ site.profiles.scholar }}">Google Scholar</a> - citation record, publication visibility, and scholarly profile</li>
        <li><a href="{{ site.profiles.github }}">GitHub</a> - code repositories, project visibility, and technical portfolio</li>
        <li><a href="{{ site.profiles.docker }}">Docker Hub</a> - published containers and applied machine learning artifact visibility</li>
        <li><a href="{{ site.profiles.kaggle }}">Kaggle</a> - dataset visibility, competitions profile, and Dataset Master ranking</li>
        <li><a href="{{ site.profiles.academia }}">Academia.edu</a> - academic affiliation and publication visibility</li>
        <li><a href="{{ site.profiles.linkedin }}">LinkedIn</a> - professional profile, speaking visibility, and career-facing public presence</li>
        <li><a href="{{ site.profiles.researchgate }}">ResearchGate</a> - academic profile visibility and research discovery</li>
        <li><a href="{{ site.profiles.orcid }}">ORCID</a> - persistent researcher identity and scholarly record linkage</li>
      </ul>
      <div class="kv">
        <div>GitHub Stats</div><div>{{ site.profiles.github_profile_repositories }} repositories, {{ site.profiles.github_total_stars }} stars, {{ site.profiles.github_total_forks }} forks, {{ site.profiles.github_profile_followers }} followers</div>
        <div>Docker Stats</div><div>{{ site.profiles.docker_images }} images, {{ site.profiles.docker_downloads }} downloads</div>
        <div>Kaggle Stats</div><div>Dataset Master ranked {{ site.profiles.kaggle_dataset_rank }} ({{ site.profiles.kaggle_dataset_percentile }})</div>
      </div>
    </section>

    <section id="service" class="content-block">
      <h2>Global Peer Review &amp; Technical Judging</h2>
      <p class="section-subtitle">
        Dedicated to ensuring technical excellence and ethical standards in the global AI ecosystem through the rigorous evaluation of emerging research and technologies.
      </p>
      <h3>Conference Program Committees</h3>
      <ul>
        <li><strong>Expert Jury:</strong> <a href="https://2025.ijcai.org/">IJCAI 2025</a></li>
        <li><strong>Expert Jury:</strong> <a href="https://2026.ijcai.org/">IJCAI 2026</a></li>
        <li><strong>Expert Jury:</strong> <a href="https://aaai.org/conference/aaai/aaai-25/">AAAI 2025 workshops and review tracks</a></li>
        <li><a href="https://www.pakdd2026.org/program-committee">PAKDD 2026</a></li>
        <li><strong>Editor:</strong> <a href="https://journals.plos.org/plosone/">PLOS ONE</a></li>
      </ul>

      <h3>Innovation Panels</h3>
      <ul>
        <li><strong>Expert Jury:</strong> <a href="https://healthhack.mit.edu/">MIT Hacking Medicine</a></li>
        <li><strong>Expert Jury:</strong> <a href="https://eurekathon.com/">Eurekathon</a></li>
        <li><strong>Expert Jury:</strong> <a href="https://lablab.ai/event/ai-for-connectivity-hackathon">AI for Connectivity</a></li>
        <li><strong>Expert Jury:</strong> <a href="https://nexora-hacks-2026.devpost.com/">Nexora Hacks 2026</a></li>
      </ul>
      <p><a href="{{ '/service/' | relative_url }}">View the full service page</a></p>
    </section>

    <section id="speaking" class="content-block">
      <h2>Public Engagements &amp; Expert Insights</h2>
      <div class="engagement-table">
        <div class="engagement-row engagement-head">
          <div>City</div>
          <div>Session</div>
          <div>Event</div>
        </div>
        <div class="engagement-row">
          <div>Toronto</div>
          <div>Artificial Intelligence in Healthcare and Industry</div>
          <div><a href="https://www.scitechseries.com/artificial-intelligence-machine/speakers/2026">SciTech Series, August 19-20, 2026</a></div>
        </div>
        <div class="engagement-row">
          <div>London</div>
          <div>Neuroscience2026 invited speaker</div>
          <div><a href="https://neuroscience2026.researchconnects.org/#Speakers">Neuroscience2026, March 12-14, 2026</a></div>
        </div>
        <div class="engagement-row">
          <div>Prague</div>
          <div>HealthAI2026 featured session</div>
          <div><a href="https://healthai.pagesconferences.org/speakers">HealthAI2026, July 27-28, 2026</a></div>
        </div>
        <div class="engagement-row">
          <div>Madrid</div>
          <div>VACCINES2026 invited address</div>
          <div><a href="https://vaccines.researchconnects.org/">VACCINES2026, May 28-30, 2026</a></div>
        </div>
        <div class="engagement-row">
          <div>Frankfurt</div>
          <div>ISRAI2026 speaker session</div>
          <div><a href="https://robotics2026.spectrumconferences.com/">ISRAI2026, April 20-22, 2026</a></div>
        </div>
      </div>
      <div class="callout">
        <h3>AI as a Medical Co-Pilot</h3>
        <p>Invited to share insights on LLM interpretability for clinical decision support systems.</p>
      </div>
      <p><a href="{{ '/speaking/' | relative_url }}">View the full speaking page</a></p>
    </section>

    <section id="media" class="content-block">
      <h2>Media Mentions</h2>
      <h3>Industry Commentary &amp; Analysis</h3>
      <ul>
        <li><a href="https://alltechmagazine.com/ai-that-doesnt-collapse-under-pressure/">All Tech Magazine: AI That Doesnt Collapse Under Pressure</a></li>
        <li><a href="https://www.theverge.com/2024/9/25/24253712/meta-rayban-ai-features-reminders-translation-transparent-style">The Verge: Meta's Ray-Ban will now remember for you</a></li>
        <li><a href="https://gizmodo.com/the-ray-ban-meta-smart-glasses-will-now-remind-you-to-restock-the-fridge-2000502802">Gizmodo: Ray-Ban Meta Smart Glasses and reminder features</a></li>
        <li><a href="https://techcrunch.com/2024/09/25/meta-updates-ray-ban-smart-glasses-with-real-time-ai-video-reminders-and-qr-code-scanning/?guccounter=1&guce_referrer=aHR0cHM6Ly9sLndvcmtwbGFjZS5jb20v&guce_referrer_sig=AQAAAJT0VqyFgPGtwVMR2aK02q6dUTjTSNLHUeJFJUxak0gdupbaMwq7obrxzgmlKFx18IeeFyep7fApxKx7GS6yvL9S3_nHBTkIYOS3gsodbo0YhQfSGBQVjIN5gyabDAKQQWpKxPr30Q7HSqZN8tPjGh6bigIxZnM_d3ukpT7vYFLv">TechCrunch: Meta updates Ray-Ban smart glasses</a></li>
        <li><a href="https://www.usatoday.com/story/tech/2024/12/16/meta-ray-ban-smart-glasses-live-translation/77035096007/">USA Today: Meta Ray-Ban smart glasses live translation</a></li>
      </ul>
      <h3>Videos</h3>
      <ul>
        <li><a href="https://www.youtube.com/watch?v=dzLzszUNih0">YouTube: Featured AI video</a></li>
        <li><a href="https://www.youtube.com/watch?v=bgth6IBc9VQ">YouTube: Featured AI video</a></li>
      </ul>
      <p><a href="{{ '/media/' | relative_url }}">View the full media page</a></p>
    </section>

    <section id="certifications" class="content-block">
      <h2>Certifications</h2>
      <ul>
        <li><a href="https://www.coursera.org/account/accomplishments/verify/CW8B76P6MV2P?utm_medium=certificate&utm_source=link&utm_campaign=copybutton_certificate&utm_content=cert_image">Stanford Machine Learning</a></li>
        <li><a href="https://www.coursera.org/account/accomplishments/verify/RMPAXG5NBGL4?utm_source=link&utm_medium=certificate&utm_content=cert_image&utm_campaign=pdf_header_button">Getting Started with AWS Machine Learning</a></li>
        <li><a href="https://learn.nvidia.com/certificates?id=5722168cf9aa4f57b8bc6bb5fbb00c36">NVIDIA Fundamentals of Deep Learning for Computer Vision</a></li>
      </ul>
    </section>
  </div>
</div>

---
layout: page
title: Our Team
permalink: /team/
---

<div class="text-center mb-4">
  <p class="hero-subtitle">Meet the world-class researchers and practitioners behind Proaxis AI. Our team brings together leading experts from University College Dublin's acclaimed HCI research community, combining decades of academic research with practical industry experience in conversational AI.</p>
</div>

<div class="team-grid">
  {% for member in site.team %}
  <div class="team-member">
    <div class="member-photo">
      {% if member.photo %}
        <img src="{{ member.photo | relative_url }}" alt="{{ member.name }}">
      {% else %}
        👤
      {% endif %}
    </div>
    <div class="member-info">
      <h3>{{ member.name }}</h3>
      <div class="member-title">{{ member.title }}</div>
      <div class="member-bio">{{ member.bio }}</div>
    </div>
  </div>
  {% endfor %}
</div>

## Our Expertise

Our team represents one of the world's leading concentrations of expertise in conversational AI and human-computer interaction. Based at University College Dublin, home to the HCI@UCD group and the SFI ADAPT Centre, our researchers and practitioners combine:

- **Conversational AI Research**: Advanced dialogue systems, natural language understanding, and speech technology
- **Human-Computer Interaction**: User experience design, interaction design, and usability engineering  
- **Cross-Cultural Communication**: Multilingual AI systems and culturally-aware interaction design
- **Psychological Foundations**: Understanding human cognition, social dynamics, and communication patterns
- **Industry Applications**: Translating research into scalable, production-ready AI solutions

## Join Our Team

Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. We're always looking for talented researchers, developers, and designers who share our passion for advancing conversational AI.

<div class="text-center mb-4">
  <a href="/contact/" class="cta-button">Contact Us About Opportunities</a>
</div>

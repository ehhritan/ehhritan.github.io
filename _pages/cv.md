---
layout: single
title: "CV"
permalink: /cv/
author_profile: false
classes: wide
redirect_from:
  - /resume
---

<style>
  .page__title {
    display: none;
  }

  .page__content {
    padding-top: 0;
  }

  .cv-viewer {
    width: 100%;
    height: calc(100vh - 130px);
    min-height: 850px;
    border: none;
  }

  @media (max-width: 768px) {
    .cv-viewer {
      height: calc(100vh - 100px);
      min-height: 650px;
    }
  }
</style>

<iframe
  class="cv-viewer"
  src="{{ '/files/Hritan_CV.pdf#view=FitH' | relative_url }}"
  title="Emtiaz Hossain Hritan Curriculum Vitae">
</iframe>

<noscript>
  <p>
    <a href="{{ '/files/Hritan_CV.pdf' | relative_url }}">
      Download my CV
    </a>
  </p>
</noscript>

---
layout: single
title: "CV"
permalink: /cv/
author_profile: false
classes: wide
redirect_from:
  - /resume/
---

<style>
.page__title {
  display: none;
}

.page__inner-wrap,
.page__content {
  width: 100% !important;
  max-width: 100% !important;
}

.cv-container {
  width: 100%;
  max-width: 1200px;
  margin: 0 auto;
}

.cv-viewer {
  display: block;
  width: 100%;
  height: calc(100vh - 110px);
  min-height: 900px;
  border: 0;
}

.cv-download {
  margin-bottom: 0.75rem;
  text-align: right;
}

@media (max-width: 768px) {
  .cv-viewer {
    height: calc(100vh - 90px);
    min-height: 650px;
  }
}
</style>

<div class="cv-container">

<p class="cv-download">
  <a href="{{ '/files/Hritan_CV.pdf' | relative_url }}" target="_blank">
    Open or download CV
  </a>
</p>

<iframe
  class="cv-viewer"
  src="{{ '/files/Hritan_CV.pdf#view=FitH' | relative_url }}"
  title="Emtiaz Hossain Hritan Curriculum Vitae">
</iframe>

</div>

---
layout: page
permalink: /cv/
title: CV
nav: true
nav_order: 5
---

{% assign cv_url = '/assets/pdf/CV_Chuwen Zhang.pdf' | relative_url | replace: ' ', '%20' %}

See below or click <a href="{{ cv_url }}" target="_blank">CV</a>.

<object data="{{ cv_url }}" type="application/pdf" width="100%" height="1000px">
  <p>
    Unable to display the CV PDF in your browser.
    <a href="{{ cv_url }}" target="_blank">Open or download the PDF instead.</a>
  </p>
</object>

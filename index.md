---
layout: splash
author_profile: false
title:
header:
  overlay_color: "#0c1012"
  overlay_filter: "0.5"
  overlay_image: /assets/images/wago-stiftung_startseite.jpg
  wrapper: "height: 400px"
row1:
  - image_path: /assets/images/MM-16230_WAGO_Stiftung_GWA_01_2000x1125.jpg
    video:
      id: tmAZAQFCKEc
      provider: youtube
    alt: "WAGO Stiftung"
    title: "DIE WAGO STIFTUNG"
    excerpt: "Die WAGO Stiftung möchte Ideen und Potenziale finden und fördern. In Makeathons und Kolloquien vernetzen sich Nachwuchstalente und Experten in der modernen Automatisierungstechnik – um die Fachkräfte und Innovationen von morgen zu sichern und Zukunft zu gestalten."
    url: "/"
    btn_label: "Mehr erfahren"
    btn_class: "btn--primary"
row2:
  - image_path: /assets/images/MM-16230_WAGO_Stiftung_GWA_01_2000x1125.jpg
    alt: "WAGO Stiftung - Makeathon"
    title: "Makeathon"
    excerpt: "Engagiert und technikinteressiert? Dann beim Makeathon der WAGO Stiftung kreativ werden – und gemeinsam die Zukunft der Automatisierung gestalten."
    url: "makeathon"
    btn_label: "Mehr erfahren"
    btn_class: "btn--secondary"
  - image_path: /assets/images/Teaser-Kolloquium_2000x1125.jpg
    alt: "Kolloquium"
    title: "Kolloquium"
    excerpt: "Hier vernetzen sich Experten und Nachwuchstalente, um über die Zukunftstrends im Bereich Digitalisierung und Automatisierung zu sprechen und gemeinsam neue Ideen zu entwickeln."
    url: "kolloquium"
    btn_label: "Mehr erfahren"
    btn_class: "btn--secondary"
row3:
  - image_path: /assets/images/envelope_x3.svg
    alt: "Kontakt"
    title: "Fragen? Wir helfen gern!"
    excerpt: "Hast Du Fragen zur Stiftung generell oder zu einem unserer Formate? Dann melde Dich bei uns und wir beantworten diese gern."
    url: "kontakt"
    btn_label: "Mehr erfahren"
    btn_class: "btn--secondary"
---

<!-- <p>This text should appear above the recent posts.</p> -->

{% include feature_row id="row1" type="left" %}

{% include feature_row id="row2" %}

{% include feature_row id="row3" type="left" highlight="true" %}

# WAGO Stiftung News

{% include posts-recent3.html %}

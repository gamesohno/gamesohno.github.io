---
layout: post
title: First post!
image: /img/hello_world.jpeg
---

{% assign image_files = site.static_files | where: "image", true %}
{% for myimage in image_files %}
  {{ myimage.path }}
{% endfor %}
\
[markdown]({{ site.url }}/pdf/28_selected_duets_for_two_saxophones_or_oboes_intermediate_advanced.pdf)\
[markdown]({{ site.url }}/pdf/clinical_and_investigative_features_of_cardiac_pathology_congenital_heart_disease.pdf)\
[markdown]({{ site.url }}/pdf/frank_erickson_high_school_band_course_flute_texas_edition.pdf)\
[markdown]({{ site.url }}/pdf/kansas_prairie_wildflowers.pdf)\
[markdown]({{ site.url }}/pdf/las_sociedades_secretas_spanish_edition.pdf)\



This is my first post, how exciting!
image: /img/hello_world.jpeg

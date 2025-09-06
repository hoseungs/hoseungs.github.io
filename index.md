---
layout: home
title: Home
---

<style>
.profile{ display:flex; gap:24px; align-items:flex-start; margin:8px 0 0; }
.profile__photo{ width:167px; height:auto; flex:0 0 auto; display:block; border-radius:6px; }
.profile__text{ flex:1 1 0; min-width:0; }

.kv{
  display:grid;
  grid-template-columns: 72px 1fr; /* ← 라벨 폭. 간격 넓히거나 줄이려면 숫자만 조정 */
  column-gap:12px; row-gap:4px; margin:10px 0 0;
}
.kv dt{ margin:0; font-weight:600; }
.kv dd{ margin:0; }

@media (max-width:640px){
  .profile{ flex-direction:column; }
}
</style>

<div class="profile">
  <img class="profile__photo" src="https://hoseungs.github.io/img/profile.png" alt="Hoseung Song">

  <div class="profile__text" markdown="1">
  Hoseung Song

  Assistant Professor

  [Department of Industrial and Systems Engineering](http://ise.kaist.ac.kr)  
  [Graduate School of Data Science](https://gsds.kaist.ac.kr/eng)  
  [KAIST](https://www.kaist.ac.kr/en/) (Korea Advanced Institute of Science & Technology)

  <dl class="kv">
    <dt><small>Email</small></dt><dd><small>hoseung [at] kaist.ac.kr</small></dd>
    <dt><small>Tel</small></dt><dd><small>82-42-350-3117</small></dd>
    <dt><small>Office</small></dt><dd><small>4103 E2-2, 291 Daehak-ro, Daejeon 34141, Republic of Korea</small></dd>
  </dl>
  </div>
</div>

<hr>

Research Interests
* Statistical data science/decision making
* Change-point analysis (Anomaly detection)
* Two/Multi-sample (A/B) tests, Association tests
* Spatial clustering
* Biomedical and healthcare sciences

<br>

<center>
<a href="mailto:hoseung@kaist.ac.kr" target="_blank" title="Email">
  <img alt="Email" src="https://hoseungs.github.io/assets/css/email.png" width="20" height="20" />
</a> &ensp;
<a href="https://scholar.google.com/citations?hl=en&user=kTC7m0wAAAAJ&view_op=list_works&sortby=pubdate" target="_blank" title="Google Scholar">
  <img alt="Google Scholar" src="https://hoseungs.github.io/assets/css/gs.png" width="20" height="20" />
</a> &ensp;
<a href="https://www.linkedin.com/in/songhs/" target="_blank" title="Linkedin">
  <img alt="Linkedin" src="https://hoseungs.github.io/assets/css/linkedin.png" width="20" height="20" />
</a>
</center>

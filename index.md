---
layout: home
title: Home
---

<style>
/* 기존 profile 스타일은 그대로 두고, 바깥 래퍼만 추가 */
.profile-wrap{
  max-width: 860px;  /* 본문 폭에 맞춰 720~920px 사이로 취향대로 조절 */
  margin: 0 auto;    /* 가운데 정렬 */
  padding: 0 16px;   /* 좌우 여백(살짝 안쪽으로) */
}

/* 참고: 이미 넣어둔 것 */
.profile{ display:flex; gap:24px; align-items:flex-start; margin:8px 0 0; }
.profile__photo{ width:167px; height:auto; display:block; border-radius:6px; }
.profile__text{ flex:1 1 0; min-width:0; }
@media (max-width:640px){ .profile{ flex-direction:column; } }
</style>

<div class="profile-wrap">
  <div class="profile">
    <img class="profile__photo" src="https://hoseungs.github.io/img/profile.png" alt="Hoseung Song">
    <div class="profile__text" markdown="1">
      ## Hoseung Song
      Assistant Professor  
      [Department of Industrial and Systems Engineering](http://ise.kaist.ac.kr)  
      [Graduate School of Data Science](https://gsds.kaist.ac.kr/eng)  
      [KAIST](https://www.kaist.ac.kr/en/) (Korea Advanced Institute of Science & Technology)

      <dl class="kv">
        <dt>Email</dt><dd>hoseung [at] kaist.ac.kr</dd>
        <dt>Tel</dt><dd>82-42-350-3117</dd>
        <dt>Office</dt><dd>4103 E2-2, 291 Daehak-ro, Daejeon 34141, Republic of Korea</dd>
      </dl>
    </div>
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

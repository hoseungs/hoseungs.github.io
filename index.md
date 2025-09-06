---
layout: home
title: Home
---

<style>
/* 상단 프로필: 사진 왼쪽 + 텍스트 오른쪽 */
.profile{ display:flex; gap:24px; align-items:flex-start; margin:8px 0 0; }
.profile__photo{ width:167px; height:auto; flex:0 0 auto; display:block; border-radius:6px; }
.profile__text{ flex:1 1 0; min-width:0; }

/* 라벨-값 정렬(Email / Tel / Office) */
.kv{
  display:grid;
  grid-template-columns: 72px 1fr; /* ← 라벨 폭. 간격 넓히거나 줄이려면 숫자만 조정 */
  column-gap:12px; row-gap:4px; margin:10px 0 0;
}
.kv dt{ margin:0; font-weight:600; }
.kv dd{ margin:0; }

/* 모바일에서 세로로 쌓이게 */
@media (max-width:640px){
  .profile{ flex-direction:column; }
}
</style>

<div class="profile">
  <img class="profile__photo" src="https://hoseungs.github.io/img/profile.png" alt="Hoseung Song">

  <!-- markdown="1" 을 넣어야 div 안의 마크다운 링크들이 Jekyll에서 렌더링됩니다 -->
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

---
layout: post
title: Marks of Existence

# thumbnail:
# photos: 
#   - url: 
#   - url: 
# description:
---

<div class="siema01">
  <div><img src="{{ site.baseurl }}/assets/photos/marks-of-existence/impermanence00.jpg"></div>
  <div><img src="{{ site.baseurl }}/assets/photos/marks-of-existence/impermanence01.jpg"></div>
  <div><img src="{{ site.baseurl }}/assets/photos/marks-of-existence/impermanence02.jpg"></div>
  <div><img src="{{ site.baseurl }}/assets/photos/marks-of-existence/impermanence03.jpg"></div>
  <div><img src="{{ site.baseurl }}/assets/photos/marks-of-existence/impermanence04.jpg"></div>
  <div><img src="{{ site.baseurl }}/assets/photos/marks-of-existence/impermanence05.jpg"></div>
  <div><img src="{{ site.baseurl }}/assets/photos/marks-of-existence/impermanence06.jpg"></div>
  <div><img src="{{ site.baseurl }}/assets/photos/marks-of-existence/impermanence07.jpg"></div>
  <div><img src="{{ site.baseurl }}/assets/photos/marks-of-existence/impermanence08.jpg"></div>
  <div><img src="{{ site.baseurl }}/assets/photos/marks-of-existence/impermanence09.jpg"></div>
  <div><img src="{{ site.baseurl }}/assets/photos/marks-of-existence/impermanence10.jpg"></div>
  <div><img src="{{ site.baseurl }}/assets/photos/marks-of-existence/impermanence11.jpg"></div>
  <div><img src="{{ site.baseurl }}/assets/photos/marks-of-existence/impermanence12.jpg"></div>
  <div><img src="{{ site.baseurl }}/assets/photos/marks-of-existence/impermanence13.jpg"></div>
</div>
<h4>
  01 IMPERMANENCE
  <div class="align-right">
    <button class="prev01"> < </button>
    <button class="next01"> > </button>
  </div>
</h4>
<p>

<div class="siema02">
  <div><img src="{{ site.baseurl }}/assets/photos/marks-of-existence/suffering00.jpg"></div>
  <div><img src="{{ site.baseurl }}/assets/photos/marks-of-existence/suffering01.jpg"></div>
  <div><img src="{{ site.baseurl }}/assets/photos/marks-of-existence/suffering02.jpg"></div>
  <div><img src="{{ site.baseurl }}/assets/photos/marks-of-existence/suffering03.jpg"></div>
  <div><img src="{{ site.baseurl }}/assets/photos/marks-of-existence/suffering04.jpg"></div>
  <div><img src="{{ site.baseurl }}/assets/photos/marks-of-existence/suffering05.jpg"></div>
  <div><img src="{{ site.baseurl }}/assets/photos/marks-of-existence/suffering06.jpg"></div>
</div>
<h4>
  02 SUFFERING
  <div class="align-right">
    <button class="prev02"> < </button>
    <button class="next02"> > </button>
  </div>
</h4>
<p>

<div class="siema03">
  <div><img src="{{ site.baseurl }}/assets/photos/marks-of-existence/nonidentity00.jpg"></div>
  <div><img src="{{ site.baseurl }}/assets/photos/marks-of-existence/nonidentity01.jpg"></div>
  <div><img src="{{ site.baseurl }}/assets/photos/marks-of-existence/nonidentity02.jpg"></div>
  <div><img src="{{ site.baseurl }}/assets/photos/marks-of-existence/nonidentity03.jpg"></div>
  <div><img src="{{ site.baseurl }}/assets/photos/marks-of-existence/nonidentity04.jpg"></div>
  <div><img src="{{ site.baseurl }}/assets/photos/marks-of-existence/nonidentity05.jpg"></div>
  <div><img src="{{ site.baseurl }}/assets/photos/marks-of-existence/nonidentity06.jpg"></div>
</div>
<h4>
  03 NON-IDENTITY
  <div class="align-right">
    <button class="prev03"> < </button>
    <button class="next03"> > </button>
  </div>
</h4>
<p>

<script src="{{ site.baseurl }}/javascripts/siema.min.js"></script>
<script>
  siema01 = new Siema({
    selector: '.siema01',
    duration: 0,
    loop: true});
  document.querySelector('.prev01').addEventListener('click', () => siema01.prev());
  document.querySelector('.next01').addEventListener('click', () => siema01.next());
  siema02 = new Siema({
    selector: '.siema02',
    duration: 0,
    loop: true});
  document.querySelector('.prev02').addEventListener('click', () => siema02.prev());
  document.querySelector('.next02').addEventListener('click', () => siema02.next());
  siema03 = new Siema({
    selector: '.siema03',
    duration: 0,
    loop: true});
  document.querySelector('.prev03').addEventListener('click', () => siema03.prev());
  document.querySelector('.next03').addEventListener('click', () => siema03.next());
</script>
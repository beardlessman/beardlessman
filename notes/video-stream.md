---
title: Видео работает?
date: 2020-06-24
tags:
  - fun
layout: layouts/post.njk
---

(надо нажать "Разрешить")

<video playsinline autoplay id="target" style="max-width: 100%;"></video>

<script>
(() => {
  const video = document.querySelector("#target");

  video.width = 480;
  video.height = 360;

  navigator.mediaDevices
    .getUserMedia({
      audio: false,
      video: true,
    })
    .then(videoHandleSuccess)
    .catch(videoHandleError);

  function videoHandleSuccess(stream) {
    video.srcObject = stream;
  }

  function videoHandleError(err) {
    console.log("Video handle error: ", err);
  }
})();</script>

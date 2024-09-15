---
title: 
layout: hextra-home
---

{{< count >}}

<script>
 var searchIndexData = [];
 // fetch on page load from the search index
 let json_path = window.location.origin + '/index.json'

 fetch(json_path).then(function (response) {
 	return response.json();
 })
 .then(function (data) {
 	searchIndexData = data;
 })
 .catch(function (err) {
 	console.log(err)
 });

  
 function sendToRandomArticle() {
 let randIndex = Math.floor(Math.random() * searchIndexData.length);
 let randArticle = searchIndexData[randIndex]['permalink'] + '?utm_source=RandomButton';
 window.location.href = randArticle;
 }

</script>

<button type="button" onclick='sendToRandomArticle()' style="background: radial-gradient(ellipse at 50% 80%,rgba(221,210,59,0.50),hsla(0,0%,100%,0));margin-top:6px;margin-bottom:16px;border-radius:4px;float:none !important">&nbsp;Ves ta una canción aleatoria&nbsp;</button>

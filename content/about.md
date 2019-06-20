---
title: "About me"
draft: false
showpagemeta: false
showcomments: false
---

Got my Dipl. Ing. in the Department of Computer Engineering and Informatics in Patras, Greece. Continued studying in ETH Zurich and got my MSc in Computer Science, focusing in Distributed Systems, Web & System Security.

Currently working at [*Futurae*](https://futurae.com), with the vision to bring 2FA to the world.

Among other topics, interested in web security (that's right), cloud computing, software systems and programming languages. When not engineering things, I'm into socialising, music, books and sports.

Have a look at my interests and skills (tag cloud made using [wordcloud2.js](https://github.com/timdream/wordcloud2.js)):
<div id="tagcloud" style="height: 150px;width:100%;margin-top:30px;">
</div>

<script src="/scripts/wordcloud2.js"></script>
<script type="text/javascript">

  function techTags() {
    var hTags = ['go', 'git', 'java', 'c#', 'sh', 'docker', 'linux', 'puppet'];
    var mTags = ['ruby', 'python', 'c', 'c++', 'elk', '.NET', 'android', 'haproxy', 'nginx', 'ansible', 'jenkins'];
    var lTags = ['perl', 'rails', 'k8s', 'js', 'vuejs', 'iOS', 'obj-c'];

    var i;
    var tags = [];
    var h = 50; var m = 30; var l = 20;
    for(i = 0; i < hTags.length; i++) {
      tags.push([hTags[i], h]);
    }

    for(i = 0; i < mTags.length; i++) {
      tags.push([mTags[i], m]);
    }

    for(i = 0; i < lTags.length; i++) {
      tags.push([lTags[i], l]);
    }

    return tags
  }

  WordCloud(
    document.getElementById('tagcloud'),
    {
      list: techTags(),
      color: 'random-dark',
      minRotation: 0,
      maxRotation: 0,
      shuffle: true,
      //gridSize: 10, // grid spacing between tags
    }
  );
</script>

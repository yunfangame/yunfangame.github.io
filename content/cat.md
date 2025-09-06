---
title: "圈小猫"
date: 2023-10-01T12:00:00+08:00
---
 
{{< catch-the-cat >}}
<p>捉住那只小猫，一个有趣同时也很难的游戏，通过围堵的方式阻止小猫跑到边缘处。</p>

<script src="../js/phaser.min.js"></script>
<script src="../js/catch-the-cat.js"></script>
<div id="catch-the-cat"></div>
<script>
      window.game = new CatchTheCatGame({
        w: 11,
        h: 11,
        r: 20,
        initialWallCount: 8,
        backgroundColor: 0xffffff,
        parent: 'catch-the-cat',
        statusBarAlign: 'center',
        credit: '圈小猫'
      });
</script>

{{< /catch-the-cat >}}

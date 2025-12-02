---
title: Open Source Contributions
date: 2023-06-15
# external_link: https://github.com/pytorch/pytorch
tags:
image:
  hint: picture
  preview_only: true
---

Here are a few of the Open Source projects I maintain or regularly contribute to!

<script src="https://tarptaeya.github.io/repo-card/repo-card.js"></script>
<div class="repo-card" data-repo="jclds139/hdf5storage"></div>
<br/>
<div class="repo-card" data-repo="NohPei/GeoMCU"></div>
<br/>
<div class="repo-card" data-repo="NohPei/geoscope-sensor"></div>
<br/>
<div class="repo-card" data-repo="NohPei/geoscope-gateway"></div>

<script type="text/javascript">

    function setRepoCardsTheme(is_dark) {
        const local_cards = document.getElementsByClassName("repo-card");

        for (var i = 0; i < local_cards.length; i++) {
            if (is_dark)
                local_cards[i].setAttribute('data-theme', 'dark-theme');
            else
                if (local_cards[i].hasAttribute('data-theme'))
                    local_cards[i].removeAttribute('data-theme');
        }
    };

    window.addEventListener('hbThemeChange', function () {
      setRepoCardsTheme(document.documentElement.classList.contains("dark"));
    });

    setRepoCardsTheme(document.documentElement.classList.contains("dark"));

</script>
<!--more-->
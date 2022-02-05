---
permalink: /
title: "Hello/ Namaste/ Allô/ Hola"
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

<style>
    ul { display: flex; margin: 0; padding: 0; overflow: hidden; }
    li { display: block; list-style: none; }

    button.prev, button.next {
        display: flex; font-size: 32px;
        align-items: center; justify-content: center;
        color: #FFF; background-color: #333;
        border-radius: 50%;
        width: 44px; height: 44px;
    }
    button.prev {
        position: absolute; left: 0; top: 80px;
    }
    button.next {
        position: absolute; right: 0; top: 80px;
    }
</style>

<ul>
      <li><img class="img1" src="//picsum.photos/300/200?1"></li>
      <li><img class="img2" src="//picsum.photos/300/200?2"></li>
      <li><img class="img3" src="//picsum.photos/300/200?3"></li>
      <li><img class="img4" src="//picsum.photos/300/200?4"></li>
      <li><img class="img5" src="//picsum.photos/300/200?5"></li>
      <li><img class="img6" src="//picsum.photos/300/200?6"></li>
      <li><img class="img7" src="//picsum.photos/300/200?7"></li>
      <li><img class="img8" src="//picsum.photos/300/200?8"></li>
      <li><img class="img9" src="//picsum.photos/300/200?9"></li>
</ul>
<button onclick="show(-1)">&lt;</button>
<button onclick="show(+1)">&gt;</button>

<script>
let liEls = document.querySelectorAll('ul li');
let index = 0;
window.show = function(increase) {
  index = index + increase;
  index = Math.min(Math.max(index,0), liEls.length-1);
  liEls[index].scrollIntoView({behavior: 'smooth'});
}
</script>

Coucou! I'm Khashiff and I've just made the move up to Quebec City to start a PhD in Oceanography! How cold does it get? How's your French? Are we having a good time? Yes yes and YES! Life up here is great, I spend my days researching the effects of climate change on ice, algae and mussels, learning about sustainability from Inuit Communities and, in my free time, going out snowboarding and bouldering. Moving up here was something I've been looking forward to for a while. I've been keen on working in another language and here I've got both French and Inuktitut to grapple with. More importantly I get to learn from both the Inuit and the Quebecois on life in this strange part of the earth where folks roam outdoors at -30 C and how climate change is affecting these high latitudes. Hopefully, if I get off my butt quick enough I'll be able to have a blog post out every week or so to keep my fans (mainly mum and dad) up to date with my life!

---
title: "PSYC 2021: Syllabus"
subtitle: Statistical Methods I &middot; York University &middot; Winter 2026
description: "PSYC 2021: Syllabus, York University, taught by Naomi Martinez Gutierrez, PhD."
---

<div class="container-fluid px-0 embed-wrap">
  <iframe id="embedded-page" src="{{ '/syllabus/' | relative_url }}" title="PSYC 2021: Syllabus" loading="eager" scrolling="no"></iframe>
</div>

<style>
  .embed-wrap { background: #fff; }
  #embedded-page { display: block; width: 100%; border: 0; min-height: 80vh; }
</style>
<script>
  (function () {
    var f = document.getElementById('embedded-page');
    function fit() {
      try {
        var d = f.contentDocument;
        if (!d) return;
        f.style.height = Math.max(d.documentElement.scrollHeight, d.body.scrollHeight) + 'px';
      } catch (e) {}
    }
    f.addEventListener('load', function () {
      fit();
      try {
        var d = f.contentDocument;
        // open links that leave this section in the main window, not inside the frame
        d.querySelectorAll('a[href]').forEach(function (a) {
          var href = a.getAttribute('href');
          if (href && href.charAt(0) !== '#') a.setAttribute('target', '_top');
        });
        if (window.ResizeObserver) new ResizeObserver(fit).observe(d.body);
      } catch (e) {}
      setTimeout(fit, 500); setTimeout(fit, 1500);
    });
    window.addEventListener('resize', fit);
  })();
</script>

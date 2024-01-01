---
title: 'test'
permalink: /test
redirect_to: https://www.google.com/
---
<script>
  // Add a delay (in milliseconds) before the redirect
  const delay = 20000; // 20000 milliseconds = 20 seconds
  const destinationUrl = "{{ page.redirect_to }}";

  setTimeout(() => {
    window.location.href = destinationUrl;
  }, delay);
</script>
Redirecting to [{{ page.redirect_to }}]({{ page.redirect_to }})...

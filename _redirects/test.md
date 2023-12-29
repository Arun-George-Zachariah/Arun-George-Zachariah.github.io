---
title: 'test'
permalink: /test
---
<script>
  // Add a delay (in milliseconds) before the redirect
  const delay = 2000; // 2000 milliseconds = 2 seconds
  const destinationUrl = "{{ page.redirect_to }}";

  setTimeout(() => {
    window.location.href = destinationUrl;
  }, delay);
</script>
Redirecting to [{{ page.redirect_to }}]({{ page.redirect_to }})...

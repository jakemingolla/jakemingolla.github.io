---
layout: default
permalink: /
---
{% include landing.html %}
<script type='text/javascript'>
  const selectedTheme = localStorage.getItem('theme');

  // Default to dark mode unless previously set
  if (!selectedTheme) {
    setTheme('dark');
  }
</script>

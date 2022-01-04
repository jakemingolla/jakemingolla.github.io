---
layout: default
permalink: /
---
{% include landing.html %}
<script type='text/javascript'>
  const STORAGE_THEME_KEY = 'theme';
  const selectedTheme = localStorage.getItem(STORAGE_THEME_KEY);

  // Default to dark mode unless previously set
  if (!selectedTheme) {
    setTheme('dark');
    localStorage.setItem(STORAGE_THEME_KEY, 'dark');
  }
</script>

---
title: PocketSuite Hub
---

<style> 
  /* 🚫 Force theme engine elements to stay hidden */ 
  header, .site-header, #header, footer, .site-footer, .footer, #footer { display: none !important; } 

  /* 🟧 Light Mode Alert Box Coloring */ 
  .markdown-body blockquote, #main_content blockquote, blockquote { background-color: #fff8ec !important; border-left: 0.25em solid #e68a00 !important; padding: 15px !important; color: #3b2c11 !important; border-radius: 6px; } 

  /* 🌓 Dark Mode Core Layout Overrides */ 
  body.dark-mode-active, body.dark-mode-active .container-lg, body.dark-mode-active #main_content { background-color: #0d1117 !important; color: #c9d1d9 !important; } 
  body.dark-mode-active h1, body.dark-mode-active h2, body.dark-mode-active h3, body.dark-mode-active h4 { color: #f0f6fc !important; border-bottom: 1px solid #21262d !important; } 
  body.dark-mode-active a { color: #58a6ff !important; } 

  /* 🟧 Dark Mode Alert Box Coloring */ 
  body.dark-mode-active blockquote, body.dark-mode-active .markdown-body blockquote { background-color: rgba(187, 128, 9, 0.15) !important; border-left: 0.25em solid #f2cc60 !important; color: #f0e1b2 !important; } 

  /* 💻 Code Block Adjustments */ 
  body.dark-mode-active code { background-color: rgba(110, 118, 129, 0.4) !important; color: #e6edf3 !important; } 
  
  /* 🌙 Theme Toggle Button Interface Styles */
  #theme-toggle-btn { 
    padding: 10px 16px !important; 
    background: #21262d !important; 
    color: #f0f6fc !important; 
    border: 1px solid #30363d !important; 
    border-radius: 6px !important; 
    cursor: pointer !important; 
    font-weight: 600 !important; 
    font-size: 14px !important;
    margin-bottom: 20px !important;
    display: inline-block !important;
  }
  body.dark-mode-active #theme-toggle-btn { 
    background: #ffffff !important; 
    color: #0d1117 !important; 
    border-color: #d0d7de !important; 
  } 

  /* ========================================== */ 
  /* 🔥 FORCED AGGRESSIVE BUTTON OVERRIDES      */ 
  /* ========================================== */ 

  /* 1. Force the layout container to stack cleanly */ 
  div.btn-container { 
    margin: 20px 0 !important; 
    display: flex !important; 
    flex-direction: column !important; 
    gap: 12px !important; 
    max-width: 320px !important; 
  } 

  /* 2. Target the link inside the container and smash it into a solid button */ 
  div.btn-container a { 
    display: block !important; 
    padding: 14px 20px !important; 
    background-color: #24292e !important; 
    color: #ffffff !important; 
    text-decoration: none !important; 
    font-weight: bold !important; 
    border-radius: 6px !important; 
    border: 1px solid #444c56 !important; 
    text-align: center !important; 
    transition: all 0.2s ease-in-out !important; 
    font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", Helvetica, Arial, sans-serif !important; 
    box-shadow: 0 1px 3px rgba(0,0,0,0.12) !important; 
  } 

  /* 3. Hover state response animation */ 
  div.btn-container a:hover { 
    background-color: #2c3137 !important; 
    transform: translateY(-2px) !important; 
    box-shadow: 0 4px 12px rgba(0,0,0,0.2) !important; 
  } 

  /* 4. Force unique styling specifically for the Website variant container */ 
  div.site-container a { 
    background-color: #1f6feb !important; 
    border-color: #388bfd !important; 
  } 
  div.site-container a:hover { 
    background-color: #388bfd !important; 
  } 

  /* 5. Protect button text legibility inside Dark Mode updates */ 
  body.dark-mode-active div.btn-container a { 
    color: #ffffff !important; 
  } 
</style> 

<!-- 🌓 Interactive Theme Selector Elements -->
<button id="theme-toggle-btn" onclick="toggleDarkMode()">🌙 Switch Theme</button>

<script>
  function toggleDarkMode() {
    const bodyElement = document.body;
    const themeBtn = document.getElementById('theme-toggle-btn');
    
    // Toggle class name matches your custom dark mode CSS rule targets
    bodyElement.classList.toggle('dark-mode-active');
    
    // Dynamically shift visual label text based on active states
    if (bodyElement.classList.contains('dark-mode-active')) {
      themeBtn.innerHTML = '☀️ Light Mode';
    } else {
      themeBtn.innerHTML = '🌙 Dark Mode';
    }
  }
</script>

# 🚀 PocketSuite Hub

### USE THE LINKS BELOW TO SEE THE GITHUB REPOS
<div class="btn-container"> 
  <a href="https://github.com/m97493578-ops/PocketPyCharm">🚀 Open PocketPyCharm</a> 
  <a href="https://github.com/m97493578-ops/PocketPython">🚀 Open PocketPython</a> 
</div> 

### CLICK THE LINKS BELOW FOR THE WEBSITE VERSION
<div class="btn-container site-container"> 
  <a href="https://m97493578-ops.github.io/PocketPyCharm/">🚀 Open PocketPyCharm</a> 
  <a href="https://m97493578-ops.github.io/PocketPython/">🚀 Open PocketPython</a> 
</div>

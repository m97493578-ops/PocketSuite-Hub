<style> 
  /* 🚫 Force theme engine elements to stay hidden */ 
  header, .site-header, #header, footer, .site-footer, .footer, #footer { display: none !important; } 

  /* 🟧 Light Mode Alert Box Coloring */ 
  .markdown-body blockquote, #main_content blockquote, blockquote { background-color: #fff8ec !important; border-left: 0.25em solid #e68a00 !important; padding: 15px !important; color: #3b2c11 !important; border-radius: 6px; } 

  /* 🌓 Dark Mode Core Layout Overrides (Triggers when the URL ends in #dark) */ 
  body:has(:target), .container-lg:has(:target), #main_content:has(:target) { background-color: #0d1117 !important; color: #c9d1d9 !important; } 
  body:has(:target) h1, body:has(:target) h2, body:has(:target) h3, body:has(:target) h4 { color: #f0f6fc !important; border-bottom: 1px solid #21262d !important; } 
  body:has(:target) a { color: #58a6ff !important; } 

  /* ⚙️ Theme Toggle Link Elements formatted as Markdown Buttons */
  .theme-btn {
    display: inline-block !important;
    padding: 8px 14px !important;
    background-color: #21262d !important;
    color: #f0f6fc !important;
    border: 1px solid #30363d !important;
    border-radius: 6px !important;
    text-decoration: none !important;
    font-size: 14px !important;
    font-weight: 600 !important;
    margin-bottom: 20px !important;
  }
  
  /* Swap button visibility based on target anchors */
  #light-mode-link { display: none !important; }
  body:has(:target) #dark-mode-link { display: none !important; }
  body:has(:target) #light-mode-link { display: inline-block !important; background-color: #ffffff !important; color: #0d1117 !important; border-color: #d0d7de !important; }

  /* ========================================== */ 
  /* 🔥 FORCED AGGRESSIVE BUTTON OVERRIDES      */ 
  /* ========================================== */ 
  div.btn-container { 
    margin: 20px 0 !important; 
    display: flex !important; 
    flex-direction: column !important; 
    gap: 12px !important; 
    max-width: 320px !important; 
  } 
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
  } 
  div.btn-container a:hover { background-color: #2c3137 !important; } 
  div.site-container a { background-color: #1f6feb !important; border-color: #388bfd !important; } 
  div.site-container a:hover { background-color: #388bfd !important; } 
  body:has(:target) div.btn-container a { color: #ffffff !important; } 
</style> 

<div id="dark"></div>
<a href="#dark" class="theme-btn" id="dark-mode-link">🌙 Dark Mode</a>
<a href="#" class="theme-btn" id="light-mode-link">☀️ Light Mode</a>
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

<!-- 🌓 PocketPyCharm UI Engine (Dark Mode + Custom Theme Colors + Layout Fix) --> 
<div style="text-align: right; margin: 15px 0;"> 
  <button id="theme-toggle-btn" style="padding: 8px 16px; border-radius: 20px; border: 1px solid #ccc; background: #ffffff; color: #24292e; cursor: pointer; font-weight: bold; font-family: sans-serif; transition: all 0.2s ease;">🌙 Dark Mode</button> 
</div> 

<img width="1418" height="617" alt="image" src="https://github.com/user-attachments/assets/f5f70848-1cbd-4556-aeda-27a173cf53b7" />


<script> 
  const themeButton = document.getElementById('theme-toggle-btn'); 
  
  if (localStorage.getItem('site-theme') === 'dark' || (!localStorage.getItem('site-theme') && window.matchMedia('(prefers-color-scheme: dark)').matches)) { 
    document.body.classList.add('dark-mode-active'); 
    themeButton.textContent = '☀️ Light Mode'; 
  } 

  themeButton.addEventListener('click', () => { 
    document.body.classList.toggle('dark-mode-active'); 
    if (document.body.classList.contains('dark-mode-active')) { 
      themeButton.textContent = '☀️ Light Mode'; 
      localStorage.setItem('site-theme', 'dark'); 
    } else { 
      themeButton.textContent = '🌙 Dark Mode'; 
      localStorage.setItem('site-theme', 'light'); 
    } 
  }); 
</script>

# 🚀 PocketSuite Hub

### USE THE LINKS BELOW TO SEE THE GITHUB REPOS
<div class="btn-container">
  <a href="https://github.com/m97493578-ops/PocketPyCharm" class="custom-btn">🚀 Open PocketPyCharm</a>
  <a href="https://github.com/m97493578-ops/PocketPython" class="custom-btn">🚀 Open PocketPython</a>
</div>

### CLICK THE LINKS BELOW FOR THE WEBSITE VERSION
<div class="btn-container site-container">
  <a href="https://m97493578-ops.github.io/PocketPyCharm/" class="custom-btn">🚀 Open PocketPyCharm</a>
  <a href="https://m97493578-ops.github.io/PocketPython/" class="custom-btn">🚀 Open PocketPython</a>
</div>


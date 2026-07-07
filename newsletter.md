---
layout: default
---

<!-- Complete Style Overhaul -->
<style>
  /* Fix the default layout spacing and completely hide theme clutter/sidebar constraints */
  header, footer, .sidebar, .project-links, #forkongithub { display: none !important; }
  body { background-color: #f7f9fc; margin: 0; padding: 0; font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif; width: 100%; }
  
  /* Blows open the theme's default layout container box to span 100% of the screen width */
  .wrapper { 
    max-width: 100% !important; 
    width: 100% !important;
    margin: 0 !important; 
    padding: 0 !important;
    display: block !important;
  }
  
  /* Absolute Center Force: Centers the layout container right in the middle of the wide viewport */
  section { 
    max-width: 900px !important; 
    width: 90% !important;
    padding: 130px 20px 60px 20px !important; 
    margin: 0 auto !important; 
    float: none !important; 
    clear: both !important;
    display: flex !important;
    flex-direction: column !important;
    align-items: center !important;
    box-sizing: border-box !important;
  }
  
  /* Top Nav Bar Styling */
  .custom-nav { background-color: white; padding: 15px 40px; border-bottom: 1px solid #eaeaea; display: flex; justify-content: space-between; align-items: center; position: fixed; top: 0; left: 0; right: 0; z-index: 9999; box-shadow: 0 2px 5px rgba(0,0,0,0.05); }
  .nav-links-left { display: flex; gap: 35px; font-weight: 700; font-size: 0.85rem; letter-spacing: 0.05em; }
  .nav-links-left a { color: #333; text-decoration: none; transition: color 0.2s; }
  .nav-links-left a:hover { color: #1e73be; }
  
  /* Action Buttons */
  .btn-donate { background-color: #ff6600; color: white !important; padding: 14px 32px; text-decoration: none; font-weight: bold; border-radius: 6px; display: inline-block; font-size: 1.1rem; box-shadow: 0 4px 10px rgba(255, 102, 0, 0.2); transition: transform 0.2s; margin: 8px; }
  .btn-donate:hover { transform: translateY(-2px); text-decoration: none; }
</style>

<!-- Clean White Navigation Bar Layer -->
<div class="custom-nav">
  <div class="nav-links-left">
    <a href="./index.html">HOME</a>
    <a href="./about.html">ABOUT US</a>
    <a href="./events.html">UPCOMING EVENTS</a>
    <a href="./Newsletter.html" style="color: #1e73be;">NEWSLETTER</a>
  </div>
  <div>
    <a href="https://events.nationalmssociety.org/teams/ydc" style="background-color: #ff6600; color: white; padding: 9px 20px; text-decoration: none; font-weight: bold; border-radius: 4px; font-size: 0.85rem; display: inline-block; letter-spacing: 0.05em;">DONATE</a>
  </div>
</div>

<!-- Main Content Area -->
<section>
 <!-- Integrated Substack Section Styled as a Clean Card -->
  <div style="background: white; border-radius: 12px; padding: 40px 20px; box-shadow: 0 4px 15px rgba(0,0,0,0.05); text-align: center; width: 100%; box-sizing: border-box;">
    <h3 style="color: #333; font-weight: 700; font-size: 1.6rem; margin-top: 0; margin-bottom: 20px; letter-spacing: -0.02em;">Subscribe for Campaign Milestones</h3>
    <div style="display: flex; justify-content: center; width: 100%; overflow: hidden;">
      <iframe src="https://youthdrivingchange.substack.com/embed" width="480" height="320" style="border: none; background: transparent;" frameborder="0" scrolling="no"></iframe>
    </div>
</section>

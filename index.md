---
layout: default
---

<!-- Complete Style Overhaul (No code required on your part) -->
<style>
  /* Fix the default layout spacing and hide theme clutter */
  header, footer, .sidebar, .project-links, #forkongithub { display: none !important; }
  body { background-color: #f7f9fc; margin: 0; padding: 0; font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif; }
  .wrapper { max-width: 100% !important; padding: 0 !important; margin: 0 !important; }
  section { max-width: 900px !important; margin: 0 auto !important; padding: 120px 20px 60px 20px !important; float: none !important; width: 100% !important; }
  
  /* Top Nav Bar Styling */
  .custom-nav { background-color: white; padding: 15px 40px; border-bottom: 1px solid #eaeaea; display: flex; justify-content: space-between; align-items: center; position: fixed; top: 0; left: 0; right: 0; z-index: 9999; box-shadow: 0 2px 5px rgba(0,0,0,0.05); }
  .nav-links-left { display: flex; gap: 35px; font-weight: 700; font-size: 0.85rem; letter-spacing: 0.05em; }
  .nav-links-left a { color: #333; text-decoration: none; transition: color 0.2s; }
  .nav-links-left a:hover { color: #1e73be; }
  
  /* Hero Call-To-Action Layout */
  .hero-container { text-align: center; background: white; border-radius: 12px; padding: 50px 30px; box-shadow: 0 4px 15px rgba(0,0,0,0.05); margin-bottom: 40px; }
  .main-headline { color: #1e73be; font-size: 2.8rem; font-weight: 800; margin: 20px 0 10px 0; }
  .main-subheadline { color: #555; font-size: 1.2rem; margin-bottom: 35px; max-width: 600px; margin-left: auto; margin-right: auto; line-height: 1.6; }
  
  /* Action Buttons */
  .btn-donate { background-color: #ff6600; color: white !important; padding: 14px 32px; text-decoration: none; font-weight: bold; border-radius: 6px; display: inline-block; font-size: 1.1rem; box-shadow: 0 4px 10px rgba(255, 102, 0, 0.3); transition: transform 0.2s; margin: 10px; }
  .btn-register { background-color: #1e73be; color: white !important; padding: 14px 32px; text-decoration: none; font-weight: bold; border-radius: 6px; display: inline-block; font-size: 1.1rem; box-shadow: 0 4px 10px rgba(30, 115, 190, 0.3); transition: transform 0.2s; margin: 10px; }
  .btn-donate:hover, .btn-register:hover { transform: translateY(-2px); text-decoration: none; }
</style>

<!-- Clean White Navigation Bar Layer -->
<div class="custom-nav">
  <div class="nav-links-left">
    <a href="./index.html" style="color: #1e73be;">HOME</a>
    <a href="./about.html">ABOUT US</a>
    <a href="./events.html">UPCOMING EVENTS</a>
    <a href="./newsletter.html">NEWSLETTER</a>
  </div>
  <div>
    <a href="https://events.nationalmssociety.org/teams/ydc" style="background-color: #ff6600; color: white; padding: 9px 20px; text-decoration: none; font-weight: bold; border-radius: 4px; font-size: 0.85rem; display: inline-block; letter-spacing: 0.05em;">DONATE</a>
  </div>
</div>

<!-- Main Content Area -->
<section>
  <div class="hero-container">
    <img src="image_fab823.png" alt="YouthDrivingChange Logo" style="max-width: 220px; border-radius: 50%; box-shadow: 0 4px 10px rgba(0,0,0,0.1);">
    
    <h1 class="main-headline">YouthDrivingChange</h1>
    <p class="main-subheadline">Driving change and making an impact through BikeMS.</p>
    
    <div style="margin-top: 30px;">
      <a href="https://events.nationalmssociety.org/teams/ydc" class="btn-donate">Donate to BikeMS</a>
      <a href="https://events.nationalmssociety.org/index.cfm?fuseaction=register.start&eventID=2736&teamID=100250" class="btn-register">Register for the Event</a>
    </div>
  </div>

  <div style="background: white; border-radius: 12px; padding: 40px; box-shadow: 0 4px 15px rgba(0,0,0,0.05); line-height: 1.8; color: #444;">
    <h3 style="color: #333; font-weight: 700; margin-top: 0; font-size: 1.4rem;">Welcome to our community</h3>
    <p>Welcome to the official hub for YouthDrivingChange. Use the navigation links at the top left to explore our mission, check out our ride schedules, or subscribe to our community newsletter. Your support directly powers the fight against multiple sclerosis!</p>
  </div>
</section>

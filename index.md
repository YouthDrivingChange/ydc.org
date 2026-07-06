---
layout: default
---

<!-- Complete Style Overhaul -->
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
  
  /* Watermark Hero Container Layout */
  .hero-container { 
    position: relative; 
    text-align: center; 
    background: white; 
    border-radius: 12px; 
    padding: 80px 30px; 
    box-shadow: 0 4px 15px rgba(0,0,0,0.05); 
    margin-bottom: 40px; 
    overflow: hidden; 
  }
  
  /* The Background Logo Watermark Layer */
  .hero-watermark {
    position: absolute;
    top: 50%;
    left: 50%;
    transform: translate(-50%, -50%);
    width: 100%;
    max-width: 650px;
    opacity: 0.07; 
    mix-blend-mode: multiply; /* Blends away the image's background box */
    pointer-events: none; 
    z-index: 1;
  }
  
  /* Content Layer forcing text/buttons over the watermark */
  .hero-content {
    position: relative;
    z-index: 2;
  }
  
  .main-headline { color: #1e73be; font-size: 3.2rem; font-weight: 800; margin: 0 0 15px 0; letter-spacing: -0.03em; }
  .main-subheadline { color: #555; font-size: 1.25rem; margin-bottom: 35px; max-width: 600px; margin-left: auto; margin-right: auto; line-height: 1.6; font-weight: 500; }
  
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
    <a href="./Newsletter.html">NEWSLETTER</a>
  </div>
  <div>
    <a href="https://events.nationalmssociety.org/teams/ydc" style="background-color: #ff6600; color: white; padding: 9px 20px; text-decoration: none; font-weight: bold; border-radius: 4px; font-size: 0.85rem; display: inline-block; letter-spacing: 0.05em;">DONATE</a>
  </div>
</div>

<!-- Main Content Area -->
<section>
  <div class="hero-container">
    <!-- Huge Background Watermark Image -->
    <img src="./logo.png" class="hero-watermark" alt="">
    
    <!-- Foreground Content Layer -->
    <div class="hero-content">
      <h1 class="main-headline">YouthDrivingChange</h1>
      <p class="main-subheadline">Accelerating the fight for a cure, one mile at a time.</p>
      
      <div style="margin-top: 30px;">
        <a href="https://events.nationalmssociety.org/teams/ydc" class="btn-donate">Donate to BikeMS</a>
        <a href="https://events.nationalmssociety.org/index.cfm?fuseaction=register.start&eventID=2736&teamID=100250" class="btn-register">Register for the Event</a>
      </div>
    </div>
  </div>

  <div style="background: white; border-radius: 12px; padding: 40px; box-shadow: 0 4px 15px rgba(0,0,0,0.05); line-height: 1.8; color: #444;">
    <h3 style="color: #333; font-weight: 700; margin-top: 0; font-size: 1.5rem; letter-spacing: -0.02em;">Driven by Youth. Fueled by Community.</h3>
    <p style="font-size: 1.05rem; color: #555; margin-bottom: 20px;">
      YouthDrivingChange was founded in 2022 to transform a personal family tradition into a powerful, youth-led movement. We manage, organize, and execute strategic fundraising campaigns and team rides for BikeMS to accelerate the fight for a multiple sclerosis cure.
    </p>
    <p style="font-size: 1.05rem; color: #555; margin-bottom: 0;">
      Whether you are looking to check out our <strong>Upcoming Events</strong>, read our story in <strong>About Us</strong>, or subscribe to our <strong>Newsletter</strong> for real-time milestones, you are part of the momentum. Explore the navigation links above to find out how you can ride, donate, or help us spread powerful awareness.
    </p>
  </div>
</section>

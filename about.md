---
layout: default
---

<style>
  /* Fix the default layout spacing and completely hide theme clutter/sidebar constraints */
  header, footer, .sidebar, .project-links, #forkongithub { display: none !important; }
  
  body { 
    background-color: #f7f9fc; 
    margin: 0; 
    padding: 0; 
    font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif; 
    width: 100%; 
  }
  
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
    padding: 110px 20px 60px 20px !important; /* Adjusted slightly to tuck neatly under the navbar */
    margin: 0 auto !important; 
    float: none !important; 
    clear: both !important;
    display: flex !important;
    flex-direction: column !important;
    align-items: stretch !important;
    box-sizing: border-box !important;
  }
  
  /* Top Nav Bar Styling */
  .custom-nav { 
    background-color: white; 
    padding: 15px 40px; 
    border-bottom: 1px solid #eaeaea; 
    display: flex; 
    justify-content: space-between; 
    align-items: center; 
    position: fixed; 
    top: 0; 
    left: 0; 
    right: 0; 
    z-index: 9999; 
    box-shadow: 0 2px 5px rgba(0,0,0,0.05); 
  }
  .nav-links-left { display: flex; gap: 35px; font-weight: 700; font-size: 0.85rem; letter-spacing: 0.05em; }
  .nav-links-left a { color: #333; text-decoration: none; transition: color 0.2s; }
  .nav-links-left a:hover { color: #1e73be; }
  .nav-links-left .active { color: #1e73be; }

  /* Content & Call-to-Action Cards */
  .info-card {
    background: white; 
    border-radius: 12px; 
    padding: 40px; 
    box-shadow: 0 4px 15px rgba(0,0,0,0.05); 
    line-height: 1.8; 
    color: #444; 
    width: 100%; 
    box-sizing: border-box; 
    text-align: left; 
    margin-bottom: 30px;
  }
  .info-card h1 { color: #1e73be; font-size: 2.5rem; font-weight: 800; margin-top: 0; margin-bottom: 20px; letter-spacing: -0.02em; }
  .info-card h3 { color: #333; font-weight: 700; font-size: 1.4rem; margin-top: 0; margin-bottom: 15px; }
  .info-card .intro-text { font-size: 1.15rem; font-weight: 600; color: #333; line-height: 1.6; margin-bottom: 0; }
  .info-card p { font-size: 1.05rem; color: #555; margin-bottom: 20px; }
  .info-card p:last-child { margin-bottom: 0; }

  /* Bottom Call to Action Formatting */
  .cta-card { text-align: center; }
  .cta-card h4 { color: #333; font-weight: 700; font-size: 1.5rem; margin-top: 0; margin-bottom: 15px; letter-spacing: -0.02em; }
  .cta-card p { font-size: 1.05rem; color: #555; line-height: 1.7; max-width: 750px; margin: 0 auto 30px auto; }
  .cta-buttons { display: flex; justify-content: center; flex-wrap: wrap; gap: 10px; }

  /* Action Buttons */
  .btn-donate-nav { background-color: #ff6600; color: white !important; padding: 9px 20px; text-decoration: none; font-weight: bold; border-radius: 4px; font-size: 0.85rem; display: inline-block; letter-spacing: 0.05em; }
  .btn-donate { background-color: #ff6600; color: white !important; padding: 14px 32px; text-decoration: none; font-weight: bold; border-radius: 6px; display: inline-block; font-size: 1.1rem; box-shadow: 0 4px 10px rgba(255, 102, 0, 0.2); transition: transform 0.2s; margin: 8px; }
  .btn-register { background-color: #1e73be; color: white !important; padding: 14px 32px; text-decoration: none; font-weight: bold; border-radius: 6px; display: inline-block; font-size: 1.1rem; box-shadow: 0 4px 10px rgba(30, 115, 190, 0.2); transition: transform 0.2s; margin: 8px; }
  .btn-donate:hover, .btn-register:hover { transform: translateY(-2px); text-decoration: none; }

  /* Mobile Adjustments */
  @media (max-width: 768px) {
    section { padding-top: 180px !important; } 
    .custom-nav { padding: 15px 20px; flex-direction: column; gap: 15px; text-align: center; }
    .nav-links-left { gap: 15px; flex-wrap: wrap; justify-content: center; }
  }
</style>

<div class="custom-nav">
  <div class="nav-links-left">
    <a href="./index.html">HOME</a>
    <a href="./about.html" class="active">ABOUT US</a>
    <a href="./events.html">UPCOMING EVENTS</a>
    <a href="./newsletter.html">NEWSLETTER</a>
  </div>
  <div>
    <a href="https://events.nationalmssociety.org/teams/ydc" class="btn-donate-nav">DONATE</a>
  </div>
</div>

<section>

  <div class="info-card">
    <h1>About YouthDrivingChange</h1>
    <h3>Our Mission</h3>
    <p class="intro-text">
      YouthDrivingChange is dedicated to changing lives by raising critical funds for multiple sclerosis research, accelerating the fight for a cure, and spreading powerful awareness throughout our community.
    </p>
  </div>

  <div class="info-card">
    <h3>Our Story</h3>
    <p>
      YouthDrivingChange started long before a team was ever officially formed. Growing up, I watched my mom ride in the BikeMS event year after year, witnessing firsthand the incredible power of a community uniting for a cure.
    </p>
    <p>
      In 2022, the moment I was finally old enough to start a team of my own, I didn't hesitate. What began as a mission rooted in family tradition has since become deeply personal. Today, YouthDrivingChange has raised over $188,000 and I have close friends who are living with multiple sclerosis. Every dollar raised, every mile logged, brings us closer to a world free of MS.
    </p>
  </div>

  <div class="info-card">
    <h3>Broader Impact</h3>
    <p>
      The MS society has supported nearly 450,000 people since 2017 with highly skilled, compassionate professionals who help people with MS get the resources, information, and support they need. They have established nearly 400 partnerships with high-quality MS care centers and have invested more than $1.1 billion in MS research since 1946.
    </p>
  </div>

  <div class="info-card cta-card">
    <h4>Be Part of the Change</h4>
    <p>
      What started as a family tradition has grown into a mission to protect our friends, families, and community. The fight to cure MS requires all of us. Join YouthDrivingChange today, help us fuel breakthrough research, spread powerful awareness, and bring us one step closer to a cure.
    </p>
    <div class="cta-buttons">
      <a href="https://events.nationalmssociety.org/index.cfm?fuseaction=register.start&eventID=2736&teamID=100250" class="btn-register">Register to Ride</a>
      <a href="https://events.nationalmssociety.org/teams/ydc" class="btn-donate">Support Our Team</a>
    </div>
  </div>
</section>

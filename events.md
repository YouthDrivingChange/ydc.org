---
layout: default
---

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
  
  /* Absolute Center Force */
  section { 
    max-width: 900px !important; 
    width: 90% !important;
    padding: 60px 20px 60px 20px !important; 
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

  /* Content Card Styling */
  .content-card {
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
  
  /* Event Item Container */
  .event-item {
    border-bottom: 1px solid #eaeaea;
    padding: 25px 0;
    display: flex;
    justify-content: space-between;
    align-items: center;
  }
  .event-item:last-child {
    border-bottom: none;
    padding-bottom: 0;
  }
  .event-date {
    color: #ff6600;
    font-weight: 700;
    font-size: 0.85rem;
    letter-spacing: 0.05em;
    display: block;
  }
  .event-title {
    color: #333;
    margin: 5px 0 10px 0;
    font-size: 1.4rem;
    font-weight: 700;
    letter-spacing: -0.02em;
  }
  .event-description {
    color: #555;
    margin: 0;
    font-size: 1.05rem;
  }
  .btn-details {
    border: 2px solid #1e73be;
    color: #1e73be;
    padding: 10px 20px;
    text-decoration: none;
    font-weight: bold;
    border-radius: 6px;
    font-size: 0.9rem;
    white-space: nowrap;
    transition: background 0.2s, color 0.2s;
  }
  .btn-details:hover {
    background-color: #1e73be;
    color: white;
  }
</style>

<div class="custom-nav">
  <div class="nav-links-left">
    <a href="./index.html">HOME</a>
    <a href="./about.html">ABOUT US</a>
    <a href="./events.html" style="color: #1e73be;">UPCOMING EVENTS</a>
    <a href="./newsletter.html">NEWSLETTER</a>
  </div>
  <div>
    <a href="https://events.nationalmssociety.org/teams/ydc" style="background-color: #ff6600; color: white; padding: 9px 20px; text-decoration: none; font-weight: bold; border-radius: 4px; font-size: 0.85rem; display: inline-block; letter-spacing: 0.05em;">DONATE</a>
  </div>
</div>

<section style="margin-top: 40px;">
  
  <!-- Header Block -->
  <div class="content-card">
    <h2 style="color: #1e73be; font-size: 2.5rem; font-weight: 800; margin: 0 0 15px 0; letter-spacing: -0.03em;">Upcoming Events</h2>
    <p style="font-size: 1.1rem; color: #555; margin: 0;">
      Stay tuned for details regarding our upcoming campaign rides, team schedules, and logistics. Whether you are riding hard with us on the pavement, tackling the gravel trails, or cheering us on from the sidelines, your support builds our momentum.
    </p>
  </div>

  <!-- Events List Card -->
  <div class="content-card">
    <h3 style="color: #333; font-weight: 700; margin-top: 0; font-size: 1.5rem; letter-spacing: -0.02em; border-bottom: 2px solid #f7f9fc; padding-bottom: 15px;">Official Team Schedule</h3>
    
    <!-- Event 1: Bike MS New Bern -->
    <div class="event-item">
      <div style="padding-right: 20px;">
        <span class="event-date">SEPTEMBER 19 - 20, 2026</span>
        <h4 class="event-title">Bike MS: Historic New Bern Ride</h4>
        <p class="event-description">Our primary campaign event of the year. Featuring scenic coastal architecture and a deep-woods gravel trail experience through Croatan National Forest. All routes kick off from Union Point Park.</p>
      </div>
      <div>
        <a href="https://events.nationalmssociety.org/2736" target="_blank" class="btn-details">Event Details</a>
      </div>
    </div>

    <!-- Event 2: Raleigh Turkey Trot -->
    <div class="event-item">
      <div style="padding-right: 20px;">
        <span class="event-date">NOVEMBER 26, 2026 (THANKSGIVING MORNING)</span>
        <h4 class="event-title">Raleigh Turkey Trot</h4>
        <p class="event-description">Kick off your Thanksgiving morning with the Triangle's favorite holiday tradition. Join us out at Ridgewood Shopping Center to run, walk, and raise critical funds to strike out multiple sclerosis.</p>
      </div>
      <div>
        <a href="https://ridgewoodturkeytrot.itsyourrace.com/" target="_blank" class="btn-details">Event Details</a>
      </div>
    </div>

  </div>

  <!-- Contact Callout -->
  <div style="background: #eef4fa; border-left: 4px solid #1e73be; border-radius: 4px 12px 12px 4px; padding: 20px; text-align: center; width: 100%; box-sizing: border-box; color: #333; font-size: 1.05rem;">
    <strong>Email <a href="mailto:ydcms@pm.me" style="color: #1e73be; text-decoration: none;">ydcms@pm.me</a> for an itinerary and more details.</strong>
  </div>
</section>

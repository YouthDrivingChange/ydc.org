---
layout: default
---

<style>
  /* Fix layout spacing and hide theme clutter */
  header, footer, .sidebar, .project-links, #forkongithub { display: none !important; }
  body { background-color: #f7f9fc; margin: 0; padding: 0; font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif; width: 100%; }
  
  .wrapper { 
    max-width: 100% !important; 
    width: 100% !important;
    margin: 0 !important; 
    padding: 0 !important;
    display: block !important;
  }
  
  section { 
    max-width: 900px !important; 
    width: 90% !important;
    padding: 120px 20px 60px 20px !important; 
    margin: 0 auto !important; 
    float: none !important; 
    clear: both !important;
    display: flex !important;
    flex-direction: column !important;
    align-items: center !important;
    box-sizing: border-box !important;
  }
  
  /* Responsive Centered Top Nav Bar Styling */
  .custom-nav { 
    background-color: white; 
    padding: 20px 20px; 
    border-bottom: 1px solid #eaeaea; 
    display: flex; 
    flex-direction: column;
    align-items: center; 
    gap: 15px;
    position: fixed; 
    top: 0; 
    left: 0; 
    right: 0; 
    z-index: 9999; 
    box-shadow: 0 2px 5px rgba(0,0,0,0.05); 
  }
  .nav-links-container { 
    display: flex; 
    flex-wrap: wrap; 
    justify-content: center; 
    gap: 15px 25px; 
    font-weight: 800; 
    font-size: 0.85rem; 
    letter-spacing: 0.05em; 
    text-align: center;
  }
  .nav-links-container a { color: #333; text-decoration: none; transition: color 0.2s; }
  .nav-links-container a:hover { color: #1e73be; }

  /* Desktop View Layout Adjustment */
  @media (min-width: 850px) {
    .custom-nav {
      flex-direction: row;
      justify-content: space-between;
      padding: 15px 40px;
    }
    section {
      padding-top: 80px !important;
    }
  }

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
    align-items: flex-start;
    gap: 20px;
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
    margin: 0 0 12px 0;
    font-size: 1.05rem;
  }
  .event-contact {
    font-size: 0.95rem;
    color: #333;
    display: block;
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
    display: inline-block;
    transition: background 0.2s, color 0.2s;
  }
  .btn-details:hover {
    background-color: #1e73be;
    color: white;
  }

  @media (max-width: 650px) {
    .event-item { flex-direction: column; }
  }
</style>

<div class="custom-nav">
  <div class="nav-links-container">
    <a href="./index.html">HOME</a>
    <a href="./about.html">ABOUT US</a>
    <a href="./events.html" style="color: #1e73be;">UPCOMING EVENTS</a>
    <a href="./sponsorship.html">SPONSORSHIP</a>
    <a href="./sponsors.html">OUR SPONSORS</a>
    <a href="./newsletter.html">NEWSLETTER</a>
  </div>
  <div>
    <a href="https://events.nationalmssociety.org/teams/ydc" style="background-color: #ff6600; color: white; padding: 10px 28px; text-decoration: none; font-weight: 800; border-radius: 6px; font-size: 0.85rem; display: inline-block; letter-spacing: 0.05em;">DONATE</a>
  </div>
</div>

<section>
  
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
      <div style="padding-right: 20px; width: 100%;">
        <span class="event-date">SEPTEMBER 19 - 20, 2026</span>
        <h4 class="event-title">Bike MS: Historic New Bern Ride</h4>
        <p class="event-description">Our primary campaign event of the year. Featuring scenic coastal architecture and a deep-woods gravel trail experience through Croatan National Forest. All routes kick off from Union Point Park.</p>
        <span class="event-contact"><strong>Email <a href="mailto:ydcms@pm.me" style="color: #1e73be; text-decoration: none;">ydcms@pm.me</a> for an itinerary and more details.</strong></span>
        
        <details style="margin-top: 20px;">
          <summary style="font-weight: 700; color: #1e73be; cursor: pointer; padding: 10px 0; user-select: none; outline: none;">
            Click to View Full Event Details, Schedule & Information
          </summary>
          
          <div style="margin-top: 20px; line-height: 1.6; color: #444; border-top: 1px solid #eee; padding-top: 15px;">
            <h2 style="color: #1e73be; font-size: 1.6rem; border-bottom: 2px solid #eee; padding-bottom: 8px; margin-top: 15px;">Event Schedule</h2>
            
            <h3 style="color: #ff6600; font-size: 1.2rem; margin-top: 20px; margin-bottom: 8px;">Friday, September 18, 2026</h3>
            <p style="margin: 0 0 10px 0;"><strong>9:00 a.m. to 4:00 p.m.</strong> – Optional Educational Seminar <em>(5 North Carolina Insurance Continuing Education credits pending approval)</em><br>
            <strong>Location:</strong> DoubleTree by Hilton Atlantic Beach Oceanfront, 2717 West Fort Macon Road, Atlantic Beach, North Carolina</p>
            
            <h4 style="color: #ff6600; font-size: 1rem; margin-top: 10px; margin-bottom: 5px;">Featured Speakers:</h4>
            <ul style="margin-top: 0; padding-left: 20px;">
              <li>Dr. Gleb Tsipursky – The Psychology of AI Adoption at Work</li>
              <li>Dr. Brenda Wells – Emerging Trends in Insurance</li>
            </ul>
            <p style="font-size: 0.95rem; color: #666; margin-bottom: 15px;"><em>Seminar participants will receive a signed copy of Dr. Tsipursky's newly published book, The Psychology of AI Adoption at Work.</em></p>
            
            <p style="margin: 15px 0 5px 0;"><strong>6:00 p.m.</strong> – Welcome Reception<br>
            <strong>Location:</strong> DoubleTree by Hilton Atlantic Beach Oceanfront, 2717 West Fort Macon Road, Atlantic Beach, North Carolina</p>

            <h3 style="color: #ff6600; font-size: 1.2rem; margin-top: 25px; margin-bottom: 8px;">Saturday, September 19, 2026</h3>
            <h4 style="color: #ff6600; font-size: 1rem; margin-top: 10px; margin-bottom: 5px;">Your Choice:</h4>
            <ul style="margin-top: 0; padding-left: 20px;">
              <li>Bike MS: Historic New Bern Ride featuring 30, 50, 75, and 100 mile routes</li>
              <li>Fishing</li>
              <li>Paint-Along Workshop: Instructor-led session where you create your own keepsake masterpiece</li>
              <li>Coastal tours</li>
              <li>Relaxing day at the beach</li>
            </ul>
            
            <p style="margin: 15px 0 5px 0;"><strong>6:00 p.m.</strong> – Group Dinner at The Dunes Club<br>
            <strong>Location:</strong> 710 E. Fort Macon Rd, Atlantic Beach, NC<br>
            <em>Hosted by Guy Carpenter | Entertainment by DJ David Franks of the Band of Oz</em></p>

            <h3 style="color: #ff6600; font-size: 1.2rem; margin-top: 25px; margin-bottom: 8px;">Sunday, September 20, 2026</h3>
            <p style="margin: 0 0 20px 0;">Return home or enjoy a second day riding in the Bike MS event.</p>

            <h2 style="color: #1e73be; font-size: 1.6rem; border-bottom: 2px solid #eee; padding-bottom: 8px; margin-top: 30px;">Accommodations</h2>
            <p>A block of rooms have been reserved at the DoubleTree by Hilton Atlantic Beach Oceanfront, 2717 West Fort Macon Road, Atlantic Beach, North Carolina. Please contact Annette Alford or me if you would like us to reserve a room in our room block for you.</p>

            <h2 style="color: #1e73be; font-size: 1.6rem; border-bottom: 2px solid #eee; padding-bottom: 8px; margin-top: 30px;">Bike Registration</h2>
            <p>If you would like to participate in Bike MS: Historic New Bern Ride 2026, simply let me know, and we will register you. Bicycles will be provided for guests traveling from out of town.</p>

            <h2 style="color: #1e73be; font-size: 1.6rem; border-bottom: 2px solid #eee; padding-bottom: 8px; margin-top: 30px;">Educational Seminar Speakers</h2>
            <p><strong>Dr. Gleb Tsipursky</strong> is Chief Executive Officer of Disaster Avoidance Experts and a nationally recognized authority on leadership, artificial intelligence, and the future of work. Called the 'Office Whisperer' by The New York Times, he is the author of seven books, including his newly published <em>The Psychology of AI Adoption at Work</em>. His work has been featured in Harvard Business Review, Fortune, Forbes, Inc., Scientific American, and other national publications.</p>
            <p><strong>Dr. Brenda Wells</strong> is the Robert F. Bird Distinguished Professor of Risk Management and Insurance and Chair of the Department of Finance and Insurance at East Carolina University. A nationally respected educator, consultant, and speaker, she has spent nearly four decades teaching risk management and insurance while advising organizations throughout the industry on emerging risks, insurance operations, and market trends.</p>

            <h2 style="color: #1e73be; font-size: 1.6rem; border-bottom: 2px solid #eee; padding-bottom: 8px; margin-top: 30px;">Organizations Represented Last Year</h2>
            <p style="font-size: 0.95rem; color: #555;">Last year's participants represented organizations including Bain & Company, Builders Mutual, Burns & Wilcox, Campbell University, Century 21 Real Estate, Creative Adjusting, Disaster Avoidance Experts, East Carolina University, Elder Research, Experience Design International, Guy Carpenter, Hannover Re, Joyce and Associates, Morgan Stanley, Munich Re, NCJUA and NCIUA, North Carolina Gold Buyers, the North Carolina Department of Agriculture, Nowpreneur, Pinnacle Bank, PIPSO, PNC Bank, ProNavigator, Sanderson High School, Solvrays, UNC Charlotte, the University of New Hampshire, ValueCore, and Verisk (ISO).</p>

            <h2 style="color: #1e73be; font-size: 1.6rem; border-bottom: 2px solid #eee; padding-bottom: 8px; margin-top: 30px;">Travel Information</h2>
            <p>Most attendees drive from within North Carolina. Guests flying to the event may choose from Coastal Carolina Regional Airport in New Bern, approximately 45 minutes from the hotel; Wilmington International Airport, approximately 2 hours away; or Raleigh-Durham International Airport, approximately 3.5 hours away, with a wide selection of nonstop flights. We recommend arriving on Thursday if you plan to attend the educational seminar or on Friday if you will participate only in the weekend activities. Departures are recommended on Sunday or Monday. If your schedule allows, you are also welcome to visit our Raleigh office before or after the weekend.</p>

            <div style="background-color: #f8f9fa; border-left: 4px solid #ff6600; padding: 15px; margin: 25px 0;">
              <h3 style="color: #ff6600; font-size: 1.1rem; margin: 0 0 5px 0;">Please RSVP by August 20</h3>
              <p style="margin: 0;">If you would like to attend, simply let me know by August 20. We will be happy to coordinate your event registration and hotel accommodations.</p>
            </div>

            <h2 style="color: #1e73be; font-size: 1.6rem; border-bottom: 2px solid #eee; padding-bottom: 8px; margin-top: 30px;">Contact Information</h2>
            <p style="margin-bottom: 10px;">
              <strong>Robert Schwitzgebel</strong><br>
              <a href="mailto:wrhardy@pm.me" style="color: #1e73be;">wrhardy@pm.me</a>
            </p>
            <p>
              <strong>Annette Alford</strong><br>
              <a href="mailto:Annette.Alford@ncjua.com" style="color: #1e73be;">Annette.Alford@ncjua.com</a>
            </p>

            <h2 style="color: #1e73be; font-size: 1.6rem; border-bottom: 2px solid #eee; padding-bottom: 8px; margin-top: 30px;">How You Can Help</h2>
            <p>Whether you join us in New Bern or support the effort from afar, I hope you will consider supporting the National Multiple Sclerosis Society. Every contribution helps fund research, advocacy, and programs that improve the lives of people affected by multiple sclerosis.</p>

            <h3 style="color: #ff6600; font-size: 1.2rem; margin-top: 20px; margin-bottom: 8px;">Personal Donations</h3>
            <p style="margin-bottom: 10px;"><strong>Donate online:</strong> <a href="https://events.nationalmssociety.org/teams/ydc" target="_blank" style="color: #1e73be; font-weight: bold;">Donate to Youth Driving Change Team</a></p>
            <p><strong>Donate by Check:</strong><br>
            Checks should be made payable to the <em>National MS Society</em> with <em>'Youth Driving Change'</em> on the memo line and mailed to:</p>
            <blockquote style="margin: 10px 0; padding-left: 15px; border-left: 3px solid #ccc; color: #555;">
              North Carolina Joint Underwriting Association<br>
              Attn: Annette Alford<br>
              751 Corporate Center Drive, Suite 200<br>
              Raleigh, NC 27607
            </blockquote>

            <h3 style="color: #ff6600; font-size: 1.2rem; margin-top: 25px; margin-bottom: 8px;">Corporate Sponsorship Opportunities</h3>
            <p>Organizations and individuals interested in providing additional support may also participate through one of the following sponsorship levels. Corporate sponsorships help advance the team's fundraising efforts in support of the National Multiple Sclerosis Society and demonstrate a shared commitment to improving the lives of people affected by multiple sclerosis.</p>
            <ul style="line-height: 1.8;">
              <li><strong>Legacy Sponsor</strong> — $10,000 and above</li>
              <li><strong>Leadership Sponsor</strong> — $5,000 to $9,999</li>
              <li><strong>Impact Sponsor</strong> — $2,500 to $4,999</li>
              <li><strong>Partner Sponsor</strong> — $1,000 to $2,499</li>
              <li><strong>Friend of the Cause</strong> — Up to $999</li>
            </ul>
            <p style="font-size: 0.95rem; color: #555;">If you are interested in becoming a corporate sponsor or would like to contribute by ACH or wire transfer, please contact Annette Alford or me. We would be happy to discuss sponsorship opportunities and ensure your contribution is properly credited and acknowledged.</p>

            <div style="background-color: #f0f7ff; padding: 20px; border-radius: 8px; margin-top: 25px; text-align: center;">
              <p style="margin: 0; font-size: 1.05rem; color: #333; font-weight: 500;">
                Thank you for your friendship and support. I hope you will join us for a memorable weekend of learning, fellowship, recreation, and service. Together, we can help advance the National Multiple Sclerosis Society's mission and make a meaningful difference in the lives of people affected by multiple sclerosis.
              </p>
            </div>

          </div>
        </details>
      </div>
      <div>
        <a href="https://events.nationalmssociety.org/2736" target="_blank" class="btn-details">Event Details</a>
      </div>
    </div>

    <!-- Event 2: Raleigh Turkey Trot -->
    <div class="event-item">
      <div style="padding-right: 20px; width: 100%;">
        <span class="event-date">NOVEMBER 26, 2026 (THANKSGIVING MORNING)</span>
        <h4 class="event-title">Raleigh Turkey Trot</h4>
        <p class="event-description">Kick off your Thanksgiving morning with the Triangle's favorite holiday tradition. Join us out at Ridgewood Shopping Center to run, walk, and raise critical funds to strike out multiple sclerosis.</p>
        <span class="event-contact"><strong>Email <a href="mailto:ydcms@pm.me" style="color: #1e73be; text-decoration: none;">ydcms@pm.me</a> for an itinerary and more details.</strong></span>
      </div>
      <div>
        <a href="https://ridgewoodturkeytrot.itsyourrace.com/" target="_blank" class="btn-details">Event Details</a>
      </div>
    </div>

  </div>
</section>

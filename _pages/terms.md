---
permalink: /terms/
title: "Terms and Privacy Policy"
modified: 2016-06-06
---
<style>
  /* Basic styling for the team member container */
  .team-container {
    display: flex;
    flex-wrap: wrap; /* Allows cards to wrap to the next line on smaller screens */
    gap: 30px; /* Space between each team member card */
    justify-content: center; /* Centers cards horizontally */
    padding: 20px 0; /* Add some vertical padding */
  }

  /* Styling for individual team member cards */
  .team-member-card {
    display: flex; /* Enables flexbox for image-left, text-right layout */
    align-items: flex-start; /* Aligns content to the top within the card */
    width: 100%; /* Default to full width on very small screens */
    max-width: 700px; /* Max width for each card on larger screens */
    border: 1px solid #e0e0e0;
    border-radius: 8px;
    padding: 20px;
    box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
    background-color: #ffffff;
  }

  /* Wrapper for the image to control its spacing */
  .team-image-wrapper {
    flex-shrink: 0; /* Prevents image from shrinking */
    margin-right: 20px; /* Space to the right of the image */
    text-align: center; /* Centers the image if it's smaller than its container */
  }

  /* Styling for the actual team member image */
  .team-image-wrapper img {
    width: 120px; /* Fixed width for consistent photos */
    height: 120px; /* Fixed height for consistent photos */
    object-fit: cover; /* Ensures images fill the space without distortion */
    border-radius: 50%; /* Makes the images circular */
    border: 3px solid #007bff; /* Accent border color */
    box-shadow: 0 2px 4px rgba(0, 0, 0, 0.15);
  }

  /* Styling for the employee description text */
  .employee-description {
    flex-grow: 1; /* Allows text to take up remaining space */
    color: #333;
  }

  .employee-description h3 {
    margin-top: 0;
    margin-bottom: 5px;
    color: #0056b3;
  }

  .employee-description .role {
    font-weight: bold;
    color: #555;
    margin-bottom: 10px;
    display: block; /* Ensures role is on its own line */
  }

  .employee-description p {
    margin-bottom: 0;
    line-height: 1.5;
  }

  /* Responsive adjustments for smaller screens */
  @media (max-width: 600px) {
    .team-member-card {
      flex-direction: column; /* Stacks image and text vertically */
      align-items: center; /* Centers content when stacked */
      text-align: center; /* Centers text when stacked */
    }

    .team-image-wrapper {
      margin-right: 0; /* Remove right margin when stacked */
      margin-bottom: 15px; /* Add bottom margin for spacing */
    }
  }
</style>

<div class="team-container">

  <div class="team-member-card">
    <div class="team-image-wrapper">
      <img src="https://via.placeholder.com/120/007bff/FFFFFF?text=Jane" alt="Jane Doe - CEO">
    </div>
    <div class="employee-description">
      <h3>Jane Doe</h3>
      <span class="role">Chief Executive Officer (CEO)</span>
      <p>Jane is the visionary behind our success, leading our strategic initiatives and fostering a culture of innovation. With over 15 years in the industry, she's passionate about empowering teams and delivering exceptional results.</p>
    </div>
  </div>

  <div class="team-member-card">
    <div class="team-image-wrapper">
      <img src="https://via.placeholder.com/120/28a745/FFFFFF?text=John" alt="John Smith - CTO">
    </div>
    <div class="employee-description">
      <h3>John Smith</h3>
      <span class="role">Chief Technology Officer (CTO)</span>
      <p>As our CTO, John spearheads all technological advancements, ensuring our platforms are robust, scalable, and secure. He's a true expert in cutting-edge development and infrastructure design.</p>
    </div>
  </div>

  <div class="team-member-card">
    <div class="team-image-wrapper">
      <img src="https://via.placeholder.com/120/ffc107/333333?text=Emily" alt="Emily White - Marketing Director">
    </div>
    <div class="employee-description">
      <h3>Emily White</h3>
      <span class="role">Marketing Director</span>
      <p>Emily drives our brand's voice and market presence. Her innovative marketing strategies and keen understanding of consumer behavior ensure our message resonates deeply with our audience.</p>
    </div>
  </div>

  <div class="team-member-card">
    <div class="team-image-wrapper">
      <img src="https://via.placeholder.com/120/dc3545/FFFFFF?text=David" alt="David Lee - Lead Developer">
    </div>
    <div class="employee-description">
      <h3>David Lee</h3>
      <span class="role">Lead Developer</span>
      <p>David is our go-to for complex coding challenges, consistently delivering high-quality, efficient solutions. He plays a pivotal role in mentoring junior developers and maintaining our core software.</p>
    </div>
  </div>

</div>

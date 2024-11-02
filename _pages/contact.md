---
layout: archive
title: "Contact"
permalink: /contact/
author_profile: true
include_in_list: true
---
<div class="custom-line"></div>

<div class="map-container">
  <iframe
    src="https://www.google.com/maps/embed?pb=!1m14!1m8!1m3!1d11545.909942794027!2d-79.3883586!3d43.6590384!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x882b34c9d7bae5ab%3A0xc9f5c9dba5ec9544!2sToronto%20General%20Hospital!5e0!3m2!1sen!2sca!4v1729889964737!5m2!1sen!2sca"
    frameborder="0"
    allowfullscreen=""
    aria-hidden="false"
    tabindex="0">
  </iframe>
</div>

<!-- Contact Form -->
<form id="contact-form" method="POST" action="https://formspree.io/f/xgvevjlg">
  <div class="form-group">
    <input type="text" id="full-name" name="name" required placeholder="Full Name*">
  </div>
  
  <div class="form-group">
    <input type="email" id="email-address" name="_replyto" required placeholder="Email Address*">
  </div>
  
  <div class="form-group">
    <textarea id="message" name="message" rows="6" required placeholder="Message*"></textarea>
  </div>
  
  <!-- Honeypot field -->
  <input type="text" name="_honeypot" style="display:none">
  
  <!-- Formspree options -->
  
  <button type="submit">Send Message</button>
</form>

<!-- Custom Styles -->
<style>
/* Map Container */
.map-container {
  position: relative;
  padding-bottom: 30%; /* Adjust to make the map taller or shorter */
  height: 0;
  overflow: hidden;
  margin-bottom: 18px;
  border-radius: 15px; /* Rounded corners */
}

.map-container iframe {
  position: absolute;
  top: 0;
  left: 0;
  width: 80%;
  height: 100%;
  border: 0;
  border-radius: 15px; /* Match the container's rounded corners */
}

/* Contact Form Styles */
#contact-form {
  width: 80%; /* Make the form full width */
  max-width: none; /* Remove max-width constraint */
  margin: 0; /* Remove centering */
  text-align: left; /* Ensure text is left-aligned */
}

/* Form Group */
.form-group {
  margin-bottom: 0px;
}

/* Input Fields and Textarea */
#contact-form input,
#contact-form textarea {
  width: 100%;
  padding: 15px;
  border: 1px solid #ccc;
  border-radius: 8px;
  font-size: 16px;
  background-color: #f9f9f9;
  text-align: left; /* Left-align text inside inputs */
}

/* Input Focus Styles */
#contact-form input:focus,
#contact-form textarea:focus {
  border-color: #e74c3c;
  background-color: #fff;
  outline: none;
}

/* Textarea Specific Styles */
#contact-form textarea {
  resize: vertical;
}

/* Placeholder Styling */
#contact-form ::placeholder {
  color: #aaa;
  opacity: 1; /* For Firefox */
}

/* Submit Button Styles */
#contact-form button {
  background-color: #F27380;
  color: #fff;
  padding: 15px 30px;
  border: none;
  border-radius: 8px;
  font-size: 18px;
  cursor: pointer;
  transition: background-color 0.3s ease, transform 0.2s ease;
  text-align: left; /* Left-align button text */
  margin-top: 0px;
}

/* Submit Button Hover and Active States */
#contact-form button:hover {
  background-color: #ED4054;
  transform: translateY(-2px);
}

#contact-form button:active {
  transform: translateY(0);
}
.custom-line {
  width: 4.5%;
  height: 5px; /* Adjust thickness here */
  background-color: #F27380; /* Replace with your specific red color */
  border-radius: 3px; /* Half of the height for fully rounded ends */
  margin: 0px left; /* Space above and below the line */
  margin-top: 0px; /* Space above the line */
  margin-bottom: 16px; /* Space below the line */
} 
</style>
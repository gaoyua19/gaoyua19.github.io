---
layout: archive
title: "Curriculum Vitae"
permalink: /resume/
author_profile: true
redirect_from:
  - /resume
include_in_list: True
---

<div class="custom-line"></div>
<div class="content-wrapper">
Below is a summary of my education/work experience. My CV can be downloaded here:
<div class="button-container">
  <a href="/files/yuangao_cv.pdf" download class="download-button">Download CV</a>
</div>
<p></p>
</div>
<h1>Resume</h1>
<div class="custom-line"></div>
<div class="content-wrapper">
<h2>Education</h2>
<ul><strong>Ph.D. in Medical Biophysics, <span class="location-time">University of Toronto (2021 -- Present)</span></strong></ul>
  <ul2>Deep learning in healthcare monitoring and wearables.</ul2>

<ul><strong>M.Sc. in Pharmacology, <span class="location-time">University of Toronto (2018 -- 2020)</span></strong></ul>
  <ul2>The effects of tobacco smoke and nicotine on lung CYP2A expression.</ul2>

<ul><strong>HB.Sc. in Medical Sciences, <span class="location-time">University of Western Ontario (2014 -- 2018)</span></strong></ul>
  <ul2>Specialization in Interdisciplinary Medical Sciences.</ul2>
<p></p>
<h2>Work Experience</h2>

<ul><strong>Data Analyst, <span class="location-time">University of Toronto Innovation Hub (2019 -- 2020)</span></strong></ul>
  <ul2>Updates and improvements to templates.</ul2>

<ul><strong>Teaching Assistant, <span class="location-time">University of Toronto (2018 -- 2020)</span></strong></ul>
  <ul2>Assisting in course material preparation, conducting lab sessions and tutorials.</ul2>

<ul><strong>Research Assistant, <span class="location-time">Robarts Research Institute, London, Ontario (2017 -- 2018)</span></strong></ul>
  <ul2>Tagging issues and managing research data, and merging pull requests.</ul2>
<p></p>
<h2>Skills<br></h2>
  <ul><strong>Programming Languages:</strong> Python, R, Java, C++, C, SQL, XML, LaTeX<br></ul>
  <ul><strong>Databases:</strong> MySQL, PostgreSQL, Cassandra, MongoDB<br></ul>
  <ul><strong>Machine Learning:</strong> PyTorch, TensorFlow, Scikit-learn<br></ul>
</div>
<style>
/* Custom Line Below the Title */
.custom-line {
  width: 4.5%;
  height: 5px; /* Adjust thickness here */
  background-color: #F27380; /* Replace with your specific accent color */
  border-radius: 3px; /* Half of the height for fully rounded ends */
  margin-top: 0px; /* Space above the line */
  margin-bottom: 20px; /* Space below the line */
}
/* Content Wrapper */
.content-wrapper {
  width: 75%;
  max-width: 1200px; /* Optional: set a maximum width */
  margin: 0 left; /* Center horizontally */
}
/* Differentiate Location and Time */
.location-time {
  color: #F27380; /* Choose a color that complements your theme */
  font-style: strong;
}
/* Reduce the Size of Section Titles */
h2 {
  font-size: 1.3em; /* Adjust as needed */
  margin-top: 0px; 
  margin-bottom: 0px;
}
/* Optional: Improve List Styling */
ul {
  list-style-type: disc;
  padding-left: 20px;
  margin-bottom: 0px;
}
ul li {
  margin-bottom: 8px; /* Reduced spacing between bullet points */
}
ul2 {
  list-style-type: disc;
  padding-left: 40px;
  margin-bottom: 10px;
  margin-top: 0px;
}
ul3 {
  list-style-type: disc;
  padding-left: 20px;
  margin-bottom: 15px;
  margin-top: 1000px;
}
/* Custom Download Button Styling */
.download-button {
  background-color: #F27380;
  color: #fff;
  padding: 15px 30px;
  border: none;
  border-radius: 8px;
  font-size: 18px;
  cursor: pointer;
  transition: background-color 0.3s ease, transform 0.2s ease;
  text-align: center; /* Center-align button text */
  display: inline-block; /* Allow padding and margin */
  text-decoration: none; /* Remove underline */
  margin-top: 20px; /* Space above the button */
  box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1); /* Adds a subtle shadow */
}

/* Hover Effects for the Download Button */
.download-button:hover {
  background-color: #d94b63; /* Darker shade on hover */
  transform: translateY(-3px); /* Slight upward movement */
  box-shadow: 0 6px 8px rgba(0, 0, 0, 0.15); /* Slightly deeper shadow on hover */
}

/* Active Effects for the Download Button */
.download-button:active {
  background-color: #c33f59; /* Even darker shade when clicked */
  transform: translateY(0); /* Reset movement */
  box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1); /* Reset shadow */
}

/* Center the Download Button */
.button-container {
  text-align: left; /* Centers the button within the container */
}

/* Responsive Design Enhancements */
@media (max-width: 600px) {
  .custom-line {
    width: 6%;
  }

  h1 {
    font-size: 1.8em; /* Slightly smaller on mobile */
  }

  .location-time {
    font-size: 0.9em; /* Adjust font size for mobile */
  }

  ul li {
    margin-bottom: 6px; /* Further reduce spacing on mobile */
  }

  .download-button {
    padding: 12px 25px; /* Slightly smaller padding on mobile */
    font-size: 16px; /* Slightly smaller font size on mobile */
    width: 100%; /* Make the button full-width on mobile */
    text-align: center; /* Center-align text */
  }
}
</style>
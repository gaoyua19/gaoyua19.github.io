---
layout: archive
title: "Background"
permalink: /journey/
author_profile: false
include_in_list: false

---
<!-- Custom Line for Consistency -->
<div class="custom-line"></div>
<div class="content-wrapper">
Originally trained in basic sciences, my research journey has equipped me with a multifaceted perspective on any research project. With a strong foundation in basic sciences, clinical research, advanced expertise in genetics and bioinformatics, and training in mathematics, computer programming, and machine learning, I approach research challenges from a interdisciplinary view-point. This unique combination enables me to leverage artificial intelligence effectively, solving complex problems through an integrated lens.
<p></p>
</div>

Journey
======
<div class="custom-line"></div>
<div class="content-wrapper">
  <div class="flowchart-container">
    <!-- Flowchart Step 2: Undergraduate Degree -->
    <div class="flowchart-step">
      <div class="step-content">
        <div class="step-number">2014-2018</div>
        <div class="step-text">
          <p>I completed my <strong>basic science training</strong> at the University of Western Ontario and conducted research under the mentorship of Dr. Donald Welsh. My work focused on blood flow dynamics, allowing me to develop expertise in physiology and translational intersect between physics and medicine.
          </p>
        </div>
      </div>
    </div>
    <!-- Arrow -->
    <div class="arrow-down"></div>
    <div class="flowchart-step">
      <div class="step-content">
        <div class="step-number">2018-2020</div>
        <div class="step-text">
          <p>I earned my Master’s under Dr. Rachel Tyndale at the University of Toronto. I developed expertise in deep genetic sequencing, programming, and statistics. My research focused on gene expression and predicting the impact of rare genetic variants on clinical outcomes, equipping me with valuable <strong> bioinformatics skills </strong> for future challenges.
          </p>
        </div>
      </div>
    </div>
    <!-- Arrow -->
    <div class="arrow-down"></div>
    <div class="flowchart-step">
      <div class="step-content">
        <div class="step-number">2020-2021</div>
        <div class="step-text">
          <p>Motivated to specialize in complex computational modeling, I dedicated 20 months to online courses in machine and deep learning, complemented by university studies in data structures, system programming, and linear algebra. This comprehensive training strengthened my <strong>foundation in mathematics and computer science</strong>.
          </p>
        </div>
      </div>
    </div>
    <!-- Arrow -->
    <div class="arrow-down"></div>
    <div class="flowchart-step">
      <div class="step-content">
        <div class="step-number">2021-Present</div>
        <div class="step-text">
          <p>Motivated to specialize in complex computational modeling, I dedicated 20 months to online courses in machine and deep learning, complemented by university studies in data structures, system programming, and linear algebra. This comprehensive training strengthened my <strong>foundation in mathematics and computer science</strong>.
          </p>
        </div>
      </div>
    </div>
  </div> <!-- End of flowchart-container -->
</div> <!-- End of content-wrapper -->

<!-- Custom Styles -->
<style>
/* Content Wrapper */
.content-wrapper {
  width: 80%;
  max-width: 1200px; /* Optional: set a maximum width */
  margin: 0 left; /* Center horizontally */
}

/* Custom Line Below the Title */
.custom-line {
  width: 4.5%;
  height: 5px; /* Adjust thickness here */
  background-color: #F27380; /* Replace with your specific red color */
  border-radius: 3px; /* Half of the height for fully rounded ends */
  margin-top: 0px; /* Space above the line */
  margin-bottom: 20px; /* Space below the line */
}

/* Flowchart Container */
.flowchart-container {
  display: flex;
  flex-direction: column;
  gap: 30px; /* Space between steps */
}

/* Flowchart Step */
.flowchart-step {
  display: flex;
  align-items: flex-start;
  position: relative;
}

/* Step Content */
.flowchart-step .step-content {
  display: flex;
  align-items: flex-start;
  background-color: #ffffff;
  border-radius: 10px;
  padding: 15px 20px;
  box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
  width: 100%;
  transition: transform 0.3s ease, box-shadow 0.3s ease;
  position: relative; /* To contain the step-number */
}

/* Hover Effects */
.flowchart-step .step-content:hover {
  transform: translateY(-5px);
  box-shadow: 0 8px 15px rgba(0, 0, 0, 0.2);
}
.project-info h5 {
  margin-top: 0;
  margin-bottom: 0px;
  font-size: 1.20em;
}
/* Step Number */
.flowchart-step .step-number {
  background-color: #F27380; /* Accent color */
  color: #ffffff;
  border-radius: 50%;
  width: 150px; /* Increased size */
  height: 150px; /* Increased size */
  display: flex;
  align-items: center;
  justify-content: center;
  font-weight: bold;
  margin-right: 20px;
  margin-top: 15px;
  flex: 0 0 150px; /* Fixed width for the icon column */

}

/* Step Text */
.flowchart-step .step-text {
  flex: 1; /* Take the remaining space */
}

/* Arrow Down */
.arrow-down {
  width: 5px;
  height: 40px; /* Increased height for better visibility */
  background-color: #F27380; /* Same as step-number background */
  margin: 0 auto;
  position: relative;
  border-radius: 3px; /* Half of the height for fully rounded ends */
}

/* Adding Arrowheads using Pseudo-elements */
.arrow-down::after {
  content: '';
  position: absolute;
  top: 80%;
  left: 50%;
  transform: translateX(-50%);
  border-left: 6px solid transparent;
  border-right: 6px solid transparent;
  border-top: 12px solid #F27380; /* Same as arrow color */
}

/* Responsive Design */
@media (max-width: 600px) {
  .content-wrapper {
    width: 95%;
  }
  
  .flowchart-step .step-content {
    flex-direction: column;
    align-items: flex-start;
  }
  
  .flowchart-step .step-number {
    margin-right: 15px;
    width: 40px;
    height: 40px;
    font-size: 1em;
  }
  
  .arrow-down {
    height: 30px;
  }
  
  .arrow-down::after {
    border-left: 5px solid transparent;
    border-right: 5px solid transparent;
    border-top: 10px solid #F27380;
  }
}
</style>

---
permalink: /
title: "Home"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

<style>
@import url('https://fonts.googleapis.com/css2?family=Caveat:wght@400..700&family=Pacifico&display=swap');

* {
  font-family: "Trebuchet MS", Helvetica, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
}

/* Override page layout to use full width */
.page {
  /* width: 100% !important; */
  /* padding-left: 4.23% !important; */
  /* padding-right: 4.23% !important; */
  /* margin-left: 0 !important; */
  /* margin-right: 0 !important; */
  /* float: none !important; */
}

/* #main {
  max-width: 100% !important;
  padding-left: 2em;
  padding-right: 2em;
} */

/* Hide the page title/heading */
.page__title {
  display: none !important;
}

body {
  font-size: 15px;
  line-height: 1.5;
  color: #333;
}

.about-container {
  max-width: 1200px;
  margin: 0 auto;
  padding: 0px;
  font-family: "Trebuchet MS", Helvetica, sans-serif;
  font-size: 16px;
  line-height: 1.65;
  color: #333;
}

.about-header {
  margin-bottom: 40px;
  text-align: left;
}

.about-header h1 {
  font-size: 36px;
  font-weight: 600;
  margin-bottom: 8px;
  color: #222;
  letter-spacing: -0.02em;
}

.about-header .subtitle {
  font-size: 16px;
  color: #666;
  margin-bottom: 20px;
  font-weight: 400;
}

.about-links {
  display: flex;
  gap: 12px;
  margin-top: 20px;
  flex-wrap: wrap;
}

.about-links a {
  display: inline-block;
  padding: 8px 14px;
  background-color: #f5f5f5;
  border-radius: 3px;
  color: #0066cc;
  text-decoration: none;
  font-size: 13px;
  font-weight: 500;
  transition: background-color 0.2s, color 0.2s;
  border: 1px solid #e0e0e0;
}

.about-links a:hover {
  background-color: #ececec;
  text-decoration: none;
}

.about-section {
  margin-bottom: 40px;
}

.about-section h2 {
  font-size: 24px;
  font-weight: 600;
  margin-top: 0px;
  margin-bottom: 16px;
  color: #222;
  border-bottom: 1px solid #e0e0e0;
  padding-bottom: 12px;
  letter-spacing: -0.01em;
}

.about-section p {
  font-size: 15px;
  line-height: 1.75;
  color: #555;
  margin-bottom: 14px;
}

.about-section ul {
  font-size: 15px;
  line-height: 1.75;
  color: #555;
  margin: 15px 0;
  padding-left: 24px;
}

.about-section ul li {
  margin-bottom: 10px;
}

.about-section strong {
  color: #222;
  font-weight: 600;
}

.highlight-box {
  background-color: #f9f9f9;
  padding: 18px 20px;
  border-left: 3px solid #0066cc;
  margin: 25px 0;
  border-radius: 3px;
}

.highlight-box p {
  margin-bottom: 0;
  font-size: 15px;
  line-height: 1.7;
}

a {
  color: #0066cc;
  text-decoration: none;
  transition: color 0.2s;
}

a:hover {
  color: #0052a3;
  text-decoration: none;
}

.quote-box {
  font-style: italic;
  font-size: 16px;
  color: #333;
}

.quote-box p {
  margin-bottom: 12px;
  font-family: "Pacifico", Arial;
}

.quote-author {
  margin-top: 12px;
  font-style: normal;
  font-weight: 500;
  color: #333;
  font-size: 14px;
}

.quote-author::before {
  content: "— ";
}

.project-row {
  display: flex;
  gap: 30px;
  margin-bottom: 40px;
  align-items: flex-start;
}

.project-image-wrapper {
  flex-shrink: 0;
  width: 280px;
  position: relative;
  overflow: hidden;
  border-radius: 6px;
}

.project-image {
  width: 100%;
  border-radius: 6px;
  display: block;
  transition: opacity 0.4s ease-in-out;
}

.project-image-primary {
  position: relative;
  z-index: 2;
}

.project-image-secondary {
  position: absolute;
  top: 0;
  left: 0;
  width: 100%;
  opacity: 0;
  z-index: 1;
}

.project-image-wrapper:hover .project-image-primary {
  opacity: 0;
}

.project-image-wrapper:hover .project-image-secondary {
  opacity: 1;
}

.project-content {
  flex: 1;
  min-width: 0;
}

.project-title {
  font-size: 17px;
  font-weight: 600;
  margin: 0 0 8px 0;
  color: #222;
  line-height: 1.4;
}

.project-links {
  margin: 8px 0 12px 0;
  font-size: 14px;
}

.project-links a {
  margin-right: 12px;
}

.project-description {
  color: #555;
  font-size: 15px;
  margin-bottom: 10px;
  line-height: 1.6;
}

.project-points {
  list-style: none;
  padding: 0;
  margin: 0;
}

.project-points li {
  font-size: 14px;
  line-height: 1.6;
  color: #555;
  margin-bottom: 6px;
  padding-left: 18px;
  position: relative;
}

.project-points li::before {
  content: "•";
  position: absolute;
  left: 0;
  color: #0066cc;
  font-weight: bold;
}

@media (max-width: 768px) {
  .project-row {
    flex-direction: column;
    gap: 15px;
  }
  
  .project-image-wrapper {
    width: 100%;
  }
}
</style>

<div class="about-container">
  <!-- <div class="about-header">
    <h1>Tanvir Redoy</h1>
    <div class="subtitle">PhD Student in Computer Science at Baylor University</div>
  </div> -->
  <div class="about-section" id="about">
    <h2>About</h2>
    <p>
      I am currently a Ph.D. Student in Computer Science at Baylor University, glad and greateful to be advised by <a href="https://acfreeman.dev">Dr. Andrew Freeman</a>. Prior to that, I obtained my B.Sc. degree in Computer Science and Engineering from Rajshahi University of Engineering and Technology (RUET), under the supervision of <a href="https://www.cse.ruet.ac.bd/kmzahir61">Md. Zahirul Islam</a>.
    </p>
    <p>
      My research interests include <strong>Video Streaming & Compression, Neural Video Coding, Computer Vision, Networking, Generative AI</strong>. I am passionate about developing novel approaches to solve complex problems in my field.
    </p>
    <p>
      Traveling, Photography, and Filmmaking—this combination makes feel me refreshed.
    </p>
  </div>
  <div class="about-section" id="news">
    <h2>🎯 News</h2>
    <ul>
      <li><strong>Dec, 2025</strong> — Preparing a research publication in collaboration with international researchers.</li>
      <li><strong>Nov, 2025</strong> — Reproduced a MoQ-based point-cloud live streaming system and extended it into a complete VV-DASH workflow.</li>
      <li><strong>Oct, 2025</strong> — Built out complete evaluation pipelines for neural codecs like DCVC-RT.</li>
      <li><strong>Sept, 2025</strong> — Analyzing emerging Neural Video Codecs (such as C3, NEVC-1.0, Cool-Chic).</li>
      <li><strong>Aug, 2025</strong> — Started Ph.D. in Computer Science at Baylor University.</li>
    </ul>
  </div>
  <div class="highlight-box quote-box" id="quote">
    <p>"My Boy, Life is Good, Life is Beautiful, Life is Simple."</p>
    <div class="quote-author">Rezaul Karim, Dept. of Mathematics, Notre Dame College</div>
  </div>
  <!-- <div class="about-section" id="research">
    <h2>Research Focus</h2>
    <p>
      My research spans multiple areas within [field]. I focus on:
    </p>
    <ul style="color: #555; line-height: 1.8;">
      <li><strong>Area 1:</strong> Brief description of your research in this area.</li>
      <li><strong>Area 2:</strong> Brief description of your research in this area.</li>
      <li><strong>Area 3:</strong> Brief description of your research in this area.</li>
    </ul>
  </div> -->
  <!-- <div class="highlight-box">
    <p>
      <strong>📋 For more details:</strong> 
      Check out my <a href="#portfolio">portfolio</a>, 
      <a href="#publications">publications</a>, or 
      <a href="#cv">CV</a>.
    </p>
  </div> -->
  <div class="about-section" id="research_projects">
    <h2>Research Projects</h2>
    <!-- Project 1 -->
    <div class="project-row">
      <div class="project-image-wrapper">
        <img src="../images/rd_curve_Bosphorus_v3.png" alt="RD curve for Seq. Bosphorus" class="project-image project-image-primary">
        <img src="../images/Bosphorus_hevc_qp42_vmaf71.9.png" alt="Visual repr. of a frame from Seq. Bosphorus" class="project-image project-image-secondary">
      </div>
      <div class="project-content">
        <h3 class="project-title">DCVC-RT vs HEVC/AV1 Efficiency Benchmarking</h3>
        <div class="project-links">
          <a href="https://github.com/tanvir-redoy/DCVC-RT-vs-HEVC-AV1-Efficiency-Benchmarking.git">Code</a>
        </div>
        <p class="project-description">Evaluation pipelines to compare traditional codecs with neural codecs, focusing on BD-rate, complexity, and real-time feasibility.</p>
        <!-- <ul class="project-points">
          <li>.</li>
        </ul> -->
      </div>
    </div>    
    <!-- Project 2 -->
    <div class="project-row">
      <div class="project-image-wrapper">
        <img src="../images/noseg.png" alt="Project 2" class="project-image project-image-primary">
        <img src="../images/seg.png" alt="Project 2 Alt" class="project-image project-image-secondary">
      </div>
      <div class="project-content">
        <h3 class="project-title">Point Cloud Live Streaming—MoQ vs DASH</h3>
        <div class="project-links">
          <a href="https://arxiv.org/abs/2507.15673">Paper (arXiv)</a>
        </div>
        <p class="project-description">Latency driven MoQ-based point cloud live streaming pipeline, and performance comparison against VV-DASH architecture.</p>
        <!-- <ul class="project-points">
          <li>.</li>
        </ul> -->
      </div>
    </div>
    <!-- Project 3 -->
    <div class="project-row">
      <div class="project-image-wrapper">
        <img src="../images/CTU_partitioning_vehicles_UM.PNG" alt="Project 3" class="project-image project-image-primary">
        <img src="../images/Cub-256.png" alt="Project 3 Alt" class="project-image project-image-secondary">
      </div>
      <div class="project-content">
        <h3 class="project-title">Cuboidal Image Map utilization to generate CUs partition decisions</h3>
        <div class="project-links">
          <a href="https://ieeexplore.ieee.org/abstract/document/10869620">Paper</a> / <a href="https://github.com/tanvir-redoy/CUBOIDAL-image-map-procesisng-to-generate-CUs-partition-decisions">Code</a>
        </div>
        <p class="project-description">Modification of VVC encoder (VTM-20.2) pipeline to bypass expensive RDO stages and integrate algorithm-generated predictions.</p>
        <!-- <ul class="project-points">
          <li></li>
        </ul> -->
      </div>
    </div>
    <!-- Project 4 -->
    <!-- <div class="project-row">
      <div class="project-image-wrapper">
        <img src="/images/project3.jpg" alt="Project 4" class="project-image project-image-primary">
        <img src="/images/project3-alt.jpg" alt="Project 4 Alt" class="project-image project-image-secondary">
      </div>
      <div class="project-content">
        <h3 class="project-title">Project Title 4</h3>
        <div class="project-links">
          <a href="#">Project Page</a> / <a href="#">Paper</a> / <a href="#">Code</a>
        </div>
        <p class="project-description">Brief description of the project and its significance.</p>
        <ul class="project-points">
          <li>Key feature or finding of the project</li>
          <li>Technical approach or methodology used</li>
          <li>Impact or results achieved</li>
        </ul>
      </div>
    </div> -->
  </div>
  <div class="about-section" id="publications">
    <h2>📝 Selected Publications</h2>
    <!-- <p>Highlights from my recent publications. Full list available below.</p> -->
    <ul>
      <li><strong>[ACM NOSSDAV 2026, (Under Review)]</strong> A. C. Freeman, M. Rudolph, <strong>T. A. Redoy</strong>, F. Schnier, H. Hassler, S. Afzal, A. Rizk. <a href="https://arxiv.org/abs/2507.15673">Point Cloud Streaming with Latency-Driven Implicit Adaptation using MoQ</a></li>
      <li><strong>[IEEE DICTA 2024]</strong> M. Z. Islam, <strong>T. A. Redoy</strong>, A. Ahmmed, M. Paul, M. Murshed. <a href="https://ieeexplore.ieee.org/abstract/document/10869620">Leveraging the Cuboidal Partitioning for Low Complexity CTU Structure Prediction in Versatile Video Coding</a></li>
    </ul>
    <p><a href="https://scholar.google.com/citations?hl=en&user=_nnDhe4AAAAJ">View full publications →</a></p>
  </div>
  <!-- <div class="about-section" id="talks">
    <h2>Talks</h2>
    <p>Selected talks and presentations.</p>
    <p><a href="/talks/">View talks →</a></p>
  </div> -->
  <div class="about-section" id="teaching">
    <h2>Teaching</h2>
    <div class="portfolio-meta">Lecturer | Dept. of CSE, Daffodil International University, Dhaka, Bangladesh
      <ul>
        <li>Jan, 2025 - April, 2025: Compiler Design (CSE331, CSE332), Artificial Intelligence Lab (CSE412), Theory of Computation (CSE228).</li>
        <li>May, 2025 - July, 2025: Object Oriented Programming with Java (CSE221, CSE222).</li>
      </ul>
    </div>
    <p><a href="https://sites.google.com/view/tanvirahmedredoy/teaching">View teaching videos →</a></p>
  </div>
  <!-- <div class="about-section" id="portfolio">
    <h2>Portfolio</h2>
    <p>Selected projects and case studies.</p>
    <p><a href="/portfolio/">View portfolio →</a></p>
  </div> -->
  <div class="about-section" id="awards">
    <h2>🏆 Awards & Honors</h2>
    <ul>
      <li>Prime Minister Cub-Scout Award [1st position nationwide], Bangladesh Scouts.</li>
      <li>1st in 8th semester, GPA: 4.00, Dept. of CSE, RUET.</li>
      <li>100% Attendance Certificate, Notre Dame College, Dhaka.</li>
      <li>Education Board scholarships e.g., HSC, SSC.</li>
    </ul>
    <p><a href="https://sites.google.com/view/tanvirahmedredoy/awards">View photos →</a></p>
  </div>
  <!-- <div class="about-section" id="blog">
    <h2>Blog Posts</h2>
    <p>Notes and articles.</p>
    <p><a href="/year-archive/">View blog →</a></p>
  </div> -->
  <!-- <div class="about-section" id="cv">
    <h2>CV</h2>
    <p>Download my CV for a detailed overview.</p>
    <p><a href="/cv/">View CV →</a></p>
  </div> -->
</div>

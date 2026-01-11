---
permalink: /
title: "Home"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

<style>
* {
  font-family: "Trebuchet MS", Helvetica, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
}

body {
  font-size: 15px;
  line-height: 1.5;
  color: #333;
}

.about-container {
  max-width: 800px;
  margin: 0 auto;
  padding: 40px 20px;
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
  background-color: #fafafa;
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
</style>

<div class="about-container">
  <div class="about-header">
    <h1>Your Name</h1>
    <div class="subtitle">Your Affiliation / University</div>
    <div class="about-links">
      <a href="mailto:your.email@example.com">Email</a>
      <a href="#">LinkedIn</a>
      <a href="#">Google Scholar</a>
      <a href="#">GitHub</a>
    </div>
  </div>

  <div class="about-section">
    <h2>About</h2>
    <p>
      Welcome to my academic portfolio. I am a researcher and scholar focused on [your research area]. 
      Currently, I am [your position] at [your institution].
    </p>
    <p>
      My research interests include [interest 1], [interest 2], and [interest 3]. I am passionate about 
      developing novel approaches to solve complex problems in my field.
    </p>
  </div>

  <div class="about-section">
    <h2>Research Focus</h2>
    <p>
      My research spans multiple areas within [field]. I focus on:
    </p>
    <ul>
      <li><strong>Area 1:</strong> Brief description of your research in this area.</li>
      <li><strong>Area 2:</strong> Brief description of your research in this area.</li>
      <li><strong>Area 3:</strong> Brief description of your research in this area.</li>
    </ul>
  </div>

  <div class="highlight-box">
    <p>
      <strong>📋 For more details:</strong> 
      Check out my <a href="/portfolio/">portfolio</a>, 
      <a href="/publications/">publications</a>, or 
      <a href="/cv/">CV</a>.
    </p>
  </div>
</div>

<div class="about-container">
  <div class="about-header">
    <h1>Your Name</h1>
    <div class="subtitle">Your Affiliation / University</div>
    <div class="about-links">
      <a href="mailto:your.email@example.com">Email</a>
      <a href="#">LinkedIn</a>
      <a href="#">Google Scholar</a>
      <a href="#">GitHub</a>
    </div>
  </div>

  <div class="about-section">
    <h2>About</h2>
    <p>
      Welcome to my academic portfolio. I am a researcher and scholar focused on [your research area]. 
      Currently, I am [your position] at [your institution].
    </p>
    <p>
      My research interests include [interest 1], [interest 2], and [interest 3]. I am passionate about 
      developing novel approaches to solve complex problems in my field.
    </p>
  </div>

  <div class="about-section">
    <h2>Research Focus</h2>
    <p>
      My research spans multiple areas within [field]. I focus on:
    </p>
    <ul style="color: #555; line-height: 1.8;">
      <li><strong>Area 1:</strong> Brief description of your research in this area.</li>
      <li><strong>Area 2:</strong> Brief description of your research in this area.</li>
      <li><strong>Area 3:</strong> Brief description of your research in this area.</li>
    </ul>
  </div>

  <div class="highlight-box">
    <p>
      <strong>📋 For more details:</strong> 
      Check out my <a href="/portfolio/">portfolio</a>, 
      <a href="/publications/">publications</a>, or 
      <a href="/cv/">CV</a>.
    </p>
  </div>
</div>
1. Upload any files (like PDFs, .zip files, etc.) to the files/ directory. They will appear at https://[your GitHub username].github.io/files/example.pdf.  
1. Check status by going to the repository settings, in the "GitHub pages" section

Site-wide configuration
------
The main configuration file for the site is in the base directory in [_config.yml](https://github.com/academicpages/academicpages.github.io/blob/master/_config.yml), which defines the content in the sidebars and other site-wide features. You will need to replace the default variables with ones about yourself and your site's github repository. The configuration file for the top menu is in [_data/navigation.yml](https://github.com/academicpages/academicpages.github.io/blob/master/_data/navigation.yml). For example, if you don't have a portfolio or blog posts, you can remove those items from that navigation.yml file to remove them from the header. 

Create content & metadata
------
For site content, there is one Markdown file for each type of content, which are stored in directories like _publications, _talks, _posts, _teaching, or _pages. For example, each talk is a Markdown file in the [_talks directory](https://github.com/academicpages/academicpages.github.io/tree/master/_talks). At the top of each Markdown file is structured data in YAML about the talk, which the theme will parse to do lots of cool stuff. The same structured data about a talk is used to generate the list of talks on the [Talks page](https://academicpages.github.io/talks), each [individual page](https://academicpages.github.io/talks/2012-03-01-talk-1) for specific talks, the talks section for the [CV page](https://academicpages.github.io/cv), and the [map of places you've given a talk](https://academicpages.github.io/talkmap.html) (if you run this [python file](https://github.com/academicpages/academicpages.github.io/blob/master/talkmap.py) or [Jupyter notebook](https://github.com/academicpages/academicpages.github.io/blob/master/talkmap.ipynb), which creates the HTML for the map based on the contents of the _talks directory).

**Markdown generator**

The repository includes [a set of Jupyter notebooks](https://github.com/academicpages/academicpages.github.io/tree/master/markdown_generator
) that converts a CSV containing structured data about talks or presentations into individual Markdown files that will be properly formatted for the Academic Pages template. The sample CSVs in that directory are the ones I used to create my own personal website at stuartgeiger.com. My usual workflow is that I keep a spreadsheet of my publications and talks, then run the code in these notebooks to generate the Markdown files, then commit and push them to the GitHub repository.

How to edit your site's GitHub repository
------
Many people use a git client to create files on their local computer and then push them to GitHub's servers. If you are not familiar with git, you can directly edit these configuration and Markdown files directly in the github.com interface. Navigate to a file (like [this one](https://github.com/academicpages/academicpages.github.io/blob/master/_talks/2012-03-01-talk-1.md) and click the pencil icon in the top right of the content preview (to the right of the "Raw | Blame | History" buttons). You can delete a file by clicking the trashcan icon to the right of the pencil icon. You can also create new files or upload files by navigating to a directory and clicking the "Create new file" or "Upload files" buttons. 

Example: editing a Markdown file for a talk
![Editing a Markdown file for a talk](/images/editing-talk.png)

For more info
------
More info about configuring Academic Pages can be found in [the guide](https://academicpages.github.io/markdown/), the [growing wiki](https://github.com/academicpages/academicpages.github.io/wiki), and you can always [ask a question on GitHub](https://github.com/academicpages/academicpages.github.io/discussions). The [guides for the Minimal Mistakes theme](https://mmistakes.github.io/minimal-mistakes/docs/configuration/) (which this theme was forked from) might also be helpful.

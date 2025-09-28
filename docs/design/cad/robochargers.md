title: RoboChargers CAD Class
<div id="lesson-id" data-lesson-id="robochargers"></div>
<h1 class="lesson-title">CAD 3005</h1>
<p class="lesson-subtitle">
  <a href="/design/cad/" class="lesson-back-inline">← Back to Lesson Overview</a>
</p>


<div class="lesson-article">

  <h2><strong>Introduction</strong></h2>

  <p>The CAD 3005 course is created by <strong>FRC Team 3005 - The RoboChargers</strong> and is specifically designed to teach CAD skills that are directly applicable to FRC robotics. This course focuses on practical, hands-on learning through video tutorials and real FRC examples.</p>



<div class="red-line"></div>

<div class="header-w-button">
  <h2><strong>Getting Started</strong></h2>
  <a href="https://www.youtube.com/playlist?list=PLYpOH7Nj2lA0SV_2x0zKpuOj3U2YGgRW4" target="_blank" rel="noopener noreferrer" class="article-button">
    Access Course
  </a>
</div>

<p>The course is structured as a YouTube playlist with multiple modules, each building on the previous lessons. You'll start with the basics of Onshape in an FRC context and work your way up to designing complete robot mechanisms.</p>

<p><strong>Prerequisites:</strong> Make sure you have an Onshape account set up with your Westtown email address. If you need help with this, check out our <a href="/design/cad/whatis/">What is CAD?</a> lesson.</p>

<div style="margin-top: 2rem;"></div>



<div class="red-line"></div>

<h2><strong>Course Modules</strong></h2>

<p>The course is divided into several modules that progressively build your FRC CAD skills:</p>

<div style="margin-top: 2rem;"></div>

<ul id="cad3005-progress-list" class="progress-list">
  <li data-id="cad3005-module-1"><strong>Module 1:</strong> Onshape Basics for FRC</li>
  <li data-id="cad3005-module-2"><strong>Module 2:</strong> Working with FRC Parts Libraries</li>
  <li data-id="cad3005-module-3"><strong>Module 3:</strong> Drivetrain Design Fundamentals</li>
  <li data-id="cad3005-module-4"><strong>Module 4:</strong> Mechanism Design Principles</li>
  <li data-id="cad3005-module-5"><strong>Module 5:</strong> Assembly Techniques</li>
  <li data-id="cad3005-module-6"><strong>Module 6:</strong> Robot Layout and Packaging</li>
  <li data-id="cad3005-module-7"><strong>Module 7:</strong> Design for Manufacturing</li>
  <li data-id="cad3005-module-8"><strong>Module 8:</strong> Advanced FRC Mechanisms</li>
</ul>

<div class="red-line"></div>

<h2><strong>Learning Tips</strong></h2>

<p>To get the most out of this course:</p>

<ul>
  <li><strong>Follow Along:</strong> Open Onshape in a separate tab and replicate what you see in the videos</li>
  <li><strong>Take Notes:</strong> Write down keyboard shortcuts and important design principles</li>
  <li><strong>Practice:</strong> Try to recreate mechanisms from memory after watching each lesson</li>
</ul>

<div style="margin-top: 2rem;"></div>


<div class="red-line"></div>


<h2><strong>Next Steps</strong></h2>

<p>After completing CAD 3005, you'll have the fundamental skills needed to contribute to FRC robot design. Consider exploring:</p>

<ul>
  <li>The <strong><a href="/design/cad/frcdesign/">FRCDesign.org</a></strong> course for more advanced techniques</li>
  <li>Our <strong><a href="/design/mini/">Mini Projects</a></strong> section to practice your new skills</li>
</ul>

<div style="margin-top: 3rem;"></div>

</div>

<button id="finish-lesson" class="completed-lesson-button">
  Finish Lesson
</button>

<script>
  const listItems = document.querySelectorAll('#cad3005-progress-list li');

  listItems.forEach(item => {
    const id = item.dataset.id;

    // Restore saved progress
    if (localStorage.getItem(id) === 'true') {
      item.classList.add('completed');
    }

    // Toggle completion on click
    item.addEventListener('click', () => {
      item.classList.toggle('completed');
      const isComplete = item.classList.contains('completed');
      localStorage.setItem(id, isComplete);
    });
  });
</script>
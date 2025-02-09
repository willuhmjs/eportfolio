<style>
  .jumbotron {
    max-width: 100%;
    height: 700px;
    background-image: url('/wide_will.png');
    background-size: cover;
    background-position: center;
    display: flex;
    align-items: center;
    padding: 20px;
    box-shadow: inset 0 -60px 60px -20px rgba(0, 0, 0, 0.3);
    justify-content: center;
    text-align: center;
    background-color: rgba(50, 50, 50, 0.8);
  }
  .jumbotron-text {
    max-width: 50%;
    color: #2c3e50;
  }

  .jumbotron-text h1 {
    font-size: 3.5rem;
    margin-bottom: 20px;
  }

  .jumbotron-text > *:not(h1) {
    font-size: 1.6rem;
  }

  .content {
    padding: 20px;
    max-width: 1200px;
    margin: 0 auto;
    overflow: hidden;
    background-color: #f9f9f9;
    border-radius: 8px;
  }
  .content h2 {
    margin-top: 20px;
    font-size: 2em;
    color: #16a085;
  }
  .content ul {
    list-style-type: disc;
    padding-left: 20px;
    margin-bottom: 20px;
  }
  .content p, .content li {
    line-height: 1.6;
    font-size: 1.1rem; 
    color: #7f8c8d;
  }
  .experience-container {
    display: flex;
    flex-wrap: wrap;
    gap: 20px;
  }
  .experience-card {
    flex: 1;
    min-width: 250px;
    border: 1px solid #ddd;
    border-radius: 8px;
    padding: 20px;
    margin-bottom: 20px;
    box-shadow: 0 2px 4px rgba(0, 0, 0, 0.1);
    background-color: #fff;
  }
  .experience-card h3 {
    margin-top: 0;
    color: #2c3e50;
  }
  .certifications-container {
    display: flex;
    flex-wrap: wrap;
    gap: 20px;
  }
  .certification-card {
    flex: 1;
    min-width: 250px;
    border: 1px solid #ddd;
    border-radius: 8px;
    padding: 20px;
    margin-bottom: 20px;
    box-shadow: 0 2px 4px rgba(0, 0, 0, 0.1);
    background-color: #fff;
  }
  .certification-card h3 {
    margin-top: 0;
    color: #2c3e50;
  }
</style>

<div class="jumbotron">
  <div class="jumbotron-text">
    <h1>William Faircloth</h1>
    <h2>Cybersecurity E-Portfolio</h2>
  </div>
</div>

<div class="content">
  <h2>About Me</h2>
  <p>I am a full-stack developer and cybersecurity student with a decade of software development experience. I hold CompTIA Security+ and GIAC Foundational Cybersecurity Technologies (GFACT) certifications and specialize in Node.js, TypeScript, Python, C#, and web frameworks like SvelteKit. Currently studying Cybersecurity & Computer Science at Old Dominion University, I maintain an active <a href="https://github.com/willuhmjs" target="_blank">GitHub portfolio</a> with over 100 projects. </p>
  <h2>Experience</h2>
  <div class="experience-container">
    <div class="experience-card">
      <h3>IT Consultant at Old Dominion University</h3>
      <p><em>Aug 2024 - Present</em></p>
    </div>
    <div class="experience-card">
      <h3>Web Developer at Old Dominion University Research Foundation</h3>
      <p><em>Oct 2024 - Dec 2024</em></p>
    </div>
    <div class="experience-card">
      <h3>Software Development Intern at AERMOR</h3>
      <p><em>Jun 2024 - Aug 2024</em></p>
    </div>
  </div>
  <h2>Licenses & Certifications</h2>
  <div class="certifications-container">
    <div class="certification-card">
      <h3>CompTIA Security+</h3>
      <p><em>Issued May 2024</em></p>
    </div>
    <div class="certification-card">
      <h3>GIAC Foundational Cybersecurity Technologies</h3>
      <p><em>Credential ID 3868</em></p>
    </div>
  </div>
</div>

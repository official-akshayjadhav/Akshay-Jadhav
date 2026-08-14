<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<style>
  @page {
    size: A4;
    margin: 20mm 24mm;
    background-color: #ffffff;
  }

  body {
    font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, Helvetica, Arial, sans-serif, "Apple Color Emoji", "Segoe UI Emoji", "Segoe UI Symbol";
    font-size: 11.5pt;
    line-height: 1.65;
    color: #111111;
    margin: 0;
    padding: 0;
  }

  /* Header / Navigation Bar */
  .site-header {
    margin-bottom: 40px;
    padding-bottom: 12px;
    border-bottom: 1px solid #eaeaea;
  }

  .site-title {
    font-size: 16pt;
    font-weight: 700;
    letter-spacing: -0.3px;
    margin: 0 0 8px 0;
    color: #000000;
  }

  .site-nav {
    font-size: 10pt;
    color: #666666;
  }

  .site-nav a {
    color: #555555;
    text-decoration: none;
    margin-right: 18px;
  }

  /* Main Title Section */
  .page-title {
    font-size: 24pt;
    font-weight: 800;
    letter-spacing: -0.6px;
    margin: 0 0 24px 0;
    color: #000000;
  }

  /* Typography & Prose */
  p {
    margin: 0 0 18px 0;
    color: #222222;
  }

  p.intro {
    font-size: 13pt;
    line-height: 1.6;
    color: #333333;
    margin-bottom: 24px;
  }

  h2 {
    font-size: 14pt;
    font-weight: 700;
    letter-spacing: -0.2px;
    margin: 32px 0 12px 0;
    padding-bottom: 4px;
    color: #000000;
    page-break-after: avoid;
  }

  /* Links style matching Steph Ango's minimal underline style */
  a {
    color: #000000;
    text-decoration: underline;
    text-underline-offset: 3px;
    text-decoration-color: #bbbbbb;
  }

  /* Experience / Work list */
  .work-item {
    margin-bottom: 22px;
  }

  .work-header {
    margin-bottom: 4px;
  }

  .work-title {
    font-weight: 700;
    color: #000000;
  }

  .work-company {
    font-weight: 600;
    color: #333333;
  }

  .work-date {
    font-size: 9.5pt;
    color: #777777;
    margin-left: 6px;
  }

  .work-desc {
    margin-top: 4px;
    font-size: 10.5pt;
    color: #444444;
  }

  ul.bullet-list {
    margin: 6px 0 16px 0;
    padding-left: 18px;
  }

  ul.bullet-list li {
    margin-bottom: 6px;
    font-size: 10.5pt;
    color: #333333;
  }

  /* Highlight box for key tech / stack */
  .tech-tag {
    display: inline-block;
    background: #f4f4f5;
    border-radius: 4px;
    padding: 2px 7px;
    font-size: 9.5pt;
    font-family: SFMono-Regular, Consolas, "Liberation Mono", Menlo, monospace;
    color: #333333;
    margin-right: 4px;
    margin-bottom: 6px;
  }

  /* Footer / Contact block */
  .contact-section {
    margin-top: 40px;
    padding-top: 20px;
    border-top: 1px solid #eaeaea;
    font-size: 10pt;
    color: #666666;
  }

  .contact-section a {
    margin-right: 15px;
  }
</style>
</head>
<body>

  <!-- Minimal Header Bar -->
  <div class="site-header">
    <div class="site-title">Akshay Jadhav</div>
    <div class="site-nav">
      <a href="#">About</a>
      <a href="#">Projects</a>
      <a href="#">Writing</a>
      <a href="#">Contact</a>
    </div>
  </div>

  <!-- Page Content -->
  <div class="page-title">About</div>

  <p class="intro">
    I am a Blockchain Developer and Software Engineer with 6 years of experience building institutional tokenization protocols, distributed systems, and LLM-powered backends. Based in Pune, India.
  </p>

  <p>
    Currently, I work as a <strong>Blockchain Developer at UBS</strong>, where I engineer high-throughput smart contract infrastructure for institutional finance—including <strong>UMINT</strong> (UBS USD Money Market Investment Fund Token) on Ethereum/EVM networks. My focus spans EVM architecture, zero-vulnerability contract security, and bridging decentralized finance (DeFi) with enterprise core banking systems.
  </p>

  <p>
    Previously, I developed LLM multi-agent systems and FinOps automation modules at <strong>Amdocs</strong>, and built scalable microservice APIs for enterprise data lakes at <strong>Tata Consultancy Services (TCS)</strong>.
  </p>

  <h2>Focus & Expertise</h2>
  <p>
    My work sits at the intersection of Web3 smart contract design, automated compliance (ERC-3643 / ERC-20), high-volume transaction optimization, and AI backend integration.
  </p>

  <div style="margin-bottom: 20px;">
    <span class="tech-tag">Solidity</span>
    <span class="tech-tag">Ethereum / EVM</span>
    <span class="tech-tag">ERC-3643</span>
    <span class="tech-tag">Foundry</span>
    <span class="tech-tag">Hardhat</span>
    <span class="tech-tag">TypeScript</span>
    <span class="tech-tag">Go (Golang)</span>
    <span class="tech-tag">Python (FastAPI)</span>
    <span class="tech-tag">LangChain</span>
    <span class="tech-tag">Docker / K8s</span>
  </div>

  <h2>Selected Experience</h2>

  <div class="work-item">
    <div class="work-header">
      <span class="work-company">UBS</span> — <span class="work-title">Blockchain Developer</span>
      <span class="work-date">(Oct 2024 — Present)</span>
    </div>
    <ul class="bullet-list">
      <li>Engineered compliant ERC-20 / ERC-3643 smart contracts for UMINT (UBS USD Money Market Fund Tokenization).</li>
      <li>Architected backend integration pipelines connecting smart contract events with core institutional banking infrastructure.</li>
      <li>Implemented automated security & audit pipelines using Foundry, Hardhat, Slither, and Mythril to guarantee zero-vulnerability deployments.</li>
    </ul>
  </div>

  <div class="work-item">
    <div class="work-header">
      <span class="work-company">Amdocs</span> — <span class="work-title">Software Engineer</span>
      <span class="work-date">(Jun 2022 — Sep 2024)</span>
    </div>
    <ul class="bullet-list">
      <li>Spearheaded <i>Doxana</i>, an LLM-based multi-agent system supporting 50+ custom operational agents that cut resolution time by 35%.</li>
      <li>Built AI-driven cost anomaly detection modules for cloud FinOps, reducing manual monitoring efforts by 50%.</li>
    </ul>
  </div>

  <div class="work-item">
    <div class="work-header">
      <span class="work-company">Tata Consultancy Services</span> — <span class="work-title">Software Engineer</span>
      <span class="work-date">(Feb 2021 — Jun 2022)</span>
    </div>
    <ul class="bullet-list">
      <li>Built high-throughput microservices handling real-time data streaming for UPS Capital data pipelines.</li>
    </ul>
  </div>

  <h2>Education & Certifications</h2>
  <p>
    <strong>B.E. in Computer Science</strong> — Pune University (2017 – 2020)<br>
    <strong>DeFi Specialization</strong> — Duke University<br>
    <strong>AWS Certified Solutions Architect</strong> & <strong>AWS Certified Developer</strong>
  </p>

  <!-- Contact / Footer -->
  <div class="contact-section">
    <strong>Connect:</strong>
    <a href="mailto:akshayj9809@gmail.com">Email</a>
    <a href="https://linkedin.com/in/akshayj9809" target="_blank">LinkedIn</a>
    <a href="https://github.com/akshayj9809" target="_blank">GitHub</a>
  </div>

</body>
</html>

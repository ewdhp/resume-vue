
<template>
  <main class="resume-container">
     <!-- Header Section -->
    <section class="resume-header">
  <h1 class="resume-name">Your Name</h1>
  <div class="resume-title">Software Engineer</div>
      <div class="resume-contact">
        <span>Email: your.email@example.com</span> |
        <span><a href="https://linkedin.com/in/yourprofile" target="_blank">LinkedIn</a></span> |
        <span><a href="https://github.com/your-github" target="_blank">GitHub</a></span>
      </div>
    </section>

      <!-- Professional Summary Section -->
      <section class="resume-professional-summary">
        <h2>Professional Summary</h2>
        <p>
          Machine Learning Engineer with hands-on expertise in building scalable web, backend, and data-driven systems. Proven track record developing decentralized game backends, advanced image and NLP pipelines, authentication platforms, and enterprise-grade servers using modern frameworks and cloud-native technologies.
            Skilled in .NET Core, C#, Node.js, Vue.js, React, Motoko, and Python for full-stack and AI development; experienced with REST APIs, OAuth, Passport.js for secure authentication; and proficient in Docker, Kubernetes, and decentralized infrastructure.
        </p>

      </section>
   
    <section class="resume-experience">
      <h2>Experience</h2>
      <ul>
        <li>
          <strong>COSMICRAFTS</strong>:
          A decentralized game backend built on ICP, featuring user management, missions, matchmaking, statistics, achievements, and NFT/token standards. Designed for scalable Web3 gaming experiences with secure, modular architecture.
        </li>
        <li>
          <strong>IMAGE-PROCESSING</strong>:
          A Python pipeline for image and computer vision tasks, including 2D-to-3D transformation, perspective correction, stereo vision, clustering, and segmentation. Configurable via JSON phase files for automated, multi-step workflows.
        </li>
        <li>
          <strong>LOGIN-PROVIDERS</strong>:
          A basic Node.js/Express authentication backend supporting dynamic routing for multiple OAuth and social login strategies. Uses Passport.js for modular, secure user authentication in web and cloud applications.
        </li>
        <li>
          <strong>MSERVER</strong>:
          A .NET Core backend server providing secure HTTPS and WebSocket (WSS) connections, SSH integration, graph-based workflow and task processing, and Docker deployment. Built for scalable, real-time enterprise applications.
        </li>
        <li>
          <strong>NLP-PIPELINE</strong>:
          A configurable Python NLP pipeline for advanced text analysis, supporting recursive multi-stage processing, dynamic function integration, and JSON-based configuration. Supports keyword extraction, document classification, and automated reporting.
        </li>
        <li>
          <strong>PYTHON-AI</strong>:
          Comprehensive collection of Python AI and machine learning algorithms, including HMMs, Markov models, RNNs, transformers, and mathematical utilities. Covers NLP, sequence modeling, probabilistic reasoning, and advanced math for research and applied AI solutions. Organized for experimentation, prototyping, and educational use.
        </li>
        <li>
          <strong>REACT_NODES</strong>:
          A modular React application for interactive graph visualization and node-based workflows. Features 2D/3D graph rendering, integrated terminal with SSH capability, code editor, and flexible component architecture for rapid prototyping and data exploration.
        </li>
        <li>
          <strong>VIEWPATH</strong>:
          A dynamic view navigation system built with Vue.js and Motoko, managed by DFX. Supports modular UI composition with dynamic injection of components for onboarding tours, guided navigation, and interactive user journeys in decentralized applications.
        </li>
      </ul>
      </section>
  </main>

</template>

<style scoped>
.resume-container {
  max-width: 700px;
  margin: 2rem auto;
  padding: 2rem;
  background: #fff;
  border-radius: 12px;
  box-shadow: 0 2px 16px rgba(0,0,0,0.08);
}
section {
  margin-bottom: 2rem;
}
h2 {
  font-size: 1.5rem;
  font-weight: bold;
  margin-bottom: 1rem;
}

.resume-header {
  text-align: center;
  margin-bottom: 2rem;
}
.resume-name {
  font-size: 2.5rem;
  font-weight: 700;
  margin-bottom: 0.5rem;
}

.resume-experience strong {
  font-weight: bold;
  color: #464545;

  letter-spacing: 0.5px;
}
.resume-title {
  font-size: 1.25rem;
  font-weight: 500;
  margin-bottom: 0.5rem;
  margin-top: -0.5rem;
  color: #555;
}
.resume-contact {
  font-size: 1rem;
  color: #555;
}
.resume-summary {
  margin-bottom: 2rem;
}
.resume-summary h2 {
  font-size: 1.3rem;
  margin-bottom: 0.5rem;
}

</style>

---
layout: default
title: Home
description: Copy and update human consciousness and memory to the digital world.
---
<style>
  .hero-video-bg {
    position: relative;
    overflow: hidden;
    min-height: 600px;
    display: flex;
    align-items: center;
  }
  .hero-video-bg video {
    position: absolute;
    top: 50%;
    left: 50%;
    min-width: 100%;
    min-height: 100%;
    width: auto;
    height: auto;
    transform: translate(-50%, -50%);
    z-index: 0;
    object-fit: cover;
  }
  .hero-video-bg::after {
    content: '';
    position: absolute;
    inset: 0;
    background: rgba(10, 13, 46, 0.65);
    z-index: 1;
    pointer-events: none;
  }
  .hero-video-bg .container {
    position: relative;
    z-index: 2;
    text-align: center;
  }
</style>
<header class="hero hero-video-bg">
  <video autoplay muted loop playsinline>
    <source src="{{ '/assets/background-video.mp4' | relative_url }}" type="video/mp4">
    <source src="{{ '/assets/background-video.webm' | relative_url }}" type="video/webm">
    Your browser does not support the video tag.
  </video>
  <div class="container">
    <span class="badge">Consciousness Digitalization</span>
    <h1>Spirit Connect Science and Technology</h1>
    <p class="lead">
      We are pioneering the future of human consciousness preservation. Our mission is to copy and update human consciousness 
      and memory to the digital world, creating a bridge between the physical and digital realms. Experience immortality through 
      technology that captures the essence of who you are.
    </p>
    <div class="hero-actions">
      <a class="btn btn-primary" href="{{ '/contact/' | relative_url }}">Get Started</a>
      <a class="btn btn-ghost" href="{{ '/products/cabin-sc1/' | relative_url }}">Explore Products</a>
    </div>
  </div>
</header>

<section class="section section-featured">
  <div class="container">
    <div class="section-header">
      <span class="section-badge">OUR TECHNOLOGY</span>
      <h2>Revolutionary Products for Memory Upload</h2>
      <p class="lead">
        Our cutting-edge hardware solutions enable the transfer of human consciousness and memories into the digital realm. 
        Experience the future of human existence through our innovative products.
      </p>
    </div>
    <div class="grid grid-featured">
      <div class="card card-featured">
        <div class="card-icon">🧠</div>
        <h3>Cabin SC1</h3>
        <p>Advanced consciousness transfer system designed for seamless memory upload and digital preservation of human consciousness.</p>
        <a href="{{ '/products/cabin-sc1/' | relative_url }}" class="card-link">Learn More →</a>
      </div>
      <div class="card card-featured">
        <div class="card-icon">📽️</div>
        <h3>3D Projector</h3>
        <p>State-of-the-art projection technology that visualizes and interacts with digitized consciousness in immersive 3D environments.</p>
        <a href="{{ '/products/3d-projector/' | relative_url }}" class="card-link">Learn More →</a>
      </div>
      <div class="card card-featured">
        <div class="card-icon">🌐</div>
        <h3>Another World</h3>
        <p>A virtual reality real-time immersive game where digitized consciousness can exist, interact, and thrive in a digital universe.</p>
        <a href="{{ '/another-world/' | relative_url }}" class="card-link">Explore →</a>
      </div>
    </div>
  </div>
</section>

<section class="section">
  <div class="container">
    <h2>How It Works</h2>
    <p class="lead">Our revolutionary technology captures and preserves the essence of human consciousness through advanced neural mapping and digital transfer processes.</p>
    <div class="grid">
      <div class="card">
        <h3>Neural Mapping</h3>
        <p>Advanced scanning technology maps your neural pathways, capturing every memory, thought pattern, and aspect of your consciousness.</p>
      </div>
      <div class="card">
        <h3>Memory Extraction</h3>
        <p>Sophisticated algorithms extract and digitize your memories, experiences, and personality traits with unprecedented accuracy.</p>
      </div>
      <div class="card">
        <h3>Digital Transfer</h3>
        <p>Seamless upload process transfers your consciousness to secure digital storage, preserving your essence for eternity.</p>
      </div>
      <div class="card">
        <h3>Consciousness Update</h3>
        <p>Continuous synchronization keeps your digital consciousness updated with new experiences and memories from the physical world.</p>
      </div>
      <div class="card">
        <h3>Virtual Existence</h3>
        <p>Your digitized consciousness can exist, interact, and evolve in virtual environments like Another World.</p>
      </div>
      <div class="card">
        <h3>Immortal Preservation</h3>
        <p>Your consciousness is preserved indefinitely, ensuring that your memories, thoughts, and essence never fade away.</p>
      </div>
    </div>
  </div>
</section>

<section class="section section-case-study">
  <div class="container">
    <div class="case-study-content">
      <div class="case-study-text">
        <span class="section-badge">EXPERIENCE THE FUTURE</span>
        <h2>Another World</h2>
        <p class="lead">
          Step into a virtual reality real-time immersive game where digitized consciousness comes alive. 
          Another World is not just a game—it's a new dimension where your digital self can explore, 
          interact, and create in ways never before possible.
        </p>
        <div class="case-study-actions">
          <a href="{{ '/another-world/' | relative_url }}" class="btn btn-primary">Enter Another World</a>
          <a href="{{ '/products/cabin-sc1/' | relative_url }}" class="btn btn-ghost">Learn About Upload</a>
        </div>
      </div>
      <div class="case-study-visual">
        <div class="visual-placeholder">
          <img src="{{ '/images/anotherworld/ao.PNG' | relative_url }}" alt="Another World" style="max-width: 60%; height: auto; border-radius: var(--radius);">
        </div>
      </div>
    </div>
  </div>
</section>

<section class="section section-solution">
  <div class="container">
    <div class="solution-content">
      <div class="solution-visual">
        <div class="visual-placeholder">
          <img src="{{ '/images/anotherworld/humanexistence.png' | relative_url }}" alt="Human Existence" style="max-width: 60%; height: auto; border-radius: var(--radius);">
        </div>
      </div>
      <div class="solution-text">
        <h2>The Future of Human Existence</h2>
        <p class="lead">
          At Spirit Connect Science and Technology, we believe that consciousness is not bound by physical limitations. 
          Our revolutionary technology allows you to transcend the boundaries of time and space, preserving your essence 
          in the digital realm where you can continue to grow, learn, and exist indefinitely.
        </p>
      </div>
    </div>
  </div>
</section>

<section class="section section-cta">
  <div class="container">
    <div class="cta-content">
      <h2>Ready to Begin Your Digital Journey?</h2>
      <p class="lead">
        Take the first step towards digital immortality. Contact us to learn more about our consciousness 
        transfer technology and how you can preserve your memories and essence in the digital world.
      </p>
      <a href="{{ '/contact/' | relative_url }}" class="btn btn-primary btn-large">Get In Touch</a>
    </div>
  </div>
</section>

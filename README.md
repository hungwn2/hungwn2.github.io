<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <meta name="description" content="Henry Hung — Electrical Engineering student focused on embedded systems, firmware, and low-level software." />
  <meta name="theme-color" content="#0b1220" />
  <title>Henry Hung | Embedded Systems & Firmware</title>
  <link rel="icon" type="image/svg+xml" href="assets/favicon.svg" />
  <link rel="stylesheet" href="style.css" />
</head>
<body>
  <div class="page-shell">
    <header class="site-header">
      <a class="brand" href="#home" aria-label="Henry Hung — Home">
        <span class="brand-mark" aria-hidden="true">H<span>.</span></span>
        <span>Henry Hung</span>
      </a>
      <nav aria-label="Main navigation">
        <a href="#about">About</a>
        <a href="#projects">Projects</a>
        <a href="#contact">Contact</a>
      </nav>
    </header>

    <main id="home">
      <section class="hero" aria-labelledby="hero-title">
        <p class="eyebrow"><span class="status-dot" aria-hidden="true"></span> ELECTRICAL ENGINEERING · UNIVERSITY OF WATERLOO</p>
        <h1 id="hero-title">Embedded Systems<br /><span>&amp; Firmware.</span></h1>
        <p class="hero-description">
          I build software close to the hardware — from microcontroller firmware
          to RISC-V operating systems and device drivers.
        </p>
        <div class="hero-actions">
          <a class="button button-primary" href="#projects">Explore projects <span aria-hidden="true">↗</span></a>
          <!-- Replace YOUR_USERNAME with your GitHub username. -->
          <a class="button button-outline" href="https://github.com/YOUR_USERNAME" target="_blank" rel="noopener noreferrer">GitHub profile <span aria-hidden="true">↗</span></a>
        </div>
      </section>

      <section class="projects section" id="projects" aria-labelledby="projects-title">
        <div class="section-heading">
          <div>
            <p class="section-kicker">SELECTED WORK</p>
            <h2 id="projects-title">Featured projects<span class="accent">.</span></h2>
          </div>
          <p>Hardware, software, and everything in between.</p>
        </div>

        <div class="project-grid">
          <article class="project-card">
            <div class="project-image">
              <img src="assets/riscv-board.svg" alt="Stylized illustration of a RISC-V development board with a microprocessor and circuit traces" />
              <span class="image-label">01 / OPERATING SYSTEMS</span>
            </div>
            <div class="project-content">
              <div class="project-meta"><span>RISC-V</span><span>C</span><span>OS DEVELOPMENT</span></div>
              <h3>xv6 on Allwinner D1</h3>
              <p>Bringing the xv6 teaching operating system to a real RISC-V board, including memory mapping, UART bring-up, and low-level device support.</p>
              <!-- Replace href with the corresponding project repository. -->
              <a class="project-link" href="https://github.com/YOUR_USERNAME" target="_blank" rel="noopener noreferrer">View on GitHub <span aria-hidden="true">↗</span></a>
            </div>
          </article>

          <article class="project-card">
            <div class="project-image">
              <img src="assets/stm32-board.svg" alt="Stylized illustration of a microcontroller development board with PCB traces and pin headers" />
              <span class="image-label">02 / EMBEDDED FIRMWARE</span>
            </div>
            <div class="project-content">
              <div class="project-meta"><span>STM32</span><span>C</span><span>FIRMWARE</span></div>
              <h3>STM32 Firmware &amp; Drivers</h3>
              <p>Firmware update workflows, flash partition handling, and embedded communication drivers spanning I²C, RS-485, and CAN.</p>
              <a class="project-link" href="https://github.com/YOUR_USERNAME" target="_blank" rel="noopener noreferrer">View on GitHub <span aria-hidden="true">↗</span></a>
            </div>
          </article>
        </div>
      </section>

      <section class="about section" id="about" aria-labelledby="about-title">
        <div>
          <p class="section-kicker">A LITTLE ABOUT ME</p>
          <h2 id="about-title">Curious about what happens <span class="accent">under the hood.</span></h2>
        </div>
        <div class="about-copy">
          <p>I'm an Electrical Engineering student at the University of Waterloo with an interest in embedded software, computer architecture, and hands-on hardware development.</p>
          <p>I enjoy understanding systems from the register level up — building drivers, debugging peripherals, and figuring out how operating systems interact with real hardware.</p>
          <div class="skill-list" aria-label="Technical interests">
            <span>Embedded C/C++</span><span>STM32</span><span>RISC-V</span><span>Linux</span><span>RTOS</span><span>PCB Design</span>
          </div>
        </div>
      </section>

      <section class="contact section" id="contact" aria-labelledby="contact-title">
        <p class="section-kicker">GET IN TOUCH</p>
        <h2 id="contact-title">Have something in mind?</h2>
        <p>I'm always interested in embedded systems, firmware, and hardware-software projects.</p>
        <div class="contact-actions">
          <!-- Replace with your actual email address. -->
          <a class="button button-primary" href="mailto:YOUR_EMAIL@example.com">Email me <span aria-hidden="true">↗</span></a>
          <a class="button button-outline" href="https://github.com/YOUR_USERNAME" target="_blank" rel="noopener noreferrer">Find me on GitHub <span aria-hidden="true">↗</span></a>
        </div>
      </section>
    </main>

    <footer class="site-footer">
      <span>© <span id="copyright-year">2026</span> Henry Hung</span>
      <span>Built with HTML &amp; CSS · Hosted on GitHub Pages</span>
    </footer>
  </div>
  <script>
    document.getElementById('copyright-year').textContent = new Date().getFullYear();
  </script>
</body>
</html>

<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <meta name="description" content="Portfolio of Bach Nguyen, a front-end developer creating thoughtful and responsive digital experiences.">
  <title>Bach Nguyen | Front-End Developer</title>
  <link rel="stylesheet" href="styles.css">
</head>
<body>
  <a class="skip-link" href="#main">Skip to main content</a>

  <header class="site-header" id="siteHeader">
    <nav class="navbar" aria-label="Main navigation">
      <a class="brand" href="#home" aria-label="Bach Nguyen, home">
        <span class="brand-mark">BN</span>
        <span>
          <span class="brand-name">Bach Nguyen</span>
          <span class="brand-role">Front-End Developer</span>
        </span>
      </a>

      <ul class="nav-links" id="navLinks">
        <li><a href="#home" class="active">Home</a></li>
        <li><a href="#about">About</a></li>
        <li><a href="#projects">Projects</a></li>
        <li><a href="#skills">Skills</a></li>
        <li><a href="#contact">Contact</a></li>
      </ul>

      <div class="nav-actions">
        <button class="icon-button theme-toggle" id="themeToggle" type="button" aria-label="Switch to dark mode">
          <svg class="sun-icon" viewBox="0 0 24 24" aria-hidden="true">
            <circle cx="12" cy="12" r="4"></circle>
            <path d="M12 2v2M12 20v2M4.93 4.93l1.42 1.42M17.66 17.66l1.41 1.41M2 12h2M20 12h2M4.93 19.07l1.42-1.42M17.66 6.34l1.41-1.41"></path>
          </svg>
          <svg class="moon-icon" viewBox="0 0 24 24" aria-hidden="true">
            <path d="M21 12.79A9 9 0 1 1 11.21 3 7 7 0 0 0 21 12.79Z"></path>
          </svg>
        </button>
        <button class="icon-button menu-toggle" id="menuToggle" type="button" aria-label="Open navigation menu" aria-expanded="false">
          <span></span><span></span><span></span>
        </button>
      </div>
    </nav>
  </header>

  <main id="main">
    <section class="hero section" id="home">
      <div class="hero-content reveal">
        <div class="availability"><span></span> Available for new opportunities</div>
        <p class="eyebrow">Hello, I'm Bach Nguyen</p>
        <h1>Building digital experiences that feel <span>effortless.</span></h1>
        <p class="hero-text">
          I am a computer science student and front-end developer focused on clean interfaces, thoughtful interactions, and websites that work beautifully on every screen.
        </p>

        <div class="hero-actions">
          <a href="#projects" class="btn primary">
            Explore my work
            <svg viewBox="0 0 24 24" aria-hidden="true"><path d="m9 18 6-6-6-6"></path></svg>
          </a>
          <a href="#contact" class="btn secondary">Let's talk</a>
        </div>

        <div class="hero-metrics" aria-label="Portfolio highlights">
          <div><strong>3+</strong><span>Featured projects</span></div>
          <div><strong>4</strong><span>Core technologies</span></div>
          <div><strong>100%</strong><span>Responsive layouts</span></div>
        </div>
      </div>

      <div class="hero-visual reveal" aria-label="Developer profile illustration">
        <div class="visual-orbit orbit-one"></div>
        <div class="visual-orbit orbit-two"></div>
        <div class="portrait-card">
          <div class="portrait-top">
            <span class="window-dots"><i></i><i></i><i></i></span>
            <span>portfolio.js</span>
          </div>
          <div class="avatar" aria-hidden="true">
            <span>BN</span>
          </div>
          <div class="code-lines" aria-hidden="true">
            <span><i></i></span><span><i></i></span><span><i></i></span>
          </div>
          <div class="profile-chip">
            <span class="chip-icon">&lt;/&gt;</span>
            <span><strong>Front-End</strong><small>Crafting with care</small></span>
          </div>
        </div>
        <div class="floating-tag tag-one">Responsive</div>
        <div class="floating-tag tag-two">Accessible</div>
      </div>
    </section>

    <section class="trust-strip" aria-label="Development principles">
      <div>
        <span>Semantic HTML</span><i></i>
        <span>Modern CSS</span><i></i>
        <span>Vanilla JavaScript</span><i></i>
        <span>Mobile First</span><i></i>
        <span>Accessible UI</span>
      </div>
    </section>

    <section class="section about-section" id="about">
      <div class="section-intro reveal">
        <p class="section-label">About me</p>
        <h2>Curious by nature.<br>Intentional by design.</h2>
      </div>
      <div class="about-content reveal">
        <p class="lead">
          I turn ideas into clear, responsive interfaces where every detail has a purpose.
        </p>
        <p>
          I am currently growing my front-end development skills through hands-on projects. I enjoy the space where design and code meet: translating visual ideas into accessible experiences that feel fast, polished, and easy to use.
        </p>
        <div class="principle-grid">
          <article>
            <span>01</span>
            <h3>Thoughtful design</h3>
            <p>Clear hierarchy, purposeful spacing, and visual decisions that support the content.</p>
          </article>
          <article>
            <span>02</span>
            <h3>Solid foundations</h3>
            <p>Semantic markup, maintainable styles, and interactions built with progressive enhancement.</p>
          </article>
        </div>
      </div>
    </section>

    <section class="projects-section" id="projects">
      <div class="section section-heading reveal">
        <div>
          <p class="section-label">Selected work</p>
          <h2>Projects built with purpose</h2>
        </div>
        <p>A small collection of responsive concepts focused on useful experiences and careful visual systems.</p>
      </div>

      <div class="section project-list">
        <article class="project-card reveal">
          <div class="project-image travel">
            <span class="project-number">01</span>
            <div class="browser-frame" aria-hidden="true">
              <div class="browser-bar"><i></i><i></i><i></i></div>
              <div class="travel-mockup">
                <span>EXPLORE</span>
                <strong>Find your next<br>great escape.</strong>
                <button tabindex="-1">Discover places</button>
              </div>
            </div>
          </div>
          <div class="project-body">
            <div>
              <span class="project-type">Travel platform</span>
              <h3>Travel Explorer</h3>
            </div>
            <p>A destination discovery experience with immersive imagery, clear trip categories, and a layout designed to inspire exploration.</p>
            <div class="project-footer">
              <ul><li>HTML</li><li>CSS</li><li>JavaScript</li></ul>
              <a href="#contact" aria-label="Ask about Travel Explorer">
                View project
                <svg viewBox="0 0 24 24" aria-hidden="true"><path d="M5 12h14M13 6l6 6-6 6"></path></svg>
              </a>
            </div>
          </div>
        </article>

        <article class="project-card reverse reveal">
          <div class="project-image task">
            <span class="project-number">02</span>
            <div class="task-mockup" aria-hidden="true">
              <div class="task-sidebar"><b>T.</b><i></i><i></i><i></i></div>
              <div class="task-board">
                <small>MONDAY, JUNE 16</small>
                <strong>Good morning, Bach.</strong>
                <div class="task-row done"><i></i><span>Review project brief</span></div>
                <div class="task-row"><i></i><span>Design landing page</span></div>
                <div class="task-row"><i></i><span>Build responsive layout</span></div>
              </div>
            </div>
          </div>
          <div class="project-body">
            <div>
              <span class="project-type">Productivity app</span>
              <h3>Focus Task Manager</h3>
            </div>
            <p>A calm workspace for organizing daily priorities, reducing visual clutter, and keeping progress visible at a glance.</p>
            <div class="project-footer">
              <ul><li>UI Design</li><li>CSS Grid</li><li>JavaScript</li></ul>
              <a href="#contact" aria-label="Ask about Focus Task Manager">
                View project
                <svg viewBox="0 0 24 24" aria-hidden="true"><path d="M5 12h14M13 6l6 6-6 6"></path></svg>
              </a>
            </div>
          </div>
        </article>

        <article class="project-card reveal">
          <div class="project-image recipe">
            <span class="project-number">03</span>
            <div class="recipe-card" aria-hidden="true">
              <span>WEEKEND KITCHEN</span>
              <strong>Fresh pasta,<br>made simple.</strong>
              <div><i></i><small>25 min</small><i></i><small>Easy</small></div>
            </div>
          </div>
          <div class="project-body">
            <div>
              <span class="project-type">Recipe discovery</span>
              <h3>Weekend Kitchen</h3>
            </div>
            <p>A warm, editorial recipe finder that makes browsing meals feel inviting while keeping ingredients and preparation easy to scan.</p>
            <div class="project-footer">
              <ul><li>Responsive UI</li><li>Typography</li><li>Interaction</li></ul>
              <a href="#contact" aria-label="Ask about Weekend Kitchen">
                View project
                <svg viewBox="0 0 24 24" aria-hidden="true"><path d="M5 12h14M13 6l6 6-6 6"></path></svg>
              </a>
            </div>
          </div>
        </article>
      </div>
    </section>

    <section class="section skills-section" id="skills">
      <div class="skills-copy reveal">
        <p class="section-label">Skills & approach</p>
        <h2>The tools behind the details</h2>
        <p>I build from a strong web foundation, pairing clean code with a practical eye for layout, usability, and responsive behavior.</p>
        <a href="#contact" class="text-link">
          Start a conversation
          <svg viewBox="0 0 24 24" aria-hidden="true"><path d="M5 12h14M13 6l6 6-6 6"></path></svg>
        </a>
      </div>

      <div class="skills-panel reveal">
        <div class="skill">
          <div class="skill-info"><span>HTML & accessibility</span><span>95%</span></div>
          <div class="progress"><span style="--width:95%"></span></div>
        </div>
        <div class="skill">
          <div class="skill-info"><span>CSS & visual systems</span><span>90%</span></div>
          <div class="progress"><span style="--width:90%"></span></div>
        </div>
        <div class="skill">
          <div class="skill-info"><span>JavaScript interactions</span><span>80%</span></div>
          <div class="progress"><span style="--width:80%"></span></div>
        </div>
        <div class="skill">
          <div class="skill-info"><span>Responsive design</span><span>95%</span></div>
          <div class="progress"><span style="--width:95%"></span></div>
        </div>
        <div class="feature-pills" aria-label="Interactive features">
          <span>Theme toggle</span><span>Mobile navigation</span><span>Lightbox gallery</span><span>Testimonial slider</span>
        </div>
      </div>
    </section>

    <section class="gallery-section" id="gallery">
      <div class="section section-heading reveal">
        <div>
          <p class="section-label">Visual journal</p>
          <h2>Details that inspire me</h2>
        </div>
        <p>A collection of places, spaces, and textures. Select an image for a closer look.</p>
      </div>
      <div class="section gallery-grid reveal">
        <button class="gallery-item mountain" data-title="Desert mountains" aria-label="Open desert mountains image"><span>Landscape</span></button>
        <button class="gallery-item desk" data-title="Creative workspace" aria-label="Open creative workspace image"><span>Workspace</span></button>
        <button class="gallery-item bridge" data-title="Golden Gate Bridge" aria-label="Open Golden Gate Bridge image"><span>Architecture</span></button>
        <button class="gallery-item coast" data-title="Quiet coastline" aria-label="Open quiet coastline image"><span>Travel</span></button>
      </div>
    </section>

    <section class="section testimonial-section" id="testimonials">
      <p class="section-label reveal">Kind words</p>
      <div class="testimonial-card reveal">
        <svg class="quote-mark" viewBox="0 0 64 48" aria-hidden="true"><path d="M0 48V28C0 9.3 9.3 0 28 0v10c-8 0-12.7 3.7-14 11H28v27H0Zm36 0V28C36 9.3 45.3 0 64 0v10c-8 0-12.7 3.7-14 11h14v27H36Z"></path></svg>
        <div class="testimonial-content">
          <p id="testimonialText">"Bach created a clean and responsive design. The website is easy to use and looks professional."</p>
          <div>
            <strong id="testimonialName">Linh Tran</strong>
            <span id="testimonialRole">UI/UX Designer</span>
          </div>
        </div>
        <div class="slider-controls">
          <button class="slider-btn" id="prevTestimonial" type="button" aria-label="Previous testimonial">
            <svg viewBox="0 0 24 24" aria-hidden="true"><path d="m15 18-6-6 6-6"></path></svg>
          </button>
          <span id="testimonialCount">01 / 03</span>
          <button class="slider-btn" id="nextTestimonial" type="button" aria-label="Next testimonial">
            <svg viewBox="0 0 24 24" aria-hidden="true"><path d="m9 18 6-6-6-6"></path></svg>
          </button>
        </div>
      </div>
    </section>

    <section class="contact-section" id="contact">
      <div class="section contact-grid">
        <div class="contact-copy reveal">
          <p class="section-label">Get in touch</p>
          <h2>Have an idea?<br><span>Let's make it real.</span></h2>
          <p>Whether it is a new website, a thoughtful redesign, or simply a conversation about the web, I would love to hear from you.</p>
          <div class="contact-details">
            <a href="mailto:bachnguyen@example.com"><small>Email</small><strong>bachnguyen@example.com</strong></a>
            <div><small>Based in</small><strong>Hanoi, Vietnam</strong></div>
          </div>
        </div>

        <form class="contact-form reveal" id="contactForm">
          <div class="form-row">
            <label for="name">Your name</label>
            <input id="name" name="name" type="text" placeholder="Bach Nguyen" required>
          </div>
          <div class="form-row">
            <label for="email">Email address</label>
            <input id="email" name="email" type="email" placeholder="hello@example.com" required>
          </div>
          <div class="form-row">
            <label for="message">Tell me about your project</label>
            <textarea id="message" name="message" rows="5" placeholder="A few details about your idea..." required></textarea>
          </div>
          <button type="submit" class="btn primary">
            Send message
            <svg viewBox="0 0 24 24" aria-hidden="true"><path d="M22 2 11 13M22 2l-7 20-4-9-9-4 20-7Z"></path></svg>
          </button>
          <p class="form-status" id="formStatus" role="status"></p>
        </form>
      </div>
    </section>
  </main>

  <div class="lightbox" id="lightbox" role="dialog" aria-modal="true" aria-labelledby="lightboxTitle" aria-hidden="true">
    <div class="lightbox-content">
      <button id="closeLightbox" type="button" aria-label="Close image preview">
        <svg viewBox="0 0 24 24" aria-hidden="true"><path d="M18 6 6 18M6 6l12 12"></path></svg>
      </button>
      <div id="lightboxImage" class="lightbox-image"></div>
      <p id="lightboxTitle"></p>
    </div>
  </div>

  <footer class="footer">
    <div class="footer-inner">
      <a class="brand footer-brand" href="#home">
        <span class="brand-mark">BN</span>
        <span class="brand-name">Bach Nguyen</span>
      </a>
      <p>Designed and built with care.</p>
      <p>&copy; <span id="currentYear">2026</span> Bach Nguyen</p>
    </div>
  </footer>

  <script src="script.js"></script>
</body>
</html>

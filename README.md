- **Hosted at:** [https://devagnihotri.github.io/Candles/](https://devagnihotri.github.io/Candles/)

---

### Tech Stack Analysis

**1. Core Technologies:**
- **HTML5**: The project’s structure and layout are defined in HTML, primarily in `index.html`.
- **CSS3**: Custom styling is implemented via a dedicated `style.css` and embedded styles in `index.html`. Features include:
  - Responsive design using media queries
  - CSS animations (float, wiggle, sparkle)
  - Modern techniques like custom properties (CSS variables)

**2. JavaScript:**
- **Vanilla JavaScript**: The interactive functionality (carousel, games, UI behaviors) is handled using plain JavaScript in `script.js` and inline scripts.
- **Third-party Libraries:**
  - **GSAP (GreenSock Animation Platform)**: Included via CDN for advanced animations and scroll-triggered effects (`gsap.min.js` and `ScrollTrigger.min.js`).

**3. Assets:**
- **Images**: Several images are used for slideshows and decorative effects (e.g., `1.jpeg`, `WELCOME TO (1).png`).
- **Audio**: Background music is embedded using the `<audio>` element, with streaming from SoundCloud.

**4. UI Features:**
- **3D Carousel**: Inspired by or adapted from open source work, rendered with DOM/CSS transforms, controlled by custom JS.
- **Slider/Carousel**: Custom-built slider with navigation and touch support.
- **Game Elements**: Candle lighting game with interactive scoring.
- **Responsive & Modern UI**: Uses CSS variables, gradients, and fluid layouts for visual appeal across devices.

**5. No Build Tools or Frameworks:**
- The project does not use React, Vue, Angular, or any build tool like Webpack, Vite, or Babel. It’s straightforward HTML/CSS/JS.

**6. Deployment:**
- **GitHub Pages**: The site is deployed via GitHub Pages, making use of the `gh-pages` branch (or the root for user/organization pages).

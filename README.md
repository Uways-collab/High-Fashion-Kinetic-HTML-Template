ÈKÓ — Lagos Metamorphosis

ÈKÓ is a brutalist, motion-driven, high-fashion website template inspired by the raw kinetic energy of modern Lagos. Designed for fashion houses, streetwear brands, and creative studios, this single-page showcase leverages cutting-edge web performance and smooth, scroll-driven animations.

✨ Features

Kinetic Hero Typography: Elastic character-staggering text reveals built using GSAP.

Scroll-Driven Transformations: Smooth scale-and-fade video hero container powered by ScrollTrigger.

Dynamic Lookbook Reveal: Organic geometric clip-path animations triggered on scroll entry.

Cursor-Tracking Media Card: Interactive product drops that reveal floating, mouse-following video previews on hover.

Fluid Custom Cursor: Interactive dual-ring cursor tracking system with hover state expansion.

Inertial Smooth Scrolling: Integrated Lenis smooth scroll engine for silky 60fps performance.

Accessibility Ready: Native prefers-reduced-motion detection that gracefully speeds up or disables heavy transforms.

Tailwind CSS Powered: Configured via a customized dark palette (black, gunmetal, adire-bright).

🛠️ Tech Stack & Dependencies

The project is built lightweight without heavy JS framework overhead:

HTML5 & CSS3

Tailwind CSS (CDN) – Utility-first styling framework.

GSAP 3 – Advanced animation library.

ScrollTrigger – Scroll-driven GSAP plugins.

Lenis – Modern smooth scroll library.

Google Fonts: Archivo Black & Space Grotesk.

🚀 Quick Start

Because this project is built as a unified single-file HTML structure, running it locally requires no build step:

Clone or Download the Repository:

git clone https://github.com/your-username/eko-lagos-metamorphosis.git
cd eko-lagos-metamorphosis


Run Locally:

Open eko-lagos-metamorphosis.html directly in any web browser.

Alternatively, serve it using a local development server like VS Code's Live Server or Python:

python -m http.server 8000


Deploy:

Ready for instant deployment on Vercel, Netlify, or GitHub Pages by serving index.html.

🎨 Customization

Changing the Color Palette

You can adjust the theme colors inside the inline Tailwind config block:

tailwind.config = {
  theme: {
    extend: {
      colors: {
        black: '#0a0a0a',
        gunmetal: '#17191a',
        off: '#f2efe8',
        adire: '#25409e',
        'adire-bright': '#3f5fe0',
      },
    },
  },
};


Adjusting Animation Timings

All motion triggers are managed cleanly inside the DOMContentLoaded script at the bottom of the file. You can adjust the Lenis scroll inertia or GSAP duration/eases to suit your brand aesthetic:

const lenis = new Lenis({ lerp: 0.09, smoothWheel: true });


📄 License

This template is available under the Commercial License.

Permitted: Usage in personal portfolios, client builds, and commercial digital deployments.

Prohibited: Direct resale or redistribution of the raw source files on third-party template platforms without authorization.

Designed & Developed for Èkó Studios — Lagos, Nigeria.

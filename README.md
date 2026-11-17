# PulseAI — Modern SaaS Landing Page Built with Astro.js

A high-converting, accessible, and ultra-responsive landing page built with **Astro.js**, designed with dark-first futuristic aesthetics, smooth light-mode switching, glassmorphism accents, and interactive micro-experiences.

> **Note:** As requested, no Git repository has been initialized (`.git` is omitted).

---

## ⚡ Quick Start

You can run commands directly from the root folder or inside `modern-astro-blog/`:

### Start the Local Development Server
```bash
npm run dev
```
Then open [http://localhost:4321](http://localhost:4321) in your browser.

### Build for Production
```bash
npm run build
```
The static, zero-JS optimized assets will be emitted to `modern-astro-blog/dist/`.

### Preview Production Build
```bash
npm run preview
```

---

## 🎨 Features & Highlights

1. **Futuristic Hero Cockpit**:
   - Dynamic announcement pill (`✨ NEW v3.4`)
   - Bold gradient headline & high-contrast CTAs
   - Social proof avatar stack with 5-star ratings (45,000+ engineers)
   - Interactive macOS-style terminal simulation showcasing real-time AST analysis and edge canary deploys
   - Interactive command runner with instant feedback

2. **Logo Cloud**:
   - Vector SVGs of tech pioneers (Vercel, GitHub, Stripe, Supabase, Cloudflare, Datadog) with smooth hover states.

3. **Asymmetric Bento Grid**:
   - Real-time code diff preview comparing mutex locks vs lockless channel dispatching
   - Sub-15ms global edge latency meter
   - Hardware-isolated SOC2 zero-trust compliance badges
   - Microsecond trace telemetry sparklines
   - Universal Git toolchain with one-click copy command

4. **Deep Feature Tabs Switcher**:
   - Interactive 4-tab switcher (Autonomous Intelligence, Instant Global Rollouts, Realtime Telemetry, Zero-Trust Enclaves) with live interactive previews and technical specs.

5. **3-Step Visual Workflow**:
   - Step 1: Connect Repository & Policy
   - Step 2: Autonomous AST Synthesis
   - Step 3: Verified Canary Rollout with automated rollback guarantee

6. **Interactive ROI & Time Savings Calculator**:
   - Real-time interactive sliders for Team Size, DevOps toil hours, and Blended Developer Hourly Rate
   - Dynamically calculates Annual Cost Reclaimed, Hours Saved, and Deployment Cadence acceleration.

7. **Verified Testimonial Grid**:
   - Quotes from VPs of Engineering, Principal Architects, and SRE Leads with verified badges and metrics.

8. **Predictable Pricing Matrix**:
   - Monthly vs Annual billing switch with a "Save 20%" discount badge
   - Developer ($0), Team Pro ($29/mo or $23/mo annual with luminous glow), and Enterprise ($199/mo) tiers.

9. **Accessible FAQ Accordion**:
   - Smooth animated expand/collapse accordions with ARIA attributes.

10. **High-Conversion CTA Banner & Form**:
    - Email submission form with live client-side validation and instant success state.

11. **Dark & Light Mode Toggle**:
    - Top navigation switch with instant theme swap and `localStorage` persistence, with zero flash of unstyled theme.

12. **Interactive Live Demo Modal**:
    - Triggered via the "Watch Live Demo" button in the Hero section.

---

## 📁 Architecture

```
astrojs/
├── package.json              # Root script forwarder (dev, build, preview)
├── README.md                 # Project documentation
└── modern-astro-blog/        # Astro project root
    ├── astro.config.mjs
    ├── package.json
    ├── public/
    │   └── favicon.svg       # Brand gradient SVG favicon
    └── src/
        ├── styles/
        │   └── global.css    # Design tokens, variables, typography, animations
        ├── layouts/
        │   └── Layout.astro  # HTML5 shell, SEO meta tags, theme flash preventer
        ├── components/
        │   ├── Navbar.astro
        │   ├── ThemeToggle.astro
        │   ├── Hero.astro
        │   ├── LogoCloud.astro
        │   ├── BentoGrid.astro
        │   ├── FeatureTabs.astro
        │   ├── WorkflowSteps.astro
        │   ├── RoiCalculator.astro
        │   ├── Testimonials.astro
        │   ├── Pricing.astro
        │   ├── Faq.astro
        │   ├── CtaBanner.astro
        │   ├── Footer.astro
        │   └── DemoModal.astro
        └── pages/
            └── index.astro   # Main landing page composition
```


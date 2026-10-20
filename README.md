# SYNAPSE — The Future of AI

An interactive one-page website about the real value, the risks and the future of artificial intelligence. Built as a university project on the usefulness of AI.

**Live:** https://synapse-ai-plum-five.vercel.app

## Features

- **Cinematic hero** with an animated headline and a particle network that reacts to your mouse (click to send a pulse)
- **Scenario simulator 2045:** three sliders (automation, regulation, education) produce six possible futures. The whole page changes color with your scenario
- **Myth check:** six flip cards. Guess "myth" or "fact", then read the explanation
- **Impact in everyday life & work:** a bento grid with an *Opportunity / Critique* switch
- **Partner spotlight:** [Wendka Uhren](https://wendka-uhren.com), luxury watches from Vienna & Munich, presented in Wendka's own brand look
- **Rolex quiz:** answer 4 questions correctly to unlock a 5% discount code for Wendka Uhren

## Tech

One single `index.html` file: HTML, [Tailwind CSS](https://tailwindcss.com) via CDN and plain JavaScript. No build step, no dependencies.

## Run locally

Open `index.html` in any modern browser.

## Deploy on Vercel

1. Push this repository to GitHub.
2. On [vercel.com](https://vercel.com), choose **Add New → Project** and import the repository.
3. Keep the default settings (framework preset: *Other*) and click **Deploy**.

## Configuration

The discount code and shop links are at the top of the `<script>` block in `index.html`:

```js
const CONFIG = {
  discountCode: 'WENDKA-KI5',
  discountPercent: 5,
  shopUrl: 'https://wendka-uhren.com',
  rolexUrl: 'https://wendka-uhren.com/collections/rolex',
};
```

---

Rolex is a registered trademark of Rolex SA. This project is not affiliated with Rolex.

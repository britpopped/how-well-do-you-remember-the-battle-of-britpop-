# How well do you remember the Battle of Britpop?

A standalone interactive quiz built in HTML, CSS, and JavaScript.

Clean, responsive, and designed to feel editorial on both desktop and mobile, it works as:

* a standalone GitHub Pages site
* an iframe embed in WordPress
* a direct Custom HTML embed in WordPress

## Live demo

**Play it here:**
[https://britpopped.github.io/how-well-do-you-remember-the-battle-of-britpop-/](https://britpopped.github.io/how-well-do-you-remember-the-battle-of-britpop-/)

## About

This project is a 10-question multiple-choice quiz about the Battle of Britpop, with instant feedback, score tracking, keyboard shortcuts, and a controlled fixed-frame layout.

## Features

* 10 multiple-choice questions
* responsive desktop and mobile layout
* fixed-size quiz frame for a consistent presentation
* instant answer feedback overlay
* score tracking across the full quiz
* keyboard shortcuts for numbered answers
* reduced-motion support
* accessible labels and focus states
* no build tools required
* single-file setup

## Stack

* HTML
* CSS
* JavaScript
* GitHub Pages

## File structure

```text
/
├── index.html
└── README.md
```

## Run locally

Open `index.html` in your browser.

## WordPress embed

### iframe version

```html
<div style="max-width: 1040px; margin: 0 auto;">
  <iframe
    src="https://britpopped.github.io/how-well-do-you-remember-the-battle-of-britpop-/"
    title="How well do you remember the Battle of Britpop?"
    loading="lazy"
    scrolling="no"
    style="width: 100%; height: 560px; border: 0; display: block;"
  ></iframe>
</div>
```

### Direct WordPress embed

If you want tighter control over the page layout, you can paste the quiz directly into a WordPress Custom HTML block instead of using an iframe.

## Customisation

Current key layout values:

* overall quiz width: `max-width: 1040px;`
* desktop frame height: `clamp(500px, 68vh, 620px)`
* mobile frame height: `clamp(480px, 76svh, 560px)`
* question content width: `max-width: 860px;`

## Accessibility

The quiz includes:

* visible keyboard focus states
* reduced-motion handling
* numbered answer shortcuts
* labelled feedback dialog
* mobile-friendly touch targets

## Notes

* The project is currently a single self-contained HTML file.
* Google Fonts are loaded at runtime.
* For a stricter production setup, fonts, CSS, and JavaScript can be split into separate assets.

## License

Add your preferred license here if you want the repo to be reusable by others.

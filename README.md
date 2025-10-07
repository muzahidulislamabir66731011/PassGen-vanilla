# 🔐 PassGen-vanilla
A **single-file** password generator that runs anywhere.  
No frameworks, no build tools, no trackers – just pure HTML/CSS/JS.

## ⚡ Features
- 16-character passwords with uppercase, lowercase, numbers & symbols  
- One-click copy (visual feedback on the copy icon)  
- Keyboard-friendly: `Enter` → new password  
- Responsive dark-theme UI (looks great on phone or 4K monitor)  
- Total weight < 10 kB (images included)

## 🚀 Quick start
1. Clone or download this repo  
2. Double-click `index.html` – done!  
3. *(Optional)* Replace `copy.png` / `generate.png` with your own icons.

## File map
```
PassGen-vanilla/
├── index.html     – markup
├── style.css      – dark-theme styles
├── script.js      – generator + clipboard logic
├── copy.png       – clipboard icon
├── generate.png   – tiny key icon
└── docs/
    └── passgen-demo.gif  – eye-candy for README
```

## Customize in 30 s
| What | Where |
|------|-------|
| Password length | `script.js` line 2 `const lenght = 16;` *(yes, the typo is on purpose—PR welcome 😄)* |
| Allowed symbols | edit `const symbol = "...";` |
| Colors | change `#019f55` in `style.css` to your brand accent |

## Deploy anywhere
Static host friendly – drag to Netlify, Vercel, GitHub Pages, or even open from `file://`.

## License
MIT – generate, share, fork, profit.

# PassGen
![](https://img.shields.io/badge/JavaScript-ES6+-yellow?style=for-the-badge&logo=javascript)
![](https://img.shields.io/badge/License-MIT-green?style=for-the-badge)

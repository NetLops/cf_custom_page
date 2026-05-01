# Multi-Style Cloudflare Custom Error Pages 🎁

Welcome to the ultimate "Blind Box" collection of Cloudflare custom error pages! Instead of a single boring design, this repository contains 5 **completely different, visually stunning, and highly surprising** error pages tailored for specific Cloudflare error types.

Designed with ❤️, caffeine, and a lot of humor by NetLops.

## 🎨 The 5 Unique Styles

1. **`waf_block.html` (WAF Block / 403)**
   - **Style**: Retro Hacker Terminal 📟. Matrix-style green text, blinking cursor, and typewriter animation.
   - **Vibe**: "Security guard caught you looking like a hacker."
2. **`500_errors.html` (500 Class Errors)**
   - **Style**: Lost in Space 🌌. Interactive glowing particle canvas with a 3D tilting glassmorphism card and glitching neon text.
   - **Vibe**: "Our servers got abducted by aliens."
3. **`1000_errors.html` (1000 Class / Config Errors)**
   - **Style**: Hand-drawn Blueprint 📐. Blue background, white grid, sketch font, and a massive red "REJECTED" stamp.
   - **Vibe**: "The foreman held the blueprints upside down."
4. **`ip_block.html` (IP / Country Block)**
   - **Style**: Border Checkpoint 🛂. Passport paper texture with a massive, shaking "ACCESS DENIED" red stamp.
   - **Vibe**: "You're not from around here, partner."
5. **`rate_limit.html` (Rate Limiting / 429)**
   - **Style**: Zen Mode 🧘‍♂️. Extremely soft pastel gradients, blurred glass, and an animated breathing circle to calm the user down.
   - **Vibe**: "You click too fast. Take a deep breath."

## 🌐 Features Built-in

- **Dialect Humor (i18n)**: All pages auto-detect the user's browser language (`navigator.language`). If Chinese is detected, it loads localized, highly humorous "dialect" jokes (e.g., "俺们村的服务器被外星人拐跑了"). If English is detected, it loads equivalent English humor.
- **Cloudflare Tokens**: Every page seamlessly supports standard CF tokens (`::ERROR_CODE::`, `::RAY_ID::`, `::CLIENT_IP::`, `::GEO::`, `::ERROR_MESSAGE::`).
- **Local Mocking**: Open any HTML file directly in your browser without Cloudflare, and it will automatically generate fake "Mock" data for you to preview the design perfectly.
- **Zero Dependencies**: 100% pure HTML, CSS, and Vanilla JS. No external libraries means blazing fast load times.

## Setup

See `QUICK_START.md` for instructions on how to use these pages in Cloudflare.

# CuddleHeros Store Demo-Website

A demo storefront showing [TedPro](https://github.com/Hendrik-InfoSec/Ted-Pro)'s embeddable AI assistant running live on a real website.

🔗 **Live demo:** https://hendrik-infosec.github.io/cuddleheros-demo/

---

## What this is

CuddleHeros is a fictional plushie store built to demonstrate how TedPro's widget looks and behaves once embedded on an actual business website — not just described in a README.

Scroll to the bottom right corner: that's Ted, running live, answering real product questions from the actual CuddleHeros catalog.

## The integration

The entire AI assistant is added with one line, right before the closing `</body>` tag:

```html
<script src="https://ted-pro.onrender.com/embed.js"></script>
```

No other code, no build step, no dependencies. The business owner pastes this once and Ted appears — branded, functional, and connected to their real product data.

## What it's for

This repo exists to answer one question: **"What does a client's website actually look like with TedPro installed?"**

The main [Ted-Pro](https://github.com/Hendrik-InfoSec/Ted-Pro) repository contains the full platform — multi-tenant backend, admin dashboard, security architecture, AI engine. This repo is the other half of that story: the simplest possible proof that the embed works exactly as advertised.

## Stack

Plain HTML/CSS. No framework, no build tools — intentionally simple so the focus stays on the widget integration, not the demo site itself.

---

Built by [Hendrik Selogilwe](https://github.com/Hendrik-InfoSec) as a companion demo to [TedPro](https://github.com/Hendrik-InfoSec/Ted-Pro).

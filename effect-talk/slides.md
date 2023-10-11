---
theme: default
class: text-center
highlighter: shiki
lineNumbers: true
drawings:
  persist: false
transition: slide-left
mdc: true
---

<h1 class="flex items-center">
  Build applications with <EffectLogo />
</h1>

---

# Introduction

<div class="flex">
    Cosimo Matteini, software developer at <img src="/doubleloop.svg" class="ml-1 h-6 self-end">
</div>

<br/>

- <mdi-web class="mr-1" /> [cosimomatteini.com](https://cosimomatteini.com)
- <mdi-github class="mr-1" /> [@devmatteini](https://github.com/devmatteini)
- <mdi-mastodon class="mr-1" /> [@cosimomatteini](https://hachyderm.io/@cosimomatteini)
- <mdi-twitter class="mr-1" /> [@MatteiniCosimo](https://twitter.com/MatteiniCosimo)

---
layout: statement
---

# What is Effect?

Effect is a TypeScript library for building application with concurrency, error handling, observability and
composability...and many more things!

---

# Why Effect?

We are using `fp-ts` in production and we like it.

At the end of february 2023, `fp-ts` was merged into the Effect ecosystem.

Even if Effect 1.0 is far away, we've been using Effect in production since april!

---

# Effect features

<img src="/effect-features.png" />


---

# We are going to focus on...

<img src="/effect-talk-focus-on.png" />

---

# Sample application: football-calendar

<div class="flex items-center mb-5">
    <mdi-github class="mr-1" /> <a href="https://github.com/devmatteini/football-calendar" target="_blank">devmatteini/football-calendar</a>
</div>

<img src="/football-calendar-architecture.png">

---
layout: center
---

# Let's start coding!

---
layout: center
---

# Conclusion

- slides: https://github.com/devmatteini/socrates-2023
- source code: https://github.com/devmatteini/football-calendar

Other useful links:

- Effect: https://www.effect.website/
- From fp-ts to Effect: https://github.com/devmatteini/from-fp-ts-to-effect-ts

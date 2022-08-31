# Design System

<aside class="notes">

"What does it consist of?"
</aside>
---
# Design Tokens
"Specs" of your design system
<div><img src="dist/images/blueprint_lego_block.jpg" alt=""></div>

<aside class="notes" data-markdown>

* Design decisions
* CSS/SCSS variables
* Measurements
* Color pallete
* Typography
* Theme's
    * Light, dark, high contrast
    * Compact / porous
    * Larger/smaller text

## Transition
"Handy styling utilities, but incomplete"
</aside>

---
# CSS Utility classes
<div><img src="dist/images/legos-sorted.png" alt=""></div>
<aside class="notes" data-markdown>
* Layer around the design tokens

* Layout
* Breakpoints
* Repetitive group of styling rules
</aside>

---
# Components
<div><img src="dist/images/atomic-design.png" alt="Granularity steps in Atomic Design by Brad Frost"></div>
<aside class="notes" data-markdown>
* Atomic design (Brad Frost)
    * Atoms & Molecules

* Must use the design tokens and CSS Styling utilities
* "Dumb" components
* Context unaware
* Applicable ("appropriate") technique
</aside>

---
# Patterns
<div class="r-stack">
    <img class="fragment fade-in-then-semi-out" style="width: 60%;" src="dist/images/lego-instructions-workspace.jpg" alt="">
    <img class="fragment fade-in-then-semi-out" style="width: 50%;" src="dist/images/lego-instructions_king-kahuna.jpg" alt="">
    <img class="fragment fade-in-then-semi-out" style="width: 80%;" src="dist/images/lego-instructions-firetruck.jpeg" alt="">
    <img class="fragment fade-in-then-semi-out" style="width: 60%;" src="dist/images/lego-instructions-golden-snitch.jpg" alt="">
    <img class="fragment fade-in-then-semi-out" style="width: 90%;" src="dist/images/lego-instructions-be-like.jpg" alt="">
    <img class="fragment fade-in-then-semi-out" style="width: 50%;" src="dist/images/ikea-henj.jpg" alt="">
</div>
<aside class="notes" data-markdown>
* Describes how DS elements work and could be used together
* Kind of like a style guide, but not quite
* Not everything is a DS component
* Organisms/Templates
</aside>

---

<h1 class="r-fit-text">Design system <span class="subheading">Conclusion</span></h1>

* Not just a component library
* Faster UI development
* Focus feature > brand
* Consistency is key
* Brand recognition
* Themes

<aside class="notes" data-markdown>

# Transition
"Now that we know what it is, lets look at how Rabobank does it"
</aside>
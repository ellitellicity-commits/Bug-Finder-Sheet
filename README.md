# Bug Finder Sheet

<p align="center">
  <img src="https://readme-typing-svg.demolab.com/?lines=It's+not+a+bug...;It's+a+feature!;(narrator:+it+was+a+bug);Now+with+15+caught+specimens&font=Fira+Code&size=20&pause=1200&color=46503C&center=true&vCenter=true&width=500&height=50" alt="Typing SVG">
</p>

A personal field log of bugs found, diagnosed, and fixed while learning Java through [MOOC.fi's Java Programming course](https://java-programming.mooc.fi/), kept as preparation for an Advanced Object-Oriented Programming course.

This isn't a tool or an app. It's a record: fifteen real bugs hit while working through lists, search logic, and loops, each one written down in plain words, with the reasoning behind the fix. The goal is to turn debugging mistakes into a pattern library that gets faster to recognize over time.

## What's inside

Each entry in the log follows the same structure:

- **How it was found**, the debugging step that surfaced the problem (a print statement, an unexpected output, a re-read of the logic)
- **My own words**, the actual reasoning written down in the moment, not cleaned up after the fact
- **The lesson**, the underlying principle, generalized so it applies beyond the one bug

The fifteen specimens cover things like control-flow timing bugs, the difference between `==` and `.equals()` for strings, why `indexOf()` can't find duplicate values, an `else` branch that quietly broke a search loop, and a few classic off-by-one and scope mistakes.

## View it

The site lives in [`/site`](./site) as a single self-contained HTML file. Open `site/Ellison-TheBugFinder.html` directly in a browser, no build step or dependencies required.

## Why this exists

Most of these bugs took real time to track down and understand. Writing them down, in plain language, turns a frustrating afternoon into something reusable, the next time a similar bug shows up, it's recognized faster because it's already been named once.

This repo will keep growing as new bugs get caught while working through the rest of the course.

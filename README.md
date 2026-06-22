# excuse-generator

> A single-file static web app that assembles dry, self-aware excuses for why
> something in software is broken, delayed, or on fire.

## Live demo

`https://yourusername.github.io/excuse-generator`

## Screenshot

<!-- add screenshot.png -->

## What it is

A developer excuse generator. One button click assembles a randomly composed
excuse from a template engine — seven sentence templates layered over seven
word banks — producing roughly 328 million possible excuses. The humour is
dark, dry, and self-aware: it punches at software industry absurdity, process,
and tooling, never at people.

## Run it

Clone the repo and open `index.html` in a browser. No install, no build step,
no dependencies.

## Stack

HTML, CSS, JavaScript — zero dependencies.

## Features

- **Template engine** — sentences are assembled at runtime from interchangeable
  parts rather than picked from a flat list of canned lines.
- **Thousands of combinations** — seven templates over seven word banks yield
  hundreds of millions of distinct excuses (the live count is computed in the
  app from the actual array sizes).
- **Shareable URLs** — every excuse is encoded into the URL hash, so a link
  reproduces the exact same excuse for whoever opens it.
- **Keyboard shortcut** — press Space or Enter to generate a new excuse.
- **Copy to clipboard** — one click copies the current excuse.

## Skills demonstrated

- DOM manipulation
- Combinatorial template systems
- URL state serialisation
- Zero-dependency JavaScript
- Shipping a finished and documented project

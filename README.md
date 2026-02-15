# HTML Newspaper Recreation

## Student Information
**Name:** Ali Jaffar
**Roll Number:** 22P-9064
**Section:** BCS-8A

## Original Newspaper
**Name:** Nawa-i-Waqt (Daily Nawa-i-Waqt / روزنامہ نوائے وقت)
**Date:** Thursday, August 18, 1988
**Source:** Historical Digital Archives

## Project Description
This project is a reconstruction of the front page of the Nawa-i-Waqt newspaper from 1988, which reported the tragic plane crash of President Zia-ul-Haq. The recreation focuses on translating the original Urdu content into English while maintaining a high-density, broadsheet-style layout using standard HTML5 and inline CSS.

## Features Implemented
* **3-Column Table Layout:** Used a rigid table structure to define the 30%-40%-30% column split typical of 1980s journalism.
* **Semantic HTML5:** Implemented `<header>`, `<main>`, `<article>`, `<section>`, and `<footer>` tags for better document structure.
* **Inline CSS Styling:** Applied all visual formatting (borders, spacing, and font styles) via the `style` attribute to satisfy technical constraints.
* **Visual Information Density:** Replicated the "busy" look of the original paper with multiple articles, photos, and a localized bank advertisement.

## Challenges Faced
The main challenge was mimicking the multi-column newspaper grid without using external CSS or Flexbox. I solved this by nesting articles within table cells and using `text-align: justify` to create the clean block-text appearance of a printed paper.

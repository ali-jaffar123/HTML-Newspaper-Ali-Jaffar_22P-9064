# HTML Newspaper Recreation

## Student Information
**Name:** [Your Name]
**Roll Number:** [Your Roll No]
**Section:** [Your Section]

## Original Newspaper
**Name:** Nawa-i-Waqt (نوائے وقت)
**Date:** August 18, 1988
**Source:** Provided Class Material

## Project Description
This project is a recreation of the front page of the Urdu newspaper "Nawa-i-Waqt" from 1988. The objective was to translate and reformat the historical coverage of President Zia-ul-Haq's death into a modern HTML5 document while maintaining a 70% visual similarity to the original multi-column layout.

## Features Implemented
* **3-Column Table Layout**: Used a `<table>` to structure the complex newspaper columns as per assignment requirements.
* **Semantic HTML5**: Utilized `<header>`, `<nav>`, `<article>`, `<section>`, and `<footer>` tags for better accessibility and structure.
* **Inline Styling**: All visual formatting (borders, column widths, padding) was achieved strictly through the `style` attribute.
* **Accessibility**: All images include descriptive `alt` tags.

## Challenges Faced
The primary challenge was replicating the dense, vertical column structure of a traditional newspaper without using external CSS Flexbox or Grid. I solved this by nesting content within a 3-column HTML table and using `table-layout: fixed` to ensure consistent column widths.

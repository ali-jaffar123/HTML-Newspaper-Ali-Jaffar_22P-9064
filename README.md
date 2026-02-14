# HTML Newspaper Recreation

## Original Newspaper
**Name:** Daily Nawa-i-Waqt (روزنامہ نوائے وقت)
**Date:** August 18, 1988
**Source:** Provided scan of the Multan edition covering the presidential crash.

## Project Description
This project is a technical recreation of the front page of "Nawa-i-Waqt" using only HTML5. The layout focuses on replicating the dense, columnar broadsheet style of late-80s Pakistani print journalism, specifically highlighting the air tragedy involving President Zia-ul-Haq.

## Features Implemented
Semantic Layout: Utilized `<header>`, `<nav>`, `<main>`, `<article>`, and `<footer>` tags for document structure[cite: 40].
3-Column Table Structure: Implemented a fixed-width `<table>` to mirror the original newspaper's article alignment[cite: 41, 59].
Headline Hierarchy: Used `<h1>` through `<h4>` to establish clear content priority[cite: 43].
Inline CSS: Managed borders, padding, and text alignment through the `style` attribute[cite: 49].

## Challenges Faced
The primary challenge was aligning the President's portrait within the center column of the table while maintaining readability. I solved this by using a `div` wrapper with `text-align: center` inside the table cell to ensure the image did not disrupt the flow of the adjacent news columns.

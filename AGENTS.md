
# AGENTS.md — The Arsenal Journal

## 1. Project Overview

The Arsenal Journal is a personal football magazine dedicated to documenting Arsenal Football Club matches.

The website allows the author to publish personal match reviews after watching Arsenal games. It serves as a growing archive of football memories, match observations, and personal experiences.

This is an independent fan website, not an official Arsenal website.

## 2. Technology

This project uses:
- HTML for website structure.
- CSS for visual design.
- JavaScript for interactive features when needed.
- GitHub Pages for deployment.

Avoid unnecessary frameworks and dependencies.

## 3. Design Guidelines

The website follows a modern football editorial magazine aesthetic.

### Color Palette
- Arsenal Red: #DB0007
- Cream: #F7F5F0
- Dark Charcoal: #171717
- Gray: #77736D
- Light Gray: #E8E6E1

### Visual Style
- Editorial magazine layout.
- Large headlines and readable typography.
- Football photography as a visual focus.
- Generous whitespace.
- Consistent colors and spacing.
- Responsive design for desktop and mobile.

## 4. Project Structure

- index.html: Main homepage and match review archive.
- AGENTS.md: AI development instructions.
- articles/: Individual match review pages.
- public/images/: Website images.
- src/styles/style.css: Main stylesheet.
- src/components/: Reusable website components.
- src/pages/: Additional website pages.
- src/data/: Website data.

Keep files in their designated directories.

## 5. Match Review Format

Every match review should include:

1. Match date.
2. Competition.
3. Opponent and final score.
4. Article headline.
5. Match overview.
6. Key moments.
7. Player observations.
8. Personal review.
9. Final thoughts.

Writing should feel like a personal football magazine rather than a formal news report.

Use natural language and maintain a personal storytelling style.

Never invent match results, statistics, goalscorers, or match events.

## 6. File Naming Rules

Each match review must be an independent HTML file.

Use this format:

YYYY-MM-DD-opponent-name.html

Example:

2026-11-07-hull-city.html

All match review pages must be stored in the articles/ directory.

## 7. Rules for Adding New Articles

When the user requests a new match review:

1. Read the match information provided by the user.
2. Create a new HTML file inside articles/.
3. Follow the established match review format.
4. Reuse the existing stylesheet.
5. Maintain the established editorial design.
6. Add a new article card to index.html.
7. Include the match date, opponent, score, headline, and summary.
8. Link the homepage card to the corresponding article page.
9. Preserve all existing articles.

If important match information is missing, ask the user instead of inventing details.

## 8. Development Rules

- Read AGENTS.md before modifying the project.
- Maintain the existing visual design.
- Reuse existing CSS classes whenever possible.
- Do not redesign the website without permission.
- Keep all navigation and article links functional.
- Preserve existing content.
- Ensure responsive layouts.
- Avoid unnecessary dependencies.

## 9. Main Principle

The Arsenal Journal should grow into a continuously updated personal football magazine.

Every new article should look and feel like part of the same publication.

Consistency, readability, and personal storytelling are the highest priorities.

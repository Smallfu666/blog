// Publishing
// 1. Create posts/<slug>/index.qmd with title, description, author, date, image in frontmatter
// 2. Run `quarto render` to rebuild docs/
// 3. Commit and push (GitHub Pages auto-deploys from docs/)
// Example: posts/adrs-systems-research-talk/index.qmd

// Theme
// Light: claude-light.css | Dark: claude-dark.css
// Set via _quarto.yml: format.html.theme.{light,dark}
// Both are complete SCSS-format files with /*-- scss:rules --*/ header

// Fixed issues (don't touch)
// - TOC scrollspy: toc-scrollspy.html via include-after-body
// - Dark mode persistence: URL param (?theme=dark) + localStorage fallback, in toc-scrollspy.html
// - Color toggle icon: CSS ::after (☀), reader mode hidden, in both claude CSS files
// - data-mode="dark" on dark Bootstrap sheet: fixed in toc-scrollspy.html DOMContentLoaded

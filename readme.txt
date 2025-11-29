Habitat for Nature - Mission Section (Drop-in)
=============================================

Files:
- styles/mission.css
- mission.html
- assets/forest-placeholder.jpg (temporary background - replace with your forest image if you like)

How to use on Netlify (static HTML site):
1) Copy `styles/mission.css` and `assets/forest-placeholder.jpg` into your site at the same relative paths (keep the folders as-is).
2) In your main HTML (index.html or /pages/mission.html), add this line inside <head>:
 <link rel="stylesheet" href="/styles/mission.css">
3) Find your current Mission block and replace it with the contents of `mission.html`.
4) (Optional) Replace `/assets/forest-placeholder.jpg` with a real forest photo; keep the same file name, or update the CSS background-image path in `styles/mission.css`.
5) Deploy.

For React/Vite/Next:
- Create the CSS file in `src/styles/mission.css` and import it in your Mission component:
 import './styles/mission.css';
- Paste the `mission.html` <section> markup into your component's JSX (class -> className).
- Put the placeholder image in `public/assets/forest-placeholder.jpg` or adjust the path.

Accessibility:
- The section uses semantic tags and an aria-labelledby heading.

Questions? Ping me and I’ll tailor it to your exact framework/layout.
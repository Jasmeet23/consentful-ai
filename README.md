# Consentful AI — CHI 2027 Workshop Website

Static workshop website ready for GitHub Pages.

## Publish with GitHub Pages

1. Create a public GitHub repository named `consentful-ai`.
2. Upload `index.html` and `style.css` to the repository root.
3. In GitHub, open **Settings → Pages**.
4. Under **Build and deployment**, choose **Deploy from a branch**.
5. Select **main** and **/(root)**, then Save.
6. Your site will appear at:
   `https://YOUR-USERNAME.github.io/consentful-ai/`

## Before launch

Search `index.html` for `TBA` / `To be announced` and replace:
- submission deadline
- notification date
- workshop date
- submission link
- contact details

## Organizer photos

The current design uses initials, so it works immediately without photos.
If you want headshots, place them in `images/organizers/` and replace each
`<div class="avatar">XX</div>` with an `<img>` element. Add a CSS rule such as:

```css
.organizer img {
  width: 100%;
  aspect-ratio: 1;
  object-fit: cover;
  border-radius: 50%;
  margin-bottom: 1.2rem;
}
```

## Local preview

Simply open `index.html` in a browser. For the most accurate preview, use a
small local HTTP server or GitHub Pages.

## Content basis

The page copy is adapted from the supplied CHI workshop proposal:
"Consentful AI: Designing Consent Across Data, Models, and Human-AI Interaction."
No dates, submission URL, organizer biographies, or contact information were
invented; missing information is marked TBA.

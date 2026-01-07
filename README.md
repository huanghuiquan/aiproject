# Astro Markdown Blog

A minimal Astro blog scaffold that uses Markdown files as posts.

How to use
1. Install dependencies:
   ```bash
   npm install
   ```
2. Start dev server:
   ```bash
   npm run dev
   ```
   Open http://localhost:3000

3. Add a new post:
   - Create a file `src/content/posts/my-new-post.md`
   - Add frontmatter:
     ```yaml
     ---
     title: "My New Post"
     pubDate: "2026-01-08"
     description: "A short summary shown on the index"
     ---
     ```
   - Write Markdown below the frontmatter. The site will pick it up automatically.

Build & deploy
- Build: `npm run build`
- Preview production build locally: `npm run preview`
- Deploy to platforms like Netlify, Vercel, or GitHub Pages. Astro builds a static `dist/` you can deploy.

Notes & next steps
- This scaffold uses a tiny inline CSS for simplicity. Replace with Tailwind, Sass or your preferred styling.
- You can extend frontmatter fields (tags, author, coverImage) and update index.html to show them.
- If you want RSS, pagination, or tags, I can add those next.

Enjoy writing in Markdown!

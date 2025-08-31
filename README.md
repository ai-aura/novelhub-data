# novelhub-data
 
📚 NovelHub Data Repository

This repository powers the NovelHub Flutter application by hosting structured novel metadata in a simple, free, and open format.

🔑 Purpose

Store all novel metadata in one place (novels.json).

Provide lightweight, static hosting via GitHub Pages so the app can fetch and display novels without a backend server.

Keep novel files hosted externally (e.g., MediaFire for PDFs, Pinterest or CDN links for cover images).

🗂️ Repository Contents

novels.json → The main metadata file containing all novel entries. Each entry includes:

id: Unique novel ID.

title: Title of the novel.

author: Author name.

description: Short synopsis.

coverUrl: Link to the novel’s cover image (Pinterest/CDN).

pdfUrl: Direct link to the novel PDF (MediaFire, Drive, etc.).

genre: Novel category (Fantasy, Romance, etc.).

createdAt: Upload date.

isFeatured: Boolean flag for homepage highlight.

downloadCount: Counter updated in-app when downloaded.

/covers/ (optional, if you want to upload cover images here instead of Pinterest).

README.md → Documentation on how to update novels.json safely.

🌍 Hosting

The repository is configured with GitHub Pages to serve novels.json as a public API endpoint, e.g.:

https://your-username.github.io/novelhub-data/novels.json

📝 Updating Novels

Add your new novel details in novels.json.

Commit changes with a clear message (e.g., Added "The Time Traveler" novel).

Push to GitHub → changes will be live automatically.

⚠️ Notes

No Firebase / Backend: This repo is static-only; it holds metadata and external links, not PDFs.

Free-tier friendly: Uses GitHub Pages, MediaFire, and Pinterest → no hosting costs.

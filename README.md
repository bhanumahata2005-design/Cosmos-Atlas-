# COSMOS ATLAS — Interactive Universe Explorer

A mobile-friendly, browser-based 3D space visualization plus a searchable **Universe Encyclopedia**.

## Features
- Interactive 3D starfield with drag-to-orbit and zoom controls.
- Selectable cosmic objects, guided tour, category filters and object notes.
- Encyclopedia with 100+ curated topics across cosmology, galaxies, stars, black holes, nebulae, planets, moons, cosmic events and space exploration.
- Search and category filters for encyclopedia entries.
- Lazy-loaded image previews from NASA's public Images API when available, with robust failure states and direct Google Images links.
- Reference links to NASA Universe, NASA Images, ESA/Webb and ESA/Hubble.
- Each entry has a Google Images search link and a NASA-focused research search link.
- Responsive layout for mobile and desktop.

## Run it
Open `index.html` in a modern browser with an internet connection. Three.js is loaded from jsDelivr, and NASA image previews require internet access. If a local browser blocks a remote request, run a simple local server (for example `python -m http.server 8000`) and open `http://localhost:8000`.

## Design references
The original design takes broad inspiration from the clarity, image-led storytelling and navigation patterns used by NASA Science, ESA/Webb and ESA/Hubble. It does not copy their exact layouts, branding or page content.

## Publish with GitHub Pages
1. Create a GitHub repository.
2. Upload `index.html`, `README.md`, and `.nojekyll` to the repository root.
3. In **Settings → Pages**, choose deploy from the `main` branch and `/(root)`.
4. Open the URL GitHub Pages provides.

## Scientific and image notes
This is an educational guide, not a complete catalogue of every object in the universe. Many objects remain undiscovered, and professional catalogues can contain billions of sources. The 3D scene is illustrative and not to scale. Encyclopedia text is concise and introductory; consult linked NASA/research material for more depth. Image previews are retrieved from NASA's public image API when available; the Google Images button opens a search and does not copy Google's results into this site. Always check the original publisher's image credits and usage terms before reusing images.

Useful references: https://science.nasa.gov/universe/ and https://images.nasa.gov/

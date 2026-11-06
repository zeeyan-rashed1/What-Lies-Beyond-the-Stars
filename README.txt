QORA READER STUDIO — PREMIUM DEPLOYMENT
Files:
- index.html: responsive QORA publication website with interactive PDF.js reader
- chapters.json: chapter metadata extracted from the supplied book contents page
- assets/cover.jpg: high-resolution 300-DPI cover
- assets/what-lies-beyond-the-stars-volume-one.pdf: premium 42-page PDF

Reader features:
- Responsive landing page and mobile layout
- Interactive page rendering (PDF.js)
- Previous/next page controls
- Zoom and fit-width controls
- Search across selectable PDF text
- Chapter shortcuts and page thumbnails
- Local reading-position saving
- Direct PDF download and fallback link
- SEO/social metadata

DEPLOY:
1. Extract this ZIP.
2. Drag the extracted QORA_Reader_Studio folder to https://app.netlify.com/drop
3. Wait for Netlify to provide a public HTTPS URL.
4. Use that URL as QORA's Read / open link.
5. Test on desktop and mobile.

The PDF.js library is loaded from cdnjs, so the interactive viewer needs an internet connection. The direct PDF link remains available as fallback.

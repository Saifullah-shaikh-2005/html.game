# TODO: Implement Google-like Image Search with Unsplash Integration

## Approved Plan Steps

**Step 1: [COMPLETE] Update index.html**
- Add Web Search toggle UI near search input (checkbox/button: "Web Search")
- Enhance JS search logic: Detect web mode → fetch Unsplash images via source.unsplash.com (no key, CORS-free)
- Generate 12-20 image results for query (thumbnails like Google Images)
- Allow "upload" (add to local gallery) for web results via new button on cards
- Update gallery render to handle web results (temporary array `webImages`, source: 'Unsplash Web')

**Step 2: [COMPLETE] Update style.css**
- Add styles for web toggle, web result cards (e.g., blue badge, upload button)
- Loading spinner for search

**Step 3: [COMPLETE] Test**
- Run in browser, test local vs web search, upload web images to gallery, verify persistence/render

**Step 4: [COMPLETE] Attempt completion**

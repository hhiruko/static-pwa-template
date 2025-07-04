# Static PWA Template

This is a lightweight static progressive web-app (PWA) template, that you can use to quickly build and deploy your own PWA. Core features include:
- Offline access via caching
- Buildtime webmanifest and icons auto-generation (just provide a single .svg)
- Light/dark/system preference themes
- localStorage wrapper classes (Storage, CollectionStorage)
- Transfer class for importing/exporting the entire localStorage contents in JSON
- Github workflow for Github Pages deployment
- Icon library using Lucide-preact

### Dependencies:
- Vite
- Preact
- Glob
- Favicons
- Lucide-preact
- Water.css

### Start:
1. Install dependencies:
```
npm i
```
2. Update .env file.
3. Opionally, put your icon.svg into public/favicons and write the filename to .env file.
4. Dev server:
```
npm run dev
```
5. Prod static build:
```
npm run build
```
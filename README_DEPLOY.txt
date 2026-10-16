# Aligarh MLC 2026 voter-search portal package

## Included
- `index.html`: updated search page with part/PDF-specific result links.
- `data.json`: currently available page-level OCR text index from the uploaded part-104 JSON (165 page entries).
- `44 PDF files`: uploaded Aligarh PDF parts, with byte-identical duplicates removed.
- `PDF_Index.xlsx`: inventory and page-level OCR status.

## Important limitation
The Excel workbook is NOT a complete voter-by-voter transcription. The current `data.json` has 165 page entries, but many entries have blank OCR text. All 44 PDF parts are included as source files, totalling 6188 pages. Name-wise searchable indexing for every part still requires Hindi OCR and human verification.

## Upload to GitHub
1. Download and extract this ZIP on your computer.
2. Open the GitHub repository `Rahul-Gupta-MLC`, branch `main`.
3. Use **Add file → Upload files**.
4. Upload `index.html`, `data.json`, and all PDF files from this folder into the repository root (same level as `campaign-poster.jpg`).
5. Keep the existing `campaign-poster.jpg` in the repository; it is not included in this package.
6. Commit changes. Render Auto-Deploy should publish them.
7. Test the live website and confirm the banner still loads.

Do not upload secrets or the Render Deploy Hook. Do not delete the old files until the updated site is tested.

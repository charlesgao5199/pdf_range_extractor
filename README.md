# PDF Page Range Extractor

A simple web app to upload a PDF, preview its pages, and extract a specific page range into a new PDF — all processed entirely in your browser. No server uploads required.

## Features
- Upload a PDF by clicking or drag-and-drop  
- Scrollable page preview with thumbnails  
- Click a page to choose **Start** or **End** page  
- End cannot be selected before a Start page is chosen  
- Highlights selected Start (green) and End (blue)  
- Toggle preview layout: 5 pages per row or 10 pages per row  
- Download a new PDF containing only the chosen page range  

## Live Demo
Once deployed with GitHub Pages, the app will be available here:  
[Live site](https://charlesgao5199.github.io/pdf_range_extractor/)  

## Tech Stack
- [pdf-lib](https://github.com/Hopding/pdf-lib) — extract and manipulate PDFs in the browser  
- [pdf.js](https://mozilla.github.io/pdf.js/) — render PDF thumbnails for preview  
- HTML, CSS, and JavaScript  

## Installation (local development)
Clone the repository:
```bash
git clone https://github.com/charlesgao5199/pdf_range_extractor.git
cd pdf_range_extractor

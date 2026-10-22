The certification gallery in `index.html` displays the image and PDF files in this folder. Clicking an image opens the full-size certificate; the Power BI PDF card opens the document.

To add another image certificate, upload the image here and add a card inside `.certification-gallery` in `index.html`. Update the filename in both `href` and `src`, and provide descriptive alt text and a title:

```html
<figure class="certification-card">
    <a class="certification-link" href="assets/certifications/your-certificate.jpg" target="_blank" rel="noopener noreferrer">
        <img src="assets/certifications/your-certificate.jpg" alt="Describe the certification shown">
    </a>
    <figcaption>
        <strong>Certification name</strong>
    </figcaption>
</figure>
```

To add a PDF, use a `.certification-pdf` link containing a visible document label. The gallery scrolls horizontally on smaller screens and snaps to each card.

Upload your certification images to this folder.

In `index.html`, replace the certification placeholder inside `#certifications` with a card for each certificate. Use this format and update the image path, descriptive alt text, certification name, issuer, and date:

```html
<figure class="certification-card">
    <img src="assets/certifications/your-certificate.jpg" alt="Describe the certification shown">
    <figcaption>
        <strong>Certification name</strong>
        <span>Issuer &bull; Date earned</span>
    </figcaption>
</figure>
```

The certification gallery scrolls horizontally on smaller screens and snaps to each card.

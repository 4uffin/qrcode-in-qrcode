# qrcode-in-qrcode

A recursive QR experiment.

This project generates realistic, functional URLs and converts them into QR codes — but once deployed to GitHub Pages, the project itself effectively becomes a QR code inside a QR code.

The generated QR can point to the hosted application, which then generates more QR codes recursively.

In practice:

```
QR Code
→ GitHub Pages URL
→ QR Generator
→ More QR Codes
```

The application becomes self-referential infrastructure.

## Features

* Functional HTTPS URL generation
* Real-world domain patterns
* Realistic enterprise-style paths
* Query parameter synthesis
* URL fragment generation
* QR rendering
* Copy/open URL controls
* Fully static architecture
* GitHub Pages compatible

## Recursive Concept

When hosted on GitHub Pages:

```
https://USERNAME.github.io/REPOSITORY/
```

A QR code pointing to that URL opens a page whose primary purpose is generating more QR codes.

Technically, the entire project becomes:

```
A QR code generator contained inside a QR code.
```

## Stack

* HTML
* CSS
* JavaScript
* QRCode.js

## Deployment

### GitHub Pages

1. Push repository to GitHub
2. Open repository settings
3. Navigate to Pages
4. Select the `main` branch
5. Save

The deployment URL becomes:

```
https://4uffin.github.io/qrcode-in-qrcode/
```

At that point, scanning a QR code for the site opens a QR code generator capable of generating additional QR codes indefinitely.

# Anyways...

Interested in helping?

[Contributing](CONTRIBUTING.md)

For legal purposes...

[LICENSE](LICENSE)

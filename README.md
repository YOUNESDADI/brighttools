# BrightTools — static website

BrightTools is a static website with six browser-based tools: image compressor, image resizer, word counter, case converter, password generator, and QR code generator.

## Files
- `index.html` — homepage and tools
- `about.html` — project information
- `contact.html` — feedback and bug reports
- `privacy.html` — current privacy disclosures
- `terms.html` — terms of use

## Publish
Upload all five HTML pages and this README to the root of the hosting repository. For GitHub Pages, select **Deploy from a branch**, branch `main`, folder `/(root)`.

## Before monetizing
- Review the privacy policy and terms for your real services and target audiences. They are starter templates, not legal advice.
- Update the privacy policy before adding analytics, ads, forms, or other third-party scripts.
- Check the hosting provider's terms for commercial use and advertising before monetizing.
- Test every tool on desktop and mobile, including downloads and keyboard accessibility.
- QR code generation depends on a third-party library loaded from a CDN.

## Privacy notes
Most tool processing happens in the browser. The QR tool loads a third-party library, and the static host may process technical logs. This version does not intentionally include analytics or advertising scripts.

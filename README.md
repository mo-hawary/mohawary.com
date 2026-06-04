# mohawary.com

Private staging repository for the GitHub Pages redirect to [mohawary.com](https://mohawary.com/).

This repository exists for a simple discovery purpose: when published, GitHub Pages should forward visitors and crawlers from the GitHub-hosted page to Mohamed ElHawary's canonical website.

## Canonical Links

- Website: https://mohawary.com/
- GitHub: https://github.com/mo-hawary
- LinkedIn: https://www.linkedin.com/in/mohawary

## SEO Notes

- `index.html` redirects to `https://mohawary.com/`.
- `404.html` redirects unmatched GitHub Pages paths to `https://mohawary.com/`.
- Both pages use `rel="canonical"` for `https://mohawary.com/`.
- Both pages use `noindex,follow` so search engines keep the canonical site, not this redirect shim.

Do not add a `CNAME` file here unless GitHub Pages is intended to host `mohawary.com` directly. The current purpose is redirect only.

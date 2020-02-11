# [ry.sb](https://ry.sb) URL shortener
[![Netlify Status](https://api.netlify.com/api/v1/badges/57f2be25-bb30-4f76-bc94-7223718324ff/deploy-status)](https://app.netlify.com/sites/relaxed-rosalind-7da7b3/deploys) [![status.rongyi.io](https://img.shields.io/badge/status-rongyi.io-green?logo=statuspage&style=flat-square)](https://status.rongyi.io)

This is my personal URL shortener built entirely on top of Netlify redirects.

## Current URLs
See the [`_redirects`](/_redirects) file for shortened URLs.

## Submit a new URL
Just open a pull request on Github, adding the URL to `_redirects` file, under the section that says `# Make a PR to add new ones here`

Be aware that your redirects might be modified/removed in the future if it collides with a path I potentially want (say we both want `/home` to point to our homepages, then I'll just take over)

## License
Doesn't matter.

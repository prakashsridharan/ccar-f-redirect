# ccar-f.pratechlabs.com redirect

The practice exam site moved to https://certprep.pratechlabs.com on 2026-10-04.
This repo only serves the old domain and forwards every request to the same
path on the new one (keeping query string and #hash, e.g. #admin).

- `index.html`, `ccar-f/`, `ccar-p/` - redirect pages for known paths.
- `404.html` - GitHub Pages serves this for any other path; its script still
  forwards to the matching path on the new domain.
- `google1d2e12cf818d8638.html` - keeps the old Search Console property
  verified. Do not delete.

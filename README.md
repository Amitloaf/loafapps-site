# loafapps-site

The public pages for Loaf Apps. **Deliberately public** — it exists so that
Google Play has a privacy policy URL to point at, and a policy nobody can read
is not a policy.

Nothing here is written by hand. `naipes/privacy/index.html` is generated from
`docs/privacy.md` in the (private) naipes repo by `tools/site.py`, so the
published policy cannot drift from the one that sits next to the code it
describes.

To update: change the markdown in the app repo, then

    python tools/site.py ../loafapps-site

and push. Served by GitHub Pages.

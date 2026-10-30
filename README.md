# mobile-app-legal

Public legal documents for a mobile app, served with GitHub Pages:

- Privacy Policy: https://vlad-j.github.io/mobile-app-legal/privacy-policy.html
- Terms of Service: https://vlad-j.github.io/mobile-app-legal/terms.html

## Do not edit these pages here

`privacy-policy.html` and `terms.html` are generated files. Their source is kept
in the app's own (private) repository, where a check fails the test suite if the
generated pages fall out of step with it. A change made here would be
overwritten by the next update, and would make the published policy differ from
the one shown inside the app.

To change a document: change it at the source, regenerate, then copy the two
generated files into this repository unchanged and commit them.

`index.html` (the list of documents), `.nojekyll` (serve the files exactly as
committed) and `.gitattributes` (keep LF line endings, so the published bytes
match the generated ones) belong to this repository.

# NextActivity Legal

Generated bilingual privacy and contact pages for NextActivity.

This repository is a generated publication target. Do not maintain the privacy
copy here. The only canonical source is:

`nextactivity/legal/privacy_policy.json`

Regenerate from the sibling app repository:

```powershell
dart run tool/generate_legal_content.dart --site-dir=..\nextactivity-legal
dart run tool/generate_legal_content.dart --check --site-dir=..\nextactivity-legal
```

The site contains no analytics, application JavaScript, remote fonts, or remote
images. It is ready to be served from the root of the public repository
`timofly27/nextactivity-legal` using
GitHub Pages branch deployment. No remote or Pages deployment is configured by
the generator.

The contact page is deliberately not presented as a complete or legally
reviewed imprint. That legal question remains a production-release blocker.

# MiniProgram Static Publish

This folder contains public/static delivery artifacts for `aws_backend_smoke_20260522193334`
version `1.0.0`.

Upload the contents of this folder to GitHub Pages, a CDN, S3 public hosting,
Cloudflare Pages, Netlify, Vercel static hosting, or another public static host.

GitHub Pages users should keep the generated `.nojekyll` file so generated
paths are served as normal static files. If this folder is committed inside a
larger Pages repo, also keep a `.nojekyll` file at the repo root.

Use the public URL for this folder as the endpoint base URI:

```dart
MiniProgramEndpoint.public(
  apiBaseUri: Uri.parse('https://your-cdn.example.com/public_mini_program/'),
)
```

Public static delivery is unauthenticated. Do not publish private data or
business-only mini-programs with this mode. Use protected AWS/GCP/backend
delivery with a MiniProgram access key for production partner access control.

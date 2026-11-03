SARTHAK TOY MART — VERCEL PACKAGE

1. Extract this ZIP.
2. Upload/deploy the folder containing index.html to Vercel.
3. In Vercel, make sure the Project Root Directory is the folder containing index.html.
4. For a plain HTML site, leave the Framework Preset as Other and do not set a build command.

IMPORTANT:
- index.html is the original uploaded HTML, copied without changing its contents.
- The original admin/login/product/order code has NOT been removed from this file.
- The original file calls claude.use('db'), claude.use('assets'), and claude.use('artifact').
  Those are external Claude-hosted integrations and are not automatically provided by Vercel.
  Therefore, admin database, uploads, and publishing may still need a compatible backend
  before those features can work on Vercel.
- This package fixes the common homepage filename issue by naming the entry page index.html;
  it does not claim to migrate or replace the original backend.

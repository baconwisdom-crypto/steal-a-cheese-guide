# Steal a Cheese Wiki

Source: `I:\游戏站\steal-a-cheese`

Production host: https://www.stealacheese.wiki

Repository: https://github.com/baconwisdom-crypto/steal-a-cheese-guide

Cloudflare Pages project: `steal-a-cheese-guide`, production branch `main`, build command `npm run verify`, output `out`, Node 22.23.2. A real Git push triggers production builds. Pages preview hosts send a noindex response header; formal routes contain unique static titles, descriptions, canonical URLs and article HTML.

The framework lives in `framework/`, site and domain data in `config/site.json`, editorial content and clean source bindings in `content/`. Research, raw media, account receipts and generated output are ignored by Git. Artwork is official Roblox artwork. Gameplay screenshots are compressed original frames with committed source, timestamp and section bindings.

Run `npm run verify` before a push. It builds all nine routes, checks distinct titles, verifies committed video evidence and runs the shared scheduled-ad unit tests. Complete source verification also includes the isolated negative cases retained in `research/release/video-evidence-isolated-check.json` and the Chrome responsive audit.

Advertising reuses the common reference-template runtime. Each unit must come from this exact domain's verified five-format code bundle. The permanent absolute `enableAt` is the first verified formal publication timestamp plus 48 hours; updates must preserve it. Missing codes and future dates leave no ad frame or layout gap. The 160×600 rail has a 192px column on at least 1280×700 screens and is sticky at 100px. Hidden desktop units make no mobile request.

Rollback content by reverting the relevant commit or selecting a prior successful Pages deployment. Domain changes require the saved DNS snapshot and DNSSEC timing evidence. Keep `research/release/` for first publication, deployment, analytics, GSC, ad approval and cloud reminder receipts. Google indexing, ad fill and ad revenue require separate observations.

# curfew-software.github.io

The published landing page for **Curfew**, a system-wide app and website blocker for
Windows 10 and 11.

Live at **https://curfew-software.github.io/**

## Do not edit these files here

This repository is a publish target, not a source. Everything in it is generated from the
`site/` directory of the Curfew source repository and pushed by `site/publish.sh`, which
force-pushes. Changes made directly here will be destroyed on the next publish.

`legal/*.html` are themselves generated from `docs/legal/*.md` by `site/build-legal.py`.

## Custom domain

When `curfew.alexandermcfadden.com` is pointed here (Cloudflare `CNAME` →
`curfew-software.github.io`, proxy off), update the canonical link and `og:url` in
`site/index.html`, plus `site/robots.txt` and `site/sitemap.xml`, in the source repository.

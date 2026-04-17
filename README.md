# jkeesh.com

Visit https://jkeesh.com

Personal short-domain landing page — static HTML with a grid of hats that colorize on hover (desktop) or tap (mobile).

### Stack

Pure static HTML + a single base image (`hats_bw.png`) with pixel-positioned `<div>` hit-boxes layered on top. Hovering or tapping a hit-box swaps its background to the colored version of that hat. Responsive: a tiny bit of JS scales the 1500×600 stage down to fit narrow viewports.

### Deploying

    # to GitHub
    git push origin master

    # to the live site (new Linode — auto-deploys via post-receive hook)
    git push web master

### Remotes

- `origin` → GitHub (`jkeesh/jkeesh.com`)
- `web` → `ssh://jkeesh@172.234.29.183/home/jkeesh/repos/jkeesh.git` (new Linode, moved from old thekeesh.com server on 2026-04-17)

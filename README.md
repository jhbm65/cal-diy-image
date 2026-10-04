# cal-diy-image

Builds [Cal.diy](https://github.com/calcom/cal.diy) (MIT) from source with GitHub Actions and publishes the image to GHCR as `ghcr.io/<owner>/cal.diy`. Upstream publishes no prebuilt image.

To build: Actions, "Build Cal.diy image", Run workflow, and give the upstream commit to build. The image is tagged with the short commit SHA and `latest`.

This repository holds no application code and no secrets.

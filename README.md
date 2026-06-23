# gpmf-studio-releases

This repo holds no application source. It exists only to:

1. Run CI (`.github/workflows/build.yml`) that checks out the private
   `GPMFStudio` source via a read-only deploy key, builds installers for
   macOS, Windows, and Linux, and publishes them as GitHub Release assets.
2. Host those Release assets for download.

The download page is at https://felipecabargas.github.io/gpmf-studio-site.

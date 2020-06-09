pkgbuilds
=========

PKGBUILDs for [Arch AUR](https://aur.archlinux.org/) packages I maintain. I use
[aurpublish](https://github.com/eli-schwartz/aurpublish) to manage AUR
repositories in this GitHub repository.

## CONTRIBUTING
---------------

If you would like to contribute to this repo and have more than 15 lines of code
of contribution, please sign the file `WAIVER` under the repo's root directory
with

```
$ gpg --no-version --armor --output AUTHORS/WAIVER-signed-by-<name>.asc --clearsign AUTHORS/WAIVER
```

Replace `<name>` with your name or username. Make sure the public key of which
you use for signing can be found from public servers or obtained from you. Next,
add/commit/push the newly generated & signed file (i.e., `WAIVER-signed-by-xxxxxxxx.asc`).

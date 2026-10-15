# easy-cc-autofill
Forgot your stored CC details, but can't access them? Use this to prompt your browser's autofill and copy them.

## Link preview

`assets/og.png` is the 1200×630 image link unfurls show. Its source is `scripts/og.html`, which reuses the site's stylesheets. `assets/icon.svg` is the favicon, and `assets/icon-32.png` and `assets/icon-180.png` (Apple touch icon) are renders of it. To regenerate the preview image, run this from the repo root:

```sh
"/Applications/Google Chrome.app/Contents/MacOS/Google Chrome" --headless --hide-scrollbars \
  --force-device-scale-factor=1 --window-size=1200,630 --virtual-time-budget=2000 \
  --allow-file-access-from-files --screenshot="$PWD/assets/og.png" "file://$PWD/scripts/og.html"
```

## Meta Preview

<!-- meta-preview https://tuckerchap.in/easy-cc-autofill/ -->
> <a href="https://tuckerchap.in/easy-cc-autofill/"><img src="https://tuckerchap.in/favicon.ico" width="16" height="16" alt=""></a> Easy CC Autofill
>
> **[Easy CC Autofill](https://tuckerchap.in/easy-cc-autofill/)**
<!-- /meta-preview -->

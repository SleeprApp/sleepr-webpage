# sleepr-webpage (legacy — redirect only)

This repo used to host the Sleepr Privacy Policy at <https://sleeprapp.github.io/sleepr-webpage/>.

The canonical Privacy Policy now lives at **<https://sleeprapp.org/privacy>**, served from the marketing site in [`SleeprApp/sleepr-website`](https://github.com/SleeprApp/sleepr-website).

`index.html` here is now just a meta-refresh + JS redirect to the new URL. It exists because Sleepr v1.0 ships with this URL hardcoded in `LegalLinks.privacyPolicyURL` (`Sleepr/Views/Auth/TermsOfServiceView.swift`). v1.1 onwards points directly at `sleeprapp.org/privacy`, so this redirect only matters until v1.0 installs are gone.

`Sleepr_Privacy_Policy.pdf` is kept here so any direct PDF link out in the wild still resolves.

**Do not delete this repo** until v1.0 is fully retired from the App Store install base.

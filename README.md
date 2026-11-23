# Basement Datacenter app links

The Play App Signing certificate belongs in the `target.sha256_cert_fingerprints` array beside the upload certificate. When Play assigns it, append the actual SHA-256 from the app signing key certificate in Play Console to `android/assetlinks.json` in the game source, commit the change, then run `bash tools/publish-site.sh --asset-links`.

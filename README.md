# Mom, It's a Startup app links

The upload certificate and Play app signing certificates are listed in `target.sha256_cert_fingerprints`. If Play adds a signing certificate, append its SHA-256 from Play Console to `android/assetlinks.json` in the game source, keep the existing certificates, commit the change and run `bash tools/publish-site.sh --asset-links`.

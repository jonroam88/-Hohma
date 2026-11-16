# Hohma — Microsoft Store release checklist

**Status:** Draft; not submitted, not certified.

## Public app
- The public Store candidate must exclude private Einstein enrollment code, PINs, credentials, account databases and test profiles.
- Review visual assets and licenses; verify attribution.
- Test planet explorer, Apollo markers, Birth Sky, NOAA imagery, ISS/Starlink availability and offline behavior on Windows.
- Verify privacy-policy statements against actual application behavior.

## Windows packaging
- Build EXE on Windows using BUILD_WINDOWS_EXE.cmd.
- Run and test the compiled EXE on a clean Windows installation.
- Build MSIX using BUILD_STORE_MSIX.cmd and Partner Center package identity / publisher.
- Validate installation, uninstall, permissions, network errors and package architecture.

## Partner Center
- Fill pricing, properties, age rating, package, listing and privacy policy URL.
- Confirm public support contact and HTTPS website.
- Upload the tested MSIX and submit for certification only after gates pass.

**Private family development:** Keep Einstein files in a private location; do not commit secrets to the public repository.

AskApt repository generated successfully.

This v0.1 repository is UNSIGNED. For private/testing use, after hosting it over HTTPS,
APT can be pointed at it with a source like:

  deb [trusted=yes] https://YOUR-HOST/YOUR-PATH stable main

Then run:
  sudo apt update
  sudo apt install askapt

For public distribution, sign the Release metadata and distribute a signing key instead of using trusted=yes.

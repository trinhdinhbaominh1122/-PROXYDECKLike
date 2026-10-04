# PROXYDECK Like — GitHub build

## Build IPA

1. Create a GitHub repository.
2. Upload the contents of this folder to the repository.
3. Open **Actions**.
4. Select **Build unsigned IPA**.
5. Press **Run workflow**.
6. When it finishes, open the workflow run and download the artifact:
   `PROXYDECKLike-IPA`
7. The artifact contains `PROXYDECKLike.ipa`.

The workflow builds for `iphoneos` on a GitHub-hosted macOS runner with
Apple's Xcode toolchain and disables code signing. The resulting IPA is
unsigned and must be signed with a compatible certificate/provisioning
profile before installation.

This project is an original safe implementation and does not contain the
kernel exploit or sandbox-escape code from the supplied IPA.

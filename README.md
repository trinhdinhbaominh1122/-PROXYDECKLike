# PROXYDECK Like

Safe SwiftUI project inspired by the supplied app's general proxy/DNS concept.

Bundle ID:
com.example.proxydecklike

Minimum iOS:
16.0

This project intentionally does not contain kernel exploit, kernel R/W,
sandbox escape, or copied proprietary executable code.

## Build
Open `PROXYDECKLike.xcodeproj` in Xcode on macOS, select an iPhone/iPad
device (not a simulator), and build/archive the app. Apple documents that
an iOS archive is produced from a real-device/build-only destination and
can then be exported as an IPA.

For ESign-style signing, the exported app must first contain a valid
Mach-O executable and then be re-signed with an appropriate certificate/
provisioning profile.

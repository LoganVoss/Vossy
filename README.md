# Vossy

A macOS SwiftUI project containing the **NotchGlow** Xcode app target.

## Current state

The current app entry point opens a window containing the starter SwiftUI globe and “Hello, world!” view. The repository also contains unit-test and UI-test targets. This is a starting point, not a description of finished notch effects.

## Open the project

1. Open `NotchGlow.xcodeproj` in Xcode.
2. Select the **NotchGlow** scheme and a Mac destination.
3. Build and run with **Product → Run**. Signing settings may need to be adjusted for your development team.

The project settings specify macOS 15.4 as the deployment target and record Xcode 16.3 as the creation tools version. Builds and tests have not been verified as part of this documentation update.

## Repository layout

- `NotchGlow/` — app entry point, SwiftUI view, and app resources
- `NotchGlowTests/` — unit-test target
- `NotchGlowUITests/` — UI-test target
- `NotchGlow.xcodeproj/` — Xcode project and build settings

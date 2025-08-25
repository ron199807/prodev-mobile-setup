# Mobile Development Setup with Expo Go

## Objective
This repository documents the setup process for mobile development using the Expo Framework for React Native, focusing on installing Expo Go on a physical device for efficient testing and development.

## Prerequisites
- ✅ **Node.js LTS** (v18.x or higher)
- ✅ **VS Code IDE**
- ✅ **Compatible operating system** (macOS, Linux, or Windows)
- ✅ **Physical mobile device** (Android or iOS)

## Expo Go Installation Process

### Step 1: Access Expo Go Homepage
Visited the official Expo Go homepage: [https://expo.dev/go](https://expo.dev/go)

### Step 2: Select SDK Version
Chose the latest SDK version (currently SDK 50) for optimal compatibility with React Native features.

### Step 3: Device Installation

#### For Android:
1. Clicked "Install" button redirecting to Google Play Store.
2. Installed "Expo Go" app (Size: ~45MB).
3. App successfully installed on physical Android device.

#### For iOS:
1. Clicked "Install" button redirecting to Apple App Store.
2. Installed "Expo Go" app (Size: ~50MB).
3. App successfully installed on physical iOS device.

### Step 4: Initial Setup
1. Opened Expo Go app on device.
2. Created new Expo account using email authentication.
3. Completed profile setup.
4. Successfully logged into the application.

## Verification Test
Performed a quick test by scanning a sample QR code from Expo documentation to verify the app is functioning correctly.

## Challenges Faced

### During Installation:
1. **Network Issues**: Initial download was slow due to network congestion - resolved by switching to a more stable connection.
2. **Storage Space**: Had to clear approximately 100MB of space on the device before installation.
3. **Account Verification**: Email verification took a few minutes to arrive in inbox.

### Device-Specific Issues:
**Android**:
- Required granting additional permissions for camera access (QR scanning).
- Needed to enable "Install from unknown sources" temporarily.

**iOS**:
- Required iOS 13 or higher (device was compatible).
- Needed to grant camera permissions through iOS settings.

## Troubleshooting Solutions

1. **If app crashes on launch:**
   - Clear app cache/data.
   - Reinstall the application.
   - Ensure device meets minimum OS requirements.

2. **If QR code scanning doesn't work:**
   - Check camera permissions.
   - Ensure good lighting conditions.
   - Clean camera lens.

3. **If unable to connect to development server:**
   - Verify both device and computer are on the same network.
   - Check firewall settings.
   - Restart Expo development server.

## Next Steps
- [ ] Set up a new React Native project with Expo.
- [ ] Test hot-reload functionality.
- [ ] Experiment with basic components on physical device.
- [ ] Explore Expo SDK features and APIs.

## Resources
- [Expo Documentation](https://docs.expo.dev/)
- [React Native Documentation](https://reactnative.dev/docs/getting-started)
- [Expo Community Forums](https://forums.expo.dev/)

## System Information
- **Node.js Version:** v18.17.0
- **npm Version:** 9.6.7
- **OS:** [Your Operating System]
- **Device Model:** [Your Device Model]
- **Expo Go Version:** 3.0.14

---
*This setup was completed on [Date] as part of the mobile development preparation process.*
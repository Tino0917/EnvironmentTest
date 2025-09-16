# Environment Setup Documentation

## System Specifications
- **Operating System:** Windows 11
- **RAM:** 16 GB
- **Storage:** 512 GB SSD
- **Processor:** Intel Core i7-1165G7
- **Administrative Privileges:** Yes

## Software Versions Installed
- **Node.js:** v20.17.0
- **npm:** 11.0.0
- **React Native CLI:** @react-native-community/cli
- **Android Studio:** AI-251.26094.121.2513.14007798
- **Java JDK:** 21.0.7
- **Git:** 2.45.0
- **VS Code:** 1.10


## Setup Steps Followed

### 1. Node.js Installation
- Downloaded Node.js LTS version from official website
- Verified installation with `node --version` and `npm --version`

### 2. React Native Setup
- Installed React Native CLI using: `npm install -g @react-native-community/cli`
- Created project with: `npx @react-native-community/cli init EnvironmentTest`

### 3. Android Development Environment
- Installed Android Studio with default settings
- Configured Android SDK with:
  - Android SDK Platform 33 (Android 13)
  - Android SDK Build-Tools 33.0.0
  - Android Emulator
  - Android SDK Platform-Tools
- Set environment variables:
  - ANDROID_HOME: `C:\Users\tinom\AppData\Local\Android\Sdk`
  - Added platform-tools to PATH
- Created Android Virtual Device (Pixel 4 API 33)

### 4. Development Tools
- Installed Visual Studio Code
- Added extensions:
  - React Native Tools
  - ES7+ React/Redux/React-Native snippets
  - Auto Rename Tag
  - Bracket Pair Colorizer

## Deviations from Lab Instructions

1. **Used newer React Native initialization command** instead of deprecated `react-native init`
2. **Required specific NDK version (27.0.3)** instead of what was initially expected
3. **Project created with TypeScript template** initially, requiring conversion to JavaScript
4. **Higher Android SDK versions** used due to newer tooling requirements

## Time Taken for Each Step

- **Node.js setup:** 15 minutes
- **Android Studio installation:** 45 minutes
- **SDK and emulator configuration:** 30 minutes
- **Project creation and troubleshooting:** 2 hours
- **Environment variable setup:** 15 minutes
- **Testing and verification:** 30 minutes


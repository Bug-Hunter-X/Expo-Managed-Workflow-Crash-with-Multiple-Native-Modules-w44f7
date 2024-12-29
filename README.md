# Expo Managed Workflow Crash with Multiple Native Modules

This repository demonstrates a bug where an Expo managed workflow application crashes during the build process or immediately after installation. The crash is likely caused by conflicts between numerous native modules or problems with linking them correctly.  The primary cause may be related to dependency versioning or incorrect configuration within the `package.json` file and the build process itself.

## Steps to Reproduce

1. Clone this repository.
2. Run `npm install` or `yarn install`.
3. Attempt to start the application using `expo start`.
4. Observe the crash during the build or at launch.

## Solution
This bug requires careful examination of the native module dependencies.   The solution is generally a process of identifying conflicting packages or resolving discrepancies in their native module configurations.  Tools such as `react-native-info` can help analyze the project's dependencies.
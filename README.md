# Expo CLI Error: Dependency Mismatch with Expo SDK

This repository demonstrates a common error encountered when using Expo CLI: a dependency mismatch with the Expo SDK version. The error is characterized by unexpected build failures or runtime errors resulting from missing modules or incompatible APIs.  The root cause often involves outdated package versions or incorrect configuration.

## Steps to Reproduce

1. Clone this repository.
2. Attempt to run `expo start`.
3. Observe the error related to dependency mismatch.

## Solution

The provided `bugSolution.js` shows how to resolve this error by updating dependencies to versions compatible with the Expo SDK or by correctly configuring the project to use the right API versions. This might involve updating `package.json`, checking `app.json` for compatibility settings, or removing conflicting packages.
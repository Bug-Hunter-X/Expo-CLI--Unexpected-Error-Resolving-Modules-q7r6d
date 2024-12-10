# Expo CLI: Unexpected Error Resolving Modules

This repository demonstrates a common error encountered when using the Expo CLI: an unexpected error during module resolution.  This usually stems from dependency conflicts, incorrect Metro bundler configuration, or problems with the Expo installation itself.

## Problem

When attempting to run an Expo CLI command (e.g., `expo start`), the command fails with a cryptic error message that mentions problems resolving modules. The exact error message can vary but often points to missing or mismatched dependencies.

## Solution

This repository provides a problematic `package.json` and `metro.config.js` and shows how to resolve the issue.  The solution often involves carefully examining the `package.json` for dependency conflicts, ensuring that all necessary packages are installed correctly, and verifying that the `metro.config.js` (if present) is correctly configured.  In some cases, reinstalling Expo or clearing the cache might be needed.

## Setup

1. Clone this repository.
2. Navigate to the project directory using your terminal.
3. Install the dependencies: `npm install`
4. Attempt to run Expo using `expo start`. Observe the error.
5. Implement the solution from `bugSolution.js` which demonstrates correcting any dependency issues or Metro bundler configuration. 
6. Rerun `expo start` to verify that the error is resolved. 
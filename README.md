# React Native Dimensions API Undefined Issue

This repository demonstrates a common error encountered when using the `Dimensions` API in React Native: accessing dimensions before the component has fully mounted, resulting in `undefined` values.

## Problem

The `Dimensions` API provides screen dimensions.  However, directly accessing these values before the component's mount lifecycle may result in unexpected behavior (e.g., crashes, incorrect calculations).

## Solution

The solution involves leveraging the `useEffect` hook to access dimensions after the component has mounted. This ensures the values are defined before using them.

## Usage

1. Clone the repository.
2. Navigate to the project directory.
3. Run `npm install` to install dependencies.
4. Run `npx react-native run-android` or `npx react-native run-ios` to start the app. 

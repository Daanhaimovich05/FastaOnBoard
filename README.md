# FASTA — Achieve Your Goals

A React + TypeScript fitness trainer discovery platform.

## Getting Started

```bash
npm install
npm run dev
```

Open http://localhost:3000

## Stack
- React 19 + TypeScript
- Vite 6
- Tailwind CSS
- Leaflet (map view)

## Bug Fixes Applied
1. Trainer average rating now updates live after a review is submitted
2. Price filter now correctly filters on both min AND max price
3. Verification code is no longer exposed in the UI toast
4. Dashboard now safely redirects unauthenticated users to login

## For Capacitor (iOS/Android)
```bash
npm install @capacitor/core @capacitor/cli @capacitor/ios @capacitor/android
npx cap init
npm run build
npx cap add ios
npx cap add android
npx cap open ios   # opens Xcode
npx cap open android  # opens Android Studio
```

# Project Index

## Overview
This repository is a React Native Expo application named `DoNow` using Expo Router-based file-based navigation.

## Runtime and Framework
- Package manifest: package.json
- Expo configuration: app.json
- TypeScript configuration: tsconfig.json
- Styling and linting: eslint.config.js

## App Structure

### Application entry and routing
- Root layout: app/_layout.tsx
- Root modal route: app/modal.tsx
- Tab layout: app/(tabs)/_layout.tsx
- Home screen: app/(tabs)/index.tsx
- Explore screen: app/(tabs)/explore.tsx

### Main navigation model
The app uses Expo Router with a tab navigator inside app/(tabs) and a stack root layout exposing modal support. The home route anchors to the tabs layout.

## Components
Key reusable UI components placed under components/:
- app-level UI wrappers: components/themed-view.tsx, components/themed-text.tsx
- Expo-specific interactions: components/external-link.tsx, components/haptic-tab.tsx
- animated/parallax examples: components/hello-wave.tsx, components/parallax-scroll-view.tsx
- icon component: components/ui/icon-symbol.tsx, components/ui/icon-symbol.ios.tsx
- collapsible UI element: components/ui/collapsible.tsx

## Constants, Assets, and Hooks
- Theme palette and shared constants: constants/theme.ts
- Color-scheme hooks: hooks/use-color-scheme.ts, hooks/use-color-scheme.web.ts
- Theme color hook: hooks/use-theme-color.ts
- Static assets: assets/images/

## NPM Scripts
- start: expo start
- android: expo start --android
- ios: expo start --ios
- web: expo start --web
- lint: expo lint
- reset-project: node ./scripts/reset-project.js

## Status
The workspace currently contains a generated Expo starter UI, not a finished TODO-specific UI implementation. The main developing zone is the app directory, especially the tab-based screens.

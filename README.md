# DoNow

DoNow is a React Native Expo application for managing daily tasks and to-do items. The project currently uses Expo Router with a tab-based layout and a modal screen placeholder.

## Project Status

This repository is in an early scaffold stage. The Expo starter UI is present, and the folder structure is set up for a task-management application.

## Tech Stack

- React Native
- Expo SDK
- Expo Router
- TypeScript
- React Navigation

## Getting Started

Install dependencies:

```bash
npm install
```

Start the development server:

```bash
npm start
```

Or run platform-specific development commands:

```bash
npm run android
npm run ios
npm run web
```

## Scripts

The available scripts are defined in [package.json](package.json):

- `npm start` - launch Expo development server
- `npm run android` - start the Expo project in Android mode
- `npm run ios` - start the Expo project in iOS mode
- `npm run web` - start the Expo project for web
- `npm run lint` - run Expo linting
- `npm run reset-project` - restore or reset the Expo starter project

## App Structure

```text
app/
  _layout.tsx          Root Expo Router layout
  modal.tsx            Modal screen
  (tabs)/
    _layout.tsx        Tab navigation layout
    index.tsx          Home screen
    explore.tsx        Explore screen
components/            Reusable UI and screen helpers
constants/            Theme configuration
hooks/                Theme and color-scheme hooks
assets/images/        App assets and images
```

## Development Notes

The application is configured with file-based routing using Expo Router. The home screen and the explore tab are mapped in the tabs layout under the app directory.

## License

This project is currently a private/development workspace and does not define a package license yet.

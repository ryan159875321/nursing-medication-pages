# Internal Testing

## Prerequisites

- Expo account
- Apple Developer account for iOS device/TestFlight distribution
- Google Play Console account for Android internal testing
- Supabase project if testing backend auth/progress sync

## Configure Environment

Copy `.env.example` to `.env` and fill in:

```bash
EXPO_PUBLIC_SUPABASE_URL=
EXPO_PUBLIC_SUPABASE_ANON_KEY=
```

If these are missing, the app falls back to local-only auth and local progress.

## Configure EAS

```bash
npx eas-cli login
npx eas-cli build:configure
```

## Internal Builds

```bash
npx eas-cli build --profile preview --platform ios
npx eas-cli build --profile preview --platform android
```

## Production Builds

```bash
npx eas-cli build --profile production --platform ios
npx eas-cli build --profile production --platform android
```

## Submit

```bash
npx eas-cli submit --profile production --platform ios
npx eas-cli submit --profile production --platform android
```

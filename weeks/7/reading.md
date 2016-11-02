# Getting Started With Firebase

If you don't already have one, set-up an account at firebase.google.com.

## Firebase Hosting Setup

1. Create a new project.
2. Build the production code for your application from the command-line, using `npm run build`.
3. Run `firebase init` - when prompted for a location for the public directory, type `build`. Accept all other defaults.
4. `firebase deploy`

## Firebase Database Setup

1. In the Firebase console, under "Database", select the tab that says "Rules"
2. Change the part that reads `auth != null` to `true`. The finished rules should look like this:

```
{
  "rules": {
    ".read": "auth != null",
    ".write": "auth != null"
  }
}
```

3. Hit "Publish"
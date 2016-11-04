# Getting Started With Firebase

If you don't already have one, set-up an account at firebase.google.com and install the Firebase command-line tools using:

```
npm install -g firebase-tools
```

## Firebase Hosting Setup

1. Create a new project.
2. Build the production code for your application from the command-line, using `npm run build`.
3. Run `firebase init` - unselect "Database" and, when prompted for a location for the public directory, type `build`. Accept all other defaults.
4. `firebase deploy`

## Firebase Database Setup

1. In the Firebase console, under "Database", select the tab that says "Rules"
2. Change the part that reads `"auth != null"` to `true` and hit "Publish". The finished rules should look like this:

```
{
  "rules": {
    ".read": true,
    ".write": true"
  }
}
```

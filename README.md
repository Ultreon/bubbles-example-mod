# Bubble Blaster Example Mod

## Setup
1. Create an access token on GitHub with `packages:read`.
2. Put the username and access token in `<USER-DIR>/.gradle/gradle.properties` like this:
   ```properties
   gpr.user=<USER_NAME>
   gpr.key=<ACCESS_TOKEN>
   ```
   Where `<USER_NAME>` is the GitHub username, and ` <ACCESS_TOKEN>` is the access token added.

**Make sure to set `gpr.key` again when the access token expires.**

## Build
1. Sync the project using the 🔃 button in the gradle tool-window.
2. Run the `gradle build` task.

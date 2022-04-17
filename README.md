![Social Media Preview](https://user-images.githubusercontent.com/6172851/163731801-48e9da3b-b828-4517-9c20-2da7ec01543f.png)


Quickly toggle your Mac's System Appearance via Spotlight (Command–Space bar).

https://user-images.githubusercontent.com/6172851/163730882-2a3d6349-65f4-4579-b5b7-7e515a9148d3.mov

## The Code

This is the entire script, there's not much to it.

```AppleScript
tell application "System Events" to tell appearance preferences
  set dark mode to not dark mode
end tell
```

# Focus - A Pomodoro App Extension
{
  "name": "Focus",
  "description": "A Pomodoro Extension that helps you increase your productivity",
  "version": "1.0",
  "manifest_version": 2,

  "browser_action": {
    "default_popup": "index.html"
  },
  "permissions": ["storage", "unlimitedStorage"],
  "background": {
    "scripts": ["background.js"],
    "persistent": false
  }
}

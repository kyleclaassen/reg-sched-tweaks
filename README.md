# Rose-Hulman reg-sched tweaks
An addon to make the schedule lookup page a little better.  More info coming soon.

## Installation

## Usage and Features

### On the main lookup page

### When viewing all sections of a class (schedule grid)

### When viewing all sections of a class (roster)

### When viewing a class (section) roster
* A new "View All Sections" button is available to quickly navigate to seeing the roster for all sections of a given class.

### On the "ad-hoc group schedules" page

## Development
Some information about developing extensions and testing them is [here](https://extensionworkshop.com/documentation/develop/getting-started-with-web-ext/#testing-out-an-extension)

You'll probably want to install Node.js, and then use the `web-ext` node package to configure and run.

### Setup
Install Node.js and web-ext.  Then, create a Firefox profile for testing, using the profile management screen:

- on linux/mac: `firefox --no-remote -P`
- on windows powershell: `& 'C:\Program Files\Mozilla Firefox\firefox.exe' --no-remote -P`

### Running to debug
Once a profile is created, use web-ext to run it:
```
web-ext run --keep-profile-changes --firefox-profile=<profilename>
```

Or you can use the VS Code "Debugger for Firefox" extension and the `.vscode/launch.json` file provided in this repo.
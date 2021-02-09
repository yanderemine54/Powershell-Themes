# Powershell Themes
These are my custom Powershell Themes

## Frost Powershell
A theme based around the frost theme, but in the Powershell style.

Screenshot:

![Screenshot](docs/screenshots/Frost%20Powershell.png)

### Install

Go to the Windows Terminal (If you haven't already, download it [here](https://aka.ms/terminal))

Then inside it, go to the arrow and click settings.

Normally it will open a JSON file in your default text editor.

Locate the schemes section and paste the following code inside it :
`{
            "name" : "Frost Powershell",
            "background" : "#012456",
            "black" : "#3a3a3a",
            "blue" : "#17b2ff",
            "brightBlack" : "#0a0a0a",
            "brightBlue" : "#27B2F6",
            "brightCyan" : "#13A8C0",
            "brightGreen" : "#89AF50",
            "brightPurple" : "#760af2",
            "brightRed" : "#ff1100",
            "brightWhite" : "#ffffff",
            "brightYellow" : "#e6ff04",
            "cyan" : "#3C96A6",
            "foreground" : "#EEEEEE",
            "green" : "#6AAE08",
            "purple" : "#5d0597",
            "red" : "#c00e0e",
            "white" : "#fcf5f5",
			"yellow" : "#c5d816"
}`

### Adding the theme

To add the themes reopen the settings file, then locate the profile you want to edit.

Just add or modify the `colorScheme` property to `colorScheme : "Frost Powershell"`.

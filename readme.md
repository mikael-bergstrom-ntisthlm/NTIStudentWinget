AI Disclusure: None of this was vibe coded, but I did use Gemini to dig out some of the options and settings. Winget configurations are incredibly badly documented and it's pretty hard to find reliable information.

# Installing

In an administrative Terminal/Powershell (easiest: Right click Windows icon, choose Terminal (Admin)):

```
winget configure --enable

winget configure -f https://raw.githubusercontent.com/mikael-bergstrom-ntisthlm/NTIStudentWinget/refs/heads/main/ntistudent.winget
```

After a little while, it will ask if you're sure you want to apply this configuration. Press 'y'.

# What it does

**Installs:**
- Powershell 7 (In Program Files)
- [OBS Studio](https://obsproject.com/)
- .NET SDK 10
- Visual Studio Code (including context menus)
- Some Visual Studio Code extensions
  - [C# Dev Kit](https://marketplace.visualstudio.com/items?itemName=ms-dotnettools.csdevkit)
  - [Gitignore](https://marketplace.visualstudio.com/items?itemName=codezombiech.gitignore)
  - [NuGet Gallery](https://marketplace.visualstudio.com/items?itemName=patcx.vscode-nuget-gallery)
  - [Hide Comments](https://marketplace.visualstudio.com/items?itemName=eliostruyf.vscode-hide-comments)
  - [Thunder Client](https://marketplace.visualstudio.com/items?itemName=rangav.vscode-thunder-client)
  - [Visual Code Icons](https://marketplace.visualstudio.com/items?itemName=vscode-icons-team.vscode-icons)

**Windows Explorer settings:**
- Show hidden files
- Show file extensions

**Visual Studio Code user settings:**
- Disable AI
- Set C# debug console to External Terminal
- Disable CodeLens reference counter
- Turn off "modern UI"
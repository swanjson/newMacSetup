# Mac Settings
- Dark window theme / colored highlight/accent
- Trackpad four fingers and right click
- Download Chrome (Set default browser to chrome)
- Setup appleID and messages
- Battery Percentage
- Terminal (after ZSH install):
	- Preferences:Profile:Window:Title:"Wayne Enterprises - Special Projects"
	- Preferences:Profile:Window:WindowSize:95x20

# Downloads
- Chrome: See below section
- Homebrew
	- Install CLI tools for Xcode: (`xcode-select —-install`)
	- Install homebrew: (`/usr/bin/ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"`)
- ZSH: See below section.
- VLC
- Spotify
- CheatSheet (mac keyboard shortcuts)
- Update Xcode?
- Stickies
- 1password
- Sublime Text
- Visual Studio Code (dark theme) (also setup command line 'code .' command) (https://code.visualstudio.com/)
- Node.js
- Better Snap Tool (setup corners, thirds and two-thirds) (dark highligh color)
- Amphetamine
- Alphred
- TexShop
- Microsoft Office
- Python3
	- (pip3)
- Tableau Public (free data viz)
- Steam
	- xbox controller driver (https://github.com/360Controller/360Controller/releases)
- JS Stuff (watch for downloading privileges, might not download on secure network)
	- npm/npx (https://www.npmjs.com/)
	- yarn
	- eslint (https://eslint.org/)
	- prettier (https://github.com/prettier/prettier)
	- Postman (https://www.getpostman.com/)
- (Possible other work stuff)
	- Slack/Discord
	- Zoom meeting

# ZSH (Z-Shell for terminal)
- Download homebrew first then: `brew install zsh` `sh -c "$(curl -fsSL https://raw.githubusercontent.com/robbyrussell/oh-my-zsh/master/tools/install.sh)"` `upgrade_oh_my_zsh`(https://medium.freecodecamp.org/how-to-configure-your-macos-terminal-with-zsh-like-a-pro-c0ab3f3c1156)
- Install powerline fonts (https://github.com/powerline/fonts)
```bash
git clone https://github.com/powerline/fonts.git
cd fonts
./install.sh
```
- Font: Meslo LG L Bold for Powerline
- Theme: Homebrew
- Edit `~/.zshrc` file for customs:
	- change theme to `ZSH_THEME="agnoster"` (https://github.com/agnoster/agnoster-zsh-theme)
	- add `DEFAULT_USER=`whoami` ` to make the terminal prompt blank
	- add `DISABLE_AUTO_TITLE="true"` to keep original terminal window title
	- Add new paths by putting them in `~/.zshrc` file as:
```bash
export PATH=/Users/jay.swanson/scriptStuff/adbScripts/testingAdbScripts/:$PATH
```

# Set file extensions to open with Sublime Text
- .txt
- .json
- .xml
- .md
- .csv

# Chrome and Extensions
- Dark Theme (Inspect feature too)
Extensions:
- Violentmonkey (Script for dark theme GitHub: https://raw.githubusercontent.com/StylishThemes/GitHub-Dark-Script/master/github-dark-script.user.js)
- JSON Formatter
- Text Blaze
- Redux DevTools
- Google Keep
- Google Docs Offline
- Ad Block (ad block plus)





### [Xcode](https://developer.apple.com/xcode)

#### Git Installation

Clone the repository to stay updated:

```bash
git clone https://github.com/dracula/xcode.git
```

#### Manual Installation

Download the [GitHub `.zip` file](https://github.com/dracula/xcode/archive/main.zip) and extract it.

#### Homebrew Installation

Install via [dracula/homebrew-install](https://github.com/dracula/homebrew-install/blob/master/Casks/dracula-xcode.rb):

```bash
brew tap dracula/install
brew install --cask dracula-xcode
```

#### Theme Setup

**For Git/Manual installations only:**

1. Create the themes directory:

```bash
mkdir ~/Library/Developer/Xcode/UserData/FontAndColorThemes
```

2. Move `Dracula.xccolortheme` or `Alucard.xccolortheme` to the themes folder.

**For all installation methods:**

1. Open _Xcode > Preferences > Themes_
2. Select Dracula Theme

**For Xcode 27+**

1. In the menu bar: `Xcode -> Settings -> Appearance -> Theme`;
2. Next to `Theme`, click **Choose**
3. Click **Import** on the bottom
4. Find and select the `Dracula.xccolortheme` or `Alucard.xccolortheme` files
5. Keep *Colors* and *Fonts* toggled **ON**
6. Click **Import**
7. Enjoy!

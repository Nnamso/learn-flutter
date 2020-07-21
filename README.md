# Learn-flutter
Documenting my learning process of flutter and the issues i faced in the process.(Mac user)
# Install Andriod studio 
https://developer.android.com/studio/install

# Configure you terminal 
From Bash to Zsh (some licencing reasons)

# Run this command should do that 
sh -c "$(curl -fsSL https://raw.githubusercontent.com/ohmyzsh/ohmyzsh/master/tools/install.sh)"

# Download Flutter 
Download the following installation bundle to get the latest stable release of the Flutter SDK:

https://flutter.dev/docs/get-started/install/macos

Extract the file in the desired location.

You can also get from git clone https://github.com/flutter/flutter.git


# Optionally, pre-download development binaries:
```zsh
flutter precache
```

Make sure you folder directory looks like this 

Untitled > Users > System name > developer > flutter 

```zsh
vim ~/.zshrc
```
i to insert

paste and edit path

# For macOS catalina
export PATH="$PATH:/Users/macbook/Developer/flutter/bin"

```zsh
:wq! for exit 
```

close your terminal before running flutter --version 

```zsh
flutter --version
```

Verify that the flutter/bin directory is now in your PATH by running:


```zsh
echo $PATH 
```

Verify that the flutter command is available by running:

```zsh
which flutter 
```

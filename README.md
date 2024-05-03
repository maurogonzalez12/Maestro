# Maestro

General steps
Install Maestro framework locally
For iOS, install Homebrew

/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"

Install Xcode - Xcode can be installed from the App Store.

https://developer.apple.com/xcode/

Install JDK

https://www.oracle.com/java/technologies/downloads/#jdk22-mac

For iOS, install the Facebook IDB tool:

brew tap facebook/fb

brew install facebook/fb/idb-companion

Install the Maestro CLI using the following command:

curl -Ls "https://get.maestro.Mobile.dev" | bash

After that run the following command

export PATH="$PATH":"$HOME/.maestro/bin"

To make sure it’s installed successfully you can check the version with the following command

maestro -v

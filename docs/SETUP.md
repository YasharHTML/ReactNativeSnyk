# React Native + snyk

See Introduction [here](./INTRO.md)

<hr>

## Prerequisites for Windows

### Android

<hr>

    Note: IOS can't be run or build in windows, Mac is required

1. Install node for Windows:

Install node [here](https://nodejs.org/en)

2. Install Android studio

Install android studio [here](https://developer.android.com/studio/index.html), and follow google's instructions

3. Set Env

   1. Open the Windows Control Panel.
   2. Click on User Accounts, then click User Accounts again
   3. Click on Change my environment variables
   4. Click on New... to create a new ANDROID_HOME user variable that points to the path to your Android SDK: `%LOCALAPPDATA%\Android\Sdk`

   5. Open the Windows Control Panel.
   6. Click on User Accounts, then click User Accounts again
   7. Click on Change my environment variables
   8. Select the Path variable.
   9. Click Edit.
   10. Click New and add the path to platform-tools to the list. `%LOCALAPPDATA%\Android\Sdk\platform-tools`

4. Reboot

## Prerequisites for Linux

### Android

<hr>

    Note: IOS can't be run or build in linux, Mac is required

1. Install node for Linux:

Install node for your own distro [here](https://nodejs.org/en/download/package-manager/)

2. Install Android studio

Install android studio [here](https://developer.android.com/studio/index.html), and follow google's instructions

3. Setup ENV

Append this to .bashrc

```bash
export ANDROID_HOME=$HOME/Android/Sdk
export PATH=$PATH:$ANDROID_HOME/emulator
export PATH=$PATH:$ANDROID_HOME/platform-tools
```

4. Reboot

## Prerequisites for Mac

### Android

<hr>

1. Install node and watchman:

```bash
brew install node
brew install watchman
```

2. Install jdk

```bash
brew install --cask zulu@17
brew info --cask zulu@17
```

3. Install Android studio

Install android studio [here](https://developer.android.com/studio/index.html), and follow google's instructions

Append this to .zshrc

```bash
export ANDROID_HOME=$HOME/Library/Android/sdk
export PATH=$PATH:$ANDROID_HOME/emulator
export PATH=$PATH:$ANDROID_HOME/platform-tools
```

## Prerequisites for Mac

### IOS

<hr>

1. Install node and watchman:

```bash
brew install node
brew install watchman
```

2. Install XCode

Install XCode from app store

3. Reboot
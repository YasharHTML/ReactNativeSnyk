# Report

See Introduction [here](./INTRO.md)
See Setup GUIDE [here](./SETUP.md)

<hr>

I have created React Native app named ReactNativeSnyk

```bash
npx react-native@latest init ReactNativeSnyk
```

Here is my project structure:
![Project Structure](./images/ProjectStructure.png 'Project Structure')

Now starting the application

```bash
npm run ios
```

I have the app ready:
![Metro And Emulator](./images/MetroAndEmulator.png 'Metro And Emulator')

Here hardcoded secrets are written and located by snyk:
![Bad Code](./images/BadCode.png 'Bad Code')

```bash
snyk code test
```

![Snyk Report](./images/SnykReport.png 'Snyk Report')

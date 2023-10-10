# LEIA Reactive Native app
## Follow instructions to install
- Follow this installation instructions: https://docs.expo.dev/get-started/installation/ (only the first time)
- Run on terminal: 
  - `cd leia`
  - `npm install`
  - `$env:NODE_ENV="development"` on Powershell to select development enviroment
  - or `NODE_ENV="development"` on Command Prompt
  - `npx expo start`
- or follow instructions on https://docs.expo.dev/get-started/create-a-new-app/ to run on emulator or any device on the same network as your pc.

## Important notes
- Universal Components style used: **NativeBase** - docs here: https://docs.nativebase.io/getting-started
- To build the app follow this instructions:
  - Download and install eas: https://docs.expo.dev/build/setup/
  - Run on terminal:
    - `npx eas build -p android --profile preview2` - this will generate a apk for android
  - More on this docs: https://docs.expo.dev/build-reference/apk/
- Build automatically every time a PR is merged on branch `main`. Verify `Actions` to see apk link.
- Using **React Navigation** to moving between screens - docs here: https://reactnavigation.org/docs/hello-react-navigation
- Using **Redux Toolkit** to manage global data - docs here: https://redux-toolkit.js.org/tutorials/quick-start
- Using **@expo/vector-icon** to icons: https://icons.expo.fyi/
# React Native Test

### Developing on Chromebook & debugging on a physical device
Unfortunately, you have to install the app on the device from a machine that has USB access (claims to be coming to ChromeOS end of 2018). Until then, the first install must be done from another machine 😩.

But then...
- from the project directory, `npm start` | `yarn start` | `react-native start` | `whatever`
- in another terminal, `./ngrok http 8081`
- from the app on the device, open the settings (shake device), click "dev settings"
- in "Debug server host & port for device", enter the ngrok address
- boom? 💥
- dance if you want to

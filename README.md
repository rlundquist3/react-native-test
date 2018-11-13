# React Native Test

### Developing on Chromebook & debugging on a physical device
Until you can access the device via USB (claims to be coming to ChromeOS end of 2018), the first install must be done from another machine 😩.

But then...
- from the project directory, `npm start` | `yarn start` | `react-native start` | `whatever`
- in another terminal, `./ngrok http 8081`
- from the app on the device, open the settings (shake device), click "dev settings"
- in "Debug server host & port for device", enter the ngrok address
- boom (in a good way) 💥
- dance if you want to

We'll see about hot reloading...

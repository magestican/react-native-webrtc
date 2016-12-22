## Do :

npm install

npm install -g react-native-cli



## Development workflow

After you have set up the project using above instructions, you can use your favorite IDE or text editor to write code, and run the application from the command line. Turn on React Native hot module reloading in the app developer menu to update your application as you code.

To learn how to structure your application and use the Redux application architecture, read the **[Architecture guide](docs/ARCHITECTURE.md)** for more details.

##### Start the application in iOS simulator
```
$ react-native run-ios
```

##### Start the application in Android simulator
(If using the stock emulator, the emulator must be running)
```
$ react-native run-android
```

##### Run unit tests
```
$ npm test
```

##### Run tests every time code changes
```
$ npm run test:watch
```

##### Generate code coverage report
```
$ npm run coverage
```

Read the **[Testing guide](docs/TESTING.md)** for more information about writing tests.

## Deployment

Read the **[Deployment guide](docs/DEPLOYMENT.md)** to learn how to deploy the application to test devices, app stores, and how to use Code Push to push updates to your users immediately.

## Contributing

If you find any problems, please [open an issue](https://github.com/futurice/pepperoni-app-kit/issues/new) or submit a fix as a pull request.

We welcome new features, but for large changes let's discuss first to make sure the changes can be accepted and integrated smoothly.

## License

[MIT License](LICENSE)

## Credits

This project was initially motivated by [Snowflake](https://github.com/bartonhammond/snowflake), a React Native boilerplate by Barton Hammond. It shares some features and design principles for Pepperoni, but it wasn't the right fit for our needs. At this time Snowflake is more mature, so if you like Pepperoni but didn't agree with something we are doing, you should check it out to see if it's a good fit for your app.

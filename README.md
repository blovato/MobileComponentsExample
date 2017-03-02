# Example App for SCA-Mobile-Components

## Development

1. install dependencies:

  `$ npm install`

2. link sca-mobile-components repo to test here:

    [using npm link](https://medium.com/@the1mills/how-to-test-your-npm-module-without-publishing-it-every-5-minutes-1c4cb4b369be#.a82sciofu)

    1. in the root of sca-mobile-components run:

        `$ npm link`

    2. then in this project root run:

        `$ npm link sca-mobile-components`

3. start react storybook:

  `$ npm run storybook`

4. start emulator or device:

  `$ react-native run-ios`

  and/or

  `$ react-native run-android`
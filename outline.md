# React Native Talk

## General Outline


### 1: Who
- You're a JS developer, familiar with web technologies (CSS, HTML, JS, etc) and you want to leverage this existing knowledge to build native apps
- You've at least built something small with React & ReactDOM

### 2: Options
- Web App (HTML/CSS/JS, jQuery Mobile)
- Hybrid (Cordova, Ionic, Sencha Touch, Phone Gap)
- Native (Swift, Java, Obj-C)

### 3: New Category
- React Native is a framework for creating **native** apps using **only JavaScript**.


### 4: What's in the box?
- RCTBridgeModule
- RN Components (and growing, watch for suffixes)
- `react-native-cli`


### Dependencies, getting set up
- node, watchman, xcode, android sdk
- get your hello-world app running on all wanted platforms first, then continue dev


### Outside the box, what to watch for
- troubleshooting
- 3rd party libs

### Worthwhile plugins/libraries
- deployments with Code Push
- react-router-native
- react-redux
- babel plugins & presets

### Dev, what you need to know

#### Styles
- Custom flexbox implementation
  - Flipped axis
- `import { StyleSheet } from 'react-native'`
  - `StyleSheet.create({ key: { prop: 'value' } })`

#### Platform Specific Code
- file extensions
- folders
- `Platform.select({ios: <FooIOS/>})` or `if(Platform.OS === 'ios')` etc

### Running on Device

#### iOS
- plug in

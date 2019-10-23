# react-native-twsqlite

## Getting started

`$ npm install react-native-twsqlite --save`

### Mostly automatic installation

`$ react-native link react-native-twsqlite`

### Manual installation


#### iOS

1. In XCode, in the project navigator, right click `Libraries` ➜ `Add Files to [your project's name]`
2. Go to `node_modules` ➜ `react-native-twsqlite` and add `Twsqlite.xcodeproj`
3. In XCode, in the project navigator, select your project. Add `libTwsqlite.a` to your project's `Build Phases` ➜ `Link Binary With Libraries`
4. Run your project (`Cmd+R`)<

#### Android

1. Open up `android/app/src/main/java/[...]/MainApplication.java`
  - Add `import com.reactlibrary.TwsqlitePackage;` to the imports at the top of the file
  - Add `new TwsqlitePackage()` to the list returned by the `getPackages()` method
2. Append the following lines to `android/settings.gradle`:
  	```
  	include ':react-native-twsqlite'
  	project(':react-native-twsqlite').projectDir = new File(rootProject.projectDir, 	'../node_modules/react-native-twsqlite/android')
  	```
3. Insert the following lines inside the dependencies block in `android/app/build.gradle`:
  	```
      compile project(':react-native-twsqlite')
  	```


## Usage
```javascript
import Twsqlite from 'react-native-twsqlite';

// TODO: What to do with the module?
Twsqlite;
```

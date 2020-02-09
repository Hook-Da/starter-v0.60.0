Version of react-native-cli 0.60.0

redux
react-redux
react-native-reanimated
react-native-gesture-handler@1.3.0
react-native-screens@^1.0.0-alpha.23
react-navigation
react-navigation-stack
react-native-vector-icons

node 12.3.0
npm 6.9.0

are installed

You can generate the debug keystore by running this command in the android/app/ directory: keytool -genkey -v -keystore debug.keystore -storepass android -alias androiddebugkey -keypass android -keyalg RSA -keysize 2048 -validity 10000

/*
* for android react-native-vector-icons
*/
Edit android/app/build.gradle ( NOT android/build.gradle ) and add the following:

apply from: "../../node_modules/react-native-vector-icons/fonts.gradle"

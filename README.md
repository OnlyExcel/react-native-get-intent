# react-native-get-intent

Get access to the Android Activity's intent - forked from https://github.com/jaslong/react-native-get-intent

# Compatibilty with @twilio/voice-react-native-sdk

The Twilio SDK injects a UUID into the intent bundle; this fork converts the UUID to a string before passing the bundle to the react bridge.
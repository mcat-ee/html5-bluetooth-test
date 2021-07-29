# html5-bluetooth-test
Testing the functionality of Bluetooth in web browsers (focused on Chrome compatibility currently)

# Caveats
1. Bluetooth functionality requires user interaction before it will execute (for example, a button could be pressed). The code will raise an exception if it is executed at the window level
2. Support for the Bluetooth API [isn't available across all browsers](https://developer.mozilla.org/en-US/docs/Web/API/Web_Bluetooth_API#browser_compatibility), and tends to require the toggling of an in-browser flag before it will be accessible 

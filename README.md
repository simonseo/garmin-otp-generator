# Garmin Watch OTP Generator widget
Simple OTP Generator widget for Garmin watches

User should be able to
1. Download the app from Garmin Express
1. Input their secret code & current counter through Garmin Connect/App itself
1. Use Garmin watch thereafter to generate OTPs
1. Choose one of multiple accounts (able to generate OTPs for multiple several occasions)
1. Developers should find it easy to port the same functionalities by changing a few resources

Use case: Generate OTP
1. Scroll through widget until otpGen widget shows up
1. Enter the widget
1. Scroll through list of accounts for which to generate OTP
1. Select account
1. New and unique OTP shows up
1. Exit widget

Use case: Add account on widget
1. Scroll through widget until otpGen widget shows up
1. Enter the widget
1. Scroll to top/bottom of list of accounts to find the "Add Account" option
1. Type in secret key and counter (This must be painful. Should be able to do the same on a computer/ConnectIQ program)

TODO:
- [ ] Learn Monkey C syntax
- [ ] Create HMAC library / Find Crypto Monkey Barrel
- [ ] Make data stucture/DB to save secret keys and counter that can safely store keys (only able to write, never read)
- [ ] See if there is a HSM (hardware security module) on a Garmin watch
- [ ] Make identifiable logo for widget face


[Garmin Developer Reference](https://developer.garmin.com/connect-iq/programmers-guide/getting-started/)

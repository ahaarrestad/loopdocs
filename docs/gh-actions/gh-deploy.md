## Deploy Using TestFlight

This is only available with Loop 3 and Loop dev branch.

**You must build Loop every 90 days when you use this method.**

After successfully building Loop using Actions in github, here are two important things to know. The next statements might not make sense to you if you have not gone to the link above and reviewed the instructions.

1. Once you have installed TestFlight on your phone and you see your app in the TestFlight screen, tap on it to see an expanded screen with an option to automatically update or not.  You should choose which you prefer. If you do not turn it off, the app will automatically update whenever a new Build action completes in your github fork.

1. The Apple ID used to sign in for TestFlight on a given phone does not have to match the Apple ID of the phone user. This is important for children. [Loopers Need Their Own Apple ID](../build/step6.md#loopers-need-their-own-apple-id), but children cannot use TestFlight with their ID. If you plan to [Install Loop for Child](#install-loop-for-child), you will need to use your ID on their phone (not the whole phone - just the Media & Purchase portion), so send the TestFlight invitation to the email associated with your ID.

### Install Loop for Child

The adult (Apple Developer Account owner) can log into Media & Purchase (see steps below) without affecting the child Apple ID associated with a phone (and thus their health records used by Loop). After the adult installs or updates Loop using TestFlight, they probably should reverse those steps to remove their credentials from Media & Purchase.

Media & Purchase affects access to the App Store, Books, Music and Podcasts.

On the Looper's phone:

* Tap on Settings
* At the very top of Settings, tap on the Name of the phone, for example, `my kids phone`
* Apple ID Screen appears
    * Tap on Media & Purchases
    * Tap on Sign Out, and confirm
    * Reboot the phone
* After phone reboots, repeat the process and sign in with the adult (Apple Developer Account owner) Apple ID and password
* Install or Update Loop from TestFlight on child's phone
* Repeat the process to sign out the adult and (if needed) sign back in the child


# feed-pusher-android
Realtime feed Android app using Pusher. This is meant to be used with the project https://github.com/eh3rrera/node-api-pusher as the back-end.

You can follow the [tutorial](https://blog.pusher.com) to build this application or jump straight to the code.

# Requirements

- [A free Pusher account](https://pusher.com)
- [Android Studio](https://developer.android.com/studio/index.html)
- MinSdkVersion: 15
- TargetSdkVersion: 25

# Installation
1. Create an app on Pusher and copy your app key.
2. Start the server at https://github.com/eh3rrera/node-api-pusher.
3. Clone this repository and open it with Android Studio.
4. Open the file `app/src/main/java/com/pusher/feed/MainActivity.java` and enter your Pusher app key in the line `private Pusher pusher = new Pusher("ENTER_PUSHER_APP_KEY_HERE");`
5. Build the project and run it.
6. Start sending POST/PUT/DELETE requests to the server.  The app will show the events published.

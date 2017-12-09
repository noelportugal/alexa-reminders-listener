# alexa-reminders-listener

This is an example of using [https://github.com/noelportugal/alexa-reminders](https://github.com/noelportugal/alexa-reminders) as a listener.

#### Listener
Modify index.js to include your device name, username and password.


```sh
$ git clone https://github.com/noelportugal/alexa-reminders-listener
$ cd alexa-reminders-listener
$ npm install
$ node index.js
External endpoint:
 curl -X POST -d "reminder=Ask Alexa team for a proper Reminders API" https://xxxxxx.ngrok.io/alexa-reminders
Internal endpoint:
 curl -X POST -d "reminder=Ask Alexa team for a proper Reminders API" http://localhost:8091/alexa-reminders
Logged in

```

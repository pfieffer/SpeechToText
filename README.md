# SpeechToText
> Does exactly speech to text and nothing else. Speech To Text in the most simple way possible. 


## Test this app

1.  Download zip **or** Clone this repository:  Type  `git clone git@github.com:pfieffer/SpeechToText.git`(SSH) or `git clone https://github.com/pfieffer/SpeechToText.git`(HTTPS)
2. Open the project in your Android Studio(3.0.+ and gradle 4.+ recommended). Build and Run.

#### But what does the app do?
It starts the `android.speech.RecognizerIntent`; in simple words the google's dialog box type of thing to take voice input. The voice is passed to the `onActivityResult` callback where we can get an `ArrayList` of String from the `RecognizerIntent`.

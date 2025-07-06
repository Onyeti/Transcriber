SETUP INSTRUCTIONS

1)    Clone the Repository

2)    Open the ‘Transcriber’ project in Xcode 15 or newer


3)    Configure app permissions:

        Key -NSMicrophoneUsageDescription
        String - This app needs access to your microphone to record audio.

        Key - NSSpeechRecognitionUsageDescription
        String - This app requires speech recognition access to record and transcribe audio.

4)    Build and run from the ‘ContentView’ page (via: Transcriber -> ContentView)


----App Features----

Large mic button for starting and pausing recordings.
Play, pause, and stop controls with animated icons.
Full transcription of recorded audio using Apple’s Speech framework.
Chunked transcription for long recordings to avoid API failures.
Saved sessions with timestamped history.
Built-in search bar to find sessions by transcript content.
SwiftData-based persistent storage.
Recording confirmation popup when recording ends.
Export/share functionality

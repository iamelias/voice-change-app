VoiceChangeApp, iOS Developer: Elias Hall
File Name: PitchPerfect

Overview: The VoiceChaneApp records users voice and plays it back with user chosen sound effect. App uses AVAudioRecorder from AVFoundation

RecordSoundsViewController: This view controller contains 2 buttons. A recording button and a finished recording button. User taps on the record button, speaks, then taps on the stop recording button. User is then automatically segued to the PlaySoundsViewController. 

PlaySoundsViewController: This view controller contains 6 buttons each with its own sound effect. User taps the button to hear there recorded voice played back with button's sound effect. The playback options are: fast, slow, chipmunk, Darth Vader, echo, and reverb. Stop button force-stops the playback.  User can select back in nav bar to return to the recording screen where they can repeat record-playback process.

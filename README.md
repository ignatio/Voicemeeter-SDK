# Voicemeeter-SDK - Ignatio's Personal Version

Hey I forked this and edited a few things to fit better with the way my environment looks. I changed the colour sceheme to match what I like and also added the abillity for the strips to have an inactive colour when not in use, which the current shipping version seems to have but the example didn't. 

![image](https://user-images.githubusercontent.com/721547/202579651-98900e7b-3551-43d5-9b4b-245de53e8c4e.png)

*Original ReadMe below...

Voicemeeter Remote API + Source Code Examples

Voicemeeter Remote API provides a set of functions to control Voicemeeter parameters,  to process audio inside Voicemeeter, to get MIDI messages coming from the Voicemeeter MIDI-Mapping and to control the MacroButtons application. Voicemeeter SDK offers different source code example. example0 is expected to show every functionnalties while other projects are concrete application examples:

- Matrix8x8: example of Audio Processing Application offering a 8x8 gain matrix on a selected BUS.
- vmr_osd: Exemple of Overlay Screen Display Application to show the current gain of the current moving slider.
- vmr_play: example to use voicemeeter as audio board to playback a stereo sound.
- vmr_streamer: example of custom Graphic User Interface controlling Voicemeeter.

# Compilation Instructions and Documentation
Voicemeeter API are provided by standard Windows DLL installed with Voicemeeter. It provides 2x DLL for x32 and x64 applications. Linking method is given in the source code example. Compilation instructions are given in source code header and all API specifications are in the PDF document.

# Licensing
All source code of this SDK is free to use in any kind of project interacting with Voicemeeter through the voicemeeterremote DLL or VBAN protocol. More details in VoicemeeterRemoteAPI.pdf

Copyright (c) 2021 Vincent Burel

# Links
Download Voicemeeter: www.voicemeeter.com
VBAN Protocol: https://vb-audio.com/Voicemeeter/vban.htm
VB-Audio Support page: https://vb-audio.com/Services/support.htm

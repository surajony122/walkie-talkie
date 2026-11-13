# 📻 Team Walkie-Talkie

Push-to-talk voice for a small team (2–8 people), running entirely in the browser.
Voice goes directly between devices over WebRTC; the free PeerJS cloud server only introduces people to each other.

## Use it
1. Open **https://surajony122.github.io/walkie-talkie/?room=YOUR-CHANNEL**
2. Enter your name, allow the microphone.
3. Hold the big button (or Spacebar on a laptop) to talk.

Everyone who opens the same `?room=` link is on the same channel.

## Notes
- The channel name acts like a password — pick something unique.
- Keep the page open with the screen on (browsers stop the mic on a locked phone). On Android, use *Add to Home screen*.
- Some strict networks block direct connections; a TURN relay can be added if someone can't hear anyone.

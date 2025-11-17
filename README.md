## Projects
### Earbrowsing, 2025
An attempt at developing a new type of screen reader interaction based on audio with spatial cues. It consists of a mini game where you have to find buttons, on a screen and double clic on them. The catch: you are blind and you can only use sound to find where the button are. Move your mouse around the screen to hear the buttons that are close to your mouse.
#### How does it work ?
- use a headset, you need **stereo**
- clic [here](https://nathanaelambert.github.io/nthlmb/earbrowsing/AudioSpace.html) to access the prototype
- press start
- **close your eyes**
- use **clic** + **drag** to move in the virtual space
- **double clic** to select the element
#### Why did I make this ?
This prototype is a theoretical feature that could be added to a screen reader, to improve accessibility of the web for blind users. The issue with current screen readers is that they are only efficient if the user knows the specific layout of the website/app that they are using. The idea with this project was to allow spatial exploration of a screen through sound. It is inspired by directional sounds in video game. Watch. [this video](https://youtu.be/sBLmSlFco9A) to get an example of how it could be used.
#### What did I learn from this project ?
Directional sound is a technical challenge. My solution with a basic stereo headset, and the sound library Tone.js is not precise enough for this usecase.
